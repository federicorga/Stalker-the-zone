# S.T.A.L.K.E.R - THE ZONE.

## Pagina inspirada en la franquicia Stalker, con informacion del juego + chat interactivo + juego(busqueda de Artefactos)

_Stalker The Zone_

- [Pagina del Proyecto](https://federicorga.github.io/Stalker-the-zone/)




## Autor

- [@Federico Garea](https://www.linkedin.com/in/federicogarea/)

![Logo](https://www.stalker2.com/user/themes/s2/images/favicon.png)




## Construido con:

* [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript) - Lenguaje de Programación
  
* [SweetAlert2](https://sweetalert2.github.io/) - plugin de jQuery

* [NodeJS](https://nodejs.org/es) - Lenguaje de Progrmación
  
* [Handlebars](https://handlebarsjs.com/) - Motor de Plantilla
  
* [Express + API-REST](https://expressjs.com/es/) - framework
  
* [SocketIo](https://socket.io/)- Biblioteca






## Pre-Requerimientos :🔧

Para poder utilizar la aplicacion se deben instalar las siguientes dependencias:

```
npm i
npm i express
npm i express-handlebars
npm i socket.io
```

## Descripción del proyecto:

Insiprado en la Franquicia Stalker, un juego donde los eventos transcurren en la Zona de Exclusión de Chernóbil ubicado en Ucrana, donde se produjo uno de los mayores desastres nucleares de la historia.

La pagina posee:

 * Una seccion principal donde se cuenta un poco de informacion sobre dicha franquicia y links directo a los diferentes juegos.
 
 * Una seccion con un chat interactivo mediante una PDA, esta PDA es la misma que se encuentra en el juego donde los personajes se comunicaban, la misma cuenta con una seccion de mapa, una seccion de chat, una seccion donde se pueden ver los diferentes usuarios conectados y una seccion de guia donde se encontrara informacion para el uso de la PDA y el detector de Artefactos. ademas cuenta con los sonidos originales del juego y puede encenderse y apagarse.
 
 * Un juego interactivo llamado "Detector de Artefactos", al activarlo la persona debe explorar el mapa en busca de la misma y se creo una especie de sensor de proximidad que al acercarnos al objetivo zonara con mayor intensidad, a su ves se pondra visible dicho artefacto y podra ser capturado.

* Un Inventario con diferentes elementos comestibles (con los sonidos originales del juego), actualmente no posee una funcionalidad 

El chat fue construido con Express y Socket.io, se puede interactuar con las personas que se conecten a la pagina solo debe colocarse un nombre de usuario para tal fin.

## Screenshot:

![img1](https://github.com/federicorga/ChatStalkers/blob/main/src/public/docs/S1.png)

![img2](https://github.com/federicorga/ChatStalkers/blob/main/src/public/docs/S2.png)

![img3](https://github.com/federicorga/ChatStalkers/blob/main/src/public/docs/S3.png)

![img4](https://github.com/federicorga/ChatStalkers/blob/main/src/public/docs/S4.png)

![img5](https://github.com/federicorga/ChatStalkers/blob/main/src/public/docs/S5.png)

![img6](https://github.com/federicorga/ChatStalkers/blob/main/src/public/docs/S6.png)
