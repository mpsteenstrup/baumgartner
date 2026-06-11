### Indholdsfortegnelse

* [Introduktion](https://mpsteenstrup.github.io/baumgartner/introduktion)
* [Frit fald](https://mpsteenstrup.github.io/baumgartner/fritfald)
* [Luftmodstand](https://mpsteenstrup.github.io/baumgartner/luftmodstand)
* [Atomsfærens densitet](https://mpsteenstrup.github.io/baumgartner/atmosfaere)
* [Den fulde model](https://mpsteenstrup.github.io/baumgartner/fulde-model)

basal programmering

* [Grundelementer i programmering](https://mpsteenstrup.github.io/baumgartner/former)
* [Former](https://mpsteenstrup.github.io/baumgartner/basal-programmering)
* [Bevægelse](https://mpsteenstrup.github.io/baumgartner/bevaegelse)

# Den fulde model

Vi har nu byggeklodserne til den endelige model af faldet.

Den fulde model indeholder en eksponentielt aftagende afmosfære og skrives som
$$
F = m\cdot g-0.5\cdot c\cdot \rho_0\cdot e^{-0.0001166\cdot h}\cdot A\cdot v^2
$$


Data for det faktiske hop er taget ud fra grafen i Introduktions afsnittet og er nok ikke sætligt præcist.

[ https://glowscript.org/#/user/mps/folder/baumgartner/program/fuldmodel](https://glowscript.org/#/user/mps/folder/baumgartner/program/fuldmodel)


* Kør simuleringen og beskriv hvilken delen af kuven den faldet den kan beskrive.
* Beskriv hvilken dele den har svært ved.
* Prøv at lav om på parametrene ( husk variabelkontrol) og se hvordan det ændrer på grafen. I kan sætte rate på fra 40 hvis det går for langsomt.
* På videoen kan man se at han begynder at rotere omkring 1 minut inde i faldet. Hvilken parametre har det betydning for og hvad vil det betyde for simuleringen hvis den ændrer sig.