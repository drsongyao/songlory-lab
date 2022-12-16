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
    - title: Focus on Digital Humanities 🎨 专注数字人文
      content: Interdisciplinary Tasks + Rich Data + Outstanding Members = Our Lab
      学科交叉任务 + 丰富的数据资源 + 杰出的成员 = 本实验室
      align: center
      background:
        position: right
        color: '#666'
        brightness: 0.7
        media: pcs.png
    - title: Learn & Explore 📝 学习与探索
      content: 'Share your knowledge with the group and explore exciting new topics together!
      与大家分享你的知识，一起探索令人振奋的新课题!'
      align: left
      background:
        position: center
        color: '#555'
        brightness: 0.7
        media: env.png
    - title: Welcome to the group 👋 欢迎加入
      content: 'Are you interested? Why not join now?
      感兴趣？何不现在加入？'
      align: right
      background:
        position: center
        color: '#333'
        brightness: 0.5
        media: welcome.png
      link:
        icon: graduation-cap
        icon_pack: fas
        text: Join Us 加入我们
        url: ../contact/
---
