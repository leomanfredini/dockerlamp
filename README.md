#Docker LAMP

###INSTALL DOCKER

`sudo apt-get update`

`sudo apt-get -y install apt-transport-https ca-certificates curl software-properties-common gnupg2`
UBUNTU
`curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -`

`echo -e "\ndeb [arch=amd64] https://download.docker.com/linux/ubuntu bionic stable" | sudo tee -a /etc/apt/sources.list`


DEBIAN

`curl -fsSL https://download.docker.com/linux/debian/gpg | sudo apt-key add -`

`add-apt-repository \
“deb [arch=amd64] https://download.docker.com/linux/debian \
$(lsb_release -cs) \
stable”`


`sudo apt-get update`

`sudo apt-get -y  install docker-ce docker-compose`

`sudo usermod -aG docker $USER`


------------


###DOCKER COMMANDS

Start and build containers
`$ docker-compose up --build`


Start containers
`$ docker-compose up -d`


Stop Containers
`$ docker-compose down`


Delete all containers
`$ docker system prune -a`


------------


###LINKS DE REFERÊNCIA

https://computingforgeeks.com/install-docker-and-docker-compose-on-linux-mint-19/

https://gist.github.com/sethbergman/9ef9d14aef86ba7705791785ed377f69

https://www.hiroom2.com/2018/08/06/linuxmint-19-docker-en/

https://www.digitalocean.com/community/tutorials/how-to-remove-docker-images-containers-and-volumes

https://medium.com/jundevelopers/ambiente-de-desenvolvimento-php-com-docker-parte-1-ide-php-banco-de-dados-9459a147073c

https://medium.com/@danilolutz/ambiente-de-desenvolvimento-php-com-docker-parte-2-qualidade-de-c%C3%B3digo-git-4ca9c5cbfc6c

https://onebitcode.com/o-que-e-e-como-funciona-o-rancher/

https://www.mundodocker.com.br/racheros-painel-docker/
