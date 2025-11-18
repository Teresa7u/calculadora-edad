📋 Descripción del Proyecto

Una Calculadora de Edad, es una aplicación web que permite a los usuarios calcular su edad exacta en años, meses y días a partir de su fecha de nacimiento.

🎯 Objetivos Cumplidos

✅ Funcionalidades Implementadas

Cálculo preciso de edad en años, meses y días

Validación completa de fechas

Interfaz responsive para móvil y desktop

Manejo de errores con mensajes claros

Animaciones en los resultados


✅ Casos de Validación

Campos vacíos

Días fuera de rango (1-31)

Meses fuera de rango (1-12)

Fechas futuras

Fechas inválidas (ej: 31/04/1991)

Años bisiestos

🛠️ Tecnologías Utilizadas

Frontend:

HTML5 - Estructura semántica

CSS3 - Estilos y diseño responsive

JavaScript - Lógica y validaciones

Características Técnicas:
Diseño mobile-first

Variables CSS para colores

Flexbox para layout

Media queries para responsividad

Validación en tiempo real

📁 Estructura de Archivos

text

calculadora-edad/
│
├── index.html          # Estructura principal
├── style.css           # Estilos y diseño
└── app.js              # Lógica y funcionalidad


🔧 Explicación del Código

HTML (index.html)

html
<!-- Estructura básica -->
<form> con 3 inputs (día, mes, año)
<section> para mostrar resultados
Botón de calcular con ícono SVG
  
CSS (style.css)

css

/* Organización */
:root {}          # Variables de colores
* {}              # Reset global
body {}           # Configuración base
.container {}     # Contenedor principal
.input-group {}   # Campos de fecha
.results {}       # Sección de resultados
@media queries {} # Responsividad
  
JavaScript (app.js)

javascript

// Funciones principales
validateDate()     # Valida la fecha ingresada
calculateAge()     # Calcula la edad exacta
displayAge()       # Muestra resultados con animación
clearErrors()      # Limpia mensajes de error


🎨 Paleta de Colores

Colores Primarios

css
--purple-500: hsl(259, 100%, 65%);  /* Morado principal */
--red-400:    hsl(0, 100%, 67%);    /* Rojo para errores */
--white:     hsl(0, 100%, 100%);  /* Blanco puro */
--grey-100:  hsl(0, 0%, 94%);     /* Gris claro (fondo) */
--grey-200:  hsl(0, 0%, 86%);     /* Gris medio (bordes) */
--grey-500:  hsl(0, 1%, 44%);     /* Gris oscuro (textos) */
--black:     hsl(0, 0%, 0%);      /* Negro (textos principales) */
--purple-100: hsl(259, 100%, 95%); /* Morado muy claro (fondos) */

Tipografía:

Poppins - Fuente principal

Pesos: 400 (normal), 700 (bold), 800 (extra-bold)

Layout:

Móvil: Campos apilados verticalmente

Desktop: Campos en línea, botón a la derecha

⚡ Lógica de Cálculo

Algoritmo de Edad:

javascript

// Ejemplo: Nacimiento 15/03/1990 - Hoy 20/10/2024
años = 2024 - 1990 = 34
meses = 10 - 3 = 7  
días = 20 - 15 = 5

// Resultado: 34 años, 7 meses, 5 días
Validaciones Especiales:
Años bisiestos: Febrero tiene 29 días cada 4 años

Días por mes: 30/31 días según el mes

Fecha futura: No puede ser mayor a hoy

📱 Responsividad

Breakpoints:

Móvil: 375px

Tablet: 768px

Desktop: 1440px

Cambios por Dispositivo:

Tamaños de fuente

Espaciados

Posición del botón

Layout de inputs

🧪 Pruebas Realizadas

Casos de Prueba:

✅ Fecha válida normal
✅ Fecha con año bisiesto (29/02/2000)
✅ Fecha inválida (31/04/1991)
✅ Campos vacíos
✅ Fecha futura
✅ Límites de días/meses (32 días, 13 meses)

🚀 Cómo Usar

Ingresar fecha en los campos día, mes y año

Hacer clic en el botón de calcular

Ver resultados animados en años, meses y días

Corregir errores si se muestran mensajes en rojo

📝 Aprendizajes Obtenidos

Técnicos:

Manipulación avanzada de fechas en JavaScript

Validación de formularios

Animaciones CSS y JavaScript

Diseño responsive

Metodológicos:

Organización de código

Manejo de errores

Pruebas de usabilidad

Documentación de proyectos

🔮 Posibles Mejoras Futuras

Selectores de fecha nativos

Cálculo de edad en tiempo real

Modo oscuro

Historial de cálculos

Exportar resultados

 Autor
Estudiante de Desarrollo de Software
Proyecto educativo para practicar HTML, CSS y JavaScript

Documentación creada para el proyecto "Calculadora de Edad"
Fecha de entrega: 19/11/2025
