<h1 align="center">TRABALHO FINAL SSROC</h1>
<h2 align="center">CONFIGURAÇÕES DE CACHE NO SQUID</h2>

<p align="center">
<b>Repositório Utilizado Somenete Para a Aplicação da Atividade Do Projeto Final da Cadeira de Segurança em Sietemas Operacionais e Redes de Computadores!</b>
</p>

<h2>Objetivo Da Atividade</h2>
O objetivo desta atividade é que você configure o Squid para ajustar o tamanho do cache, configure a limpeza automática dos arquivos antigos e personalize outros parâmetros de cache para melhorar o desempenho e a eficiência do servidor proxy.

<h2>Materiais</h2>

Para a realização dessa atividade, será necessário alguns pré-requisitos:

- Ter Visturalizado de Sistemas Operacionasi VirtualBox
    - [VirtualBox](https://www.virtualbox.org/wiki/Downloads)
- O Sistema Operacaional Linux Debian
    - [debian-12.9.0-amd64-netins](https://cdimage.debian.org/debian-cd/current/amd64/iso-cd/debian-12.9.0-amd64-netinst.iso)

<h2>Métodos</h2>
Apara realização dessa atividade é essencial a instalação de alguns programas na sua máquina Debian.

<h4>Instalação do Proxy Squid</h4>

```bash
sudo apt update && sudo apt install squid -y
```
Após a instalação, verificar status do serviços:

```bash
sudo systemctl status squid
```

<h4>Instalação da Ferramenta curl</h4>

```bash
sudo apt install curl
```
_ferramenta de linha de comando usada para transferir dados entre um cliente e um servidor usando diversos protocolos, como HTTP, HTTPS, FTP, SCP, LDAP, e muitos outros_

<h4>Instalação da Ferramenta squidclient</h4>

```bash
sudo apt install squidclient
```

_ferramenta usada para interagir com um servidor Squid Proxy. Ele permite que você envie requisições HTTP através do Squid, obtenha estatísticas e depure sua configuração de proxy._

<h2>DESENVOLVIMENTO DA ATIVIDADE</h2>

<h3>Passo 1: Configurar Cache</h3>
<h4>Agora vamos configurar o cache no squid</h4>

- Abra em seu terminal o arquivo do squid

```bash
sudo nano /etc/squid/squid.conf
```

<h2 id="contribute">Contribute 🚀</h2>

If you want to contribute, clone this repo, create your work branch and get your hands dirty!

```bash
git clone https://github.com/Fernanda-Kipper/Readme-Templates.git
```

```bash
git checkout -b feature/NAME
```




