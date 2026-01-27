# Interactive Plotly Presentation

## Project Overview

This is an R Markdown presentation created for the Coursera Data Science Specialization course "Developing Data Products" (Course 9, Project 3).

## Features

- Interactive 3D surface plot using Plotly
- R Markdown ioslides presentation format
- Responsive and mobile-friendly
- Hosted on GitHub Pages

## Viewing the Presentation

Once deployed, the presentation will be available at:
`https://[your-username].github.io/[repo-name]/presentation.html`

## Local Development

### Prerequisites

- R (version 4.0 or higher)
- RStudio (recommended)
- Required R packages:
  ```r
  install.packages(c("rmarkdown", "plotly", "knitr"))
  ```

### Building the Presentation

1. Clone this repository
2. Open `presentation.Rmd` in RStudio
3. Click "Knit" button or run:
   ```r
   rmarkdown::render("presentation.Rmd", output_dir = "docs")
   ```

## Project Requirements

- ✅ Date: January 27, 2026
- ✅ Format: R Markdown presentation (ioslides)
- ✅ Interactive Plotly visualization (3D surface plot)
- ✅ Hosted on GitHub Pages

## Technical Details

The presentation features a 3D wave interference pattern created using the mathematical function:

```
f(x, y) = sin(sqrt(x^2 + y^2)) / (sqrt(x^2 + y^2) + 1)
```

This creates a visually stunning radial wave pattern with interactive rotation, zoom, and hover capabilities.

## License

This project is created for educational purposes as part of the Coursera Data Science Specialization.

## Author

Rahul Vijayraghavan
January 2026
