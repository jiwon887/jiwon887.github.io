---
# An instance of the Experience widget.
# Documentation: https://docs.hugoblox.com/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 20

title: 공부
subtitle:

# Date format for experience
#   Refer to https://docs.hugoblox.com/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: MLP
    company: 
    #company_url: 'https://www.jbnu.ac.kr/kor/'
    company_logo: 
    location: 
    date_start: '2024-07-20'
    date_end: ''
    description: |2-
        여러 개의 뉴런 층으로 구성된 신경망으로, 각 뉴런이 이전 및 다음 층의 모든 뉴런과 연결되어 있으며, 일반적으로 지도 학습 작업에 사용됨
        [View PDF](MLP.pdf)

  - title: LeNet
    company: 
  #  company_url: ''
  #  company_logo: org-x
    location: 
    date_start: '2024-07-30'
  #  date_end: '2020-12-31'
    description: |2-
        레이어 간의 스킵 연결 또는 단축선을 포함하는 딥러닝 아키텍처로, 매우 깊은 네트워크의 학습을 가능하게 하여 소실 기울기 문제를 완화
        [View PDF](LeNet.pdf)
  
  - title: ReNet
    company: 
  #  company_url: ''
  #  company_logo: org-x
    location: 
    date_start: '2024-08-01'
  #  date_end: '2020-12-31'
    description: |2-
        가장 초기의 합성곱 신경망 중 하나로, 합성곱 층과 서브샘플링, 그리고 완전 연결 층으로 구성
        [View PDF](ReNet.pdf)


design:
  columns: '1'
---
