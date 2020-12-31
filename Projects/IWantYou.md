---
layout: default
title: I Want You
parent: Game Projects
nav_order: 2
---

### I Want You (01/2020 - 07/2020) - Lead Engineer

Team size:		10

Engine:		Unreal & VR

Status:			Finished

Introduction:

I Want You is a VR psychological horror game, in which player operates a physical wheelchair to navigate through a hospital which illustrates the issues with the VA system.

Work on:

- Alt-ctrl

  Uses the delta rotation between two vive trackers to compute wheelchair movement. Character movements are exactly the same as real-life wheelchair movements, such as slow start, turning around and the influence of friction.

- AI

  Three types of AI based on line trace and shape trace:
  
  - Triggered when player camera sees the monster. Chases player until chair and camera forward vector are not facing it. Immediately kills player if the View Meter is 7 or Viewing Time is 7s. 
  
  - After a glitch effect, crawling monsters are spawned in and converge on the player's location with no escape.
  
  - Jump scare triggered when player stares at a location for too long or leaves the room.

- UI
  
  UI that is compatible with VR headset. Shows typewriter style prompts of configuring left and right vive tracker in VR headset.
  
    

**Trailer&Gameplay:**

  [![I Want You Trailer](https://img.youtube.com/vi/h7urEWaOKbk/0.jpg)](https://www.youtube.com/watch?v=h7urEWaOKbk)