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
    - company: Samsung Electronics
      company_logo: samsung
      company_url: ""
      date_end: ""
      date_start: "2022-03-01"
      description: |2-
          Responsibilities include:
          * SSD Firmaware Architecture
          * DRAM/NAND Operation Optimization
      location: South Korea
      title: Senior Software Development Engineer
    - company: Samsung Electronics
      company_logo: samsung
      company_url: ""
      date_end: "2022-02-28"
      date_start: "2017-03-01"
      description: |2-
          Responsibilities include:
          * DRAM Test Methods & SW Development
          * DRAM Defense Methods & SW Development
      location: South Korea
      title: Software Development Engineer
    - company: Samsung Electronics
      company_logo: samsung
      company_url: ""
      date_end: "2016-08-14"
      date_start: "2016-06-01"
      description: Verification HW Acceleator with FPGA
      location: South Korea
      title: Solution Development Internship
    title: Work Experiences
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
    - name: Memory System
      tag: Memory System
    - name: Storage System
      tag: Storage System
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
