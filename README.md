# Project Pi-hole

![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
Estou rodando dentro de um docker-compose.yml 4 containers: Pi-Hole, Pi-hole-exporter (faz a exportação das métricas para o Prometheus), Prometheus e o Grafana

# Painel do Pi-Hole

![Pi-Hole](https://img.shields.io/badge/pihole-%2396060C.svg?style=for-the-badge&logo=pi-hole&logoColor=white)
Pi-hole é um aplicativo para bloqueio de anúncios e rastreadores na Internet que atua como um serviço de DNS

![Raspberry Pi](https://img.shields.io/badge/-RaspberryPi-C51A4A?style=for-the-badge&logo=Raspberry-Pi)
O atual projeto foi criado em um Raspberry Pi 2w.
Também foi adicionado nas configurações do roteador o IP do Servidor DNS, logo todo o tráfego feito pelos meus dispositivos conectados irão passar primeiro pelo servidor, deixando a internet sem ADS e mais limpa.
![](https://github.com/luizhpferreira/blacklist-meu/blob/main/dns.png?raw=true)




# Painel do Grafana
![Grafana](https://img.shields.io/badge/grafana-%23F46800.svg?style=for-the-badge&logo=grafana&logoColor=white)
![Grafana](https://github.com/luizhpferreira/pi-hole/blob/main/images/grafana-pi-hole.png)

Pré-requisitos 📋
Você só precisa ter o serviço Pi-Hole instalado, consulte o site oficil para mais detalhes.

https://pi-hole.net
