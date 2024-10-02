# To-Do Application (TypeScript) by Régis Boamah

This project is a simple To-Do application built with TypeScript, designed to introduce students to the basics of TypeScript. It serves as an introductory chapter for a course on TypeScript technology, showcasing key syntax and concepts in a real-world context.

## Learning Outcomes

Through this project, students will gain hands-on experience with:

- **TypeScript Type System**: Understanding the fundamentals of type annotations, interfaces, and type inference.
- **Package Importing**: Addressing common issues and solutions when importing third-party packages in TypeScript.
- **Development Tools**: Using modern development tools like Snowpack to streamline the process of building TypeScript applications.

## Why Snowpack?

**Snowpack** is used as the module bundler in this project because it provides a lightweight and efficient alternative to more complex bundlers like Webpack. Snowpack enables the browser to access Node modules directly, significantly speeding up the development process by avoiding unnecessary bundling steps.  
This choice, made by the project author, Regis Boamah, was to ensure that students could focus on learning TypeScript without being bogged down by heavy toolchains.

## Installation

To set up the project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/Reggis94/to-do-typescript

2. Navigate into the project directory:
   ```bash
   cd to-do-typescript

3. Install the required dependencies, including Snowpack:
   ```bash
   npm install --save-dev snowpack

## Project Setup

This project was bootstrapped with **Create Snowpack App (CSA)**, which provides a simple and fast setup for modern web development using Snowpack.

### Available Scripts

- **`npm start`**  
  Launches the development server. Open [http://localhost:8080](http://localhost:8080) in your browser to see the app.  
  The app will automatically reload as you make changes, and any TypeScript lint errors will appear in the console.

- **`npm run build`**  
  Builds a production-ready version of the app and saves the output in the `build/` directory.  
  For optimal performance in production, consider adding a bundler plugin like `@snowpack/plugin-webpack` or `snowpack-plugin-rollup-bundle` in your `snowpack.config.mjs` file.

---

### Additional Information

This project is intentionally kept simple to focus on teaching TypeScript basics. As students progress through the course, more advanced features and concepts will be introduced in subsequent projects.

Happy Coding! ✨
