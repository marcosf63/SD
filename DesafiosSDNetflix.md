# Desafios de Sistemas Distribuídos

## Apresentação
Marcos Antônio Fernandes de Oliveira

marcosf63@gmail.com

##
![Netflix](img/netflix.png)

## Heterogeneidade
* Roda em PCs, Android, iPhone, PS4, Tvs
    * Frontend feita em React (Framework Javascript)
    * Certificação de dispositivos
    * SDK que faz o build para a plataforma específica
    * SDK utiliza dados da certificação de dispositivos
    * Parte da SDK é também distribuída para os fabricantes
    * SDK não é open source

## Sistemas Abertos
* Netflix Open Source Software Center
* http://netflix.github.io
* BigData, Buid and Delivery Tools
* Content Encoding, Segurança
* Disponível em container Docker

## Segurança
* Securitiy Monkey
* Netflix Open Conect
* Instâncias distribuídas em diferentes zonas do AWS

## Escalabidade e Concorrêcia
* Dezenas de milhares instâncias de VMs na AWS
* CPU 4 cores 30GB HD
* Criadas e removidas constantemente
* Milhares nodes NoSQL Cassandra

## Tratamento de falhas
* Chaos Engineering
* Chaos Monkey

## Fontes
* [https://medium.com/netflix-techblog](https://medium.com/netflix-techblog)
* [http://netflix.github.io](http://netflix.github.io)
* [https://www.slideshare.net/adrianco](https://www.slideshare.net/adrianco)
* [https://www.slideshare.net/netflix](https://www.slideshare.net/netflix)
* [https://principlesofchaos.org](https://principlesofchaos.org)
* [https://github.com/marcosf63/SD](https://github.com/marcosf63/SD)
