Intro:
Opdrachtgever: Bloemenpark Frankendael
Wensen opdrachtgever: QR code, nieuw map pagina design, inlog process versoepelen.

Beschrijving:
Bloemenpark Frankendael heeft mij gevraagd om een paar veranderingen te maken aan hun huidige design. Het gaat om de map van het park,
die heb ik wat meer zichtbaar gemaakt en een nieuwe map toegevoegd. Daarnaast heeft Bloemenpark Frankendael erom gevraagd het inlog process te verschrappen,
voor de oplossing heb ik een gast optie gemaakt, waar iedere gebruiker als een gast kan inloggen met 1 knopje. Alle informatie zoals opdrachten die je uitvoert worden lokaal opgeslagen en
collectie kan nog steeds blijven staan, alleen dan kan je de bloemencollectie zelfstanding afvinken en staan ze al gepresenteerd op een nieuwe pagina.


Huisstijl:
Van de opdrachtgever hebben wij een figma bestand ontvangen maar werd ons tegelijkerteid verteld om er zelf wat verandering hier en daar aan te brengen. Ik zal het proberen om bij te houden en hier en daar graphische veranderingen aan te passen.

Kenmerken:
HTML, CSS en JS
Homepagina, Veldverkenner (vernieuwde map pagina) en een nieuw collectie pagina.

HTML:
Ik heb meerdere HTML files gebruikt:
<img width="285" height="392" alt="image" src="https://github.com/user-attachments/assets/5bc8463e-2fa8-4d2f-8568-1fb292b438a0" />

In de <head> worden de CSS files: <link rel="stylesheet" href="styles.css"> en <link rel="stylesheet" href="style.css">

BODY
De structuur voor elk HTML pagina is Header, main en footer

In de header zul je het logo, achtergrond foto en je gast account informatie vinden

In de mains vind je:
div class="Kaart">
    <a href="veldverkenner.html">
      <img src="Images/map.WEBP" alt="Kaart">
    </a>
  </div>
Icoon die je kan klikken voor een verwijzing

(Dit is de carousel voor de homepagina die al het veldnieuws netjes laat zien, ook kan je zelf er doorheen scrollen als gebruiker)
<div class="carousel">
  <div class="carousel-track">
    <div class="group">

(Hier is het stuk voor de open source map pagina, de coordinaten zijn bedoeld om te plaatsen als link naar elke locatie van de bloem/plant, als je er op klikt zal je een informatiekaart tevoorschijn zien komen die je verteld over de bloem.
<map name="Mapkaart">
  <area shape="circle" coords="34,44,270,350" alt="Computer" href="computer.htm">
  <area shape="circle" coords="290,172,333,250" alt="Phone" href="phone.htm">
  <area shape="circle" coords="337,300,44" alt="Coffee" href="coffee.htm">
</map>


In de <footer>, zal je een navigatiebalk vinden waar je dus doorheen kan scrollen om de plekken te kunnen vinden. 


Bronnen:
https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements
https://www.youtube.com/
https://github.com/Crazeygruy/the-client-website
https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-readmes



