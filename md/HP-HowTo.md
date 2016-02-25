---
Pr-id: PublishingLab
P-id: PublishingLab How To
A-id: 10
Type: article
Book-type: anthology
Anthology item: article
Item-id: unique no.
Article-title: title of the article
Article-status: accepted
Author: name(s) of author(s)
Author-email:   corresponding address
Author-bio:  about the author
Abstract:   short description of the article (100 words)
Keywords:   epub, pandoc, conversion, hybrid, workflow, publishing, arts publishing, styles, css, markdown, design, ebooks, epub3, GitHub
Rights: CC BY-NC 4.0
...

<div class="pagetitle">
# How-to voor digitale kunstkritiek
</div>

#How-to voor digitale kunstkritiek

## Introductie
Hoe kunnen we op zinvolle wijze online kritiek bedrijven en koe kan de digitale omgeving de huidige kunstkritiek verrijken? Met deze vragen als uitgangspunt onderzocht het PublishingLab samen met verschillende kunst- en cultuurredacties de mogelijkheden die het genre van de 'longform' de kritiek biedt. In deze 'how-to' delen we deze ervaringen en kennis. 
##Wat vind je in deze how-to Deze how-to biedt een praktische 'guide' voor culturele tijdschriften, kleine uitgeverijen, websites, blogs, critici, schrijvers, ontwerpers en ontwikkelaars voor het creëren en verrijken van longform-artikelen. Hoe maak je een longform? Waar te beginnen? In deze publicatie vind je vier verschillende experimenten - voorbeelden van longforms - met benodigdheden en tips om zelf aan de slag te gaan.  

##Voor wie is deze how-to
De how-to is tot stand gekomen in samenwerking met kunstcritici, redacteuren, vormgevers, webdevelopers en onderzoekers en is ook bedoeld voor iedereen die zich bezig wil houden met nieuwe vormen van kunstkritiek in het digitale domein.

##Wat is longform
Er bestaat geen duidelijke definitie van wat longform is, veelal wordt ermee verwezen naar diepgaande online artikelen met een grote hoeveelheid content, die alle technieken van online schrijven belichamen. Hier benaderen we longforms als multimedia-essays die verrijkt kunnen worden met foto's, video's, tijdlijnen, biografieën, audioboeken, interviews, infographics, kaarten, interne en externe links etc.

<div class="infobox">
#Hoe moet je deze how-to gebruiken 
In deze how-to zijn vier experimenten met longforms te vinden, elk met een eigen moeilijkheidsgraad die aangeeft in welke mate technische kennis vereist is: easy, moderate en expert. Bij elk experiment vind je links op de pagina het voorbeeld en de technische overwegingen. Rechts kun je de benodigdheden en extra bronnen raadplegen. 
</div>

