---
layout: default
title: Proc Gen
parent: Game Projects
nav_order: 4
---

### An Automated Map Generator for Rhythm Platformer (11/2020) - Solo

Team size:		1

Engine:		Unity

Status:			Finished

Project page: [View it on GitHub](https://github.com/Yuhan-Wu/RhythmPlatformer){: .btn .fs-5 .mb-4 .mb-md-0 }

Introduction:

Using spectral flux algorithm, this beat map generator can analyze any songs selected by player and generates a *beat pattern*. As long as the program can read the beat pattern, any rhythm games can make use of it. The project contains a simple rhythm game that is coded by myself.

Work on:

- Analyze

  Use fast fourier transform in DSP lib to convert the sample data we get from AudioClip to spectrum data. Divide a song into small parts, and calculate the average of each part. Then keep the data that can be used for next step.

- Generate 

  Analyze the pattern of the beat within a period of time, then if necessary, combine multiple beat into one or combine the beat with the blank space and group them together into one obstacle. 

**Gameplay:**

  [![Rhythm](https://img.youtube.com/vi/N59ozf_ln1w/0.jpg)](https://www.youtube.com/watch?v=N59ozf_ln1w)

Citation:

Jesse. “Algorithmic Beat Mapping in Unity: Real-Time Audio Analysis Using the Unity API.” *Giant Scam*, Giant Scam, 16 Feb. 2018, medium.com/giant-scam/algorithmic-beat-mapping-in-unity-intro-d4c2c25d2f27. 