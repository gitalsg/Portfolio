Load
=======================

Uppgiften handlar om att analysera laddningstiden för tre webbplatser. Utifrån mätvärden kommer jag att anaysera laddningstiden och eventuellt hur denna kan förbättras.

Urval
-----------------------

Jag har valt att analysera samma webbplatser som i tidigare kmom04 för att fortsätta att undersöka vidare dessa webbplatser. Jag har valt ut tre stycken webbplatser som har som mål att sälja varor till människor, och därför bör ha en webbplats som tilltalar kunder och är någorlunda snabb samt attraktiv för att inte tappa kunder. 

Metod
-----------------------

För undersökningen har jag använt mig av verktyget PageSpeed Insights samt Devtools - Network. Med hjälp av dessa verktyg kan man se webbplatsens prestande för mobilt och dator. De värderna som jag fick fram har jag samlat i ett Google Kalkylark där man kan se resultatet från tre tester för de webbplatserna som analyserats; på ett smidigt sätt kan man jämföra dessa med varandra. Här nedan kan man se sammaställningen av resultaten, som även kan ses här: [Analysis](https://docs.google.com/spreadsheets/d/1ASgPFp0rXllDr_LJp5bSdMsthWKE_bqUFsJ0oh_ULFw/edit?gid=0#gid=0)

<a href="%base_url%/image/analysis.png" target="_blank" aria-label="Analysis">
    <picture>
        <source media="(min-width: 668px)" srcset="%base_url%/image/analysis.png" alt="analysis">
        <img src="%base_url%/image/analysis.png&w=1200" alt="analysis">
    </picture>
</a>

Resultat
-----------------------

Rusta

<a href="%base_url%/image/rusta.png" target="_blank" aria-label="Rusta">
    <picture>
        <source media="(min-width: 668px)" srcset="%base_url%/image/rusta.png" alt="Rusta">
        <img src="%base_url%/image/rusta.png&w=667" alt="Rusta">
    </picture>
</a>

Länk - [Rusta](https://www.rusta.com/sv-se)

Prestandan för Rustas webbplats hamnar på ett genomsnitt av 
47 för mobilt och 76 för dator. Dessa värden är inte godkända enligt Test av Core Web Vitals; lite bättre för dator än mobilt. Laddningstiden är strax över två sekunder vilket är någorlunda snabbt jämfört med de två andra företagen. Sidans storlek är inte så hög men för att förbättra laddningstiden hade man kunna komprimera bilder samt minifiera CSS, JS och/eller HTML filer.

City Gross

<a href="%base_url%/image/citygross.png" target="_blank" aria-label="CityGross">
    <picture>
        <source media="(min-width: 668px)" srcset="%base_url%/image/citygross.png" alt="CityGross">
        <img src="%base_url%/image/citygross.png&w=667" alt="CityGross">
    </picture>
</a>

Länk - [City Gross](https://www.citygross.se/)

Webbplatsens genomsnittliga prestanda för mobilt är 46 och för dator 54, även är väldigt lågt för att vara en försäljningssida. Här kan vi se en högre laddningstid på 3,87 sekunder, vilket kan bero på sidans storlek som ligger på 8,1 MB. Eftersom att dessa webbplatser använder sig av mestadels bilder, ligger en stor del av förbättringspotetialen att optimera samt komprimera bilderna för att få en lägre laddningstid. 

Willys

<a href="%base_url%/image/willys.png" target="_blank" aria-label="Willys">
    <picture>
        <source media="(min-width: 668px)" srcset="%base_url%/image/willys.png" alt="Willys">
        <img src="%base_url%/image/willys.png&w=667" alt="Willys">
    </picture>
</a>

Länk - [Willys](https://www.willys.se/)

Företagets webbplats har i genomsnitt en prestanda på 15 för mobilt samt 32 för dator. Det är ett väldigt låg resultat med tanke på att företaget bör vilja inrikta sig att ha en så bra prestanda som möjligt för att göra det smidigt för sina kunder att navigera på webbplatsen. Webbplatsen har den längsta laddningstiden av dessa tre webbplatserna jag har undersökt, en tid på lite mer än 6 sekunder. Även här är bildkomprimering en lösning, samt bättre lösningar på JS och CSS för att sidan ska rendera bättre. 

Analys
-----------------------

Resultatet av undersökningen visar att dessa tre webbplatser har väldig låg prestanda, vilket kan bero på att de använder sig av många produktbilder, annonser, mm. som tar upp väldigt mycket och påverkar laddningstiden. Det verkar inte vara ovanligt eftersom att alla tre hade någorlunda långa laddningstider och sidornas totala storlek var någorlunda lika, förutom för Rusta där den var något lägre. Webbplatserna hade ändå inte så låga värden på de övriga värderna som PageSpeed Insights mäter men man hade kunnat förbättra deras prestande genom att se över bildoptimering samt minifiering av skript.

Utifrån mätvärderna så presterar Rustas webbplats bäst av de tre; sedan kommer City Gross och tillslut Willys, som hade sämst prestanda och lägnt laddningstid.

Laddningstid är en viktig aspekt när det gäller att få någon att stanna kvar på en webbplats, framförallt om det kan vara en potentiell kund. Gränsen för var som är snabbt är väl relativt men jag skulle tycka att något mellan 1-4 sekunder är snabbt. Mer ärn 6-8 sekunder skulle jag säga är något långsamt eftersom att man gärna vill att det ska hända saker snabbt. 
