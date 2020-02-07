# Infra Estutura para Sistemas Web
##Instalação do Servidor Apache2
![asdf](oi.jpg)
Para instalar o apache 2 digite a seguinte linha linha de comando 
apt update
aptitude install apache2
##Ajustando o Firewall (caso necessario)
ufw app list
ufw allow apache2
##verificando alteraçes
ufw status
##Verificando se o serviço do apache esta em perfeito funcionamento(Active (Running))
service apache2 status ou systemctl status apache2



