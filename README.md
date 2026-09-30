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
