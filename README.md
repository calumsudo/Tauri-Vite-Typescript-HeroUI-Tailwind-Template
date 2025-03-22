# Tauri + React + TypeScript + Vite + HeroUI + Tailwind CSS

A modern desktop application template that combines Tauri's native capabilities with React's frontend power, enhanced by TypeScript, HeroUI components, and Tailwind CSS styling.

## Features

- **Tauri**: Lightweight, secure framework for building cross-platform desktop apps
- **React 18**: Modern UI library for building interactive interfaces
- **TypeScript**: Type safety and improved developer experience
- **Vite**: Next-generation frontend tooling for fast development
- **HeroUI**: Beautiful, accessible UI components
- **Tailwind CSS**: Utility-first CSS framework for rapid UI development

## Prerequisites

- [Node.js](https://nodejs.org/) (v16 or newer)
- [Rust](https://www.rust-lang.org/tools/install)
- [Tauri setup dependencies](https://tauri.app/v1/guides/getting-started/prerequisites)

## Getting Started

### Clone the repository

```bash
git clone https://github.com/calumsudo/Tauri-Vite-Typescript-HeroUI-Tailwind-Template.git
cd Tauri-Vite-Typescript-HeroUI-Tailwind-Template
```

### Install dependencies

```bash
npm install
```

### Development

Run the app in development mode with hot reload:

```bash
npm run tauri dev
```

### Building

Build the app for production:

```bash
npm run tauri build
```

This will create executable files for your platform in the `src-tauri/target/release` directory.

## Project Structure

```
/
├── src/                  # React frontend code
├── src-tauri/            # Tauri backend code (Rust)
├── public/               # Static assets
├── index.html            # HTML entry point
├── tailwind.config.js    # Tailwind CSS configuration
├── tsconfig.json         # TypeScript configuration
├── vite.config.ts        # Vite configuration
└── package.json          # Project dependencies and scripts
```

## Recommended IDE Setup

- [VS Code](https://code.visualstudio.com/) with the following extensions:
  - [Tauri](https://marketplace.visualstudio.com/items?itemName=tauri-apps.tauri-vscode)
  - [rust-analyzer](https://marketplace.visualstudio.com/items?itemName=rust-lang.rust-analyzer)
  - [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
  - [Tailwind CSS IntelliSense](https://marketplace.visualstudio.com/items?itemName=bradlc.vscode-tailwindcss)

## License

MIT

## Contributing

Contributions, issues, and feature requests are welcome!