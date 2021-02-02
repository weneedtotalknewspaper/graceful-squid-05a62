---
title: Contact
sections:
  - type: hero_section
    title: Contact
    align: center
    background_color: secondary
  - type: form_section
    content: >-
      ### Get in touch!
      
      If you have a story you'd like us to cover, feedback to give, or just a general inquiry, let us know!
      
      ### Join us on social media!
      
      We're on [Facebook](https://www.facebook.com/weneedtotalknewspaper), [Twitter](https://twitter.com/wnttnewspaper), and [Instagram](https://www.instagram.com/weneedtotalknewspaper/). Requests to join our Telegram channel are also open!
    content_align: left
    form_position: right
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
          - General inquiries
          - Pitching a story
          - Joining our team
          - Telegram channel
          - Feedback
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
template: advanced
---
