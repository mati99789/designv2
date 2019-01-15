Analys valfri: Laddningstid
================

Urval
----------------------
Jag har vald 3 sidor som är:  
[FC Barcelona](https://www.fcbarcelona.com/en/)  
[Liverpool LFC](https://www.liverpoolfc.com/welcome-to-liverpool-fc)  
[FC Bayern München](https://fcbayern.com/en)  

Metod
--------------------------

Jag hade tänkt mig att analyser dem 3 sidor när det gäller laddningstid och för det kommer jag använda mig av devtools för att ta reda på laddningstid och även använt mig av [SpeedPage](https://developers.google.com/speed/pagespeed/insights/)

Resultat
-----------------------
### FC Barcelona

Enligt PageSpeed Insights har fått 27 för mobil och 95 för dator. När man mäter tiden med devtools så ta det ca 10,82 sekunder för att ladda alla förfrågningar och storleken på hemsida är ca 6,60MB. Det finns alltid möjligheter för att sidan ska vara snabbare när det gäller för datorer som är t.ex. skuja upp CSS som inte används eller använda bilder med rätt storlek. Det märks att på några platser finns det för stora bilder. Sidan är fotfarande i beta så hoppas dem rättar till den när det gäller mobil för sidan är tungt.  

### Liverpool LFC

För LFC blev det lite bättre när det gäller mobil då den hade fått 44 och för dator 100. laddningstid ligger på 4,54s och storleken 3.93MB. Det känns bättre än FC Barcelona bilderna har rätt storlek och är anpasad. För att göra det bättre på mobilen kunde man ta bort resurser som blockerar renderingen eller skjuta upp CSS som inte används.

### FC Bayern München

Enligt devtools så första sidan liger på 23.35MB! coh slutfört total tid för att ladda alla förfrågningar 1,3min. Sidan är lika tungt som FC Barcelona då den inehåller både stora bilder men även video. PageSpeed Insights ger en låg värde för mobil som är 23 och 60 för dator. För att optimera sida mer kunde man läsa in viktiga resureser i förväg då det känns att sida laddas hela tiden medans man läser.
Analys
-----------------------

Fotbollen är jätte populär i hela världen och därför alla stora klubbar vill ger både information och locka mer fans genom deras hemsidor. I detta fallat hamnar man att bilderna spelar stor roll som är stora och tunga för att ger det bästa kvalitet. Själv tycker jag att det behövs inte lägga så tunga bilder för att locka mer folk. Sidan ska vara lätt hanterbart men i FC Bardelona och Bayern Muchen fallet tyckte jag att det blev för mycket saker som gjorde att det blev fullpackat.

Övrigt
-----------------------

Arbete gjort av Matteus Urbaniak
