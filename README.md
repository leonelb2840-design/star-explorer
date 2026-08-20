# 🚀 Star Explorer

> Un simulador espacial 2D inspirado en los clásicos de Android, con física real, planetas del Sistema Solar, asteroides destructibles y power-ups.

[![GitHub Pages](https://img.shields.io/badge/🌐-Jugar%20Online-blue?style=flat-square)](https://tuusuario.github.io/star-explorer)
[![PWA](https://img.shields.io/badge/📲-PWA%20Ready-purple?style=flat-square)](https://tuusuario.github.io/star-explorer)
[![License](https://img.shields.io/badge/📄-MIT-green?style=flat-square)](LICENSE)

---

## 🎮 Demo en vivo

👉 **[Jugar ahora](https://tuusuario.github.io/star-explorer)** *(reemplaza con tu URL de GitHub Pages)*

---

## ✨ Características

| Feature | Descripción |
|---------|-------------|
| 🪐 **Planetas reales** | Explora el Sol y los 8 planetas del Sistema Solar con gravedad realista |
| 💥 **Física de colisiones** | Choques elásticos entre nave, asteroides y planetas |
| ☄️ **Asteroides destructibles** | 60 asteroides con HP, rotación y formas procedurales |
| 🎁 **4 Power-ups** | Escudo 🛡️, Reparación ❤️, Velocidad ⚡ y Multishot 🔫 |
| 🔫 **Sistema de disparo** | Destruye asteroides a cañonazos |
| 🎵 **Audio espacial** | Efectos de sonido generados proceduralmente con Web Audio API |
| 🗺️ **Minimapa** | Navegación táctica del sistema solar en tiempo real |
| 📱 **Joystick virtual** | Controles táctiles optimizados para móvil y tablet |
| 🖱️ **Controles de ratón** | Apunta con el cursor, impulsa con click, turbo con espacio |
| 📲 **PWA** | Instalable como app nativa desde el navegador |

---

## 🕹️ Controles

### PC (Ratón + Teclado)

| Acción | Input |
|--------|-------|
| 🎯 Apuntar | Mover el ratón |
| 🚀 Impulso | Click izquierdo o `W` / `↑` |
| ⏪ Reversa | Click derecho o `S` / `↓` |
| ⚡ Turbo | `Espacio` |
| 🔫 Disparar | `F` |

### Móvil / Tablet

| Acción | Input |
|--------|-------|
| 🎯 Apuntar | Joystick virtual (arrastrar) |
| 🚀 Impulso | Joystick virtual (empujar) |
| 🔫 Disparar | Botón 🔥 |
| ⚡ Turbo | Botón ⚡ |

---

## 🛠️ Tecnologías

- **HTML5 Canvas** — Renderizado 2D acelerado por GPU
- **Vanilla JavaScript (ES6+)** — Sin dependencias externas
- **Web Audio API** — Síntesis de sonido procedural
- **Service Worker** — Funcionamiento offline (PWA)
- **Web App Manifest** — Instalación como app nativa

---

## 📁 Estructura del proyecto

```
star-explorer/
├── index.html          # Juego completo (HTML + CSS + JS)
├── sw.js               # Service Worker para PWA offline
├── manifest.json       # Manifest de la Web App
└── README.md           # Este archivo
```

> **Nota:** El juego está contenido en un único archivo `index.html` para facilitar el despliegue. No requiere build ni dependencias.

---

## 🚀 Despliegue en GitHub Pages

1. **Fork** o crea un nuevo repositorio en GitHub.
2. Sube los 3 archivos (`index.html`, `sw.js`, `manifest.json`) a la rama `main`.
3. Ve a **Settings → Pages** en tu repositorio.
4. En **Source**, selecciona:
   - Branch: `main`
   - Folder: `/ (root)`
5. Guarda y espera ~1 minuto.
6. Tu juego estará disponible en:
   ```
   https://TU_USUARIO.github.io/NOMBRE_DEL_REPO/
   ```

---

## 🧪 Instalación local

No necesitas servidor para probarlo, pero si quieres que el Service Worker funcione correctamente:

```bash
# Clona el repositorio
git clone https://github.com/tuusuario/star-explorer.git
cd star-explorer

# Opción A: Python 3
python -m http.server 8000

# Opción B: Node.js (necesitas npx)
npx serve .

# Opción C: VS Code con Live Server
# Haz clic derecho en index.html → "Open with Live Server"
```

Luego abre `http://localhost:8000` en tu navegador.

---

## 🎯 Objetivo del juego

1. **Explora** los 8 planetas del Sistema Solar (el Sol cuenta como cuerpo pero no da punto).
2. **Destruye asteroides** para ganar puntos.
3. **Recoge power-ups** para sobrevivir más tiempo.
4. **Evita chocar** contra el Sol — ¡te quita vida!
5. **Usa el minimapa** para orientarte en el espacio infinito.

---

## 🖼️ Iconos

El juego incluye iconos SVG inline en el `manifest.json`, por lo que **no necesitas archivos de imagen adicionales**. Si prefieres usar PNGs personalizados, reemplaza las entradas en `manifest.json` con:

```json
"icons": [
  { "src": "icon-192x192.png", "sizes": "192x192", "type": "image/png" },
  { "src": "icon-512x512.png", "sizes": "512x512", "type": "image/png" }
]
```

---

## 📜 Licencia

Este proyecto está bajo la licencia **MIT**. Puedes usarlo, modificarlo y distribuirlo libremente.

---

## 🙏 Créditos

- Inspirado en los simuladores espaciales de **Android Raster Egg**.
- Datos de planetas basados en el **Sistema Solar real**.
- Desarrollado con ❤️ y mucho café.

---

<p align="center">
  <b>🌟 Si te gusta el proyecto, dale una estrella en GitHub 🌟</b>
</p>
