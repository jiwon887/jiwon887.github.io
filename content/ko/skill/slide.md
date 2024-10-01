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
  loop: true
  # Duration of transition between slides (in ms)
  interval: 2000

content:
  slides:
    - title: C
      content: 프로그래머인 당신을 믿을 테니까 알아서 프로그래밍해라
      align: center
      background:
        position: center
        color: '#666'
        brightness: 0.7
        media: C.jpg
        fit: contain
    - title: C++
      content: 'std::println("Hello, world!");'
      align: left
      background:
        position: center
        color: '#555'
        brightness: 0.7
        media: c++.jpg
        fit: contain
    - title: Python
      content: '인생이 짧으니 파이썬을 사용해라'
      align: right
      background:
        position: center
        color: '#333'
        brightness: 0.5
        media: python.jpg
        fit: contain
    - title: Java
      content: '객체지향이라는 말을 내가 만들었지만, 그게 c++에 적용되진 않았다(Alan Kay)'
      align: right
      background:
        position: center
        color: '#444'
        brightness: 0.5
        media: java.jpg
        fit: contain

---