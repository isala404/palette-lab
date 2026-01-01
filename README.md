# Palette Lab

A visual color palette testing tool for UI design. Create, compare, and refine color schemes in real-time with live preview.

**Live Demo:** [https://isala404.github.io/palette-lab/](https://isala404.github.io/palette-lab/)

## Features

- **Live Preview** - See your color changes instantly applied to a realistic UI mockup
- **Multiple Palettes** - Create and switch between different color schemes
- **Color Picker & Hex Input** - Use the visual picker or enter hex codes directly
- **CSS Export** - Copy CSS variables to clipboard with one click
- **JSON Import/Export** - Switch to code mode to paste palette JSON directly
- **Claude AI Integration** - Get AI-powered palette suggestions
- **Persistent Storage** - Palettes are saved to localStorage
- **Responsive Design** - Works on desktop and mobile devices

## Color Variables

Each palette defines these CSS variables:

| Variable | Purpose |
|----------|---------|
| `bgMain` | Main background color |
| `bgCard` | Card/container background |
| `textPrimary` | Primary text color |
| `textSecondary` | Secondary/muted text |
| `accent` | Accent for buttons and links |
| `badge` | Badge/tag color |
| `highlight` | Highlight/gradient color |

## Usage

1. Open the palette editor panel (opens by default, or click the "Palettes" tab on the left)
2. Adjust colors using the color pickers or hex inputs
3. Switch between palettes using the theme buttons at the top
4. Click the `+` button to create a new palette
5. Use the clipboard button to copy CSS variables
6. Switch to "Code" mode to import/export palette JSON

## Palette JSON Schema

```json
{
  "id": "unique-id",
  "name": "Palette Name",
  "colors": {
    "bgMain": "#hex",
    "bgCard": "#hex",
    "textPrimary": "#hex",
    "textSecondary": "#hex",
    "accent": "#hex",
    "badge": "#hex",
    "highlight": "#hex"
  }
}
```

## Local Development

Just open `index.html` in your browser - no build step required.

```bash
# Clone the repo
git clone https://github.com/isala404/palette-lab.git

# Open in browser
open index.html
```

## License

MIT

## Author

Built by [@isala404](https://isala.me)
