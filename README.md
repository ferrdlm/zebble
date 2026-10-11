# 🎐 zebble

> an interactive 3d raymarched pebble & 432hz tone generator compressed into a single <3kb data uri.

built for **hack club shrink** 🩵

---

## 💫 features

- **3d raymarched pebble:** real time sdf pebble rendering with soft organic rim lighting using pure raw webgl.
- **interactive deformation:** drag or touch to rotate, squish, and ripple the pebble surface dynamically.
- **432hz harmonic audio:** tap anywhere across the canvas to play ambient sine wave tones tuned to 432hz harmonic notes.
- **extreme size constraint:** the entire experience (html, css, webgl shaders, web audio api logic) is packed under 3,072 bytes in a data:text/html,... string.

---

## 🫧 tech stack

- **webgl** (raw glsl raymarching shader)
- **web audio api** (synthesizer)
- **vanilla js & css**

---

## 🛼 how to run

1. **from file:** open index.html in any browser.
2. **from data uri:** copy the full string inside `data-uri.txt` and paste it directly into your browser address bar (chrome recommended).
