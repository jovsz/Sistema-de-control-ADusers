# Sistema-de-control-ADusers

Esta Aplicacion esta especialmente desarrollada para la administracion de Usuarios de Dominio 0Windows Server
Active Directory.

Una de sus principales funciones es poder general altas y modificaciones con los usuarios de dominio ya sea la creacion,
modificion y desbloqueo de usuarios dentro del mismo dominio.

Esta aplicacion fue desarrollado principalmente con NodeJs, y algunas librerias como express, passport,fs, pathFile, entre otros >
para poder hacer ejecutar esta aplicacion en una nueva instancia, sera necesario aplicar la ejecucion del comando #NPM i, tanbien requiere de la Instalacion
de paquetes de Windows "RSAT: Remote Acces Management Tool", ya que la aplicacion ejecuta comandos via powerShell y este a su vez se comunica con el servidor
de dominio con dicha herramienta.

Lista de cosas que quedan pendientes por programar:
-Bajas de usuarios
-Completar el sistema de login para una mayor seguridad en el servidor


Jovanny Fuentes.