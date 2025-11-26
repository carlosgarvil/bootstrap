# Guía de Bootstrap – Material didáctico

Este repositorio contiene una serie de páginas HTML autoexplicativas para enseñar Bootstrap de forma progresiva y orientada a alumnado de desarrollo web (DAW/DAM).

Cada archivo incluye:

- Explicación del concepto
- Ejemplos visuales
- Código comentado
- Un ejercicio final resuelto

Está pensado para trabajar Bootstrap solo con CDN, sin necesidad de instalación adicional.

---

## Contenido del repositorio

### 1. Layout básico y breakpoints  
**Archivo:** `01-layout.html`

Aprenderás:

- `.row`, `.col`, `.col-*`
- Breakpoints (`col-sm-*`, `col-md-*`, `col-lg-*`)
- Distribución responsive real

**Ejercicio:** crear varias grids responsive con diferentes combinaciones de columnas.

---

### 2. Containers  
**Archivo:** `02-containers.html`

Incluye:

- `.container`
- `.container-fluid`
- `.container-{breakpoint}`

**Ejercicio:** usar la misma grid dentro de distintos tipos de container para comparar los anchos.

---

### 3. Espaciado y utilidades  
**Archivo:** `03-spacing-utils.html`

Aprenderás:

- Márgenes: `m-*` (por ejemplo `m-3`, `mt-4`, `mx-2`)
- Padding: `p-*` (por ejemplo `p-2`, `py-3`, `px-4`)
- Gap en grids: `g-*` dentro de `.row`
- Alineación de texto: `text-start`, `text-center`, `text-end`
- Flexbox rápido: `d-flex`, `justify-content-*`, `align-items-*`

**Ejercicio:** maquetar tres cajas con espacios, alineaciones y centrados distintos.

---

### 4. Cards (tarjetas)  
**Archivo:** `04-cards.html`

Incluye:

- `.card`, `.card-body`
- `.card-img-top`
- `.card-title`, `.card-text`
- Combinación de cards con grid para hacer listados tipo tienda o blog

**Ejercicio:** crear un grid responsivo de cards (productos o entradas de blog).

---

### 5. Tipografía y colores  
**Archivo:** `05-typography-colors.html`

Aprenderás:

- Niveles de título: `.h1` a `.h6`
- Párrafo destacado: `.lead`
- Grosor del texto: `.fw-bold`, `.fw-light`
- Colores de texto: `.text-primary`, `.text-muted`
- Fondo claro: `.bg-light`

**Ejercicio:** convertir un bloque de texto plano en contenido con estructura visual (título, subtítulo, párrafos y elementos secundarios).

---

### 6. Botones y Call To Action  
**Archivo:** `06-buttons-cta.html`

Incluye:

- Botones base: `.btn`
- Variantes: `.btn-primary`, `.btn-secondary`, `.btn-outline-*`
- Tamaños: `.btn-sm`, `.btn-lg`
- Botones de ancho completo en móvil: `.d-block`, `.w-100`

**Ejercicio:** crear una sección tipo hero con un botón principal grande y un botón secundario.

---

### 7. Formularios modernos  
**Archivo:** `07-forms.html`

Aprenderás:

- Campos de entrada: `.form-control`
- Etiquetas: `.form-label`
- Grupos de entrada: `.input-group`
- Selects estilizados: `.form-select`
- Checkboxes y radios: `.form-check`
- Validación visual básica: `.is-valid`, `.is-invalid` y mensajes de feedback

**Ejercicio:** construir un formulario de registro responsivo con nombre, apellidos, email, contraseña, curso, aceptación de términos y validación visual básica.

---

### 8. Navbar y menús responsivos  
**Archivo:** `08-navbar.html`

Incluye:

- Barra de navegación: `.navbar`
- Comportamiento responsive: `.navbar-expand-*`
- Marca o logo: `.navbar-brand`
- Botón hamburguesa: `.navbar-toggler` y `.navbar-toggler-icon`
- Contenido colapsable: `.collapse`, `.navbar-collapse`
- Enlaces de menú: `.nav-item`, `.nav-link`

**Ejercicio:** crear una navbar que se colapsa en móvil (menú hamburguesa) y se muestra horizontal en escritorio.

---

## Objetivo del material

Este material permite que el alumnado:

- Aprenda Bootstrap paso a paso desde ejemplos sencillos.
- Comprenda cómo se construyen layouts responsive reales.
- Modele interfaces modernas (landing, cards, formularios, menús).
- Pueda reutilizar los ejemplos como base para sus propios proyectos.

Está especialmente indicado para:

- Desarrollo Web en Entorno Cliente (DAW)
- Diseño de Interfaces Web
- Talleres o cursos de iniciación a Bootstrap/desarrollo web

---