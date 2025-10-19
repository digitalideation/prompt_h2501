# Day 01 — Prompting for Image & Video Generation

**Duration:** 2 h 30 min.  
**Focus:** Understanding how text-to-image models interpret prompts and practicing expressive scene design through the _Artistic Telephone_ exercise.  
**Mode:** Browser-only (Replicate pages) — small groups of ≈ 6.

| Block | Activity                          | Duration       |
| :---- | :-------------------------------- | :------------- |
| 1     | Foundations & Demo                | 15 min         |
| 2     | Tools & Prompt Craft              | min            |
| 3     | Writing Visual Scene Descriptions | 20 min         |
|       | Break                             | 10 min         |
| 4     | Artistic Telephone Exercise       | 70 min         |
| 5     | Mini-Gallery & Wrap-Up            | 20 min         |
|       | **Total**                         | **2 h 30 min** |

## 🧱️ Block 1 — Foundations & Demo

### 1. How Text-to-Image / Video Models Work

- **Key concepts:** diffusion, latent space, conditioning, tokenization, attention.
- **Typical models:** DALL·E 3, Midjourney, Stable Diffusion XL, Runway, Pika Labs, Sora (conceptual).
- **Visual pipeline:** prompt → text embedding → latent noise → progressive denoising → image/video.

### 2. Prompt Parameters (Quick Demo)

- **Structure:** _subject → medium → style → lighting → composition → mood_.
- **Modifiers:** camera angle, aspect ratio, render engine, realism vs stylization.
- **Negative prompts:** exclude undesired features.

## 🧱️ Block 2 — Tools & Prompt Craft

### 3. Tools Overview

- **Images:** Replicate pages for different image models.
- **Videos:** Runway ML, Pika Labs, Kaiber.
- **Workflow helpers:** ComfyUI, Automatic1111 (for later exploration).  
  🔘 Compare one identical prompt across two models → observe aesthetic bias and parameter defaults.

### 4. Effective Prompts for Art Styles

- **Example:**

  - “A portrait of a young woman” → baseline.
  - “Cinematic portrait of a young woman, shot on 35 mm film, soft lighting, shallow depth of field, realistic skin texture” → refined.

- **Mini task:** rewrite a plain prompt in three styles (realistic / surreal / graphic).
- **Discuss:** which words shift mood, depth, or color palette?

## 🧱️ Block 3 — Writing Visual Scene Descriptions

### 5. Scene Construction & Narrative Detail

- **Think like a director:** Who / What / Where / When / How.
- Encourage multi-sentence prompts: _“At dawn, a cyclist crosses a foggy bridge, warm orange light cutting through mist, cinematic composition.”_
- **Pair activity:** expand a one-line scenario into a 3-line scene prompt.
- **Group demo:** generate a few examples → discuss clarity vs ambiguity.

## 🧱️ Block 4 — Artistic Telephone Exercise (1:30 → 2:20)

### 6. Collaborative Prompt Drift Game — Overview

**Purpose:** Practice scene and style prompting while experiencing how meaning shifts through iterative reinterpretation.

**Structure:**

- Students form 6–7 groups of ~6 participants each (≈38 total).
- Each group runs a 6-step image-passing chain — every student interprets the previous image and generates a new one.
- One shared folder per group; consistent naming system.
- Class uses one diffusion model (e.g., Fux @ 1024px) for uniformity.

**Timing:** ~75–85 min total for the full chain + gallery.

**Example Flow:**

1. Round 1: Write & generate first prompt.
2. Rounds 2–6: Each student reinterprets only from the received image.
3. Upload all images sequentially for gallery comparison.

**In-Class Focus:**

- Emphasize prompt clarity, stylistic vocabulary, and visual storytelling.
- Encourage playful drift — ambiguity and misinterpretation are expected.

**Further Details:**
👉 Full step-by-step timing, starter themes, and instructor guidance available in [`Artistic Telephone Guide`](./notes/artistic_telephone.md).

## 🧱️ Block 5 — Mini-Gallery & Wrap-Up

- Each group shows its three-image chain side by side.
- Lightning discussion: _Which details persisted? Which words caused surprising changes?_
- Optional quick votes: Most Surprising Transformation / Best Scene Composition.

### ✅ Learning Outcomes

Students can:

- Design scene-based prompts that control style and composition.
- Compare how different models interpret identical language.
- Experience and analyze interpretation drift in generative chains.
