---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
    image_fullwidth: "header_pluma.jpg"
    caption: Imagen por Sara L. Ríos
image:
    thumb: "Mapacolor.jpg"
teaser: El <a href='https://biodiversidad.gt'>Portal de Biodiversidad de Guatemala</a> es una plataforma especializada, basada en <a href='https://symbiota.org/es'>Symbiota</a>, para la digitalización y movilización de Colecciones Biológicas del país. Es administrado por <a href='https://biodiversidadgt.github.io/docs/contactos/'>biólogos guatemaltecos</a> y mantenido por el <a href='https://symbiota.org/ayuda/'>Symbiota Support Hub</a> y el [Biodiversity Knowledge Integration Center](https://biokic.asu.edu/) de Arizona State University, en apoyo a instituciones científicas nacionales. 

widget1:
  title: "Documentación Para Curadores"
  url: 'http://biodiversidadgt.github.io/docs/curadores/'
  image: Portal.jpg
  text: 'Doucumentación actualizada para la digitalización y manejo de colecciones en el Portal de Biodiversidad de Guatemala.'
widget2:
  title: "Documentación para Usuarios"
  url: 'http://biodiversidadgt.github.io/docs/usuarios/'
  image: Mapacolor.jpg
  text: 'Doucumentación actualizada para la la búsqueda y uso de información en el Portal de Biodiversidad de Guatemala.'
widget3:
  title: "Symbiota"
  url: 'http://symbiota.org/es/'
  image: widsymbiota.jpg
  text: 'Conozca más acerca de esta plataforma especializada en el manejo de datos de biodiversidad.'
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
  url: https://biodiversidad.gt
  text: Ir al Portal de Biodiversidad de Guatemala ›
  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---



