---
Title: Projekt
Description: Part 10
Template: kmom
---

Projekt
==================

##### 1.1 Webbplats
- Jag valde att börja med en ny installation av portfolio för att kunna gå igenom kmomenten igen, och göra några saker annorlunda. Dessutom har jag tagit hjälp av min först portfolios kod. 
- Jag har skapat en ***förstasidan*** som innehåller information om Artisten och hans karriär, en ***about-sida*** i vilken jag skrev om artistens verksamhet och hans nya kommande shower och danskurser och hur kan man anmäla sig.
Till slut av sidan finns en länk till dokumentation av sidan. ***En highlight-sida*** som representerar artistens förra shower.


- Till webbplatsen har anpassat en ***navigering*** som funkar bra till dator och mobila enheter, och jag använt en bild av artisten och hans dancing team som ***flash-image***, och en ***logo*** inspirerat av hans dancing program och den var använt som en ***favicon*** också.


- ***Footern*** innehåller artistens instagram, facebook, mail länkar och även en knapp som låter användaren byta till den andra tema och byta tillbaka.


- Jag har skapat en till sida med artistens egna bilder men att ta hjälp av ***Cimage*** för att få anpassat storlek till bilderna.


##### 1.2 Tema 

Jag har skapat min tema med hjälp av min gamla portfolio och från grunden samtidigt, och den var skapat enligt ***kundens beskrivning*** av målet och känslan han vill för sina kunder att ha.


Med ***sass*** delade jag upp min kod i flera moduler, varje sida på webbplatsen har sin egen sassfil som göra det lätt och praktisk om kunden vill ändra något på en av sidorna ( Highlights, index, gallery ), och även teman har var sitt fil. Jag använde mig av variabler för att kunna ta bra kontroll av färgerna i webbplatsen och även nesting som organiserar och ger en bra struktur till koden. Jag valde mina färger enligt webbplatsens mål med hjälp av adobe color(jag valde vit i början som bakgrund färg sen kunde jag välja resten av färger i min ***färgpaletten***) Jag valde en monokromatiskt vit-svart färgpalett efter att jag läst två artiklar* om svart och vit betydelse och med hjälp av Toptal - ColorBlind Web Page Filter kunde jag kolla att sidan fungerade bra även för ***färgblinda***. For ***typografin*** har jag använt bold, wide Archivo Black* för titler som ger ett intryck som passar aktivitetsinriktad publik, och roboto för brödtext som passar med titlers font type, enkel och mycket läsbar, för webb- och mobil användning.


Jag använde mig av olika ***designprinciper och designelement*** till exempel contrast med att använda svart och vit som skapar en intryck av emphasis också med att använda bold svart för titler. jag använde stor heroimage som tar användarens uppmärksamhet till båda dancing och även artisten som finns i framme på bilden, bilden som har en rörelsen som ger en känsla av aktiv pigg "lifestyle" som väcker användarens intresse om att dansa och kanske anmäla sig till danckursen eller att köpa biljeter till dancingshowes. Till slut av about-sidan finns en länk till en ***dokumentation sida*** som dokumenterar min val av färgpaletten, typografin, design, webbplatsens känsla, och min användning av sass.


##### 1.3 Responsivitet och tillgänglighet
Jag använde mig av CSS-grid och flexbox för att kunna presentera  informationen i sidorna på bra sätt till exemple highlight och gallerie sidan. För att kunna få sidorna funkar responsivt använde jag cimage och @media (max-width: 992px)och @media (max-width: 767px. Med hjälp av cimage och srcset har jag fått bra responsivitet och bra laddningstid. Jag behövde ändra på några kod till exempel på mina .twig filer (aria-hidden), en del av mina images saknade "Alt attributes" jag fixade dett så jag kunde få Accessibility 100 i google lighthouse.


##### 1.4 Tema alternativt

Jag gjorde en till tema till webbplatsen som är ett mörkt tema, så jag behövde ***ändra*** på hur jag använder mina ***färger***, svart som behåller samma mål av webbplatsen att öka ka känslan av potential och möjlighet för att kolla eller testa nya aktiviteter, eller mörkt silver färg till texten som är mer bekvämt att läsa på mörkt bakgrund och passar fortfarande till målet som är beskriven i artikeln "The Color Silver,The color of illumination and reflection"* (it signals a time of reflection and a change of direction as it illuminates the way forward.) och ändrade på ***typografin*** till light open sans som är bekvämt att läsa på dar bakgrund.
på så sätt blev ***designprinciper och designelement*** påverkade och justerade för att passa det andra temat  till exemple contrast på ett annat sätt mörk bakgrund och ljus text.  


##### 1.6 Analys

Jag analyserade min portfolio enligt färg och typografin för att jag tänkte att jag behövde berätta och förklara hur mina val av färg och typografin funkar bra med min val av artist (en dansare) webbplats, Och så i analys texten dokumenterade jag  färgpaletten och noterade typsnittsval för rubriker och om det är serif eller snas-serif, och visat hur webbplatsens färgval och typografi motsvarar den profil som Kunden vill ha.


#### Hur projektet gick att genomföra
Jag har börjat bygga webbplatsen från grunden, skapat tre sidor tänkte på hur temat ska se ut, kundens mål och hur ska designelementer ska vara. Allt gick bra och smidigt med footern, header, flash bilden….    
Jag hade svårt med att testa publicera portfolio sidan på student server  får att det visade det gamla portfolio men sen fick jag hjälp i discord att ändra på .htdocs. En till problem var kunna presentera highlights sidan med hjälp an grid det gick inte så smidigt, jag ville att ha tre shows bilder i rad i samma storlek, men jag fick dem i konstigt ordning sen kollade jag på min kod och det var fel kod på min sass fil så jag ändrade och fixade problemet.
I  allmänt tycker jag att projektet är lagom lätt att genomför på det practical sida (koda, använda sass, cimage) för att vi gick genomföra alla punkter i kursmomenten, men på design sidan är det inte lätt och det är tid krävande till exempel att bestämma typsnittet för att man behöver bereda sin kunskap om den och läsa mycket för att anpassa en typografin efter webbplatsens mål, och det är samma fall när vi tänker på färger, och designen. Till slut vill jag säga att jag tycker att det var ett projekt som är rimligt och hjälper att träna på design på bra sätt.

#### Tankar om kursen: 
Mina tankar är helt positívt om kursen. Med den kan man fokusera på designen, hur att nå en harmonious webbplats som uttrycker ditt eller din kunds mål, dessutom att man fick alltid hjälp från boda lärarna i discord. Och att kunna nå kurs materialet online(boken till kursen). Det enda svårighet som jag kan tänka på är  labbmiljön som vi jobbat på i början av kursen, jag kände att jag behöver ladda ner många verktyg och ny ramverk som jag inte förstod riktigt och hur allt hänger ihop och vilka kommander ska användas och varför jag tror att det behövs en video som förklara allt detta som till exempel Niklas videos om PICO. Därför ger jag kursen 8 av 10.
 