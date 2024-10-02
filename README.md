# README

This is a GitHub repository hosting the [dashboard](https://delta-stewardship-council.github.io/restoration_synthesis/) created by the [Delta Stewardship Council's 2023 Restoration working group](https://www.deltacouncil.ca.gov/delta-science-program/science-synthesis-working-group). The dashboard visualizes several key datasets that provide important insights to restoration projects located in the Sacramento-San Joaquin River Delta. 

## How to edit

To make edits to this dashboard, first [install Quarto](https://quarto.org/docs/dashboards/#getting-started) (if you don't have it already) and then feel free to make edits according to the [Quarto dashboard layout](https://quarto.org/docs/dashboards/layout.html). The rest of the documentation on Quarto dashboards can be found on the sidebar in the previous link, as well.

Make sure to provide your own [personal file path](https://github.com/Delta-Stewardship-Council/restoration_synthesis/blob/main/index.qmd#L28) to the NCEAS Restoration Box folder in order to run the code in `index.qmd`. Once you're satisfied with your edits, remember to render `index.qmd` and commit+push the resulting `index.html` file. 

## Potential next steps

Here are some ideas for potential next steps for this dashboard:

- Publish the datasets in the dashboard to a data repository such as [KNB](https://knb.ecoinformatics.org/)
  - Then edit the file paths in `index.qmd` to read from the published data instead
- Add text descriptions on Page 1 and Page 2 to give context on the project
- Continue to refine the visualizations on Page 2
