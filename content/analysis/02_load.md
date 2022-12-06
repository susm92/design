---
Title: Load
Description: This is an report about load.
Template: analysis
---

# Utvärdering av webbplatsers laddningstid

Vi skall i följande rapport kort analysera laddningstiderna på 3 webbplatser, vi kommer även se över möjligheterna att förbättra laddningstiden samt hur/ om detta spelar in på användarbarheten.

Urval
-----------------------

Hemsidorna vi skall titta på i denna rapport är följande:
* https://www.svt.se/
* https://www.idg.se/
* https://www.dagensps.se/

<br>
Anledningen till varför vi valt att utgå från dessa hemsidorna är då vi vill se hur bilder speglar in på laddningstiderna samt användarbarheten på hemsidan som helhet.

Metod
-----------------------

Vi kommer använda oss av PageSpeed Insights för att verifiera hur stora antal poäng sidorna får samt även titta över hur mycket storlek som laddas för varje hemsida, detta kommer göras via developer tools i webbläsare (webbläsaren som använts är Mozilla Firefox).

Resultat
-----------------------

![screenshot dagensPS](%base_url%/image/dagensPS.png?w=250&h=250&crop-to-fit)
![screenshot idg2](%base_url%/image/idg2.png?w=250&h=250&crop-to-fit)
![screenshot svtNyheter](%base_url%/image/svtNyheter.png?w=250&h=250&crop-to-fit)

#####(från vänster till höger: dagensps.se, idg.se, svt.se)

<br>
## Mätningar via PageSpeed Insights & developer tools
<div class="embed-container">
    <iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vRdJdfydy6G8qE-NKZ1QHy-OuniobmaX4AgBeCR0c_Vx12Esf227NdyjbCppYq0ZoUdXv2ZGLh3GDbr/pubhtml?widget=true&amp;headers=false"></iframe>
</div>

<br><br>

## Förbättringsförslag hemsidor

Jag ser direkt inga stora förbättringsförslag när jag tittar till hemsidorna (<strong>svt.se</strong> & <strong>idg.se</strong>), detta då man gjort ett relativt bra jobb med bilderna då de inte är speciellt stora, men något som jag kan möjligtvis poängtera är att man ser över ifall det är möjligt att ändra på fonterna som används då jag kan se att de tar större plats vid överföring än bilderna.

Det största problemet med hemsidan <strong>dagensPS.se</strong> är att man valt att använda sig av många olika fonter, detta kan tydligt ses i developer tools, här ser vi också att de tar upp mer utrymme vid överföring än bilderna. Det känns som om man hade kunnat dra ner på några av fonterna för att försöka snabba uppsidans upplevnad överlag.

Analys
-----------------------

Efter att ha sett över resultaten för ovan hemsidor kan jag tydligt se att det vanligast förekommande bekymret när man jobbar med laddningstider är bilder och fonter.

Dagens webbutvecklare/ designers ser ut att ha med sig informationen om att många bilder kan bidra med att hemsidor laddas långsammare, vilket då bidrar till helhetsintrycket. Vad jag kunnat se i ovan urval av hemsidor är att man blivit mycket bättre på att ha i åtanke att hålla bilerna mindre för att få ner laddningshastigheterna, men något annat som då sticker ut är att om man använder sig av massor av annonser på sin hemsida bör man vara försiktig över hur många olika fonter man då väljer att ha med i hemsidan, detta då man inte på samma sätt kan komprimera dem som med bilder.

Detta är som sagt något som blir väldigt synligt på hemsidan <strong>dagensPS.se</strong>, som har nästan dubbelt så många förfrågningar jämfört med de andra hemsidorna som jag gått igenom.

Om vi då får rangordna ovan hemsidor baserat på mätvärdena jag tagit ut har vi <strong>svt.se</strong> på första plats, på andra plats kommer <strong>idg.se</strong> och på sista plats hittar vi <strong>dagensPS.se</strong>.

Tittar vi på <strong>dagensPS.se</strong> så ser vi att det på ett ungefär tar ca 7 sekunder att ladda hemsidan från det att man besöker den. Detta märks ganska tydligt då det tar ett tag för samtliga annonser, bilder och artiklar att ladda in innan allt är på sin plats. Tittar vi till de övriga hemsidorna så verkar det som om man bättre optimerat innehållet på hemsidan, då vi verkar landa på samma laddningstider för både <strong>svt.se</strong> och <strong>idg.se</strong>. Detta får mig personligen att tycka att man borde hamna på ett ungefär under 1,5 sekunder från det att man besöker hemsidan till det att allt är på plats, allt över det kommer att påverka användarerfarenheten på ett negativt sätt.

Referenser
-----------------------

1. https://pagespeed.web.dev/
2. https://developers.google.com/speed/docs/insights/rules
3. https://www.idg.se/
4. https://www.svt.se/
5. https://www.dagensps.se/
6. https://web.dev/why-speed-matters/

Övrigt
-----------------------

Följande stycke är skrivet av Sucro Smrkovic
