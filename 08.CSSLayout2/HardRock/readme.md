# DesertTourism

Tip: druk **Ctrl+Shift+V** in VS Code om deze tekst opgemaakt weer te geven.

Deze oefening gaat over alle CSS layout technieken, zie [CSS cursus](https://rogiervdl.github.io/CSS-course/04_layout.html). 

De CSS is verdeeld over meerdere bestanden. Aan elke pagina zijn twee CSS bestanden gelinkt: een algemene `styles.css` en een paginaspecifieke CSS, b.v. voor de indexpagina:

```
<link rel="stylesheet" href="styles.css">
<link rel="stylesheet" href="css/pages/index.css">
```

Het bestand `styles.css` importeert vijf andere CSS bestanden (de namen spreken voor zich):

```
@import 'css/general.css';
@import 'css/header.css';
@import 'css/nav.css';
@import 'css/main.css';
@import 'css/footer.css';
```

## A. Body in breedte beperken en centreren

1. Beperk de breedte van de body tot 1200px en zet het centraal, zie [centreren of rechts plaatsen](https://rogiervdl.github.io/CSS-course/04_layout.html#centreren-of-rechts-plaatsen) uit de CSS Layout cursus.

## B. Horizontaal menu

2. Layout het menu. Inspireer je op [Voorbeeld 1: horizontaal menu](https://rogiervdl.github.io/CSS-course/04_layout.html#voorbeeld-1-horizontaal-menu-flexbox) uit de cursus. De ruimte tussen de menu items is 35px. 

## C. Header 

3. Layout de header. Inspireer je op [Voorbeeld 2: header layout](https://rogiervdl.github.io/CSS-course/04_layout.html#voorbeeld-2-header-layout-flexbox) uit de cursus. 
4. Aligneer de tekst "your indoor climbing hall" van het logo rechts

## D.Footer

5. Layout nu de footer op dezelfde manier als de header 
6. Layout het sociale media menu; de tussenruimte is 12px 

## E.Indexpagina

7. Beperk de halftransparante box in breedte tot 340px
8. Zet 60px padding boven en onder de banner
9. Plaats de box rechts in de banner; gebruik margins (net zoals je in 1. bij de body gedaan hebt)
10. Verdeel met CSS Grid de main in twee kolommen; de tweede kolom is 350px breed, tussenruimte is 40px
11. Maak de fotogallerij op; gebruik de minmax versie bij [Voorbeeld 5: foto gallerij](https://rogiervdl.github.io/CSS-course/04_layout.html#voorbeeld-5-foto-gallerij-grid) uit de cursus. Tussenruimte is 7px.
12. Aligneer de tekst "reserve your wall" rechts
13. Layout de drie afbeeldingen in de rechterkolom: beperk de breedte tot 100px, laat de tekst er rechts rondvloeien en zet een margin van 10px rechts en onder de afbeeldingen.  
14. Zet alle "Read more" links op aparte regels (tip: gebruik de `display` property en zet er een margin van 10px boven)

## F. Contactpagina

15. Layout de main: er zijn twee rijen en twee kolommen, 20px tussenruimte; het bovenste deel overspant twee kolommen
16. Maak het formulier op op; gebruik de minmax versie bij [Voorbeeld 4: formulier](https://rogiervdl.github.io/CSS-course/04_layout.html#voorbeeld-4-formulier-grid) uit de cursus. Tussenruimte is 10px, eerste kolom is 120px breed, berichtvak is 130px hoog. Zet de knop ook rechtsonder zoals het voorbeeld in de cursus.
17. Rek tenslotte de kaart horizontaal en verticaal uit (tip: gebruik `justify-self` en `align-self`). 