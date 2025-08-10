# 📖 GitHub Pages Setup Guide

Esta guía te ayudará a configurar GitHub Pages para que tu proyecto COSMOS sea accesible públicamente en internet.

## 🚀 Pasos para Activar GitHub Pages

### 1. Sube tu proyecto a GitHub

1. **Crea un repositorio en GitHub**:
   - Ve a [github.com](https://github.com)
   - Haz clic en "New repository"
   - Nombre: `COSMOS_frontend`
   - Descripción: "COSMOS - Navigate the Universe of Inventory Management"
   - Marca como **Público**
   - Haz clic en "Create repository"

2. **Sube el código**:
   ```bash
   cd /Users/anapaulaelizondo/Desktop/COSMOS_frontend
   git init
   git add .
   git commit -m "Initial commit: COSMOS frontend application"
   git branch -M main
   git remote add origin https://github.com/anapaulaelz/COSMOS_frontend.git
   git push -u origin main
   ```

### 2. Configura GitHub Pages

1. **Ve a la configuración del repositorio**:
   - En tu repositorio de GitHub, haz clic en "Settings"
   - Busca la sección "Pages" en el menú lateral izquierdo

2. **Configura la fuente**:
   - **Source**: Selecciona "Deploy from a branch"
   - **Branch**: Selecciona "main"
   - **Folder**: Selecciona "/docs"
   - Haz clic en "Save"

3. **Espera el despliegue**:
   - GitHub construirá tu sitio automáticamente
   - En unos minutos, verás un mensaje verde: "Your site is published at https://anapaulaelz.github.io/COSMOS_frontend"

### 3. Accede a tu Aplicación

Una vez configurado, tu aplicación estará disponible en:
**https://anapaulaelz.github.io/COSMOS_frontend**

#### Credenciales de acceso:
- **Usuario**: `admin`
- **Contraseña**: `admin123`

## 🔧 Configuración Automática

Tu proyecto ya está configurado con:

✅ **Carpeta `docs`**: Contenido web listo para GitHub Pages  
✅ **Archivo `.nojekyll`**: Evita procesamiento Jekyll  
✅ **GitHub Actions**: Despliegue automático en cada push  
✅ **Rutas relativas**: Compatibles con GitHub Pages  
✅ **README actualizado**: Con enlace al sitio en vivo  

## 🔄 Actualizaciones Automáticas

Cada vez que hagas push a la rama `main`, GitHub Pages actualizará automáticamente tu sitio web gracias al archivo de GitHub Actions incluido.

## 🌐 Compartir tu Proyecto

Una vez en línea, puedes compartir tu proyecto enviando el enlace:
**https://anapaulaelz.github.io/COSMOS_frontend**

### URLs Específicas:
- **Página de Login**: https://anapaulaelz.github.io/COSMOS_frontend/
- **Dashboard**: https://anapaulaelz.github.io/COSMOS_frontend/pages/dashboard.html
- **Smart Inventory**: https://anapaulaelz.github.io/COSMOS_frontend/pages/smart-inventory.html
- **Forecasting**: https://anapaulaelizondo.github.io/COSMOS_frontend/pages/demand-forecasting.html

## 🛠️ Solución de Problemas

### Problema: El sitio no carga
- Verifica que el repositorio sea público
- Asegúrate de haber seleccionado la carpeta `/docs` como fuente
- Espera unos minutos para que GitHub procese los cambios

### Problema: Archivos CSS/JS no cargan
- Verifica que las rutas en HTML sean relativas (sin `/` al inicio)
- Asegúrate de que todos los archivos estén en la carpeta `docs`

### Problema: Los cambios no se reflejan
- Haz push de los cambios a la rama `main`
- Espera unos minutos para el despliegue automático
- Limpia la caché del navegador (Ctrl+F5 o Cmd+Shift+R)

## 📱 Características del Sitio

✨ **Responsivo**: Funciona en móviles, tablets y escritorio  
🚀 **Rápido**: Carga optimizada con recursos CDN  
🔒 **Seguro**: Servido a través de HTTPS  
🌍 **Global**: Accesible desde cualquier lugar del mundo  

---

¡Tu aplicación COSMOS ya está lista para explorar el universo del manejo de inventarios! 🌌
