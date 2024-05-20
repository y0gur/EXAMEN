"Este es el repositorio del examen de lenguaje de marcas"
"
Ejercicio: Crear una Página Web Básica

Objetivo: Desarrollar una página web básica que incluya HTML, CSS y JavaScript para practicar la integración de estos lenguajes.

Descripción:

Desarrolla una página web simple que cumpla con los siguientes requisitos:

1. HTML:
   - Crea un archivo index.html.
   - La página debe tener un título en la barra de navegación.
   - Incluir una cabecera (<header>) con un título principal (<h1>).
   - Incluir un párrafo (<p>) con una breve descripción de la página.
   - Incluir un botón (<button>) que diga "Hacer clic".

2. CSS:
   - Crea un archivo styles.css.
   - Aplica estilos básicos para que la cabecera tenga un fondo de color azul y el texto en blanco.
   - El párrafo debe tener un tamaño de fuente de 16px y un margen de 20px.
   - El botón debe tener un fondo de color verde, un borde redondeado y un cambio de color cuando se pase el cursor sobre él (hover).

3. JavaScript:
   - Crea un archivo script.js.
   - Cuando se haga clic en el botón, debe aparecer una alerta con el mensaje "¡Botón clicado!".

Instrucciones:

1. Crea un nuevo directorio para tu proyecto.
2. Dentro del directorio, crea tres archivos: index.html, styles.css y script.js.
3. Enlaza los archivos CSS y JavaScript en tu archivo HTML.
4. Escribe el código necesario en cada archivo para cumplir con los requisitos descritos.

Estructura del Proyecto:


/tu-proyecto
│
├── index.html
├── styles.css
└── script.js


Pistas:

- Para enlazar el archivo CSS en el HTML, utiliza la etiqueta <link> dentro del <head>.
- Para enlazar el archivo JavaScript en el HTML, utiliza la etiqueta <script> justo antes de la etiqueta de cierre </body>.
- Utiliza la propiedad :hover en CSS para cambiar el color del botón cuando el cursor esté sobre él.
- En JavaScript, utiliza el método alert() para mostrar la alerta y el método addEventListener() para manejar el evento de clic en el botón.

Ejemplo de Código:

index.html
html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Página Web Básica</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Bienvenidos a mi página web</h1>
    </header>
    <p>Esta es una página web de ejemplo para practicar HTML, CSS y JavaScript.</p>
    <button id="myButton">Hacer clic</button>
    <script src="script.js"></script>
</body>
</html>


styles.css
css
header {
    background-color: blue;
    color: white;
    text-align: center;
    padding: 20px;
}

p {
    font-size: 16px;
    margin: 20px;
}

button {
    background-color: green;
    color: white;
    border: none;
    border-radius: 5px;
    padding: 10px 20px;
    cursor: pointer;
}

button:hover {
    background-color: darkgreen;
}


script.js
javascript
document.getElementById('myButton').addEventListener('click', function() {
    alert('¡Botón clicado!');
});


Entrega:

Sube tu proyecto completo en un repositorio de GitHub y proporciona el enlace.
"
