# Level 5: Chain Of Thought (CoT) - Een ketting van gedachten.

## Uitleg
Taalmodellen zijn goed in taal, maar soms hebben ze moeite met logisch nadenken, vooral bij taken zoals rekenen. Chain of Thought (CoT) prompting is een slimme manier om ze daarbij te helpen. Het is alsof je de computer vraagt om hardop te denken, zodat je kunt zien hoe hij tot een antwoord komt. Een ketting van gedachten.

### Hoe werkt het?

In plaats van alleen de vraag te stellen, vraag je het taalmodel om de stappen te laten zien die hij neemt om tot het antwoord te komen. Je zegt bijvoorbeeld niet alleen:

`Hoe oud is mijn broer?`, maar: `Hoe oud is mijn broer? Laten we stap voor stap denken.`

### Waarom is het handig?

- Betere Antwoorden: Door de tussenstappen te laten zien, kan het taalmodel betere en nauwkeurigere antwoorden geven.
- Begrip: Je kunt zien hoe het taalmodel tot zijn antwoord komt. Als er iets fout gaat, kun je zien waar het misgaat.

## Voorbeeld: Een Rekenprobleem

Zonder CoT:

```
Vraag: Toen ik 3 was, was mijn broer 3 keer zo oud. Nu ben ik 20. Hoe oud is mijn broer?

Antwoord: 63 jaar oud (Fout!)
```


Zoals je ziet, is het antwoord fout. Taalmodellen hebben vaak moeite met rekenen.

Met CoT:

```
Vraag: Toen ik 3 was, was mijn broer 3 keer zo oud. Nu ben ik 20. Hoe oud is mijn broer? Laten we stap voor stap denken.

Antwoord:

Toen ik 3 was, was mijn broer 3 * 3 = 9 jaar oud.
Ik ben nu 20, dus ik ben 20 - 3 = 17 jaar ouder geworden.
Mijn broer is ook 17 jaar ouder geworden.
Dus mijn broer is nu 9 + 17 = 26 jaar oud.
Mijn broer is dus 26 jaar oud. (Goed!)
```

Nu is het antwoord wel goed! Door het taalmodel stap voor stap te laten denken, komt hij tot de juiste oplossing.

# Nu jij:
Zet de creativiteit op 0.1.
Kopieer de volgende prompt in https://michielderuyter.uc.r.appspot.com/

    Toen ik 3 was, was mijn broer 3 keer zo oud. Nu ben ik 20. Hoe oud is mijn broer? Laat mij iedere stap zien.

Maak nu een ketting van gedachten door het delen van een voorbeeld. 
Kopieer de volgende prompt in https://michielderuyter.uc.r.appspot.com/

    Vraag: Toen mijn broer 2 jaar oud was, was ik dubbel zo oud. Nu ben ik 40 jaar oud. Hoe oud is mijn broer? Laat mij iedere stap zien.

    Antwoord:
    1. Toen mijn broer 2 jaar was, was ik 2 * 2 = 4 jaar oud.
    2. Dat is een leeftijdsverschil van 2 jaar en ik ben ouder.
    3. Nu ben ik 40 jaar oud, dus mijn broer is 40 - 2 = 38 jaar oud.
    
    Het antwoord is 38.

    Vraag: Toen ik 3 was, was mijn broer 3 keer zo oud. Nu ben ik 20. Hoe oud is mijn broer? Laten we stap voor stap denken.
    Antwoord: