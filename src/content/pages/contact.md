---
_schema: default
title: Contact
description: "Start a project with SIGNAL. Tell us about your business and we'll figure out if we can help."
pageSections:
  - _component: page-sections/ctas/cta-form
    heading: "Let's talk about your growth"
    subtext: >-
      Tell us what you are working on. No sales pitch, no pressure. If we can
      help, we will tell you exactly how. If we cannot, we will tell you that
      too. Most responses within 24 hours.
    formAction: ./
    formBlocks:
      - _component: building-blocks/forms/input
        label: Your Name
        name: name
        type: text
        required: true
      - _component: building-blocks/forms/input
        label: Email
        name: email
        type: email
        required: true
      - _component: building-blocks/forms/input
        label: Company
        name: company
        type: text
        required: false
      - _component: building-blocks/forms/input
        label: Website URL
        name: website
        type: url
        required: false
      - _component: building-blocks/forms/select
        label: What do you need help with?
        name: service
        required: true
        options:
          - label: Performance Marketing
            value: performance
          - label: SEO & Content
            value: seo
          - label: Brand & Creative
            value: brand
          - label: Web Development
            value: web
          - label: Email & Lifecycle
            value: email
          - label: Multiple Services
            value: multiple
          - label: Not Sure Yet
            value: unsure
      - _component: building-blocks/forms/textarea
        label: Tell us about your project
        name: message
        required: true
      - _component: building-blocks/forms/submit
        text: Send Message
        variant: primary
        size: md
    imageSource: /src/assets/images/component-docs/quiet-street.jpg
    imageAlt: Get in touch with SIGNAL
    reverse: false
    colorScheme: dark
    backgroundColor: surface
    paddingVertical: 5xl
---
