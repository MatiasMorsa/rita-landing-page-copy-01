---
title: General enquiries
sections:
  - type: hero_section
    title: Conctactanos
    subtitle: Se uno de los primeros en tener una RITA
    align: center
    padding_top: medium
    padding_bottom: medium
    background_color: none
  - type: form_section
    content: >-
      ## Venta

      Actualmente la venta de RITAs es exclusiva, si queres ser uno de 
      los primeros en poder obtenerla deberas dejarnos tus datos y nosotros
      nos comunicaremos contigo
  
    content_align: left
    form_position: right
    form_width: fifty
    form_layout: stacked
    enable_card: true
    form_id: contact-form
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: name
        label: Nombre
        default_value: Tu nombre
        is_required: true
      - input_type: email
        name: email
        label: Email
        default_value: Tu direccion de email
        is_required: true
      - input_type: select
        name: subject
        label: Subject
        default_value: Quiero comprar una RITA
        options:
          - Quiero comprar una RITA
          - Quiero saber mas sobre como funciona
          - Partnership
          - Other
      - input_type: textarea
        name: mensaje
        label: Mensaje
        default_value: Tu mensaje
      - input_type: checkbox
        name: consent
        label: >-
          Comprendo que al enviar este formulario estoy dando mis datos para que se contacten conmigo.
        is_required: true
    submit_label: Send Message
    align_vert: top
    padding_top: medium
    padding_bottom: medium
    background_color: primary
seo:
  title: General Enquiries
  description: This is the general enquiries page
  extra:
      - name: 'og:type'
        value: website
        keyName: property
      - name: 'og:title'
        value: General Enquiries
        keyName: property
      - name: 'og:description'
        value: This is the general enquiries page
        keyName: property
      - name: 'twitter:card'
        value: summary
      - name: 'twitter:title'
        value: General Enquiries
      - name: 'twitter:description'
        value: This is the general enquiries page
layout: advanced
---
