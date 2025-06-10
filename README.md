# SASS Template

This is a SASS template designed to help developers streamline their CSS workflows. It includes a variety of useful tools, mixins, and functions to help you quickly create consistent and responsive designs.

## Features

- Modular structure for easy customization and maintenance
- Consistent design system based on variables for colors, typography, and spacing
- Mixins and functions for common CSS tasks such as media queries, flexbox, and animations
- Responsive design with support for mobile, tablet, and desktop viewports
- Light and dark theme options
- Fully customizable with easy-to-understand documentation

## Getting Started

To use this template, simply download the source files and include them in your project. You can then import the appropriate SASS partials into your main SASS file using the `@import` directive.

For example, to include the partial for buttons, you would add the following line to your main SASS file:

```scss
@import 'buttons';
```

## Contributing

Contributions are welcomed from anyone who would like to help make SASS-TEMPLATE better. If you have an idea for a new feature, or have found a bug that needs fixing, please open a new issue in the GitHub repository.

If you'd like to contribute code to thi SASS-TEMPLATE, please fork the repository, create a new branch for your changes, and submit a pull request.   Your changes would be reviewed and merged into the main branch if they meet our guidelines.


## Compilation

To compile the SCSS files into a single CSS file (`main.css`), you'll need a Sass compiler.

### Using Node Sass (Dart Sass is recommended)

It's recommended to use Dart Sass, which is the primary implementation of Sass.

1.  **Install Dart Sass:**
    If you have Node.js and npm installed, you can install Dart Sass globally:
    ```bash
    npm install -g sass
    ```
    Alternatively, check the official Sass website for other installation options: [https://sass-lang.com/install](https://sass-lang.com/install)

2.  **Compile `main.scss`:**
    Navigate to the root directory of this project in your terminal and run the following command:
    ```bash
    sass main.scss main.css
    ```
    This will compile `main.scss` and its imported partials into `main.css`.

3.  **Watch for Changes (Optional):**
    To automatically recompile your CSS when you make changes to your SCSS files, you can use the `--watch` flag:
    ```bash
    sass --watch main.scss:main.css
    ```

### Output
The compiled CSS will be saved as `main.css` in the root directory. You can then link this file in your HTML, as demonstrated in `index.html`.
