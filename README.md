# NavegacionIntro

Para empezar un proyecto con navegacion primero creamos un elemento de tipo Navigation dentro de la carpeta resources como se muestra en la siguiente imágen


![](.README_images/99ddc905.png)

A continuación nos solicitará importar la biblioteca de fragmentos, le damos OK

![](.README_images/8aeaf11c.png)

Eliminamos el texto que nos aparece por default y dejamos el ConstraintLayout

![](.README_images/c93fae64.png)

En la paleta de componentes seleccionamos Containers y seleccionamos la opción NavHostFragment la cual arrastarmos al layout:

![](.README_images/61c29ed4.png)

Una vez hecho esto, nos aparecerá un cuadro indicandonos a que navegador se va a asociar, este Main activity se convierte en un hospedador de fragmentos, es decir, 
el layout del Main activity solo va a servir para hospedar a los fragmentos, no se va a diseñar

![](.README_images/66bc86bf.png)

Nos muestra en la parte del navGraph el enlazamiento hecho y procedemos a dejar en 0 las anclas del texto

![](.README_images/79079321.png)

Un fragmento en Android es una parte de la interfaz de usuario y estan relacionados a una misma activity, cada fragmento tambien tiene asociada su propia clase, asi como un layout 
tiene asociado un activity.

Ahora generamos los fragmentos,esto se hace en el archivo de "navegación" que se generó en el paso 1. le damos doble click:

![](.README_images/c8c9fd67.png)

Le damos click en la imagen con el signo "+"

![](.README_images/05bdeb2a.png)

Seleccionamos la opción "Create new destinatoon"

![](.README_images/6e2a0877.png)

Nos aparece un cuadro de dialogo para nombrar al fragmento, le damos el nomnre y le damos OK

![](.README_images/deb07572.png)

Ahora generamos un segundo fragmento realizando el paso anterior, pueden ser tantos fragmentos que se necesiten:

![](.README_images/9d605f0c.png)

Nota importante: cada que se genera un fragmento tienen asociada una clase, la cual genera una excepción la cual debe ser borrada al ejecutarse.

El la carpeta java se encuentran las clases, seleccionamos la primer opción e ingresamos a la clase:

![](.README_images/3ae6c60a.png)

Una vez que ingresamos al PrimerFragmento, borramos la linea que se indica a continuación:

![](.README_images/9040272d.png)

Procedemos de la misma forma a borrar esa linea del código del SegundoFragmento:

![](.README_images/45928f93.png)

Regresamos a la carpeta "navegacion" y seleccionamos la estrella que se indica en la imagen, esto con la finalidad de ordenar los fragmentos, es importante
mencionaer que el fragmento que tiene la imagen de una casita en su parte superior, es la que se visualizará al inicio de la aplicación:

![](.README_images/e57aee97.png)

Enlazamos la flecha del primer fragmento con la segunda, arrastrando hasta llegar al segundo fragmento:

![](.README_images/13f12301.png)

Seleccionamos la flecha que comunica los fragmnetos y procedemos a nombrar su ID, en este caso se le ponemos "primero_a_segundo", a continuación le damos la animación 
al fragmento, con el nombre que tienen cada uno de éstos, los cuales aparecen dentro de las opciones:

![](.README_images/de53bb88.png)

Ahora editaremos cada pantalla, en esta ocasión pondremos un botón al fragmento 1 para pasar al fragmento 2:

![](.README_images/52c40036.png)