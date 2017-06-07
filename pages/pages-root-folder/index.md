---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: 01home2000.jpg
  caption: Photo by @charles_forerunner - Unsplash.
  caption_url: https://unsplash.com/@charles_forerunner

widget1:
  title: "Change Management"
  url: '/02ocm/'
  image: 02ocm302x182.jpg
  text: '<b><i>Achieving sustained competitive advantage</b></i> requires contending with an evolving business terrain that offers both rewards and risks. <i>Building change capability</i> prepares your organization for avoiding threats and seizing opportunities along the path to realizing your strategic vision.'

widget2:
  title: "Communication"
  url: '/03com/'
  image: 03com302x182.jpg
  text: '<b><i>Embracing change</b></i> without disrupting day-to-day  operations involves overcoming uncertainty and information overload. <i>Facilitating 2-way communication</i> ensures essential feedback reaches decision makers and that employees have a clear sense of direction on how to participate.'

widget3:
  title: "Instructional Design"
  url: '/04insd/'
  image: 04insd302x182.jpg
  text: '<b><i>Realizing new capabilities</b></i> depends upon acquiring skills in a workplace filled with time constraints and job demands. <i>Designing a responsive learning solution</i> will provide employees with a personalized experience, whether through the classroom or a just-in-time mini lesson. '

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
#  text: Visit the Future State Resource Center ›
#  style: secondary
#permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/3b5zCFSmVvU" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
