# SCINCE FAIR ~~POSTER~~ WEBSITE
### Laget av Didrik Wiig-Andersen <br></br>

### Denne nettsiden inneholder besvarelser for følgende oppgaver:
- [Terningkast](#Terningkast)
- [Radiokativitet](#Radioaktivitet)

## Terningkast
En sekssidet terning viser kun én side etter å ha blitt kastet. På bakgrunn av dette er sannsynligheten for å få et spesielt ønsket tall 1/6 eller 16.7%. Basert på sannsynligheten må man derfor regne med å kaste en terning seks ganger for å få et ønsket tall (en sekser). Det er likevel slik at man i virkeligheten kan oppleve å få ønsket tall på første kast, eller å ikke få ønskede tall selv om man har kastet 10 ganger. 

```
import random

t = 0

while t < 6:
t = random.randint(1, 6)
print(t)
```

Koden vil fungere likt som en terning hvor målet er å få en sekser. Koden fungerer slik: 

```
import random
```
Vi begynner med å inkludere python biblioteket **random** som blant annet inneholder `methods` slik som **.randint(x, y)**. Med **.randint(x, y)** kan vi få tilfeldige tall innenfor <x, y> intervallet. 

```
t = 0
```
Vi lager en variabel (int) med navn **t** og setter dens verdi til 0. 

```
while t < 6:
t = random.randint(1, 6)
print(t)
```
Vi setter dermed opp en `while - loop` som vil kjøre så lenge verdien av t er under 6. Loopen vil kjøre minst èn gang fordi t er satt til 0 i begynnelsen av programmet. t vil dermed få en ny, tilfeldig, verdi mellom 1 og 6 og videre printes til terminalen. Loopen kjører igjen dersom t < 6.
![](MEDIA/holed-cube.png)

## Radioaktivitet








