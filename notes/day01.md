# 🧑‍🏫 Teacher Notes — Day 01 (Blocks 1–3)

These notes provide additional examples, prompts, and cues for **Blocks 1–3**. Use them for live demos, warm-up prompts, or guided discussions.


## 🧱 Block 1 — Foundations & Demo

### 💡 Key Concepts Recap

- **Diffusion models:** explain how noise is iteratively removed to reveal an image.
- **Latent space:** where the model encodes abstract ideas of form, color, and composition.
- **Conditioning:** how the text prompt influences sampling.
- **Attention:** the mechanism aligning words to image features.

🧠 **Talking Points:**

- Relate model stages to traditional art: _latent space = sketch stage_, _denoising = refinement_, _sampling = rendering_.
- Clarify that models don’t “see” like humans — they map statistical patterns.

### 🧰 Quick Demo Ideas

1. **Baseline demo:**

   - Prompt: `A cat sitting on a chair.`
   - Show the output — note how generic and underspecified it is.

2. **Modifier layering:**

   - Prompt: `A cat sitting on a vintage armchair, sunlight streaming through a window, cinematic lighting, detailed textures.`
   - Discuss how adding medium and lighting words improves coherence.

3. **Negative prompts:**

   - Add: `--no text, --no watermark, --no blurry background.`
   - Observe differences and note where the model still fails.

### ⚙️ Optional Quick Exercise

- Ask students to modify the same subject three ways:

  1. Realistic photo
  2. 3D render
  3. Pencil sketch

- Discuss how each descriptor changes tone and form.


## 🧱 Block 2 — Tools & Prompt Craft

### 🎨 Example Prompts for Art Styles

| Style                           | Example Prompt                                                                                         | Discussion Focus                                                                          |
| ------------------------------- | ------------------------------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------- |
| **Cyberpunk / Digital Art**     | `A futuristic cityscape at night, digital art, neon lighting, rain reflections, ultra-detailed`        | Focus on lighting, atmosphere, and medium keywords (`digital art`, `neon`, `cinematic`).  |
| **Impressionist Painting**      | `A quiet village in watercolor at sunrise, soft brush strokes, pastel colors, atmospheric perspective` | Use of medium and texture; color tone shaping the emotional feel.                         |
| **Surreal Photography**         | `A floating whale above desert dunes, golden hour light, wide-angle lens, photo-realistic style`       | How realism terms (`photo-realistic`, `lens`, `lighting`) blend with dream-like elements. |
| **Graphic Poster / Minimalist** | `Abstract geometric shapes forming a sunset, flat colors, vector art, minimalist composition`          | Shape and composition vocabulary — introduce `vector`, `flat color`, `negative space`.    |

💡 **Teaching Tip:**

- Generate one scene (e.g., “a forest clearing at dawn”) in multiple styles above to visualize how adjectives change the composition.
- Ask students to identify which words _anchor_ realism and which drive _style_.


### 🧩 Comparison Prompts — Tone & Texture

Show how small changes transform results:

- `A forest path at night, mysterious atmosphere` → darker, moody lighting.
- `A forest path at night, whimsical atmosphere` → glowing elements, fantasy cues.
- `A forest path at night, photorealistic style` → natural shadows and detail.

🗣️ **Prompt exercise suggestion:** Have each group rewrite “portrait of an old sailor” into three versions:

1. _Oil painting on canvas, 19th century realism._
2. _Comic book panel, dramatic lighting, expressive lines._
3. _3D render, cinematic light, detailed textures._

Compare how the model shifts medium and emotion.


## 🧱 Block 3 — Writing Visual Scene Descriptions

### 🧠 Teaching Cues

Encourage students to think like directors — emphasize **Who, What, Where, When, How.**

**Mini scenarios for practice:**

1. A street musician playing saxophone under a streetlamp at sunset.
2. A small boat approaching an iceberg in fog.
3. A child releasing balloons in a busy market.
4. An astronaut planting a tree on Mars at dawn.
5. A dancer moving through beams of light on an empty stage.


### ✍️ Example 3-Line Scene Prompts

Use these to illustrate descriptive richness and spatial detail:

1. _“At dawn, a cyclist crosses a foggy bridge, warm orange light cutting through the mist. Wide cinematic frame, lens flare, backlit composition.”_
2. _“Inside an abandoned theater, dust particles float through a single beam of light. A solitary dancer stretches, reflected in broken mirrors.”_
3. _“A red umbrella lies open on a rainy Tokyo street, neon reflections on wet pavement, captured from a low camera angle.”_

💬 **Teaching Tip:**

- Show how adding _time of day_, _light source_, and _camera angle_ deepens storytelling.
- Have students create a short description, then ask their peers to sketch or imagine the composition before generating it — emphasizing clarity of visualization.


### 🎯 Outcome for Blocks 1–3

After these sections, students should be able to:

- Explain core principles of text-to-image generation.
- Use descriptive modifiers that clearly communicate style and mood.
- Translate conceptual or emotional ideas into visual cues.
- Write multi-sentence prompts that create coherent, story-driven imagery.
