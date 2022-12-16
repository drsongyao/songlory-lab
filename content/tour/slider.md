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
    - title: Focus on Digital Humanities 🎨
      content: Interdisciplinary Tasks + Rich Data + Outstanding Members = SongLory's Lab
      align: center
      background:
        position: right
        color: '#666'
        brightness: 0.7
        media: pcs.png
    - title: Learn & Explore 📝
      content: 'Share your knowledge with the group and explore exciting new topics together!'
      align: left
      background:
        position: center
        color: '#555'
        brightness: 0.7
        media: env.png
    - title: Welcome to the group 👋
      content: 'Are you interested? Why not join now?'
      align: right
      background:
        position: center
        color: '#333'
        brightness: 0.5
        media: welcome.jpg
      link:
        icon: graduation-cap
        icon_pack: fas
        text: Join Us
        url: ../contact/
---
