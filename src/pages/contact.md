---
title: 'Contact me '
subtitle: ''
img_path: images/contact.jpg
form_id: contactForm
form_action: /success
form_fields:
  - type: form_field
    input_type: text
    name: name
    label: Name
    default_value: 'Your name '
    is_required: true
  - type: form_field
    input_type: email
    name: email
    label: E-Mail
    default_value: 'Please enter your e-mail address '
    is_required: true
  - type: form_field
    input_type: select
    name: subject
    label: 'Subject '
    default_value: ''
    options:
      - 'Please contact me via phone '
      - 'Submission of vita '
      - 'Error on the page '
      - 'Contact me via E-mail '
  - type: form_field
    input_type: textarea
    name: message
    label: 'Message '
    default_value: 'Your message '
  - type: form_field
    input_type: checkbox
    name: consent
    label: >-
      I agree this website saves my submitted information so that I can be
      contacted 
    is_required: true
submit_label: 'Send '
seo:
  type: stackbit_page_meta
  title: 'Viktoria Castellano - Actress: Contact'
  description: >-
    Anna-Viktoria Castellano (born 19th March 1993 in Milano) is an
    Italian-German actress.

    From a very young age, Viktoria had a strong compassion for art.
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: 'Viktoria Castellano - actress: Getting in touch'
      keyName: property
    - name: 'og:description'
      value: >-
        Anna-Viktoria Castellano (born 19th March 1993 in Milano) is an
        Italian-German actress.

        From a very young age, Viktoria had a strong compassion for art.
      keyName: property
    - name: 'og:image'
      value: images/contact.jpg
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: Get in Touch
    - name: 'twitter:description'
      value: This is the contact page
    - name: 'twitter:image'
      value: images/contact.jpg
      relativeUrl: true
template: contact
---
