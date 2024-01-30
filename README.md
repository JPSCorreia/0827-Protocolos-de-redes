
# Exercicios

## exer 1

### 192.168.100.0/24 necessidade de 2 redes com 60 endereços, ip 192.168.100.0 com subnet mask 24

passar para /26
net1:
id - 192.168.100.0 | intervalo ips 192.168.100.1 - 192.168.100.62  | broadcast 192.168.100.63 | SM 255.255.255.192
net2:
192.168.100.64 | intervalo ips 192.168.100.65 - 192.168.100.126  | broadcast 192.168.100.127 | SM 255.255.255.192
net3:
192.168.100.128 | intervalo ips 192.168.100.129 - 192.168.100.190  | broadcast 192.168.100.191 | SM 255.255.255.192
net4:
192.168.100.192 | intervalo ips 192.168.100.193 - 192.168.100.254  | broadcast 192.168.100.255 | SM 255.255.255.192

escolher 2 destas

## exer2

172.16.12.0/24 necessidade de 4 redes com 50 endereços
172.16.12.0 com subnet mask 24

passar para /26
net1
id - 172.16.12.0 | intervalo ips 172.16.12.1 - 172.16.12.52  | broadcast 172.16.12.53 | SM 255.255.255.192
net2:
172.16.12.54 | intervalo ips 172.16.12.55 - 172.16.12.106  | broadcast 172.16.12.107 | SM 255.255.255.192
net3:
172.16.12.108 | intervalo ips 172.16.12.109 - 172.16.12.160  | broadcast 172.16.12.161 | SM 255.255.255.192
net4:
172.16.12.192 | intervalo ips 172.16.12.193 - 172.16.12.254  | broadcast 172.16.12.255 | SM 255.255.255.192

escolher 2 destas

### exer3

10.10.10.0/24 necessidade de 6 redes com 10 endereços
10.10.10.0 com subnet mask 24

passar para /28
net1:
id - 10.10.10.0 | intervalo ips 10.10.10.1 - 10.10.10.11  | broadcast 10.10.10.12 | SM 255.255.255.240
net2:
10.10.10.13 | intervalo ips 10.10.10.14 - 10.10.10.25  | broadcast 10.10.10.26 | SM 255.255.255.240
net3:
10.10.10.27 | intervalo ips 10.10.10.28 - 10.10.10.39  | broadcast 10.10.10.40 | SM 255.255.255.240
net4:
10.10.10.41 | intervalo ips 10.10.10.42 - 10.10.10.53  | broadcast 10.10.10.54 | SM 255.255.255.240
net5:
10.10.10.55 | intervalo ips 10.10.10.56 - 10.10.10.67  | broadcast 10.10.10.68 | SM 255.255.255.240
net6:
10.10.10.69 | intervalo ips 10.10.10.70 - 10.10.10.81  | broadcast 10.10.10.82 | SM 255.255.255.240

### exer4

192.168.30.128/25 necessidade de 2 redes com 50 endereços
192.168.30.128 com subnet mask 25

passar para /26
net1:
192.168.30.128 | intervalo ips 192.168.30.129 - 192.168.30.180 | broadcast 192.168.30.181 | SB 255.255.255.192
net2:
192.168.30.182 | intervalo ips 192.168.30.183 - 192.168.30.234 | broadcast 192.168.30.235 | SB 255.255.255.192

### exer5

Rede: 192.168.10.0
Máscaras:
1 – 255.255.255.128/25
2 – 255.255.255.192/26
3 – 255.255.255.224/27
4 – 255.255.255.240/28
5 – 255.255.255.248/29
6 – 255.255.255.252/30

1: 2 nets
1ª net: id 192.168.10.0, intervalo ips 192.168.10.1 - 192.168.10.126, broadcast 192.168.10.127
2ª net: id 192.168.10.128, intervalo ips 192.168.10.129 - 192.168.10.254, broadcast 192.168.10.255

2: 4 nets
1ª net: id 192.168.10.0, intervalo ips 192.168.10.1 - 192.168.10.62, broadcast 192.168.10.63
2ª net: id 192.168.10.64, intervalo ips 192.168.10.65 - 192.168.10.126, broadcast 192.168.10.127
3ª net: id 192.168.10.128, intervalo ips 192.168.10.129 - 192.168.10.190, broadcast 192.168.10.191
4ª net: id 192.168.10.192, intervalo ips 192.168.10.193 - 192.168.10.253, broadcast 192.168.10.255

3: 8 nets
1ª net: id 192.168.10.0, intervalo ips 192.168.10.1 - 192.168.10.30, broadcast 192.168.10.31
2ª net: id 192.168.10.32, intervalo ips 192.168.10.31 - 192.168.10.62, broadcast 192.168.10.63
3ª net: id 192.168.10.64, intervalo ips 192.168.10.63 - 192.168.10.94, broadcast 192.168.10.95
4ª net: id 192.168.10.96, intervalo ips 192.168.10.97 - 192.168.10.126, broadcast 192.168.10.127
5ª ...

4: 16 nets

1ª net: id 192.168.10.0, intervalo ips 192.168.10.1 - 192.168.10.14, broadcast 192.168.10.15
2ª net: id 192.168.10.16, intervalo ips 192.168.10.17 - 192.168.10.30, broadcast 192.168.10.31
3ª net: id 192.168.10.32, intervalo ips 192.168.10.33 - 192.168.10.46, broadcast 192.168.10.47
4ª net: id 192.168.10.48, intervalo ips 192.168.10.49 - 192.168.10.62, broadcast 192.168.10.63
5ª ...

5: 32 nets
1ª net: id 192.168.10.0, intervalo ips 192.168.10.1 - 192.168.10.6, broadcast 192.168.10.7
2ª net: id 192.168.10.8, intervalo ips 192.168.10.9 - 192.168.10.14, broadcast 192.168.10.15
3ª net: id 192.168.10.16, intervalo ips 192.168.10.17 - 192.168.10.22, broadcast 192.168.10.23
4ª net: id 192.168.10.24, intervalo ips 192.168.10.25 - 192.168.10.30, broadcast 192.168.10.31
5ª ...

6: 64 nets
1ª net: id 192.168.10.0, intervalo ips 192.168.10.1 - 192.168.10.2, broadcast 192.168.10.3
2ª net: id 192.168.10.4, intervalo ips 192.168.10.5 - 192.168.10.6, broadcast 192.168.10.7
3ª net: id 192.168.10.8, intervalo ips 192.168.10.9 - 192.168.10.10, broadcast 192.168.10.11
4ª net: id 192.168.10.12, intervalo ips 192.168.10.13 - 192.168.10.14, broadcast 192.168.10.15
5ª ...
