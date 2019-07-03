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


