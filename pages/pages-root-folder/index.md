---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
widget1:
  title: "About the Exhibition"
  url: /info/
  image: exhibition_icon.png
  text: "ISTD Design Exhibition. Some history. Links to ISTD site and the Faculty for the courses."
widget2:
  title: "50.001 Project Showcase"
  url: /50.001/
  image: project_icon.png
  text: "Introduction to Information Systems and Technology"
widget3:
  title: "50.002 Project Showcase"
  url: /50.002/
  image: project_icon_2.png
  text: "Computation Structures"
#
# Use the call for action to show a button on the frontpage
#
# To make internal links, just use a permalink like this
# url: /50.001/
#
# To style the button in different colors, use no value
# to use the main color or success, alert or secondary.
# To change colors see sass/_01_settings_colors.scss
#
# callforaction:
#   url: https://tinyletter.com/feeling-responsive
#   text: Inform me about new updates and features ›
#   style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---