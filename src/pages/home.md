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
  _bookshop_name: sections/fullImageTextBottomHero
  content:
    sectionId:
    highlightEybrow: false
    eyebrow: '\[\[st.name\]\]: Genuine Hats. Enduring Style. Since 2005.'
    headline: Crafting Idaho's Legacy, One Hat At A Time.
    description: >-
      For over **two decades**, \[\[st.name\]\] has been the trusted name for
      quality headwear. A **family-run legacy**, we're dedicated to finding or
      creating the **perfect hat** that speaks to **your unique story.**
    buttons:
      - _bookshop_name: generic/button
        url: '#'
        openInNewTab: false
        text: Explore our collection
        color_group: primary
        colorFromGroup: primary
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
    backgroundOpacity: 50
content_blocks:
  - _bookshop_name: sections/imageCarousel
    content:
      showNote: true
      sectionId:
      heading:
        _bookshop_name: generic/headingHorizontal
        content:
          highlightEyebrow: false
          eyebrow: Want to Browse?
          headline: Your Signature Style, Defined.
          description: >-
            Whether you're looking for iconic Western wear or a bespoke
            creation, explore our curated selection for every adventure.
          buttons:
            - _bookshop_name: generic/button
              url: '#'
              openInNewTab: false
              text: Explore our collection
              color_group: primary
              colorFromGroup: primary
              ghostButton: false
              formSubmit: false
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
        - review: 341e416f-ee7e-47d5-b833-efa5e4c6535a
          card_color_group: 5c9075f8-80f9-4482-b041-91cffdfe02be
          colorFromGroup: primary
        - review: e8b58d19-77b3-4e15-9d00-88808b9dc2b4
          card_color_group: 5c9075f8-80f9-4482-b041-91cffdfe02be
          colorFromGroup: primary
        - review: 31517161-09a3-46e8-8041-f5dd1ac900c0
          card_color_group: 5c9075f8-80f9-4482-b041-91cffdfe02be
          colorFromGroup: primary
        - review: c8c2e548-7b7f-4052-a2d5-8084a541260a
          card_color_group: 5c9075f8-80f9-4482-b041-91cffdfe02be
          colorFromGroup: primary
        - review: 137dcc92-85bf-4937-8785-8e9bfc8eb9c5
          card_color_group: 5c9075f8-80f9-4482-b041-91cffdfe02be
          colorFromGroup: primary
        - review: 357687d6-211f-4cbf-8c9e-b3cb2224de21
          card_color_group: 5c9075f8-80f9-4482-b041-91cffdfe02be
          colorFromGroup: primary
        - review: b7b5b2d0-2aaa-4b47-9b8d-eb884ac5b0b3
          card_color_group: 5c9075f8-80f9-4482-b041-91cffdfe02be
          colorFromGroup: primary
    styles:
      color_group: 7910a55b-f91e-47da-b36c-a80a4b23865a
  - _bookshop_name: sections/sideBySideStandard
    content:
      sectionId:
      heading:
        _bookshop_name: generic/heading
        content:
          highlightEyebrow: false
          eyebrow: ''
          headline: A Little About Us
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
      entries:
        - _bookshop_name: generic/leftRight
          content:
            heading:
              _bookshop_name: generic/heading
              content:
                highlightEyebrow: false
                eyebrow: ''
                headline: Experience the Art of Hatmaking.
                description: >-
                  At \[\[st.name\]\], we believe a hat is more than an
                  accessory—it's an extension of who you are. As an American Hat
                  Company Certified Reseller and a family-run business for over
                  20 years, we've helped thousands of proud Idahoans find their
                  perfect fit. From classic Western to modern custom designs,
                  every hat in our Nampa showroom embodies quality, tradition,
                  and personalized service.
                buttons:
                  - _bookshop_name: generic/button
                    url: '#'
                    openInNewTab: false
                    text: Meet the Family
                    color_group: primary
                    colorFromGroup: secondary
                    ghostButton: false
                    formSubmit: false
                headingHierarchy: h2
              styles:
                contentAlignment: left
                textAlignment: left
                visualInterest: none
                visualInterestColor: '#000000'
                highContrast: false
                contrastColorGroup:
                contrastAgainst:
                textClassOverride:
            image:
              _bookshop_name: generic/image
              imagePath: /assets/uploads/home/cowboy-riding-watching-sunset.jpg
              imageAlt:
              yAxisPosition:
              imageSizes:
              class:
              imageNumber:
            entryNumber: 0
          styles:
            color_group: primary
            colorFromGroup: background
    styles:
      color_group: primary
      startImageRight: false
      fullWidth: true
  - _bookshop_name: sections/coloredCTA
    content:
      sectionId:
      CallToAction:
        _bookshop_name: generic/heading
        content:
          highlightEyebrow: false
          eyebrow: ''
          headline: Discover Your Perfect Hat
          description: At Idaho Hat Company, we have everything you need for men and women.
          buttons:
            - _bookshop_name: generic/button
              url: '#'
              openInNewTab: false
              text: Explore our collection.
              color_group: primary
              colorFromGroup: background
              ghostButton: false
              formSubmit: false
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
    styles:
      color_group: 7910a55b-f91e-47da-b36c-a80a4b23865a
      card_color_group: primary
      colorFromGroup: primary
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
