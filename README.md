# InteractiveList
A way to change a list of care tools into a low interactive view

## How to update the Excel
Hier leg ik kort uit hoe je de pagina kan updaten met behulp   
Van een online tool genaamt: ASPOSE Excel converter:  
Url: https://products.aspose.app/cells/conversion/excel-to-json

### Step 1 Excel up to date
Zorg dat alle nodige changes zijn gemaakt aan het excel bestand  
Doe wel nogmaal een check dat het gaat in coloum wise als:  
Toolnaam | Toolbeschrijving | Toolimg | Toollink  

### Step 2 Updaten
Ga naar de aangeven url in onder de update sectie.  
Eenmaal op de pagina klik op drop upload en selecteer het gewenste Excel bestand  
Check daarna of de **Save as** knop staat op JSON  
Zo ja klik dan op convert. Zo niet zet hem op json en click convert.

### Step 3 Update Zorgtools.Json
Je hebt nu een hoop text in het box. Kopieer dat en open ZorgTools.js  
Dit bestand staat onder in de JS folder. Laat het daar staan en open het  
Indaar plak de gekopieerde code tusssen:  
`var zorgToolData = Hier plakken` Mocht er nog oude data staan dan  
Haal dat weg zodat je eerst het volgende overhoudt: `var zorgToolData = `.  
Plak dan je gekopieerde code op de plek na de **=** en volla  
Save and your done de website zou nou moet updaten op iedere nieuwe laad.

### Step 4 Check Step 3
Mocht je hier komen met onzekerheid over stap 3. begin dan overnieuw  
Eenmaal bij stap 3 en het bestand open verwijder alles wat erin staat  
Voeg toe: `var zorgToolData = ` en plek je json data dan na **=** en volla.