# Criando um jogo com Python e Pygame
Vamos criar um Shoot 'em up de nave utilizando o python e a biblioteca pygame.

## Pré-requisitos
* Python 3.8 (provavelmente vai funcionar em algumas versões anteriores, mas com só teste nessa)
* Editor de código Python preferido (aqui eu uso o Visual Studio da Microsoft)
* Linux Ubuntu (Ou derivado Debian, teoricamente também funciona no Windows, mas como não uso ele, não tenho como testar)

## Instalando os pré-requisitos do Pygame
Vamos instalar no sistema base algumas bibliotecas e requisitos para rodar o pygame.

```shell
$ sudo apt-get update
$ sudo apt-get install git python3-dev python3-setuptools python3-numpy python3-opengl libsdl-image1.2-dev libsdl-mixer1.2-dev libsdl-ttf2.0-dev libsmpeg-dev libsdl1.2-dev libportmidi-dev libswscale-dev libavformat-dev libavcodec-dev libtiff5-dev libx11-6 libx11-dev fluid-soundfont-gm timgm6mb-soundfont xfonts-base xfonts-100dpi xfonts-75dpi xfonts-cyrillic fontconfig fonts-freefont-ttf libfreetype6-dev
```

## Criando um ambiente virtual python
Ambientes virtuais são uma forma de criar um ambiente local, que pode ter todas as suas dependências e requisitos instalados, sem afetar o sistema operacional que está rodando na maquina, mesmo que um utilize versões diferentes e incompatíveis entre elas é uma forma muito boa de trabalhar dentro do desenvolvimento python.

Para criar um virtual env com python utilize o comando abaixo:

```shell
$ mkdir nome_projeto
$ cd nome_projeto
$ python -m venv env
```
Para ativar o virtualenv utilize o comando abaixo:
```shell
$ source env/bin/activate
(env) william@william-Note:~/Projetos/PySpace$
```

Para desativar o virtualenv utilize o comando abaixo:
```shell
$ deactivate
william@william-Note:~/Projetos/PySpace$
```

## Instalando o Pygame
Agora vamos instalar o pygame dentro do nosso ambiente virtual. Lembre-se de ativa-lo antes.
Dentro da pasta do projeto, digite o comando abaixo para ativar o ambiente.
```shell
$ source env/bin/activate
(env) william@william-Note:~/Projetos/PySpace$
```
Agora vamos instalar o pygame
```shell
$ pip install pygame
```