# TechConsultas PWA

## 📁 Archivos del proyecto
```
index.html          ← App principal
manifest.json       ← Configuración PWA
sw.js               ← Service Worker (offline)
icon-*.png          ← Iconos Android
apple-touch-icon.png← Icono iPhone/iPad
Code.gs             ← Backend Google Apps Script
```

## 🚀 Publicar en GitHub Pages (paso a paso)

### 1. Crear repositorio en GitHub
1. Ve a https://github.com y crea cuenta si no tienes
2. Haz clic en **"New repository"**
3. Nombre: `techconsultas` (todo minúsculas)
4. Márcalo como **Public**
5. Haz clic en **"Create repository"**

### 2. Subir los archivos
1. En el repositorio recién creado, haz clic en **"uploading an existing file"**
2. Arrastra TODOS los archivos de esta carpeta (excepto Code.gs y README.md)
   - index.html
   - manifest.json
   - sw.js
   - icon-72.png, icon-96.png, icon-128.png, icon-144.png
   - icon-152.png, icon-192.png, icon-384.png, icon-512.png
   - apple-touch-icon.png
3. Haz clic en **"Commit changes"**

### 3. Activar GitHub Pages
1. Ve a **Settings** (pestaña del repositorio)
2. En el menú izquierdo: **Pages**
3. En "Branch": selecciona **main** y carpeta **/ (root)**
4. Haz clic en **Save**
5. Espera 2 minutos → tu URL será:
   `https://TU_USUARIO.github.io/techconsultas`

---

## 📱 Instalar en Android
1. Abre Chrome y ve a la URL de GitHub Pages
2. Aparecerá un banner azul **"Añadir a pantalla de inicio"** → tócalo
3. Si no aparece: menú ⋮ → **"Añadir a pantalla de inicio"**
4. La app aparecerá como icono en el móvil

## 🍎 Instalar en iPhone / iPad
1. Abre **Safari** (obligatorio, no Chrome) y ve a la URL
2. Toca el botón **compartir** (cuadrado con flecha ↑)
3. Desplázate y toca **"Añadir a pantalla de inicio"**
4. Toca **"Añadir"**
5. La app aparecerá como icono en el iPhone

---

## ✅ Checklist antes de publicar
- [ ] Code.gs desplegado como Web App en Apps Script
- [ ] URL del Web App copiada en index.html (CONFIG.APPS_SCRIPT_URL)
- [ ] DEMO_MODE: false en index.html
- [ ] Todos los archivos subidos a GitHub
- [ ] GitHub Pages activado
