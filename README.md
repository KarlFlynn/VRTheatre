# VRTheatre — Shadow Theatre

A WebXR illusion experience for the Meta Quest browser (also works in a normal desktop browser).

Out front, a spinning object is projected flat onto a night-sky screen as glowing white, blue and red "stars". With no depth cues, your brain can't tell which way it's turning — imagine looking down on it, then up, and watch it flip. Backstage you can walk or orbit around the real 3D object, look from above or below, and even jump inside it.

## Open it

- **GitHub Pages:** https://karlflynn.github.io/VRTheatre/ (once Pages is enabled for this repo)
- Open the page in the Quest browser and press **Enter VR**.

## Features (v14)

- 9 ambiguous shapes: dot cylinder, wire cube, dot sphere, dot torus, double helix, carousel, pyramid, hex prism, icosahedron
- Sliders: **Lamp** angle, **Turn** by hand, **Tilt** the spin axis, **Orbit** and **Height** backstage
- **Reveal** the object through the screen, **Reverse** spin, 5 speeds (starts on Very slow), Pause
- Backstage: **Auto orbit**, plus hotspots to **jump inside** the object and **step back out**
- Panels you can grab and move with the grip button; **Exit VR** button

## VR controls

| Control | Action |
|---|---|
| Trigger | Press buttons, drag sliders, use hotspots |
| Grip | Grab and move a panel |
| Left stick | Move |
| Right stick | Snap turn |
| A / X | Jump between front of house and backstage |

Desktop: drag to look, WASD / arrow keys to move, click the panels.

## Versions

Each version is a commit with a matching tag (`v5` … `v14`). To view an old one, open the tag on GitHub, or run `git checkout v8`.

| Tag | Change |
|---|---|
| v5 | Ten shapes with a shape-picker grid |
| v6 | Lamp, Turn and Tilt sliders |
| v7 | Ballerina removed |
| v8 | Backstage Orbit, Height, Auto orbit; panel travels with you |
| v9 | Space theme: dark screen, white/blue/red stars |
| v10 | Slower speeds, Exit VR button |
| v11 | Jump-inside / step-out hotspots |
| v12 | Smaller hotspot orbs at the base |
| v13 | Grab-and-move panels |
| v14 | Very slow default speed; panel resets on jump in/out |

Built with [three.js](https://threejs.org/) (loaded from the jsDelivr CDN).
