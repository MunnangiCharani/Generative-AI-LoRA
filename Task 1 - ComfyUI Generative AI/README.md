# Task 1 — Generative AI with ComfyUI

## Overview

This task focused on exploring **Generative AI using ComfyUI**, a node-based interface for building and running AI generation workflows.

The work included both **image generation** and **image-to-video generation** using locally running models.

---

## Objectives

- Understand the basic workflow of ComfyUI
- Generate a realistic image using SDXL Turbo
- Learn prompt and negative-prompt design
- Explore image-to-video generation
- Configure a Wan 2.1 workflow
- Understand node-based Generative AI pipelines
- Experiment with generation settings based on available GPU resources

---

## Tools and Models

- **ComfyUI Desktop**
- **SDXL Turbo** — Image Generation
- **Wan 2.1** — Image-to-Video Generation
- GPU-based local inference

---

## Part 1 — Image Generation

A realistic village pond scene was generated using SDXL Turbo.

### Prompt

> A realistic photograph of a peaceful village pond in India during early morning, surrounded by green trees and grass, soft golden sunlight, calm water with natural reflections, a few birds in the distance, natural colors, realistic photography, highly detailed.

### Negative Prompt

> cartoon, illustration, anime, painting, 3D render, unrealistic, text, watermark

The generated image was then used as the input for the video generation stage.

---

## Part 2 — Image-to-Video Generation

The generated pond image was converted into a short video using **Wan 2.1**.

The workflow included:

1. Loading the required models
2. Providing start and end images
3. Defining positive and negative prompts
4. Configuring sampling parameters
5. Decoding the generated frames
6. Creating and saving the final video

### Video Prompt

> A realistic peaceful village pond in India during early morning. The water gently ripples, leaves and grass move softly in a light breeze, birds move naturally in the distant sky, and the camera slowly moves forward. Stable cinematic camera movement, natural lighting, realistic motion, photorealistic.

### Negative Prompt

> cartoon, anime, illustration, distorted, unrealistic motion, flickering, warping, blurry, text, watermark

---

## Generation Settings

For the final video generation:

| Parameter | Value |
|---|---:|
| Width | 480 |
| Height | 480 |
| Length | 33 frames |
| Batch Size | 1 |
| Steps | 10 |
| CFG | 6.0 |
| Sampler | uni_pc |
| Scheduler | simple |
| Denoise | 1.00 |
| FPS | 16 |

---

##  Outputs

The task produced:

- A realistic AI-generated village pond image
- A short image-to-video generation showing natural environmental motion
- A ComfyUI workflow for the generation process

---

## Key Learnings

Through this task, I gained practical experience with:

- Node-based Generative AI workflows
- Prompt engineering
- Negative prompting
- Image generation using diffusion models
- Image-to-video generation
- Model and workflow configuration
- GPU-based local AI generation
- Adjusting generation parameters according to available computational resources

---

## Conclusion

This task provided hands-on experience with **ComfyUI and Generative AI**, starting from text-to-image generation and progressing to image-to-video generation.

The experiment demonstrated how different AI models and node-based workflows can be combined to create realistic visual content locally.

---
