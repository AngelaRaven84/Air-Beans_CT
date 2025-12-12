# Air-Beans_CT # https://www.figma.com/board/PjRgPbN3eQorOFXWjv7fwJ/AirBean-FireBananas?node-id=0-1&p=f&t=Yn7ZjRicOTW02ajR-0
## Describing the different parts of computational thinking ##

### DECOMPOSITION ###


 

### PATTERN RECOGNITION ###
När vi hade gjort klart vår decomposition så började vi fundera på vilka saker som var återkommande. Det var svårt först att kunna se, men såg sedan att det som alltid händer när man kommer in på hemsidan är att det alltid köps en vara, varorna är alltid samma, ett köp genomförs och man får en orderbekräftelse. Vi såg också i profilsidan att man alltid återkom till sin profil vare sig man loggade in eller skapade en profil. Orderbekräftelsen återkommer också via kundkorgen efter köp och vid menyn i början.  

**Återkommande funktioner**
- Samma produkter i menyn
- nånting läggs i varukorgen vid köp
- beställningsbekräftelse finns vid både färdigt köp och via huvudmenyn
- min profil kommer både vid logga-in och skapa konto
- data skickas alltid till backend med info om användare, köp och orderhistorik
- data kommer från backend med info om användare, lagersaldo o.s.v.

Vi hittade också en del design som återkom på flera sidor i webappen  

**Återkommande komponenter i UI**
- Bakgrundsbilden med löv är ofta återkommande på flera av sidorna
- varje produkt är uppställd på exakt samma vis
- varje "lägg till" symbol ser likadan ut vid varje produkt
- profil- och "take my money"- knapparna har samma layout
- "Ok, cool"- knappen på beställningsbekräftelsen är samma layout som de andra knapparna, bara omvända färger.
- profilsidorna och Vårt kaffe-sidan har samma bakgrundsfärg
- huvudmenyn och min profil har samma bakgrundsfärg som är mörkare
  
### ABSTRACTION ###
Vår abstraction blev väldigt kort. Och vi är osäkra om den är komplett
1. användaren kommer till webappen
2. användaren går till menyn
3. en produkt läggs till i kundkorgen
4. klickar på kundkorgen
5. klickar på "take my money" knappen
6. beställningsbekräftelsen kommer fram med info om leveranstid
   
### ALGORITHM DESIGN ###

