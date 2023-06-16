# Tailwind CSS for Docusaurus v2/v3

Docusaurus v2 plugin to provide support for [tailwindcss](https://tailwindcss.com/).

## Features

- Configured with [autoprefixer](https://github.com/postcss/autoprefixer) as recommended in tailwindcss configuration.
- Native Tailwind CSS configuration with `tailwind.config.js`.

## Installation

Install the plugin with npm :

```bash
npm install --save docusaurus-tailwindcss
```

or yarn :

```bash
yarn add docusaurus-tailwindcss
```

Add the plugin to `docusaurus.config.js` :

```javascript
module.exports = {
  // ...
  plugins: [
    // ...
    'docusaurus-tailwindcss',
  ],
};
```

Include tailwind in `custom.css` :

```css
@tailwind base;
@tailwind components;
@tailwind utilities;
```

## Configuration

Refer to [tailwindcss configuration](https://tailwindcss.com/docs/configuration).
