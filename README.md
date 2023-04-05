Repaso git e incorporacion de github.
Recuerden que git trabajo de manera local y que github trabajac en la nube.
Yo tengo que tener un root con git inicializado y en paralelo, tener un repo creado dentro de si usuario de github.
Luego de cumplir con estos dos pasos tengo que realizar la creacion de un "tubo" que una las dos partes: en un extremo mi root local y en el otro, mi repo de github.
¿como creo mi repo en github?
Entro a mi usuario, toco sobre "repositorios" y luego toco el boton "new" (boton verde) Yo en la pantalla de "crear repositorio" tengo que completar con un nombre unico e irrepetible, dejar tildada la opcion "public" y dejar todo como esta. Luego se me habilita el crear el boton "crear repositorio" (boton verde).
A partir de ahora, puedo usar el comando que crea el tubo entre las dos partes.
¿Cual es el comando?
git remote add origin https://...
Este paso se ejecuta una sola vez y luego tengo que usar comando:
git push -u origin master
Para pasar toda la info de mi local por el todo hasta mi github.

-------
Para generar in github pages (url de github que nos permite ver como va quedando el front de nuestro proyecto) necesitamos:
-tener codigo en nuestro repo (tener un push)
-nos dirigimos a setting
-Dentro de  setting, tocamos sobre "pages" en el sidebar
-dentro de "pages" tocamos sobre eldesplegable que dice "none" y lo modificamos por el "master"
-Instantaneamente tocamos sobre el boton "save"
Luego de esto, debemos esperar hasta que se nos genere automaticamente el link con una extencion .io