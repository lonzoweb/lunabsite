---
type: PageLayout
title: LUNABUNNIES TALENT AGENCY
sections:
  - type: ContactSection
    title: LUNABUNNIES - COMING SOON
    text: |
      Drop your email and we'll keep you up to date.
    form:
      type: FormBlock
      title: Title of the form
      fields:
        - type: EmailFormControl
          name: email
          label: email
          hideLabel: true
          placeholder: ''
          width: full
          isRequired: true
      submitLabel: SIGN UP
      elementId: contact-form
      styles:
        submitLabel:
          textAlign: left
    colors: colors-d
    backgroundSize: full
    elementId: 'netlify'
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-28
          - pb-36
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      text:
        textAlign: left
addTitleSuffix: true
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: /images/bg2.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 80
---
