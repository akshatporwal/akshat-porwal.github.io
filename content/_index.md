---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/Akshat_Porwal.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: '📚 My Research'
      subtitle: ''
      text: |-
        Under the guidance of Prof. Ceren Budak, I am analyzing subscription and donation behaviors across over 5,000 news platforms to uncover patterns in user engagement and financial trends. This research involves developing data strategies and leveraging statistical and machine learning techniques to provide actionable insights into the evolving digital media landscape.

        In a separate project, I worked with Prof. Budak to design and deploy a real-time classifier for identifying local election-related articles. This system integrates an optimized BERT-based model with XGBoost using TF-IDF and numeric features. By implementing paragraph-level aggregation, I enhanced the classifier's accuracy and facilitated its seamless integration into newsroom workflows through a production handoff process.

        During the Summer of 2023, I collaborated with Prof. Dallas Card to perform Bayesian analysis on over 1,000 graduate student publications. This research aimed to identify trends in computer science academic productivity, providing insights into the changing dynamics of scholarly contributions in the field. 
    design:
      columns: '2'
---
