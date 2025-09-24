# latex-cv

This is my personal LaTeX project for building and maintaining a professional CV.

## Project Purpose
The repository contains LaTeX source files, templates, and assets for generating a high-quality PDF CV. It is based on a developer-focused template and customized for my experience and career.

## Usage
Edit the main `.tex` file (e.g., `cv_marcin_hajost_2025.tex`) to update CV content. Compile the document using a LaTeX engine such as `pdflatex` or `latexmk`:

```
latexmk -pdf cv_marcin_hajost_2025.tex
```

The output PDF will be generated in the project directory.

## Notes
- The project uses custom class and style files (e.g., `developercv.cls`).
- Some assets (images, icons) may be required for full compilation.
- For troubleshooting, check the `.log` file generated during compilation.