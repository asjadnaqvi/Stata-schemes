# Stata schemes

In this folder are various new Stata schemes. The schemes have been programmed in three flavors: **white**, **black**, and **grey (gg)**. As the names suggest, these are the background colors, where the last one is inspired by the [ggplot2](https://ggplot2.tidyverse.org/) scheme in R.

These schemes are procedurally generated where the colors and other information is introduced in the schemes via scripts. The core white scheme is based on the [Cleanplots theme](https://www.trentonmize.com/software/cleanplots) (Mize 2018) that itself is derived from the [plainplots theme](https://www.stata.com/meeting/switzerland16/slides/bischof-switzerland16.pdf) (Bischof 2017). Most of the elements have been overwritten but the simple structure of the dotted grid lines and the axis colors is maintained. I really like these features! The colors have been passed on to the scheme using Benn Jan's [colorpalette](http://repec.sowi.unibe.ch/stata/palettes/index.html) package (Jann 2018)

Since the schemes are scripted, this folder will be filled up with various schemes over time. It is also likely some schemes go through minor adjustments since not all possible graph combinations have been tested. Names and installation paths might change. Please check here for the updates.

* The dofile contains the script to test the code.
* The graph folder contains the high resolution sample figures.


## How to use the schemes:

The dofile in the folder can be copied and executed in Stata. Otherwise:

Check the installation:
> net d tsg_schemes, from("https://raw.githubusercontent.com/asjadnaqvi/Stata-schemes/main/schemes/")

Install the schemes:
> net install tsg_schemes, from("https://raw.githubusercontent.com/asjadnaqvi/Stata-schemes/main/schemes/")

You can try various graphs either using this test data set:
> use "https://github.com/asjadnaqvi/Stata-schemes/blob/main/scheme_test.dta?raw=true", clear

or use your own dataset!

Please report errors or bugs or suggestions to improve the schemes. 


*Note: This is a beta page. Links might get updated. Please check here for the latest version.* 


## Tableau color scheme

### white_tableau
<img src="./figures/scatter_white_tableau.png" height="200"><img src="./figures/line_white_tableau.png" height="200">
<img src="./figures/mlabel_white_tableau.png" height="200"><img src="./figures/bygraph_white_tableau.png" height="200">
<img src="./figures/bar_white_tableau.png" height="200"><img src="./figures/barh_white_tableau.png" height="200">
<img src="./figures/pie_white_tableau.png" height="200"><img src="./figures/density_white_tableau.png" height="200">
<img src="./figures/ci_white_tableau.png" height="200"><img src="./figures/rcap_white_tableau.png" height="200">
<img src="./figures/box_white_tableau.png" height="200">

### black_tableau
<img src="./figures/scatter_black_tableau.png" height="200"><img src="./figures/line_black_tableau.png" height="200">
<img src="./figures/mlabel_black_tableau.png" height="200"><img src="./figures/bygraph_black_tableau.png" height="200">
<img src="./figures/bar_black_tableau.png" height="200"><img src="./figures/barh_black_tableau.png" height="200">
<img src="./figures/pie_black_tableau.png" height="200"><img src="./figures/density_black_tableau.png" height="200">
<img src="./figures/ci_black_tableau.png" height="200"><img src="./figures/rcap_black_tableau.png" height="200">
<img src="./figures/box_black_tableau.png" height="200">

### gg_tableau
<img src="./figures/scatter_gg_tableau.png" height="200"><img src="./figures/line_gg_tableau.png" height="200">
<img src="./figures/mlabel_gg_tableau.png" height="200"><img src="./figures/bygraph_gg_tableau.png" height="200">
<img src="./figures/bar_gg_tableau.png" height="200"><img src="./figures/barh_gg_tableau.png" height="200">
<img src="./figures/pie_gg_tableau.png" height="200"><img src="./figures/density_gg_tableau.png" height="200">
<img src="./figures/ci_gg_tableau.png" height="200"><img src="./figures/rcap_gg_tableau.png" height="200">
<img src="./figures/box_gg_tableau.png" height="200">


## Cividis color scheme

### white_cividis
<img src="./figures/scatter_white_cividis.png" height="200"><img src="./figures/line_white_cividis.png" height="200">
<img src="./figures/mlabel_white_cividis.png" height="200"><img src="./figures/bygraph_white_cividis.png" height="200">
<img src="./figures/bar_white_cividis.png" height="200"><img src="./figures/barh_white_cividis.png" height="200">
<img src="./figures/pie_white_cividis.png" height="200"><img src="./figures/density_white_cividis.png" height="200">
<img src="./figures/ci_white_cividis.png" height="200"><img src="./figures/rcap_white_cividis.png" height="200">
<img src="./figures/box_white_cividis.png" height="200">

### black_cividis
<img src="./figures/scatter_black_cividis.png" height="200"><img src="./figures/line_black_cividis.png" height="200">
<img src="./figures/mlabel_black_cividis.png" height="200"><img src="./figures/bygraph_black_cividis.png" height="200">
<img src="./figures/bar_black_cividis.png" height="200"><img src="./figures/barh_black_cividis.png" height="200">
<img src="./figures/pie_black_cividis.png" height="200"><img src="./figures/density_black_cividis.png" height="200">
<img src="./figures/ci_black_cividis.png" height="200"><img src="./figures/rcap_black_cividis.png" height="200">
<img src="./figures/box_black_cividis.png" height="200">

### gg_cividis
<img src="./figures/scatter_gg_cividis.png" height="200"><img src="./figures/line_gg_cividis.png" height="200">
<img src="./figures/mlabel_gg_cividis.png" height="200"><img src="./figures/bygraph_gg_cividis.png" height="200">
<img src="./figures/bar_gg_cividis.png" height="200"><img src="./figures/barh_gg_cividis.png" height="200">
<img src="./figures/pie_gg_cividis.png" height="200"><img src="./figures/density_gg_cividis.png" height="200">
<img src="./figures/ci_gg_cividis.png" height="200"><img src="./figures/rcap_gg_cividis.png" height="200">
<img src="./figures/box_gg_cividis.png" height="200">

