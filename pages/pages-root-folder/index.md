---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  title: "Velommen til RF-Regi"
  image_fullwidth: "redbackline.jpg"
  #image_fullwidth: images/redbackline.jpg
widget1:
  title: "Lydutleie"
  url: '/utleie/lydutleie'
  image: lyd-eksempel.jpg
  text: 'Vi har det meste av høyttalere mikrofoner og mixere enten dere trenger utstyr til enkle oppsett som debatter, eller mere avanserte ting som revyer, konserter eller fester.'
widget2:
  title: "Lysutleie"
  url: '/utleie/lysutleie'
  image: lys-eksempel.jpg
  text: 'Vi har lyskontrollere, lyskastere, movingheads og strober. Trenger du lys til et arrangement har vi det du trenger.'
widget3:
  title: "Riggere og teknikere"
  url: '/utleie'
  image: geir-tek.jpg
  text: 'Trenger dere hjelp med rigging av utstyr eller avvikling av produksjonen så har vi mange flotte teknikere som gjerne tar på seg jobben med å hjelpe dere.'
widget4:
  title: "Frivillig i RF-Regi"
  url: '/frivillig'
  image: flex-i-garderobe.jpg
  text: 'Ønsker å være med i en studentforening? Er du glad i lyd, lys og tekniske ting? Kanskje vi er studentforeningen du ser etter! Ønsker du mere informasjon om hvordan det er å være i RF-Regi og moderforeningen vår Realistforeningen, klikk her.'
#
# Use the call for action to show a button on the frontpage
#
# To make internal links, just use a permalink like this
# url: /getting-started/
#
# To style the button in different colors, use no value
# to use the main color or success, alert or secondary.
# To change colors see sass/_01_settings_colors.scss
#
#callforaction:
#  url: https://tinyletter.com/feeling-responsive
#  text: Inform me about new updates and features ›
#  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---
