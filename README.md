Financial Stress Index Data
===========================


The R package ```stressr``` provides convenient access to the financial stress index and components data provided by the Federal Reserve Bank of Cleveland.  The package provides data download functions and some representative plots along the same categories as provided by the bank. See the [FRB's terms of use](http://www.clevelandfed.org/utilities/terms_of_use.cfm?DCS.nav=Footer) regarding these data.   

As a simple example of gathering data and drawing simple plots consider the R code
```{r}
require(stressr)
require(lattice)
idx <- getStressIndex()
stressIndexChart(idx,"2007/")
```

Several examples of plots are shown by category below.  For details on each query and more example plots, please see the package vignette.  

Index Report
------------
<img src="man/figures/indexLine.png" width="100%"/>

Summary Report
--------------
<img src="man/figures/summaryPanels.png" width="100%"/>
<img src="man/figures/summaryLine.png" width="100%"/>
<img src="man/figures/summaryArea.png" width="100%"/>


Securitization Markets
----------------------
<img src="man/figures/securitizationLine.png" width="100%"/>
<img src="man/figures/securitizationArea.png" width="100%"/>

Real Estate Markets
-------------------
<img src="man/figures/realLine.png" width="100%"/>
<img src="man/figures/realArea.png" width="100%"/>

Funding Markets
---------------
<img src="man/figures/fundingLine.png" width="100%"/>
<img src="man/figures/fundingArea.png" width="100%"/>

Foreign Exchange Markets
------------------------
<img src="man/figures/foreignLine.png" width="100%"/>
<img src="man/figures/foreignArea.png" width="100%"/>

Equitiy Markets
-----------------------------
<img src="man/figures/equityLine.png" width="100%"/>
<img src="man/figures/equityArea.png" width="100%"/>

Credit Markets
--------------------------------------------------
<img src="man/figures/creditLine.png" width="100%"/>
<img src="man/figures/creditArea.png" width="100%"/>

Index Components
----------------
<img src="man/figures/components.png" width="100%"/>


References
----------
* See [Cleveland FRB](http://www.clevelandfed.org/research/data/credit_easing/index.cfm) for more details.

