Bubble Sort
I denne opgave skulle jeg implementere sorteringsalgoritmen Bubble Sort i C.
Bubble Sort er en simpel algoritme, der gentagne gange gennemløber et array og sammenligner naboelementer. Hvis et element ikke står i den korrekte rækkefølge i forhold til det næste, byttes de om. Dette fortsætter, indtil hele listen er sorteret, og der ikke længere sker nogen bytninger. De største elementer “bobler” op mod slutningen af listen, hvilket har givet algoritmen sit navn.
Opgaven bestod af flere deltrin:
Først skulle jeg implementere en swap-funktion, som bytter to elementer i et array.

Derefter skulle jeg lave to sammenligningsfunktioner:

letters_in_order() der sammenligner bogstaver uden hensyn til store/små bogstaver.

numbers_ascending() der sammenligner tal i stigende rækkefølge.

Til sidst blev selve sorteringsfunktionen bubble_sort() implementeret, hvor funktionen modtager et array og en funktionspointer, der afgør om to elementer er i orden eller skal byttes.

Programmet blev testet i en main.c-fil med to forskellige arrays – ét med bogstaver ({'z', 's', 's', 'a'}) og ét med tal ({4, -1, 2, 9}).
Resultatet viser, at funktionen kan bruges generelt til at sortere data baseret på forskellige kriterier.
Derudover blev der udarbejdet et flowchart, som illustrerer logikken bag algoritmen med de to centrale løkker:
Den ydre løkke gentager sorteringen, indtil ingen bytning sker, mens den indre løkke sammenligner og bytter elementer parvist.
Formålet med opgaven var at opnå forståelse for, hvordan en klassisk sorteringsalgoritme fungerer i praksis, samt at lære brugen af funktionspointere, modulopdeling i C-filer (.h og .c) og logisk strukturering af kode.
