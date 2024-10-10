**Markdown para el README.md de un ejercicio individual:**

```markdown
# Ejercicio 1: Crear una tarjeta de presentación interactiva

**Descripción:**
En este ejercicio, creamos una tarjeta de presentación interactiva utilizando HTML, CSS y JavaScript. La tarjeta muestra información básica sobre mí y tiene animaciones al pasar el cursor por encima.

**Tecnologías utilizadas:**
* HTML5
* CSS3 (Flexbox, Grid, Animaciones)
* JavaScript (DOM Manipulation)

**Funcionalidades:**
* Mostrar información personal de forma clara y concisa.
* Utilizar animaciones suaves para mejorar la experiencia del usuario.
* Hacer que la tarjeta sea responsive para adaptarse a diferentes tamaños de pantalla.

**Cómo ejecutar:**
1. Clonar este repositorio.
2. Abrir el archivo `index.html` en un navegador web.

**Código:**
```javascript
// Ejemplo de código JavaScript
const card = document.querySelector('.card');
card.addEventListener('mouseover', () => {
  card.classList.add('hover');
});

card.addEventListener('mouseout', () => {
  card.classList.remove('hover');   

});