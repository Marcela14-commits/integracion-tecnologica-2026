# Taller Linux – Usuarios, Grupos y Permisos

## ¿Qué es un usuario?

Un usuario en Linux es una cuenta que permite a una persona acceder al sistema. 
Cada usuario tiene un nombre, contraseña y permisos específicos.

Ejemplo:
sudo useradd -m dev1


## ¿Qué es un grupo?

Un grupo es un conjunto de usuarios que comparten permisos sobre archivos o directorios.

Ejemplo:
sudo groupadd developers


## ¿Cómo funciona chmod?

El comando chmod permite cambiar los permisos de un archivo o directorio.

Ejemplo:
sudo chmod 755 development


## ¿Qué significa 755?

755 significa:

7 → Propietario: lectura (r), escritura (w), ejecución (x)
5 → Grupo: lectura (r), ejecución (x)
5 → Otros: lectura (r), ejecución (x)

## ¿Qué hace chown?

El comando chown cambia el propietario o el grupo de un archivo o directorio.

Ejemplo:
sudo chown :developers development

## Creación de usuario

sudo useradd -m dev1
sudo passwd dev1


## Creación de grupo

sudo groupadd developers


## Cambio de permisos

sudo chmod 755 development
sudo chmod 770 support
