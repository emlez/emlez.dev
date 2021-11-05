---
title: Contact
hide_title: false
sections:
  - section_id: contact-form
    type: section_form
    content: >-
      Hi there! Thank you so much for your interest in working together. Please
      fill the contact form below or send us an email at
      [emlez.dev@gmail.com](mailto:emlez.dev@gmail.com).
    form_id: contactForm
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: name
        label: Name
        default_value: Your name
        is_required: true
      - input_type: email
        name: email
        label: Email
        default_value: Your email address
        is_required: true
      - input_type: select
        name: subject
        label: Subject
        default_value: Please select
        options:
          - Job proposal
          - Sponsorship
          - Error on the site
          - Other
        is_required: true
      - input_type: textarea
        name: message
        label: Message
        default_value: Your message
        is_required: true
      - input_type: checkbox
        name: consent
        label: >-
          I understand that this form is storing my submitted information so I
          can be contacted.
        is_required: true
    submit_label: Send Message
  - section_id: lorem-ipsum
    image_alt: lorem-ipsum
    content: >-
      ## Lorem ipsum


      Lorem ipsum dolor sit amet, **consectetur adipiscing elit**, sed do
      eiusmod tempor incididunt ut labore et dolore magna aliqua.


      - Lorem ipsum

      - dolor sit amet
    type: section_content
seo:
  title: Emilio Sánchez Ramírez | Contact
  description: This is the contact page
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Emilio Sánchez Ramírez | Contact
      keyName: property
    - name: 'og:description'
      value: This is the contact page
      keyName: property
    - name: 'twitter:card'
      value: summary
    - name: 'twitter:title'
      value: Emilio Sánchez Ramírez | Contact
    - name: 'twitter:description'
      value: This is the contact page
    - name: 'og:image'
      value: /images/contact-preview.png
      keyName: property
      relativeUrl: true
layout: advanced
---
