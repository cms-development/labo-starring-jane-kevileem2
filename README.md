# labo-starring-jane-kevileem2

## Introductie Project

Het project dat de developers van Starring Jane kwamen tonen, is:
[mijn herrinering aan jou](https://mijnherinneringaanjou.be/#/)

Het project gaat over het verwerken van de dood van een familielid. Met een grote focus naar het kind.
Het laat ouders toe om een account te maken en een "herinnerplaats" op te stellen en kinderen toe te voegen waar ze hun eigen herinnerplaatsje hebben.

Hier kunnen de kinderen op hun eigen herinnerplaats, herinneringen toe voegen over hun overleden familielid.

herinneringen bestaan uit:

- Liedjes
- Tekst / verhalen
- Een foto
- Een spraakboodschap

Je kan deze herinnering op een plek naar keuze plakken:

- In de sterren als ster
- In de boom als blad
- In de wolken als wolk

Dit laat je dan toe om deze herrinering weer opnieuw te bekijken en eventueel te verwijderen.
Ook kunnen de kinderen met de ballon vliegen om ze een extra soort stimulans te geven om terug te komen naar de webapp.
Met de ballon kunnen ze vliegen door de wolken en door de sterren. Ze kunnen navigeren naar hun herinneringen.

---

## Workflow

### Pitches

Ze pitchen hun ideëen met de klant en werken ook nauw samen met de klant tijdens de pitches om tot een goed uitgewerkt idee te komen die in lijn staat met wat de klant wilt en wat er technisch mogelijk is.

### Concept Workshops

Dan werken ze een paar concepten uit vooralleer ze beginnen programmeren (voor de functionaliteit). In het geval van "Mijn herinnering aan jou" waren dit in totaal 4 concepten. Dit is belangrijk dat je niet een concept al begint uit te werken vooralleer terug te overleggen met de klant. Anders zou je onnodige programmaties steken in de app of moet je gewoon opnieuw beginnen wat veel tijd in beslag neemt.

#### Planning

Standaard planning waarmee ze te werk gaan:

- Illustraties en video's
- Copywriting
- UX en UI uitwerken
- Bouwen applicatie
- GDPR-compliant

### Challenges

#### Niet-technische

Zoals eerder vernoemt:

- Concept uitwerken met de klant

#### Technische

- Responsive web-app
- Content ook (gedeeltelijk) offline beschikbaar
- Mogelijkheid om de luchtballon te besturen op zowel Desktop als Mobile/Tablet
- Performant genoeg dat niet alles offline gaat bij lancering

### Sprint Planning

Wat is een sprint planning?

- Bepalen van de lengte van de sprint
- Bepalen wat er allemaal kan geprogrammeerd worde binnen die tijd
- Taken verdelen
- Na sprint demo met de klant
- Feedback van de sprints

---

## Ontwikkeling

De ontwikkeling wordt gedaan in Vue en Laravel.
De presentatie was vooral gericht naar Vue.

### Vue

- Vue is component based
- 1 file voor templating, scripts en styling
- indexedDB voor offline storage
- State management in Vue met Store
- Axios voor API calls
- Vue bus

Voor de rest heeft vue een beetje dezelfde functionaliteiten als React. Vue is in dat opzicht wel een meer lightweight oplossing aangezien de instapdrempel minder groot is.

Dat gezegd zijnde vind ik de oplossing van Vue om alles binnen 1 file te zetten langs de ene kant goed maar langs de andere kant vrij onoverzichtelijk aangezien je vrij lange files kan hebben.

Ik heb hun ook de vraag gesteld waarom ze prefereerde om prop-types te gebruiken in plaats van Typescript en ook hier ging het weer om de instapdrempel die minder groot is. Terwijl ik dit volledig snap, vind ik toch dat je niet altijd moet kiezen voor de gemakkelijkste oplossing als die niet even goed is als bv Typescript te gebruiken en de nieuwkomers hier wegwijs in te maken.

---

## Feedback

Ik vond de presentatie wel goed voor mensen die nog niet echt component based programming hebben gezien maar voor 3de jaar NMD studenten was het op sommige momenten wel vrij saai, aangezien wij eigenlijk al weten hoe het meeste van component based programming in elkaar zit.

Alsook stel ik mij dan ook de vraag of 2de jaars NMD studenten in het 1ste semester hier eigenlijk iets aan hebben aangezien die pas in het 2de semester (allesinds toen ik in het 2de zat was dit zo) component based programming zien.

Dat terzijde vond ik het project wel heel mooi en goed afgewerkt met een mooie UI waar ik wel het 1 en ander van heb opgestoken.

Ik merkte wel dat de developers in het begin een beetje nerveus waren maar naar het einde van de presentatie was dit veel beter.
