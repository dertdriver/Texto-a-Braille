# ⠃ Texto a Braille

**Texto a Braille** es una aplicación web que permite convertir texto escrito en español al sistema de lectoescritura Braille, utilizando celdas de seis puntos.

El proyecto ofrece una interfaz sencilla e interactiva para visualizar cómo se representa cada letra, número y signo mediante puntos en relieve.

## ✨ Características

- 🔤 Conversión de texto a Braille en tiempo real.
- 🔢 Soporte para letras, números y signos de puntuación.
- 🇪🇸 Soporte para caracteres del español: ñ, á, é, í, ó, ú y ü.
- 🔍 Representación visual de cada carácter mediante una matriz de 2×3.
- 💡 Identificación de los puntos activos de cada celda.
- 📋 Opción para copiar el resultado en Braille.
- 🧹 Botón para limpiar el contenido.
- 📱 Diseño adaptable a dispositivos móviles.
- 🌐 Funciona directamente en el navegador, sin instalaciones.

## 🛠️ Tecnologías utilizadas

- HTML5
- CSS3
- JavaScript

No utiliza frameworks ni dependencias externas.

## 🚀 Instalación y uso

1. Clonar el repositorio:

   ```bash
   git clone https://github.com/dert98/texto-a-braille.git
   ```

2. Entrar en la carpeta:

   ```bash
   cd texto-a-braille
   ```

3. Abrir el archivo `index.html` en cualquier navegador.

No requiere servidor ni configuración adicional.

## ⠿ ¿Cómo funciona?

El sistema Braille utiliza celdas de seis puntos distribuidos en dos columnas y tres filas.

Cada punto puede estar en dos estados:

- **1:** Punto activo.
- **0:** Punto inactivo.

Esto permite representar hasta 64 combinaciones diferentes por celda.

La aplicación utiliza una tabla de equivalencias entre caracteres del alfabeto español y sus correspondientes símbolos Unicode Braille.

## 📚 Objetivo del proyecto

Crear una herramienta educativa e interactiva que permita conocer y experimentar con el sistema Braille, facilitando la comprensión de su estructura y funcionamiento.

## 👨‍💻 Autor

**Dert Driver**

- GitHub: [@dert98](https://github.com/dert98)

---

⭐ Si te resulta útil este proyecto, ¡no olvides darle una estrella al repositorio!
