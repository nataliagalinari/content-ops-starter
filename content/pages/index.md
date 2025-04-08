---
title: Home
slug: /
sections:
  - type: GenericSection
    title:
      text: Transforme seus negócios através do Tráfego Pago.
      color: text-dark
      type: TitleBlock
    subtitle: O que é tráfego pago?
    text: >
      Tráfego pago é uma estratégia do marketing digital que consiste em
      investir dinheiro em anúncios, com o intuito de gerar leads qualificados,
      aumentar as visitas no seu site e suas vendas.
    actions: []
    media:
      altText: Unblock your team boost your time to production preview
      elementId: ''
      type: ImageBlock
    badge:
      label: ''
      color: text-primary
      type: Badge
    elementId: ''
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
        flexDirection: row
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
  - title: Divider
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-7
          - pl-7
          - pb-7
          - pr-7
    type: DividerSection
  - type: FeaturedItemsSection
    title:
      text: Por quê contratar um gestor de tráfego?
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: ''
    items:
      - type: FeaturedItem
        title: Elaboração de estratégias de tráfego pago
        subtitle: ''
        text: ''
        actions: []
        elementId: null
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
        image:
          type: ImageBlock
          altText: Lightning bolt symbol on red background
          elementId: ''
          url: /images/icon1.svg
          styles:
            self:
              borderRadius: x-large
      - type: FeaturedItem
        title: >-
          Criação de públicos e audiências altamente segmentadas e com grande
          potencial de conversão.
        subtitle: ''
        text: ''
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
      - type: FeaturedItem
        title: Seleção precisa de objetivos de campanhas
        subtitle: ''
        text: ''
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
      - title: Organização financeira de gastos com anúncios online.
        subtitle: ''
        text: ''
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
        type: FeaturedItem
      - title: Criação de relatórios mensais para prestação de contas e resultados.
        subtitle: ''
        text: ''
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
  - title:
      text: Natália Galinari
      color: text-dark
      type: TitleBlock
    subtitle: ''
    text: >+
      Nascida no interior de Minas Gerais, mudou-se para Juiz de Fora para fazer
      faculdade de Artes e Design e logo em seguida realizou uma Pós-graduação
      em Comunicação e Marketing em Mídias Digitais. Atualmente, atua com
      Tráfego Pago com o objetivo de transformar e impulsionar negócios.

    actions: []
    media:
      url: /images/IMG_0067NataliaGalinariInsta.jpg
      altText: ''
      type: ImageBlock
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
        flexDirection: row-reverse
    type: GenericSection
  - title: Divider
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-7
          - pl-7
          - pb-7
          - pr-7
    type: DividerSection
  - type: CarouselSection
    title:
      type: TitleBlock
      text: '"Vencer sem correr riscos é triunfar sem glórias!"'
      color: text-dark
    subtitle: Ayrton Senna
    items: []
    elementId: null
    variant: next-prev-nav
    colors: bg-light-fg-dark
    styles:
      self:
        justifyContent: center
      subtitle:
        textAlign: center
  - subtitle: ''
    text: |
      contato.nataliagalinari\@gmail.com
    media:
      fields:
        - name: Nome
          label: Nome
          hideLabel: true
          placeholder: Nome
          isRequired: true
          width: full
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Email
          isRequired: true
          width: full
          type: EmailFormControl
        - name: message
          label: Message
          hideLabel: true
          placeholder: Sua mensagem
          width: full
          type: TextareaFormControl
      elementId: contact-form
      styles:
        self:
          padding:
            - pt-6
            - pb-6
            - pl-6
            - pr-6
          borderColor: border-dark
          borderStyle: solid
          borderWidth: 1
          borderRadius: large
      type: FormBlock
      submitButton:
        type: SubmitButtonFormControl
        label: Enviar
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: null
    badge:
      label: Entre em contato
      color: text-primary
      type: Badge
    colors: bg-light-fg-dark
    type: GenericSection
    actions:
      - type: Link
        label: Instagram
        altText: Instagram
        url: 'https://www.instagram.com/galinarinatalia/'
        showIcon: true
        icon: instagram
        iconPosition: left
        style: secondary
        elementId: ''
seo:
  metaTitle: Home - Demo site
  metaDescription: This demo site is built with Netlify Create.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---
