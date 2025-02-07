# Level 2: One-Shot/Few-Shot Prompting: Prompten met voorbeelden.

## Uitleg
Je weet nu wat prompts zijn: de vragen die je stelt aan taalmodellen (LLM). Maar soms is het handig om niet alleen een vraag te stellen, maar ook een voorbeeld te geven! Net als wanneer je iemand iets leert door het voor te doen.

### Waarom voorbeelden geven?

Stel, je wilt dat de LLM het sentiment van een filmrecensie bepaalt: is de recensie positief, negatief of neutraal? Je kunt dan zeggen: `Is deze filmrecensie positief, negatief of neutraal: 'Deze film was echt geweldig!'` Maar je kunt ook een voorbeeld geven:

Jouw voorbeeldrecensie:

```
# Voorbeeld
"De nieuwe Minions film is echt geweldig! Het verhaal is spannend en ook grappig."
Sentiment: Positief

Recensie: Paddington is een hartverwarmende film die zowel jong als oud zal bekoren.
Sentiment:
```

Door dit voorbeeld begrijpt het taalmodel beter wat je bedoelt met een positieve recensie. Hij kan de woorden "geweldig", "spannend" en "grappig" koppelen aan een positief sentiment.

### One-shot Prompts: Eén Voorbeeld

Als je één voorbeeld geeft, noemen we dat een *one-shot prompt*. "One" betekent één, dus één voorbeeld. Je geeft het taalmodel één voorbeeld om te laten zien hoe het de taak moet uitvoeren.

### Few-shot Prompts: Meerdere Voorbeelden

Soms is één voorbeeld niet genoeg. Als je wilt dat het taalmodel een heel specifiek soort sentiment herkent, kun je meerdere voorbeelden geven. Dat noemen we een `few-shot prompt. "Few" betekent een paar, dus een paar voorbeelden. Door meerdere voorbeelden te geven, laat je de LLM een patroon zien dat hij moet volgen.

Voorbeeld met meerdere recensies (few-shot):

```
# Voorbeelden
Recensie: "Deze film is echt geweldig! Het verhaal is spannend en de acteurs zijn fantastisch."
Sentiment: Positief
Recensie: "Wat een saaie film! Ik heb me de hele tijd verveeld."
Sentiment: Negatief
Recensie: "De film was oké, niet goed, niet slecht."
Sentiment: Neutraal

Recensie: Paddington is een hartverwarmende film die zowel jong als oud zal bekoren.
Sentiment:
```

### Hoeveel voorbeelden heb je nodig?

Hoeveel voorbeelden je nodig hebt, hangt af van een paar dingen:

- **Hoe moeilijk de taak is**: Als je wilt dat de LLM iets heel ingewikkeld doet, zoals sarcasme herkennen, heb je misschien meer voorbeelden nodig.
- **Hoe goed je voorbeelden zijn**: Duidelijke en goede voorbeelden helpen de AI beter.
- **Hoe slim het taalmodel is**: Sommige LLM's hebben minder voorbeelden nodig dan andere.
Meestal begin je met een paar voorbeelden, bijvoorbeeld drie tot vijf. Maar als het niet goed lukt, kun je meer voorbeelden proberen.

Kortom, voorbeelden zijn super handig om de LLM te laten begrijpen wat je wilt. Of je nu één voorbeeld (one-shot) of een paar voorbeelden (few-shot) geeft, het helpt de LLM om betere en meer passende antwoorden te geven over het sentiment van een filmrecensie!

# Nu jij:
Kopieer de volgende prompt in https://michielderuyter.uc.r.appspot.com/

    Groepeer de karakters als held of schurk, zoals voorbeeld:
    Spider-Man = Held
    The Joker = Schurk
    Sneeuwwitje = Held
    Maleficent = Schurk
    Jafar =

Je mag ook proberen om zelf categorieën te bedenken, met voorbeelden.
(Bijv. groeten & fruit, zoet & zout, vogels die kunnen vliegen & vogels die niet kunnen vliegen...)