---
layout: default
modal-id: 2
date: 2014-07-16
img: game.png
alt: image-alt
category: Comprehensive Creative Technologies Project (Final Year Dissertation Project)
description: Use this area of the page to describe your project. Lorem ipsum dolor sit amet, consectetur adipisicing elit. Mollitia neque assumenda ipsam nihil, molestias magnam, recusandae quos quis inventore quisquam velit asperiores, vitae? Reprehenderit soluta, eos quod consequuntur itaque. Nam.
accordions:
    - title: "Lostness"
      content: "This project involved harnessing the 'lostness metric', as a means of detecting when a player is becoming lost in a 3D open-world environment. To briefly explain the lostness metric in the context of my project, the system would check for the minimum required tiles the player needed to travel to, in order to reach their objective. Then, it tracks how many unique tiles, and revisits to previous tiles, to output a number, which in a post-game setting would result in a number value between 0.0 and 1.0. Attempting to use this in real-time uncovered an issue where the output values in real-time would often exceed this value, which caused a pivot in the methodolgy, and started an investigation on Unreal Engine State Trees, though this was, unfortunately out of scope due to time constraints."
    - title: "Environment Query System"
      content: "Using the Environment Query System, I was able to trigger an actor to spawn in the best possible location, closest to an objective, whilst remaining within the player's camera view. This system would be used as a template for the diegetic guidance cue system proposed in my poster presentation (poster below!)"
      image: CCTP_Poster.png
    - title: "Real-Time lostness tracking"
      content: "Translated the 2D lostness metric into a 3D environment, tracking player lostness during gameplay, with the help of state trees "

---
