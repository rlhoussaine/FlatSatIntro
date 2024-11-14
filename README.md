# FlatSatIntro

This project introduces new team members to our service, with a flexible structure that can support broader use across the company.

## Project Overview

FlatSatIntro serves as a guide for creating and maintaining documents with Quarto, making it easy to produce, manage, and update team documentation.

## Prerequisites

1. **Install Quarto**  
   Download and install Quarto from [https://quarto.org](https://quarto.org).

2. **Install VS Code and Quarto Extension**  
   Download [Visual Studio Code](https://code.visualstudio.com/) and add the Quarto extension by searching for "Quarto" in the Extensions panel.

## Creating and Updating QMD Documents

1. **Start a New QMD Document**  
   In VS Code, create a new `.qmd` file, allowing Markdown and executable code for dynamic content.

2. **Use the Template**  
   The [Openscapes Quarto Website Tutorial](https://openscapes.github.io/quarto-website-tutorial/) provides a useful template to help structure your document.

3. **Rendering QMD Files**  
   Render a file to the desired format (HTML, PDF, etc.) by running:
   ```bash
   quarto render yourfile.qmd
   ```

## Maintaining the Index

1. **Edit the Index Page**  
   Update `index.qmd` for new content or changes to the site structure.

2. **Re-render the Index**  
   Run:
   ```bash
   quarto render index.qmd
   ```

3. **Preview Changes**  
   View the output in a web browser or PDF viewer to confirm updates.

## Contributing

For improvements or feature requests, submit a pull request with a detailed description.