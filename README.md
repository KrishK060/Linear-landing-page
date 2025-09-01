# Linear Landing Page with Tailwind CSS

This project demonstrates a proper integration of Tailwind CSS with npm build tools.

## 🚀 Quick Start

### Prerequisites
- Node.js (v14 or higher)
- npm

### Installation & Setup

1. **Install dependencies:**
   ```bash
   npm install
   ```

2. **Build CSS once:**
   ```bash
   npm run build:css
   ```

3. **Start development mode (watch for changes):**
   ```bash
   npm run dev
   ```

4. **Open `index.html` in your browser**

## 📁 Project Structure

```
linear-landing-page/
├── index.html              # Main HTML file
├── src/
│   ├── input.css          # Tailwind directives
│   └── output.css         # Compiled CSS (generated)
├── tailwind.config.js     # Tailwind configuration
├── postcss.config.js      # PostCSS configuration
└── package.json           # Dependencies and scripts
```

## 🛠️ Available Scripts

- `npm run build:css` - Build CSS once
- `npm run build:css:watch` - Build CSS and watch for changes
- `npm run dev` - Start development mode (watch mode)

## 🔧 How It Works

1. **Tailwind CSS v4** is installed as a dev dependency
2. **@tailwindcss/cli** provides the build tools
3. **PostCSS** processes the CSS with autoprefixer
4. **input.css** contains Tailwind directives
5. **output.css** is the compiled, optimized CSS file

## 📝 Tailwind Directives

The `src/input.css` file contains:
```css
@tailwind base;
@tailwind components;
@tailwind utilities;
```

## 🎨 Customization

- Edit `tailwind.config.js` to customize themes, colors, and plugins
- Modify `src/input.css` to add custom CSS
- Run `npm run build:css` after any changes

## 🌐 Browser Support

The compiled CSS includes autoprefixer for better browser compatibility.

## 📚 Resources

- [Tailwind CSS Documentation](https://tailwindcss.com/docs)
- [Tailwind CSS v4 Guide](https://tailwindcss.com/docs/installation)
- [PostCSS Documentation](https://postcss.org/)
