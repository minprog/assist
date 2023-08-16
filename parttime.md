---
layout: default
---

<header markdown="1">

# Assistentenhandboek Minor Programmeren

## <small>Deel B: Werkgroepen en nakijken  <br>Herfst 2022</small>

<small>Deze versie is gemaakt in 2020--2022 door Martijn Stegeman.</small>

</header>


{% include_relative werkgroep/overzicht.md %}



# Week 1

- Deze week gaan studenten aan de slag met Scratch, en ze starten ook met het basisboek (zonder dat ze al C gehad hebben!). Richting het einde van de week gaan ze het installatiescript draaien op hun computer zodat ze een C-compiler en werkende terminal hebben.

- Fulltime-studenten gaan ook leren over computerhardware en binair tellen. Dat is een voorbereiding op bijvoorbeeld de Filter-opdracht in een latere week, maar ook op het PIDAC-practicum dat volgende week start.

- Een belangrijk punt om voor iedereen in de gaten te houden is of de installatie goed lukt! Dit moet echt klaar tijd vóór het weekend.

- Er is deze week géén werkgroep. De groepen worden pas in de loop van de week ingedeeld.

- Het basisboek en de reader worden uitgedeeld op maandagmiddag na het introductiecollege.

## Aftekenen week 1
{:.break}

Deze week ga je alleen nog aftekenen en geen feedback schrijven. Na indeling van de groepen kun jij de inzendingen van je eigen groep bekijken op de websites van Programmeren 1 en Datarepresentaties. Zorg dat het aftekenen uiterlijk zondagavond klaar is.

{% include_relative nakijken/scratch.md %}

{% include_relative nakijken/boek.md opdracht="Variabelen" %}

{% include_relative nakijken/boek.md opdracht="Control Flow" %}

{% include_relative nakijken/final.md %}



# Week 2

- Deze week een aantal kleinere opdrachten in C. Studenten starten met "Hello, you!", een uitbreiding op de `hello.c` die ze vorige week gemaakt hebben. Daarna een paar opdrachten om met loops en if's te oefenen.

- Fulltime-studenten gaan daarnaast leren over beveiliging, en over besturingssystemen. Later in de week doen ze een flinke tutorial over UNIX-gebruik.

- Bij de werkgroep ga je vooral kennismaken met je studenten. Neem er rustig de tijd voor.

- Zorg dat je vooraf alle onderstaande punten goed doorneemt, want de uitleg is te lang om ter plekke al improviserend te lezen.

- Er is deze week niks om af te tekenen!

## Werkgroep week 2 (40 min)

De werkgroep staat in het teken van kennismaking!

{% include_relative werkgroep/kennismaking.md %}

{% include_relative werkgroep/scratch-demo.md %}

{% include_relative werkgroep/mentor.md %}

{% include_relative werkgroep/terugblik.md %}

{% include_relative werkgroep/grote-vragen-1.md %}

0. Wijs tot slot even op de extra opdracht die eind van de week in het schema staat. De deadline is, net als voor alle opdrachten, op vrijdag. De opdracht is dus echt voor mensen die snel gaan en tijd over hebben. Maar wel superleuk uitdagend!

## Administratie

{% include_relative werkgroep/naderhand.md %}



# Week 3

- Deze week staat in het teken van Strings en Arrays. De opdrachten zijn allemaal gerelateerd aan cryptografie. Ze komen je misschien bekend voor maar let op dat ze in detail wel anders zijn dan vorige jaren!

- De Fulltime-studenten gaan leren over binaire representaties, dus hoe elke soort informatie in essentie binair is. Ze gaan ook leren hoe dat concreet in een bestand er uit ziet. Een voorbereiding op de bitmap-opdrachten van een latere week.

- In de werkgroep ga je voor het eerst een code review organiseren, en daar ga je ook wat uitleg over geven, zie hieronder.

- Tot slot ga je zelf voor het eerst nakijken, zodra studenten hun definitieve versie van Caffeine hebben ingeleverd. Instructies vind je hieronder.

## Werkgroep week 3 (80 minuten)

0. Wijs even op de extra opdracht die eind van de week in het schema staat. De deadline is, net als voor alle opdrachten, op vrijdag. De opdracht is dus echt voor mensen die snel gaan en tijd over hebben. Maar wel superleuk uitdagend!

{% include_relative werkgroep/terugblik.md %}

{% include_relative werkgroep/code-review-eerste.md %}

3. Code review Caffeine (40 minuten)

    Aspecten:

    - Formatting

{% include_relative werkgroep/code-review.md %}

{% include_relative werkgroep/grote-vragen-2.md %}

## Aftekenen en nakijken week 3
{:.break}

Deze opdrachten kun je gedurende de week al aftekenen (en problemen signaleren). In het weekend moet alles sowieso ingeleverd zijn, dus als je het in bulk doet: graag uiterlijk zondagmiddag.

{% include_relative nakijken/boek.md opdracht="Strings & Arrays" %}

{% include_relative nakijken/schrijfoefeningen.md opdracht="Strings" %}

{% include_relative nakijken/cijfers.md opdracht="Caffeine" %}



# Week 4

- Deze week gaan studenten aan de slag met Functies. Hierover is geen apart CS50-college maar het verdient wel extra aandacht. De Calendar-opdracht trekt dit redelijk ver door met een flink aantal functies die geïmplementeerd moeten worden.

- De Fulltime-studenten gaan ook wat leren over reguliere expressies en een klein stukje automatentheorie. Het is allemaal niet te serieus bedoeld, uiteindelijk gaat het om de praktische vaardigheid en het basisbegrip.

