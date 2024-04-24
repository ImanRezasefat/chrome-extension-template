# Chrome Extension Starter Template with React, TypeScript, Vite, and Tailwind

This repository serves as a starter template for creating Chrome extensions using React, TypeScript and Webpack. It's designed to provide a solid foundation for developing browser extensions with modern web technologies.

## Features

- **React**: Utilize React for building dynamic and interactive user interfaces.
- **TypeScript**: Benefit from TypeScript's static typing and other features for a more robust development experience.
- **Webpack**: Leverage Webpack for bundling and optimizing your extension.

# Loading the Extension into Chrome

To load your extension into Chrome for testing or development purposes, follow these steps:

1. Open Chrome browser.
2. Navigate to `chrome://extensions/`.
3. Enable "Developer mode" by toggling the switch in the top right corner.
4. Click on the "Load unpacked" button.
5. Navigate to your project's `dist` folder.
6. Select the folder to load your extension.

Your extension should now be loaded into Chrome and ready for testing or development.

# Development and Build

During development and for building your extension, you can use the following npm scripts:

## Development

For development, you can use the `npm run watch` command to start a development server with hot-reloading. This allows you to instantly see changes as you develop your extension. You may need to reload the extension on chrome to see changes.

```bash
npm run watch
```
