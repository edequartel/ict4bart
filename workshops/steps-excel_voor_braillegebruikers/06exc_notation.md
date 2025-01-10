# 6. Getalnotatie

1. Getalnotatie
2. Sneltoetsen – Getalnotatie
3. Downloads

##Onderwerp Getalnotatie
In Excel moet er met getallen gerekend kunnen worden. Daarom voer je getallen in Excel in zonder daarbij de eenheid van een getal, zoals euro’s of procenten. In een rekenblad kan het echter ook gaan om bedragen in euro’s of het berekenen van een uitkomst door middel van percentages. Deze eenheden moeten in Excel aan een cel worden toegekend door dit aan te geven in de eigenschappen van een cel. De eigenschappen van een cel krijg je met de sneltoets Ctrl+1.

In de volgende opdracht wordt een berekening gemaakt van de groei van een spaarbedrag door de jaarlijkse rente die je erover krijgt van de bank.

###Opdracht 06.1

* Download en open het Excelbestand Werkmap 06 getalnotaties.xlsx
* Verken het rekenblad van deze werkmap

In cel B10 komt het startbedrag van sparen in euro’s.

* Stel de getalnotatie van cel B10 in op ‘Financieel’ met twee cijfers achter de komma en het Euroteken als symbool.

####Zo doe je dat:

* Ga naar cel B10
* Open de celeigenschappen; Ctrl+1
* Ga naar het tabblad ‘Getal’; Ctrl+Tab voor gaan naar volgend tabblad
* Ga naar de lijst Categorie; Tab
* Kies in de lijst de categorie ‘Financieel’; Pijl omlaag
* Ga naar Decimalen en stel deze in op 2; Tab
* Ga naar de lijst symbool en stel deze in op het Euroteken; Tab
* Bevestig met Enter

Zet in de cel B10 nu het startbedrag 1000 en controleer of het Euroteken er aan wordt toegevoegd door de ingestelde celeigenschap.

In de cel B11 komt het rentepercentage in procenten. Hiervoor moet de getalnotatie voor deze cel worden ingesteld op ‘Percentage’. Bij de getalnotatie Percentage wordt een al ingevoerde celwaarde vermenigvuldigd met 100. Daarom is het belangrijk om de getalnotatie eerst in te stellen en daarna het rentepercentage in te voeren.

* Stel de getalnotatie van cel B11 in op ‘Percentage’ met 1 cijfer achter de komma. Hiervoor kies je in de lijst Categorie voor Percentage.
* Zet in de cel B11 het rentepercentage 3,5 en controleer of het procentteken er aan wordt toegevoegd door de ingestelde celeigenschap.

Als de jaarlijkse rente over het spaarbedrag op de spaarrekening wordt gestort, wordt het rentebedrag ieder jaar hoger omdat je dan ook rente ontvangt over de rente.

###Opdracht 06.2

Omdat Excel bij vermenigvuldigen van een cel met de getalnotatie Percentage het resultaat automatisch deelt door 100, kun je bij de renteberekening het startbedrag vermenigvuldigen met het rentepercentage om het juiste resultaat te krijgen.

* Bereken in cel B14 de rente over het eerste jaar door het startbedrag in B10 te vermenigvuldigen met de het rentepercentage in cel B11.
* Bereken in cel C14 het totaalbedrag voor het eerste jaar door het startbedrag en de rente van het eerste jaar op te tellen.

De rente van het tweede jaar bereken je door het totaalbedrag van het eerste jaar te vermenigvuldigen met het rentepercentage.

* Bereken in B15 de rente over het tweede jaar
* Bereken in C15 het totaalbedrag voor het tweede jaar door het totaalbedrag van het eerste jaar en de rente van het tweede jaar op te tellen.

Het totaalbedrag van het tweede jaar is € 1071,23

Controleer het totaalbedrag

Voor de jaren 3 tot en met 10 kunnen we de formules die we nu hebben, doorvoeren van cel B15 naar B23 en van C15 naar C23. Voordat de formule in B15 kan worden doorgevoerd moet het celadres van het rentepercentage absoluut worden gemaakt door een dollarteken voor de kolomletter en het rijnummer te zetten. Want het celadres van het rentepercentage mag niet worden aangepast bij het doorvoeren van de formule.

* Maak het celadres van het rentepercentage in cel B15 absoluut
* Voer de formule in cel B15 door tot en met cel B23
* Voer de formule in cel C15 door tot en met cel C23

Het eindbedrag na 10 jaar sparen is € 1410,60

Controleer je eindbedrag

Overige getalnotaties

Behalve de getalnotatie voor de Euro en Percentage zijn er nog een paar getalnotaties die van belang zijn.

##Cijfers als tekst
Bij het invoeren van een telefoonnummer begin je altijd met een 0. Excel haalt een 0 voor een getal automatisch weg omdat die geen rekenkundige waarde heeft. Om er voor te zorgen dat getallen niet worden gewijzigd geeft je ze de getalnotatie Tekst.

###Opdracht 06.3
* Zet in de cel A25 alleen de cijfers van je mobiele telefoonnummer (zonder streepje of andere tekens er in)
* Geef de cel B25 de getalnotatie Tekst
* Zet ook in cel B25 alleen de cijfers van je mobiele telefoonnummer
* Zet in cel C25 je telefoonnummer, maar nu met een streepje, het minteken na de cijfers 06 
* vergelijk de weergave van je telefoonnummer in de cellen A25, B25 en C25.

##Breuken
Het getal 0,5 kun je ook weergeven als een breuk. Dan schrijf je 1/2. Dit mag je echter niet invoeren als een ‘1 deelstreep 2’. Ook hiervoor moet je de getalnotatie van de cel aanpassen naar Breuk in de categorielijst.

###Opdracht 06.4
* zet in cel A28 het getal 0,25
* Geef de cel A28 de getalnotatie Breuk met maximaal twee cijfers
* Controleer de weergave van cel A28
* Vermenigvuldig in cel B28 de breuk met 5
* Hoe is het resultaat weergegeven?

Stuur het bestand Werkmap 06 getalnotatie.xlsx naar je docent of trainer.

##2. Sneltoetsen Celadressering en getalnotaties

Eigenschappen van een cel; Ctrl+1
Celadres absoluut maken; $ (dollarteken) plaatsen voor kolomletter en/of rijnummer afhankelijk van of je de rij absoluut wil maken of de kolom, of beide.

##Downloads:

* [Werkmap 06 getalnotaties](https://www.eduvip.nl/cms/files/Werkmap-05-celadressering.xlsx)

