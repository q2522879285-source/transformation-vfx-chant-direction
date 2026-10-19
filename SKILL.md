---
name: transformation-vfx-chant-direction
description: "Design transformation scenes in which an ordinary person's decision to protect or confront danger visibly summons power, with a clear human '変身!' call, separate system chant, staged VFX, emotional readability, and a grand but controlled finishing effect. Use for original masked-hero transformation prompts, storyboards, or scene direction; do not use as a replacement for general mechanical-transformation, VFX, sound-mix, or platform-compilation skills."
---

# Transformation VFX and Chant Direction

## Scope

Own the intersection of **emotional decision → power response → transformation spectacle → chant timing**.
The result must make the audience feel that the power answered a choice, not that a costume was applied by a preset.

Do not take ownership of:

- detailed hinges, rails, mass migration, locking, or armor engineering; hand those to `mechanical-transformation-design`;
- general effect physics and material simulation; hand the effect layer to `cinematic-vfx-director`;
- full sound mixing, score, or loudness design; hand the audio layer to `cinematic-music-sound-design`;
- Seedance/Jimeng or other platform syntax; hand final compilation to the active platform skill.

## Required Inputs

- ordinary-person identity and readable pre-transformation state;
- threat and the person/object being protected, or the danger being faced;
- the decision that triggers the response;
- reference-image invariants, if any (use them for the hero suit only unless the user says otherwise);
- output medium, duration, aspect ratio, and any continuity constraints.

If a detail is missing but does not change the emotional or visual route, choose a concrete default and continue.
For a missing delivery format, default to a 16:9, 20–30 second cinematic shot/prompt; state the chosen default in the output header.

## Core Sequence

Build the scene in this order:

1. **Human baseline** — show fear, fatigue, hesitation, or ordinary vulnerability through breath, eyes, hands, stance, and voice.
2. **Choice in action** — the person physically moves between danger and the protected subject (or advances toward the monster); do not jump directly to a pose.
3. **Declaration** — give the person one short protective or confrontational line. Leave a small breath/silence before the transformation call.
4. **Power response** — the first pulse must originate at the person's chest/core or established device and answer the declared intent. The person remains visibly human while the response begins.
5. **Call and assembly** — the person says the Japanese transformation command once; only after it does the independent system chant and staged armor/effect assembly begin.
6. **Proof of completion** — the transformed figure absorbs the new weight, settles into a stable stance, and changes the environment once at a controlled peak before facing the threat.

## Voice and Chant Contract

Keep these sources unmistakably separate:

### Human command

- The human alone says **「変身！」** (へんしん / Henshin) once.
- Use a clean, visible mouth sync and foreground human voice; do not let a device, narrator, or chorus say it.
- Do not repeat it, bury it under effects, or use it as a system-chant line.

### System chant

The transformation device/core uses an independent mechanical voice. Each line is short, stressable, and tied to one visible beat. It must not contain the word 「変身」. Mark the stressed mora in **CAPS** in the romanization (for example, `CO-re A-WAKE`), while preserving the Japanese line unchanged.

Use this adaptable five-line pattern (translate or rename to fit the hero; do not treat it as a fixed franchise slogan):

```text
コア・アウェイク！          // core answers the decision
ガード・パルス！            // protection pulse expands
アーマー・スライド！        // armor modules enter their tracks
ロック・シーケンス！        // joints align and lock
コンプリート・ガーディアン！ // completed form is confirmed
```

For every line specify: timestamp or beat, voice source, stressed syllable, visual action, contact/lock sound, and the state inherited by the next beat. Keep no more than three module actions visually dominant in one beat; queue the rest as readable continuations. Never add chant words that have no visible or audible consequence.

## Five-Level VFX Progression

Use a readable escalation rather than an instant full-screen flash:

| Level | Visual job | Causal rule |
|---|---|---|
| 1. Standby light | A small pulse at chest/core and seams | source is the person's answered intent; face and eyes remain clear |
| 2. Activation gate | A translucent geometric gate/portal rises around the core | the gate opens on the human command; it frames, never masks, the mouth or silhouette |
| 3. Guided tracks | Red/white bands, rails, or particles guide each armor module | every module has a source → path → arrival → contact/lock → light-up sequence |
| 4. Lock burst | Short arcs, recoil, and one controlled outward burst on the final locks | burst proves energy transfer and new weight; it is not random glitter |
| 5. Aftermath | One ground-hugging impact ring, environmental response, and fading motes | peak happens once, then decays to rain, breath, metal hum, and stable light |

For every effect write the chain explicitly: **source → route → contact/lock → consequence → decay**. Give the body a matching response (brace, lowered hips, widened feet, shoulder tension, or regrip) so the power has weight.

## Camera, Blocking, and Emotional Readability

- Begin in a medium or medium-close emotional view; keep the threat and protected subject on a stable front/back axis.
- Follow the protective move laterally, push toward the eyes and mouth for the declaration, then use a restrained orbit during the response.
- Reveal the completed hero from a low angle only after the assembly is readable; hold a clean full-body silhouette at the peak.
- Effects may be large, but never obscure the human command, face, mouth, armor boundaries, or the protected subject's location.
- End with a changed stance and a changed spatial relationship to the threat, not a frozen beauty pose.

## Output Shape

```text
Emotional trigger:
Ordinary-person baseline:
Protection/confrontation action:
Human declaration:
Human command: 「変身！」 (once, with mouth-sync)
System chant map:
  - line / beat / visual event / sound / inherited state
VFX progression:
  - standby light
  - activation gate
  - guided tracks and module routes
  - lock burst
  - aftermath and environmental response
Body and camera choreography:
Completion proof:
Continuity and anti-obscuration locks:
Paste-ready scene or prompt:
```

## Acceptance Check

Before delivery, confirm the final candidate—not an earlier draft—passes all of these:

- The decision to protect or face danger is readable before the first major effect.
- 「変身！」 appears exactly once as the human's audible command; the system never repeats or replaces it.
- Every system-chant line has a distinct visual/audio event and a next-state handoff.
- The five VFX levels escalate from a clear source and end in a single, decaying peak.
- Armor/effect motion has visible causality and the body adapts to new weight or inertia.
- The face, mouth, protected subject, and final full-body silhouette remain legible.
- The protected subject has an explicit end state (safe position, readable condition, and unchanged relationship to the hero).
- The scene uses original mechanisms and wording rather than copying a named franchise's character, slogan, melody, or shot.

## Handoff

When the scene needs deeper engineering, effect construction, sound design, or platform formatting, preserve this emotional/chant map and pass it to the relevant specialist. A successful tool call or generated frame does not by itself prove that the emotional cause, voice separation, or final readability worked.
