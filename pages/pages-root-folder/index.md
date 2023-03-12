---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
permalink: /index.html

header:
  image_fullwidth: "index-001.jpeg"
  

widget1:
  title: "Our Services"
  url: '/services'
  image: "contact-widget-002.jpeg"
  text: 'View Our Services.'
widget2:
  title: "Who We Are"
  url: '/about'
  image: "about-003.jpeg"
  text: 'At Liquid Leads we are dedicated to delivering high-quality valuable results to our clients because understand that is the best way to build a successful long-lasting relationship.'
widget3:
  title: "Contact Us"
  url: '/contact'
  image: contact-widget-001.jpeg
  text: '<h4>Phone</h4> (832) 510-7123<br /> <h4></h4>Email</h4> <ul> <li>info@liquidleads.us</li><li>support@liquidleads.us</li>'
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


  style: alert info
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---


