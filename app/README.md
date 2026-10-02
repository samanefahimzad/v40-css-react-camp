1. Hur kopplas CSS in i React?
Jag importerar App.css och använder CSS-klasser med className.
2. Hur ser användaren vilka todos som är klara? Peka på klassen i din CSS.
När done är true får todo klassen completed, som gör texten genomstruken och nedtonad.
Min kod:
.completed {
  text-decoration: line-through;
  opacity: 0.6;
}
3. Tre steg när stil “inte tar”: spara → import → className → Inspect.
Spara - Har jag sparat App.css?
Import - Har jag import "./App.css";  i App.jsx?
className - Har elementet rätt klass?
Inspect - Jag kan högerklicka på elementet i Chrome 
Inspektera och kontrollera att klassen verkligen finns.
