---
_schema: default
title: Home
description: "SIGNAL is a growth marketing agency that builds brands people actually remember. Strategy, design, and performance under one roof."
pageSections:
  - _component: page-sections/heroes/hero-center
    eyebrow: GROWTH MARKETING AGENCY
    heading: "Cut through the noise"
    subtext: >-
      Most marketing is invisible. Forgettable campaigns, wasted ad spend,
      websites that look like everyone else's. SIGNAL exists because your brand
      deserves better than the algorithm's table scraps. We build marketing
      systems that compound.
    buttonSections:
      - _component: building-blocks/core-elements/button
        text: Start a Project
        link: /contact/
        variant: primary
        size: lg
      - _component: building-blocks/core-elements/button
        text: See Our Work
        link: /work/
        variant: tertiary
        size: lg
    colorScheme: dark
    backgroundColor: base
    paddingVertical: 6xl

  - _component: page-sections/builders/custom-section
    label: stats
    maxContentWidth: 2xl
    paddingHorizontal: lg
    paddingVertical: 4xl
    colorScheme: dark
    backgroundColor: surface
    contentSections:
      - _component: building-blocks/wrappers/grid
        gap: lg
        minItemWidth: "200"
        maxItemWidth: "300"
        items:
          - contentSections:
              - _component: building-blocks/core-elements/counter
                number: 340
                suffix: "%"
                alignX: center
                size: 3xl
              - _component: building-blocks/core-elements/simple-text
                text: "Average revenue growth for our clients"
                alignX: center
          - contentSections:
              - _component: building-blocks/core-elements/counter
                number: 48
                suffix: "x"
                alignX: center
                size: 3xl
              - _component: building-blocks/core-elements/simple-text
                text: "Best ROAS achieved across campaigns"
                alignX: center
          - contentSections:
              - _component: building-blocks/core-elements/counter
                number: 12
                suffix: "K+"
                alignX: center
                size: 3xl
              - _component: building-blocks/core-elements/simple-text
                text: "Monthly organic visitors generated"
                alignX: center
          - contentSections:
              - _component: building-blocks/core-elements/counter
                number: 97
                suffix: "%"
                alignX: center
                size: 3xl
              - _component: building-blocks/core-elements/simple-text
                text: "Client retention rate year over year"
                alignX: center

  - _component: page-sections/features/feature-grid
    eyebrow: WHAT WE DO
    heading: "Full-stack growth, no fluff"
    subtext: >-
      Strategy to execution. We do not hand you a PDF and wish you luck.
      Every engagement ships real work that drives real numbers.
    features:
      - _component: page-sections/features/feature-grid/feature-item
        iconName: chart-bar
        heading: Performance Marketing
        description: >-
          Paid search, paid social, programmatic. We manage seven-figure
          budgets and obsess over ROAS so you do not have to.
      - _component: page-sections/features/feature-grid/feature-item
        iconName: magnifying-glass
        heading: SEO & Content
        description: >-
          Technical SEO audits, content strategy, link building. Organic
          traffic that compounds month over month.
      - _component: page-sections/features/feature-grid/feature-item
        iconName: paint-brush
        heading: Brand & Creative
        description: >-
          Visual identity, messaging frameworks, campaign creative. Brands
          people recognize before they read the logo.
      - _component: page-sections/features/feature-grid/feature-item
        iconName: code-bracket
        heading: Web Development
        description: >-
          Fast, conversion-optimized websites built on modern stacks. No
          WordPress themes. No page builders. Clean code.
      - _component: page-sections/features/feature-grid/feature-item
        iconName: envelope
        heading: Email & Lifecycle
        description: >-
          Automated flows, segmentation, deliverability. Turn one-time buyers
          into repeat customers without burning your list.
      - _component: page-sections/features/feature-grid/feature-item
        iconName: presentation-chart-line
        heading: Analytics & CRO
        description: >-
          GA4 setups, conversion tracking, A/B testing. Decisions backed by
          data, not gut feelings and vanity metrics.
    colorScheme: dark
    backgroundColor: base
    paddingVertical: 5xl

  - _component: page-sections/features/feature-slider
    colorScheme: dark
    backgroundColor: surface
    paddingVertical: 5xl
    slides:
      - _component: page-sections/features/feature-slider/feature-slider-item
        eyebrow: CASE STUDY
        title: "Meridian Outdoors: 340% revenue growth in 9 months"
        description: >-
          Meridian came to us spending $40K/month on Meta ads with a 1.2x ROAS.
          We rebuilt their funnel from the ground up: new landing pages,
          restructured campaigns, lifecycle email flows. Nine months later they
          hit $2.1M in monthly revenue with a 4.8x blended ROAS.
        imageSource: /src/assets/images/component-docs/sunset.jpg
        imageAlt: Meridian Outdoors campaign
      - _component: page-sections/features/feature-slider/feature-slider-item
        eyebrow: CASE STUDY
        title: "Vault Health: from 0 to 12K organic visitors/month"
        description: >-
          A telehealth startup with zero organic presence. We built their
          content engine from scratch. 180 pages of medically-reviewed content,
          a technical SEO overhaul, and strategic link building. They now rank
          for 2,400+ keywords.
        imageSource: /src/assets/images/component-docs/castle.jpg
        imageAlt: Vault Health results
      - _component: page-sections/features/feature-slider/feature-slider-item
        eyebrow: CASE STUDY
        title: "Basecamp Labs: 6-week website rebuild, 2x conversions"
        description: >-
          Their old WordPress site loaded in 8 seconds and converted at 0.4%.
          We rebuilt on Astro with CloudCannon CMS, launched in six weeks,
          and watched conversions double in the first month. The team updates
          content without developer tickets.
        imageSource: /src/assets/images/component-docs/dunedin-cliff.jpg
        imageAlt: Basecamp Labs website

  - _component: page-sections/people/testimonial-section
    text: >-
      SIGNAL is the first agency that actually moved our numbers. Not
      vanity metrics, real revenue. They think like operators, not
      consultants. We went from burning cash on ads to a 4.8x ROAS
      in under a year.
    authorName: Rachel Torres
    authorDescription: CEO, Meridian Outdoors
    colorScheme: dark
    backgroundColor: base
    paddingVertical: 4xl

  - _component: page-sections/people/testimonial-section
    text: >-
      We interviewed eight agencies. SIGNAL was the only one that told us
      what we were doing wrong in the pitch instead of just agreeing with
      everything. That honesty has saved us hundreds of thousands.
    authorName: James Liu
    authorDescription: VP Marketing, Vault Health
    colorScheme: dark
    backgroundColor: surface
    paddingVertical: 4xl

  - _component: page-sections/ctas/cta-split
    heading: "Ready to stop guessing?"
    subtext: >-
      Tell us what you are working on. If we can help, we will tell you how.
      If we cannot, we will tell you that too. No pitch decks. No 12-week
      onboarding. Just results.
    buttonSections:
      - _component: building-blocks/core-elements/button
        text: Start a Conversation
        link: /contact/
        variant: primary
        size: lg
      - _component: building-blocks/core-elements/button
        text: See Our Work
        link: /work/
        variant: tertiary
        size: lg
    imageSource: /src/assets/images/component-docs/quiet-street.jpg
    imageAlt: SIGNAL office
    reverse: false
    colorScheme: dark
    backgroundColor: base
    paddingVertical: 5xl
---
