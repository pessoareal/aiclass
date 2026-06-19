# Vila Mariana Bakery & Café Website

A beautiful, bilingual (Portuguese/English) website for Vila Mariana Bakery & Café built with React, Vite, and Tailwind CSS.

## Features

- ✨ Responsive design (mobile-first)
- 🌐 Bilingual support (PT/EN)
- 🎨 Modern UI with Tailwind CSS
- ♿ Accessibility features
- 📱 Mobile-optimized navigation
- 🔍 SEO-friendly
- ⚡ Fast performance with Vite

## Getting Started

### Prerequisites
- Node.js 16+ and npm

### Installation

1. Install dependencies:
```bash
npm install
```

2. Run development server:
```bash
npm run dev
```

3. Build for production:
```bash
npm run build
```

## Deployment Options

### Option 1: Vercel (Recommended - Free)
1. Go to [vercel.com](https://vercel.com)
2. Import this repository
3. Select the default settings and deploy
4. Your site will be live instantly!

### Option 2: Netlify
1. Go to [netlify.com](https://netlify.com)
2. Connect your GitHub repository
3. Set build command: `npm run build`
4. Set publish directory: `dist`
5. Deploy!

### Option 3: GitHub Pages
1. Update `package.json` with your repo name:
```json
{
  "homepage": "https://pessoareal.github.io/aiclass"
}
```
2. Install gh-pages: `npm install --save-dev gh-pages`
3. Add deployment scripts to `package.json`
4. Run: `npm run deploy`

## Project Structure

```
├── index.html          # HTML entry point
├── src/
│   ├── App.jsx        # Main React component
│   ├── main.jsx       # React entry point
│   └── index.css      # Global styles
├── vite.config.js     # Vite configuration
├── tailwind.config.js # Tailwind CSS configuration
└── package.json       # Dependencies
```

## Customization

All text and configuration is in `src/App.jsx` in the `CONFIG` object:
- Business info
- Navigation items
- Hero section
- Menu items
- Contact details
- etc.

Simply edit the values and your site updates automatically!

## Technologies

- **React 18** - UI library
- **Vite** - Build tool
- **Tailwind CSS** - Styling
- **PostCSS** - CSS processing

## License

© 2024 Vila Mariana Bakery & Café. All rights reserved.
