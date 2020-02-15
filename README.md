# micro:bit opdrachten

Deze pagina bevat een aantal opdrachten, gemaakt door Lukas Potters, waarmee je leert de micro:bit te programmeren.

Voor het programmeren van de micro:bit ga je in een browser naar <a href="https://makecode.microbit.org/#editor" target="_blank">Microsoft MakeCode for micro:bit</a>. (Het kan zijn dat je daarna nog Nederlands als taal moet selecteren.)

*Zorg ervoor dat je radiokanaal is ingesteld op jouw nummer als je een programma maakt met meerdere micro:bits!*  
*De links bij de opdrachten gaan naar het programma en geven dus "spoilers". Gebruik ze alleen als het je zelf niet lukt om te kijken hoe het wel moet.*

## Makkelijk

### Veranderende afbeelding
- Je kunt blokjes `toon lichtjes` of `toon pictogram ...` gebruiken om lichtjes op de micro:bit aan te zetten.
- Zet meerdere van deze blokjes achter elkaar en gebruik ook `pauzeer (ms) ...` om een veranderende afbeelding te maken.
- Je kunt ook `wanneer knop ... wordt ingedrukt` of `bij ...` gebruiken om een andere afbeelding te laten zien bij verschillende inputs.

### Signalen sturen
- Bedenk welke dingen je wilt sturen.
- Hoe zorg je ervoor dat als je op een knop drukt er een signaal verzonden wordt? (TIP: gebruik radiosignalen om dingen te verzenden en bij de volgende stap om ze te ontvangen.)
- Hoe zorg je ervoor dat het signaal ontvangen kan worden?
- Tip: gebruik de knoppen.

De oplossing vind je <a href="https://makecode.microbit.org/_DDLfm62VbLs6" target="_blank">hier</a>. De code hiervoor kun je ook downloaden: [solutions/microbit-A-or-B.hex](solutions/microbit-A-or-B.hex).

## Gemiddeld

### Sneeuwbol
- Zorg er eerst voor dat je alle LED-jes aan zet met een `toon lichtjes` blokje.
- De rest kan op 2 manieren gedaan worden:
- De Extra makkelijke manier!  
  Je kunt een simpele animatie maken die steeds lichtjes weghaalt om een animatie te maken. (Met `toon lichtjes` blokjes.)
- De Iets lastiger maar nog steeds makkelijke manier!  
  Je kunt een lus gebruiken om steeds een paar lichtjes uit te doen (met `... keer herhalen` en `wis x ... y ...` blokjes).

De oplossing vind je <a href="https://makecode.microbit.org/_DH9PevP9jXVk" target="_blank">hier</a>. De code hiervoor kun je ook downloaden: [solutions/microbit-snowglobe.hex](solutions/microbit-snowglobe.hex).

### Steen-papier-schaar
- Zorg er eerst voor dat je bij 3 verschillende inputs verschillende dingen selecteert (bijvoorbeeld bij A kies je steen, bij B kies je papier, bij A+B kies je schaar).
- Zorg ervoor dat je je keuze niet meer kan veranderen (TIP: gebruik een variabele en `als ... dan`).
- Zorg ervoor dat je keuze verstuurd wordt naar de andere micro:bit (met `Radio verzend ...` en `wanneer de radio ontvangt ...`)
- Maak een systeem dat laat zien wie gewonnen heeft door de verschillende inputs te vergelijken. (TIP: gebruik een `de hele tijd` lus en `als ... dan` erin met de twee getallen van de keuzes.)
- Zorg dat het spel een score bijhoudt en zichzelf herhaalt.

De oplossing vind je <a href="https://makecode.microbit.org/_hDMcD4Wy3Ru0" target="_blank">hier</a>. De code hiervoor kun je ook downloaden: [solutions/microbit-Better-Rock-Paper-Scissors.hex](solutions/microbit-Better-Rock-Paper-Scissors.hex).

## Extra moeilijk

### Schietspel
- Geen uitleg voor deze opdracht :)
- Zorg dat je kunt bewegen met A&B.
- Zorg dat je kunt schieten door A en B in te drukken of dat je schudt om te schieten.
- Zorg dat als je schiet een kogel vooruit gaat en over gaat naar het andere scherm.
- Als de kogel je raakt, verlies je een leven en als je geen levens meer hebt ben je af.
- Zorg dat je eventueel kan herstarten als je af bent.

De oplossing vind je <a href="https://makecode.microbit.org/_6YRXx0CyXWDY" target="_blank">hier</a>. De code hiervoor kun je ook downloaden: [solutions/microbit-schietspel.hex](solutions/microbit-schietspel.hex).

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons-Licentie" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />Dit werk valt onder een <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/deed.nl">Creative Commons Naamsvermelding-NietCommercieel-GelijkDelen 4.0 Internationaal-licentie</a>.
