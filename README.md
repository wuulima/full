<<<<<<< HEAD

```bash
sudo adduser vespertineweb
sudo usermod -aG sudo vespertineweb
sudo su vespertineweb
```

Instalação das bibliotecas

```bash
sudo apt -y update && apt -y upgrade
```

DOWNLOAD DO INSTALADOR & INICIANDO A PRIMEIRA INSTALAÇÃO:

```bash
sudo apt install -y git && git clone https://github.com/VespertineWeb/FullInstaller.git && sudo chmod -R 777 FullInstaller && cd FullInstaller && sudo ./install_primaria
```

SEGUNDA OU MAIS INSTALAÇÕES:
```bash
=======
DOWNLOAD DO INSTALADOR & INICIANDO A PRIMEIRA INSTALAÇÃO:

```bash
sudo apt install -y git && git clone https://github.com/VespertineWeb/FullInstaller.git && sudo chmod -R 777 FullInstaller && cd FullInstaller && sudo ./install_primaria
```

SEGUNDA OU MAIS INSTALAÇÕES:
```bash
>>>>>>> c4ffebb476860f1b13a44aa179375465cf8f5858
cd ./FullInstaller && sudo ./install_instancia
```

