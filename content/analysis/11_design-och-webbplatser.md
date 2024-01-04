---
Title: design och webbplatser
Description: analys angående färger.
Template: analyze
---

Design och webbplatser
=======================
Jag ska analysera en webbplats och ta reda på vad den har för ladd-tid.


Urval
-----------------------
Bew Gorp

Jag valde denna hemsidan då denna analys är till organisationen valfrihet som specifikt bad mig göra en analys för denna hemsidan.

Metod
-----------------------
För att analysera sidans ladd-tid har jag valt att använda mig av hemsidan Pagespeed där jag kan läsa av hastigheten.
Jag kommer även att använda mig av min webbläsares developers tools för att komplettera resultatet från Pagespeed, samt Googles extension "Lighthouse".


Resultat
-----------------------


<iframe class="iframe load" title="load-result" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vSIF_tybEXMB9e54ks09WC_7V2HJrP_ntgMNFJ_A5IJBnn6a5FiTVgeoMw65c1KxukV0cvxHENp9TZJ/pubhtml?gid=0&amp;single=true&amp;widget=true&amp;headers=false">
</iframe>

<hr>

#### Home page

![Home page](%base_url%/image/home-bew-gorp.png)

#### About page

![Home page](%base_url%/image/about-bew-gorp.png)


#### Highlights page

![Home page](%base_url%/image/highlights-bew-gorp.png)

Sidorna hade ganska lågt värde på best practice vilket berodde på att hemsidan körs utan ssl-sertifikat.
Mobil performence vart ganska låg, detta berodde på att scalen på bilderna kanske inte vart dem mest optimala, samt att ett nyare bild format som webP och AVIF.

Sidorna hade utmärkt responstid, och liten storlek.


Analys
-----------------------
<!-- 1. about
2. home
3. highlights -->

Resultatet av analysen är att hemsidorna hade väldigt låg ladd-tid, detta eftersom att hemsidan inte innehåller så mycket. Sidorna hade som mest 11 i requests vilket är väldigt lågt, och accessibility vart alltid på 100.

För att förbättra resultatet hade man kunnat skaffa ett ssl-sertifikat och kört hemsidan i https istället för http vilket hade ökat poängen från best practice samt använt nyare bild format, exempelvis webP eller AVIF.

Laddningstiden för sidorna vart aldrig över 200ms vilket är väldigt snabbt, jag tycker att en hemsida alltid ska ligga under 1000ms i laddningstid för att verka snabb.

Referenser
-----------------------


<a href="http://www.student.bth.se/~mapg23/dbwebb-kurser/design/me/kmom10/">Bew Gorp</a>

<a href="https://pagespeed.web.dev/">Pagespeed</a>

<a href="https://developer.chrome.com/docs/lighthouse/overview">Lighthouse</a>

Övrigt
-----------------------

Marcus Pettersson