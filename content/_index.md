---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Overview
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: lenslabintro
  - block: markdown
    id: moreaboutus
    content:
      title: More about us
      subtitle: ''
      text: We work with different programming environments, including [Gymnasium](https://gymnasium.farama.org/), python packages for machine learning, open source communication stacks such as [srsRAN](https://www.srslte.com/), and [OpenFlow](https://www.opennetworking.org/) for software defined networking (SDN).Hardware support includes GPU workstations from [Lambda Labs](https://lambdalabs.com/), Software Defined Radios (SDR) from [National Instruments](https://www.ni.com/en-us/innovations/white-papers/11/what-is-ni-usrp-hardware-.html) in both sub-six and mm-wave bands, a variety of robots such as [Jackal UGVs](https://clearpathrobotics.com/jackal-small-unmanned-ground-vehicle/), [Turtlebots](https://www.turtlebot.com/) and [Amazon DeepRacers](https://aws.amazon.com/deepracer/) and assorted Android-based smart devices.We are also supported in conducting real-world field experiments by the [Bush Combat Development Complex](https://bcdc.tamus.edu/) located at a former Air Force base located about ten miles away from the main campus.Participants are encouraged to act as a community of experts and talk about their experiences with one another. Prototyping often poses many technical challenges. Getting involved at the LENS lab entails being exposed to the frustrations and the rewards associated with open-ended engineering problems. <br> <br> {{< youtube auUnazOFeeE >}} <br>  The lab is supported through the sponsorship of several organizations including Department of Electrical and Computer Engineering at Texas A&M University, National Instruments, Google, the National Science Foundation, and The US Army Futures Command, among others. 
  - block: features
    content: 
      title: Courses Taught by Faculty
      text : <br> <br>
      items:
        - name: ECEN 424 Fundamentals of Networking 
        - name: ECEN 489 Artificial Intelligence <br> <br>
        - name: ECEN 489 Mobile Applications with Android
        - name: ECEN 743 Reinforcement Learning
        - name: ECEN 750 Design and Analysis of Communication Networks
        - name: ECEN 756 Game Theory
  - block: markdown
    id: news
    content:
      title: News
      subtitle: 
      text :  • [09/2023] TAMU News article about our new NSF grant for the project “Combining Deep Reinforcement Learning Control with Novel Vertical Flight Concepts for Robust Ship based Operation” [Link](https://engineering.tamu.edu/news/2023/08/automating-aircraft-ship-landings-at-rough-seas.html) <br>
        • [09/2023] TAMU News article about our new ONR grant for the project “EdgeRIC- Empowering Real-time Intelligent Control and Optimization for NextG Cellular Radio Access Networks” [Link](https://engineering.tamu.edu/news/2023/09/engineering-researchers-to-study-wireless-communication-and-machine-learning-with-nsf-grant.html) <br>
        • [08/2023] Kishan Panaganti has graduated with a PhD dissertation on “Robust Reinforcement Learning- Theory and Algorithms”! He will join as a Postdoc in Caltech. <br>
        • [08/2023] Archana Bura has graduated with a PhD dissertation on “Constrained Reinforcement Learning for Wireless Networks”! She will join as a Postdoc in University of California, San Diego (UCSD). <br>
        • [08/2023] Desik Rengarajan has graduated with a PhD dissertation on “Enhancing Reinforcement Learning using Data and Structure”! He will join as a Research Scientist in the HP Labs. <br>
  - block: collection
    content:
      title: Recent Research
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: True
    # design:
    #   columns: '2'
    #   view: citation
  - block: markdown
    id: group
    content:
      title: Group
      subtitle: List of Students
      text: • Zaiyan Xu [[Webpage](https://www.zaiyanxu.com/)]  (Fall 2020 - Present) <br> • Sapana Chaudhary [[Webpage](https://sapanachaudhary.github.io/)] (Fall 2019 - Present) <br> • Kishan Panaganti [[Webpage](https://sapanachaudhary.github.io/)] (Fall 2018 - Summer 2023) <br> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Next position - Postdoc, Caltech. <br> • Archana Bura [[Webpage](https://sites.google.com/tamu.edu/archanabura)]  (Fall 2017 - Summer 2023) . (co-advised with Prof. Srinivas Shakkottai) <br> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Next position - Postdoc, UCSD. <br> • Desik Rengarajan [[Webpage](https://sites.google.com/view/desik-rengarajan/home)]  (Fall 2017 - Summer 2023). (co-advised with Prof. Srinivas Shakkottai). <br> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Next position -Research Scientist, HP Labs.

  - block: markdown
    id: group
    content:
      title: Lab Gallery
      subtitle: Sneak peek into the lab
      text: _ {{< gallery album="demo" >}}
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: 
      # Contact (add or remove contact options as necessary)
      email: sshakkot@tamu.edu , dileep.kalathil@tamu.edu
      phone: 1-979-458-0094
      address:
        street: 188 Bizzell St , Wisenbaker Engineering Building (WEB) - 002
        city: College Station
        region: TX
        postcode: '77840'
        country: United States
        country_code: US
      
      
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
    design:
      columns: '2'
  
  # - block: collection
  #   id: featured
  #   content:
  #     title: Featured Publications
  #     filters:
  #       folders:
  #         - publication
  #       featured_only: true
  #   design:
  #     columns: '2'
  #     view: card

      # <br> <br> **Aggie Deep Racers** <br>  This is an initiative specifically aimed at applied machine learning in a # # # robotics context using the [Amazon DeepRacer](https://aws.amazon.com/deepracer/) platform. <br> <br> ![Lens robot # # image](lensrobotimage.jpg)
  # office_hours:
  #       - 'Monday 10:00 to 13:00'
  #       - 'Wednesday 09:00 to 10:00'
---
