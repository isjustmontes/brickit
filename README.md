# 🧱 BrickIt

![BrickIt Logo](logo.png)

**BrickIt** es un minijuego arcade retro de estilo *Arkanoid* / *Breakout* desarrollado íntegramente en un único archivo `index.html` utilizando HTML5 Canvas y JavaScript puro, sin dependencias ni librerías externas.

Este proyecto ha sido concebido y desarrollado dentro de un entorno de trabajo local asistido por herramientas de IA y Orca.

---

## 🎮 Enlace en vivo (Jugar online)

Puedes probar la última versión del juego directamente en tu navegador a través de **GitHub Pages**:

👉 **[Jugar a BrickIt](https://isjustmontes.github.io/brickit/)**

---

## ✨ Características principales

- **Gráficos en Canvas:** Renderizado fluido y dinámico en 2D adaptado para cualquier navegador.
- **Sistema de Progresión (15 Niveles):** Curva de dificultad ascendente con 15 distribuciones (*layouts*) distintas de bloques y pantallas de victoria.
- **Mecánica de Power-Ups y Power-Downs:** Al destruir ladrillos, existe una probabilidad de que caigan objetos especiales que otorgan efectos al recogerlos con la pala:
  - 🟢 **Objeto Verde:** Amplía temporalmente el tamaño de la pala (Ventaja).
  - 🔴 **Objeto Rojo:** Reduce temporalmente el tamaño de la pala (Penalización).
  - 🔵 **Objeto Azul:** Duplica la pelota actual en juego (Multibola).
- **Efectos de Sonido Sintéticos:** Audio integrado mediante la **Web Audio API** para rebotes y destrucción de bloques, sin depender de archivos de audio externos.
- **Marcador y Vidas:** Gestión completa de puntuación, contador de vidas y pantallas interactivas de *Game Over* y victoria final.

---

## 🛠️ Tecnologías utilizadas

- **HTML5 Canvas** (Renderizado gráfico 2D)
- **JavaScript (Vanilla)** (Lógica de juego, físicas de rebote y colisiones)
- **Web Audio API** (Efectos de sonido procedimentales)
- **GitHub CLI & GitHub Pages** (Control de versiones, releases y despliegue continuo)

---

## 🚀 Cómo jugar en local

Al ser un proyecto autónomo alojado en un único archivo, no requiere instalación ni compilación.

1. Clona este repositorio en tu equipo:
   ```bash
   git clone [https://github.com/isjustmontes/brickit.git](https://github.com/isjustmontes/brickit.git)
