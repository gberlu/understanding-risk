---
widget: slider
weight: 1
active: true
headless: true

design:
  # Slide height is automatic unless you force a specific height (e.g. '400px')
  slide_height: ''
  is_fullscreen: true
  # Automatically transition through slides?
  loop: false
  # Duration of transition between slides (in ms)
  interval: 2000

content:
  slides:
    - title: Introducing the project
      content: Take a look at what we're working on...
      align: center
      background:
        position: right
        color: '#666'
        brightness: 0.7
        media: umbrella.jpg
      link:
        icon: circle-question
        icon_pack: fas
        text: More information
        url: ../news/
#    - title: Lunch & Learn ☕️
#      content: 'Share your knowledge with the group and explore exciting new topics together!'
#      align: left
#      background:
#        position: center
#        color: '#555'
#        brightness: 0.7
#        media: contact.jpg
#      link:
#        icon: file
#        icon_pack: fas
#        text: More information
#        url: ../news/
    - title: Are you a man who buys sex in England and Wales?
      content: 'Consider taking part in the study'
      align: right
      background:
        position: center
        color: '#333'
        brightness: 0.5
        media: contact.jpg
      link:
        icon: envelope
        icon_pack: fas
        text: Contact Us
        url: ../contact/
---
