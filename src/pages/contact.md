---
title: Kontakt
img_path: images/contact.jpg
form_id: contactForm
form_action: /success
form_fields:
  - type: form_field
    input_type: text
    name: name
    label: Name
    default_value: Ihr Name
    is_required: true
  - type: form_field
    input_type: email
    name: email
    label: E-Mail Adresse
    default_value: E-Mail Adresse eingeben
    is_required: true
  - type: form_field
    input_type: select
    name: subject
    label: Betreff
    default_value: Bitte auswählen
    options:
      - Bitte mit mir mehr Informationen zukommen lassen
      - Fehler auf den Seiten
      - Übermittlung Lebenslauf
      - Sonstiges
  - type: form_field
    input_type: textarea
    name: message
    label: Nachricht
    default_value: Ihre Nachricht
  - type: form_field
    input_type: checkbox
    name: consent
    label: >-
      Ich bin einverstanden, dass dieses Formular meine übermittelten
      Informationen speichert, damit ich kontaktiert werden kann.
    is_required: true
submit_label: Senden
seo:
  type: stackbit_page_meta
  title: Get in Touch
  description: This is the contact page
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Get in Touch
      keyName: property
    - name: 'og:description'
      value: This is the contact page
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
subtitle: Per E-Mail Kontakt aufnehmen
---
Formular für Kontaktaufnahme ausfüllen, bitte. 
