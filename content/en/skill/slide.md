---

widget: slider  # Use the Slider widget as this page section
weight: 1  # Position of this section on the page
active: true  # Publish this section?
headless: true  # This file represents a page section.dddd

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
    - title: C
      content: Since I trust you as a programmer, just go ahead and handle the programming
      align: center
      background:
        position: right
        color: '#666'
        brightness: 0.7
        media: C.jpg
        fit: cover
    - title: C++
      content: 'Share your knowledge with the group and explore exciting new topics together!'
      align: left
      background:
        position: center
        color: '#555'
        brightness: 0.7
        media: c++.jpg
        fit: cover
    - title: Python
      content: 'Just opened last month!'
      align: right
      background:
        position: center
        color: '#333'
        brightness: 0.5
        media: python.jpg
        fit: cover
    - title: Java
      content: 'Just opened last month!'
      align: right
      background:
        position: center
        color: '#444'
        brightness: 0.5
        media: java.jpg
        fit: cover
      link:
        icon: graduation-cap
        icon_pack: fas
        text: Join Us
        url: ../contact/

---