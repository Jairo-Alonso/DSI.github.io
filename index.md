# Informe Práctica 1 UyA

## Qué peticiones desencadena la consulta.
Tanto en Google como en Mozilla se generan las mismas peticiones, todas son tipo GET. En este caso la consulta pide primero acceso a  los recursos del servidor y luego se le responde con un código 200 y los recursos que había solicitado.

![Peticiones](https://user-images.githubusercontent.com/65543522/155112243-489e5bdc-9f20-4790-8f8b-354bb6899347.png)

## ¿Qué tipo de petición estás realizando?

Como se puede ver en la imagen de arriba las paticiones son tipo GET. Estas peticiones tienen la diferencia en cuanto a las de POST en que la URL en las peticiones GET suele contener toda la información introducida por el usuario.

## Qué código de estatus devuelve.
En cada petición devuelve el código 200 que nos confirma la petición y por lo tanto el servidor nos facilita el recurso que estabamos soicitando.

## Qué DNS tiene el servidor
Para averiguar el DNS del servidor e ha usado la herramienta https://mxtoolbox.com/
Por lo tanto el DNS sería: site.gobiernodecanarias.org

![Dns](https://user-images.githubusercontent.com/65543522/155116901-42049fce-7da0-49b8-b4aa-bd45b1e13d28.png)


## Qué IP tiene tiene el servidor

Para saber que ip tiene se ha usado el comando `dig` seguido de la dirección https://www3.gobiernodecanarias.org/citasalud/#/


![Ip](https://user-images.githubusercontent.com/65543522/155114972-9981a4df-0b23-433e-84cf-19b9ed5d1bc7.png)
Como se puede ver el servidor tiene la ip: 127.0.0.53

## ¿La página tiene alguna cookie?, ¿Cuáles?.

La página contiene 2 cookies:

![cookies](https://user-images.githubusercontent.com/65543522/155117005-c32c9af4-7636-43ef-8ca7-d0335555287d.png)

## Alguna línea de código JavaScript
Archivo Javascript abierto:

![Javascript](https://user-images.githubusercontent.com/65543522/155117072-27ae16ee-2421-4db5-9bb1-8fcda8675c00.png)

## Alguna línea de código CSS que se aplique
Archivo CSS abierto:

![Css](https://user-images.githubusercontent.com/65543522/155117494-008a681e-963b-4560-b898-53c47af44f73.png)

## Alguna línea de código HTML que se aplique.
Archivo HTML abierto:

![html](https://user-images.githubusercontent.com/65543522/155117190-821e5f42-588d-4381-aae4-ab0719d4331b.png)

