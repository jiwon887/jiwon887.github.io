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
      content: 프로그래머인 당신을 믿을 테니까 알아서 프로그래밍해라
      align: center
      background:
        position: right
        color: '#666'
        brightness: 0.7
        media: C.jpg
        fit: cover
    - title: C++
      content: 'std::println("Hello, world!");'
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