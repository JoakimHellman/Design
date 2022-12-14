Laddningstid och användarbarhet
=======================

Denna rapport handlar om hur olika sidor presterar när man testar laddningstider och användarbarhet. En analys av detta genomförs i resultatdelen och resultaten diskuteras i analysdelen.

Urval
-----------------------

För denna annalys har jag valt tre stycken hemsidor från artister som deltagit i årets upplaga av tv-produktionen "Så mycket bättre". De utvalda är Måns Zelmelöw[1], Mats Wester (Nordman)[2]  och Johnossi[3]. Dessa har valts ut för att de faller under kategorin "personsidor" vilket innebär att de kommer kunna utgöra grunden även under kommande analyser. Tillvägagångssättet var att tänka ut kända svenska indivier eller artister. Eftersom jag inte har någon vidare bra fantasi så nyttjades listan över artiskter som deltar i årets "Så mycket bättre". Samtliga artisters hemsidor besöktes och valet landade därefter på dessa tre. I senaste rapporten gällande färger analyserades Darins hemsida istället för Mats Wester. Till denna rapport togs Darin bort eftersom hans hemsida endast utgör en startsida innehållande all information och som sen länkar vidare till andra sidor, så som Instagram, TikTok och eventbolag.

Metod
-----------------------
För att få en helhetsbild av hur prestandan och användarbarheten är på respektive webbplats genomfördes tester på tre olika sidor på webbplatsen, detta i syfte att inte få en missvisande bild av hela webbplatsen om en sida råkar vara mycket bra eller dåligt uppbyggd/designad.
För att genomföra analysen användes PageSpeed Insights, vilket är ett verktyg utvecklat av Google för att analysera webbplatsers prestanda och användarbarhet. Därtill mättes laddningstid, antal nerladdade resurser (requests) och sidans totala storlek som skickats (transferred) med hjälp av devtools flik Network i Chrome. Samtliga mätningar med devtools genomfördes tre gånger och ett genomsnitt räknades ut.
<br>
All data från testerna dokumenterades i ett kalkylark och redovisas i sin helhet samt uppdelat för respektive webbplats i resultatet.


Resultat
-----------------------
<br>
<h3>Sammanställt</h3>

<a href="https://docs.google.com/spreadsheets/d/e/2PACX-1vQM0q9PbOhvzhdb50BnQv-Vo6oIj2GjcGxX1SUe2cOg43j3o4p6Ayh72OBWzrf4aVvvCDaO6dvUlHeJ/pubhtml?widget=true&amp;headers=false" target="_blank">
    <iframe class="w100p h500f" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vQM0q9PbOhvzhdb50BnQv-Vo6oIj2GjcGxX1SUe2cOg43j3o4p6Ayh72OBWzrf4aVvvCDaO6dvUlHeJ/pubhtml?widget=true&amp;headers=false"></iframe>
</a>

<br>
<h3>Måns Zelmelöw</h3>

<img class='figure h300' src="%base_url%/image/mans.png?&save-as=jpg" alt="Skärmklipp på hemsida" title="Måns hemsida">


<iframe class="w100p h250f" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vRyDC6J569Aeg0GhQ-mridncibUgWUbD4Y4sAeQ5aGKnDOawiuDpPEuC9wTzBkNLdGT9a8sFYedha9A/pubhtml?widget=true&amp;headers=false"></iframe>
<br>
På Måns Zelmerlöws webbplats går det inte att få fram ett resultat baserat på det som kallas Viktiga vebbvärden. Jag vet inte varför men något med sidan hindrar att vissa av testresultaten, men ser man till de värden som PageSpeed kan kontrollera så är det höga (dåliga) värden rakt över. Därtill har webbpltsen den sämsta genomsnittliga prestandan av de tre undersökta hemsidorna, med ett medelvärde på 42,3 i prestanda. Framförallt är det mobil-testerna som får väldigt låga resultat och främsta anledningen till detta är att sidan innehåller mycket JavaScript som inte används, vilket medför en lång laddningstid. Dessutom har sidan det överlägset lägsta resultatet när det kommer till tillgänglighet med ett medelvärde på endast 60. Några av anledningarna till det låga resultatet är att alla bildelement inte har alt-attribut, vissa frame-element saknar titel och vissa länkar har inte ett igenkännligt namn. 

<br>
<h3>Mats Wester</h3>

<img class='figure h300' src="%base_url%/image/wester.png?&save-as=jpg" alt="Skärmklipp på hemsida" title="Westers hemsida">

<iframe class="w100p h250f" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vQuoCQXs8ysobmctw_VN-n8uaplrf9nSqyVFkckshIAh7UGi-1OGdEgc0uk52udwSAeuLBCsfFe12F_/pubhtml?widget=true&amp;headers=false"></iframe>
<br>
Mats Wester med sin enkla (fula och tråkiga) designade webbplats är den enda som blir godkännd när det kommer till "Viktiga webbvärden", iallafall när mobiltesterna genomförs. Dessutom har sidan den högsta genomsnittliga prestandan på ca 59 poäng och även den högsta tillgängligheten. Det som framförallt påverkar prestandan på webbplatsen är att det finns JavaScript som inte används, vilket borde reduceras. Utav de testade sidorna på webbplatsen sticker sidan "Musik & Produktion" ut på ett negativt sätt. Den har den längsta laddningstiden på nära 4 sekunder och eftersom den innehåller flertalet videoklipp som börjar spelas upp automatiskt drar stroleken snabbt iväg som medför en hög dataförbrukning, vilket är ett problem framförallt om man använder mobilabonnemang där man betalar för datatrafiken.

