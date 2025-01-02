---
title: "Home"
date: 2024-12-15
type: landing

design:
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: |
        Care when it's most important. 
        Made Possible.
      text: Dux creates real-time healthcare that guides health to take the right path at critical crossroads in life.
      primary_action:
        text: Learn About Our Vision
        url: /#vision
        icon: rocket-launch
      secondary_action:
        text: Send Us a message
        url: /#contact
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      css_class: "dark"
      background:
        color: "zinc"
        image:
          filename: endless-constellation.svg
          filters:
            brightness: 0.4
  - block: stats
    content:
      items:
        - statistic: "Peace of Mind"
          description: |
            Giveing individuals control 
            over their lives
        - statistic: "Deep Expertise"
          description: |
            AI-driven research  
            powered by clinicians and scientists
        - statistic: "Patient-Centered"
          description: |
            Designed with real-world  
            usability in mind
    design:
      css_class: "bg-purple-900"
      spacing:
        padding: ["1rem", 0, "1rem", 0]
  - block: features
    id: vision
    content:
      title: Our Vision
      text: |
        At Dux Health, we recognize that the transition from health to illness is often shaped by a few critical events or periods—moments like strokes, heart attacks, or seizures that profoundly impact a person’s health journey. While modern medicine is adept at managing the consequences of these events, it often falls short in being present at the pivotal moments when timely intervention could change everything. These life-altering events frequently occur outside healthcare settings, leaving individuals without immediate access to the care they urgently need. <br><br>Our vision is to transform healthcare by creating real-time systems that provide care precisely when it matters most. Through advanced AI, wearable technologies, and personalized medicine, Dux ensures that health takes the right path at life’s critical crossroads.<br><br>Care when it’s most important. Made possible.
      items:
        - name: Innovative Research
          icon: academic-cap
          description: Pioneering advancements in AI, signal processing, and neuroscience to deliver real-time interventions at life’s critical moments.
        - name: Patient-Centric Design
          icon: heart
          description: Developing solutions that seamlessly integrate into daily life, empowering individuals with timely care when it matters most.
        - name: Continuous Improvement
          icon: wrench-screwdriver
          description: Harnessing real-world data to refine, personalize, and enhance outcomes, ensuring health takes the right path.
        - name: Proactive Care
          icon: eye
          description: Shifting healthcare from reactive to proactive by addressing critical moments to prevent crises before they occur.
        - name: Real-Time Insights
          icon: clock
          description: Delivering actionable, real-time health data that empowers patients and healthcare providers to make life-saving decisions.
        - name: Global Collaboration
          icon: globe-asia-australia
          description: Partnering with researchers and clinicians worldwide to revolutionize healthcare through real-time, life-changing solutions.
    design:
      css_class: "bg-purple-900"
  - block: cta-image-paragraph
    id: progress
    content:
      items:
        - title: The Largest Seizure Prediction Experiment Ever Conducted
          text: We are embarking on an unprecedented clinical trial to validate real-world seizure prediction.
          feature_icon: check
          features:
            - "Hundreds of Participants<br>Monitoring individuals with epilepsy over several months to gather extensive, real-world data."
            - "Sleek, Wearable Technology<br>Using comfortable, state-of-the-art wearables that seamlessly integrate into daily life."
            - Real-World Impact<br>Demonstrating that high-performance seizure prediction is achievable outside clinical settings, empowering patients to live with confidence and control.
          image: muse2.jpeg
          button:
            text: Explore Our Work
            url: https://forms.gle/P7Am9qAN1w3jQWjW7
        - title: Join Our Journey
          text: Be part of the change. Whether you're a researcher, clinician, or advocate, we’d love to collaborate.
          feature_icon: hand-thumb-up
          features:
            - "Partner with us on research"
            - "Provide feedback and insights"
            - "Help shape the future of healthcare"
          image: friends.jpeg
          button:
            text: Collaborate With Us
            url: https://forms.gle/P7Am9qAN1w3jQWjW7
    design:
      css_class: "bg-purple-900"
  - block: cta-card
    id: contact
    content:
      title: Join Us in Shaping the Future of Healthcare
      text: We’re on a mission to make epilepsy management smarter, safer, and more personalized.
      button:
        text: Get Involved
        url: https://forms.gle/P7Am9qAN1w3jQWjW7
    design:
      css_class: "bg-purple-900"
      card:
        css_class: "bg-primary-700"
        css_style: ""

  - block: contact-details
    id: contact-details
    content:
      title: Contact Us
      subtitle: We'd love to hear from you!
      email: community@dux-health.com
    design:
      css_class: "bg-blue-500 p-8 rounded-lg"
---
