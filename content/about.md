---
Title: OM
Description: This is my about-site.
---

Min Om-sida
==========================

På denna sida används olika tekniker.

Pico är ramverket på sidan. Pico är ett så kallat flat.file CMS, vilket innebär att innehållet hämtas från filer istället för från en databas. Detta är en bra lösning ur säkerhetshänseende.

Layouten på webbplatsen så som header, footer och navbaren är skriven i twig. Alla content-sidor (som denna t.ex. är) är skrivna i MarkedDown (.md). .md har ett väldigt enkelt syntax vilket gör att det passar bra i denna kurs då fokus ska ligga på att skapa en snygg och användarvänlig webbplats och inte skriva snygg t.ex. HTML.

Temat (designen) på webbplatsen använder sig av SASS och filerna är skrivna i .scss. Detta gör det enkelt att skapa många moduler i scss som sen sparas ner i en stor css-fil genom kommandot $ npm run style.

Typsnitten på webbplatsen är hämtade från Google Fonts och alla ikoner är från Font Awesome och laddas in med hjälp av SASS.