# Persistent Homology Examples

This repo exists to hold interactive html widgets related to my Towards Data Science Medium article.

Unfortunately, I cannot share code, as that belongs to my employer (Geometric Data Analytics). I can say that all code to create the visualizations in my article was in Python.

The Persistent Homology Calculations were done using an open source Topological Data Analysis package called `gda-public`, which is available [here](https://github.com/geomdata/gda-public).

All my visualizations were generated using `matplotlib` or `holoviews`.

# Height Filtration Segmentation Example

In the article, I include a static image from running the height filtration up to a specified threshold:

![](../figures/segmentation_coverage.png){width=50%}

The widget referenced below allows you to see the connected components that form running the height filtration to aribtrary values:

<a href="https://gjkoplik.github.io/pers-hom-examples/segmentation_lowerstar_widget.html" title="Segmentation Widget">Click here for the segmentation widget</a>
