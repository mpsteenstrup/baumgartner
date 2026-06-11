Ved brug af Newtons anden lov vil vi gennem denne øvelse opbygge en model for det spring som Felix Baumgartner foretog i Oktober 2012 fra en højde af 39 km og brød lydmuren. 

Newtons anden lov siger at $$F=m\cdot a$$, hvor F er kraften i newton, N, m er massen i kg og a er accelerationen.
Her skal vi bruge tyngdekraften som i nærheden af Jorden er $$ F_T = m\cdot g$$ hvor $$g = -9,82m/s^2$$ er tyngdeaccelerationen. 

Hvis vi sætter $$F=F_T$$ får vi $$m\cdot a = m\cdot g$$ eller at accelerationen bliver $$ a = g $$ og det er jo derfor at g har navnet tyngdeaccelerationen.

Her kommer koden for en faldende bold.

Prøv at kør koden ved at trykke på play knappen.

* hvad viser animationen?
* hvad viser grafen?

[https://glowscript.org/#/user/mps/folder/baumgartner/program/fritfald](https://glowscript.org/#/user/mps/folder/baumgartner/program/fritfald)



For at forstå hvad der foregår i løkken tager vi den langsomt.

"while bold.pos.y>=0:" angiver at vi skal fortsætte løkken, indtil bolden rammer jorden (y=0). 

"rate(10)" angiver hastigheden for animationen, prøv at skift til 100 eller 1.

"f1.plot(t,bold.pos.y)" indtegner punktet (t,y) for de værdier tiden og højden har netop nu.

"bold.v = bold.v + a*dt" er måden vi opdaterer hastigheden. Hvis vi læser det fra venstre til højre siger ligningen at hastighen er lig med hastigheden før plus ændringen i hastigheden. Ændringen i hastigheden er accelerationen, a, ganget med det tidsskridt vi tager, dt.

" bold.pos = bold.pos  + bold.v*dt" gør det samme for positionen, som er positionen før plus hastighedn gange tiden, altså distancen.

"t = t + dt", her opdaterer vi tiden

Tid til at ændre noget ved koden, husk at beskriv hvad der kommer ud af det.
* Brug (t,s) grafen til at finde ud af hvor lang tid det tager en bold at falde 10 meter.
* Brug (t,v) grafen til at finde boldens hastighed når den rammer jorden.
* Undersøg om hastigheden bolden rammer jorden ændrer sig hvis den starter med en hastighed på 10 meter per sekund op, ved at skift starthastighed til v0=10.
* Hvad hvis det var 10 meter i sekundet ned, (v0=-10)?
* Gå tilbage til simuleringen med v0=10 og se om I kan forklare hvorfor bolden næsten rammer med samme hastighed.
* Undersøg hvilken betydning boldens masse, m, har for bevægelsen.

Vi er interesserede i om Felix Baumgartner kan bryde lydmuren, på 343m/s.

* Undersøg hvor langt bolden skal falde for at opnå lydens hastighed. ( lav rate(10) om til noget andet hvis I synes det går for langsomt).

Baumgartners hop var fra ca 39.000 meters højde, så hans højde var altså stor nok.

* Undersøg hvad hans maksimale hastighed med den højd vil være.
* Find hastigheden af en faldskærmsudspringer på nettet, før faldskærmen udløses.
* Diskuter om jeres simulering er realistisk og overvej hvilke andre fysiske størrelser modellen skal medtage for at blive mere realistisk.


### Egne spørgsmål

I har nu arbejdet med en model af en bold som bevæger sig i et tyngdefelt, hvor det kun er en konstant tyngdekraft som påvirker bolden. I skal nu overvej hvad man kan undersøge med en så simpel mode.

* Kom med forslag til ting som kunne være interessante at undersøge, og hvad undersøgelsesspørgsmålet skulle være. 
* Kom med et bud på hvad der skal ændres i modellen ( I behøver ikke implementerer det i koden).
* Hvis I kan, så prøv at implementer en enkelt ide og se om I kan besvare jeres spørgsmål. 

