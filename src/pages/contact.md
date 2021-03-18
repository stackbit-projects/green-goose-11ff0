---
title: Contact
sections:
  - section_id: contact
    type: section_contact
    background: gray
    title: Contato
    content: |
      Por favor, envie seus dados para fazer um orçamento.
    form_id: contactForm
    form_fields:
      - input_type: text
        name: name
        label: Name
        is_required: true
      - input_type: email
        name: email
        label: Email
        is_required: true
      - input_type: select
        name: Subject
        label: Como ficou sabendo de nós.
        default_value: Por favor selecione
        options:
          - Internet
          - Amigo indicou
          - Outros
      - input_type: textarea
        name: message
        label: Mensagem
      - input_type: checkbox
        name: consent
        label: >-
          Eu entendo que este formulário está armazenando minhas informações
          enviadas para que eu possa ser contatado.
        is_required: true
    submit_label: Send Message
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
      value: summary_large_image
    - name: 'twitter:title'
      value: Contact
    - name: 'twitter:description'
      value: This is the contact page
template: landing
---
