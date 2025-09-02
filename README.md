# Aero Fabrication Club Website

This is the official website for the Aero Fabrication Club at PDPM IIITDM Jabalpur. The site showcases the club's projects, achievements, team, gallery, sponsors, and contact information.

## Features

- Responsive design using [Chakra UI](https://chakra-ui.com/)
- Smooth scrolling navigation
- Project and achievement highlights
- Interactive gallery with modal view
- Sponsor and contact sections

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v16 or above recommended)
- [npm](https://www.npmjs.com/)

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/website.git
   cd website
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Start the development server:
   ```sh
   npm run dev
   ```
4. Open [http://localhost:5173](http://localhost:5173) in your browser.

### Building for Production

```sh
npm run build
```

The production-ready files will be in the `dist/` directory.

### Linting and Formatting

To lint your code:
```sh
npm run lint
```
To format your code:
```sh
npm run format
```

## Project Structure

```
├── public/
│   └── assets/         # Images and static assets
├── src/
│   ├── components/     # React components
│   ├── App.jsx         # Main app component
│   ├── main.jsx        # Entry point
│   └── index.css       # Global styles
├── index.html
├── package.json
└── vite.config.js
```

## Contributing Guidelines

We welcome contributions! Please follow these steps:

1. **Fork the repository** and create your branch from `main`.
2. **Install dependencies** if you haven't already: `npm install`
3. **Make your changes** in the appropriate files.
4. **Lint your code** before committing:
   ```sh
   npm run lint
   ```
5. **Test your changes** locally by running the development server.
6. **Commit your changes** with a clear and descriptive message.
7. **Push to your fork** and submit a Pull Request (PR) with a description of your changes.

### Code Style

- Use [Prettier](https://prettier.io/) and [ESLint](https://eslint.org/) for formatting and linting.
- Use functional React components.
- Use Chakra UI components for styling and layout.
- Keep components modular and reusable.

### Issues

If you find a bug or have a feature request, please [open an issue](https://github.com/your-username/website/issues).

## License

This project is licensed under the [MIT License](LICENSE).

---

**Aero Fabrication Club**
PDPM IIITDM Jabalpur
