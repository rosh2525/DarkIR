# LaTeX Report Project

This folder contains a ready 2-column project report:

- Main file: `main.tex`

## Compile

Use either of these commands from `report/`:

```bash
pdflatex main.tex
pdflatex main.tex
```

Or with latexmk:

```bash
latexmk -pdf main.tex
```

## Add your PPT images

Create a `figures/` folder under `report/` and place these files:

- `figures/problem_statement_slide.png`
- `figures/contributions_slide.png`
- `figures/visual_results_slide.png`

If image files are missing, placeholders will appear in the PDF automatically.

## Update links

Edit `main.tex` and replace:

- `REPLACE_WITH_VIDEO_ID` with your YouTube video id
- GitHub URL if needed
