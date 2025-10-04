# Blog Personal de Kevin

Un blog personal desarrollado con **Next.js** que demuestra las mejores prácticas de desarrollo web moderno, incluyendo renderizado estático, rutas dinámicas y optimización de imágenes.

## 📋 Descripción del Proyecto

Este es un blog personal que utiliza Next.js como framework principal, diseñado para mostrar artículos y contenido personal. El proyecto implementa:

- **Static Site Generation (SSG)** para páginas optimizadas
- **Server-Side Rendering (SSR)** cuando es necesario
- **Rutas dinámicas** para artículos individuales
- **Procesamiento de Markdown** para contenido de blog
- **Optimización de imágenes** con Next.js Image
- **Estilos con CSS Modules y Tailwind CSS**

## 👨‍💻 Autor

**Kevin** - Desarrollador Web

Este blog personal fue creado como parte del aprendizaje de Next.js, implementando las mejores prácticas de desarrollo moderno.

## 🚀 Características Principales

- ✅ **Renderizado Estático**: Páginas pre-renderizadas para máximo rendimiento
- ✅ **Blog con Markdown**: Artículos escritos en formato Markdown
- ✅ **Rutas Dinámicas**: URLs amigables para cada artículo (`/posts/[id]`)
- ✅ **Optimización SEO**: Meta tags y Open Graph configurados
- ✅ **Responsive Design**: Diseño adaptable a todos los dispositivos
- ✅ **CSS Modules**: Estilos encapsulados y reutilizables
- ✅ **Tailwind CSS**: Framework de utilidades para estilos rápidos

## 🛠️ Tecnologías Utilizadas

- **Next.js** - Framework de React para producción
- **React** - Biblioteca de interfaz de usuario
- **Markdown** - Formato de contenido de blog
- **gray-matter** - Procesamiento de metadatos de Markdown
- **remark** - Procesador de Markdown a HTML
- **date-fns** - Utilidades para manejo de fechas
- **Tailwind CSS** - Framework de CSS utilitario
- **CSS Modules** - Estilos con scope local

## 📁 Estructura del Proyecto

```
nextjs-blog/
├── components/          # Componentes reutilizables
│   ├── date.js         # Componente para formatear fechas
│   ├── layout.js       # Layout principal del sitio
│   └── layout.module.css
├── lib/                # Utilidades y funciones
│   └── posts.js        # Lógica para procesar posts
├── pages/              # Páginas de la aplicación
│   ├── api/            # API routes
│   ├── posts/          # Páginas dinámicas de posts
│   ├── _app.js         # Configuración global de la app
│   ├── index.js        # Página principal
│   └── 404.js          # Página de error 404
├── posts/              # Contenido del blog en Markdown
│   ├── pre-rendering.md
│   └── ssg-ssr.md
├── public/             # Archivos estáticos
│   ├── images/         # Imágenes del sitio
│   └── favicon.ico
└── styles/             # Estilos globales
    ├── global.css
    ├── Home.module.css
    └── utils.module.css
```

## 🚀 Instalación y Uso

### Prerrequisitos

- Node.js 18 o superior
- npm, yarn o pnpm

### Pasos de Instalación

1. **Clonar el repositorio**
   ```bash
   git clone [URL_DEL_REPOSITORIO]
   cd nextjs-blog
   ```

2. **Instalar dependencias**
   ```bash
   npm install
   # o
   yarn install
   # o
   pnpm install
   ```

3. **Ejecutar en modo desarrollo**
   ```bash
   npm run dev
   # o
   yarn dev
   # o
   pnpm dev
   ```

4. **Abrir en el navegador**
   ```
   http://localhost:3000
   ```

### Scripts Disponibles

- `npm run dev` - Ejecuta el servidor de desarrollo
- `npm run build` - Construye la aplicación para producción
- `npm run start` - Ejecuta la aplicación en modo producción

## 📝 Cómo Agregar Nuevos Posts

1. Crear un nuevo archivo `.md` en la carpeta `posts/`
2. Agregar metadatos en formato YAML al inicio del archivo:
   ```markdown
   ---
   title: 'Título del Post'
   date: '2024-01-01'
   ---
   
   Contenido del post en Markdown...
   ```
3. El post aparecerá automáticamente en la página principal

## 🌐 Despliegue

Este proyecto está optimizado para desplegarse en plataformas como:

- **Vercel** (recomendado para Next.js)
- **Netlify**
- **GitHub Pages**
- **Cualquier servidor Node.js**

### Despliegue en Vercel

1. Conectar el repositorio a Vercel
2. Configurar automáticamente con las configuraciones por defecto
3. ¡Listo! El sitio estará disponible en línea

## 📚 Recursos de Aprendizaje

- [Documentación oficial de Next.js](https://nextjs.org/docs)
- [Tutorial de Next.js](https://nextjs.org/learn)
- [Guía de Markdown](https://www.markdownguide.org/)

## 📄 Licencia

Este proyecto es de código abierto y está disponible bajo la [Licencia MIT](LICENSE).

## 🌍 Idiomas / Languages

- **Español** - Este README
- **English** - [README_EN.md](README_EN.md)

---

**Desarrollado con ❤️ por Kevin usando Next.js**
