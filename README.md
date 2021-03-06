rdryad
======

[![Build Status](https://api.travis-ci.org/ropensci/rdryad.png)](https://travis-ci.org/ropensci/rdryad)

`rdryad` is a package to interface with the Dryad data repository.

Dryad API documentation here: http://wiki.datadryad.org/wiki/API

There is no need to get an API key, as in some of our other packages. They use an OAI-PMH (Open Archives Initiative Protocol for Metadata Harvesting) interface; see here for a description of OAI-PMH: http://en.wikipedia.org/wiki/Open_Archives_Initiative_Protocol_for_Metadata_Harvesting

We now implement the ImpactStory API.  You can query for the data they serve up using `totimp`.  Use `totimp_dryad` to get metrics for just Dryad datasets.  See here for their documentation: http://total-impact.org/about#toc_2_16


## Quick start

### Installation

Install Dryad from CRAN


```r
install.packages("rdryad")
```

Or install development version of rdryad from GitHub:


```r
install.packages("devtools")
devtools::install_github("rdryad", "ropensci")
```


```r
library('rdryad')
```

### Examples

**We'll have examples up soon.**

## Meta

* Please [report any issues or bugs](https://github.com/ropensci/rdryad/issues).
* License: MIT
* Get citation information for `rdryad` in R doing `citation(package = 'rdryad')`

[![](http://ropensci.org/public_images/github_footer.png)](http://ropensci.org)

### Data provided by...

Data is provided from the Dryad API.

<a href="http://wiki.datadryad.org/Data_Access"><img src="http://wiki.datadryad.org/wg/dryad/images/b/bc/Dryad_web_banner_small_v4.jpg" alt="Dryad API" /></a>
