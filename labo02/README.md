# Labo 2 - reflecties

Naam: Vale De Clercq

## 2. Selectors lezen

Welke elementen raakt elke selector? Eén zin per selector.

- a. `header nav ul li a`: selecteert alle a elementen die in li,ul,nav of header bevinden 
- b. `article > p`: selecteert alle p's die in een article zitten
- c. `.uren li:nth-child(3)`: het 3de li element binnen een element met de klas uren
- d. `h2 ~ p`: selecteert alle p elementen die na een h2 staan en dezefde ouder hebben
- e. `.rassen li:first-child`: selecteert het eerste li binnen een li met de class rassen

## 3. Voorspel, dan kijk

Vul de eerste twee kolommen in vóór je de pagina opent. Trede: herkomst, specificiteit, volgorde of overerving (of iets anders, benoem het).

| vraag | mijn voorspelling (kleur) | beslissende trede | uitkomst in de browser | juist? |
|---|---|---|---|---|
| 1 |groen |specifiteit |groen |ja |
| 2 |blauw |volgorde |blauw |ja |
| 3 |blauw |specifiteit |rood |ja |
| 4 |groen |specifiteit |rood |nee | je moest kijken naar de volgorde
| 5 |blauw |specifiteit |blauw |ja |
| 6 |blauw |specifiteit |blauw |ja |
| 7 |rood |overerving |rood |ja |
| 8 |rood |specifiteit |blauw |nee | andere class werd gebruikt
| 9 |rood |important |rood |ja |
| 10 |groen |volgorde |blauw |nee | geen idee waarom

Bij welke vraag zat je fout, en wat was de reden? (Alles juist? Welke vraag duurde het langst, en waarom?)

## 4. De nabouw

- Welke selector koos je voor de links in de navigatie, en waarom geen class?
    Nav a, doordat alle links dezelfde stijl gebruiken in nav.
- Welke regel kostte je het meeste tijd, en wat was uiteindelijk de oorzaak?
    .kaart li:nth-child(odd), omdat die de meeste voorwaardes had.
    
## 6. Je site

- Welke drie waarden staan in je tokenblok, en waarom die?
- Wat verandert er in je site als je één token wijzigt?

## Thuis: R2.3 (met AI)

Prompt en onbewerkte output staan in `review/`. Minstens vijf bevindingen, elk met een verwijzing naar de sectie of het foutnummer:

1. 
2. 
3. 
4. 
5. 
