# F# Introductie

## Hello F#

* Run even hello world (start je console app mee)
* Maak een variabele met ```let```
* Gebruik een interpolated string: ```"hello %s{msg}"``` met een variabele
  * Merk op dat dit al sterk getypeerd is: ```%s``` voor strings, ```%d``` voor ints, ```%O``` voor objects...

## Types

* Maak een tuple-type Coordinaat aan, met twee ints (x & y)
* Maak een record-type Persoon aan, met een voornaam, achternaam, leeftijd.
* Maak een een tweetal instanties er type, en print die.

## Functies
(roep deze functies ook met wat argumenten aan, en print de resultaten om het te testen natuurlijk)

* Maak een functie ```greet``` die "Hello " voor het input argument zet, en gebruik die in de eerdere hello-world
* Maak een functie ```distance``` die de afstand tussen twee coordinaten berekent
* Maak een functie ```agediff``` die het verschil in leeftijd tussen twee personen teruggeeft
* Maak een functie ```distanceToP``` die de afstand tot één van de eerdere coordinaten berekent (dit heet partiele applicatie)

## Recursie

* Maak een functie ```som``` die recursief de faculteit berekent (```5! = 5*4*3*2*1```)
* Maak een functie ```palindroom``` die recursief bepaalt of een woord een palindroom is.
  Een palindroom is een woord dat je in het midden kan spiegelen, zoals ```deed```, ```tot```, maar ook ```meetsysteem```
* Maak een functie ```fibonacci(n)``` die recursief het n'de getal in de fibbonacci reeks uitrekent.
  De fibonacci reeks (```0, 1, 1, 2, 3, 5, 8, 13, 21, 34, 55, 89, 144, ...```) maak je door elke keer de twee vorige getallen
  bij elkaar op te tellen. (en per definitie vast te stellen dat ```fib(0)=0``` en ```fib(1)=1``` )

## Hogere order functies

* Maak een eigen functie ```map```, die hetzelfde doet als List.map
* Maak een eigen functie ```filter```, die hetzelfde doet als List.filter
* Maak een eigen functie ```fold```, die hetzelfde doet als List.fold

## Algebraïsche types

* TODO: records zijn een algebraic type (namelijk een product-type)
* TODO: Intuitieve Union-types oefening. Placeholder zijn error meldingen...