---
name: transformation-vfx-chant-direction
description: "Write paste-ready transformation prompts centered on an independent system chant, beat-by-beat VFX order, and a readable completed form. Include one clear human '変身!' call; keep story or emotion outside the core prompt. Use for original masked-hero transformation prompts; do not use as a replacement for general mechanical-transformation, VFX, sound-mix, or platform-compilation skills."
---

# Transformation Prompt: Chant & VFX Direction

## Scope

Own **prompt structure → chant timing → causal VFX beats → readable completion** inside a paste-ready transformation prompt.
Story motivation and ordinary-person emotion are not required. The deliverable must make the human command, system chant, effect order, and final state easy to read and check beat by beat.

Do not take ownership of:

- detailed hinges, rails, mass migration, locking, or armor engineering; hand those to `mechanical-transformation-design`;
- general effect physics and material simulation; hand the effect layer to `cinematic-vfx-director`;
- full sound mixing, score, or loudness design; hand the audio layer to `cinematic-music-sound-design`;
- Seedance/Jimeng or other platform syntax; hand final compilation to the active platform skill.

## Required Inputs

- output medium, duration, aspect ratio, and continuity constraints;
- reference-image invariants, if any (use them for the hero suit only unless the user says otherwise);
- hero device/core, module routes, and completion state;
- chant language/romanization and the visual/audio event each line must trigger;

If a detail is missing but does not change the chant or VFX route, choose a concrete default and continue.
For a missing delivery format, default to a 16:9, 20–30 second cinematic shot/prompt; state the chosen default in the output header.

## Core Sequence

Build the prompt in this order:

1. **Prompt brief** — lock medium, duration, framing, continuity, reference invariants, device/core, and completion state.
2. **Human command** — give the person one short line only when needed, then one clean Japanese transformation command.
3. **Chant map** — bind each independent system-chant line to a timestamp/beat, stress, visible event, sound, and inherited state.
4. **VFX beat map** — stage source → route → contact/lock → consequence → decay for every major effect.
5. **Camera and completion locks** — keep face, mouth, module boundaries, full silhouette, body weight, and final spatial relation readable.
6. **Optional context** — if the user supplies story context, keep it to one short line outside the chant/VFX core; otherwise omit it.

## Chant-first Prompt Contract

Keep these sources unmistakably separate:

### Human command

- The human alone says **「変身！」** (へんしん / Henshin) once.
- Use a clean, visible mouth sync and foreground human voice; do not let a device, narrator, or chorus say it.
- Do not repeat it, bury it under effects, or use it as a system-chant line.
- This is the only required human vocal cue; do not expand the prompt into a protection or resolve storyline.

### System chant

The transformation device/core uses an independent mechanical voice. Each line is short, stressable, and tied to one visible beat. It must not contain the word 「変身」. Mark the stressed mora in **CAPS** in the romanization (for example, `CO-re A-WAKE`), while preserving the Japanese line unchanged.

Use this adaptable five-line pattern (translate or rename to fit the hero; do not treat it as a fixed franchise slogan):

```text
コア・アウェイク！          // core wakes
ガード・パルス！            // field pulse expands
アーマー・スライド！        // armor modules enter their tracks
ロック・シーケンス！        // joints align and lock
コンプリート・ガーディアン！ // completed form is confirmed
```

For every line specify: timestamp or beat, voice source, stressed syllable, visual action, contact/lock sound, and the state inherited by the next beat. Keep no more than three module actions visually dominant in one beat; queue the rest as readable continuations. Never add chant words that have no visible or audible consequence.

## VFX Prompt Construction

Use a readable escalation rather than an instant full-screen flash:

| Level | Visual job | Causal rule |
|---|---|---|
| 1. Standby light | A small pulse at chest/core and seams | source is the device/core, optionally keyed by the human command; face and eyes remain clear |
| 2. Activation gate | A translucent geometric gate/portal rises around the core | the gate opens on the human command; it frames, never masks, the mouth or silhouette |
| 3. Guided tracks | Red/white bands, rails, or particles guide each armor module | every module has a source → path → arrival → contact/lock → light-up sequence |
| 4. Lock burst | Short arcs, recoil, and one controlled outward burst on the final locks | burst proves energy transfer and new weight; it is not random glitter |
| 5. Aftermath | One ground-hugging impact ring, environmental response, and fading motes | peak happens once, then decays to rain, breath, metal hum, and stable light |

For every effect write the chain explicitly: **source → route → contact/lock → consequence → decay**. Give the body a matching response (brace, lowered hips, widened feet, shoulder tension, or regrip) so the power has weight.

## Prompt Camera, Blocking, and Readability Locks

- Begin in a medium or medium-close view on the human, device/core, and first effect source.
- Push toward the eyes and mouth for the declaration, then use a restrained orbit that keeps each chant-triggered effect readable.
- Reveal the completed hero from a low angle only after the assembly is readable; hold a clean full-body silhouette at the peak.
- Effects may be large, but never obscure the human command, face, mouth, armor boundaries, or final silhouette.
- End with a stance that proves the new weight and a controlled aftermath, not a frozen beauty pose.

## Output Shape

```text
Prompt brief:
Optional context (one line, only if supplied):
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
Body and camera locks:
Completion proof:
Continuity and anti-obscuration locks:
Paste-ready prompt:
```

## Acceptance Check

Before delivery, confirm the final candidate—not an earlier draft—passes all of these:

- The final candidate is directly paste-ready in the requested prompt format.
- 「変身！」 appears exactly once as the human's audible command; the system never repeats or replaces it.
- Every system-chant line has a distinct visual/audio event and a next-state handoff.
- The five VFX levels escalate from a clear source and end in a single, decaying peak.
- Armor/effect motion has visible causality and the body adapts to new weight or inertia.
- The face, mouth, chant-triggered effects, and final full-body silhouette remain legible.
- Any story context is optional, one line at most, and never displaces the chant, VFX, or camera read.
- The prompt uses original mechanisms and wording rather than copying a named franchise's character, slogan, melody, or shot.

## Handoff

When the prompt needs deeper engineering, effect construction, sound design, or platform formatting, preserve this prompt/chant/VFX map and pass it to the relevant specialist. A successful tool call or generated frame does not by itself prove that the chant timing, effect causality, or final readability worked.
