---
# Leave the homepage title empty to use the site title
title:
date: 2026-10-02
type: landing

sections:
  - block: hero
    content:
      title: 'Welcome to the ESA Lab'
      text: 'Developing next-generation data center technologies.'
      cta:
        label: View Our Research
        url: 'publication'
        icon: arrow-down
        icon_pack: fas
    design:
      background:
        video:
          filename: data_centre.mp4
        text_color_light: true
        filters:
          brightness: 0.4
      spacing:
        # This controls how tall the video section is (vh = viewport height)
        padding: ["30vh", "0", "30vh", "0"]

  # 1. GOALS AND BACKGROUND
  - block: hero
    content:
      title: |
        Data Center Project
      image:
        filename: welcome.jpg # You can replace this image in assets/media/ later
      text: |
        <br>
        This is a Swiss National Science Foundation (SNSF) funded initiative exploring next-generation data center architectures.
        
        **Our Background & Goals:**
        Data centers consume a massive amount of global energy. This project investigates new cooling methodologies, optimizes server workloads, and aims to provide sustainable frameworks for the tech industry over the next three years.

  # 2. THE TEAM
  - block: people
    content:
      title: The Team
      user_groups:
        - Principal Investigators
        - Researchers
        - Grad Students
        - Temps
    design:
      show_interests: true
      show_role: true
      show_social: true

  # 3. OUTCOMES
  - block: markdown
    content:
      title: Project Outcomes
      subtitle: Open Source Tools & Datasets
      text: |
        As part of our commitment to Open Research Data (ORD), all our project outcomes will be published here:
        
        * **Dataset:** [Thermal metrics from 100 servers (Zenodo)](#)
        * **Software:** [Open-source workload scheduler (GitHub)](#)
        * **Whitepaper:** [Industry guidelines for green data centers](#)
    design:
      columns: '1'

  # 4. LATEST PUBLICATIONS
  - block: collection
    content:
      title: Latest Publications
      text: ""
      count: 5
      filters:
        folders:
          - publication
    design:
      view: citation # This makes them look like nicely formatted academic citations
      columns: '1'
---