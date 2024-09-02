
<!-- README.md is generated from README.Rmd. Please edit that file -->

# owhaley

<!-- badges: start -->
<!-- badges: end -->

The goal of owhaley is to produce a whale with a nice message for
STAT1378 tutorial work.

owhaley is a work in progress and can be downloaded from
[GitHub](https://github.com/):

``` r
install.packages("remotes")
library(remotes)
remotes::install_github("van-whiteman/owhaley")
```

## Example

`owhaley` contains one function only. `say()` will echo a randomly
chosen whale-themed phrase for your enjoyment.

``` r
library(owhaley)
say() 
#> 
#>             ------ 
#>            Whale, whale, whale...look who's here! 
#>             ------ 
#>                \   
#>                 \  
#>                  \
#>      .-'
#> '--./ /     _.---.
#> '-,  (__..-`       \
#>    \          .     |
#>     `,.__.   ,__.--/
#>      '._/_.'___.-`
```

Alternatively, you can supply your own phrase

``` r
say("I'm beached as bro!!!")
#> 
#>             ------ 
#>            I'm beached as bro!!! 
#>             ------ 
#>                \   
#>                 \  
#>                  \
#>      .-'
#> '--./ /     _.---.
#> '-,  (__..-`       \
#>    \          .     |
#>     `,.__.   ,__.--/
#>      '._/_.'___.-`
```

’t forget to commit and push the resulting figure files, so they display
on GitHub and CRAN.
