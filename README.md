# Joshua's CV in LaTeX

Template suitable for long-length resumes, with support for images and SVG conversion.

## Requirements

- LaTeX distribution (I use `pdflatex`)
- `inkscape` for SVG image handling

## File Structure

- `cv.tex`: Main LaTeX file
- `cv.cls`: Style file
- `imgs/`: dir for image assets
- `svg-inkscape/`: dir for converted image assets

## Usage

`$ pdflatex -shell-escape cv.tex`

NB - you need the `-shell-escape` for your system to call `inkscape`