> _Fork_ deze leertaak en ga aan de slag. Onderstaande outline ga je gedurende deze taak in jouw eigen GitHub omgeving uitwerken. De instructie vind je in: [docs/INSTRUCTIONS.md](docs/INSTRUCTIONS.md)

# Red Pers
Red pers is een toegankelijk en inclusief opleidingsplatform dat is bedoeld voor jonge, aspirerende journalisten.

## Inhoudsopgave

  * [Beschrijving](#beschrijving)
  * [Gebruik](#gebruik)
  * [Kenmerken](#kenmerken)
  * [Installatie](#installatie)
  * [Bronnen](#bronnen)
  * [Licentie](#licentie)

## Beschrijving
<!-- In de Beschrijving staat kort beschreven wat voor project het is en wat je hebt gemaakt -->
De website is erg nieuw, ze willen graag een beter versie van de website. De website bestaat nu uit elementor en ze willen graag over uit een uitgebreider functionelere versie van de website. De user experience is nog matig en kan verbetert worden. De mobiele versie is ook nog erg vaag. Zij willen graag een website zien die zich niet afhangt van plugins en programma’s als wordpress en elementor

Er zijn verschillende weergave. Waarbij artikelen worden weergeven, maar ook een onderwerp waarbij een fotogalerij wordt weer gegeven. Bij deze sprint is het de bedoeling om vooral te focussen op de artikelen, die het grootste deel van de website onderbouwd. Bij de Scrap Yard pagina kan je alle onderdelen zien van een artikel pagina. Het design mag doorontwikkeld worden. De user experience is voor nu niet goed en duidelijk, dus dat mag verbeterd worden. Bepaalde elementen zijn nog niet helemaal duidelijk.

<!-- Voeg een mooie poster visual toe 📸 -->
### Home 📸
**Desktop**

<img width="800" alt="Desktop Home" src="https://github.com/zoepje/the-web-is-for-everyone-interactive-functionality/assets/144004461/a491d466-a239-4b15-afc6-d432792dd2eb">

**Mobile**

<img width="400" alt="Mobile Home" src="https://github.com/zoepje/the-web-is-for-everyone-interactive-functionality/assets/144004461/46fc49e1-5532-493f-a5b2-62b665771de1">

<img width="400" alt="Mobile Menu" src="https://github.com/zoepje/server-side-rendering-server-side-website/assets/144004461/5783b268-0b74-4ad0-aaae-790bec72775c">

### Categorie 📸
**Desktop**

<img width="800" alt="Desktop Categorie" src="https://github.com/zoepje/the-web-is-for-everyone-interactive-functionality/assets/144004461/d8e2c543-a45d-4028-bef6-003a06cfc6d5">

**Mobile**

<img width="400" alt="Mobile Categorie" src="https://github.com/zoepje/the-web-is-for-everyone-interactive-functionality/assets/144004461/b4325efd-1614-428e-9631-58f3920492ae">

### Artikel 📸
**Desktop**

<img width="800" alt="Desktop Artikel" src="https://github.com/zoepje/the-web-is-for-everyone-interactive-functionality/assets/144004461/cf5215d1-8103-46f4-bd49-7b19a7ca7465">

**Mobile**

<img width="400" alt="Mobile Artikel" src="https://github.com/zoepje/the-web-is-for-everyone-interactive-functionality/assets/144004461/f2e5a900-6524-48f1-bf14-e0fffc9e8f82">

<!-- Voeg een link toe naar Github Pages 🌐-->
Je kunt hier de website bezoeken🌐 https://the-web-is-for-everyone.onrender.com

## Gebruik
<!--Bij Gebruik staat hoe je project er uit ziet, hoe het werkt en wat je er mee kan. -->
Voor dit project heb ik een responsieve startpagina, categoriepagina en artikelweergave ontwikkeld. Deze zijn dynamisch en halen gegevens op uit de Red Pers WordPress API. Op de startpagina wordt een overzicht getoond van de 30 meest recente artikelen. In het menu kun je kiezen uit 8 hoofdcategorieën. Wanneer je op een categorie klikt, wordt je naar de bijbehorende categoriepagina geleid waar je een overzicht vindt van de artikelen binnen die categorie. Door op een artikel te klikken, word je naar de pagina van dat artikel gebracht waar je het volledige artikel kunt lezen. Elk artikel heeft een deelknop waar je op kunt klikken en dan wordt de link van dat artikel gekopieerd.

## Kenmerken
<!-- Bij Kenmerken staat welke technieken zijn gebruikt en hoe. Wat is de HTML structuur? Wat zijn de belangrijkste dingen in CSS? Wat is er met Javascript gedaan en hoe? Misschien heb je een framwork of library gebruikt? -->
Bij het ontwikkelen van deze website heb ik gebruikgemaakt van EJS, CSS, JavaScript en Node.js. In mijn EJS-templates heb ik zowel de HTML-structuur als dynamische data uit de API geïntegreerd. Met CSS heb ik de visuele opmaak van de website gemaakt. Met JavaScript heb ik een deelknop geïmplementeerd, en met behulp van Node.js post ik de benodigde data op de API. Voor meer details over hoe ik dit specifiek heb gebouwd, kun je terecht in mijn [Wiki](https://github.com/zoepje/the-web-is-for-everyone-interactive-functionality/wiki/3.-Bouwen).

Ik heb ook gewerkt volgens het principe van Progressive Enhancement. Dit betekent dat je eerst een functionele basis bouwt. Vervolgens verbeter je het stap voor stap om het aantrekkelijker en gebruiksvriendelijker te maken.
Ik eerst een laag HTML heb geschreven die het doet op elke browser. Daarna ben ik pas CSS gaan toepassen om de opmaak te maken. Nadat dit werkte heb ik pas JavaScript toegepast.


## Installatie
<!-- Bij Instalatie staat hoe een andere developer aan jouw repo kan werken -->
Als je aan deze website wilt werken kun je de reposertory forken:
1. Open deze repository in jouw editor.
1. Ga naar de terminal en voer het commando `npm install` uit. Hiermee installeer je Express en alle benodigde afhankelijkheden via NPM.
1. Start de server met het commando `npm start`.
1. Pas alles naar eigen wens aan.

## Bronnen

## Licentie

This project is licensed under the terms of the [MIT license](./LICENSE).
