# Tailwindcss for Docusaurus v2

Docusaurus v2 plugin to provide support for [tailwincss](https://tailwindcss.com/).

## Features

- Configured with [autoprefixer](https://github.com/postcss/autoprefixer) as recommanded in tailwindcss configuration.
- Native tailwindcss configuration with `tailwind.config.js`.

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
