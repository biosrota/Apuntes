## Tutorial debian

### Activar sudo:

```sh
su
apt-get install sudo
sudo adduser nombre_usuario sudo
```

### Actualizar debian

```sh
sudo apt-get update && sudo apt-get upgrade && sudo apt-get dist-upgrade && sudo apt-get autoremove
```

### Instalar instalador grafico de paquetes debian

```sh
sudo apt-get install gdebi
```
### unstalar aplicaciones

```sh
sudo apt-get install htop
sudo apt-get install libreoffice
sudo apt-get install transmission-gtk
```
equivale a:

```sh
sudo apt-get install transmission-gtk htop libreoffice
```
### Ejecutar *scrips*

 ```sh
 bash nombre_scrips.sh
 ```
