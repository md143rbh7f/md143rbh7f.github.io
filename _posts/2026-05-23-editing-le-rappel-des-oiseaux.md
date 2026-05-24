---
layout: post
title: Editing "Le Rappel des Oiseaux"
date: 2026-05-23 23:25:00 -0700
hidden: true
assets: "/assets/images/2026-05-23"
---

Work-in-progress Youtube link: <https://youtu.be/NuYbWfls5ZA>

Cinematography class project, shot late 2025. Mostly 16mm (Kodak 500T on Bolex), which produced some very nice footage, but we ran out of film and had to re-shoot some parts digitally (Black Magic Pocket Cinema, original model, mid 2010s). This introduced some technical difficulties, which is one of the reasons why it's taken so long to edit; the other reasons being life, and work, and so on.

On a positive note, dealing with uncommon technical challenges has been very educational, so I thought I'd write down some observations, mostly intended for classmates but which may also be useful to others. Things become interesting when they break!

## Pre-Shoot
Pre-shoot was extremely helpful for figuring out framing, blocking, lighting, and so on. It also helped that the BMPCC (used during pre-shoot and re-shoot) has a similar sensor size to the Bolex, so the same lens, aperture, and ISO settings should produce roughly the same depth of field. 400 ISO digital roughly matches 500 ISO film with the Bolex prism, etc.

The main mistake, obviously, was not rehearsing enough to accurately budget the required amount of film. (During the last 16mm project, *[Roshambo](https://youtu.be/eGRpAc3bW6g)*, I got lucky by simply guessing the right shot lengths, which made me overconfident.)

## Exposure
The images in this post have very minimal colour correction, only a basic colour space transformation from (Cineon or Black Magic) log/gamma to Rec. 709 and for the digital images, some artificial noise to simulate grain.

| film | digital |
| :---: | :---: |
| <img src="{{page.assets}}/volha-16mm.png" width="480px"/> | <img src="{{page.assets}}/volha-digital.jpg" width="480px"/> |

The digital looks quite overexposed, even after trying to match the camera and lighting. I believe this is for a few different reasons:
* Film and digital have different response curves. This matches the conventional wisdom that (negative) film is more forgiving of overexposure.
* Cineon gamma may not correspond exactly to Black Magic gamma.

## Framing
Another issue was framing. 16mm film is 4:3, but the BMPCC shoots 16:9. As expected, the images look very awkward when reframing from one to the other. After trying a few different crops, I found 3:2 was a good enough compromise. This is another problem that should have been solved beforehand; I completely forgot to frame for 4:3 when shooting digital.

| 4:3 | 3:2 | 16:9 |
| :---: | :---: | :---: |
| <img src="{{page.assets}}/exterior-4-3.png" width="320px"/> | <img src="{{page.assets}}/exterior-3-2.jpg" width="320px"/> | <img src="{{page.assets}}/exterior-16-9.png" width="320px"/> |
| <img src="{{page.assets}}/party-4-3.png" width="320px"/> | <img src="{{page.assets}}/party-3-2.jpg" width="320px"/> | <img src="{{page.assets}}/party-16-9.png" width="320px"/> |
| <img src="{{page.assets}}/gavi-4-3.png" width="320px"/> | <img src="{{page.assets}}/gavi-3-2.png" width="320px"/> | <img src="{{page.assets}}/gavi-16-9.png" width="320px"/> |
| <img src="{{page.assets}}/matt-4-3.png" width="320px"/> | <img src="{{page.assets}}/matt-3-2.png" width="320px"/> | <img src="{{page.assets}}/matt-16-9.png" width="320px"/> |
| <img src="{{page.assets}}/bullet-4-3.png" width="320px"/> | <img src="{{page.assets}}/bullet-3-2.png" width="320px"/> | <img src="{{page.assets}}/bullet-16-9.png" width="320px"/> |

## Sound Design
There are a lot of layers, probably enough to merit its own blog post. Currently I have 12 tracks with 6 buses, and I still need to add more.

<div style="text-align:center">
<img src="{{page.assets}}/sound-edit.png" width="800px"/>
</div>

## Bonus Footage
YouTube Link: <https://youtu.be/hYMii09HuQ4>

| | |
| :---: | :---: |
| <img src="{{page.assets}}/unused-0.jpg" width="480px"/> | <img src="{{page.assets}}/unused-1.jpg" width="480px"/> |
