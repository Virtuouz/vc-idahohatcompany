---
_schema: default
draft: false
title: Home
eleventyExcludeFromCollections: false
disableNav: false
disableSitemap: false
removeFromNavigation: false
eleventyNavigation:
  key: Home
  order: 1
  title:
  parent:
  url:
pageLink: /
permalink: >-
  {% if pageLink == 'blog' or pageLink == 'Blog' %}/{{pageLink | slugify}}{% if
  pagination.pageNumber > 0 %}/page/{{ pagination.pageNumber }}{% endif
  %}/index.html{% elsif pageLink %}/{% assign pagelink = pageLink | slugify
  %}{{  page.filePathStem | fileSubstringFilter | append: pagelink | downcase
  }}/index.html{% else %}/{% assign title = title | slugify %}{{
  page.filePathStem | fileSubstringFilter | append: title | downcase
  }}/index.html{%endif %}
metaDesc:
customCode:
  headCode: ''
  bodyCode: ''
addToCollections: false
layout: layouts/page.html
hero:
  _bookshop_name: sections/fullImageHero
  content:
    highlightEybrow: false
    sectionId:
    eyebrow: \[\[st.name\]\] \| American Hat Company Certified Reseller
    headline: |-
      Selling Genuine Hats to

      Idaho for Over 20 Years
    description: >-
      \[\[st.name\]\] is family run business and we have sold **thousands**
      <br>of hats to proud Idahoans for over **20 years**
    buttons:
      - _bookshop_name: generic/button
        url: '#'
        openInNewTab: false
        text: Explore our hats
        color_group: primary
        colorFromGroup: primary
        ghostButton: false
        formSubmit: false
      - _bookshop_name: generic/button
        url: '#'
        openInNewTab: false
        text: Custom order a hat
        color_group: primary
        colorFromGroup: secondary
        ghostButton: false
        formSubmit: false
    image:
      _bookshop_name: generic/image
      imagePath: >-
        /assets/uploads/home/portrait-cowboy-sunset-american-west-illustration-ai-generative.jpg
      imageAlt:
      yAxisPosition:
      imageSizes:
      class:
      imageNumber:
  styles:
    color_group: primary
    contentAlignment: left
    textAlignment: left
    backgroundOpacity: 55
content_blocks:
  - _bookshop_name: sections/reviewCards
    content:
      sectionId:
      heading:
        _bookshop_name: generic/heading
        content:
          highlightEyebrow: false
          eyebrow: Wall of love
          headline: Hear it From Happy Customers
          description: ''
          buttons: []
          headingHierarchy: h2
        styles:
          contentAlignment: center
          textAlignment: center
          visualInterest: none
          visualInterestColor: '#000000'
          highContrast: false
          contrastColorGroup:
          contrastAgainst:
          textClassOverride:
      usePersonImage: false
      reviews:
        - review: cf5af1f3-4b28-4280-a664-0ef482ae9215
          card_color_group: 5c9075f8-80f9-4482-b041-91cffdfe02be
          colorFromGroup: primary
        - review: e8b58d19-77b3-4e15-9d00-88808b9dc2b4
          card_color_group: 5c9075f8-80f9-4482-b041-91cffdfe02be
          colorFromGroup: primary
        - review: 341e416f-ee7e-47d5-b833-efa5e4c6535a
          card_color_group: 5c9075f8-80f9-4482-b041-91cffdfe02be
          colorFromGroup: primary
        - review: b7b5b2d0-2aaa-4b47-9b8d-eb884ac5b0b3
          card_color_group: 5c9075f8-80f9-4482-b041-91cffdfe02be
          colorFromGroup: primary
        - review: 137dcc92-85bf-4937-8785-8e9bfc8eb9c5
          card_color_group: 5c9075f8-80f9-4482-b041-91cffdfe02be
          colorFromGroup: primary
        - review: 31517161-09a3-46e8-8041-f5dd1ac900c0
          card_color_group: 5c9075f8-80f9-4482-b041-91cffdfe02be
          colorFromGroup: primary
    styles:
      color_group: primary
  - _bookshop_name: sections/imageCarousel
    content:
      showNote: true
      sectionId:
      heading:
        _bookshop_name: generic/headingHorizontal
        content:
          highlightEyebrow: false
          eyebrow: Want to Browse?
          headline: Check out Some of Our Options
          description: |-
            At \[\[st.name\]\] we everything you need for men and women.

            * Hats
            * Boots
            * Belts
            * and more!
          buttons: []
          headingHierarchy: h2
        styles:
          headingRight: false
          visualInterest: none
          visualInterestColor: '#000000'
          highContrast: false
          contrastColorGroup:
          contrastAgainst:
      images:
        - _bookshop_name: generic/image
          imagePath: /assets/uploads/home/many-hats.jpg
          imageAlt:
          yAxisPosition:
          imageSizes:
          class:
          imageNumber:
        - _bookshop_name: generic/image
          imagePath: /assets/uploads/social-hat.jpg
          imageAlt:
          yAxisPosition: 50
          imageSizes:
          class:
          imageNumber:
        - _bookshop_name: generic/image
          imagePath: /assets/uploads/home/new-hats.jpg
          imageAlt:
          yAxisPosition:
          imageSizes:
          class:
          imageNumber:
        - _bookshop_name: generic/image
          imagePath: /assets/uploads/home/brown-and-browner-boots.jpg
          imageAlt:
          yAxisPosition:
          imageSizes:
          class:
          imageNumber:
        - _bookshop_name: generic/image
          imagePath: /assets/uploads/home/black-hat.jpg
          imageAlt:
          yAxisPosition:
          imageSizes:
          class:
          imageNumber:
        - _bookshop_name: generic/image
          imagePath: /assets/uploads/home/brown-and-pink-boots.jpg
          imageAlt:
          yAxisPosition:
          imageSizes:
          class:
          imageNumber:
        - _bookshop_name: generic/image
          imagePath: /assets/uploads/home/american-hat-compnay.jpg
          imageAlt:
          yAxisPosition:
          imageSizes:
          class:
          imageNumber:
        - _bookshop_name: generic/image
          imagePath: /assets/uploads/home/sombrero-charro.jpg
          imageAlt:
          yAxisPosition:
          imageSizes:
          class:
          imageNumber:
        - _bookshop_name: generic/image
          imagePath: /assets/uploads/home/blue-sombrerro-charro.jpg
          imageAlt:
          yAxisPosition:
          imageSizes:
          class:
          imageNumber:
    styles:
      color_group: primary
_inputs:
  removeFromNavigation:
    hidden: true
  eleventyNavigation:
    hidden: true
  headCode:
    type: code
    comment: Add code at the end of the <head> tag
  bodyCode:
    type: code
    comment: Add code before the </body> tag
  addToCollections:
    type: switch
    comment: Enabling this allows this page to be added to collections of your choosing
  tags:
    hidden: '!addToCollections'
    type: multiselect
    options:
      values: data.pageCollections.tags[*]
  collectionImage:
    hidden: '!addToCollections'
  imageAltText:
    hidden: '!addToCollections'
  keyInformation:
    hidden: '!addToCollections'
    label: Key information
    comment: >-
      Short description or summary for this page. Will be shown on the
      collection cards
    type: markdown
    options:
      link: true
      blockquote: false
      bold: true
      italic: true
      strike: true
      subscript: true
      superscript: true
      underline: true
      bulletedlist: true
      numberedlist: true
      indent: false
      outdent: false
      code: false
      embed: false
      horizontalrule: false
      image: false
      table: false
      undo: true
      redo: true
      removeformat: true
      copyformatting: true
---
