# Analiza podatkov s programom R - 2021/22

Vzorčni repozitorij za projekt pri predmetu APPR v študijskem letu 2021/22. 

## Vpliv inflacije na socialno stanje prebivalstva v Evropi

Analiziral bom, kakšen vpliv ima inflacija na socialno stanje prebivalstva v evropskih državah. Osredotočil se bom na iskanje povezave med inflacijo in socialnimi kazalniki, kot so na primer stopnja brezposelnosti, stopnja tveganja za revščino, spreminjanje bruto/neto plač in povprečna potrošnja gopodinstev. pri tem bom kot kazalnik infacije uporabil index HCIP(Harmonised Index of Consumer Prices) - Harmonizirani indeks cen življenjskih potrebščin.

Tukaj boste napisali, kje ste dobili podatke, ter kakšen je vaš cilj.

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
