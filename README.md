📊 Analizadora Sociométrica - Suite Educativa v9.0

Analizadora Sociométrica es una herramienta web integral diseñada para orientadores, psicopedagogos y docentes. Permite realizar un análisis profundo de la estructura social del aula, contrastando la percepción real (lo que sucede) con la autopercepción (lo que los alumnos creen), y facilitando la creación de grupos de trabajo optimizados mediante algoritmos inteligentes.

🚀 Características Principales

Análisis Dual: Procesa simultáneamente matrices de percepción real y autopercepción.

Visualización Interactiva: Genera sociogramas dinámicos donde se pueden visualizar las relaciones de elección (verde) y rechazo (rojo).

Cálculo Automático de Métricas:

Índices de Cohesión y Disociación.

Detección automática de estatus sociométrico: Popular, Rechazado, Ignorado, Controvertido, Promedio.

Cálculo de Impacto y Preferencia.

Módulo de Contraste: Tablas comparativas para detectar discrepancias entre la realidad y las creencias del alumnado (precisión en la percepción de aceptación y rechazo).

Generador de Grupos con IA: Algoritmo heurístico que propone grupos de trabajo equilibrados, evitando conflictos mutuos y potenciando relaciones positivas.

Interfaz Moderna: Diseño "Glassmorphism" con tonos pasteles, totalmente responsive y amigable.

Privacidad Total: Todo el procesamiento se realiza en el navegador del usuario (Client-Side). Ningún dato se sube a servidores externos.

Exportación Profesional: Generación de informes en PDF con diseño ejecutivo y exportación de datos crudos a Excel.

🛠️ Tecnologías Utilizadas

Esta aplicación es una Single Page Application (SPA) construida con tecnologías web estándar, sin dependencias de backend complejas:

HTML5 & JavaScript (Vanilla ES6+): Lógica del núcleo.

Tailwind CSS: Diseño y estilos modernos.

SheetJS (xlsx): Lectura y escritura de archivos Excel.

Vis.js: Librería para la renderización de grafos y redes (sociogramas).

html2pdf.js: Motor de generación de informes PDF imprimibles.

FontAwesome: Iconografía.

📋 Instrucciones de Uso

1. Instalación

No requiere instalación. Simplemente:

Clona este repositorio o descarga el archivo ZIP.

Abre el archivo index.html en tu navegador web favorito (Chrome, Firefox, Edge).

2. Formato de Datos (Excel)

Para que la aplicación funcione, necesitas dos archivos Excel (uno para percepción real y otro para autopercepción) con el siguiente formato estricto:

Matriz Cuadrada: Los nombres de las filas deben coincidir con los de las columnas.

Fila 1: Nombres de todos los alumnos (Receptores).

Columna A: Nombres de todos los alumnos (Emisores).

Celdas:

Escribe + para indicar una elección/aceptación positiva.

Escribe - para indicar un rechazo negativo.

Deja la celda vacía si no hay relación.

3. Flujo de Trabajo

Ve a la pestaña DATOS y carga tus archivos Excel o usa el botón "Prueba Rápida" para ver una demo.

Explora las pestañas PERCEPCIÓN y AUTOPERCEPCIÓN para ver los sociogramas y tablas.

Usa la pestaña CONTRASTE para ver las diferencias y generar grupos de trabajo.

Ve a INFORMES para descargar los resultados.

🤝 Autoría y Créditos

Desarrollado con ❤️ para la comunidad educativa.

Autor: El loco de la mochila

Web: Blog Averroes - El loco de la mochila

📄 Licencia

Este proyecto se distribuye bajo la licencia MIT. Eres libre de usarlo, modificarlo y distribuirlo con fines educativos.
