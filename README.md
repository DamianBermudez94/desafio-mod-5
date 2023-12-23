Desafío del módulo N°5 de la carrera fullstack de apx.school.

El desafío consistía relizar el juego piedra, papel y tijera desarrollando el front-end, back-end y utilizando
la realtime data base y data base no relacional de firebase.
Todo ello deployado en Heroku para así poder jugar en línea.

Técnologías utilizadas: TypeScript, ExpressJs, Firebase.

El front-end fue desarrollado mediante Web Components, Pages, State Manager para la interacción con el back-end y un Router para el manejo de las rutas/pages

El back-end fue desarrollado mediante los principios restfull siendo este el que permite la interacción entre el front y la DB.

# desafio-mod-5  https://damianbermudez94.github.io/desafio-mod-5/

MODO DE JUEGO:

"Nuevo juego" Te permite crear una sala y compartir un código de identificación de la room para jugar con un amigo (guarda este código), si pasado 30 segundos tu amigo no se conecto, el juego te va a avisar y te va a pedir que vuelvas al menú de inicio.

Podes reutilizar la room que ya creaste y compartir el código con otro amigo que si este listo y tenga ganas de jugar...

Para volver a ingresar a la room ya creada, debes ingresar a traves de "ingresar a una sala". Una vez allí, pones el código de room que guardaste y compartiste, tu nombre de usuario y arranca nuevamente el proceso de esperar a que se conecte tu amigo para jugar (él tambien deberá ingresar mediante "ingresar a una sala").

Una vez que ambos hayan ingresado a la room, van a encontrar un botón que les pide que confirmen que estan listos para jugar. Una vez que ambos hayan confirmado, aparecera un contador y las tres opciones (piedra, papel o tijera) para que elijan, una vez terminado el juego y obtenido el resultado podrán seguir jugado o desconectarse para que otro pueda volver a reutilizar la room (Con cerrar el browser es suficiente)





