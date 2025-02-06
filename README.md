![KL+RP+IBE+EFS](inst/Belka-Losy-absolwentow-Kolor-PL.png)

[![Travis build status](https://travis-ci.org/tzoltak/MLASZdane.svg?branch=master)](https://travis-ci.org/tzoltak/MLASZdane)
[![Coverage status](https://codecov.io/gh/tzoltak/MLASZdane/branch/master/graph/badge.svg)](https://codecov.io/github/tzoltak/MLASZdane?branch=master)

# MLASZdane

Pakiet został opracowany w ramach projektu *Monitorowanie losów edukacyjno-zawodowych absolwentów i młodych dorosłych* (POWR.02.15.00-IP.02-00-004/16) prowadzonego w Instytucie Badań Edukacyjnych w ramach działania 2.15. Kształcenie i szkolenie zawodowe dostosowane do potrzeb zmieniającej się gospodarki II. osi priorytetowej Efektywne polityki publiczne dla rynku pracy, gospodarki i edukacji Programu Operacyjnego Wiedza, Edukacja, Rozwój.

Obecnie pakiet służy do agregacji wskaźników na potrzeby Monitoringu Karier Absolwentów, a dawniej na potrzeby projektu MLASZ.

# Instalacja / aktualizacja

Pakiet nie jest dostępny na CRAN, więc trzeba instalować go ze źródeł.

Instalację najprościej przeprowadzić wykorzystując pakiet *devtools*:

```r
install.packages('devtools') # potrzebne tylko, gdy nie jest jeszcze zainstalowany
devtools::install_github('bartplat/MLASZdane', build_opts = c("--no-resave-data"))
```

Dokładnie w ten sam sposób można przeprowadzić aktualizację pakietu do najnowszej wersji.
