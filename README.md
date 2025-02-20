# Spatial relationships and how to use them

- Anna Brázdová & Krasen Samardzhiev
- GeoPython 2025
- University of Applied Sciences and Arts Northwestern Switzerland (Basel, Switzerland), February 24th 2025

## Materials
Participants will be introduced to the new lipysal.Graph functionality to efficiently formalise spatial relationships and how to use them in various applications.
The workshop will be divided into three main parts:

1. What Are Spatial Relationships and What Is libpysal.Graph?
The focus of this part will be on will polygons and how their spatial relationships can be formalized into numerical representations.
We will cover several ways to achieve this and how to implement them in a scalable and efficient manner.
Additionally, we will provide an overview of their various applications in spatial analysis - spatial calculations, autocorrelation, clustering and others.
Lastly, this section will also introduce the libpysal ecosystem and libpysal.Graph more specifically.

2. Spatial Weights, Lag, and Descriptive Statistics.
In this part, we’ll focus on practical applications of weights matrices — spatial weights — which describe the importance of neighboring areas.
We’ll cover calculations of spatial lag, including neighborhood averages and sums, as well as more advanced operations like descriptive statistics of neighbourhoods and applying custom functions.

3. Autocorrelation.
This section will cover both global and local spatial autocorrelation, a key measure of how much a variable is clustered or dispersed spatially, based on the spatial weights graph.
We’ll explain how to calculate both types of autocorrelation and show their relevance in spatial data analysis.


## Running the material

If you'd like to run the notebook, you can create an environment using [Pixi](https://pixi.sh/latest/). See the Pixi [installation instructions](https://pixi.sh/latest/#__tabbed_1_2).

With Pixi installed, clone the repository, open a command line, and start Jupyter Lab from the included Pixi environment. Pixi will automatically install all required dependencies and start the IDE with the notebook.

```sh
pixi run jupyter lab
```
## Acknowledgements
The course material is a portion of [Spatial Data Science for Social Geography](https://martinfleischmann.net/sds/) taught by Martin Fleischmann and Anna Brazdova at Charles University in Prague. Thanks, Martin! 


[![DOI](https://zenodo.org/badge/935386396.svg)](https://doi.org/10.5281/zenodo.14901057)
