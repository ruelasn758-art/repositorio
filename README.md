# Portafolio | Jimena Maryori Trujillo Mamani

Portafolio digital de evidencias del curso **Neuropedagogía y Desarrollo Humano**.
Sitio estático (HTML + CSS + JavaScript), listo para subir a GitHub y publicar gratis en Netlify.

## Estructura

```
portafolio-jimena/
├── index.html                  ← página principal (textos personales)
├── styles.css                  ← diseño y colores
├── app.js                      ← unidades, sesiones, comentarios críticos y enlaces
├── silabo-neuropedagogia.pdf   ← sílabo del curso
├── netlify.toml                ← configuración para Netlify
└── images/
    ├── jimena1.jpg             ← foto de portada
    ├── jimena2.jpg             ← foto de "Sobre mí"
    └── jimena3.jpg             ← foto pequeña (tarjeta)
```

## Qué personalizar

- En `index.html`, busca los comentarios `✏️ EDITA`: carrera, presentación, valores, hobbies, actividades y expectativa del curso.
- En `app.js`: el comentario crítico de cada sesión y los enlaces de recursos.
- Para cambiar una foto, reemplaza el archivo en `images/` usando **el mismo nombre**.

## Subir a GitHub

1. Entra a github.com → **New repository** → ponle un nombre (por ejemplo `portafolio-jimena`) → **Create repository**.
2. Haz clic en **uploading an existing file**.
3. Descomprime el .zip y arrastra **el contenido de la carpeta** (index.html, styles.css, app.js, la carpeta images, etc.), no la carpeta completa.
4. Haz clic en **Commit changes**.

## Publicar en Netlify

1. Entra a app.netlify.com e inicia sesión con tu cuenta de GitHub.
2. **Add new site → Import an existing project → GitHub** y elige tu repositorio.
3. Deja **Build command** vacío y **Publish directory** como `.` (ya viene configurado en `netlify.toml`).
4. Haz clic en **Deploy**. En unos segundos tendrás tu URL `https://algo.netlify.app`.
5. Para un nombre más bonito: **Site configuration → Change site name** (por ejemplo `portafolio-jimena`).

Cada vez que edites un archivo en GitHub, Netlify actualizará la página automáticamente.
