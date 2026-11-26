Aquí tienes el contenido listo para copiar y pegar directamente en el archivo `README.md` de tu repositorio `mi-balance` en GitHub (pulsando **Add file** $\rightarrow$ **Create new file**, nombrándolo `README.md` y guardando con **Commit changes**):

```markdown
# Mi Balance — Gestor de Finanzas Personales (PWA Offline)

Aplicación web progresiva (**PWA**) ligera y 100 % offline para el control diario de ingresos y gastos personales, diseñada con enfoque *mobile-first* y almacenamiento local privado sin servidores externos.

🔗 **Demo en vivo:** [https://sarah-pg.github.io/mi-balance/](https://sarah-pg.github.io/mi-balance/)

---

## Características principales

* **Funcionamiento 100 % sin conexión (Offline-First):** Gracias a su *Service Worker* (`sw.js`) y manifiesto web (`manifest.json`), la aplicación puede instalarse de forma nativa en dispositivos Android/iOS y operar sin acceso a internet.
* **Privacidad total (`localStorage`):** Todos los registros financieros se almacenan exclusivamente en el navegador del dispositivo del usuario. Ningún dato se envía ni se guarda en servidores externos.
* **Control diario y balance neto mensual:** Registro rápido de ingresos y gastos con cálculo automático del saldo neto del mes activo.
* **Desglose visual por categorías:** Gráficos de barras horizontales para analizar la distribución del gasto en 10 categorías predefinidas (*alquiler, suministros, teléfono/internet, plataformas, gasolina, comida, peaje, comidas fuera, otros ocio, otros no ocio*).
* **Gestión de gastos e ingresos fijos recurrentes:** Automatización de movimientos mensuales periódicos mediante casillas de verificación rápida.
* **Respaldo de datos:** Exportación e importación de copias de seguridad en formato JSON para portabilidad y resguardo de la información.

---

## Stack técnico y arquitectura

El proyecto está construido íntegramente con tecnologías web estándar, sin dependencias externas ni *frameworks* pesados, priorizando la velocidad de carga y la sencillez de mantenimiento:

* **HTML5 semántico:** Estructura de vista única (`index.html`).
* **CSS3 moderno:** Diseño adaptativo centrado en uso móvil (*responsive design*).
* **JavaScript (ES6+ Vanilla):** Lógica de negocio, renderizado dinámico de gráficos, persistencia en `localStorage` y gestión de copias JSON.
* **PWA APIs:** `manifest.json` para instalación nativa y `Service Worker` para estrategia *cache-first*.

---

## Estructura del repositorio

```text
mi-balance/
├── index.html      # Aplicación principal (estructura, estilos y lógica)
├── manifest.json   # Metadatos e iconos para instalación como PWA
├── sw.js           # Service Worker para caché y soporte offline
├── icon-512.png    # Icono de aplicación (512x512 px)
├── LICENSE         # Licencia MIT
└── README.md       # Documentación del proyecto

```

---

## Instalación en móvil (Android / Chrome)

1. Abre [https://sarah-pg.github.io/mi-balance/](https://www.google.com/url?sa=E&source=gmail&q=https://sarah-pg.github.io/mi-balance/) en Google Chrome.
2. Pulsa el menú de opciones (**⋮**) en la esquina superior derecha.
3. Selecciona **Instalar aplicación** (o *Añadir a pantalla de inicio*).

---

## Licencia

Este proyecto se distribuye bajo la **Licencia MIT**. Consulta el archivo [LICENSE](https://www.google.com/search?q=./LICENSE) para más información.

```

<ElicitationsGroup message="Si quieres dejar algún detalle más cerrado en el proyecto o en tu perfil de GitHub:">
  <Elicitation label="Añadir descripción y etiquetas (Topics)" query="Guíame para configurar la descripción corta, el enlace web y los Topics en la barra lateral de mi repositorio en GitHub."/>
  <Elicitation label="Cómo actualizar la app en el futuro" query="Si más adelante añado mejoras a index.html en GitHub, ¿qué pasos debo seguir para que mi móvil descargue la nueva versión sin fallos de caché?"/>
</ElicitationsGroup>

```
