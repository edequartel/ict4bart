# 3 Doorvoeren formules

1. Info docent – Doorvoeren gegevens en formules
2. Onderwerp – Doorvoeren formules
3. Sneltoetsen – Doorvoeren formules
4. Downloads

##1. Info docent – Doorvoeren gegevens en formules

Het doorvoeren van gegevens kan het efficiënt werken met Excel zeer verhogen, maar door het missen van het overzicht kunnen gebruikers van braille/spraak ook gemakkelijk een vergissing maken, bijvoorbeeld door teveel of te weinig cellen te selecteren. Het weergeven van de laatst toegevoegde cel aan de selectie wordt alleen weergegeven met spraak, dus ook braille gebruikers moeten voor dit onderdeel de spraak erbij gebruiken. Selecteren kan op twee manieren: de gebruikelijke met Shift+pijltoetsen, maar ook met Ctrl+G en daarbij de te selecteren cellen opgeven.

Voor het efficiënt werken in een tabel is het nodig dat je van iedere cel weet wat de bijbehorende kolomkop of kolomtitel is en wat de bijbehorende rijkop of rijtitel is. De meeste schermleesprogramma’s hebben een functie waarmee van een cel naast de inhoud ook de kolomkop en rijkop kan worden weergegeven.

Aandacht voor het begrip tabel en de instellingen van het gebruikte schermleesprogramma voor het lezen van tabelkoppen is van groot belang bij deze opdracht.

**Afb. rekenblad met koppenaanduiding in de brailleweergave**


In de afbeelding hierboven is te zien dat de celaanwijzer op de cel C7 staat. In de braillemonitor bovenaan het scherm zie je de informatie zoals die op de brailleleesregel wordt weergegeven: ‘tbl C 7 333 rij 2011 kolom februari’ ofwel je bevindt je in een tabel in cel C7. De inhoud van de cel is 333 en de bijbehorende rijtitel is 2011 en de kolomkop of kolomtitel is februari.

##2. Onderwerp – Doorvoeren formules

Bij het maken van berekeningen in Excel worden formules ingevoerd in een cel. Zodra de cel wordt afgesloten met een Enter wordt in de betreffende cel de uitkomst van de berekening zichtbaar. De formule weer zichtbaar maken kan het beste met F2. Daarmee kom je weer in de bewerkcursor en kan de formule gelezen worden en aangepast. Met Escape verlaat je de bewerkcursor weer.

Omdat er in een rekenblad vaak veel formules moeten worden ingevoerd is er een methode om de eerste formule in een cel te plaatsen en deze door te voeren naar volgende cellen. Dit wordt het doorvoeren van formules en gegevens genoemd.

###Doorvoeren formules
Het Excel bestand ‘doorvoeren formules’ laat een overzicht zien van het gasverbruik over een aantal jaren. Per maand van ieder jaar is te lezen wat het verbruik van iedere maand is.We gaan eerst de formule invoeren om het verbruik in een heel jaar op te tellen en een formule om het verbruik van dezelfde maand van ieder jaar op te tellen. Daarna gaan we de formule doorvoeren naar de andere jaren en maanden, zodat we niet iedere formule zelf hoeven in te voeren.

###Opdracht 03.1

Open het Excel bestand Werkmap 03 doorvoeren formules.xlsx en verken dit overzicht van gasverbruik. Kijk waar gegevens beginnen en ophouden en hoe de jaren en maanden zijn weergegeven.

###Opdracht 03.2

Ga naar de cel N4 en voer de formule in om het verbruik van alle maanden van 2008 op te tellen. De formule is als volgt: =som(B4:M4).

Ga naar de cel B10 en voer de formule in om het verbruik van de maand januari van alle jaren op te tellen. Controleer de uitkomst, die moet zijn:1211.

###Selecteren van cellen

We gaan de formules nu doorvoeren naar de andere jaren en maanden. Voor het doorvoeren moeten je de cellen waarnaar je wil doorvoeren selecteren. Het selecteren kan op twee manieren. De eerste is net als in Word met de Shift en de pijltjes toetsen. Daarbij is de spraak behulpzaam om je te melden tot welke cel je hebt geselecteerd.

De tweede manier is met de functie Ctrl+G en het opgeven van de celadressen. Als je de cellen C5 tot en met G5 wil selecteren ga je als volgt te werk: Ctrl+G en daarna voer je in: C5:G5 en een Enter om te bevestigen.

