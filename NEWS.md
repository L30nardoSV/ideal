# ideal 1.6.0

## Other notes

* Added a `NEWS.md` file to track changes to the package

# ideal 1.4.0

## New features

* Specified single go term selection for generating heatmaps of gene signatures
* Added support for logFC shrinkage, following the latest devels of DESeq2

## Bug fixes

* Corrected output for the vignette, as html_document2 is now deprecated
* Menus are back in the expanded form
* Fixed the behavior with addMLE

## Other notes

* Added further progress indicators to give feedback during lengthy steps
* Improved ggplotCounts for better scale display, using exact arg matching, defaulting to the transformed counts

# ideal 0.99.0

## New features

* Ready for Bioc submission
* Completed the news

# ideal 0.9.1

## New features

* Added Instructions fully from rendered version of the vignette to have available at runtime
* Added support for downloading all plots and tables

# ideal 0.9.0

## New features

* Interactive tours are covering now all tabs, with extensive walkthroughs for the user
* Added all screenshots to vignette

# ideal 0.6.2

## New features

* Interactive tours are now available, coded in external files
* Travis-CI is now supported

# ideal 0.6.0

## New features

* Added MA plot with extra custom list to avoid manual selection of many genes
* MA plot function now automatically supports subset of gene to be extra plotted
* Added documentation with roxygen to all functions
* Heatmap functions for genes annotated to a GO term as signature
* Template report also provided
* Full draft of vignette now available, working towards bioc submission
* Added textual help to all sections, with collapsible element
* Added proof of principle to have interactive tours based on rintrojs

# ideal 0.4.0

## New features

* Gene box info added, based on rentrez
* New look for MA plots and volcano plots

# ideal 0.3.0

## New features

* Restructuring of the folders done, package can be correctly installed, loaded - namespace, description are set up
    
# ideal 0.2.0

## New features

* Correct structure of the package

# ideal 0.1.0

## New features

* Package created!