---
# An instance of the Contact widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 10

title: Contact
subtitle:

content:
  # Contact (add or remove contact options as necessary)
  email: hello@samuelcornell.com
 


  contact_links:
  - icon: twitter
    icon_pack: fab
    name: DM Me
    link: 'https://twitter.com/cornellsurf'
 

  # Automatically link email and phone or display as text?
  autolink: true
  
  # Email form provider
  form:
    provider: netlify
    formspree:
      id:
    netlify:
      # Enable CAPTCHA challenge to reduce spam?
      captcha: true
  
design:
  columns: '1'
---


