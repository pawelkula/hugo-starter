---
_schema: default
title: Txt Module Examples
seo:
  page_description: >-
    Comprehensive examples showcasing all the features and configurations of the text-block component,
    including different headline sizes, CTAs, tags, and layout options.
  canonical_url: /text-block-examples/
  featured_image: /images/blog/featured-image-1.jpg
  featured_image_alt: Text block component examples
  author_twitter_handle:
  open_graph_type: website
  no_index: false
content_blocks:
  # Example 1: XL Headline with CTAs
  - _bookshop_name: txt-module
    background_color: "#085263"
    headline:
      enabled: true
      text: "XL HEADLINE"
      size: "XL"
      alignment: "left"
      color: "#fff"
    sub_headline:
      enabled: true
      text: "Optional Sub Headline"
      alignment: "left"
      color: "#fff"
    content:
      enabled: true
      text: "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet."
      columns: 1
      color: "#fff"
    layout:
      disable_bottom_padding: false
      max_width: "var(--pageContainer)"
    action_type: "ctas"
    ctas:
      - text: "Long Button Label"
        type: "primary"
        url: "#"
        target: "_self"
        overlay_id: ""
      - text: "Button"
        type: "secondary"
        url: "#"
        target: "_self"
        overlay_id: ""
      - text: "Button"
        type: "secondary"
        url: "#"
        target: "_self"
        overlay_id: ""
      - text: "Button"
        type: "secondary"
        url: "#"
        target: "_self"
        overlay_id: ""

  # Example 2: L Headline with Tags
  - _bookshop_name: txt-module
    background_color: "#085263"
    headline:
      enabled: true
      text: "HEADLINE HEADLINE"
      size: "L"
      alignment: "left"
      color: "#fff"
    sub_headline:
      enabled: true
      text: "Optional Sub Headline"
      alignment: "left"
      color: "#fff"
    content:
      enabled: true
      text: "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet."
      columns: 2
      color: "#fff"
    layout:
      disable_bottom_padding: false
      max_width: "var(--pageContainer)"
    action_type: "tags"
    tags:
      - text: "Tag 01"
        color: "#d3ba00"
        text_color: "#085263"
      - text: "Tag 02"
        color: "#6f9c75"
        text_color: "#fff"

  # Example 3: No Bottom Padding
  - _bookshop_name: txt-module
    background_color: "#085263"
    headline:
      enabled: true
      text: "NO BOTTOM PADDING"
      size: "L"
      alignment: "left"
      color: "#fff"
    sub_headline:
      enabled: true
      text: "Optional Sub Headline"
      alignment: "left"
      color: "#fff"
    content:
      enabled: true
      text: "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet."
      columns: 1
      color: "#fff"
    layout:
      disable_bottom_padding: true
      max_width: "var(--pageContainer)"
    action_type: "none"

  # Example 4: Content Only (Single Column)
  - _bookshop_name: txt-module
    background_color: "#fff"
    headline:
      enabled: false
    sub_headline:
      enabled: false
    content:
      enabled: true
      text: "**Single Column Content:** This example shows content-only layout with a single column. Perfect for longer text sections, articles, or when you need maximum readability. The content can include **markdown formatting** like bold text, *italic text*, and even links."
      columns: 1
      color: "#085263"
    layout:
      disable_bottom_padding: false
      max_width: "var(--pageContainer)"
    action_type: "none"

  # Example 5: Mixed CTA Types
  - _bookshop_name: txt-module
    headline:
      enabled: true
      text: "MIXED CTA TYPES"
      size: "L"
      alignment: "center"
    sub_headline:
      enabled: true
      text: "Different button and link styles"
      alignment: "center"
    content:
      enabled: true
      text: "This example showcases different types of call-to-action elements: primary buttons, secondary buttons, text links, and anchor links. Each serves a different purpose in your content hierarchy."
      columns: 1
      color: "#085263"
    layout:
      disable_bottom_padding: false
      max_width: "var(--pageContainer)"
    action_type: "ctas"
    ctas:
      - text: "Primary Button"
        type: "primary"
        url: "#"
        target: "_self"
        overlay_id: ""
      - text: "Secondary Button"
        type: "secondary"
        url: "#"
        target: "_self"
        overlay_id: ""
      - text: "Text Link"
        type: "link"
        url: "#"
        target: "_blank"
        overlay_id: ""
      - text: "Anchor Link"
        type: "anchor"
        url: "#section-top"
        target: "_self"
        overlay_id: ""

  # Example 6: Colorful Tags
  - _bookshop_name: txt-module
    background_color: "#fff"
    headline:
      enabled: true
      text: "COLORFUL TAGS"
      size: "L"
      alignment: "center"
      color: "#085263"
    sub_headline:
      enabled: true
      text: "Various tag colors from the brand palette"
      alignment: "center"
      color: "#085263"
    content:
      enabled: true
      text: "Tags can use any color from your brand palette. They're perfect for categorization, skills, technologies, or any other labeling needs."
      columns: 1
      color: "#085263"
    layout:
      disable_bottom_padding: false
      max_width: "var(--pageContainer)"
    action_type: "tags"
    tags:
      - text: "Yellow Tag"
        color: "#d3ba00"
        text_color: "#085263"
      - text: "Green Tag"
        color: "#6f9c75"
        text_color: "#fff"
      - text: "Coral Tag"
        color: "#ff8383"
        text_color: "#085263"
      - text: "Blue Tag"
        color: "#01ebf4"
        text_color: "#085263"

  # Example 7: Minimal Content Block
  - _bookshop_name: txt-module
    background_color: "#085263"
    headline:
      enabled: true
      text: "MINIMAL SETUP"
      size: "L"
      alignment: "center"
      color: "#fff"
    sub_headline:
      enabled: false
    content:
      enabled: true
      text: "Sometimes less is more. This text block shows a minimal configuration with just a headline and single-column content."
      columns: 1
      color: "#fff"
    layout:
      disable_bottom_padding: false
      max_width: "var(--pageContainer)"
    action_type: "none"

  # Example 8: Two Column Feature Layout
  - _bookshop_name: txt-module
    background_color: "#fff"
    headline:
      enabled: true
      text: "TWO COLUMN LAYOUT"
      size: "L"
      alignment: "left"
      color: "#085263"
    sub_headline:
      enabled: true
      text: "Perfect for side-by-side content"
      alignment: "left"
      color: "#085263"
    content:
      enabled: true
      text: "**Fast Performance:** Built with Hugo static site generator for lightning-fast load times and optimal user experience.\n\n**Easy Management:** Content editing made simple with CloudCannon's intuitive visual interface and component-based editing."
      columns: 2
      color: "#085263"
    layout:
      disable_bottom_padding: false
      max_width: "var(--pageContainer)"
    action_type: "ctas"
    ctas:
      - text: "Learn More"
        type: "primary"
        url: "#"
        target: "_self"
        overlay_id: ""

  # Documentation Section
  - _bookshop_name: txt-module
    background_color: "#cedde0"
    headline:
      enabled: true
      text: "COMPONENT DOCUMENTATION"
      size: "XL"
      alignment: "center"
      color: "#085263"
    sub_headline:
      enabled: true
      text: "Complete feature overview and usage guide"
      alignment: "center"
      color: "#085263"
    content:
      enabled: true
      text: |
        ## Features

        ### ✅ All Parts Optional
        - Headlines (L or XL size)
        - Sub headlines
        - Content with 1-2 column layouts
        - Call-to-action buttons or tags

        ### 🎨 Headline Options
        - **Size L**: Standard headline using FSL font size
        - **Size XL**: Large headline using FSXL font size
        - **Alignment**: Left, center, or right alignment
        - **Colors**: Any CSS variable from your brand palette

        ### 🔗 CTA Types (Up to 4)
        - **Primary Button**: Main call-to-action with primary styling
        - **Secondary Button**: Alternative action with secondary styling
        - **Text Link**: Simple underlined link
        - **Anchor Link**: Smooth scroll to page sections
        - **Overlay Trigger**: Opens modal/overlay (requires custom JavaScript)

        ### 🏷️ Tags (Up to 4)
        - Customizable background and text colors
        - Rounded pill design
        - Perfect for categories, skills, or labels

        ### 📱 Responsive Behavior
        - **Mobile**: 2-column layouts automatically collapse to single column
        - **Desktop**: Choose between 1 or 2 column layouts

        ### 🎛️ Layout Options
        - Standard section padding (top and bottom)
        - Option to disable bottom padding for stacking
        - Configurable maximum width
      columns: 1
      color: "#085263"
    layout:
      disable_bottom_padding: false
      max_width: "var(--pageContainer)"
---
