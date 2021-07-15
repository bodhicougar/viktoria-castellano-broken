---
title: "Contact me "
subtitle: ""
img_path: images/contact.jpg
form_id: contactForm
form_action: /success
form_fields:
  - type: form_field
    input_type: text
    name: name
    label: Name
    default_value: "Your name "
    is_required: true
  - type: form_field
    input_type: email
    name: email
    label: E-Mail
    default_value: "Please enter your e-mail address "
    is_required: true
  - type: form_field
    input_type: select
    name: subject
    label: "Subject "
    default_value: ""
    options:
      - Bitte mit mir telefonisch Kontakt aufnehmen
      - Übermittlung Lebenslauf
      - Fehler auf Seiten
      - Sonstiges
  - type: form_field
    input_type: textarea
    name: message
    label: Nachricht
    default_value: Ihre Nachricht
  - type: form_field
    input_type: checkbox
    name: consent
    label: Ich bin einverstanden, dass dieses Formular meine übermittelten
      Informationen speichert, damit ich kontaktiert werden kann.
    is_required: true
submit_label: "Send "
seo:
  type: stackbit_page_meta
  title: Contact
  description: This is the contact page
  extra:
    - name: og:type
      value: website
      keyName: property
    - name: og:title
      value: Get in Touch
      keyName: property
    - name: og:description
      value: This is the contact page
      keyName: property
    - name: og:image
      value: images/contact.jpg
      keyName: property
      relativeUrl: true
    - name: twitter:card
      value: summary_large_image
    - name: twitter:title
      value: Get in Touch
    - name: twitter:description
      value: This is the contact page
    - name: twitter:image
      value: images/contact.jpg
      relativeUrl: true
template: contact
---
