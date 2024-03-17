# Interactive functionality

Ontwerp en maak voor een opdrachtgever een interactieve toepassing die voor iedereen toegankelijk is.


## Context

Deze leertaak hoort bij sprint 9 "The Web is for Everyone". Dit is een leertaak die je uitvoert voor een opdrachtgever.

In het college S09W1-01-Sprintplanning-The-Web-Is-For-Everyone wordt de opdracht uitgelegd.

Bij deze leertaak hoort de deeltaak:
- [UML Diagram](https://github.com/fdnd-task/uml-diagram) (Sprint 08)
- [Progressive Enhancement](https://github.com/fdnd-task/progressive-enhancement)


## Doel van deze opdracht

Tim Berners-Lee, de uitvinder van het internet zei: "_The power of the Web is in its universality. Access by everyone regardless of disability is an essential aspect._"

Het doel van deze opdracht is te leren hoe je een interactieve website kan ontwerpen en maken die voor iedereen toegankelijk is.


## Werkwijze

Ontwerp en maak een functionaliteit voor je opdrachtgever op basis van een _user story_. De _user stories_ waar je aan gaat werken gaan over User Generatied Content. Hiervoor moet je data opslaan met een formulier en POST.


Voor deze opdracht doorloop je alle fases van de DLC [analyseren](#analyseren), [ontwerpen](#ontwerpen), [bouwen](#bouwen), [integreren](#integreren) en [testen](#testen).


### Analyseren

In de analysefase inventariseer je wat er moet gebeuren om een taak uit te voeren. Je kiest een _user story_ waar je aan gaat werken en onderzoekt hoe het posten van data werkt met de REST-API.

#### Sprintplanning
1. Lees de instructies van deze leertaak zorgvuldig door
2. Bekijk de verschillende fases van de DLC en wat je per fase gaat doen
3. Bekijk de planning van [sprint 9](https://programma.fdnd.nl/data-driven-web/the-web-is-for-everyone) en wat je per week gaat doen
4. Bespreek wat je aan werk verwacht en maak aantekeningen. (wat komt je bekend voor, wat heb je al vaker gedaan of wat lijkt je lastig)

#### User Stories
Kies een _user story_ uit de backlog van het project waar je aan gaat werken. (of schrijf er zelf een)
De projecten staan bij [FDND Agency](https://github.com/fdnd-agency).

#### Directus REST-API
Bespreek met je projectcoach per _user story_ hoe je data kan posten en of er (al) een POST endpoint is en hoe deze werkt.

### Bronnen analyseerfase

* [Wat is een REST API nou echt: het basisidee](https://blog.wearefrank.nl/wat-is-een-rest-api-nou-echt-het-basisidee)


### Ontwerpen

In de ontwerpfase bedenk en schets je eerst wat je gaat maken. 

Eerst ontwerp en bouw je de _core functionality_ van je website in HTML en met behulp van formulieren en NodeJS, voor het server-side afhandelen van het posten van data. 

#### Wireflow
Teken de _core-functionalty_ van de _user story_ in een wireflow. Zorg dat je de verschillende states van het formulier, het versturen van data, een _succes state_ en mogelijke _errors_ ook tekent. 

#### Breakdown
Maak een breakdown-schets en beschrijf de juiste HTML formulier-elementen die je nodig hebt. Bedenk daarna de routing en pseudo-code voor de data-flow en control-flow van de node-code. 

### Bronnen ontwerpfase
* [Wireframing User Flow with Wireflows](https://balsamiq.com/learn/articles/wireflows/)
* [The Input (Form Input) element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/Input)
* [The Form element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/form)

### Bouwen

#### Inrichten ontwikkelomgeving

Je gaat een server-side website bouwen met Node/Express/EJS gebaseerd op een REST API met JSON. Installeer de Node ontwikkelomgeving en installeer de packages die je nodig hebt. Maak de files en folders aan die je nodig hebt op de Node server. Gebruik hiervoor `npm install`, en kopieer uit je project uit de vorige sprint de code die je mee wilt nemen.

#### Progressive enhancement

1. Eerst bouw je de _core functionality_ van je website in HTML en met behulp van formulieren en NodeJS, voor het server-side afhandelen van het posten van data. (Content layer)
2. Daarna voeg je CSS toe voor feedback voor de gebruiker en om de huisstijl toe te passen. (Presentation layer)
3. Zo nodig voeg je CSS en client-side JS toe om de User Experience te verbeteren. (Client-side scripting)


### Integreren
In de integratiefase voer je de aanpassingen door zodat iedereen ze kan zien.

Als je helemaal klaar bent en alles lokaal werkt ga je verder met het publiceren van jouw project op internet. Omdat we met Node werken is dit iets ingewikkelder dan voorheen, er moet namelijk een serveromgeving opgestart worden. Wij gebruiken cyclic.sh als hostingpartij maar je mag natuurlijk je eigen voorkeur volgen als die anders is.

### Testen

Om er voor te zorgen dat de functionaliteit voor iedereen toegankelijk is, test je je werk in verschillende browsers en devices.

Gebruik [caniuse.com](https://caniuse.com) om te achterhalen welke technieken browsers ondersteunen. 

## Criteria
*Definitions of done*


Deze opdracht is done als:

- [ ] Je hebt interactieve functionaliteit ontworpen en gemaakt met Node, Express, EJS en een REST API en HTML, CSS en misschien client-side JS
- [ ] Jouw gebruikers kunnen iets achterlaten of toevoegen op jouw website (user generated content)
- [ ] Je website is online gepubliceerd
- [ ] Je hebt gewerkt volgens de verschillende fases van de development-lifecycle en je hebt je proces bijgehouden in de Wiki
- [ ] Je hebt je werk getest in verschillende browsers en devices en de test gedocumenteerd in je wiki
- [ ] Je hebt in de Readme bij 'Kenmerken' uitgelegd wat Progressive Enhancement is en hoe je dit hebt toegepast

