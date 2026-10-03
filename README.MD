# 🎀 Lizzy Plays Violin

> Un atril digital interactivo y afinador inteligente en el navegador. Renderiza partituras (MusicXML/MIDI), reproduce audio con instrumentos reales de forma sincronizada y te ayuda a practicar con herramientas de bucle, metrónomo y detección de tono en tiempo real.

🔗 **[Ver Demo en Vivo](https://Pablo-Santana-MX.github.io/lizzy-violin/)**

## ✨ Características Principales

### 📖 Atril Digital Interactivo
* **Soporte Multiformato:** Carga e interpreta archivos `MusicXML` (.xml, .mxl, .musicxml) y `MIDI` (.mid, .midi).
* **Renderizado Nativo SVG:** Partituras nítidas y adaptables a cualquier tamaño de pantalla.
* **Audio de Alta Fidelidad:** Reproducción con muestras (SoundFonts) reales de Violín y Piano, con acústica de reverberación natural.
* **Sincronización Perfecta:** El cursor visual de la partitura y el motor de audio operan en una rigurosa rejilla de semicorcheas, eliminando el desfase (lag).
* **Navegación *Click-to-Jump*:** Haz clic o toca cualquier nota en la pantalla y el audio saltará instantáneamente a esa posición.
* **Herramientas de Práctica:** Metrónomo integrado, control de tempo (40-120 BPM) y sistema de bucles interactivos (selección por arrastre).
* **Persistencia Inteligente:** La aplicación guarda automáticamente la última partitura cargada en el `localStorage` del navegador.

### 🎻 Afinador "Kawaii" Integrado
* **Detección de Tono en Tiempo Real:** Utiliza un algoritmo de autocorrelación y la *Web Audio API* para detectar la afinación con alta precisión desde el micrófono del dispositivo.
* **Interfaz Visual Intuitiva:** Medidor estilo analógico con retroalimentación de color para una afinación perfecta (±5 cents).
* **Cuerdas de Referencia:** Botones dedicados para escuchar los tonos exactos del violín (Sol, Re, La, Mi) y afinar de oído.

## 🛠️ Tecnologías Utilizadas

* **[OpenSheetMusicDisplay (OSMD)](https://opensheetmusicdisplay.org/):** Motor de renderizado de MusicXML en el navegador.
* **[Tone.js](https://tonejs.github.io/):** Framework de Web Audio moderno para la programación de secuencias musicales precisas y síntesis/reproducción de *samples*.
* **[Tailwind CSS](https://tailwindcss.com/):** Framework de utilidades CSS para un diseño 100% responsivo (Móvil, Tablet y Escritorio).
* **HTML5 / Vanilla JS:** Código puro y optimizado sin dependencias de frameworks pesados, empaquetado en un único archivo.

## 🚀 Instalación y Uso Local

Este proyecto no requiere de procesos de compilación (build tools) ni de un backend. Todo está contenido en un único archivo `index.html`.

1. Clona el repositorio:
   ```bash
   git clone [https://github.com/Pablo-Santana-MX/lizzy-violin.git](https://github.com/Pablo-Santana-MX/lizzy-violin.git)
   ```
2. Entra en la carpeta del proyecto:
   ```bash
   cd lizzy-violin
   ```
3. ¡Listo! Solo necesitas abrir el archivo `index.html` en cualquier navegador web moderno (Chrome, Firefox, Safari, Edge).

*Nota: Para el funcionamiento del micrófono en el afinador, los navegadores modernos requieren que la página se sirva desde un origen seguro (HTTPS) o desde `localhost`. Si usas GitHub Pages, el HTTPS ya está configurado por defecto.*

## 💡 Cómo conseguir partituras
La aplicación procesa archivos locales. Si tienes partituras en PDF, puedes usar herramientas de código abierto como [Audiveris](https://github.com/Audiveris/audiveris) para convertirlas a MusicXML, o transcribirlas en software gratuito como MuseScore Studio y exportarlas a `.mxl`.

## 📜 Licencia

Este proyecto se distribuye bajo la licencia MIT. Eres libre de usarlo, modificarlo y distribuirlo.

---
*Diseñado con 💖 para músicos, estudiantes y entusiastas del código.*
