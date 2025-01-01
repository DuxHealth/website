---
title: 'Home'
date: 2024-12-15
type: landing

design:
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: Care when it's most important. Made Possible.
      text: Dux creates real-time healthcare that guides health to take the right path at critical crossroads in life.
      primary_action:
        text: Learn About Our Vision
        url: /about/
        icon: rocket-launch
      secondary_action:
        text: Contact Us
        url: /contact/
      announcement:
        text: "Pioneering the next generation of epilepsy care."
        link:
          text: "Our Approach"
          url: /approach/
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      css_class: "dark"
      background:
        color: "navy"
        image:
          filename: bg-medical-tech.svg
          filters:
            brightness: 0.4
  - block: stats
    content:
      items:
        - statistic: "100% Focused"
          description: |
            On transforming  
            epilepsy care
        - statistic: "Deep Expertise"
          description: |
            AI-driven research  
            powered by clinicians and scientists
        - statistic: "Patient-Centered"
          description: |
            Designed with real-world  
            usability in mind
    design:
      css_class: "bg-gray-100 dark:bg-gray-900"
      spacing:
        padding: ["1rem", 0, "1rem", 0]
  - block: vision
    id: vision
    content:
      title: Our Vision
      text: Harnessing cutting-edge AI and wearable technology to predict and prevent epileptic seizures.
      items:
        - name: Innovative Research
          icon: academic-cap
          description: Groundbreaking approaches in AI, signal processing, and neuroscience.
        - name: Patient-Centric Design
          icon: heart
          description: Solutions that integrate seamlessly into daily life.
        - name: Continuous Improvement
          icon: refresh
          description: Leveraging real-world data to refine and personalize outcomes.
        - name: Global Collaboration
          icon: globe
          description: Partnering with researchers and clinicians worldwide.
    design:
      css_class: "bg-gray-100 dark:bg-gray-900"
  - block: cta-image-paragraph
    id: progress
    content:
      items:
        - title: Driving Progress in Epilepsy Care
          text: Our team is dedicated to advancing AI-powered solutions that improve lives.
          feature_icon: check
          features:
            - "Real-time data analysis"
            - "Collaborative research initiatives"
            - "Focus on patient safety and efficacy"
          image: coffee.jpg
          button:
            text: Explore Our Work
            url: /technology/
        - title: Join Our Journey
          text: Be part of the change. Whether you're a researcher, clinician, or advocate, we’d love to collaborate.
          feature_icon: handshake
          features:
            - "Partner with us on research"
            - "Provide feedback and insights"
            - "Help shape the future of healthcare"
          image: coffee.jpg
          button:
            text: Collaborate With Us
            url: /contact/
    design:
      css_class: "bg-gray-100 dark:bg-gray-900"
  - block: cta-card
    content:
      title: Join Us in Shaping the Future of Healthcare
      text: We’re on a mission to make epilepsy management smarter, safer, and more personalized.
      button:
        text: Get Involved
        url: /get-involved/
    design:
      card:
        css_class: "bg-primary-700"
        css_style: ""
---
