# Circos_plot

Circos, is a circular ideogram layout to display relationships between genomic intervals.
Here , I implemented an R package, RCircos, using only R packages that come with R base installation. 
The package supports Circos 2D data track plots such as scatter, line, histogram, heatmap, tile, connectors, links, and text labels. 
Each plot is implemented with a specific function and input data for all functions are data frames which can be objects read from text files or generated
with other R pipelines.

Interpretation :  The Inner circles represent a heatmap , and the blank spaces means there is no presence of genes in it.
The second circle indicates the name of genes .
And the last Which is Outer circle it shows the presence of chromosomes pairs.
