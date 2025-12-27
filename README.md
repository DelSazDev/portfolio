# 🛡️ SEC_OPS - Portfolio de Ciberseguridad

Portfolio moderno y responsive creado con Astro para mostrar proyectos y conocimientos de ciberseguridad.

## ✨ Características

- **Header fijo** con logo animado y navegación responsive
- **Footer completo** con enlaces y estado de disponibilidad
- **Hero section** con efectos de glitch y animaciones
- **Bloque de código** animado con syntax highlighting
- **Contadores animados** de estadísticas
- **Badges flotantes** con tecnologías
- **Diseño responsive** optimizado para móviles
- **Efectos visuales** como scan line y grid background
- **Tema cyberpunk** con paleta verde neón

## 🚀 Instalación

1. Asegúrate de tener Node.js instalado (versión 18 o superior)

2. Instala las dependencias:
```bash
npm install
```

3. Inicia el servidor de desarrollo:
```bash
npm run dev
```

4. Abre tu navegador en `http://localhost:4321`

## 📦 Scripts Disponibles

```bash
npm run dev      # Inicia el servidor de desarrollo
npm run build    # Construye el proyecto para producción
npm run preview  # Previsualiza la build de producción
```

## 🎨 Personalización

### Colores

Los colores están definidos como variables CSS en `src/layouts/Layout.astro`:

```css
--bg-primary: #0a0c10;      /* Fondo principal */
--bg-secondary: #0f1419;    /* Fondo secundario */
--accent-primary: #00ff9f;  /* Verde neón */
--accent-secondary: #00d9ff; /* Azul cyan */
```

### Fuentes

El proyecto usa:
- **JetBrains Mono** - Para títulos y código
- **Space Mono** - Para texto general

### Contenido

Edita los archivos en `src/pages/` para cambiar el contenido:
- `index.astro` - Página principal
- Puedes crear más páginas como `proyectos.astro`, `blog.astro`, etc.

## 📁 Estructura del Proyecto

```
cybersec-portfolio/
├── src/
│   ├── components/
│   │   ├── Header.astro    # Navegación principal
│   │   └── Footer.astro    # Pie de página
│   ├── layouts/
│   │   └── Layout.astro    # Layout base
│   └── pages/
│       └── index.astro     # Página principal
├── public/                 # Archivos estáticos
├── astro.config.mjs       # Configuración de Astro
└── package.json
```

## 🎯 Próximos Pasos

1. **Crea páginas adicionales**:
   - `src/pages/proyectos.astro` - Lista de proyectos
   - `src/pages/blog.astro` - Blog de artículos
   - `src/pages/contacto.astro` - Formulario de contacto

2. **Añade contenido dinámico**:
   - Usa colecciones de Astro para blog posts
   - Integra un CMS headless

3. **Optimiza imágenes**:
   - Usa el componente `<Image>` de Astro
   - Implementa lazy loading

4. **Deploy**:
   - Vercel: `npm run build` y sube la carpeta `dist/`
   - Netlify: Conecta tu repositorio
   - GitHub Pages: Configura el workflow

## 🛠️ Tecnologías

- [Astro](https://astro.build) - Framework web
- CSS3 - Animaciones y estilos
- TypeScript - Type safety
- Google Fonts - Tipografías

## 📝 Licencia

Este proyecto es de código abierto y está disponible bajo la licencia MIT.

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Si encuentras algún bug o tienes sugerencias, abre un issue o pull request.

---

Creado con 💚 y mucho ☕ por un aprendiz autodidacta de ciberseguridad
