# NavegacionIntro

Para empezar un proyecto con navegacion primero creamos un elemento de tipo Navigation dentro de la carpeta resources como se muestra en la siguiente imágen


![](.README_images/99ddc905.png)

A continuación nos solicitará importar la biblioteca de fragmentos, le damos OK

![](.README_images/8aeaf11c.png)

El siguiente paso es irnos al layout del main_activity y quitar el textview  y dejar solamente el ConstraintLayout, de la paleta de componentes arrastrar un  del menu de Containers
![](.README_images/76f98c48.png)

La opcion NavHostFragment y agregarla a tu vista, asegurate de darles las anclas en los cuantro extremos a cero.


![](.README_images/012ddfdf.png)

Deepues de eso te pedira generar un archivo de navegacion, lo generas y le das de nombre navegacion, se va a generar una nueva carpeta en resources, que se llama navigation y dentro de ella
aparece en archivo de navegación.
Este archivo de navegacion debe estar ligado a la main activity activity para que pueda funcionar. Esta union se lleva a cabo de la siguiente manera


