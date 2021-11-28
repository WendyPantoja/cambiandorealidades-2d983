---
title: Contáctanos
hide_title: false
sections:
  - section_id: contact-form
    type: section_form
    content: >
      ¿Estás interesado o interesada en compartir tu trabajo? 


      Llena el siguiente formulario y te informaremos de las convocatorias para
      ilustradores.
    form_id: contactForm
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: name
        label: Nombre
        default_value: Nombre
        is_required: true
      - input_type: email
        name: email
        label: Email
        default_value: Dirección de email
        is_required: true
      - input_type: select
        name: subject
        label: Asunto
        default_value: Selecciona
        options:
          - Error on the site
          - Sponsorship
          - Other
      - input_type: textarea
        name: message
        label: Mensaje
        default_value: Tu mensaje
      - input_type: checkbox
        name: consent
        label: >-
          Entiendo que este formulario almacena la información que he enviado
          para que puedan ponerse en contacto conmigo.
    submit_label: enviar
seo:
  title: Contact
  description: This is the contact page
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Contact
      keyName: property
    - name: 'og:description'
      value: This is the contact page
      keyName: property
    - name: 'twitter:card'
      value: summary
    - name: 'twitter:title'
      value: Contact
    - name: 'twitter:description'
      value: This is the contact page
layout: advanced
---
