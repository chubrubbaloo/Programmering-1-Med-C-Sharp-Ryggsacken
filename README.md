# Programmering-1-Med-C-Sharp-Ryggsacken
Du ska i den här övningen skriva ett mer komplext program som hanterar inmatning och utskrift. Programmet är en ryggsäck som styrs genom en meny. Menyn visar tillvalen som finns för användaren.

----------------------------------------------------------
I den här uppgiften ska vi skapa ett program.

Programmet utgår från en strängvariabel som vi kan tilldela ett värde, skriva ut värdet, nollställa värdet och avsluta programmet.

Vi behöver arbeta med en meny och en while-loop som upprepas tills användaren väljer att avsluta programmet.

För att klara uppgiften behöver vi ha en förståelse för variablers livslängd och kodblock.

Kom ihåg; allting inom en loop upprepas; där även deklarationer!

----------------------------------------------------------
För att lösa uppgiften behöver du använda dig av följande delar från "Del II - Grunderna i programmering" i boken.

Utskrift till konsolapplikationen (kapitel 3).

Inmatning av data, spara i variabler med korrekt datatyp (kapitel 3).

Selektion, IF eller SWITCH för menyn (kapitel 4). Förslagsvis SWITCH, då det är bättre för menystrukturer.

Loop som accepterar menyval tills användaren väljer att avsluta programmet, se exempel 5.4 (s.58).

Kodblock och variablers livslängd, repetera Kapitel 6 och fundera på hur det påverkar ditt program.

------------------------------------------------------------
Programmet ska förutom att skriva ut och visa menyn innehålla möjlighet att:

Spara ett föremål i ryggsäcken, användaren ska kunna mata in en sträng under menyval 1, detta ska sparas. Du kan göra det genom att tilldela en Console.ReadLine() till 

strängvariabeln. Se kapitel 3, och kom ihåg att du kan tilldela och deklarera på två olika platser.

Den inmatade strängen ska kunnas skrivas ut i menyval 2.

När användaren väljer menyval 3 ska strängens värde rensas eller nollställas. Tilldela strängvariabeln ett tomt ""-värde.

Menyval 4 ska avsluta menyloopen.

Kommentera och förklara din kod, försök att förklara och motivera dina val.
