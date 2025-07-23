# 🚀 Formulario TAROMATIC Video

Este repositorio contiene un formulario optimizado en HTML, CSS y JS puro para captación de leads y generación de videos personalizados usando TAROMATIC MADRE.

---

## ✅ ¿Qué hace este formulario?

- Captura nombre, email y tipo de video deseado
- Envía los datos a una API real (puedes conectar con TAROMATIC MADRE, n8n, Make, etc.)
- Muestra confirmación al usuario
- 100% responsivo y listo para producción

---

## 🌐 Cómo desplegar en GitHub Pages

### 1. Crea un nuevo repositorio

Ve a [https://github.com/new](https://github.com/new) y:

- Ponle un nombre como `formulario-taromatic-video`
- Hazlo **público**
- Marca la opción `Add a README`

---

### 2. Sube el archivo `index.html`

Puedes hacerlo desde la web:
- Click en “Add file” → “Upload files”
- Sube tu archivo `index.html` (usa este nombre exacto para que GitHub Pages lo sirva)

O desde terminal:
```bash
git clone https://github.com/tu_usuario/formulario-taromatic-video.git
cd formulario-taromatic-video
mv /ruta/a/formulario_taromatic_video_embebido.html index.html
git add index.html
git commit -m "Deploy inicial"
git push origin main
```

---

### 3. Activa GitHub Pages

1. Entra a tu repositorio
2. Ve a **Settings** → **Pages**
3. En “Build and deployment” selecciona:
   - `Source`: `Deploy from a branch`
   - `Branch`: `main`
   - Carpeta: `/ (root)`
4. Haz clic en Save

---

### 4. Accede a tu formulario

GitHub generará una URL como:

```
https://tu_usuario.github.io/formulario-taromatic-video/
```

¡Listo! Ya tienes el formulario en línea.

---

## ⚙️ Personalización opcional

- Cambia los colores o textos en `index.html`
- Agrega una conexión real a tu API (ej. n8n webhook, Google Sheets, TaroFactura)
- Agrega tracking con Google Analytics, PostHog, etc.

---

## 🧠 Soporte

Este formulario forma parte del ecosistema TAROMATIC MADRE.

Si necesitas una versión conectada a backend real, con seguridad y persistencia de datos, solicita un despliegue cloud personalizado.

