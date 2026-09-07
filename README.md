# Hoja de Vida Profesional

## Descripción del proyecto

Este proyecto consiste en el desarrollo de una página web que presenta una hoja de vida profesional de **Fernando Barrientos**.

La página fue desarrollada utilizando **HTML5 y CSS3**, aplicando etiquetas semánticas para organizar correctamente el contenido y diferentes técnicas de diseño para lograr una presentación clara, ordenada y profesional.

El proyecto incluye información personal, formación académica, experiencia laboral, habilidades técnicas y profesionales, certificaciones, idiomas y un formulario de contacto.

---

## Tecnologías utilizadas

* HTML5
* CSS3

---

## Características del proyecto

La página web incluye los siguientes elementos:

* Estructura semántica utilizando:

  * `<header>`
  * `<nav>`
  * `<main>`
  * `<section>`
  * `<article>`
  * `<footer>`

* Información personal:

  * Fotografía
  * Nombre
  * Carrera profesional
  * Ciudad
  * Correo electrónico
  * Número telefónico
  * Perfil profesional

* Información académica.

* Experiencia laboral.

* Habilidades técnicas y profesionales.

* Certificaciones, cursos, talleres y seminarios.

* Tabla de idiomas.

* Formulario de contacto con validación HTML5.

* Diseño responsive para dispositivos móviles.

---

## Flexbox

Se utilizó **Flexbox** para organizar los datos personales de la hoja de vida.

La fotografía y la información personal se organizan mediante:

```css
display: flex;
```

Esto permite distribuir los elementos de forma ordenada y adaptable.

---

## CSS Grid

Se utilizó **CSS Grid** para organizar las experiencias laborales.

Las diferentes experiencias se presentan mediante una cuadrícula utilizando:

```css
display: grid;
```

Esto permite mostrar las experiencias en diferentes columnas en pantallas grandes y adaptarlas a una sola columna en dispositivos móviles.

---

## Diseño Responsive

El proyecto cuenta con diseño adaptable utilizando una `@media query`.

Cuando el sitio se visualiza en dispositivos con pantallas pequeñas, los elementos cambian su distribución para mejorar la visualización.

Ejemplo:

```css
@media (max-width: 768px) {
    .datos-personales {
        flex-direction: column;
    }

    .experiencia-grid {
        grid-template-columns: 1fr;
    }
}
```

---

## Accesibilidad

Se aplicaron diferentes elementos para mejorar la accesibilidad de la página:

* Uso del atributo `alt` en las imágenes.
* Uso de etiquetas `<label>` en los campos del formulario.
* Uso de `required` para validar campos obligatorios.
* Uso de `type="email"` para validar correos electrónicos.
* Uso de navegación mediante `<nav>`.
* Uso de etiquetas HTML5 semánticas.

---

## Estructura del proyecto

```text
barrientos-fernando-hoja-vida/
│
├── index.html
│
├── css/
│   └── styles.css
│
├── assets/
│   └── images/
│       └── yo.jpeg
│
└── README.md
```

---

## Ejecución del proyecto

Para ejecutar el proyecto:

1. Descargar o copiar la carpeta del proyecto.
2. Verificar que todos los archivos mantengan la estructura indicada.
3. Abrir el archivo `index.html` en cualquier navegador web.

No es necesario instalar programas adicionales.

---

## Autor

**Fernando Barrientos**

Estudiante de Ingeniería de Sistemas.

Universidad Católica Boliviana "San Pablo" - UCB.

La Paz, Bolivia.
