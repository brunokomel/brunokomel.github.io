---
# An instance of the Contact widget.
# Documentation: https://sourcethemes.com/academic/docs/page-builder/
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 130

title: Contact
subtitle:

content:
  # Automatically link email and phone or display as text?
  autolink: true
  
  email: brunokomel[at]pitt[dot]edu
  phone: +1 (360) 553-6277
  address:
    street: 230 S Bouquet St
    city: Pittsburgh
    region: PA
    postcode: '15260'
    country: USA
  contact_links:
  - icon: vcard
    icon_pack: fa
    name: 'Alternate spellings: Kömel, Komel, Koemel'
    link: ''



  
  # Email form provider
  form:
    provider:
    # provider: netlify
    formspree:
      id:
    netlify:
      # Enable CAPTCHA challenge to reduce spam?
      captcha: false
  
design:
  columns: '2'
---
