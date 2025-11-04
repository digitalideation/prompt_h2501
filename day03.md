# Day 03 — VibeCoding & Video Interpretation

**Duration:** 2 h 30 min.  
**Focus:** Translating visual rhythm and motion into procedural logic through **p5.js**, then extending those human-coded aesthetics into **AI-generated video interpretations**, inspired by Rafael Rozendaal’s _Internet_ (2002).  
**Mode:** Browser-based (p5.js Web Editor + Replicate) — pairs or small groups of 2–3.

| Block | Activity                            | Duration       |
| :---- | :---------------------------------- | :------------- |
| 1     | Foundations: Net Art & Motion Logic | 20 min         |
| 2     | VibeCoding Demo & Warm-up           | 15 min         |
|       | Break                               | 10 min         |
| 3     | Team VibeCoding Exercise            | 30 min         |
| 4     | AI Video Interpretation             | 15 min         |
| 5     | Showcase & Reflection               | 20 min         |
|       | **Total**                           | **2 h 30 min** |

## 🧱️ Block 1 — Foundations: Net Art & Motion Logic

### 1. Introduction to Rafael Rozendaal and _Internet_

- Discuss the early 2000s web-art context — minimalism, interactivity, code-as-canvas.
- View [_Internet_ (2002)](https://www.newrafael.com/internet/): observe how repetition, rhythm, and color produce emotion without narrative.
- Key themes: **loop**, **pattern**, **interaction**, **vibe through motion**.

### 2. Conceptual Bridge to VibeCoding

- Explain that **VibeCoding = prompting through parameters**:  
  _speed_, _color_, _density_, _rhythm_.
- Show how small numeric tweaks shift perception — like prompt refinements in text or sound.

## 🧱️ Block 2 — VibeCoding Demo & Warm-up

### 3. p5.js Demo (Non-coders friendly)

Demonstrate a minimal sketch:

```js
let dots = [];
function setup() {
  createCanvas(600, 600);
  for (let i = 0; i < 80; i++)
    dots.push(createVector(random(width), random(height)));
}
function draw() {
  background(0, 10);
  stroke(255);
  for (let p of dots) {
    p.x += sin(frameCount * 0.01 + p.y * 0.01);
    p.y += cos(frameCount * 0.01 + p.x * 0.01);
    point(p.x, p.y);
  }
}
```

Show how adjusting `stroke()`, `sin()` speed, or number of dots changes the vibe.

### 4. Vibe Prompts (Verbal Control)

Invite students to suggest:

> “Make it calmer.” “Add chaos.” “Shift the color toward neon.” “Fade more slowly.”

Record the effect of each description → numeric change.

## 🧱️ Block 3 — Team VibeCoding Exercise

**Objective:** Recreate the _feel_ of _Internet_ through parameter manipulation, not replication.

**Structure**

- Teams of 2 (1 Tuner + 1 Vibe Director).
- Each uses a shared p5 link (template provided).
- Directors describe motion and color conceptually; Tuners adjust numbers.
- Observers (optional) document iterations and take screenshots.

**Focus Areas**

| Aspect      | Prompt-style Guidance                          |
| :---------- | :--------------------------------------------- |
| Composition | “Like a constellation — sparse but connected.” |
| Motion      | “Oscillate like breathing, not chaos.”         |
| Color       | “Digital glow on black — cold light.”          |
| Tempo       | “Start slow, accelerate, then stillness.”      |

**Output:** looping p5 sketch + saved first and last frames.

## 🧱️ Block 4 — AI Video Interpretation

**Goal:** Use AI to “interpret” the transition between the two frames.

**Steps**

1. Teams export first and last frames (`saveFrame()` or screenshot).
2. Instructor uploads pairs to Replicate (img2vid) to generate 3–5 s videos.
3. Optional audio sync: add their Day 02 _PromptVision_ track as soundtrack.

👉 Full step-by-step setup, p5 account instructions, and submission details:
[`VibeCoding Class Flow`](./notes/vibecoding.md)

## 🧱️ Block 5 — Showcase & Reflection

**Gallery Format**

- Display each team’s p5 loop alongside its AI video.
- Quick commentary: what changed? what did the AI exaggerate or lose?

**Discussion Prompts**

- “What parameter most defined your vibe?”
- “Did the AI capture your intended motion?”
- “Where does authorship sit in this chain?”

**Optional Audience Highlights**

- 💫 _Most Hypnotic Loop_
- ⚡ _Best AI Interpretation_
- 🪞 _Closest to Rozendaal’s Spirit_

### ✅ Learning Outcomes

- Describe and control visual motion and mood through parameterized logic.
- Translate artistic intuition into computational form.
- Extend human-coded aesthetics into AI video interpretations.
- Reflect critically on machine perception of vibe and authorship.
