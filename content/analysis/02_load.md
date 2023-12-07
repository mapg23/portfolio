---
Title: Load
Description: load analysis.
Template: analyze
---

Load
=======================

Uppgiften handlar om att undersöka olika webbplatser och ta reda på vilken ladd-tid dem har.

Urval
-----------------------
1. Amazon
2. Youtube
3. Bing

Jag valde att använda mig av tre hemsidor som laddar in mycket bilder/videor, men även som har mycket trafik.
Hemsidorna jag har valt är en hemsida som innehåller e-handel, en sökmotor och en hemsida som är en streaming site.
Jag valde dessa sidor för att jag ville ha tre hemsidor som fyller tre olika syften.

Metod
-----------------------

För att mäta ladd-tiden på hemsidorna använder jag mig av verktygen Pagespeed som är en hemsida där man kan läsa av ladd hastigheten samt min webbläsares developer tools.

Resultat
-----------------------

<iframe class="iframe load" title="excel-result" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vRq-ReTDy4afzrcYvIiLWR_cqQXuqZIu6yzX8MpFiYRhige2IIqyAhdhOctvKDw6M1cXH1nTPcR0OGt/pubhtml?widget=true&amp;headers=false">

</iframe>

### Amazon

Amazon hade över 1500 html element vilket gjorde hemsidan väldigt långsammare att ladda in.
Laddnings tiden hade gått ner om hemsidan hade använt sig av färre innehåll per sida.

Sidor att mätas:
1. <a href="https://www.amazon.se/gp/bestsellers/?ref_=nav_em_cs_bestsellers_0_1_1_2">Best sellers</a>

2. <a href="https://www.amazon.se/gp/help/customer/display.html?nodeId=508510&ref_=nav_em_cs_help_0_1_1_30">Kundtjänst</a>

3. <a href="https://www.amazon.se/deals?ref_=nav_cs_gb">Erbjudanden</a>


![Amazon](%base_url%/image/amazon.png)

<hr>

#### Youtube

Enligt verktyget Pagespeed hade hemsidan youtube kunnat reducera laddningtiden genom att ta bort oanvänd javascript för att sedan läggas till under runtime.

Sidor att mätas:
1. <a href="https://www.youtube.com/feed/trending?bp=6gQJRkVleHBsb3Jl">Trending</a>
2. <a href="https://www.youtube.com/channel/UCYfdidRxbB8Qhf0Nx7ioOYw">News</a>
3. <a href="https://www.youtube.com/feed/storefront?bp=ogUCKAI%3D">Movies</a>

![Youtube](%base_url%/image/youtube.png)

<hr>

#### Bing

Bing har över 2000 element vilket skapar längre ladd tid, reducera elementen för snabbare tid.
Enligt verktyget Pagespeed så lagrar inte hemsidan tillräckligt med innehåll i cache, vilket gör att flera saker behöver laddas in vid start av hemsidan. 

Sidor att mätas:
1. <a href="https://www.bing.com/news/search?FORM=Z9LH3">News</a>
2. <a href="https://www.bing.com/videos/onecolumn/landing?form=Z9LH1">Videos</a>
3. <a href="https://www.bing.com/images/feed?form=Z9LH">Images</a>

![Bing](%base_url%/image/bing.png)

<hr>


Analys
-----------------------

Hemsidorna jag analyserat har alla snabb laddningstid under 2000ms, förutom Youtube.
Youtube hade av dem alla tre sidorna som analyserats alltid en laddningstid över 2000ms, och vart även den största hemsidan i total storlek.

Det vanligaste återgärden för laddningstiden av dem tre hemsidorna var att reducera html elementen och ta bort oanvänd css och javascript. 

Jag tycker att en laddningstid under 1500ms är en relativt snabb webbplats.
Både amazon och bing klarar mitt gränsvärde för för att vara en snabb webbplats, men inte youtube.
Dock tycker jag att youtubes laddningsvärde är bra för att ladda in så pass mycket innehåll under laddningstiden.

<!-- Amazon vinner med minst laddnings tider. -->


Referenser
-----------------------

<!-- Ange de eventuella referenser du använder dig av, om några. -->

<a href="https://www.amazon.se/ref=nav_bb_logo">Amazon</a>

<a href="">Youtube</a>

<a href="https://www.bing.com/">Bing</a>

<a href="https://pagespeed.web.dev/"> Pagespeed </a>

Övrigt
-----------------------

Marcus Pettersson
<!-- Skriv ditt eget namn samt vilka gruppmedlemmar som deltog i att författa rapporten. -->