---
layout: default
---

## Introductie

De consultancy tak van &samhoud zoekt constant manieren om nieuwe technieken in te zetten tijdens het uitvoeren van hun consultancy taken. Vooral tijdens recruitment van nieuwe junior consultants zien ze veel mogelijkheden om op een meer interactieve en digitale manier het sollicatieproces te gaan voeren.

*Lees meer over de aanleiding van dit project.*

Tijdens een selectiedag voeren de consultants een aantal cases uit, zowel individueel als in groepsverband. Aan de hand van deze cases wordt door observanten gemeten over welke communicatieve of analytische vaardigheden een kandidaat beschikt.


## Ontwerpvraag
> Hoe kan een **Web Virtual Reality toepassing** tijdens de **interne selectiedag** van **&samhoud consultancy** de huidige cases aanvullen en interactiever maken zodat **de competenties van aankomende junior consultants** beter te meten zijn?

Biedt een Virtual Reality toepassing in dit geval een meerwaarde in het recruitment process en wat zou deze toepassing moeten bieden om praktisch ingezet te worden?

Met dit vraagstuk kwam &samhoud consultancy bij dochterbedrijf &samhoud media. Als creatief bureau, gespecialiseerd in augmented en virtual reality producties, zag &samhoud media kansen om deze cases met de mogelijkheden van Virtual Reality  een stuk interactiever te maken.

### Huidige situatie
Tijdens een selectiedag (junior caroussel) voeren ongeveer 25 aankomende consultants een aantal cases uit. Een groot deel van de selectiedag is in groepsverband maar er zijn ook individuele momenten. 

*Lees meer over het scenario gedurende de selectiedag.*

Na afloop worden de kandidaten via de telefoon geïnformeerd feedback en de reden waarom ze wel of niet door zijn. Dit is op basis van de observaties en de competenties die  gedurende de dag tijdens de verschillende onderdelen zijn verzameld op een beoordelingsformulier.

### Focus Group
De kandidaten voor de selectiedag gaan straks aan de slag als junior consultant. Junior consultants werken aan complexe problemen voor verschillende bedrijven. Ze analyseren business problemen en komen met effectieve oplossingen. Strategische en abstracte vraagstukken zet een consultant om in concrete acties en methodes. Bijvoorbeeld in de vorm van team meetings of trainingen / workshops. 

*Bekijk hier een overzicht van een persona.*

Tijdens de werving van kandidaten focussen ze zich vooral op een jongere generatie. De gemiddelde leeftijd van aankomende junior consultants ligt tussen de 23 - 30 jaar. Van net afgestudeerd (technische of economische opleiding bij voorkeur) tot 3 jaar werkervaring in het vakgebied.

### Oplossing
Door het ontwikkelen van Virtual Reality Escape Room, die gebruik maakt van een smartphone en zogeten drop-in viewers, is het voor de observanten van &samhoud consultancy op een meer speelse en interactievere manier mogelijk om de competenties van de kandidaten te meten. Na afloop van de selectiedag nemen de kandidaten de drop-in viewers mee en krijgen ze een persoonlijke uitnodiging voor een vervolggesprek van oprichter Salem Samhoud in de vorm van een 360-video.

## Onderbouwing

### De meerwaarde van Virual Reality
Een Virtual Reality toepassing vergroot over het algemeen de user engagement. Doordat de cases een stuk interactiever en visueler zijn gaan mensen eerder op in de ervaring.

Door het toepassen van de digitale middelen zijn de competenties een stuk beter meetbaar, er is zo een grotere hoeveelheid data beschikbaar die een observant kan inzien.

* Hogere user engagement
* Beter meetbare competenties
* Meer data beschikbaar

Daarnaast is een credo van &samhoud 'usual unusual' ze proberen altijd net even anders te zijn dan de rest. Een VR toepassing tijdens een sollicitatie past dus erg bij deze visie en de strategie om altijd te innoveren in recruitment.

*Dit is een sidenote maar dan met veel meer tekst*

Tijdens zo'n selectiedag is het natuurlijk ook van belang een bepaalde impressie / indruk achter te laten bij de kandidaten over de bedrijfsvoering van de consultancy tak. Kandidaten worden met een interactieve toepassing op een positieve manier verrast en maken kennis met de mogelijkheden van andere business lines binnen de &samhoud group.

### Low-cost hardware componenten
Vanwege de overvloed aan hardware zijn er keuzes gemaakt in welke componenten voor deze situatie goed werken. Daarom maken we van maar een klein spectrum aan hardware componenten gebruik. We kiezen ervoor om de toepassing te optimaliseren voor low-cost components. Specifiek dus de zogeheten drop-in viewers (google cardboards) waarbij je de smartphone gebruikt als head-mounted display.

