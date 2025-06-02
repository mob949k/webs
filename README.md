# Manual para Usar y Editar la Plantilla Web

## Introducción
Esta plantilla web está diseñada para presentar el tema de "Vicios de Dicción". Incluye un submarino interactivo que se mueve, mostrando información en cada parada, y un quiz interactivo. Puede usarse para exposiciones y editarse para actualizar contenido. Este manual explica su uso y edición de forma sencilla, sin requerir experiencia previa en páginas web.

## Cómo abrir y ver la página
1. **Localiza los archivos**: Busca la carpeta con `index.html`, `scripts.js` y `styles.css`.
2. **Abre el archivo principal**: Haz doble clic en `index.html` para abrirlo en un navegador (como Chrome o Firefox). Si no se abre, haz clic derecho, selecciona "Abrir con" y elige tu navegador.

## Cómo usar la página en una presentación
- **Navega con el submarino**: Presiona "Espacio" para mover el submarino. Cada parada muestra información sobre vicios de dicción.
- **Revisa la información**: Aparece un cuadro a la derecha (o ventana emergente en pantallas pequeñas) con detalles.
- **Activa el quiz**: A 10,000 metros, haz clic en "Start Quiz", ingresa un nombre y responde preguntas.
- **En dispositivos pequeños**: Toca los puntos rojos en la línea y usa botones de la ventana emergente.

## Conceptos básicos de los archivos
- **HTML (index.html)**: Es el cuerpo de la página, contiene el texto y la estructura básica.
- **CSS (styles.css)**: Define el diseño, como colores y disposición.
- **JS (scripts.js)**: Maneja la lógica de programación, como el movimiento del submarino y el quiz.

## Cómo editar la página
Usa un editor gratuito como Notepad++ o Visual Studio Code.

### Editar desde scripts.js
1. **Abre** `scripts.js`: Usa el editor para abrir este archivo.
2. **Encuentra la función** `displaySlide`: Busca las secciones que comienzan con `if (index === 1) {` hasta `if (index === 4) {`.
3. **Modifica el texto**: Cambia los títulos (`<h2>`) y párrafos (`<p>`) dentro de cada sección. Por ejemplo, ajusta "Solecismos" o "Neologismos".
4. **Añade contenido**: Copia una sección como `if (index === 2) {` y crea una nueva con un número diferente (ej. `if (index === 5) {`) para agregar más paradas.
5. **Guarda y verifica**: Guarda el archivo y recarga `index.html` en el navegador.

### Precauciones
- No borres líneas con `<` o `}` ya que son esenciales.
- Si algo falla, verifica que los cambios se guardaron y nada se eliminó por error.

## Recomendaciones
- Guarda copias de los archivos originales.
- Pide ayuda a alguien con experiencia si es necesario.
- Prueba cambios en un archivo separado antes de usarlo.

Mis mejores deseos 😎
