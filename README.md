# prueba1css
Este es un ejemplo de un documento HTML que utiliza CSS para definir estilos y diseño en una página web.
Aquí tienes una descripción de los elementos y su funcionalidad:

    <!DOCTYPE html>: Declaración del tipo de documento HTML utilizado.

    <html lang="en">: Inicio del elemento HTML con un atributo de idioma establecido en inglés.

    <head>: La sección de encabezado que contiene metadatos y vínculos a hojas de estilo externas. 
    Aquí se especifica la codificación de caracteres, la configuración de la vista en dispositivos 
    móviles y el título de la página.

    <meta charset="UTF-8">: Especifica la codificación de caracteres como UTF-8, que es ampliamente 
    utilizada para admitir caracteres especiales y multilingües.

    <meta name="viewport" content="width=device-width, initial-scale=1.0">: Configura la vista en
    dispositivos móviles, asegurando que el ancho sea igual al ancho del dispositivo y que la escala inicial sea 1.0.

    <title>aprendiendo css</title>: Establece el título de la página que se muestra en la pestaña del navegador.

    <link rel="stylesheet" href="style2.css">: Enlaza una hoja de estilo externa llamada "style2.css" para aplicar estilos a la página.

    <body>: Comienza la sección del cuerpo del documento HTML, donde se encuentra el contenido visible de la página.

    <div class="header">: Define una sección de encabezado en la página.

    <h1 style="color: brown;">hola programador h1</h1>: Encabezado de nivel 1 con texto "hola programador h1" 
    y estilo de color de texto marrón aplicado directamente al elemento.

    <div class="sidebar">: Define una sección de barra lateral en la página.

    <h2 class="text-coral">hola programador1</h2>: Encabezado de nivel 2 con texto "hola programador1" y 
    una clase llamada "text-coral" aplicada para darle estilo.

    <div class="content">: Define una sección de contenido principal en la página.

    Varios elementos <div> con la clase "box" y diferentes contenidos y estilos aplicados, incluyendo encabezados 
    de nivel 2, párrafos con clases de estilo, y más.

    <div class="footer">: Define una sección de pie de página en la página.

    <p class="text-right">: Párrafo con una clase llamada "text-right" que alinea el texto a la derecha y le aplica un
    estilo específico.

En resumen, este documento HTML representa una página web simple con un encabezado, una barra lateral, un área de 
contenido principal y un pie de página. Los estilos se definen principalmente en una hoja de estilo externa 
(style2.css) y se aplican a elementos específicos utilizando clases y estilos en línea.

@////////////////////////

style2.css:

    Estilos generales:
        El body establece un fondo de color claro (lightblue) y una fuente de texto genérica para todo el documento.
        Se utiliza un selector universal * para eliminar el margen predeterminado de todos los elementos en la página.

    Estilos para los elementos <h2>:
        Los elementos <h2> se estilizan con un color de texto azul, un fondo púrpura (rebeccapurple), márgenes, relleno, borde y dimensiones específicas.

    Estilos para los elementos <p>:
        Los elementos de párrafo <p> tienen márgenes, un tamaño de fuente pequeño, negrita y cursiva.

    Estilos específicos para el elemento con id="cabecera3":
        El elemento con id="cabecera3" se estiliza con un color de texto verde.

    Estilos para elementos con la clase .text-danger:
        Los elementos con la clase .text-danger tienen un color de texto rojo.

    Estilos para elementos con la clase .text-coral:
        Los elementos con la clase .text-coral tienen un color de texto azul, un fondo púrpura y otros estilos similares a los elementos <h2>.

    Estilos para elementos con la clase .text-center:
        Los elementos con la clase .text-center tienen texto justificado, un color de texto amarillo y otros estilos similares a los elementos <h2>.
        También se ajusta el tamaño de fuente a 17px.

    Estilos para elementos con la clase .text-left:
        Los elementos con la clase .text-left tienen texto alineado a la izquierda y otros estilos similares a los elementos <h2>.

    Estilos para elementos con la clase .text-right:
        Los elementos con la clase .text-right tienen texto alineado a la derecha, un color de fondo rojo y otros estilos similares a los elementos <h2>.

    Estilos para el encabezado (header), la barra lateral (sidebar), el contenido (content), y el pie de página (footer):

    Cada una de estas secciones de la página tiene estilos específicos para controlar su diseño, incluidos colores de fondo y tamaños.

    Estilos para las cajas con la clase .box:

    Las cajas con la clase .box se definen con un tamaño fijo, un fondo gris, margen y flotan a la izquierda para que aparezcan en línea horizontal.

    Limpieza de flotantes:

    Al final del CSS, se utiliza la pseudo-clase ::after en la clase .content para limpiar los elementos flotantes y asegurarse de que el contenido dentro
    de .content no se superponga en el pie de página.

Este CSS define la apariencia y el diseño de una página web, pero es importante tener en cuenta que la estructura HTML de la página también desempeña un papel fundamental en la visualización final de la página.
