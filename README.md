🐍 Lenguajes y Técnicas de Programación I — PWA Educativa `v3`

> Plataforma web progresiva (PWA) de apoyo a la asignatura **LTP I**  
> Licenciatura en Informática · 3er Año · Plan E · Curso 2025-2026  
> Universidad de Informática "Jesús Montané Oropesa" (UIJ)

📋 Descripción general

Aplicación web progresiva (PWA) diseñada como plataforma de apoyo integral para la asignatura Lenguajes y Técnicas de Programación I, centrada en Python como lenguaje de implementación. La app permite al estudiante consultar el contenido teórico de las cuatro conferencias del programa, practicar con un banco de ejercicios de autoevaluación, explorar interactivamente las 35 palabras reservadas del lenguaje Python con sus funciones y ejemplos de código, acceder a 18 documentos PDF descargables y consultar un glosario de términos.

La v3 incorpora como novedad principal el módulo **Keywords** — un tópico dedicado exclusivamente a las palabras reservadas de Python con búsqueda, filtros por categoría, modal detallado por keyword y navegación secuencial.

🎯 Datos académicos

| Campo | Valor |
|---|---|
| **Asignatura** | Lenguajes y Técnicas de Programación I (LTP I) |
| **Año académico** | 3er Año, Grupo único |
| **Carrera** | Licenciatura en Informática |
| **Plan de estudios** | Plan E |
| **Institución** | UIJ "Jesús Montané Oropesa" |
| **Profesor** | Ricardo Castillo Valdés |
| **Curso** | 2025-2026 |
| **Versión de la app** | v3 |
| **Bloque** | LTP I (de tres: LTP I, LTP II, LTP III) |

🗂️ Programa de la asignatura cubierto

El programa de LTP I se divide en 4 temas con un total de **32 horas lectivas** (8 conferencias + 12 clases prácticas).

Tema 1 — Introducción al Proceso de Programación** *(6 horas)*
- Clasificación de lenguajes: bajo nivel, medio y alto nivel
- Compiladores vs. intérpretes: proceso de traducción
- Ficheros fuente, objeto, bytecode y ejecutable (`.py`, `.pyc`, `.o`, `.exe`)
- Relación: algoritmo → código fuente → programa en ejecución
- Python como lenguaje interpretado de alto nivel
- Algoritmos y pseudocódigo estructurado

Tema 2 — Elementos Sintácticos del Lenguaje** *(8 horas)*
- Las 35 palabras reservadas de Python y sus categorías
- Reglas para identificadores válidos e inválidos
- Convenciones PEP 8: `snake_case`, `MAYÚSCULAS`, `CamelCase`
- Constantes literales: `int`, `float`, `str`, `bool`, `None`
- Cadenas: concatenación, repetición, función `len()`
- Separadores e indentación obligatoria (4 espacios)
- Comentarios: `#` de línea y docstrings con triple comilla

Tema 3 — Tipos de Datos y Operadores** *(8 horas)*
- Tipos fundamentales: `int`, `float`, `str`, `bool`, `NoneType`
- Tipado dinámico: una variable puede cambiar de tipo
- Casting explícito: `int()`, `float()`, `str()`, `bool()`
- Variables: declaración y asignación simultánea, swap de variables
- Operadores aritméticos: `+`, `-`, `*`, `/`, `//`, `%`, `**`
- Jerarquía de operadores (precedencia): `()` → `**` → unarios → `*`, `/`, `//`, `%` → `+`, `-`
- Operadores compuestos: `+=`, `-=`, `*=`, `//=`, `%=`, `**=`

Tema 4 — Estructura del Programa Python** *(10 horas)*
- Patrón EPR: Entrada → Proceso → Resultado
- Sentencias y bloques: indentación de 4 espacios
- `input()` siempre retorna cadena → casting obligatorio
- `print()` con parámetros `sep=`, `end=` y f-strings
- Semántica del operador `=` (asignación, no igualdad)
- f-strings con especificadores de formato: `:.2f`, `:d`, `:>10`
- Programas integradores completos

📱 Módulos de la aplicación

🏠 Inicio
Panel principal con estadísticas globales (documentos disponibles, keywords, ejercicios totales). Acordeón expandible con los 4 temas del programa: cada tema muestra la conferencia y las guías prácticas asociadas con sus puntos de contenido.

⌨️ Keywords — Palabras Reservadas de Python
Módulo exclusivo de v3.** Las 35 palabras reservadas de Python organizadas en una cuadrícula interactiva con:

- **Búsqueda en tiempo real** por nombre de la keyword o su función
- **Filtros por categoría:** Control de flujo · Definición · Valor lógico · Manejo de errores · Importación · Operador lógico · Ámbito · Concurrencia
- **Modal detallado** al tocar cada keyword con:
  - Función explicada en español
  - Sintaxis con resaltado
  - Ejemplo de código funcional y comentado
- **Navegación anterior/siguiente** dentro del modal sin necesidad de cerrarlo

Las 35 keywords cubiertas, agrupadas por categoría:

