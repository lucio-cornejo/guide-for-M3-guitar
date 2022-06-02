# A guide for the M3 guitar tuning

The goal of this project is to spread the word about
the M3 guitar tuning. I mention its definition and
then show several examples as to what kind of chords
are possible to play (comfortably) with that tuning,
many of which are practically impossible to play
in standard tuning.

Programming wise, this projects makes great use of
[knitr](https://yihui.org/knitr/)'s **asis** engine,
due to its ability to render HTML content via pure
`R` code. 

Inside the file [index.qmd](https://github.com/lucio-cornejo/guide-for-M3-guitar/blob/main/index.qmd), the `R` function
`neck(matriz, bajo, chord_name, chord_voicing)` is used in
order to produce the type of chord diagrams present in
<https://guide-virtual-m3-guitar.netlify.app/>. Such function 
automates the **HTML** table creation and its appropriate 
**CSS** styling, as a result of the paramenters given.
