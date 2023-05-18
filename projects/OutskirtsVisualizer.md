---
layout: post
title: 'Outskirts Visualizer'
---

### A visual "instrument" for the debut concert of "Outskirts"

![OutskirtsVisualizer](/assets/img/projects/OutskirtsVisualizer/thumbnail.jpg){: .rounded-edges}

| Responsibilities: | Programming, Tools, Shader|
| Period: | 1 week |
| Framework: | Godot 4 |
{: .project-properties-table}

Notable features:
- Midi Controller Responsive:
	- Any property in the project can be controlled through midi knobs and faders
		- **Animations** can be started/stopped through midi/knobs
		- Cameras can be controlled
		- Hue/Saturation/Value shifting through knobs
	- Custom Virtual Display of current Controller Mapping
- Fracturing Simulation using RigidBodies
- Custom node that makes properties audio reactive:
	- Define frequency range to pick up from microphone,
	- define property value range,
	- set interpolation speed
	= => e.g. wave displacement reacts to the music's bass track
- Shaders:
	- Screen wobble shader
	- Displacement Shader
	- Turbulence Particles changing color based on lifetime



Also checkout Outskirts Music:

<iframe style="border-radius:12px" src="https://open.spotify.com/embed/artist/6AtmGDix7ziaavtOWpfQZI?utm_source=generator" width="100%" height="352" frameBorder="0" allowfullscreen="" allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture" loading="lazy"></iframe>