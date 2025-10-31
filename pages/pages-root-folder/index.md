---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: mirrotronCoolingHdr.jpg
widget1:
  title: "A Compact Superconducting Accelerator"
  video: '<a href="#" data-reveal-id="videoModal1"><img src="/images/fermilabThumb.png" width="450" height="253" alt="" style="border: 5px solid #89bee6;"/></a>'
widget2:
  title: "ConcenSmart"
  video: '<a href="#" data-reveal-id="videoModal2"><img src="/images/concenSmartThumb.png" width="450" height="253" alt="" style="border: 5px solid #89bee6;"/><a>'

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
#  video: 'https://www.youtube.com/embed/ixhx7huZjTI?si=0Gq-TxCqrKp-QzCg'
#  title: 'Featured Video: Blinky-Leak Installation'

permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---
<div id="videoModal1" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://player.vimeo.com/video/1128899793?dnt=1" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
<div id="videoModal2" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://player.vimeo.com/video/1112714776?dnt=1" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
