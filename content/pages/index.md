---
title: Home
slug: /
sections:
  - type: GenericSection
    title:
      text: PyC is the PyTorch library for Concept-based Deep Learning
      color: text-dark
      type: TitleBlock
      styles:
        self:
          textAlign: center
    subtitle: Build interpretable deep learning models with ease
    text: ''
    actions:
      - label: Get started
        altText: ''
        url: /
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: secondary
        elementId: ''
        type: Button
      - label: See Tutorials
        altText: ''
        url: /
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
        type: Link
    elementId: ''
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
        flexDirection: row
        padding:
          - pt-24
          - pl-16
          - pb-24
          - pr-16
        justifyContent: center
      subtitle:
        textAlign: center
    backgroundImage:
      type: BackgroundImage
      altText: altText of the image
      backgroundSize: cover
      backgroundPosition: center
      backgroundRepeat: no-repeat
      opacity: 30
      url: /images/triangles_back.jpg
  - type: ImageGallerySection
    subtitle: Built & used by
    images:
      - type: ImageBlock
        url: /images/usi-logo.png
        altText: Empathy logo
        elementId: ''
        styles:
          self:
            padding:
              - pr-2
              - pl-2
      - type: ImageBlock
        url: /images/ku-logo.png
        altText: Wellster logo
        elementId: ''
      - type: ImageBlock
        url: /images/unisi-logo.png
        altText: Vise logo
        elementId: ''
      - type: ImageBlock
        url: /images/Sns-Scuola-Normale-Superiore-Pisa.png
        altText: Telus logo
        elementId: ''
      - type: ImageBlock
        url: /images/polito_logo.png
        altText: Contentful logo
        elementId: ''
      - type: ImageBlock
        url: /images/university-of-cambridge-logo-black-and-white.png
        altText: Sanity logo
        elementId: ''
    elementId: ''
    motion: move-to-left
    colors: bg-light-fg-dark
    styles:
      self:
        margin:
          - mt-0
          - ml-0
          - mb-0
          - mr-0
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
        justifyContent: center
      subtitle:
        textAlign: center
  - type: FeaturedItemsSection
    title:
      text: Key Features
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: ''
    items:
      - title: Easy
        subtitle: ''
        text: >+
          ##### Plug\&Play Concept Layers to build your interpretable learning
          pipeline.

        image:
          url: /images/icon2.svg
          altText: Featured icon two
          elementId: ''
          type: ImageBlock
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
            textAlign: left
            justifyContent: center
            borderWidth: 0
        type: FeaturedItem
      - title: Modular
        subtitle: ''
        text: >+
          ##### Modular design with reusable blocks to build customize your
          interpretable deel learning models.

        image:
          url: /images/icon3.svg
          altText: Featured icon three
          elementId: ''
          type: ImageBlock
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
        type: FeaturedItem
      - type: FeaturedItem
        title: Compatible
        subtitle: ''
        text: |+
          ##### Compatible with the most common PyTorch libraries.

        image:
          type: ImageBlock
          url: /images/icon1.svg
          altText: Placeholder text
          elementId: ''
          styles:
            self:
              borderRadius: x-large
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
            justifyContent: center
            textAlign: left
    actions:
      - label: Get started
        altText: ''
        url: /
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
        type: Button
    elementId: ''
    variant: three-col-grid
    colors: bg-neutral-fg-dark
    styles:
      self:
        padding:
          - pb-16
          - pt-16
          - pl-16
          - pr-16
        justifyContent: center
      subtitle:
        textAlign: center
    backgroundImage:
      type: BackgroundImage
      altText: altText of the image
      backgroundSize: cover
      backgroundPosition: center
      backgroundRepeat: no-repeat
      opacity: 100
  - type: GenericSection
    title:
      type: TitleBlock
      text: Get Started
      color: text-dark
    subtitle: ''
    text: |+
      #### 1. Import the library

      #### 2. Build the model

      #### 3. Train

    actions:
      - type: Link
        label: See Tutorials
        url: /
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
    media:
      type: ImageBlock
      url: /images/Screenshot from 2024-06-27 16-13-58.png
      altText: Fun feature preview
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
seo:
  metaTitle: Home - Demo site
  metaDescription: This demo site is built with Netlify Create.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---
