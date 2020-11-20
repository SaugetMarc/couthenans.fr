---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: header_unsplash_12.jpg

widget1:
  title: "Les horaires d'ouvertures"
  url: '/mairie/'
  image: 302px-Couthenans_Mairie.jpg
  text: 'Informations sur les horaires de permanence de la marie.'

widget2:
  title: "La vie associative de Couthenans"
  url: '/couthenans/1901'
  image: 1901.png
  text: "Couthenans est riche d'une activité associative variées, retrouvez ici l'ensemble des associations de notre village."
  
widget3:
  title: "Notre école"
  url: '/couthenans/ecole'
  image: ecole.png
  text: 'Notre école : ses classes, son site, ses services associés et ses horaires.'
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
callforaction:
  url: https://tinyletter.com/marcSauget
  text: 'Vous souhaitez être au courant des nouveautés de Couthenans en avant première !'
  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---


