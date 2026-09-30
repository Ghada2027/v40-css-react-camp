# CSS i React

## Hur kopplas CSS in i React?
CSS kopplas in med import "./App.css"
Sedan används className i JSX för att koppla HTML-elementet till CSS-klassen.

## Hur ser användaren vilka todos som är klara?
När done är true får <li> klassen completed.
className={t.done ? "todo completed" : "todo"}

I App.css finns klassen .completed
Den gör texten genomstruken och nedtonad.

## När en stil inte fungerar
1. Spara filen.
2. Kontrollera att CSS-filen är importerad.
3. Kontrollera att rätt className används.
4. Kontrollera elementet med Inspect.


## Felsökning

### 1. Import

Jag kontrollerar att App.css är importerad i App.jsx med import "../App.css".

### 2. className

Jag kontrollerar att klassnamnet i JSX är samma som i CSS. I min app används completed när done är true.

### 3. Inspect

Jag använder Inspect och tittar på elementet. Om completed finns på elementet men stilen inte syns, kontrollerar jag CSS-regeln i Styles.
