# 🎀 Lizzy Plays Violin

**Lizzy Plays Violin** es una aplicación web de una sola página (SPA) diseñada para revolucionar la forma en que los estudiantes de música practican su instrumento. Combina un avanzado atril digital para leer partituras con un afinador inteligente integrado, ejecutándose 100% en el navegador sin necesidad de instalar software adicional ni subir archivos a servidores de terceros.

🔗 **[Ver Demo en Vivo](https://TU-USUARIO.github.io/lizzy-violin/)**

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
   git clone [https://github.com/TU-USUARIO/lizzy-violin.git](https://github.com/TU-USUARIO/lizzy-violin.git)
