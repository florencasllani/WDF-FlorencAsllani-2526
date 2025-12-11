# Opgave: CSS design

Je krijgt een HTML pagina waarvan de layout en grote delen van het design al af is. Aan de HTML code mag je niks meer veranderen (tenzij voor het includen van een font); het is een zuivere CSS oefening.

Werk de pagina bij met CSS naar model van de meegeleverde screenshot.

De gebruikte rode kleur in deze pagina is #B52025; de grijze achtergrondkleur van de pagina is #dfdfdf; het roze is #FDEAEB.

Het maakt niet zo uit in welke volgorde je de opmaak doet. De basislijst:
- lettertype: Roboto (gebruik een hosted webfont, b.v. Google Fonts), standaard 13px, 1.8 regelhoogte
- pagina: grijze achtergrondkleur
- menu: opmaak + hover effect (tip: dit lijkt sterk op het horizontaal menu uit de CssMenus oefening)
- banner: tekstkleur, achtergrondafbeelding en rode rand
- tekst in de banner: achtergrondkleur van de tekst in de banner (tip voor transparantie: zie [deze slide](https://rogiervdl.github.io/CSS-course/02_design.html#/rgba-hsla))
- titels: opmaak
- links in de content: verberg de lijntjes eronder; toon lijntjes weer bij hover
- afbeeldingen links: rand errond
- more knoppen: opmaak
- newsletter formulier rechts: opmaak
- maak het tekstvak en de knop op rechts onder 'Newsletter' (achtergrondkleur input: #FDEAEB)
- footer: tekst centreren en gespikkelde rand erboven

Uitbreidingen:
- body: afgeronde hoeken linksboven en rechtsboven
- banner: schaduw errond
- menu & knoppen: 0.3s transitie op hover effect (zie `video-menuhover.gif` en `video-buttonhover.gif`)
- footer: gradiënt
- tekst in de content: in de breedte uitgerokken ("justify" in het Engels)
- titels: pijltjes toevoegen (tip: gebruik de ::after pseudoselector)

Gebruikte selectoren in deze oefening:
- tag-, .class- en #id selectoren
- :hover pseudo class selector
- ::after pseudo element selector
- [type=...] attribuut selector