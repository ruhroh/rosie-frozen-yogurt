# Rosie's Frozen Yogurt Website

A modern, responsive website for Martha's Vineyard's first and only self-serve frozen yogurt shop.

## 🍦 Features

- **Modern Design**: Clean, contemporary styling with vibrant frozen yogurt-themed colors
- **Fully Responsive**: Optimized for all devices from mobile to desktop
- **Interactive Elements**: Smooth animations, hover effects, and engaging user interactions
- **Accessibility**: Full keyboard navigation support and screen reader friendly
- **Performance Optimized**: Fast loading times with optimized assets
- **Contact Form**: Functional contact form with validation and user feedback

## 🚀 Quick Start

### Local Development

1. Clone the repository:
```bash
git clone https://github.com/username/rosies-frozen-yogurt.git
cd rosies-frozen-yogurt
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

The site will open automatically at `http://localhost:8080`

### Railway Deployment

This project is configured for one-click deployment on Railway:

[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/new/template/your-template-id)

Or deploy manually:

1. Connect your GitHub repository to Railway
2. Railway will automatically detect the Node.js project
3. The site will be built and deployed using the configuration in `package.json`

## 📁 Project Structure

```
rosies-frozen-yogurt/
├── index.html          # Main HTML file
├── styles.css          # CSS styling and animations
├── script.js           # JavaScript functionality
├── package.json        # Node.js dependencies and scripts
├── README.md           # This file
└── .gitignore         # Git ignore rules
```

## 🎨 Design Features

- **Color Palette**: Pink (#e91e63), Cyan (#00bcd4), Orange (#ff9800), Yellow (#ffeb3b)
- **Typography**: Poppins for body text, Dancing Script for brand name
- **Modern CSS**: Grid layouts, Flexbox, CSS custom properties
- **Smooth Animations**: CSS keyframes and JavaScript-powered interactions
- **Mobile-First**: Responsive design that works perfectly on all devices

## 🛠️ Technology Stack

- **HTML5**: Semantic markup with accessibility features
- **CSS3**: Modern styling with custom properties, grid, and flexbox
- **Vanilla JavaScript**: No frameworks - pure, optimized JavaScript
- **Google Fonts**: Poppins and Dancing Script font families
- **HTTP Server**: Simple Node.js static file server for deployment

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🔧 Customization

### Colors
Modify the CSS custom properties in `styles.css`:

```css
:root {
    --primary-pink: #e91e63;
    --secondary-cyan: #00bcd4;
    --accent-orange: #ff9800;
    /* Add your custom colors here */
}
```

### Content
Update the content directly in `index.html` or modify the JavaScript in `script.js` for dynamic functionality.

### Styling
All styles are contained in `styles.css` with organized sections for easy modification.

## 📧 Contact Form

The contact form includes:
- Client-side validation
- Success/error messaging
- Loading states
- Keyboard accessibility

**Note**: The form currently uses a simulation function. Replace the `simulateFormSubmission()` function in `script.js` with your actual backend endpoint.

## 🚀 Performance

- Optimized CSS and JavaScript
- Lazy loading ready (for when images are added)
- Debounced scroll handlers
- Efficient animations with CSS transforms
- Minimal dependencies

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🏪 About Rosie's

Rosie's Frozen Yogurt is Martha's Vineyard's first and only self-serve frozen yogurt shop, featuring eight delicious flavors and over thirty toppings. Walk right in, grab a cup or a cone and make yourself a masterpiece!

---

Made with 💖 for Martha's Vineyard's sweetest destination.