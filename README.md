# Bun + Astro Starter Template

Welcome to the **Bun + Astro Starter** project template! This repository is designed to help you quickly start a web application using **Bun.js** for server-side rendering, **Astro.js** for static site generation, **Alpine.js** for interactivity, and **Tailwind CSS** for styling.

## Features

- **Bun.js**: Fast JavaScript runtime for building server-side applications.
- **Astro.js**: Optimized static site generator with a focus on speed and simplicity.
- **Alpine.js**: Lightweight framework for declarative UI interactivity.
- **Tailwind CSS**: Utility-first CSS framework for rapid design.

## Getting Started with the Template

### Using this Template

You can easily create your own project based on this template by clicking the **"Use this template"** button at the top of this repository. This will create a new repository in your GitHub account with this template's content.

1. Click **"Use this template"**.
2. Choose a repository name for your project.
3. Clone your new repository to your local machine:
   ```bash
   git clone https://github.com/casoon/bun-astro-starter.git
   cd bun-astro-starter
   ```

4. Install dependencies:
   ```bash
   bun install
   ```

5. Start the development server:
   ```bash
   bun dev
   ```

### Prerequisites

Make sure you have **Bun** installed on your system. If not, you can install it by following the [Bun installation guide](https://bun.sh/).

### Building for Production

To build the site for production, run:

```bash
bun run build
```

The output will be placed in the `dist` folder, which can be deployed to any static hosting provider.

### Deploying

Astro produces static HTML files that can be hosted anywhere. You can deploy to platforms like **Netlify**, **Vercel**, **GitHub Pages**, or your own server.

## Project Structure

Here's an overview of the main project files and directories:

```
├── src/
│   ├── layouts/         # Layout components (e.g., MainLayout)
│   ├── pages/           # Astro pages
│   ├── styles/          # Tailwind CSS styles
│   └── components/      # Reusable UI components
├── public/              # Public assets
├── astro.config.mjs     # Astro configuration
├── tailwind.config.cjs  # Tailwind configuration
├── bun.lockb            # Bun lockfile for package versions
└── package.json         # Project metadata and dependencies
```

### Customization

- **Alpine.js**: Alpine.js is already set up. Use `x-data`, `x-show`, and other directives to add interactivity to your components.
- **Tailwind CSS**: Modify the `tailwind.config.cjs` file to customize your Tailwind setup, such as themes, colors, and plugins.

## License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for more information.

---

## MIT License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contributing

Feel free to open issues or submit

## Author

Created by **Casoon**.