- Je hebt vorige week feedback gegeven, daarover zul je wel wat vragen krijgen. Als studenten hun eigen specifieke feedback willen bespreken kan dit het best even buiten de groep om! ("Kunnen we dat na de werkgroep even bespreken?").

## Werkgroep week 4 (80 minuten)

{% include_relative werkgroep/terugblik.md %}

0. Code review Cypher (30 minuten)

    Aspecten:

    - Formatting
    - Comments 🆕
    - Naming 🆕

{% include_relative werkgroep/code-review.md %}

{% include_relative werkgroep/grote-vragen-2.md %}

## Aftekenen en nakijken week 4

Zorg dat alles uiterlijk in het weekend afgetekend is.

{% include_relative nakijken/schrijfoefeningen.md opdracht="Functions" %}

{% include_relative nakijken/boek.md opdracht="Functies" %}

{% include_relative nakijken/cijfers.md opdracht="Cypher" %}



# Week 5

- Deze week duiken studenten in de algoritmen. Eerst een aantal analytische opdrachten en dan echt uitprogrammeren van een sorteertalgoritme. Dit is niet hetzelfde algoritme als vorige jaren! Let op dat je de studenten niet verkeerd voorlicht.

- Fulltime-studenten gaan een heleboel UNIX-commando's leren kennen en manieren (pipes) om die met elkaar te combineren. Ze leren ook de CSV- en JSON-formaten kennen die ze waarschijnlijk nog wel tegen gaan komen in latere programmeerprojecten.

## Werkgroep week 5

{% include_relative werkgroep/terugblik.md %}

0. Code review Calendar

    Nieuwe aspecten:

    - Formatting
    - Comments
    - Naming
    - Nesting 🆕

{% include_relative werkgroep/code-review.md %}

{% include_relative werkgroep/grote-vragen-2.md %}

## Aftekenen en nakijken week 5

{% include_relative nakijken/schrijfoefeningen.md opdracht="Algorithms" %}

{% include_relative nakijken/cijfers.md opdracht="Calendar" %}



# Week 6

- Deze week gaan studenten aan de slag met structs, binaire opslag en het bitmap-formaat. De Filter-opdracht sluit daar op aan en werkt ook, net als vorige week met 2D-arrays. De bedoeling is dat studenten daar niet zoveel moeite meer mee hebben, maar het is wel veel informatie tegelijk.

- Fulltime-studenten duiken de webtechnieken in en leren over HTML en CSS. Ze maken een eigen homepage en leren hoe ze CSS-selectors kunnen gebruiken voor het bedienen van een scraping-tool.

- Mogelijk krijg je al vragen over het tentamen. Deze week zal eer een mail rondgaan met meer informatie. Loop daar niet op vooruit.

## Werkgroep week 6

{% include_relative werkgroep/terugblik.md %}

0. Code review Sort

    Nieuwe aspecten:

    - Formatting
    - Comments
    - Naming
    - Nesting
    - Cleanup 🆕

{% include_relative werkgroep/code-review.md %}

{% include_relative werkgroep/grote-vragen-2.md %}


## Aftekenen en nakijken week 6

{% include_relative nakijken/schrijfoefeningen.md opdracht="Beatles" %}

{% include_relative nakijken/cijfers.md opdracht="Sort" %}



# Week 7

- Deze week gaat over datastructuren en daarbij krijgen studenten de bekende opdracht Speller. Dit is natuurlijk een pittige opdracht en het duurt even voordat iedereen begrijpt hoe pointers werken. De bedoeling is dat het een voorbereiding is op het gebruik van objecten en classes bij Programmeren 2.

- Fulltime-studenten leren ook nog over databases. Ze gaan daarbij vooral veel SQL-queries schrijven om een goed gevoel te krijgen over hoe dat allemaal werkt.

## Werkgroep week 7 (60 min)

{% include_relative werkgroep/terugblik.md %}

1. Wie stopt? (5 minuten)

    Neem even door wie er stopt na afloop van Programmeren 1. Noteer de namen hier:

    <table>
        <tbody>
            <tr><td></td><td></td><td></td></tr>
        </tbody>
    </table>

1. Code review Filter (30 minuten)

    Nieuw aspect:

    - Formatting
    - Comments
    - Naming
    - Nesting
    - Cleanup
    - Loops 🆕
    - Scope 🆕

{% include_relative werkgroep/code-review.md %}

{% include_relative werkgroep/grote-vragen-2.md %}

## Aftekenen en nakijken week 7

Check of je <u>alles tot nu toe</u> hebt afgetekend dat afgetekend moet worden! Dit zodat de eindcijfers straks zonder problemen gemaakt kunnen worden. Daarnaast zijn er nog twee oefeningen deze week.

{% include_relative nakijken/cijfers.md opdracht="Filter" %}


# Week 8

Deze week is het tentamen. Studenten vinden de datum en locatie in het rooster op datanose. Zorg dat je niet toch nog de verkeerde gegevens vooraf gaat verspreiden, maar help studenten juist zelf de up-to-date gegevens in het rooster te vinden!

Het tentamen zal bestaan uit een mix van programmeeropdrachten die live worden gedaan en meer theoretische vragen. Verdere informatie wordt via de website verspreid onder de studenten.

## Werkgroep week 8

Er is geen werkgroep. Vergeet niet om even gedag te zeggen tegen studenten die stoppen na Programmeren 1!

## Nakijken week 8

{% include_relative nakijken/cijfers.md opdracht="Speller" %}
