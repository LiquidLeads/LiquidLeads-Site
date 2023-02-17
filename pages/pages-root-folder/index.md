---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
permalink: /index.html

header:
  image_fullwidth: index-001.jpeg


widget1:
  title: "Our Services"
  url: '/services'
  image: 
  text: 'View Our Services.'
widget2:
  title: "Who We Are"
  url: '/about'
  image: 
  text: ''
widget3:
  title: "Contact"
  url: '/contact'
  image: 
  text: '<h3>Phone</h3> (832) 510-7123<br /> <h3>Email</h3> <ul> <li>info@liquidleads.us</li> <li>service@liquidleads.us</li></li> <li>support@liquidleads.us</li>'
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
  url: https://calendly.com/mayowa-liquidleads/demo
  text: Schedule A Free Call Now
  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---


