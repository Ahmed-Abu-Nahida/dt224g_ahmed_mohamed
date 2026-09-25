# README.md i projektets repo
## **En kort beskrivning av innehåll och teknik**
- Webbplatsen handlar om en kort presentation av mig själv, min fotbollshobby samt ett spelschema som visar vilka dagar vi tränar. 
- Webbsidan är byggd som en enkel och semantisk HTML webbplats skapad i Laboration 1. 
- Den innehåller HTML5 märkspråk med grundläggande element.
- 
## *Länkar till de publicerade versionerna*
* GitHub Pages: https://ahmed-abu-nahida.github.io/dt224g_ahmed_mohamed/
* Netlify: https://fascinating-cucurucho-59d94a.netlify.app/
  
## *Skillnader mellan git add och git commit*
- Git add ser till att filen hamnar i staging area, vilket betyder att den är förberedd och redo inför nästa commit. 
- När filen ligger i staging area och du har gjort ändringar i projektet kan du skapa en commit. 
- En commit sparar dessa ändringar i Git historiken som en “snapshot” av projektet vid det aktuella tillfället. 
- Varje commit bygger vidare på tidigare commits och skapar en tydlig historik över alla ändringar som gjorts.
  
## *Fördel med att arbeta direkt branch istället Main*
- Att arbeta i en parallell branch gör det lättare att hålla ordning på ändringar och publicering.
- Om man arbetar direkt i main och repot är kopplat till GitHub eller Netlify, finns det risk att alla ändringar syns direkt på den publicerade webbplatsen,vilket kan skapa problem.
- Publiceringstjänster har ofta begränsningar i sina gratisplaner och det är onödigt att “slösa” bort det på små justeringar, som att ändra en rubrik eller fixar stavfel. 
- Därför är det bättre att arbeta i en separat branch och sedan slå ihop den med main när man är klar. På så sätt styr man själv när ändringarna ska publiceras.
  
## *Att göra en merge*
- När man gör en merge slår Git samman den färdiga branchen med main. 
- De ändringar som har gjorts i den separata branchen förs över till main och anpassas så att huvudgrenen uppdateras med de nya förändringarna.
  
## *Skillnaden mellan att pusha till GitHub och att publicera direkt på Netlify*
- Att pusha till GitHub innebär att man skickar sin lokala kod till ett versionshanteringsrepo i molnet. Där lagras projektets historik, commits och filer. 
- Med Github pages kan man publicera webbsidor helt gratis genom att pusha lokal repo för att skapa webbsidan via den. Tekniken stöds med HTML, CSS, JavaScript och bilder.
- Netlify däremot är en hosting  och publiceringstjänst som är gratis webbhotel. Netlify tar emot filerna och bygger en fungerande webbplats av dem.
  
## *Exkluderar en fil från versionshantering*
- Genom att skapa en fil som kallas .gitignore och skriver in filnamnet.
