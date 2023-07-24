# Instalação Servidor Pentaho Community em Container Proxmox com Ubuntu 20.04

## Instale o Ubuntu 20.04 em um novo container em PROXMOX a partir do template.


> 1. Após instalado o ubuntu 20.04 no container novo, atualize o mesmo.

```txt

sudo apt update
sudo apt upgrade


```
---

> 2. Instale o pacote de rede do ubuntu

```txt

apt install net-tools

```

---

> 3. Instale as dependências necessárias para o Pentaho Community Edition: 

```txt

sudo apt install default-jre unzip

```

---

> 4. Baixe o arquivo zip do Pentaho Community Edition: A fonte para esse donwload esta em https://www.hitachivantara.com/en-us/products/pentaho-platform/data-integration-analytics/pentaho-community-edition.html, sempre verificar se mudou a versão para o download.

```txt

wget https://privatefilesbucket-community-edition.s3.us-west-2.amazonaws.com/9.4.0.0-343/ce/server/pentaho-server-ce-9.4.0.0-343.zip


```