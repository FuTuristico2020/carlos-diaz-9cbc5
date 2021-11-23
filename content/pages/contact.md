---
title: Contact
sections:
  - type: hero_section
    title: Contáctame
    subtitle: Llena el siguiente formulario y pronto estaremos en contacto
    align: center
    padding_top: medium
    padding_bottom: medium
    background_color: none
  - type: form_section
    content: >
      ## Precios


      El precio de la consultoría se define por la cantidad de horas que el
      proyecto necesite. Si necesitas conocer el presupuesto a detalle,
      escríbeme un mensaje con tu propuesta y los servicios que vas a contratar
      y te daré el presupuesto.


      ## Propuesta


      El presupuesto de tu proyecto dependerá de la cantidad de servicios que
      necesites y las horas para ejecutarlo.  Tu propuesta tendrá un tiempo
      límite estipulado  de entrega que coincida con la realidad de tu proyecto.
      Esto será acordado antes de empezar con las actividades.


      ## Términos


      Al momento de empezar a trabajar con tu propuesta se necesitará un
      adelanto monetario dependiendo de las variables anteriores.
    content_align: left
    form_position: left
    form_width: fifty
    form_layout: stacked
    enable_card: true
    form_id: contact-form
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: name
        label: Nombre
        default_value: Your name
        is_required: true
      - input_type: email
        name: email
        label: Email
        default_value: Your email address
        is_required: true
      - input_type: textarea
        name: Tu mensaje
        label: Mensaje
        default_value: Your message
      - input_type: checkbox
        name: consent
        label: >-
          Acepto que este formulario está almacenando mi información para ser
          contactado
        is_required: true
    submit_label: Enviar
    align_vert: top
    padding_top: medium
    padding_bottom: medium
    background_color: primary
    background_image: /images/Patrones (3).png
    background_image_repeat: repeat
    background_image_size: contain
    background_image_opacity: 100
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
