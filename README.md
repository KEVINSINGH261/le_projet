# DevAgency - Showcase Website

A modern, responsive showcase website for a web development agency built with [Astro](https://astro.build/).

## 🚀 About

DevAgency is a professional web development agency specializing in creating stunning websites for:
- 🍽️ Restaurants (online menus, reservations, ordering systems)
- 🏢 Business websites (corporate sites, service businesses)
- 🛒 E-commerce solutions (online stores with payment processing)
- ⚡ Custom web applications (tailored solutions)

## ✨ Features

- **Modern Design**: Beautiful purple gradient theme with smooth animations
- **Fully Responsive**: Works perfectly on desktop, tablet, and mobile devices
- **Fast Performance**: Built with Astro for optimal static site generation
- **SEO Optimized**: Clean semantic HTML and meta tags
- **Easy to Customize**: Well-organized code structure

## 🛠️ Project Structure

```
/
├── public/             # Static assets (favicon, images)
├── src/
│   ├── layouts/       # Layout components
│   │   └── Layout.astro
│   └── pages/         # Page components
│       └── index.astro
├── astro.config.mjs   # Astro configuration
├── package.json       # Project dependencies
└── tsconfig.json      # TypeScript configuration
```

## 🚦 Getting Started

### Prerequisites

- Node.js 18+ 
- npm or yarn

### Installation

```bash
# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

The development server will start at `http://localhost:4321/`

## 📝 Customization

### Changing Colors

Edit the CSS variables in `src/layouts/Layout.astro`:

```css
:root {
  --primary-color: #2563eb;
  --secondary-color: #1e40af;
  /* ... more variables */
}
```

### Modifying Content

All content is in `src/pages/index.astro`. Edit the sections:
- Hero section
- Services
- Portfolio
- About
- Contact

### Adding Pages

Create new `.astro` files in `src/pages/` directory.

## 📄 License

This project is open source and available for use.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

