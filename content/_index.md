---
date: "2022-12-13"
sections:
- block: about.avatar
  content:
    text: null
    username: admin
  id: about
- block: collection
  content:
    count: 5
    filters:
      author: ""
      category: ""
      exclude_featured: false
      exclude_future: false
      exclude_past: false
      folders:
      - post
      publication_type: ""
      tag: ""
    offset: 0
    order: desc
    subtitle: ""
    text: ""
    title: Management
  design:
    columns: "2"
    view: compact
  id: posts
- block: portfolio
  content:
    buttons:
    - name: All
      tag: '*'
    - name: Indigenous Vegetables
      tag: Indigenous Vegetables
    - name: Improved Chicken
      tag: Demo
    default_button_index: 0
    filters:
      folders:
      - project
    title: Projects
  design:
    columns: "1"
    flip_alt_rows: false
    view: showcase
  id: projects
- block: markdown
  content:
    subtitle: ""
    text: '{{< gallery album="demo" >}}'
    title: Gallery
  design:
    columns: "1"
- block: contact
  content:
    address:
      city: Ahero
      country: Kenya
      country_code: KEN
      postcode: "40101"
      street: 87 Yogo Primary School
    coordinates:
      latitude: -0.235396
      longitude: 35.011409
    appointment_url: kagumbacbo@gmail.com
    autolink: true
    contact_links:
    - icon: twitter
      icon_pack: fab
      link: https://twitter.com/KagumbaCBO
      name: DM The CBO
    directions: From Katito or Awasi, go to Yogo Primary School and from there you will be directed to Kagumba
    email: kagumbacbo@gmail.com
    form:
      formspree:
        id: null
      netlify:
        captcha: false
      provider: netlify
    office_hours:
    - Monday to Friday 08:00 to 17:00
    - Weekends and Public Holidays Closed
    subtitle: null
    text: Contact us to know more about the CBO.
    title: Contact
  design:
    columns: "2"
  id: contact
title: null
type: landing
---
