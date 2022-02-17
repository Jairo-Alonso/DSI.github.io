# DsiP1.github.io -- Jairo Alonso Abreu
## Cambio de la contraseña por defecto
Tras haber realizado los pasos previos de la práctica iniciamos la máquina virtual y actualizamos la contraseña de usuario.
![Inicio de la máquina y cambio de contraseña:](https://user-images.githubusercontent.com/65543522/154450480-4945de18-1675-4f79-bf6a-63b85cc13cb0.png)
## Conexión de la vm mediante ssh
Para ello se ha usado el comando `ifconfig` en la consola browser del iias.
Tras haber hecho el comando `ifconfig -a` vemos que la dirección ip es:

![NUestra ip: 10.6.128.192](https://user-images.githubusercontent.com/65543522/154451204-3b6d101c-2df7-4013-a811-9e325da6bd26.png)

## Generación de una clave pública/privada

Debido a que no haba una clave pública/privada hubo que generar una mediante el comando `ssh-keygen`.
Después de haberse guardado en el directorio: .ssh/id_rsa.pub. Ejcutamos el comando `ssh-copy-id usuario@10.6.128.192` para copiar la clave en la máquina virtual. Se introduce la contraseña del usuario y como se puede ver en la imagen ya podemos conectarnos desde esta máquina local a la máquina virtual sin tener que introducir la contraseña.

![Generación de clave y conexin a ssh sin contraseña.](https://user-images.githubusercontent.com/65543522/154470569-4863d2d4-920c-4ce4-94e6-d1d64cfbf57c.png)
