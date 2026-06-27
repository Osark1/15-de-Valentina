# 👑 XV Años · Angie Valentina — Sitio Web de Invitación

Sitio web elegante de invitación de quinceañera, 100% compatible con **GitHub Pages**.

## 📁 Estructura de archivos

```
angie-xv/
├── index.html          ← Página principal (invitación pública)
├── admin/
│   └── index.html      ← Panel de administración
├── assets/
│   ├── bg.jpg          ← ⚠️ IMAGEN DE FONDO (debes agregar tú)
│   └── music.mp3       ← ⚠️ MÚSICA DE FONDO (debes agregar tú)
└── README.md
```

---

## 🚀 Cómo publicar en GitHub Pages

1. **Crea un repositorio** en GitHub (ej: `xv-angie-valentina`)
2. **Sube todos los archivos** a la rama `main`
3. Ve a **Settings → Pages**
4. En "Source" selecciona: **Deploy from a branch → main → / (root)**
5. ¡Listo! Tu sitio estará en: `https://tuusuario.github.io/xv-angie-valentina`

---

## 🖼️ Cómo agregar la imagen de fondo

1. Coloca tu foto en la carpeta `assets/` con el nombre `bg.jpg`
2. Tamaño recomendado: **1920×1080px o mayor**
3. La imagen se verá oscurecida automáticamente para que el texto sea legible

---

## 🎵 Cómo agregar la música

1. Coloca tu archivo de audio en `assets/music.mp3`
2. Formatos compatibles: `.mp3`, `.ogg`, `.wav`
3. Si usas otro nombre o formato, edita en `index.html`:
   ```html
   <source src="assets/TU_ARCHIVO.mp3" type="audio/mpeg">
   ```

---

## 📋 Funcionalidades

### Página pública (index.html)
- ✅ Intro con consentimiento de audio
- ✅ Partículas doradas animadas de fondo
- ✅ Hero con imagen de fondo elegante
- ✅ Cuenta regresiva en vivo hasta el 18 de julio
- ✅ Mensaje personal de Angie
- ✅ Galería de fotos (agregar desde el navegador, se guarda en localStorage)
- ✅ Detalles del evento
- ✅ Paleta de código de vestimenta
- ✅ Formulario RSVP (nombre, teléfono, email, cuántos asisten)
- ✅ Animaciones de scroll reveal en todos los elementos
- ✅ Diseño 100% responsive

### Panel Admin (admin/index.html)
- ✅ Dashboard con estadísticas (confirmados, declinados, total personas)
- ✅ Lista completa de invitados con búsqueda y filtros
- ✅ Eliminar invitados individuales o todos
- ✅ **Generador de invitaciones personalizadas** (con vista previa visual + texto para copiar y enviar por WhatsApp/email)
- ✅ Exportar lista en CSV (Excel) y JSON
- ✅ Importar datos desde JSON
- ✅ Acceso desde el botón "⚙ Admin" en la página principal

---

## 💾 Almacenamiento de datos

Los datos se guardan en **localStorage** del navegador, lo que los hace:
- Completamente **gratuitos** (sin servidor)
- **Compatibles con GitHub Pages**
- **Privados** (solo accesibles desde ese dispositivo/navegador)

> **Tip:** Para no perder los datos, usa siempre el mismo navegador para administrar. Puedes exportar en CSV/JSON como respaldo.

---

## 📤 Cómo enviar invitaciones

1. Ve a `admin/index.html` → pestaña **"Generar Invitación"**
2. Escribe el nombre del invitado y un mensaje personalizado
3. Agrega la URL de tu sitio en GitHub Pages
4. Haz clic en **"⎘ Copiar texto"**
5. Pégalo en WhatsApp, Instagram DM, email o SMS

---

## ✏️ Personalización rápida

| Qué cambiar | Dónde está |
|---|---|
| Fecha del evento | `index.html` línea con `2026-07-18T19:00:00` |
| Hora del evento | `index.html` sección "details" |
| Lugar del evento | `index.html` tarjeta de detalles |
| Color principal | Cambiar `--gold` y `--sapphire` en `:root` |
| Nombre de la quinceañera | Ya está escrito "Angie Valentina" en todo el sitio |

---

*Hecho con 💎 y elegancia para el día más especial*
