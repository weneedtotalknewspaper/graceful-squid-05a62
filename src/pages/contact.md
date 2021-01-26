---
title: Contact
sections:
  - type: hero_section
    title: Get in touch
    subtitle: >-
      Have a question? Send us a note using the form below and we will be in touch soon.
    align: center
    padding_top: medium
    padding_bottom: medium
    background_color: none
  - type: form_section
    form_width: fifty
    form_layout: inline
    enable_card: true
    form_id: contact-form
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
          - General questions
          - Joining our team
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
    submit_label: Submit
    align_vert: top
    padding_top: medium
    padding_bottom: medium
    background_color: primary
template: advanced
---
