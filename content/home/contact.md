---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 90

title: Contact
subtitle:

content:
  # Automatically link email and phone or display as text?
  autolink: true

  # Email form provider
  form:
    provider: netlify
    formspree:
      id:
    netlify:
      # Enable CAPTCHA challenge to reduce spam?
      captcha: false

  # Contact details (edit or remove options as required)
  email: dddd@umich.edu
  phone: 734 548 7514
  address:
    street: 1859 Shirley Lane, Apt 8B
    city: Ann Arbor
    region: MI
    postcode: 48105
    country: United States
    country_code: US
design:
  columns: '2'
---
