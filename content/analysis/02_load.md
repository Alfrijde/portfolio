Analys av laddningstider på webbplatser
=====================================

I den här rapporten kommer jag att analysera laddningstiden på tre webbplatser.

Urval
------------
Jag valde tre museidatabaser att göra analysen på. Jag fortsätter på temat med museer och kulturarv. Databaser är stora och det är mycket information som ska komma fram. Samtidigt vill man ha en snabb databas och där användaren snabbt hittar det perosnen letar efter.

Metod
-------
Jag har använt mig av PageSpeed insight och Devtools för att göra analyserna.

Resultat
---------

<iframe src="https://onedrive.live.com/embed?resid=817C8618BD30BB01%213163&authkey=!AHuL4hSqZk9-vnw&em=2" width="700" height="650" frameborder="0" scrolling="no"></iframe>

### Digitalt museum

<img src="%base_url%/assets/img/digitaltmuseum.png" alt="Digitalt museums webbplats" class="colour">

Här är det bilder som behöver uppdateras till ett modernare format och bli bättre kodade, men även en server som behöver trimmas och reducera javaScript som inte används.

### Kringla

<img src="%base_url%/assets/img/kringla.png" alt="Kringlas webbplats" class="colour">

Här ligger det resurser och blockerar renderingen, men bilderna är också i ett äldre format.

### Stiftelsen Jamtli (sofie)

<img src="%base_url%/assets/img/jamtli.png" alt="Jamtlis webbplats" class="colour">


Här verkar problemet främst ligga i bilderna, både att de är i fel format men att de också borde vara i rätt storlek när det laddas in. 

Analys
--------
Alla tre webbplatserna hade problem med sina bilder och de tog lång tid att ladda. Jag förstår att det kan vara ett problem då alla tre baserade på bilder som ska visas och man gärna vill ha många bilder på sin startsida för att väcka intresse hos användaren att vilja söka i databasen. Men det är synd att bilderna är i ett omodernt bildformat som gör att de tar så mycket resurser. De två första webbplatserna har en längre laddningstid, men de är större databaser och med fler bilder på startsidan. Alla tre webbplatserna hade problem när webbplatsen besöktes med en mobil enhet. Där var resultaten riktigt dåliga. Det verkar som att man satsat främst på desktop-användare och deras upplevelse. Här kanske man kan dra en slutsats att man främst tänkt på forskning och att man som mer seriös användare av databasen sitter vid en desktop och inte slö söker i databasen i mobilen på bussen på väg hem. 

Vinnaren i analysen är Stiftelsen Jamtli och deras Sofie-databas. Jag valde att bara välja på resultaten i desktop-kategorin eftersom resultaten från mobil-kategorin var så dåliga. Jamtlis webbplats hade snabbast laddningstid även om den inte var minst och det var den enda som fick godkänt i prestandan i desktop-kategorin.
Jag upplevde laddningstiden som snabb på alla tre webbplatser, de som hade längre total laddningstid upplevdes som klara även när de hade något litet kvar att ladda som tog någon sekund extra att få plats. För mig beror upplevelsen av laddningstiden på vart jag är och vilken typ av sida jag vill ladda. Det värsta jag vet är när man tror att sidan laddat klart och man klickar på något men så laddas något annat element in och man klickar på något helt annat och att det sedan måste laddas in igen när man backar, så man lyckas göra samma sak igen. Så jag skulle väl säga att min optimala laddningstid är ett par sekunder, 3-4 max. 

Referenser 
----------

Digitalt museum hittar du<a href="https://www.digitaltmuseum.se/">här</a>

Kringla hittar du<a href="https://www.kringla.nu/">här</a>

Stiftelsen Jamtlis samlingar hittar du<a href="https://jlm.kulturhotell.se/">här</a>



Viktoria Arvidsson