## Predstavenie projektu

- Projekt bude obsahovat webovu aplikaciu v jave 
- Temou projektu je kriminalita v CR
- Uzivatel uvidi mapu CR rozdelenu na kraje
- Po kliknuti na vybrany kraj sa zobrazi diagram
- Diagram bude obsahovat suhrn jednotlivych trestnych cinov pre kazdy rok
- Uzivatel si bude moct v diagrame vyfiltrovat konkretne udaje ktore potrebuje (mesiac, rok, druh trestneho cinu)


## Popis dat

- Zo stránky http://www.policie.cz/clanek/statisticke-prehledy-kriminality-za-rok-2018.aspx stiahneme dáta kriminality z roku 2016 a 2016
- pre kazdy rok je vytvorenych 12 xlsl suborov, pre kazdy mesiac jeden
- subory obsahuju udaje o kriminalite v CR
- data su rozdelene do listov
- kazdy list predstavuje 1 kraj
- 1. list obsahuje data pre celu CR
- pre jednoduchsie spracovanie data prekonvertujeme z xlsl do csv

