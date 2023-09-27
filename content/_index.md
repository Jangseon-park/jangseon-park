---
date: "2022-10-24"
sections:
- block: about.biography
  content:
    title: Biography
    username: admin
  id: about
- block: experience
  content:
    date_format: Jan 2006
    items:
    - company: GenCoin
      company_logo: org-gc
      company_url: ""
      date_end: ""
      date_start: "2021-01-01"
      description: |2-
          Responsibilities include:
          * Analysing
          * Modelling
          * Deploying
      location: California
      title: CEO
    - company: University X
      company_logo: org-x
      company_url: ""
      date_end: "2020-12-31"
      date_start: "2016-01-01"
      description: Taught electronic engineering and researched semiconductor physics.
      location: California
      title: Professor of Semiconductor Physics
    title: Experience
  design:
    columns: "2"
- block: collection
  content:
    filters:
      featured_only: true
      folders:
      - publication
    title: Publications
  design:
    columns: "2"
    view: card
  id: featured
- block: portfolio
  content:
    buttons:
    - name: All
      tag: '*'
    - name: Deep Learning
      tag: Deep Learning
    - name: Other
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
- block: contact
  content:
    address:
      city: SanDiego
      country: United States
      country_code: US
      postcode: "92093"
      region: CA
      street: 9500 Gilman Drive
    autolink: true
    contact_links:
    email: jap036@ucsd.edu
    title: Contact Info
  design:
    columns: "2"
  id: contact
title: null
type: landing
---
