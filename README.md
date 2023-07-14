Crear un Bot en Dircord

1.iniciar sesion en discord

2.ya dentro de discord habra un boton  verde con el signo de mas +, dan click ahi

3. aparecera una ventana con diferentes opciones, le dan a una, por ejemplo "juegos", como es un servidor de prueba dale a la opcion "para mis amigos y yo" y le pones el nombre que quieras y lo creas

4.entra en la pagina discord developer portal

5.entran en la opcion de "Applications" le dan al boton azul que dice "New Application"

6.eligen un nombre, aceptan los terminos y condiciones y crean.

7.al crearlo deben entrar en la opcion que dice "Bot" y dan al boton azul que dice "Add Bot", aparecera una ventana que dira "ADD A BOT TO THIS APP?" basicamente les pregunta si quieren agregar el bot a su app, y haran click en el boton de "Yes do it"

8.le dan al boton azul que dice "View Token" copian el Codigo que les da y lo guardan en un block de notas o algo, porque lo usaremos ,mas adelante.

9. en esa misma pagina hacen scroll hacia abajo y accionan las opciones de
   a)presence intent
   b)server members intent
   c)required for your bot
   d)managge content intent
y guardan los cambios

10.en las opciones de la barra de la izquierda entran en la que dice "URL generation"

11. veran una serie de tablas en las que pueden hacer check, esos son los "scopes"
    a)bot
    b) application commands
en la tabla de abajo que dice "bot permmisions"
    a) activan "administrador"
12. por ultimo copian el link que les aparece justo de bajo de las tablas y lo abren, eso los llevara a una pagina que les permite agregar todas estas opciones que previamente seleccionamos al sevidor que creamos al inicio de estos pasos, como? seleccionando el nombre que le pusiste al servidor

13.en esa mis pagina le dan click al boton de continuar

14. le dan al boton de autorizar

15. marcan que si son humanos y listo, ya estaria autorizado el bot y vinculado a los parametros que pusimos y ya si entran al chat del servidor que entraron veran que el bot fue agregado

Instalar Node.js

1.entrar en Node.js.com

2.descargar la version recomendada

3.instalar Node Setup

4.entrar en el explorador de archivos y hacer click derecho sobre la carpeta de "tu equipo" (aparecera una miniventana )ahi buscar la opcion "propiedades"

5.se abrira una pestana de configuracion, ahi darle a la opcion llamada "Configuracion avanzada del sistema"

6.nuevamente se abrira una ventana, ahi deberan buscar la opcion "variables de entorno"

7.aparecera una ventana donde habra la opcion de: "Nuevo" haran click y nombraran la Variable como Node

8.sin cerrar nada vuelven al explorador de archivos, entran en la capeta llamada "Disco local c:" dentro buscan la capeta llamada "archivos de programa" no se confundan hay una que pone x86,ESA NO ES.

9.dentro buscan la capeta "nodejs" entran en ella y copian la direccion en la que esta alojada, es simple, arriba sale una barra con por ejemplo algo asi: Archivos de programa > nodejs

10.hacen click en esa barra y les saldra un pequeno texto subraydo en azul, ese texto lo copian (ctrl + c)

11.salen de ahi y entran en la ventana donde anteriormente colocaron el nombre de la variables, abajo sale la opcion que dice valor de la variable, ahi pegan el texto que acaban de copiar y le dan "aceptar" a todas las ventanas que dejaron abiertas

12.entran en Visual Studio Code

13.abren la terminal (ctrl + `)

14.escriben el comando "npm init" esperan que cargue y le dan enter hasta que les aparezca "is this OK? (yes) " dan enter una vez mas y escriben el comando "npm i express"

15.Esperan que se descargue el paquete de node.

Correr el servidor

1.ya instalado entras en la carpeta package.json y en la linea 5 saldra: "scripts": {

2.(, "server": "json-server --watch db.json") COPIA TODO LO QUE ESTA DENTRO DEL PARENTESIS, SI, INCLUYENDO ESA COMA

3.pegas todo detras de la llave que cierra, deberia quedar asi: (, "server": "json-server --watch db.json" }, )

4.presiona (crtl + s) entra en la terminal y escribe "npm run server" dale enter hasta que te salga esto: (

adminpanel@1.0.0 server
json-server --watch db.json

{^_^}/ hi!

Loading db.json Done

Resources http://localhost:3000/menu

Home http://localhost:3000

Type s + enter at any time to create a snapshot of the database Watching...

)

Enjoy!!