###Opdracht 03.3

Ga in de cel staan met de formule voor het optellen van het verbruik van het eerste jaar van het overzicht. Selecteer 5 cellen omlaag en kopieer de bovenste cel naar de geselecteerde cellen met Ctrl+D.

Ga vervolgens naar cel B10 en voer de formule door naar de rest van de maanden van het jaar. Hiervoor selecteer je de cellen en kopieer je met Ctrl+R.

Bij het doorvoeren van de formules worden deze automatisch aangepast om de optelling in iedere kolom weer te laten kloppen. Ga naar de optelling van de maanden februari en maart en controleer de formule.

In de cel N10 komt de formule die alle jaren en alle maanden bij elkaar optelt. Bepaal welke formule daarvoor nodig is en voer deze in. Als controle voor de juiste formule, de uitkomst is 8708.

###Kolom- en rijkoppen

Bij het werken in een tabel is het van belang te weten in welke kolom en in welke rij je huidige cel zich bevindt, want dat bepaalt de betekenis van de inhoud van de cel. Is het getal 333 in cel C7 het gasverbruik van februari of van maart en van het jaar 2011 of van 2012. Om dit te weten moet je nagaan wat de kop of titel van kolom C is en wat de kop of titel van rij 7 is. Er zijn verschillende manier om daar achter te komen:

1. Onthouden welke maanden in welke kolommen zitten, maar dat is lastig en leidt tot vergissingen.
2. Iedere keer als je de kolomkop weten wil even met de pijltjestoetsen naar boven gaan en daarna weer naar de cel waar je was, maar dat is erg bewerkelijk.
3. Je schermleesprogramma functies gebruiken om de koppen weer te geven bij de celinhoud. Dit laatste is het meest efficiënt. De volgende mogelijkheden heb je hiervoor:

###SuperNova

Er zijn verschillende methoden om de koppen of titels voor SuperNova herkenbaar te maken. We gebruiken nu alleen de meest eenvoudige.
Hiervoor moeten we de inhoud van de kolomkoppen en rijkoppen vet maken.

Als de koppen vet zijn gemaakt kun je op twee manieren de koppen lezen, handmatig en automatisch.
Handmatig met de sneltoets Capslock+h of Numeriek 3. De laatste moet hiervoor meerdere keren worden ingedrukt.
Het automatisch voorlezen van de kolom- en rijkoppen bij het verplaatsen van de focus, schakel je in/uit met Ctrl+Capslock+h.

###Jaws

* Lees kolomkop; INSERT+ALT+SHIFT+C
* Stel de huidige rij in voor de kolomkoppen; INSERT+ALT+CTRL+C
* Lees rijkop; INSERT+ALT+SHIFT+R
* Stel de huidige kolom in voor de rijkoppen; INSERT+ALT+CTRL+R
* Lees de actieve celcoördinaten; INSERT+C

###Opdracht 03.4
Maak de inhoud van de kolom- en rijkoppen van de tabel gasverbruik vet.Test of de handmatige en automatische methode van koppen voorlezen functioneert.

##3. Sneltoetsen Doorvoeren
Voor het doorvoeren van formules en gegevens zijn de volgende sneltoetsen van toepassing:

###Excel
* Selecteren; Shift+pijltjes toetsen of Ctrl+G en eerste en laatste cel opgeven
* Kopieren/doorvoeren naar rechts; Ctrl+R
* Kopiëren/doorvoeren naar omlaag; Ctrl+D
* Vet maken inhoud van cellen; Ctrl+B

###SuperNova
* Lezen kolom en rij-koppen; Capslock+H of Num 3
* Stel rij of kolom in voor lezen van koppen; selecteer gegevens en maak deze vet
* Schakel automatisch lezen van koppen in; Ctrl+Capslock+H

###Jaws
* Lees kolomkop; INSERT+ALT+SHIFT+C
* Stel de huidige rij in voor de kolomkoppen; INSERT+ALT+CTRL+C
* Lees rijkop; INSERT+ALT+SHIFT+R
* Stel de huidige kolom in voor de rijkoppen; INSERT+ALT+CTRL+R
* Lees de actieve celcoördinaten; INSERT+C

##Downloads:

* [Tabelkoppen](https://www.eduvip.nl/cms/files/Tabelkoppen.jpg)
* [Werkmap 03 doorvoeren formules](https://www.eduvip.nl/cms/files/Tabelkoppen.jpg)

