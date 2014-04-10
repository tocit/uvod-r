Nenápadný půvab R
========================================================
author: Petr Kočí, ihned.cz/data
date: Praha, ??. dubna 2014
font-family: "Helvetica"

Co je R
========================================================

Proč R
========================================================
- rychle roste
- poměrně snadno se učí (nenápadný přechod uživatel -> programátor)
- dostatečně univerzální pro to, abyste ho nemuseli vůbec opouštět (získání a čištění dat, analýza dat, prezentace)
- má jedno z nejlepších _IDE_ RStudio
- rozsáhlá a vstřícná komunita uživatelů/vývojářů
- software svobodný i zdarma

Proč R
========================================================
[Článek o R v New York Times (2009)](http://www.nytimes.com/2009/01/07/technology/business-computing/07program.html?pagewanted=all&_r=0)
>“R is a real demonstration of the power of collaboration, and I don’t think you could construct something like this any other way,” Mr. Ihaka said. “We could have chosen to be commercial, and we would have sold five copies of the software.”

Balíčky
========================================================
- v základní instalaci R najdete základní balík funkcí
- chcete-li něco jiného, najděte specializovaný balíček
- v nich spočívá největší síla R, nyní je jich přes 5000
- snadno se instalují a dobře spolu fungují
- základní zdroj balíčků: [Comprehensive R Archive Network (CRAN)](http://cran.r-project.org/)
- Task Views

Balíčky
========================================================

```r
# nainstaluj balíček pro pohodlnější práci s textovými řetězci
install.packages("stringr")

#nahraj balíček do paměti
library(stringr)

# nebo
require(stringr)

# vypiš všechny dostupné balíčky
available.packages()
```


Slide With Plot
========================================================


```r
plot(cars)
```

![plot of chunk unnamed-chunk-2](uvod-r-figure/unnamed-chunk-2.png) 

