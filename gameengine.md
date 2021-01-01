---
layout: default
title: Game Engine Projects
nav_order: 3
description: "Game engine"
---

### Game Engine v1.0 (09/2019 - 05/2020) - Solo

Team size:		1

Status:			Finished

Project page: [View it on GitHub](https://github.com/Yuhan-Wu/MyGameEngine)

Introduction:

A 2d game engine that enables developers to build a game using interfaces provided by the engine.

Features:

- Configure characters with JSON files.
- Various controllers (AI and player input) and components.
- Simulate physics.
- Box collision.
- Allocate, free and coalesce memory using descriptors.
- Smart pointers and weak pointers.

The example game is a bullethell-ish game. W,A,S,D to move. The longer you hold W,A,S,D, the faster you are. Q to quit. Player can rebound off the wall to escape from enemies.

### Game Engine v2.0 (09/2020 - 12/2020) - Solo

Team size:		1

Status:			Finished

Project page: [View it on GitHub](https://github.com/Yuhan-Wu/MyGameEngine2)

Introduction:

A more advanced game engine that supports both OpenGL(32 bits) and Direct3D(64 bits) with a Maya exporter. XAudio2 library is also implemented and allows you to add music to your game. The game engine also includes several builders to convert lua files to binary files to increase loading speed when game starts running.

If you want to know more about the engine, the full development log is here: [Blog Page](https://iriswuyuhan.wixsite.com/yuhan-wu/blog/categories/development)

**Example game:**

Inspired by the arcade game Raiden, Fake Raiden is also a shoot 'em up game, in which players control a rocket to avoid enemies' attack and try to shoot down all enemies on screen. Arrow keys to move and space key to shoot.

  ![Engine2](https://yuhan-wu.github.io/Pics/Engine2/engine2.gif)