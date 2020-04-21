## Installation

Direct install (requires admin privileges):
1.	[Download and install R](https://cran.rstudio.com/)
2.	[Download and install RStudio](https://rstudio.com/products/rstudio/download/#download)

Software Centre (requires VPN connection):
1.	Open the Software Centre 
2.	In the Software Centre, in the top right hand search bar type “R for Windows”
    a.	Click on “R for Windows 3.6.2” and install – accept the default settings
    b.	Do not install Microsoft R Open 3.4.2
3.	In the Software Centre, in the top right hand search bar type “RStudio”
    a.	Click on RStudio 1.2.5001 and install – accept the default settings

## Sessions

### April 20, 2020
- RStudio Tour
- [Basic commands](https://github.com/CentreForHydrology/Introduction_to_R)
- Intro to packages: dplyr, ggplot2, tidyhydat, weathercan
- [Cheatsheets](https://rstudio.com/resources/cheatsheets/): start with Base, RStudio IDE, dplyr, ggplot2
- [rseek.org](https://rseek.org/)
- Sources: [Centre for Hydrology](https://github.com/CentreForHydrology), [tidyhydat](https://github.com/ropensci/tidyhydat), [weathercan](https://github.com/rchlumsk/tRaining)

### April 30, 2020
- More examples
- Useful snippets
- Organizing your code
- if statements and loops

## Intro R & RStudio
[R for Data Science](https://r4ds.had.co.nz/)

## Packages

- [Hydrology packages on CRAN](https://cran.r-project.org/web/views/Hydrology.html)
- [tidyhydat](https://docs.ropensci.org/tidyhydat/)
- [weathercan](https://docs.ropensci.org/weathercan/)
- [CSHShydRology](https://github.com/CSHS-CWRA/CSHShydRology)

## Tips
- [Add a header snippet](http://timfarewell.co.uk/my-r-script-header-template/)
- Use [styler](https://styler.r-lib.org/) for easy formatting
- Get help more easily using [reprex](https://www.tidyverse.org/help/)
- Make pasting links easier: 

```r
snippet pp
    "`r gsub('"', "", gsub("\\\\", "/", readClipboard()))`"
```
    [source](https://stackoverflow.com/questions/17605563/efficiently-convert-backslash-to-forward-slash-in-r)

## Other

[Style Guide](https://style.tidyverse.org/)

[Geocomputation with R](https://geocompr.robinlovelace.net/)

## Webinars
- [CSHS hydRology Introduction to R](https://www.youtube.com/watch?reload=9&v=obXb9MAlZ-M)
- [Intro to Working with Canadian Data](https://www.youtube.com/watch?v=56mrlRvTmao)
- [CSHS Webinar R Markdown with Dr Kevin Shook](https://www.youtube.com/watch?v=TH3oDhRrEy0)

## Papers

- [R-functions for Canadian hydrologists: a Canada-wide collaboration](https://www.usask.ca/hydrology/papers/Anderson_et_al_2019.pdf)
- [Data Organization in Spreadsheets](https://www.tandfonline.com/doi/full/10.1080/00031305.2017.1375989)

## How to organize your repo
More to come...




