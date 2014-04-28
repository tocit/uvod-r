Lehký úvod do R
========================================================
author: Petr Kočí, ihned.cz/data
date: Praha, 29. dubna 2014
font-family: "Helvetica"

Prosím, stáhněte si a nainstalujte
========================================================
- [R](http://mirrors.nic.cz/R/)
- [R Studio](https://www.rstudio.com/)

Co je R
========================================================
- dialekt [programovacího jazyka S](http://en.wikipedia.org/wiki/S_(programming_language))
- vývoj od 1976 v Bell Labs
- R vzniká v roce 1991, autory jsou statistici Ross Ihaka a Robert Gentleman z University of Auckland
- v současné době standard při výuce statistiky na středních i vysokých školách, zejména v zámoří, ale rychle se šíří do Evropy

Alternativy k R
========================================================
- SPSS
- Python + [iPython notebook](http://ipython.org/notebook.html)
- [další](http://blog.revolutionanalytics.com/2013/10/r-usage-skyrocketing-rexer-poll.html)

Proč R
========================================================
- nenápadný přechod uživatel -> programátor
- "reproducible research "
- dostatečně univerzální pro to, abyste ho nemuseli vůbec opouštět (získání a čištění dat, analýza dat, prezentace)
- má jedno z nejlepších _IDE_ [RStudio](https://www.rstudio.com/)
- rozsáhlá a vstřícná [komunita uživatelů/vývojářů](http://stackoverflow.com/questions/tagged/r)

Proč R
========================================================
## Svobodný i zdarma
[Článek o R v New York Times (2009)](http://www.nytimes.com/2009/01/07/technology/business-computing/07program.html?pagewanted=all&_r=0)
>“R is a real demonstration of the power of collaboration, and I don’t think you could construct something like this any other way,” Mr. Ihaka said. “We could have chosen to be commercial, and we would have sold five copies of the software.”-

Proč R
========================================================
## Učte se z příkladů

Příklad 1
- [Model výsledku senátních voleb v USA  - Amanda Cox a spol.](http://www.nytimes.com/newsgraphics/2014/senate-model/)
- [Natáhněte si ho do Rka a pohrajte si s ním sami](https://github.com/TheUpshot/leo-senate-model)

Příklad 2
- [Proportional symbol mapping in R](http://www.jstatsoft.org/v15/i05/paper)
- [Kde sbíral hlasy Babiš a kde Okamura?](http://data.blog.ihned.cz/c1-61082560-kde-sbiral-hlasy-babis-a-kde-okamura-prohlednete-si-podrobne-mapy)

Balíčky
========================================================
- v základní instalaci R najdete základní balík funkcí
- chcete-li něco jiného, najděte specializovaný balíček
- v nich spočívá největší síla R, nyní je jich přes 5000
- snadno se instalují a dobře spolu fungují
- základní zdroj balíčků: [Comprehensive R Archive Network (CRAN)](http://cran.r-project.org/)
- [Task Views](http://cran.r-project.org/web/views/)

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


Pracovní adresář
========================================================
getwd()
setwd()

Získání dat
========================================================
download.file()


```r
plot(cars)
```

![plot of chunk unnamed-chunk-2](uvod-r-figure/unnamed-chunk-2.png) 

