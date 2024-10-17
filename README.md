# Responsive Portfolio Website

This repository contains the code for a **Responsive Portfolio Website** built using **HTML** and **CSS**. Additionally, GitHub Actions and linters have been set up to maintain code quality and standards.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Linting and Code Quality](#linting-and-code-quality)
- [Contributing](#contributing)
- [License](#license)

## Overview

This project is a personal portfolio website designed to be fully responsive across various screen sizes. It showcases projects, contact information, and professional details in a clean and minimalist design.

## Features

- **Responsive Design:** Fully optimized for all screen sizes (except the contact section, which is still in progress).
- **HTML5 and CSS3:** Built with modern web standards.
- **Mobile-First Approach:** Designed to adapt well on mobile devices before scaling up for larger screens.
- **Linting:** Implemented with GitHub Actions for enforcing coding standards.
  
## Project Structure

```plaintext
.
├── .github/             # GitHub workflows for continuous integration
│   └── workflows/       # Contains linter configurations for CI
├── src/                 # Contains website source code
├── .gitignore           # Specifies files to ignore in version control
├── .hintrc              # HTMLHint configuration file for linting HTML
├── .stylelintrc         # Stylelint configuration file for linting CSS
├── index.html           # Main HTML file
├── styles.css           # Main CSS file
├── README.md            # Project documentation
├── package.json         # Node.js dependencies and scripts
└── package-lock.json    # Locked dependency versions
```

## Getting Started

### Prerequisites

Make sure you have the following installed:
- [Node.js](https://nodejs.org/) and npm (for managing linting tools)
- A web browser (Chrome, Firefox, etc.)

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/responsive-portfolio.git
   cd responsive-portfolio
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Open the website:**
   Simply open the `index.html` file in your browser to view the portfolio website.

### Running the Project

You can make changes to the `src/` files and then reload the `index.html` file in your browser to see updates in real time.

## Linting and Code Quality

This project uses **HTMLHint** and **Stylelint** to maintain code quality:

- **HTMLHint:** For HTML file linting
- **Stylelint:** For CSS file linting

### Running Linters

To manually run linters, execute the following commands:

```bash
# Run HTML linter
npx htmlhint src/*.html

# Run CSS linter
npx stylelint "**/*.css"
```

GitHub Actions are set up to automatically run linters on push and pull request events to ensure consistent code quality.

## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a pull request.

## License

This project is open-source and available under the [MIT License](LICENSE).
