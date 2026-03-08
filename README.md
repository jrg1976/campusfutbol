# CampusFútbol 🏟️

**El mayor agregador de campus de fútbol de España.**

---

## 🚀 Cómo publicar en 10 minutos

### Paso 1 · Subir a GitHub

1. Ve a [github.com](https://github.com) → New repository
2. Nombre: `campusfutbol`
3. Visibility: **Public** (necesario para Netlify gratis)
4. Click **Create repository**

Luego, en tu terminal (o GitHub Desktop):
```bash
git init
git add .
git commit -m "feat: campus-v1 primera versión"
git branch -M main
git remote add origin https://github.com/TU_USUARIO/campusfutbol.git
git push -u origin main
```

---

### Paso 2 · Conectar con Netlify

1. Ve a [netlify.com](https://netlify.com) → Sign up (gratis con GitHub)
2. Click **Add new site → Import an existing project**
3. Conecta tu cuenta de GitHub
4. Selecciona el repositorio `campusfutbol`
5. Configuración de build:
   - **Build command**: *(dejar vacío)*
   - **Publish directory**: `.`
6. Click **Deploy site**

✅ En menos de 60 segundos tu web estará en una URL como `amazing-name-123.netlify.app`

---

### Paso 3 · Conectar tu dominio (opcional)

1. En Netlify → Domain management → Add custom domain
2. Escribe `campus-futbol.es`
3. Netlify te dará los DNS records
4. Configúralos en donde compraste el dominio
5. SSL automático con Let's Encrypt

---

## 📁 Estructura del proyecto

```
campusfutbol/
├── index.html       ← La web completa (todo en un archivo)
├── netlify.toml     ← Configuración de Netlify
└── README.md        ← Este archivo
```

## 🔄 Flujo de trabajo

Para actualizar la web:
1. Edita `index.html` (con VS Code o con IA)
2. `git add . && git commit -m "descripción del cambio"`
3. `git push`
4. Netlify detecta el cambio y publica automáticamente ✅

## 📊 Versiones

| Versión | Descripción |
|---------|-------------|
| v1.0    | Web con filtros + datos de ejemplo |
| v2.0    | (próxima) Datos reales de campus |
| v3.0    | (próxima) Automatización con Make.com |

---

*CampusFútbol · Marzo 2026*
