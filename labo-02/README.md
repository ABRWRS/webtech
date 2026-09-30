# Labo 2 - reflecties

Naam: (Aldo Brouwers)

## 2. Selectors lezen

Welke elementen raakt elke selector? Eén zin per selector.

- a. `header nav ul li a`: elke link die genest zit in een li, in een ul, in een nav, in een header.
- b. `article > p`: elke paragraaf die een direct kind is van een article.
- c. `.uren li:nth-child(3)`: elk li-element dat het derde kind van zijn ouder is en binnen een element met class uren staat.
- d. `h2 ~ p`: elke paragraaf die na een h2 komt en dezelfde ouder heeft.
- e. `.rassen li:first-child`: elk li-element dat het eerste kind van zijn ouder is en ergens binnen een element met class rassen staat.

## 3. Voorspel, dan kijk

Vul de eerste twee kolommen in vóór je de pagina opent. Trede: herkomst, specificiteit, volgorde of overerving (of iets anders, benoem het).

| vraag | mijn voorspelling (kleur) | beslissende trede | uitkomst in de browser | juist? |
|---|---|---|---|---|
| 1 | groen | herkomst | groen | juist |
| 2 | blauw | volgorde | blauw | juist |
| 3 | rood | specificiteit | rood | juist |
| 4 | rood | herkomst (.v4 > a werkt niet want a is niet een direct kind van v4)| rood | juist |
| 5 | blauw | specificiteit | blauw | juist |
| 6 | blauw | specificiteit | blauw | juist |
| 7 | rood | herkomst | rood | juist |
| 8 | blauw | specificiteit of volgorde (weet niet goed welke van de 2) | blauw | juist |
| 9 | rood | specificiteit (door de !important) | rood | juist |
| 10 | groen | volgorde/herkomst (de blue word niet gelezen door de fout) | groen | juist |

Bij welke vraag zat je fout, en wat was de reden? (Alles juist? Welke vraag duurde het langst, en waarom?)

Ik had alles juist maar vraag 5 duurde het langst omdat ik verward was met de 3 classes achter elkaar

## 4. De nabouw

- Welke selector koos je voor de links in de navigatie, en waarom geen class?

Ik koos voor nav a omdat dat makkelijk was en alle links die in de toekomst in de nav er bij komen ook omvat. Ik koos geen class omdat de links en nav geen class hebben.

- Welke regel kostte je het meeste tijd, en wat was uiteindelijk de oorzaak?

De regels met :hover en :focus omdat ik de mooie syntax wou gebruiken.

## 6. Je site

- Welke drie waarden staan in je tokenblok, en waarom die?

  --bg-color: #121212;  Omdat ik darkmode makkelijker vind op de ogen.
  --text-color: #ffffff;
  --font-family-base: "JetBrainsMono", monospace; Ik vind dit makkelijker om te lezen.
  --font-size-base: 16px; Omdat ik niet wist welke andere size ik kon toevoegen.


- Wat verandert er in je site als je één token wijzigt?

De kleur van de hele pagina

## Thuis: R2.3 (met AI)

Prompt en onbewerkte output staan in `review/`. Minstens vijf bevindingen, elk met een verwijzing naar de sectie of het foutnummer:

1. 
2. 
3. 
4. 
5. 
