# Nuxt Portfolio

A modern, responsive portfolio website built with Nuxt 3, featuring server-side rendering, internationalization, and a contact form integration.

This repository contains my personal portfolio website built with Nuxt 3. 
It showcases my projects, skills, and experience as a **Fullstack Developer**.

## 🌐 Live Demo

Check out the live site: [hannarembiaszdevportfolio.vercel.app](https://hannarembiaszdevportfolio.vercel.app/)

## Features

- 🌟 **Modern Stack**: Built with Nuxt 3
- 🎨 **UI Framework**: Nuxt UI for beautiful components
- 🌍 **Internationalization**: Full bilingual support (English/Polish) using `@nuxtjs/i18n`
- 📱 **Responsive Design**: Mobile-first approach with custom SCSS styling
- 📧 **Contact Form**: Integrated EmailJS for form submissions with validation
- 🖼️ **Image Optimization**: WebP/AVIF support with fallbacks
- 📊 **Project Showcases**: Interactive carousels with Embla Carousel
- 🚀 **SEO Optimized**: Meta tags, sitemap, and robots.txt
- ⚡ **Performance**: Server-side rendering with static site generation

## Tech Stack

### Frontend
- **Nuxt 3** - Full-stack Vue framework
- **Nuxt UI** - Component library
- **SCSS** - Enhanced CSS with variables and mixins

### Libraries & Integrations
- **@nuxtjs/i18n** - Internationalization
- **EmailJS** - Contact form email service
- **Embla Carousel** - Touch-friendly carousels
- **Joi** - Form validation
- **@nuxtjs/sitemap** - Automatic sitemap generation
- **@nuxtjs/robots** - Robots.txt management

## Project Structure

```
├── components/           # Vue components
│   ├── about/           # About page components
│   ├── project/         # Project-related components
│   ├── contact-form.vue # Contact form with validation
│   └── ...
├── composables/         # Vue composables
│   ├── useLanguage.ts   # Language management
│   ├── useValidationSchema.ts # Form validation
│   └── useCreateCads.ts  # Project data management
├── pages/               # File-based routing
│   ├── index.vue        # Homepage
│   ├── about.vue        # About page
│   ├── contact.vue      # Contact page
│   └── projects/        # Project pages
├── i18n/               # Internationalization
│   └── locales/        # Translation files (en.json, pl.json)
├── assets/             # Static assets
│   ├── styles/         # SCSS files
│   └── fonts/          # Custom fonts
├── public/             # Public static files
│   ├── images/         # Optimized images
│   └── svg/            # SVG icons
└── layouts/            # Layout components
```

## Setup

Install dependencies:

```bash
npm install
# or
pnpm install
# or
yarn install
```

## Environment Variables

Create a `.env` file based on `.env.example`:

```bash
NUXT_PUBLIC_SITE_URL=https://your-domain.com
NUXT_PUBLIC_EMAILJS_SERVICE_ID=your_service_id
NUXT_PUBLIC_EMAILJS_TEMPLATE_ID=your_template_id
NUXT_PUBLIC_EMAILJS_PUBLIC_KEY=your_public_key
```

## Development

Start the development server on `http://localhost:3000`:

```bash
npm run dev
# or
pnpm dev
# or
yarn dev
```

## Build & Deployment

### Local Production Build

```bash
npm run build
npm run preview
```

### Deploy to Vercel

1. **Connect Repository**: Link your GitHub repository to Vercel
2. **Configure Environment Variables**: Add your environment variables in Vercel dashboard
3. **Deploy**: Vercel will automatically build and deploy your application

#### Vercel Configuration

The application is optimized for Vercel deployment with:
- Automatic builds on git push
- Server-side rendering (SSR) support
- Automatic HTTPS and CDN distribution

#### Build Settings for Vercel

```bash
Build Command: npm run build
Output Directory: .output
Install Command: npm install
```

## Features Overview

### Internationalization
- Automatic language detection
- Route-based localization (`/en`, `/pl`)
- Dynamic content translation
- Language switcher component

### Contact Form
- Form validation with Joi
- EmailJS integration
- Real-time error handling
- Accessibility features (ARIA labels, screen reader support)

### Project Showcase
- Interactive image carousels
- Responsive image optimization
- Dynamic project data loading
- SEO-friendly project pages

### Performance Optimizations
- Server-side rendering
- Image format optimization (WebP/AVIF)
- Lazy loading
- Minified assets
- Automatic sitemap generation

### Accessibility Features
- **WCAG Compliant**: Semantic HTML structure and proper heading hierarchy
- **Keyboard Navigation**: Full keyboard support for all interactive elements
- **Screen Reader Support**: ARIA labels, roles, and live regions
- **Focus Management**: Proper focus handling in mobile menu and modals
- **Color Contrast**: High contrast color scheme for readability
- **Form Accessibility**: Form validation with screen reader announcements
- **Image Alt Text**: Dynamic alt text in multiple languages

## License

Public repository, proprietary code.

## Author

**Hanna Rembiasz** - Frontend Developer
- GitHub: [@HannaRembiasz](https://github.com/HannaRembiasz)
- LinkedIn: [Hanna Rembiasz](https://www.linkedin.com/in/hanna-rembiasz/)