# Real State Website

This repository contains the codebase for a Real State website, showcasing properties, blog entries, testimonials, and more. It's designed with modern web development techniques, including HTML5, CSS3 (with SASS), and JavaScript, alongside a build process managed by Gulp.

## Features

- **Responsive Design:** The website is fully responsive, ensuring a great user experience on devices of all sizes.
- **Modern CSS with SASS:** Utilizes SASS for styling, organized into partials for better maintainability.
- **Optimized Images:** Images are optimized for the web, including formats like WebP and AVIF for better performance.
- **Gulp Build Process:** Automates tasks such as CSS compilation, image optimization, and more.

## Development

### Prerequisites

Before you begin, ensure you have installed the latest version of [Node.js](https://nodejs.org/). This project uses `npm` for managing dependencies.

### Setup

Clone the repository and install the dependencies:

```bash
git clone https://github.com/henrytene/realstate.git
cd realstate
npm install
Running the Development Server
To start the development server, run:

npm run dev
This command compiles the SASS files, optimizes images, and watches for changes.

Building for Production
To build the project for production, run:

npm run build
This will generate optimized CSS, JavaScript, and images in the build directory.

Structure
src/: Source files including SASS, JavaScript, and images.
scss/: SASS files organized into base, components, layouts, and utilities.
img/: Images used throughout the website.
build/: Compiled and optimized files ready for deployment.
index.html: The main HTML file.
gulpfile.js: Gulp tasks for automating the build process.
Contributing
Contributions are welcome! Please open an issue or submit a pull request with your changes.

License
This project is open source and available under the MIT License.


This Readme provides a comprehensive overview of the Real State website project, including its features, development setup, project structure, and contribution guidelines.
