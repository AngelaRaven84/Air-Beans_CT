# Air-Beans_CT #
## Describing the different parts of computational thinking ##

### DECOMPOSITION ###
Vi bryter ner hela webbappen
- Air Bean
  - Menyn
    - Lägg till i varukorg
    - Pris
    - Varukorg
      - Produkt i varukorg
        - Beställningsbekräftelse
      - Totala Kostnaden 
  - Vårt Kaffe
    - Info text 
  - Min Profil
    - Skapa konto
      - Min profil
    - Logga in
      - Min profil 
  - Order Status
    - Beställningsbekräftelse

Det enklaste sättet vi kan beskriva det på är att vi valde att ta varje sida för sig och tittade vad för komponenter de innehöll, och vart det i så fall ledde vidare. 

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
Vår algorithm blev också väldigt kort och vi hade en fundering på om vi skulle lägga till flödet av hur man loggar in/skapar konto också
