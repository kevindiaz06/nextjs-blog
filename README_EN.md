# Kevin's Personal Blog

A personal blog developed with **Next.js** that demonstrates modern web development best practices, including static rendering, dynamic routes, and image optimization.

## 📋 Project Description

This is a personal blog that uses Next.js as the main framework, designed to showcase articles and personal content. The project implements:

- **Static Site Generation (SSG)** for optimized pages
- **Server-Side Rendering (SSR)** when needed
- **Dynamic Routes** for individual articles
- **Markdown Processing** for blog content
- **Image Optimization** with Next.js Image
- **Styling with CSS Modules and Tailwind CSS**

## 👨‍💻 Author

**Kevin** - Web Developer

This personal blog was created as part of Next.js learning, implementing modern development best practices.

## 🚀 Main Features

- ✅ **Static Rendering**: Pre-rendered pages for maximum performance
- ✅ **Markdown Blog**: Articles written in Markdown format
- ✅ **Dynamic Routes**: SEO-friendly URLs for each article (`/posts/[id]`)
- ✅ **SEO Optimization**: Meta tags and Open Graph configured
- ✅ **Responsive Design**: Design adaptable to all devices
- ✅ **CSS Modules**: Encapsulated and reusable styles
- ✅ **Tailwind CSS**: Utility framework for quick styling

## 🛠️ Technologies Used

- **Next.js** - React framework for production
- **React** - User interface library
- **Markdown** - Blog content format
- **gray-matter** - Markdown metadata processing
- **remark** - Markdown to HTML processor
- **date-fns** - Date handling utilities
- **Tailwind CSS** - CSS utility framework
- **CSS Modules** - Scoped local styles

## 📁 Project Structure

```
nextjs-blog/
├── components/          # Reusable components
│   ├── date.js         # Date formatting component
│   ├── layout.js       # Main site layout
│   └── layout.module.css
├── lib/                # Utilities and functions
│   └── posts.js        # Posts processing logic
├── pages/              # Application pages
│   ├── api/            # API routes
│   ├── posts/          # Dynamic post pages
│   ├── _app.js         # Global app configuration
│   ├── index.js        # Home page
│   └── 404.js          # 404 error page
├── posts/              # Blog content in Markdown
│   ├── pre-rendering.md
│   └── ssg-ssr.md
├── public/             # Static files
│   ├── images/         # Site images
│   └── favicon.ico
└── styles/             # Global styles
    ├── global.css
    ├── Home.module.css
    └── utils.module.css
```

## 🚀 Installation and Usage

### Prerequisites

- Node.js 18 or higher
- npm, yarn or pnpm

### Installation Steps

1. **Clone the repository**
   ```bash
   git clone [REPOSITORY_URL]
   cd nextjs-blog
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   # or
   pnpm install
   ```

3. **Run in development mode**
   ```bash
   npm run dev
   # or
   yarn dev
   # or
   pnpm dev
   ```

4. **Open in browser**
   ```
   http://localhost:3000
   ```

### Available Scripts

- `npm run dev` - Runs the development server
- `npm run build` - Builds the application for production
- `npm run start` - Runs the application in production mode

## 📝 How to Add New Posts

1. Create a new `.md` file in the `posts/` folder
2. Add metadata in YAML format at the beginning of the file:
   ```markdown
   ---
   title: 'Post Title'
   date: '2024-01-01'
   ---
   
   Post content in Markdown...
   ```
3. The post will automatically appear on the home page

## 🌐 Deployment

This project is optimized for deployment on platforms like:

- **Vercel** (recommended for Next.js)
- **Netlify**
- **GitHub Pages**
- **Any Node.js server**

### Deploy to Vercel

1. Connect the repository to Vercel
2. Configure automatically with default settings
3. Ready! The site will be available online

## 📚 Learning Resources

- [Official Next.js Documentation](https://nextjs.org/docs)
- [Next.js Tutorial](https://nextjs.org/learn)
- [Markdown Guide](https://www.markdownguide.org/)

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🌍 Languages / Idiomas

- **English** - This README
- **Español** - [README.md](README.md)

---

**Developed with ❤️ by Kevin using Next.js**
