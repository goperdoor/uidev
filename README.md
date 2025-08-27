# DevUI CSS Library

A comprehensive, developer-friendly CSS component library for modern web applications.

## Features

- 🎨 **150+ Components** - Cards, buttons, forms, modals, navigation, and more
- 🎯 **CSS Variables** - Easy customization with CSS custom properties
- 📱 **Responsive Design** - Mobile-first approach with responsive grid system
- ♿ **Accessibility** - WCAG compliant components with proper ARIA attributes
- 🚀 **Performance** - Lightweight and optimized for fast loading
- 📖 **Well Documented** - Comprehensive documentation with live examples
- 🔧 **Developer Friendly** - Clean, semantic class names and consistent API

## Quick Start

### Installation

Add DevUI to your project by including the CSS file:

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/anvithshetty17/devui-css-library/devui-library.css">
```

Or download the CSS file and include it locally:

```html
<link rel="stylesheet" href="path/to/devui-library.css">
```

### Basic Usage

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My App</title>
  <link rel="stylesheet" href="devui-library.css">
</head>
<body>
  <div class="container">
    <div class="card">
      <div class="card-header">Welcome to DevUI</div>
      <div class="card-body">
        <p>Start building beautiful interfaces with our component library.</p>
        <button class="btn btn-primary">Get Started</button>
      </div>
    </div>
  </div>
</body>
</html>
```

## Customization

DevUI uses CSS custom properties for easy theming. Override these variables to match your brand:

```css
:root {
  --primary-color: #your-brand-color;
  --font-family-base: 'Your Font', sans-serif;
  --border-radius-md: 12px;
  --spacing-md: 1.5rem;
}
```

## Components

### Buttons
```html
<button class="btn btn-primary">Primary Button</button>
<button class="btn btn-outline btn-primary">Outline Button</button>
<button class="btn btn-ghost btn-primary">Ghost Button</button>
```

### Cards
```html
<div class="card">
  <div class="card-header">Card Title</div>
  <div class="card-body">
    <p>Card content goes here.</p>
  </div>
  <div class="card-footer">
    <small class="text-muted">Footer text</small>
  </div>
</div>
```

### Forms
```html
<form class="form">
  <div class="form-group">
    <label class="form-label">Email</label>
    <input type="email" class="form-input" placeholder="Enter email">
  </div>
  <button class="btn btn-primary">Submit</button>
</form>
```

### Grid System
```html
<div class="container">
  <div class="row">
    <div class="col-md-4">Column 1</div>
    <div class="col-md-4">Column 2</div>
    <div class="col-md-4">Column 3</div>
  </div>
</div>
```

## Browser Support

DevUI supports all modern browsers:
- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## Documentation

Visit our [comprehensive documentation](./documentation.html) for detailed component examples and usage instructions.

## Contributing

We welcome contributions! Please read our contributing guidelines before submitting pull requests.

## License

MIT License - feel free to use in personal and commercial projects.

## Changelog

### v1.0.0
- Initial release with 150+ components
- CSS variables for customization
- Responsive grid system
- Accessibility improvements
- Comprehensive documentation

---

Built with ❤️ by [Anvith Shetty](https://github.com/anvithshetty17)
