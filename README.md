# C--Project
Project 4 op een rij S2 Programeerproject.


Ontwikkel een object-georiënteerde C# Windowsapplicatie alsook een webclient, die de gebruikers toelaat het spel vier op een rij te spelen, twee spelers tegen elkaar op 1 client of 1 speler tegen de computer. 

Het basisspel bestaat in het afwisselend laten vallen van een gekleurde schijf (elke speler heeft zijn eigen kleur), in een kolom naar keuze, waarbij de schijf naar beneden in de kolom valt. Winnaar is de eerste speler die zo 4 op een rij kan maken in een raster van 7 kolommen op 6 rijen. Ook diagonaal kan 4 op een rij ontstaan. Een volledig gevulde kolom kan uiteraard niet meer gekozen worden. Indien het bord vol zit en niemand 4 op een rij heeft, noemen we dat een tie (spel stopt, zonder winnaar).

Voor de webclient zal het nodig zijn C# klassen te kunnen gebruiken. Dit kan door zelf een webserver in C# te maken die reageert op de requests van een webbrowser. Bestudeer hiertoe de klassen HttpListener, HttpListenerRequest en HttpListenerContext. Dit is al bij al eenvoudiger dan het klinkt als je die klassen goed bestudeert. Voor wie dit een brug te ver is stellen we in de komende weken een minimale uit te breiden versie van zo’n webserver ter beschikking.

Maak gebruik van valid HTML5 code, CSS en JavaScript om deze webclient tot een goed einde te brengen. Code efficiëntie is hier van een even groot belang als bij de andere onderdelen. 

Zowel web- als windowsclient zijn user-centered ontworpen en gebruiken animaties waar mogelijk en duiden aan wanneer en waarom een spelletje gewonnen is en door wie. Verder moeten na elkaar telkens nieuwe spelletjes kunnen gespeeld worden en houdt de computer de stand bij (welke speler hoeveel keer heeft gewonnen). Het is NIET de bedoeling dat je over de webserver met verschillende clients tegen elkaar kunt spelen. De primitieve webserver ken m.a.w. geen sessies. Eenmaal je hem stopt en terug opstart herinnert hij zich ook niets meer. Als verschillende clients tegen de webserver zouden praten dan ziet deze ook geen verschil. Er is voor hem maar 1 client. Kortom 1 client waar twee spelers beurtelings spelen of 1 speler tegen de computer speelt is alles wat we vragen.

Opmerking: wie het als uitdaging wil aannemen, mag uiteraard verder gaan en sessies voorzien waarbij verschillende spelers verschillende spelletjes aan het spelen zijn naast elkaar. Maar bezint eer je hieraan begint en hou dergelijke uitbreiding weg van je hoofdbranch als die klaar is. Bij het doorlopen van het proces was het wel eenvoudig om de web- en windowsclient beide tegen elkaar te laten spelen.

Het moet mogelijk zijn af te stappen van de klassieke grenzen van 7 kolommen, 6 rijen en 4 op een rij. Waarom bijvoorbeeld geen 10 kolommen, 8 rijen en 6 op een rij? Beperk de ranges in deze dimensies zodat je geen zinloze dingen hebt (zoals 1 rij of 1 kolom, of 2 kolommen met 3 op een rij … dat heeft allemaal weinig zin).

Maak de computerspeler makkelijk los te koppelen van de rest van het spel en maak hem uiteraard zo intelligent mogelijk.

We verwachten ook een klassendiagram (UML) en wireframes van zowel de windows- als de webclient. Start met de low fidelity wireframes en leg deze voor tijdens de overlegmomenten voor je verder gaat naar een high fidelity versie. Deze mogen digitaal of op papier zijn, doch indien een papieren versie wordt aangeleverd moet deze duidelijk leesbaar en verzorgd getekend zijn. 

Een use case diagramma wordt niet gevraagd wegens beperkte opgave.

Pas tijdens het ontwikkelen de geziene methodieken uit Analyse en modelleringstechnieken toe. Verdeel het werk in slices en verdeel het werk onder elkaar. Maak duidelijke afspraken over de verdeling van het werk en documenteer deze in een logboek (wie, wanneer, welke taak, hoe lang). 

Bepaal verschillende milestones en deliverables en werk je iteraties daarnaar uit. Je kan hiervoor MS Project gebruiken maar dit is geen verplichting. 
Zorg ervoor dat je snel een uiterste basis versie (van een onderdeel) werkende hebt zodat je snel kan testen. 

De werking wordt gedemonstreerd door een werkend product, maar ook door afzonderlijke unit-en integratietesten. Ook de testen worden beschouwd als onderdeel van de codebase en als dusdanig geëvalueerd en gequoteerd.
