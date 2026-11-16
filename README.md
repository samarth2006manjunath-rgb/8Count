# 8Count

A free formation planner for dance teams, built for our college Bollywood team.

**Open it:** https://samarth2006manjunath-rgb.github.io/8Count/

## What it does
- Stage editor with a measured grid, 18 formation templates and alignment tools
- 8-count timeline with animated transitions, synced to your song
- Realistic 3D audience view with lit, rigged human dancers, plus video-to-motion: film a dancer and 8Count turns it into 3D movement on stage (runs on your device; the video is never uploaded)
- "My spot" for every dancer, with a count-by-count cue sheet, and a phone view
- Roster with heights, rehearsal schedule, costumes and props

## Sharing routines
- **Share link:** press **Share** on the Stage tab and send the link. It's a snapshot of that routine.
- **Team file (the official version):** on the Team tab press **Download team file**, then upload `team.json` to this repo. Everyone who opens the site gets it automatically, about a minute after the commit.

Everything you edit is saved in your own browser until you share or publish it.

## Credits
3D dancers use the [Male Base Mesh](https://github.com/BoQsc/Godot-Male-Base-Mesh) by orange-juice-games (CC0, public domain), drawn with [three.js](https://threejs.org) (MIT), both hosted in this repo.

Pose detection uses Google's open-source [MediaPipe Pose Landmarker](https://ai.google.dev/edge/mediapipe/solutions/vision/pose_landmarker) (Apache 2.0), hosted in `mp/`.
