# Tailwind CSS

Tailwind CSS is an open-source utility-first CSS framework that helps you rapidly build custom user interfaces. Unlike traditional CSS frameworks like Bootstrap or Foundation, Tailwind CSS provides low-level utility classes that enable you to create designs without writing custom CSS.

## Table of Contents
- [Features](#features)
- [Setup with PostCSS](#setup-with-postcss)
- [Resources](#resources)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Utility-first Approach**: Tailwind CSS promotes a utility-first approach, allowing you to apply styles directly in your HTML markup using pre-defined utility classes.
- **Highly Customizable**: Tailwind CSS is highly customizable through its configuration file. You can extend, override, or purge unused styles to optimize your CSS bundle size.
- **Responsive Design**: Tailwind CSS includes built-in support for responsive design using breakpoint utilities.
- **Component-friendly**: Although Tailwind CSS is primarily utility-focused, it also provides components and templates to help you get started quickly.

## Setup with PostCSS

1. **Installation**: Install Tailwind CSS and its dependencies using npm or yarn.

   ```bash
   npm install tailwindcss postcss autoprefixer vite


2. **Confiquration**:Generate a Tailwind CSS configuration file by running:

  
   ```bash
    npx tailwindcss init -p    

3.**Import Tailwind Styles**: In your main stylesheet, import the Tailwind CSS styles: 

@import 'tailwindcss/base';
@import 'tailwindcss/components';
@import 'tailwindcss/utilities';

4.**package.json**: In package.json change the test in script to start and add vite into "" this.[package.json](Learning_Phase_1.1/package.json)
 
    
5.**tailwind.config**:
In [tailwind.config](Learning_Phase_1.1/tailwind.config.js)in the content put the * into '' this.

6.**Build**: Finaly run this

    npm run start 

# Resources
[Tailwind CSS Documentation](https://tailwindcss.com/)
[PostCSS Documentation](https://postcss.org/docs/)
# Contributing
Contributions are welcome! If you have any ideas, suggestions, or bug fixes, feel free to open an issue or submit a pull request.

# License
[License](LICENSE)