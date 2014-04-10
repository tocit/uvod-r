Stručný úvod do R
========================================================
author: Petr Kočí, ihned.cz/data
date: Praha, ??. dubna 2014
font-import: http://fonts.googleapis.com/css?family=Exo+2:400,500,400italic,500italic,&subset=latin-ext,latin
font-family: "Exo+2"

Co je R
========================================================



For more details on authoring R presentations click the
**Help** button on the toolbar.

- Bullet 1
- Bullet 2
- Bullet 3

Balíčky
========================================================
- v základní instalaci R najdete základní balík funkcí
- chcete-li něco jiného, najděte specializovaný balíček
- v nich spočívá největší síla R, nyní je jich přes 5000
- základní zdroj balíčků: [Comprehensive R Archive Network (CRAN)](http://cran.r-project.org/)

```r
# nainstaluj balíček pro pohodlnější práci s textovými řetězci
install.packages("stringr")

#nahraj balíček do paměti
library(stringr)

# nebo
require(stringr)
```


Slide With Plot
========================================================


```r
plot(cars)
```

![plot of chunk unnamed-chunk-2](uvod-r-figure/unnamed-chunk-2.png) 

