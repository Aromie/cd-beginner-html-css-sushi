## Agregar más páginas

Esta tarjeta le mostrará cómo agregar más páginas a su sitio web.

- En la parte superior del panel de códigos, haga clic en el símbolo **+** junto a las pestañas y escriba un nombre para su nuevo archivo. Debe terminar en `.html` (¡incluido el punto!) Para que el navegador sepa que es una página web.

![Agregar un nuevo archivo en Trinket](images/tktNewFileArrows.png)

## \--- colapso \---

## título: cambio de nombre o eliminación de un archivo

Si desea cambiar el nombre de un archivo, haga clic en el icono **cog** a la derecha del nombre del archivo y luego haga clic en el ícono de **lápices**. Escriba el nuevo nombre y presione **Ingrese**. También puede eliminar un archivo haciendo clic en el icono **bin** lugar del icono **pencil**. ![](images/EditFilename.png)

Es posible que se pregunte por qué no puede cambiar el nombre del archivo `index.html`. `index.html` es un nombre especial utilizado para la página</strong> inicio **** de un sitio web. Esa es la primera página en la que aterrizas cuando visitas un sitio web. Cuando vaya a la página de inicio de un sitio web, el navegador buscará el archivo llamado `index.html` y lo mostrará en su pantalla.

\--- /colapso \---

- Busque el archivo `blank_page.html` y copie y pegue todo el código en su nuevo archivo. Como quiera copiar todo, puede hacer clic en cualquier parte del código y usar el atajo de teclado <kbd>Ctrl</kbd> (o <kbd>cmd</kbd>) y <kbd>A</kbd> para seleccionar todo al mismo tiempo.

- Cambia el texto entre las etiquetas `<title> </title>` para que tu nueva página tenga un título adecuado. Trinket no mostrará el título, pero puede verlo en la parte superior de la ventana de su navegador si descarga su proyecto.

![El título de la página que se muestra en la pestaña del navegador](images/egLocalFileWindowTitle.png)

- Entre las etiquetas `<main> </main>` del nuevo archivo, use las etiquetas que ha aprendido para agregar cosas a la página, como párrafos, encabezados, imágenes y listas.

- Repita los pasos anteriores para cada página nueva que desee agregar.

Cuando hay demasiadas pestañas para que Trinket se muestre a la vez, puede usar los íconos **<** y **>** en la esquina superior izquierda de las pestañas para desplazarse entre ellos.

![Los botones para desplazarse por las pestañas](images/tktScrollTabIcons.png)

¡Ahora necesita hacer enlaces para poder acceder a cada una de sus páginas nuevas! Pongamos todos los enlaces en una lista.

- En el archivo `index.html` , agregue el siguiente código al cuerpo de su página web:

```html
    <ul>
        <li><a href="index.html">Inicio</a></li>
        <li><a href="attractions.html">Lugares para visitar</a></li>
        <li><a href="music.html">Música</a></li>
        <li><a href="food.html">Cosas para comer</a></li>
    </ul>
```

- Cambie el valor del atributo `href` para cada enlace (recuerde, ese es el texto dentro de las comillas) para que coincida exactamente con el nombre de cada archivo HTML que haya creado.

- Cambie el texto entre las etiquetas `<a> </a>` a las descripciones adecuadas de sus páginas.

¡Ahora puede navegar a sus nuevas páginas!

![Ejemplo de lista de enlaces en una página web](images/egListOfPageLinks.png)