# Tailwind Heritage Plugin

![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-Plugin-06B6D4)
![JavaScript](https://img.shields.io/badge/JavaScript-Config-F7DF1E)
![Python](https://img.shields.io/badge/Python-Tooling-3776AB)
![License](https://img.shields.io/badge/License-MIT-green)

A Tailwind CSS plugin that extends your design system with heritage-inspired design tokens. Adds culturally rich color palettes, spacing scales, and typography presets drawn from traditional Indian and Kerala art forms.

## Features

- Custom Tailwind color palette with heritage-inspired tones
- Extended spacing and sizing scales based on traditional proportions
- Typography presets for multilingual content
- AI-powered design token generation via Python worker
- Seamless integration with existing Tailwind configurations
- Compatible with Tailwind CSS v3 and above

## Tech Stack

| Technology   | Purpose                   |
|--------------|---------------------------|
| Tailwind CSS | Utility-first CSS         |
| JavaScript   | Plugin configuration      |
| Python       | AI worker for generation  |
| Make         | Build automation          |

## Quick Start

1. Clone the repository:

```bash
git clone https://github.com/razinahmed/tailwind-heritage-plugin.git
cd tailwind-heritage-plugin
```

2. Install the plugin in your Tailwind project:

```javascript
// tailwind.config.js
module.exports = {
  plugins: [
    require('./tailwind-heritage-plugin'),
  ],
}
```

3. Use heritage utility classes:

```html
<div class="bg-heritage-gold text-heritage-ivory p-heritage-md">
  Heritage-styled content
</div>
```

## AI Worker

The included Python worker generates design tokens programmatically:

```bash
python core/ai_worker.py
```

## Build

```bash
make build
make test
```

## Project Structure

```
tailwind-heritage-plugin/
  core/
    ai_worker.py    # AI-powered token generator
  Makefile          # Build commands
  LICENSE           # MIT License
```

## Contributing

Contributions are welcome. Design token suggestions rooted in cultural heritage are encouraged.

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.
