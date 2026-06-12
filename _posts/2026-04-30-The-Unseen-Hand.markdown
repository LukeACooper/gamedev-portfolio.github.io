---
layout: default
modal-id: 2
date: 2014-07-16
img: CCTP_Hexes.png
alt: image-alt
client: Comprehensive Creative Technologies Project (Final Year Dissertation Project)
description: "This was my final year dissertation project; what started as a speculative level design project, slowly evolved into a study into the applicability of P.A.Smith's Lostness Metric: An equation which was designed to calculate the efficiency of hyperlink-based web page browsing. My aim became a means of exploring the potential usage within a real-time 3D open-world game level environment."
accordions:
    - title: "Lostness"
      content: "This project involved harnessing the 'lostness metric', as a means of detecting when a player is becoming lost in a 3D open-world environment. To briefly explain the lostness metric in the context of my project, the system would check for the minimum required tiles the player needed to travel to, in order to reach their objective. Then, it tracks how many unique tiles, and revisits to previous tiles, to output a number, which in a post-game setting would result in a number value between 0.0 and 1.0. Attempting to use this in real-time uncovered an issue where the output values in real-time would often exceed this value, which caused a pivot in the methodolgy, and started an investigation on Unreal Engine State Trees, though this was, unfortunately out of scope due to time constraints."
      image: LostnessEqn.png
    - title: "Environment Query System"
      content: "Using the Environment Query System, I was able to trigger an actor to spawn in the best possible location, closest to an objective, whilst remaining within the player's camera view. This system would be used as a template for the diegetic guidance cue system proposed in my poster presentation"
      image: CCTP_Poster.png
      image2: EQS.png
    - title: "HISM-Based Hexagonal Tiles"
      content: "I created a simple hexagonal mesh in Maya and UV mapped them to apply materials to the top face for debugging purposes in-engine. It can be tiled, which I used a mathematical blueprint to translate the hexagon tiles to fit together without any gaps or overlap. To ensure the system remained optimised, I used the 'HISM' (Hierarchical Instanced Static Mesh) system in unreal engine, which reduces the overall triangle count, and therefore reducing memory usage overall."

---
