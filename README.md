# 🏋️‍♂️ IronTrack v5.2 Cardio Edition - Rutina Gym Luis Reyes

> **Acceso Web & PWA:** [https://silverdevslabs-del.github.io/irontrack/](https://silverdevslabs-del.github.io/irontrack/)  
> Aplicación web progresiva (PWA) instalable, 100% offline-first con animaciones GIF incrustadas y pauta personalizada.

---

## 🚀 Novedades de la Versión 5.2 (Cardio Edition)
- 🏃 **Bloque de Calentamiento Cardiovascular:** Añadido al inicio de los 3 días de entrenamiento (Día 1, Día 2 y Día 3).
- 🔄 **Selector Rápido de Máquina:** *Elíptica* fijada por defecto con botón para cambiar instantáneamente a *Bicicleta Estática*.
- 📊 **Registro Integral de Parámetros:**
  - ⏱️ **Tiempo** (15 minutos sugeridos con controles `+` y `-`).
  - ⚡ **Nivel de Resistencia** (1 a 20).
  - 📍 **Distancia** en kilómetros (km).
  - 🔥 **Calorías** estimadas (kcal).
  - ✅ **Botón de Completado:** Marca el calentamiento como realizado y computa hacia el porcentaje de progreso de la sesión.
- 🎬 **Animaciones GIF Offline:** Demostración de movimiento y fases de técnica para Elíptica y Bicicleta Estática.

---

## 📱 Características Principales
1. **Identificación Visual y Máquinas:**
   - Ilustraciones y animaciones fluidas para verificar postura y técnica al instante.
   - Etiqueta destacada con el **número de máquina** de tu gimnasio (ej. *Máq. 3 - Remo*, *Máq. 12 - Prensa*, *Máq. 1 - Smith*, etc.).
   - Consejos técnicos del entrenador y botón directo a demostración en video.
2. **Registro de Pesos Reales vs Sugeridos:**
   - Carga sugerida y casillas interactivas para cada serie (Set 1 a 4).
   - Botones rápidos `+` y `-` para ajustar el peso levantado.
   - Casillas de verificación para marcar series terminadas.
3. **Temporizador de Descanso Integrado (60s):**
   - Cuenta regresiva con alertas sonoras (Web Audio API) y vibración al terminar cada serie.
4. **📈 Gráficas Interactivas de Progreso (Chart.js):**
   - Evolución de carga por ejercicio para monitorear incremento de fuerza.
   - Volumen total acumulado (kg levantados) y contador de sesiones completadas.
5. **☁️ Respaldo en la Nube y Copia de Seguridad:**
   - **Sincronización en la Nube:** Sube tu progreso con una clave personal (`luis-reyes-gym`) y descárgalo en cualquier celular o PC.
   - **Exportación JSON:** Descarga copias de seguridad locales.
   - **Compartir por WhatsApp:** Genera un resumen del entrenamiento de hoy listo para enviar.

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
