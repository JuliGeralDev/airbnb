# 🏠 AirBNB – BEM Project

AirBNB is a *study project* developed as part of a front-end learning journey. It is a fully responsive website inspired by the design and structure of AirBNB. The site is styled using **SASS**, structured with **CSS Grid**, and automated using **Gulp**. The project follows the **BEM (Block Element Modifier)** methodology to ensure clean and scalable CSS class naming.

> ⚠️ Note: This is a front-end prototype created for educational purposes. It does not include dynamic or backend functionality.

## 🔗 Live Preview

[👉 View the Demo on Netlify](https://airbnb-juligeraldev.netlify.app/)

## ✨ Features

- Responsive Design for all screen sizes using media queries  
- BEM Methodology for clean and maintainable class naming  
- Modular SCSS Architecture with reusable variables and components  
- CSS Grid for flexible and modern layouts  
- Gulp Automation for:
  - Compiling and minifying SCSS  
  - Optimizing images and generating WebP/AVIF formats  
  - Autoprefixing for browser compatibility  
  - Creating sourcemaps for easier debugging

## 📁 Project Structure

airbnb/  
├── src/  
│   ├── scss/  
│   │   ├── base/        # Variables, mixins, normalize, typography  
│   │   ├── ui/          # UI components (header, content, footer)  
│   │   └── app.scss     # SCSS entry point  
│   ├── img/             # Source images  
│   └── index.html       # Main HTML file  
├── build/  
│   ├── css/             # Compiled and minified CSS  
│   ├── img/             # Optimized image assets  
├── gulpfile.js          # Gulp configuration  
├── package.json         # Project dependencies and scripts  
└── .gitignore           # Git ignore configuration

## 🛠️ Technologies Used

- HTML5 – Semantic structure  
- SCSS (SASS) – Modular styling with reusable components  
- CSS Grid – Modern layout system  
- Gulp – Task automation for a smooth workflow  
- Autoprefixer – Ensures compatibility with older browsers  
- CSSNano – CSS minifier for reduced file size  
- Imagemin / WebP / AVIF – Image optimization and format generation

## ⚙️ Installation

To run the project locally:

1. Clone the repository  
   git clone https://github.com/your-repo/airbnb.git  
   cd airbnb

2. Install dependencies  
   npm install

3. Start the development environment  
   npm run dev

This will:  
- ✅ Compile SCSS into minified CSS  
- ✅ Optimize images and generate WebP/AVIF formats  
- ✅ Watch for changes and recompile automatically

## 🎨 SCSS Structure

base/  
- _variables.scss – Color palette, typography, spacing  
- _mixins.scss – Media queries and reusable logic  
- _normalize.scss – CSS reset for consistency  
- _globales.scss – Base element styling

ui/  
- Component styles such as header, content sections, and footer

## 🔁 Gulp Tasks

- CSS Compilation – Converts SCSS to CSS with autoprefixing and minification  
- Image Optimization – Compresses and converts images to modern formats  
- Watch Mode – Automatically rebuilds on file changes

## 👩‍💻 Author

Juliana García Corredor  
GitHub: @JuliGeralDev

## 📝 Notes

- Make sure Node.js and npm are installed on your system  
- The `/build` folder is auto-generated and ignored in Git
