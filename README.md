# 🏋️‍♂️ IronTrack - Aplicación de Rutina de Gimnasio

Aplicación web móvil personalizada para **Luis Reyes**, adaptada exactamente a la pauta entregada por tu gimnasio.

## 📱 ¿Qué incluye esta App?
1. **Identificación Visual y Máquinas:**
   - Cada ejercicio incluye su ilustración visual para recordar la postura al instante.
   - Etiqueta destacada con el **número de máquina de tu gimnasio** (ej. *Máq. 3 - Remo*, *Máq. 12 - Prensa*, *Máq. 1 - Smith*, *Máq. 5 - Jalón*, etc.).
   - Desplegable con la **técnica exacta y consejos del entrenador**.
   - Botón directo **▶ Video** para abrir una demostración en YouTube con 1 toque.
2. **Registro de Pesos Reales vs Sugeridos:**
   - Muestra el peso sugerido por tu pauta (ej. 15 kg).
   - Casillas interactivas para cada serie (Set 1, 2, 3, 4) con botones rápidos `+` y `-` para anotar el peso real que pudiste levantar hoy.
   - Casillas de verificación para marcar series terminadas.
3. **Temporizador de Descanso Integrado (1 min):**
   - Cuenta regresiva de 60 segundos con aviso sonoro y vibración al terminar cada serie.
4. **📈 Gráficas Interactivas de Progreso (Chart.js):**
   - Evolución de carga por ejercicio: selecciona cualquier ejercicio para ver cómo va aumentando tu fuerza a través del tiempo.
   - Volumen total levantado por sesión (kg acumulados).
   - Contador de sesiones y series completadas.
5. **☁️ Respaldo en la Nube y Copia de Seguridad:**
   - **Sincronización en la Nube con Clave:** Sube tu progreso con una clave personal (ej. `luis-reyes-gym`) y descárgalo en cualquier celular o computadora sin contraseñas complicadas.
   - **Descarga de Archivo (.json):** Descarga una copia de seguridad directa para guardarla en tu Google Drive o enviártela por WhatsApp.
   - **Compartir por WhatsApp:** Genera un resumen del entrenamiento de hoy formateado para enviar a tu chat.

---

## 🚀 Cómo usarla en tu Celular

### Opción A: Abrir el archivo directamente
1. Pasa el archivo `index.html` a tu celular (o ábrelo desde tu navegador móvil).
2. Toca los tres puntos de Chrome y selecciona **"Añadir a la pantalla de inicio"** (o en Safari de iPhone toca el botón Compartir ➡️ **"Añadir a pantalla de inicio"**).
3. ¡Se abrirá como una aplicación nativa completa, a pantalla completa y sin barras de navegación!

### Opción B: Ejecutar servidor local en tu red Wi-Fi
En esta misma carpeta, puedes iniciar un servidor rápido con Python:
```bash
python -m http.server 8080
```
Luego en tu celular (conectado al mismo Wi-Fi) abres:
`http://IP_DE_TU_PC:8080` (ejemplo `http://192.168.1.50:8080`).

### Opción C: Subirla a la web gratis (GitHub Pages / Vercel / Netlify)
Dado que es un archivo estático autocontenido (`index.html`), puedes subirlo gratis a:
- [GitHub Pages](https://pages.github.com/)
- [Netlify Drop](https://app.netlify.com/drop) (solo arrastras la carpeta `gym-tracker` y te da un link web al instante).
- [Vercel](https://vercel.com/)