* Cardboards zijn relatief goedkoop, lage opstartkosten
* Lichtgewicht dus makkelijk op te zetten en af te bouwen tijdens een selectiedag
* Makkelijk om meerdere aan te schaffen voor gebruik in groepsverband
* Portabiliteit, na afloop kunnen kandidaten deze meenemen

Ook na de selectieprocedure op locatie willen we de cardboard gaan gebruiken voor een terugkoppeling, de kandidaten kunnen na afloop de drop-in viewer gemakkelijk meenemen. Aangezien we voornamelijk toetsen op communicatieve vaardigheden nemen we het feit dat low cost componenten geen controllers hebben voor input op de koop toe.

### WebVR als techniek
Vrijwel alle applicaties die draaien op dure hardware zijn zogeheten 'native' applicaties die specifiek voor een bepaald platform worden gemaakt. Naast een native applicatie is het mogelijk om een Virtual Reality applicatie te maken die draait in een browser. Dit heeft voor zowel de gebruikers van de applicatie en ontwikkelaars voordelen. 

Het doel van WebVR is om het voor zowel ontwikkelaars als gebruikers toegankelijker (drempelvrij) te maken om Virtual Reality te ervaren. Ongeacht de devices en input die ze tot hun beschikking hebben.

## Prototypes
Het uitwerken van de prototypes is vooral technisch van aard. In een vrij vroeg stadium heb ik aangegeven dat ik alle prototypes publiekelijk (open-source) wou ontwikkelen. De broncode en documentatie is voor iedereen inzichtelijk. Deze manier van werken zorgt ervoor dat ik snel iteraties en feedback kan vergaren

### Escape Room
Het scenario is relatief simpel. Tijdens de selectiedag betreden de kandidaten een ruimte zonder enige vorm van instructie. Voor hun ligt een houten kist met een cijferslot en een viertal drop-in viewers. Ze werken aan het gezamenlijke doel om de houten kist open te krijgen.   De kandidaten kunnen niet in elkaars kamer kijken en mogen de VR bril niet afzetten tijdens hun sessie waardoor ze alleen met spraak met elkaar kunnen communiceren.

Voor de technische uitwerking Zoals eerder benoemd maak ik bijna uitsluitend gebruik van A-Frame. Voor het registeren van componenten heb ik in eerste instantie een bolierplate opgezet die de applicatie met Webpack bundled.

### 360-video
De drop-in viewers die tijdens de junior caroussel gebruikt worden nemen de kandidaten na afloop mee. Via een link krijgen ze na afloop een 360-video met een persoonlijke boodschap van Salem Samhoud, oprichter van de &samhoud groep.

De video is opgenomen met een Insta 360 camera, een relatief simpele camera waarbij het opnemen vrij gemakkelijk gaat. 'Point and shoot' kwam goed uit bij de geringe tijd die we beschikbaar hadden.

Adobe Premiere Pro CC heeft nieuwe mogelijkheden om 360-video te bewerken en in post-productie nog te schaven. Het syncen van de audio en het toevoegen van graphics (intro / outro) kan met deze tool prima.

## Onderzoek

## Conclusie
De Escape Room is een aanvulling op de huidige cases die tijdens de junior caroussel worden behandeld. Het resultaat, na afloop van de caroussel, hangt niet volledig af van de prestaties tijdens gedurende de toepassing. Dit geldt grotendeels voor de 360-video's. De resultaten worden in eerste instantie altijd nog telefonisch naar de kandidaat gecommuniceerd. Helemaal als het een afwijzing betreft, vanuit ethisch perspectief is er gekozen om de afwijzing alleen telefonisch te houden.

Binnen de context van &samhoud consultancy en de informele sfeer die gedurende de caroussel heerst past de WebVR toepassing prima bij de strategie om altijd te innoveren in recruitment waarbij 'usual unusual' voor &samhoud consultancy centraal staat. In een stricter solliciateproces kan ik me voorstellen dat het inzetten van een virtual reality toepassing ongepast kan zijn.

## Meta

**Naam:** Danny de Vries  
**Studentnummer:** 500705475  
**Opleiding:** Communication and Multimedia Design  
**Onderwijsinstelling:** Hogeschool van Amsterdam  
**Startdatum:** 04.02.2018  
**Eindatum:** 29.06.2018  

#### Contactgegevens Bedrijf:
* &Samhoud media
* Oosterdokskade 5
* 1011 AD Amsterdam
* +316 27 00 69 16
* [www.samhoudmedia.com](https://samhoudmedia.com)

#### Contactgegevens Begeleider:
* Tijmen van Rooijen
* tijmen@samhoudmedia.com


#### Contactgegevens Docentbegeleider:
* Sjef Smeets
* j.p.a.smeets@hva.nl

#### Contactgegevens Student:
* Danny de Vries
* 06 – 41025262
* <hi@dandevri.es>