# urban-doodle-OPHI-Drilldown-charts

A repo for creating drilldown charts related to the GMPI data in R using the {highcharter} package

## Brief for creating the chart

> We are currently reviewing GMPI data visualisations, trying to find ways to improve them. We wanted to kindly ask you if it was possible to make an interactive online version of the figure below? So the idea would be that one first sees the six regional bars on the left and then if one would hover with the mouse over or click on one of them, then the middle part (all countries from that region) would appear; and if one then clicks on one country, the subnational regions would appear. If this makes sense?

![Ref Img](img/refrence_img.png)

In order to create this I am trying to use the {highcharter} package. This is a wrapper over the JS highcharts library that allows me to use it in R.

## data

The GMPI data, 2022 is used to implement this chart and the data is in the folder `data`.

## Code & Output

The code for the implementation is in a quarto file named `index.qmd`.

The output is a html render of the above mentioned .qmd file and is hosted [here]().
