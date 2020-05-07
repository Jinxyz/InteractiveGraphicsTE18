03/04
Storlek måste ändras på paddle så den ser smal och lång ut. Man ska ej kunna flytta paddle i vänster och höger led. En till paddle ska läggas till så det går att spela en mot en. Poängsystem måste läggas till när bollen vidrör vänster och höger sida. En paddel kan åka ut ur skärmen vilket resulteras i en out of bounds exception, det måste fixas.

Ordningen för saker som ska fixas är grafiken allra först, rörlighet sen, buggfixar sist. 

Det viktigaste är att spelet fungerar på en basnivå så att allt går att köra.

09/04 
Bollen börjar om i mitten när den rör vänster eller höger kant. Den får även motsatt riktning än vad den hade innan den rörde väggen. 

23/04 
Experimenterat med score system men inte lyckats bli klar så ingen kod för det. Ska fixa så att spelet startas med space och så att den får motsatt riktning från vad den hade efter man klickat space.

24/04 
Spelet startas med space. Score system funkar nästan med en JOptionPane som kommer upp varje gång någon får poäng.  

07/05 
Score system funkar som en JOptionPane. Spelet startas fortfarande med space, men jag upptäckte att det gick att ändra riktning på bollen med space under spelets gång vilket jag tog bort genom att när bollen är stilla, så kan man klicka space men inte annars. 