| Categoría | Keywords |
|---|---|
| Control de flujo | `if` `elif` `else` `for` `while` `break` `continue` `pass` `return` `yield` |
| Definición | `def` `class` `lambda` |
| Valores especiales | `True` `False` `None` |
| Manejo de errores | `try` `except` `finally` `raise` `assert` |
| Importación | `import` `from` `as` |
| Operadores lógicos | `and` `or` `not` `in` `is` |
| Ámbito y contexto | `global` `nonlocal` `del` `with` |
| Concurrencia | `async` `await` |

🎯 Ejercicios
Banco de **28 ejercicios** distribuidos en los 4 temas del programa:
- Opción múltiple
- Verdadero / Falso
- Completar la expresión

Cada sesión presenta **12 ejercicios aleatorios** del tema o temas seleccionados. El sistema registra: respuestas correctas, porcentaje de aciertos y racha de aciertos consecutivos (🔥). Retroalimentación inmediata con explicación detallada de cada respuesta.

📁 Materiales
18 documentos PDF descargables con filtros por categoría:

| Categoría (`fi`) | Nº | Documentos |
|---|---|---|
| **Conferencias** | 4 | Conf. 1 Tema 1, Conf. 2 Tema 2, Conf. 3 Tema 3, Conf. 4 Tema 4 |
| **Guías prácticas** | 12 | Guías 1A, 1B (T1) · 2A, 2B, 2C (T2) · 3A, 3B, 3C (T3) · 4A, 4B, 4C, 4D (T4) |
| **Glosario** | 1 | Glosario LTP I — Términos Esenciales |
| **Referencia** | 1 | Palabras Reservadas de Python — Referencia Completa (66 KB) |

El PDF de referencia de palabras reservadas (66 KB) incluye: tabla resumen de las 35 keywords por categoría, ficha completa por keyword con función + sintaxis + ejemplo + nota práctica, y tabla de errores frecuentes con soluciones.

Cada documento puede visualizarse directamente en la app o descargarse al dispositivo.

🛠️ Tecnologías utilizadas

| Tecnología | Uso |
|---|---|
| HTML5 / CSS3 / JavaScript (vanilla) | Aplicación completa sin frameworks |
| Fraunces + Space Grotesk + JetBrains Mono | Tipografías (Google Fonts) |
| Web App Manifest | Instalación como PWA |
| Service Worker | Modo offline y caché |
| Base64 | 18 PDFs embebidos en el HTML |
| Blob URL API | Visualización y descarga de PDFs |
| ReportLab (Python) | Generación de los PDFs del material didáctico |

📂 Estructura del repositorio

ltp1/
├── index.html          # Aplicación completa (320 KB, autocontenida)
├── manifest.json       # Manifiesto PWA
├── sw.js               # Service Worker para modo offline
├── icons/              # Iconos PWA (8 resoluciones)
│   ├── icon-72x72.png
│   ├── icon-96x96.png
│   ├── icon-128x128.png
│   ├── icon-144x144.png
│   ├── icon-152x152.png
│   ├── icon-192x192.png
│   ├── icon-384x384.png
│   └── icon-512x512.png
└── README.md

Nota: Los 18 PDFs están embebidos en base64 dentro de `index.html`. La aplicación es completamente autocontenida y funciona sin archivos adicionales ni conexión a internet.

🚀 Despliegue

GitHub Pages
1. Subir todos los archivos a un repositorio público
2. Ir a **Settings → Pages**
3. Seleccionar rama `main`, carpeta `/ (root)` → **Save**
4. URL disponible en: `https://usuario.github.io/ltp1/`

Netlify
1. Descomprimir el ZIP
2. Arrastrar la carpeta al área de deploy en [netlify.com](https://netlify.com)
3. Publicado en segundos con HTTPS automático
4. Personalizar el nombre del sitio en Settings → Site name

Servidor local
```bash
python -m http.server 8080
# Abrir: http://localhost:8080
```

📲 Instalación como app en Android

1. Abrir la URL en **Chrome para Android**
2. Tocar el banner *"Añadir a pantalla de inicio"* → **Instalar**
3. Si no aparece el banner: menú ⋮ → *"Añadir a pantalla de inicio"*
4. La app se instala con ícono Python bicolor (azul/dorado) y funciona sin internet

🔒 Requisitos técnicos

- Navegador moderno (Chrome 60+, Firefox 55+, Safari 11+)
- HTTPS para activación del Service Worker (automático en GitHub Pages y Netlify)
- Sin dependencias externas — 100% offline tras primera carga
- Compatible con Android e iOS

📝 Historial de versiones

| Versión | Cambios principales |
|---|---|
| v1 | Primera versión: teoría, ejercicios básicos, 6 PDFs embebidos |
| v2 | 17 PDFs individuales (4 conferencias + 12 guías + glosario), banco de 100 ejercicios, descarga directa |
| **v3** | ✅ Módulo **Keywords** con las 35 palabras reservadas de Python (búsqueda + filtros + modal detallado). PDF de referencia completo de keywords (66 KB). 18 documentos totales. Nuevo filtro "Referencia" en biblioteca. Versión actual. |

📄 Licencia y uso

Recurso educativo de libre uso para fines académicos.  
Desarrollado con fines docentes para la UIJ "Jesús Montané Oropesa".

