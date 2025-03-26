# MobileBoil

A modern, mobile-first CSS boilerplate that combines the best of both worlds: modern CSS features with backward compatibility.

## Features

- 🎯 Mobile-first approach
- 📱 Responsive design with modern breakpoints
- 🎨 CSS Variables for easy theming
- 📐 Modern CSS Grid with legacy float support
- 🎭 Modern form elements with accessibility
- 🎨 Clean, minimal design
- 🔄 Smooth transitions and animations
- 📦 Modular CSS architecture

## Quick Start

1. Clone the repository:
```bash
git clone https://github.com/avantgardian/MobileBoil.git
```

2. Include the CSS files in your HTML:
```html
<link rel="stylesheet" href="stylesheets/base.css">
<link rel="stylesheet" href="stylesheets/skeleton.css">
<link rel="stylesheet" href="stylesheets/layout.css">
```

## Modern Features

### CSS Variables
```css
:root {
  --color-primary: #333;
  --color-secondary: #777;
  --font-family-base: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --spacing-base: 1rem;
}
```

### Modern Grid System
```html
<!-- Modern CSS Grid -->
<section class="grid gap-medium">
  <div class="card">Content</div>
  <div class="card">Content</div>
  <div class="card">Content</div>
</section>

<!-- Legacy Float Grid -->
<section class="row">
  <div class="column column-third">Content</div>
  <div class="column column-third">Content</div>
  <div class="column column-third">Content</div>
</section>
```

### Modern Form Elements
```html
<div class="form-group">
  <label for="name">Name</label>
  <input type="text" id="name" placeholder="Enter your name">
</div>
```

## Breakpoints

- Mobile: < 480px
- Tablet: 480px - 768px
- Desktop: 768px - 1024px
- Large Desktop: 1024px - 1440px
- Extra Large: > 1440px

## Components

### Cards
```html
<div class="card">
  <h3>Card Title</h3>
  <p>Card content</p>
</div>
```

### Buttons
```html
<button class="button">Click me</button>
```

### Forms
```html
<form>
  <div class="form-group">
    <label for="email">Email</label>
    <input type="email" id="email">
  </div>
  <button type="submit" class="button">Submit</button>
</form>
```

## Utility Classes

### Spacing
- `.remove-bottom` - Remove bottom margin
- `.half-bottom` - Half bottom margin
- `.add-bottom` - Add bottom margin

### Grid Gaps
- `.gap-none` - No gap
- `.gap-small` - Small gap
- `.gap-medium` - Medium gap
- `.gap-large` - Large gap

### Alignment
- `.align-start` - Align items to start
- `.align-center` - Center items
- `.align-end` - Align items to end
- `.justify-start` - Justify content to start
- `.justify-center` - Center content
- `.justify-end` - Justify content to end
- `.justify-between` - Space between items
- `.justify-around` - Space around items

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Opera (latest)
- iOS Safari (latest)
- Android Chrome (latest)

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Credits

- Inspired by Skeleton Boilerplate
- Created by [Andrei S](https://github.com/avantgardian)
- Modernized in 2024