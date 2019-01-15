Kmom05
=========================

Vi skall välja ut ett antal olika webbplatser och testa dem för att mäta hur snabbt de laddas och om de innehåller några saker som kan förbättras med tanke på laddningstid och användbarhet.

Urval
-----------------------

Jag har vald 3 sidor som är:  
[Sigma hemsida](https://sigma.se/sv/)  
[ÅF hemsida](http://www.hh.se/index.html)  
[Getinge hemsida](https://www.getinge.com/se/)  

Metod
-----------------------

Metoden som jag har använt är devtools för att ta reda på laddningstid och även använt mig av [SpeedPage](https://developers.google.com/speed/pagespeed/insights/) sida. Sedan har jag tänkt att allt skulle dokumenteras på excelark som bigogas längre ner.


Resultat
-----------------------

###Sigma
[FIGURE src="image/sigma.jpg" caption="Sigma hemsida"]
Enligt PageSpeed Insights så fick hemsida skala på 88 och i mobilt läge 11. När man uppdatera sidan så tycker man att sida behöver lite stund innan det vissas upp. Det finns några saker som man kunde förbättra för att på mer poäng. Ta bort resurser som blockerar rendering möjligt tidsbesparing: 1740ms, nästa sak är att skicka bilder i modernare bildformat som man kunde spra data på 734kb, Använda bilder med rätt storlek eller skjuta upp inläsningen av bilder som inte visas på skärmen. Sidan har en bakgrund video som gör att sida blir tungt och även en hel del med bilder. När det gäller mobilt sida så har vi samma sak här att det finns flera möjligheter att förbättra hemsida det största optimering enligt PageSpeed Insights är att man ska ta bort resureser som blockerar rendering.

### ÅF
[FIGURE src="image/af.jpg" caption="ÅF hemsida"]
ÅF enligt PageSpeed Insights hamnar vänligt högt i skalan både för desktop men även för mobil som jag blev jätte förvånad, men det finns alltid något att lägga till att det ska blir bättre när det gäller desktop så kan man läsa in viktiga resureser i förväg eller ta bort resurser som blockerar renderingen. När det gäller på mobilen så kan man läsa in viktiga resurser i förväg som man kunde spara 1650ms. Det verka att bilder på mobil sida skulle man kunna koda bilder effektivt och skicka bilder i modernare bildformat. En grej som jag hade hittat som tyckte inte riktigt om är att bilder saknar "alt" text.

### Getinge
[FIGURE src="image/getinge.jpg" caption="Getinge hemsida"]
Getinge ser ut nästa samma som ÅF enligt PageSpeed hamnar på 99 desktop och 81 mobil. Det finns en hel bilder som man kunde skicka bilder i mdernare bildformat och använda rätt storlek. På Getinge hemsida man skulle kunna minska svarstiderna från servern för den verka vara långt och det märks när sidan har mer bilder. Det ser ut likadant när det gäller mobil, man skulle kiunna ta bort resurser som blockerar renderingen och skicka bilder i modernare bildformat.

Analys
-----------------------
Slut resultat för dem 3 sidor är att alla sidor behöver mer eller mindre små justeringar. Att sidan laddar 2s-3s kan man leva med och godkänna det men så fort det överstiger mer än 5s då tycker man att sida är långsam. Jag tycker idag har vi så snabb internet att folk ibland inte bryr sig om storleken på bilderna, man lägger fokus på responsivitet. I mitt test kan man enkel bedöma att ÅF sida vinner pga har minst med bilder eller video. Det känns helt ok att ha inte lika mycket bilder som tex Getinge eller Sigma, men att ha bara text och då o då en liten bild fungera inte för mig då tycker jobbigt att se bara text. Sigma har på hemsida video i bakgrunden snygg är det men storleken på det blir också stort som gör att sidan behöver lite stund innan det kommer upp, misstänker att kör man på segt internet så sidan dyker inte upp iaf video. När det gäller Getinge här har vi inte alls något video men där efter mer bilder än på Åf eller Sigma samt gör att när sidan laddas så laddas alla bilder på samma gång även om det inte skall visas direkt. Jag tycker att det bör man ha mer fokus på bilderna.


Referenser
-----------------------
[Excelark tryck här](https://docs.google.com/spreadsheets/d/124RF51ArXL3gwB0mAss6z7zQOpiezAvNzEyO1Nyer9k/edit#gid=0)

Övrigt
-----------------------

Arbete gjort av Matteus Urbaniak
