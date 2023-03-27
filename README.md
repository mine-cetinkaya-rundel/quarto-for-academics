# quarto-for-academics

Materials for the Quarto for Academics video.

## teaching

- Add code-link true to the document yaml

format:
  html:
    code-link: true

- Add include = FALSE as a code chunk option and render and review the error, and fix with YAML completion

- Switch to slides

format: revealjs

Don't need to change anything else 

- Show the sidebar > Tools for PDF export of slides

- Add chalkboard

format:
  revealjs:
    chalkboard: true

- Add multiplex

format:
  revealjs:
    chalkboard: true
    multiplex: true

Show the files generated and which to post

- Add execute: true to document yaml

execute: 
  echo: true

- Highlight lines of code

code-line-numbers: "|5-12|13"

Plot is squished...

- Add output-location: slide

- Show echo: fenced for a code chunk

- Convert to document - Code annotation (1.3 PRERELEASE)

  to scale_color_colorblind() # <1>
  to theme elements           # <2>

  1. Use a color-blind friendly color scale
  2. Adjust theme elements

## research

- Go to https://quarto.org/docs/journals/templates.html

- Click on Quarto journals repo

- Create one with JASA template

my-awesome-paper

- Add a citation

First from Zotero
Welcome to the tidyverse

