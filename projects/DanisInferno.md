---
layout: post
title: "Dani's Inferno"
---

![thumbnail](\assets\img\projects\DanisInferno\thumbnail.jpg){: .centered-full-width}

// I should add a gif that only shows the powers itself. would be sick if it was on a transparent bg.

| Responsibilities: | Programming, Game Design|
| Period: | 3 days |
| Framework: | Godot 3 |
{: .project-properties-table}


##### Notable features:
- AI steering behaviors
  - I implemented the behaviors from [Reynolds, Craig. (2002). Steering Behaviors For Autonomous Characters.](https://www.red3d.com/cwr/steer/)
		for AI agents
  for this project. A year later, I brought I extended this library to also work for 3D agents.
  - The behavior of agents can be composed from different behaviors e.g. they can try to catch player A
  but flee from player B. The can follow player A, or try to block their way, by predicting where they will go.
  All of these behaviors can be mixed and matched and also packadged into different states to be handled by a statemachine.

I wanted to take this game to gameplay wise riff off of the idea of magic, I thought back a lot to playing a mage in World of Warcraft and in Magicka and wanted to create another way of magic that actually rewards _intelligence_,
the idea was to come up with simple moves that can be chained and launched together to create complex behaviors.

Such as:
- bomb - push - push -> to create a bomb and push it far into the enemies where it explodes.
- teleport - push - teleport => to get into a group of enemies push them into traps and get quickly out again.
- The game was never finished, and there never was any strong level design to fully gauge the potentials of the gameplay.