<div class="linkbox">
###Colofon
Redactie: Leonieke van Dipten & Miriam Rasch<br>
Design: Lasse van den Bosch Christensen & Marlon Harder, 
[Template](http://www.template01.info/)<br>
Met dank aan: Marina van den Berg (ArchiNed), Wouter Hillaert (rekto:verso), Daphne Rieken, Nadine Roestenburg, Laurence Scherz, Sonja van der Valk & Sophia Zürcher.  
Uitgegeven door PublishingLab en Instituut voor Netwerkcultuur, Hogeschool van Amsterdam, met ondersteuning van Domein voor Kunstkritiek, Letterenfonds en Amsterdam Creative Industries Network [logo's]  
Amsterdam, 2016  
Contact: [PublishingLab](http://www.publishinglab.nl/) en [Instituut voor Netwerkcultuur](http://www.networkcultures.org)
</div>


#Lessons learned
##Auteurs<br><li>Denk vanuit de content: wat wil je zeggen en hoe kun je dat het beste doen? Een bespreking van de productie van een film kan misschien beter in bewegend beeld dan in tekst gebeuren; vertellen waarom een boek je raakt misschien wel door een vlog.</li><li>Denk na over een hybride workflow. Dat betekent dat je vanaf het begin in kaart brengt wat je nodig hebt - audio, video, tekst, beeld - en zorgt dat die verschillende vormen geproduceerd worden. Welke expertise is nodig? Hoe kun je die vormen verbinden met elkaar? </li><li>Vertrouw op de expertise van webdevelopers en designers en betrek ze in een zo vroeg mogelijk stadium. Laat ze meedenken vanuit de technische mogelijkheden zodat techniek geen belemmering hoeft te zijn. </li><li>Een eerste longformpublicatie is een investering qua tijd en geld, elk artikel dat daarna komt is die investering waard. </li><li>Meestal blijkt er technisch meer mogelijk dan op voorhand gedacht. </li>##Developers<br><li>Denk aan de backend en of je gebruik maakt van een Content Management Systeem (CMS).</li>
<li>Overweeg de responsiveness en offline reading mogelijkheden.</li>
<li>Welke tools zijn open source beschikbaar en geschikt voor herhaald gebruik.</li>
<li>Online content is niet definitief, maar kan bijna altijd makkelijk geüpdatet worden.</li>
<li>Denk aan de hybride mogelijkheden. Houd de inhoud (tekst, beeld, video) wel apart van hoe de longform werkt of eruit ziet. Maak het ontwerp zo flexibel mogelijk.</li>


#Het multimediale essay
<div class="difficulty-level easy"></div>
<div class="difficulty-level moderate"></div>


##Introductie 
Welke open source tools zijn er reeds beschikbaar om longforms te produceren en online content te verrijken en verbeteren? In dit experiment vind je een overzicht van longform, tijdliijn- en image annotation tools die gemakkelijk en zonder al te veel technische kennis toe te passen zijn. 

##Het experiment 
**Tijdlijn- en image annotation tools** <br>

In samenwerking met ArchiNed zijn verschillende tijdlijntools onderzocht: Timeline JS, Timeglider, Tiki Toki, Dipity en Timeline Express. Timeline JS is open source, Dippity, Tiki Toki, Timeglider en Timeline Express gebruiken een Freemium model. 

Annotatietools die zijn getest zijn Thinglink, Annotorious en Cowbird. Een overzicht van voor- en nadelen, advies en aanbevelingen over de verschillende tools, lees je in de [blogpost over het onderzoek](http://www.publishinglab.nl/dekunstvandekritiek/2015/04/30/timeline-and-annotation-tools/). 

**Longform platforms** <br>
Ook is bekeken welke open source tools om een longform te producen er reeds beschikbaar zijn. De volgende platforms en tools zijn nader onderzocht: Medium, Aesop Story Engine (WordPress plugin), Creatavist en Exposure. Voor een overzicht van de bevindingen en verdere aanbevelingen, zie de [blogpost over longform tools](http://www.publishinglab.nl/dekunstvandekritiek/2015/03/31/developing-a-longform-platform-for-the-inc/). 

![](lib/ArchiNed_Comparison-chart.png)

##Technische overwegingen 

Bedenk vooraf goed waar de tools aan moeten voldoen. Denk bijvoorbeeld aan welke file types ondersteund moeten worden en aan de implementatie op de website van bijvoorbeeld het medium.

Vergeet bij het kiezen van een tool niet naar het licentiebeleid en de businessmodels te kijken. Zo kan het zijn dat je met het maken van een longform of timeline de rechten op de inhoud volledig afstaat. Daarnaast is het met gratis tools ook vaak zo dat er advertenties worden toegevoegd aan de timeline of longform. 

Aesop Engine (Wordpress plugin)
<div class="difficulty-level moderate"></div>


[Timeline Express](https://wordpress.org/plugins/timeline-express/) (Wordpress plugin) <br>
</div>

<div class="infobox">
#Een extraatje<br>
##Longform tools <br>
Exposure <br>

##Timeline tools <br>
[Timeline Tool Tiki-Toki](http://www.tiki-toki.com/) <br>
[Timeline Tool Timeglider](http://www.timeglider.com/) <br>
[Timeline Tool Timeline JS](http://timeline.knightlab.com/) <br>
[Timeline Express](https://wordpress.org/plugins/timeline-express/) (Wordpress plugin) <br>
[Dipity](http://www.dipity.com/) <br>

[Memolane](http://memolane.com/) <br>


##Links <br>
[The SIMILE project of MIT](http://www.simile-widgets.org/) <br>
[KnightLab](https://projects.knightlab.com/)<br>
Lasso Frontend editor 
</div>


#Het video-essay
<div class="difficulty-level expert"></div>

##Introductie 
Hoe kunnen we optimaal gebruik maken van de mogelijkheden van het web om een video-essay te maken? In dit experiment is er gewerkt naar verschillende elementen: tekst, video’s, citaten uit de romans en geanimeerde dialogen.

##Het experiment
In dit experiment is er gezocht naar verschillende elementen om het essay te verreiken en hoe deze elementen onderdeel kunnen zijn van de lopende tekst.
Hoe de leesbaarheid optimaal te houden?

![](lib/video.png)

##Technische overwegingen
Lasse en Marlon?
 - Het dialoog
 - automatisch spelen video
 - citaten

<div class="linkbox">
##Benodigdheden
Lasse en Marlon? (indien die er zijn)
</div>

<div class="infobox">
##Een extraatje
##Leuke Linkjes
[Kinetische poezie van Y. H. Chang](http://www.yhchang.com/THE_INLAND_SEA.html) <br>
[Video essays van Kevin B. Lee](https://vimeo.com/kevinblee)<br>
</div>


#De Dialoog
<div class="difficulty-level expert"></div>

##Introductie
Kan de lezer actief betrokken worden bij het vormen van een kritiek en hoe kunnen we de bekende commenting hiërarchie doorbreken? In dit experiment is onderzocht hoe het de lineaire verhaallijnt te doorbreken en hoe  reacties van lezers onderdeel kunnen zijn van het artikel. 

##Het experiment
In dit experiment is een systeem ontwikkeld waarin zowel de auteur, redacteur als lezer een bijdrage aan het verloop van het artikel kan leveren. Dit artikel of discussie format is zo gevisualiseerd dat lezersreacties tussen de discussie tussen auteur en redacteur komen te staan in een ping-pong-stijl. Daarnaast is een systeem ontwikkeld waarin de lezer op elke paragraaf kan reageren, waardoor de discussie dynamischer wordt.

![](lib/rekto.png)


##Technische overwegingen
<div class="difficulty-level expert"></div>
Het project bestaat uit verschillende onderdelen, allemaal met hun complicaties: <br>

1. (Backend) Het belangrijkste is het maken van een kader voor de lezers om te reageren en te antwoorden op de alinea's. Hier zullen een aantal zaken in overweging moeten worden genomen: Hoe sla je deze reactie op? Hoe laat je lezers reageren en hoe koppel je de reacties aan de juiste aline?

2.  Hoe je te beschermen tegen spam? 

3. (Frontend) Hoe worden reacties weergegeven naast bij de betreffende alinea's en hoe werkt de lay-out van het artikel?

4. Hoe moeten we omgaan met verschillende platforms en browsers?

We hebben deze probleem opgelost door:

1. (Backend) Omdat we (in dit geval) niet te maken hebben met een specifiek content management system (CMS), is de meest directe manier om reacties op te slaan als plain text-files. Iedere keer als er een reactie geplaatst wordt, wordt Javascript (frontend) aangeroepen om een command te versturen naar een PHP-script (backend) die de reactie in een textfile plaatst corresponderend met de betreffende alinea. Bij page-load zullen alle beschilbare textfiles opgehaald worden. Een 'reactie-bubble' zal verschijnen aan de zijde van elke alinea waar een textfile gekoppelt is. 

2. Om spam tegen te gaan, hebben we geprobeerd te werken met CAPTCHA's (Turing-tests),We raden dit echter af omdat die niet de meest optimale oplissing is. Om het geheel te versimpelen hebben we gekozen voor een eenvoudige 'security question': In welk jaar zitten we?

3. Lasse en Marlon?

3. Lasse en Marlon?


<div class="linkbox">
##Benodigdheden
Lasse en Marlon? (indien die er zijn)

</div>

<div class="infobox">
##Een extraatje
Hier komen leuke linkjes met inspirerende dingen/voorbeelden
</div>


#De Image Map / Beeldkaart
##Introductie
Ter aanvulling op een artikel in het blad kunstbeeld is er een kleine omgeving gecreëerd waarin je een kijkje kan nemen in het atelier van de kunstenaar. Je kunt door het atelier bewegen en op verschillende objecten klikken. In deze foto zitten popups verwerkt met audio en tekst. <br>
Link voorbeeld kunstbeeld

##Het experiment
omschrijven leonieke
![](lib/Kunstbeeld.png)

##Technische overwegingen
Voor deze image map is gezocht naar een alternatief op de meer traditionele image map. Het doel was iets te vinden met een moderne uitstraling, werkend op verschillende platforms. Er is gekozen om de traditionele image map te vervangen voor [Leaflet](http://leafletjs.com/); een open source JavaScript-bibliotheek voor interactieve kaarten. Hierdoor wordt je afbeelding minder statisch en je hebt meer het gevoel dat je kunt ’surfen’ in een digitale omgeving. Door het gebruik van Leaflet hoef je je foto niet op te delen in stukken maar kun je ‘markers’ toevoegen op je kaart. Door er op te klikken opent zich een pop-up met een speler voor audio. 

<div class="linkbox">
##Benodigdheden
[leaflet](http://leafletjs.com/) <br>
[imagemapster](http://www.outsharked.com/imagemapster/) <br>
[Responsive Image Map Plugin](http://mattstow.com/experiment/responsive-image-maps/rwd-image-maps.html#ppg) <br>
[jQuery Rain](http://www.jqueryrain.com/?xBLzPIQE) <br>
[Pedro’s Tech Mumblings](http://build-failed.blogspot.nl/2012/11/zoomable-image-with-leaflet.html) <br>
</div>

<div class="infobox">
##Een extraatje** <br>
http://psousa.net/demos/zoom-images/ <br>
</div>






