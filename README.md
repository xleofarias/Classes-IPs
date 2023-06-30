# Classes-IPs

255 = Rede
0 = Host(maquina)

- A classe A:
  - Com o intervalo de octeto de 1 - 126 e a máscara de rede é 255.0.0.0.

- O endereço 127.0.0.1 seria uma faixa de endereço IP reservada, esse seria um endereço interno da placa de rede para realizar testes e verificar se ela está de fato validando os protocolos TCP/IP.

- A classe B:
  -  Com o intervalo de octeto de 128 - 191 e a máscara de rede é 255.255.0.0.
- A classe C:
  - Com o intervalo de octeto de 192 - 223 e a máscara de rede é 255.255.255.0.
- A classe D:
  - Com o intervalo de octeto de 224 - 239 elas não tem máscara de rede já que são reservadas, não são utilizadas para ip de maquinas e utilizadas para multicast(casos em que queremos fazer a comunicação somente com alguns dispositivos que estão na nossa rede). 
- A classe E:
  - Com o intervalo de octeto de 240 - 255 elas não tem máscara de rede já que são reservadas, não são utilizadas para ip de maquinas e utilizadas para multicast(casos em que queremos fazer a comunicação somente com alguns dispositivos que estão na nossa rede).

# Intervalos de IP Privados:
- Dentro de cada um dos intervalos de IP, teremos faixas que são chamadas de privadas. Elas recebem esse nome, porque só podemos nos comunicar na rede local, não podendo ser utilizados na comunicação na internet.
  - Classe A do IP privado 10.x.x.x
  - Classe B do IP privado 172.16.x.x - 172.31.x.x
  - Classe C do IP privado 192.168.x.x

- O roteador faz a tradução do endereço que aparece no Prompt para o que vemos em um site que fala nosso ip. Isto é feito por meio do método NAT (Network Address Translation), em que é feita a tradução de um endereço privado para o público.

 
