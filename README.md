# Infraestutura para Sistemas Web


## Instalação do Servidor Apache2

![asdf](oi.jpeg)

Para instalar o apache 2 digite a seguinte linha linha de comando 

`apt update
`

`
aptitude install apache2
`

## Os arquivos de configuração se encontram no diretório

`
/etc/apache2/
`
## Ajustando o Firewall (caso necessario)
Para verificar os perfis de aplicativos disponíveis com ufw

`  
ufw app list
`  
`  
ufw allow apache2
` 

## verificando alteraçes

`
ufw status
`

## Verificando se o serviço do apache esta em perfeito funcionamento(Active (Running))

`  
service apache2 status 
ou

systemctl status apache2
`  
## Atribua as permisses a propriedade do diretorio
`
chown -R $USER:$USER /var/www/`
`
chmod 777 -R /var/www/
`

## logo apos copie o projeto para o diretorio /var/www/html
logo apos as configurações digite no terminal 
`  
servide apache2 restart
`  

## Para adicionar um arquivo html ao servidor utilize o caminho 
` /var/www/html
`

abra o navegador 

digite na barra de endereço: 

localhost

![asdf](apache.png)

seu servidor apache esta configurado corretamente !

> Maycon Douglas Oliveira da Silva

