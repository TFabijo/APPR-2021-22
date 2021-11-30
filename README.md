# Analiza podatkov s programom R - 2021/22

Vzorčni repozitorij za projekt pri predmetu APPR v študijskem letu 2021/22. 

## vpliv inflacije

Analiziral bom, kakšen vpliv ima inflacija na brezposelost, rast plač in rast BDP-ja v evropskih državah. Pri tem bom kot kazalnik infacije uporabil index HCIP(Harmonised Index of Consumer Prices) - Harmonizirani indeks cen življenjskih potrebščin. pred tem bom nardil osnovno časovno analizo inflaciske stopnje,brezposelosti, rast plač in BDP-ja po državah in jih primerjal med njim, s tem bom izvedel ali dinamika padanja oziroma naraščanja po evropskih državah podobna. Podobno bo sledila časovna anliza stopenj. Na koncu pa bom pri vsaki državi iskal korelacijo med inflacijo in ostalimi faktorji.

### Viri
Eurostat:
https://ec.europa.eu/eurostat/data/database

### Tabele
- Tabela inflaciskih stopenj po državah
    - stolpci: država,leto,stopnja inflacije
- Tabela stopenj brezposelosti po državah
    - stolpci: država, leto, stopnja brezposelosti
- Tabela povprečne in medianske plače
    - stolpci: država, leto, povprečna plača,medianska plača
- Tabela rasti BDP-ja
    - stolpci: država, leto, letna rast BDP-ja



## Program

Glavni program in poročilo se nahajata v datoteki `projekt.Rmd`.
Ko ga prevedemo, se izvedejo programi, ki ustrezajo drugi, tretji in četrti fazi projekta:

* obdelava, uvoz in čiščenje podatkov: `uvoz/uvoz.r`
* analiza in vizualizacija podatkov: `vizualizacija/vizualizacija.r`
* napredna analiza podatkov: `analiza/analiza.r`

Vnaprej pripravljene funkcije se nahajajo v datotekah v mapi `lib/`.
Potrebne knjižnice so v datoteki `lib/libraries.r`
Podatkovni viri so v mapi `podatki/`.
Zemljevidi v obliki SHP, ki jih program pobere,
se shranijo v mapo `../zemljevidi/` (torej izven mape projekta).
