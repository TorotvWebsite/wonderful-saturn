---
title: General enquiries
sections:
  - type: hero_section
    title: This is the Hero
    subtitle: The optional subtitle
    align: center
    padding_top: medium
    padding_bottom: medium
    background_color: primary
  - type: form_section
    content: >
      ![](https://makersrocket.com/content/images/2021/01/cd04d76efb163173241a14093f46156f3875f639-3270x1004.png)
    content_align: left
    form_position: right
    form_width: fifty
    form_layout: inline
    enable_card: true
    form_id: contact-form
    form_action: /thank-you
    form_fields:
      - type: form_field
        input_type: text
        name: name
        label: Name
        default_value: Your name
        is_required: true
      - type: form_field
        input_type: email
        name: email
        label: Email
        default_value: Your email address
        is_required: true
      - type: form_field
        input_type: select
        name: subject
        label: Subject
        default_value: Please select
        options:
          - Other
      - type: form_field
        input_type: textarea
        name: message
        label: Message
        default_value: Your message
      - type: form_field
        input_type: checkbox
        name: consent
        label: >-
          I understand that this form is storing my submitted information so I
          can be contacted.
        is_required: true
    submit_label: Send Message
    align_vert: top
    padding_top: medium
    padding_bottom: medium
    background_color: secondary
template: advanced
---
