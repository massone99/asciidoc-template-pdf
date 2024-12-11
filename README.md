# Asciidoc PDF Template [ENG]

This repository contains a template for generating PDF documents using Asciidoc. The template includes formatting examples, resource linking (fonts, images, etc.), and a `Makefile` script to simplify the build process.

## Features

- Asciidoc sources organized in the `src` directory.
- Resources such as fonts and images available in the `resources` directory.
- Built-in support for including and linking resources.
- Detailed formatting examples, including:
  - Headings
  - Tables
  - Code
  - Images
  - Links
  - Ordered and unordered lists

## Prerequisites

Ensure you have the following tools installed:

- [Asciidoctor](https://asciidoctor.org/)
- [Make](https://www.gnu.org/software/make/)
- A PDF viewer (e.g., [Okular](https://okular.kde.org/))

## How to Use the Template

1. **Clone the repository**:

   ```bash
   git clone git@github.com:stormtroober/asciidoc-template.git
   ```

2. **Navigate to the project directory**:

   ```bash
   cd asciidoc-template
   ```

3. **Generate the PDF**:

   ```bash
   make
   ```

   The generated file will be located in `output/report.pdf`.

4. **View the PDF**:

   ```bash
   okular output/report.pdf
   ```

5. **Clean generated files** (optional):

   ```bash
   make clean
   ```

## Project Structure

- `src/`:
  Contains the `.adoc` source files. You can edit or add new files in this directory to customize your document.

- `resources/`:
  Contains fonts, images, and other necessary resources for the document. The template already includes references to these resources.

- `output/`:
  Output directory where the generated PDF is saved.

- `Makefile`:
  Script to automate document compilation and cleaning up generated files.

## Customization

You can customize the document by modifying the files in the `src` directory. To add images or fonts, save them in the `resources` directory and update the references in the Asciidoc files.

For more details on using Asciidoc, refer to the [official documentation](https://asciidoctor.org/docs/).

## Contributions

If you wish to contribute to the project, feel free to open a pull request or report issues in the [Issues](https://github.com/stormtroober/asciidoc-template/issues) section.

## License

This project is licensed under the [MIT License](LICENSE).



