---
title: Home
slug: /
sections:
  - type: GenericSection
    title:
      text: Projeto SSAR
      color: text-dark
      type: TitleBlock
    subtitle: O que é este projeto?
    text: >+
      O **Projeto SSAR** é uma solução inovadora voltada para a modernização de
      **fazendas, sítios e áreas remotas**, garantindo conectividade, automação
      e eficiência operacional. Nossa tecnologia permite **monitoramento remoto,
      controle automatizado de equipamentos e comunicação estável**, mesmo em
      locais afastados.



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
    media:
      url: /images/main-hero.svg
      altText: Unblock your team boost your time to production preview
      elementId: ''
      type: ImageBlock
    badge:
      label: Aegis
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
  - type: FeaturedItemsSection
    title:
      text: Benefícios do uso desse sistema
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: Quais as vantagens?
    items:
      - type: FeaturedItem
        title: Custo
        subtitle: Menos gastos operacionais
        text: >+
          Nosso sistema reduz o desperdício de recursos e otimiza a gestão da
          propriedade rural, permitindo economia em combustíveis, insumos e mão
          de obra.



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
      - title: Monitoramento
        subtitle: Segurança Inteligente
        text: >+
          Com sensores e automação, agricultores podem monitorar suas terras em
          tempo real, prevenindo perdas e aumentando a produtividade.



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
      - title: Conectividade Avançada
        subtitle: Mais rapidez na tomada de decisões
        text: >+
          Mesmo em locais isolados, nosso sistema garante comunicação confiável,
          facilitando a gestão agrícola e o acesso a informações essenciais.





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
    badge:
      label: ''
      color: text-primary
      styles:
        self:
          textAlign: center
      type: Badge
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
  - posts:
      - content/pages/blog/case-study-1.md
      - content/pages/blog/case-study-2.md
      - content/pages/blog/case-study-3.md
    showThumbnail: true
    showDate: true
    showAuthor: true
    variant: three-col-grid
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
        justifyContent: center
    type: FeaturedPostsSection
    hoverEffect: move-up
  - type: DividerSection
    title: Divider
    elementId: ''
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-3
          - pl-3
          - pb-3
          - pr-3
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
  - title:
      text: Inovação para o campo
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: Vigilância local
    text: >
      O desafio de operar em áreas rurais sem infraestrutura adequada impede o
      crescimento de muitas propriedades. Nosso sistema foi desenvolvido para
      superar esses obstáculos, proporcionando uma segurança com tecnologia com
      uma rede local sem a necessidade de internet ou sem energia elétrica das
      distribuidoras elétricas. 
    media:
      title: Title of the video
      url: /images/placeholder-video.mp4
      controls: false
      aspectRatio: '16:9'
      styles:
        self:
          padding:
            - pt-2
            - pb-2
            - pl-2
            - pr-2
          borderColor: border-dark
          borderStyle: solid
          borderWidth: 1
          borderRadius: large
      type: VideoBlock
      autoplay: true
      loop: true
      muted: true
    badge:
      label: ''
      color: text-primary
      styles:
        self:
          textAlign: center
      type: Badge
    colors: bg-light-fg-dark
    styles:
      self:
        flexDirection: col
        justifyContent: center
      subtitle:
        textAlign: center
    type: GenericSection
  - type: GenericSection
    title:
      text: Vídeos do projeto
      color: text-dark
      styles:
        self:
          textAlign: left
      type: TitleBlock
    subtitle: ''
    text: |2
       Os Vídeos com o protótipo e a explicação com mais detalhes do produto ainda está em andamento, fiquem atentos para mais detalhes do projeto da nossa empresa.
    actions: []
    media:
      title: Title of the video
      url: /images/placeholder-video.mp4
      autoplay: true
      loop: true
      muted: true
      controls: false
      aspectRatio: '16:9'
      styles:
        self:
          padding:
            - pt-2
            - pb-2
            - pl-2
            - pr-2
          borderColor: border-dark
          borderStyle: solid
          borderWidth: 1
          borderRadius: large
      type: VideoBlock
    elementId: null
    colors: bg-light-fg-dark
    styles:
      self:
        flexDirection: row
        justifyContent: center
      subtitle:
        textAlign: left
  - title:
      text: Nossas redes sociais
      color: text-dark
      type: TitleBlock
    subtitle: ''
    text: >
      Caso tenham interesse, também teremos atualizações do projeto em nossas
      redes sociais, com mais frequência e uma comunicação mais direta com
      nossos clientes.
    actions:
      - label: Get started
        url: /
        icon: arrowRight
        iconPosition: right
        style: secondary
        type: Button
      - label: See Tutorials
        url: /
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        type: Link
    media:
      url: /images/hero2.svg
      altText: Fun feature preview
      type: ImageBlock
    badge:
      label: ''
      color: text-primary
      type: Badge
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
    type: GenericSection
  - title:
      text: Consulta e perguntas
      color: text-dark
      type: TitleBlock
    subtitle: Para empresas e patrocinadores
    text: >+
      Se você é um fornecedor, ou se interessou pelo nosso projeto, pode nos
      contatar via E-mail e nos enviar uma proposta ou uma reunião, iremos ouvir
      qualquer demanda de maneira ágil para que você tenha o melhor atendimento
      possível.

    actions:
      - label: Get started
        url: /
        icon: arrowRight
        iconPosition: right
        style: secondary
        type: Button
      - label: See Tutorials
        url: /
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        type: Link
    media:
      url: /images/hero3.svg
      altText: Dope design preview
      type: ImageBlock
    badge:
      label: ''
      color: text-primary
      type: Badge
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
    title: null
    subtitle: Conheça um pouco sobre a nossa moral em relação a segurança
    items:
      - title: >-
          “A verdadeira segurança do futuro depende da integração entre
          tecnologia avançada e gestão estratégica, onde a inovação é a chave
          para a proteção contínua de dados e ativos..”
        tagline: ''
        subtitle: 'Gusthavo Andrade, membro da Aegis segurança.'
        text: ''
        image:
          url: /images/person-placeholder-light.png
          altText: Maria Walters
          styles:
            self:
              borderRadius: full
          type: ImageBlock
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-9
              - pb-9
              - pl-9
              - pr-9
            textAlign: left
            borderRadius: large
            flexDirection: row
            justifyContent: center
        type: FeaturedItem
      - title: >-
          "A tecnologia não só reforça a segurança, mas também redefine os
          limites da proteção, permitindo que monitoramentos se tornem mais
          rápidos, precisos e eficazes."
        tagline: ''
        subtitle: 'Evely Alves, membro da Aegis segurança.'
        text: ''
        image:
          url: /images/person-placeholder-light.png
          altText: John Doe
          styles:
            self:
              borderRadius: full
          type: ImageBlock
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-9
              - pb-9
              - pl-9
              - pr-9
            textAlign: left
            borderRadius: large
            flexDirection: row
            justifyContent: center
        type: FeaturedItem
      - title: >-
          "Investir em segurança inteligente não é apenas sobre proteger hoje,
          mas garantir que a infraestrutura digital de amanhã esteja blindada
          contra ameaças cada vez mais sofisticadas."
        tagline: ''
        subtitle: 'Gabriel Oliveira, membro da Aegis segurança.'
        text: ''
        image:
          url: /images/person-placeholder-light.png
          altText: Maria Walters
          styles:
            self:
              borderRadius: full
          type: ImageBlock
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-9
              - pb-9
              - pl-9
              - pr-9
            textAlign: left
            borderRadius: large
            flexDirection: row
            justifyContent: center
        type: FeaturedItem
      - title: >-
          “Em fazendas, a segurança com tecnologia vai além de cercas físicas:
          sensores e câmeras conectadas podem prever e prevenir danos,
          proporcionando um ambiente mais seguro e produtivo.”
        tagline: ''
        subtitle: 'Pabliny Ferreira, membro da Aegis segurança.'
        text: ''
        image:
          url: /images/person-placeholder-light.png
          altText: Maria Walters
          styles:
            self:
              borderRadius: full
          type: ImageBlock
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-9
              - pb-9
              - pl-9
              - pr-9
            textAlign: left
            borderRadius: large
            flexDirection: row
            justifyContent: center
        type: FeaturedItem
    elementId: null
    variant: next-prev-nav
    colors: bg-light-fg-dark
    styles:
      self:
        justifyContent: center
      subtitle:
        textAlign: center
  - title:
      text: Central de ajuda ao cliente
      color: text-dark
      type: TitleBlock
    subtitle: seção de dúvidas
    text: >
      Para garantir a segurança do seu ambiente com tecnologia de ponta, entre
      em contato conosco e descubra como podemos ajudar a proteger o que você
      mais valoriza. Nossa equipe está pronta para oferecer soluções
      personalizadas, seja para sua empresa, fazenda ou vida pessoal. Não perca
      tempo, fale conosco agora mesmo e transforme sua segurança!


      **E-mail**: \[[seuemail@dominio.com]()]
             **Instagram**: @aegisperdizes
    media:
      fields:
        - name: ''
          label: Name
          hideLabel: true
          placeholder: Seu nome
          isRequired: true
          width: full
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Seu E-mail
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
seo:
  metaTitle: Home - Demo site
  metaDescription: This demo site is built with Netlify Create.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---
