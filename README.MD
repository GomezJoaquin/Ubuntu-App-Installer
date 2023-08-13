# Configuración Personal para Instalar Aplicaciones en Ubuntu

Este playbook simplifica la instalación de las aplicaciones que utilizo regularmente en mi sistema Ubuntu. 
Utilizando Ansible, puedes automatizar la instalación de estas aplicaciones con facilidad.

## Requisitos

- Ubuntu versión 23.04 (probado)

## Instrucciones

1. Clona este repositorio en tu sistema local.

2. Abre una terminal y navega hasta el directorio donde clonaste este repositorio.

3. Ejecuta el siguiente comando para comenzar la instalación de las aplicaciones:

   ```bash
   sudo ansible-playbook -i hosts.yml install_apps.yml -k
   ```
   Asegúrate de estar en el mismo directorio que el archivo playbook.yml.

4. Sigue las instrucciones y espera a que Ansible complete el proceso de instalación.

## Aplicaciones Incluidas

* Visual Studio Code
* Docker
* Wireshark
* Traceroute
* Java 8
* Postman
* npm
* Ansible
* SQLite
* GParted
* Remmina
* Meld
* Nmap
