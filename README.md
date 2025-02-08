# TikZ & PGFplots Template

A LaTeX template for creating professional-looking plots and figures using TikZ and PGFplots. This template demonstrates how to create plots from CSV data with customizable styles, colors, and markers.

## Features

- Ready-to-use template for plotting data from CSV files
- Pre-configured plot styles with custom colors
- Support for multiple data series in the same plot
- Configurable markers, line styles, and legend
- Automatic axis scaling and customizable tick marks
- Clean and well-documented code

## Prerequisites

- A LaTeX distribution (e.g., TeX Live, MiKTeX)
- Required packages:
  - tikz
  - pgfplots
  - xcolor
  - amsmath
  - amssymb
  - mathrsfs
  - amsthm
  - ulem
  - array
  - hhline
  - multirow

## Usage

1. Place your data in `data.csv` with the following structure:
   ```csv
   x,y1,y2,y3
   0.0,0,5,10
   0.5,2,8,15
   ...
   ```

2. Customize the plot in figure.tex:
   - Adjust axis limits using `xmin`, `xmax`, `ymin`, `ymax`
   - Modify colors using the predefined colors or create new ones with `\definecolor`
   - Change marker styles using the `mark` parameter
   - Position the legend using `legend style`

3. Compile the document:
   ```bash
   pdflatex figure.tex
   ```

## Customization

### Colors
The template includes several predefined colors:
- steelblue (70, 130, 180)
- forestgreen (34, 139, 34)
- indianred (205, 92, 92)
- darkorange (255, 140, 0)
- mediumpurple (147, 112, 219)
- darkgray (105, 105, 105)

### Plot Markers
Available marker types include:
- `o` (circle)
- `triangle`
- `square`

### Additional Features
- Customizable tick marks with `minor x tick num` and `minor y tick num`
- Adjustable line width with `line width`
- Configurable marker size with `mark size`
- Flexible legend positioning

## File Structure

- figure.tex - Main LaTeX template file
- data.csv - Data file for plotting
- .gitignore - Git ignore file for LaTeX auxiliary files

## License

Feel free to use and modify this template for your own work.

## Contributing

Feel free to open issues or submit pull requests if you have suggestions for improvements.