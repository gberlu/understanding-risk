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
        url: 'https://understanding-risk.netlify.app/post/2022-02-01_introducing-the-project/'
    - title: Take part in the study
      content: 'We are interested in talking to men who have engaged with and visited escorts'
      align: left
      background:
        position: center
        color: '#555'
        brightness: 0.7
        media: microphone.jpg
      link:
        icon: file
        icon_pack: fas
        text: Take part
        url: 'https://understanding-risk.netlify.app/post/2022-08-01_recruiting-participants/'
    - title: Would you like more information about the study?
      content: 'Do not hesitate to reach out'
      align: right
      background:
        position: center
        color: '#333'
        brightness: 0.5
        media: contact.jpg
      link:
        icon: envelope
        icon_pack: fas
        text: Contact us
        url: ../contact/
---
