# Quantum-design-System
# Design Tokens

This repository includes a `tokens.json` file that defines the design tokens extracted from our Figma design system using a Figma plugin.

## 📁 File: `tokens.json`

This file contains all the core design tokens used for building consistent UI components across platforms. The structure follows the [Style Dictionary](https://amzn.github.io/style-dictionary/#/) format and includes:

### 🎨 Color Tokens
- **Base colors**: Full palettes for blue, pink, green, orange, red, violet, purple, yellow, black, white, gray, sky blue.
- **Alias tokens**: Semantic roles like `Primary`, `Secondary`, `Success`, `Warning`, `Danger`, `Neutral`, and `Information`.
- **Mapped tokens**: Applied roles for `text`, `surface`, `border`, and `icons`.

### 🔤 Typography Tokens
- **Font families**: Defined for body (`Lato`) and heading (`Inter`).
- **Font weights**: Regular, Semibold, Bold.
- **Responsive typography**: Includes `fontSize`, `lineHeight`, and `paragraphSpacing` for headings (`h1`–`h6`) and body (`sm`, `md`, `lg`).

### 📏 Spacing & Sizing
- Tokens for spacing, border radius, and border widths, mapped to consistent scale values (e.g., `4px`, `8px`, `16px`).

### 📱 Responsive Tokens
- Token sets for Mobile, Desktop, and general responsive design with device-specific font sizing and layout spacing.

---

## 📦 Usage

These tokens are intended to be used in:
- A design system implementation (CSS/SCSS/JS/TS)
- Custom theming in React or styled-components
- Tailwind CSS customization
- Style Dictionary token transformation

---

## 🛠️ Next Steps

You can transform this `tokens.json` into platform-specific styles using tools like:
- [Style Dictionary](https://amzn.github.io/style-dictionary/#/)
- [Token Transformer](https://github.com/lukasoppermann/design-tokens-transformer)
- Tailwind theme extensions

Feel free to reach out or open issues if you'd like transformation templates for your target environment.