<br>
<h3>Johnossi</h3>

<img class='figure h300' src="%base_url%/image/johnossi.png?&save-as=jpg" alt="Skärmklipp på hemsida" title="Johnossi hemsida">

<iframe class="w100p h250f" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vTCxohtiXxdh1aBeDkC5NtSirSUqql-DKMxPXcpuGAnwtsqa3WPMuoCAo8iwmQ3-pBsHvyHK5DsZxa3/pubhtml?widget=true&amp;headers=false"></iframe>
<br>
Det är endast på Johnossis webbplats som det finns sidor som inte blir godkännda på "Viktiga webbvärden". Orsaken till detta är för höga värden på "Cumulative Layout Shift" (CLS) vilket innebär att objekt byter plats på sidan efter att de först har renderats, detta uppfattas störande och medför en försämrad upplevelse.[4] I övrigt har sidan en mycket låg mobil-prestanda men hög dator-prestanda vilket gör att medelvädet hammnar i mitten av de testade webbplatserna på 48 poäng. Problemet på webbplatsen är framförallt att den innehåller resurser som blockerar renderingen och att den innehåller mycket JavaScript som inte används. Webbplatsen är i sin uppbyggnad och även innehåll enkel och avskalad men en av de testade sidorna, "videos", innehåller många youtube-iframes vilket verkligen påverkar laddningstid och total storlek på sidan.

Analys
-----------------------

De vanligaste förbättringsåtgärderna för de undersökta webbplatserna är:

- Reducera JavaScript som inte används -> Detta är det som drar ner prestandan allra mest på Måns och Mats webbplatser, i flera fall med flera sekunder.
- Ta bort resurser som blockerar renderingen -> Framförallt har Johnossis webbplats problem med detta. Orsaken till att man får problem med detta är oftast att man kopierat in massa JS och CSS som sen inte används.[5] Tittar vi tillexempel på Johnossis sida TOUR i Devtools-Sources-Coverage får vi fram denna information:
<img class="w100p h250" src="%base_url%/image/johnossi_resurser.PNG" alt="Skärmklipp på hemsida" title="Johnossi dålig JS och CSS">
Allt som är rött är kod som är inläst men som inte används och vi kan se att det är väldigt hög procentandel av koden som inte används.
- Skicka bilder i modernare filformat -> Om vi tar Måns webbplats som ett exempel så används denna bild:
<img src="%base_url%/image/A-Grand-X-mas.jpg" alt="Skärmklipp på hemsida" title="Måns jul">
Det är en jpg-fil och är ganska exakt 700 kB, det innebär att bara den bilden motsvarar nästa hälften av hela sidans innehåll som ligger på 1,6 MB. Här nedanför har jag tagit samma bild men med hjälp av Cimage satt q=50. Detta gör att storleken går ner till 300 kB utan att, iallafall jag, med blotta ögat kan se någon försämring i kvalitten.
<img src="%base_url%/image/A-Grand-X-mas.jpg?q=50" alt="Skärmklipp på hemsida" title="Måns jul">
<br>

Utifrån uppnådda mätvärden kommer Mats Wester etta, Johnossi tvåa och Måns Zelmerlöw trea. Trotts detta upplever jag personligen att Mats hemsida är den sämsta av de tre. Den känns inte modern och de effekter eller animationer som används känns i flera fall ganska yxiga och tråkiga. Detta tillsammans med en i övrigt tråkig design gör att den totala användarupplevelsen blir den sämsta av de tre, trotts högre prestanda enligt testerna.
<br>
Om jag skulle sätta ett eget gränsvärde för absolut laddningstid skulle den nog hamna på runt 3-4 sekunder. Alla webbplatser i det här testet ligger inom, eller under det spannet med något enstaka undantag för enskilda sidor. Därför tycker jag inte att laddningstiderna på någon av de testade webbplatserna upplevs som ett problem. Därför blir det istället designen och hur den allmänna kännslan av webbplatsen som får störst betydelse för hur användarupplevelsen blir.
<br>
Som en slutsatts kan man alltså säga att mätningar likt de som gjort i denna analys endast kan ses som en del i vad man som utvecklare bör fokusera på när man skapar webbplatser. Så länge man säkerställer att laddningstider och tillgängliheten ligger innom gränserna för vad som kan uppfattas som "tillräckligt" är det betydligt viktigare att man säkerställer att sidan i övrigt uppfattas som snygg och smidig för att säkerställa att användarupplevesen är hög.


Källor
-----------------------
- [1] https://manszelmerlow.se/
- [2] https://www.matswester.se/
- [3] https://www.johnossi.com/
- [4] https://web.dev/cls/
- [5] https://developer.chrome.com/docs/lighthouse/performance/render-blocking-resources/?utm_source=lighthouse&utm_medium=lr

Övrigt
-----------------------

Joakim Hellman (rapporten genomförd självständigt)
