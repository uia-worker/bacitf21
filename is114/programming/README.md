# Introduksjon i web-utvikling
## Viktige begreper
<dl>
<dt>Webapplikasjon</dt>
<dd>ifølge ("Applikasjon," n.d.) er en applikasjon et program utformet for å løse spesielle oppgaver eller gi en bestemt type informasjon; webapplikasjon kan da defineres som en mengde av flere programmer for bruken på web (verdensvev)</dd>

<dt>App</dt>
<dd>(mindre) program (applikasjon) laget til bruk på smarttelefoner, nettbrett o.l. ("App," n.d.)</dd>
<dl>

---
## Viktig å lære

Siden web er basert på verdensomspennende nettverk datakommunikasjon og informasjonsspredning, består en webapplikasjon av programmer som fysisk er lagret på mange steder i dette nettverket. For å kunne utviklet en webapplikasjon må man lære litt om mange forskjellige ting og også forstå hvordan disse tingene henger sammen. 

Lagring av data er en av de viktigste forutsetningene for å kunne implementere informasjonsssystemer. Data kan bli lagret på mange forskjellige former, for eksempel, som filer på en harddisk eller en SD kort, som poster i en regnark eller som instruksjoner i et hurtigminne, som de mest utbredte regnemaskinene i dag har. Så den første viktige tingen, som vi må se på er DATALAGRING. 

Siden en webapplikasjon består av flere deler og den meste tradisjonelle arkitekturen for webapplikasjoner er klient/server-arkitektur, så pleier man å kalle den delen av webapplikasjonen som sørger for at informasjon kan vises og bearbeides hos en bruker for "front-end" og den delen som tilbyr denne informasjonen for "back-end". En bruker må lage en spørring om spesifikke data på web til en server og ved hjelp av nettverket (kalt Internett) vil denne serveren (vanligvis en selvgående prosess) sende de forespurte dataene til brukeren. Arkitekturen (hvordan komponentene former en helhet) for både "FRONT-END" og "BACK-END" består vanligvis av mange programmer.  

En annen viktig del, som man må kunne som utvikler av webapplikasjoner, er VERSJONSKONTROLL. Webapplikasjoner består av mange programmer og disse programmene blir kontinuerlig oppdatert. Da er det viktig å ha oversikt overfor hvilke versjoner av hvilke programmer som blir brukt. En liten oppdatering i en av delprogrammene kan forårsake feil i webapplikasjonen. Det finnes flere verktøy for å administrere versjoner av både dokumentasjon og kildekode (git er det mest populære verktøyet akkurat nå i 2021). Det finnes webapplikasjoner som integrerer funksjoner for prosjektadministrasjon og kildekodeadministrasjon, slik at teams av utviklere kan samarbeide effektivt på prosjekter.

En foreløpig siste del som må nevnes er FEILRETTING, som også kalles for DEBUGGING (som kommer fra det engelske ordet "bug", og kan fritt oversettes til norsk som "avlusing").
 
---

## Viktige teknologier

* HTML5 (video/audio, lerret, weblagring, geolokasjon)
* CSS3 (posisjon, gradienter, overganger, pseudoklasser)
* Twitter Bootstrap (navbar, jumbotron, alerts, grids)
* JavaScript (arrays, objects, form validation, ajax)
* jQuery (selectors, DOM manipulation, events, image slider)

* Node.js (npm, express, template engines, authentication)
* Meteor.js
* Angular
* PHP (MySQL)
* Ruby on Rails

* MySQL (PHP integration)
* PostgreSQL (... PHP integration)
* MongoDB
* CouchDB

* Memcached (telnet commands, libmemcached-tools)
* Redis (caching, data persistence, data types)
* Markdown
* Sass (variables, mixins, extending partials)

* Git
* Grunt (task runner, concatenation, watch mode)
* Gulp
* Crome Developer Tools
* PHP Debugging

## Oppgaver
* Simple HTML Template
* Bootstrap Theme
* CSS3 dropdown meny
* Page Cache w/Memcached
* jQuery image slider

# HTML
Vi vil bruke samme struktur for alle våre økter:
* Viktige begreper
* Viktig å lære
* Sentrale verktøy (vanligvis anbefalt)
* Oppgaver (vanligvis problemløsning, men i starten kan være en del imitasjon)
* Vurderingskriterier for å bestå oppgaven
* Godkjenningsprosedurer
Vi etterstreber å bruke norsk (vanligvis bokmål) så mye som mulig. Vi sjekker de norske begrepene mot Det Norske Akademis Ordbok (sett inn linken med markdown: naob.no). Vi vil bruke engelske begrep og uttrykk der hvor oversettelse virker uegnet (en følelse). Disse vil vi prøve alltid å legge i anførselstegn. 

Vi bruker Oxford dictionary som et grunnlag for engelske begrep og uttrykk.

## Viktige begreper
<dl>
<dt>&lt;BEGREPA&gt;</dt>
<dd>ifølge ("&lt;TITLE&gt;," n.d.) ... </dd>

<dt>&lt;BEGREPB&gt;</dt>
<dd> ("&lt;TITLE&gt;," n.d.)</dd>
<dl>

## Viktig å vite
HyperText Markup Language er en "markup" språk og ikke et programmeringsspråk.

Dynamiske deler i webapplikasjoner er vanligvis implementert i JavaScript. "Vanligvis" 

HTML består av tagger, som opprinnelig var tenkt for å lage tekstfiler/dokumenter, som et program kan "parse" og generere grafiske elementer som kan vises på skjermen. 
```html
<b>Dette er et fet skrift</b>
<h1> - <h6> 
<a>
<img>
```
## Notater (rå): 
* Anbefalte tekstbehandlere: Notepad++ under Windows 10 og SublimeText under macOS anbefales i begynnelsen. Ellers finnes det flere IDE, som vi vil anbefale i løpet av studier, som Visual Studio Code og IntelliJ (det finnes mange flere og dere kan bruke den dere ønsker). 

# Referanser

App. (n.d). In Det Norske Akademis Ordbok. Retreived May 7, 2021, from https://naob.no/ordbok/app

Applikasjon. (n.d). In Det Norske Akademis Ordbok. Retrieved May 7, 2021, from https://naob.no/ordbok/applikasjon 
