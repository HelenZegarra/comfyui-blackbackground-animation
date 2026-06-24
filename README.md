
# Pastel Artwork Animation Workflow (WIP)

A ComfyUI workflow for transforming handmade pastel paintings and personal artwork into animated vertical videos.

This workflow is designed to preserve the original artistic style of traditional media while expanding static illustrations into motion. It uses image expansion, scene extension, and AI-driven animation techniques to create immersive vertical video content from hand-painted artwork.

> ⚠️ Work in Progress (WIP)
>
> This workflow is currently under active development and experimentation.

---

## Overview

The goal of this workflow is to:

- Animate handmade pastel artwork and paintings
- Expand original compositions beyond the painted canvas
- Generate vertical video formats suitable for social media and digital storytelling
- Preserve the texture, color palette, and artistic characteristics of traditional media
- Create subtle environmental motion and visual depth from static artwork

---

## Workflow Stack

### Models

- **WAN 2.2**
  - Used for image-to-video animation generation
  - Creates motion and temporal consistency from expanded artwork

- **FLUX.1**
  - Used for image filling and outpainting
  - Extends artwork beyond its original boundaries while maintaining style consistency

### Pipeline

1. Import original pastel artwork
2. Expand composition using FLUX.1 fill/outpainting
3. Generate additional visual context around the artwork
4. Animate the expanded image using WAN 2.2
5. Export as a vertical video sequence

---

## Use Cases

- Animated art portfolios
- Social media reels and shorts
- Digital exhibitions
- Storytelling and visual narratives
- Experimental AI-assisted animation workflows

---

## Current Limitations

The workflow is still being refined and several areas remain under development:

- Scene-to-scene consistency
- Long-form narrative generation
- Landscape and persistence across shots
- Camera motion control
- Temporal stability between generated sequences

---

## Future Development

The next major milestone is building a more robust scene-generation system capable of:

- Defining consistent scenes across multiple shots
- Maintaining visual continuity throughout an animation sequence
- Improving subject consistency
- Creating repeatable storytelling workflows
- Supporting longer animated narratives

---

## Status

🚧 Work In Progress

This repository serves as an experimental exploration of combining traditional handmade artwork with modern generative AI video workflows. The workflow will continue evolving as new techniques and models become available.

---

## Credits

Original artwork and workflow development by Helen Zegarra.

Created using:

- ComfyUI
- WAN 2.2
- FLUX.1
