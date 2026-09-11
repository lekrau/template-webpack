# Webpack Template

Personal starter template for small JavaScript projects using Webpack.

## Includes

- Webpack with separate development and production configs
- `webpack-merge` for shared configuration
- Webpack Dev Server
- HTML template via `html-webpack-plugin`
- CSS loading with `style-loader` and `css-loader`
- Basic CSS reset
- npm scripts for development, production build, and GitHub Pages deployment

## Usage

Create a new repository from this template on GitHub.

Then:

1. Clone the new repository.
2. Update the project-specific metadata in `package.json`.
3. Replace the placeholder content in `src/template.html` and `src/index.js`.
4. Run:

```bash
npm install
npm run dev
```

For a production build:

```bash
npm run build
```

To deploy the dist directory to GitHub Pages:

```bash
npm run deploy
````

Adapt the Webpack configuration as needed for the project.

## References

- [The Odin Project – Webpack](https://www.theodinproject.com/lessons/javascript-webpack)  
  Basic setup and handling additional assets such as images.
- [The Odin Project – Restaurant Page](https://www.theodinproject.com/lessons/node-path-javascript-restaurant-page)  
  `.gitignore` and GitHub Pages deployment.
- [The Odin Project – Revisiting Webpack](https://www.theodinproject.com/lessons/node-path-javascript-revisiting-webpack)  
  npm scripts and template repositories.
- [Webpack – Production](https://webpack.js.org/guides/production/)  
  Separate development and production configurations with `webpack-merge`.
- [Josh Comeau – A Modern CSS Reset](https://www.joshwcomeau.com/css/custom-css-reset/)  
  Basis for the included CSS reset.