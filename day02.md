# Day 02 — Prompting for Music & Sound Generation

**Duration:** 2 h 30 min.  
**Focus:** Crafting prompts for genre, mood, tempo, instrumentation, and structure; producing and evaluating short AI-generated tracks in a _Eurovision-style_ contest (PromptVision).  
**Mode:** Browser-only (web-based music models) — small teams of 2 (≈ 6).  

| Block | Activity                         | Duration       |
| :---- | :------------------------------- | :------------- |
| 1     | Foundations & Demos              | 20 min         |
| 2     | Tools & Prompt Craft             | 20 min         |
|       | Break                            | 10 min         |
| 3     | **PromptVision** Creation Sprint | 45 min         |
| 4     | Listening Party & Voting         | 25 min         |
| 5     | Wrap-Up & Takeaways              | 10 min         |
|       | **Total**                        | **2 h 30 min** |

## 🧱️ Block 1 — Foundations & Demos

### 1. How Text-to-Music / Audio Models Work

- **Key concepts:** diffusion, autoregression, transformer sequence modeling.
- **Modalities:** text-to-music, text-to-sound (SFX), audio-to-audio (style/voice transfer).
- **Audio pipeline:** prompt → latent/audio tokens → decoding → waveform.

### 2. Prompt Parameters (Quick Demo)

- **Structure:** _genre → mood → tempo (BPM) → instrumentation → structure (intro/verse/chorus/ending) → vocal style/lyrics (optional)_.
- **References:** mention artists/eras cautiously; better to describe **features** (e.g., "syncopated funk guitar", "reverby 80s snare").
- **Iteration:** change **one variable** per take to hear its effect.

## 🧱️ Block 2 — Tools & Prompt Craft

### 3. Tools Overview

- **Text-to-Music:** Suno.ai, Udio, MusicFX.
- **Sound Design / Textures:** Mubert, AudioLDM/AudioCraft.
- **Editing/Finishing:** BandLab, Soundtrap, Audacity (trim, normalize).
  🔘 Run the **same prompt** on two tools → compare fidelity, vocals, and mix.

### 4. Effective Music Prompts (Mini Task)

- Start from a plain idea → refine with parameters:

  - “Ambient track” → “Ethereal **ambient** drone at **70 BPM** with **warm pad** and **field recordings**, **slow crescendo** over 30 s.”
  - “Pop song” → “Uplifting **synthpop** at **118 BPM**, **side-chained bass**, **four-on-the-floor kick**, **female lead** with vocoder doubles, **verse–chorus–outro**.”

- Students rewrite a prompt three ways (tempo/mood/instrument swap) and preview 1–2 takes.

— See teaching cues in [`Day 02 — Teaching Notes`](./notes/day02.md).

## 🧱️ Block 3 — PromptVision Creation Sprint (Contest)

**Objective:** Teams craft a **60+ s** track that matches a shared theme and submit it with the final prompt text and tool used.

**Structure:**

- No fixed Theme.
- Each team gets **~45 min** to iterate 2–3 times and export one final clip (normalize to consistent loudness).

**Prompt checklist:** genre, mood adjectives, tempo (BPM), instruments, structure/arc, vocal/lyrics (optional), mix notes (dry/wet, reverb).

👉 Full contest flow, judging rubric, and submission template: [`PromptVision Guide`](./notes/promptvision.md) _(to be added)_.

## 🧱️ Block 4 — Listening Party & Voting

- Play all tracks back-to-back (playlist or Padlet).
- Teams save read or project **their prompt** (or you read from instructor-only sheet).
- Voting:

  - 🏆 **Best Song**
  - 🥇 **Audience Favorite**   
  - 🎧 **Instructor Highlights**

## 🧱️ Block 5 — Wrap-Up & Takeaways

- Discuss: _Which prompt elements most affected structure and timbre?_
- Note limitations (lyrics coherence, long-form structure).
- Ethical reminders for follow-up sessions (voice likeness, licensing, disclosure).

### ✅ Learning Outcomes

- Design prompts that control **genre, mood, tempo, and instrumentation**.
- Compare model outputs and iterate deliberately.
- Produce and evaluate a short track aligned to a theme and prompt design.
