# Analiza podatkov s programom R - 2021/22

Vzorčni repozitorij za projekt pri predmetu APPR v študijskem letu 2021/22. 

## analiza inflacije in brezposelosti v Evropi

Analiziral bom, kakšen vpliv ima inflacija na brezposelost v evropskih državah. Osredotočil se bom na iskanje povezave med inflacijo in brezposelostjo. pri tem bom kot kazalnik infacije uporabil index HCIP(Harmonised Index of Consumer Prices) - Harmonizirani indeks cen življenjskih potrebščin. pred tem bom nardil osnovno časovno analizo inflaciske stopnje po državah in jo med nnjimi primerjal. Podobno bo sledila časovna anliza stopenj brezposelosti v državah. Na koncu pa bom pri vsaki državi iskal korelacijo med inflacijo in brezposelostjo.

### Viri
Eurostat:
https://ec.europa.eu/eurostat/data/database

### Tabele
- Tabela inflaciskih stopenj po državah
- Tabela stopenj brezposelosti po državah


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
