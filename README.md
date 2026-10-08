# 🌐 Nuxt Portfolio — Developer Portfolio

A personal developer portfolio built with **Nuxt**, showcasing my projects, technical skills, and professional experience as a Fullstack Developer.

The website features bilingual content (English and Polish), responsive layouts, interactive project showcases, and a contact form integrated with EmailJS.

---

## 🚀 Live Demo

**[View Live Portfolio](https://hannarembiaszdevportfolio.vercel.app/)**

Deployed on **Vercel**.

---

## ✨ Features

- **Internationalization** — English and Polish content powered by `@nuxtjs/i18n`, with localized routes and a language switcher
- **Project Showcase** — dedicated project pages with interactive image carousels
- **Contact Form** — EmailJS integration with Joi validation and error handling
- **Responsive Design** — mobile-first layouts with custom SCSS styling
- **Image Optimization** — WebP/AVIF support, fallbacks, and lazy loading
- **SEO** — metadata, sitemap generation, and robots.txt configuration
- **Accessibility** — semantic HTML, keyboard navigation, ARIA attributes, and accessible form feedback
- **Server-Side Rendering (SSR)** — powered by Nuxt

---

## 🛠️ Tech Stack

### Core Technologies

- **Nuxt** — Vue-based application framework
- **Vue 3** — frontend framework
- **Nuxt UI** — UI component library
- **SCSS** — custom styling with variables and mixins

### Libraries & Integrations

- **@nuxtjs/i18n** — internationalization
- **EmailJS** — contact form email service
- **Embla Carousel** — interactive project carousels
- **Joi** — form validation
- **@nuxtjs/sitemap** — sitemap generation
- **@nuxtjs/robots** — robots.txt management

### Deployment

- **Vercel** — hosting and deployment

---

## 📁 Project Structure

```text
├── components/                  # Vue components
│   ├── about/                   # About page components
│   ├── project/                 # Project-related components
│   ├── contact-form.vue         # Contact form with validation
│   └── ...
├── composables/                 # Vue composables
│   ├── useLanguage.ts           # Language management
│   ├── useValidationSchema.ts   # Form validation
│   └── useCreateCads.ts         # Project data management
├── pages/                       # File-based routing
│   ├── index.vue                # Homepage
│   ├── about.vue                # About page
│   ├── contact.vue              # Contact page
│   └── projects/                # Project pages
├── i18n/                        # Internationalization
│   └── locales/                 # Translation files (en.json, pl.json)
├── assets/                      # Static assets
│   ├── styles/                  # SCSS files
│   └── fonts/                   # Custom fonts
├── public/                      # Public static files
│   ├── images/                  # Optimized images
│   └── svg/                     # SVG icons
└── layouts/                     # Layout components
```

---

## ⚙️ Getting Started

### Install Dependencies

```bash
npm install
# or
pnpm install
# or
yarn install
```

### Environment Variables

Create a `.env` file based on `.env.example`:

```env
NUXT_PUBLIC_SITE_URL=https://your-domain.com
NUXT_PUBLIC_EMAILJS_SERVICE_ID=your_service_id
NUXT_PUBLIC_EMAILJS_TEMPLATE_ID=your_template_id
NUXT_PUBLIC_EMAILJS_PUBLIC_KEY=your_public_key
```

### Run in Development Mode

Start the development server at `http://localhost:3000`:

```bash
npm run dev
# or
pnpm dev
# or
yarn dev
```

---

## 🏗️ Build & Deployment

### Local Production Build

```bash
npm run build
npm run preview
```

### Deploy to Vercel

1. **Connect Repository** — link your GitHub repository to Vercel.
2. **Configure Environment Variables** — add the required variables in the Vercel dashboard.
3. **Deploy** — Vercel builds and deploys the application.

### Vercel Configuration

The project supports:

- Automatic builds on Git push
- Server-side rendering (SSR)
- HTTPS and CDN distribution

### Build Settings

```text
Build Command: npm run build
Output Directory: .output
Install Command: npm install
```

---

## ♿ Accessibility

The portfolio incorporates accessibility-focused practices, including:

- Semantic HTML and structured headings
- Keyboard navigation for interactive elements
- ARIA labels, roles, and live regions
- Focus handling in the mobile menu and modals
- Accessible form validation feedback
- Descriptive image alt text in both supported languages

---


## 👩‍💻 Author

- **[GitHub](https://github.com/HannaRembiasz)**
- **[LinkedIn](https://www.linkedin.com/in/hanna-rembiasz/)**
