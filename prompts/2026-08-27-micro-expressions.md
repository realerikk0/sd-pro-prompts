# Micro-Expression Prompts — 2026-08-27

> Collected from recent X (Twitter) posts about usable micro-expression / 微表情 prompts for **Seedance 2.5** and **MiniMax H3 / Hailuo H3**. Only real, sourced prompts are included. No fabricated content.

---

## 1. MiniMax H3 — Micro-expressions with cheek poke (elf character)

**Source**: [@Tomw852](https://x.com/Tomw852)  
**Model**: MiniMax H3 (INT8 Convrot) + Lightx2V Turbo 8-step LoRA  
**Original post URL**: https://x.com/Tomw852/status/2092752306982764771  
**Date**: 2026-08-26

**Full prompt** (shared in the reply):

```
prompt:
subject_definitions:
Use Image 1 as the primary anchor for character identity, facial features, makeup, and lighting: young East Asian elf female (<Subject 1>) with fair porcelain skin with subtle pink undertones, short wet-look blonde textured hair with wispy bangs, long pointed elf ears with small silver hoop earrings, clear amber-hazel pupils with rectangular window catchlights, delicate pink eyeshadow, ultra-fine natural eyeliner, defined individual eyelashes, soft dewy peach-pink blush on cheeks and nose tip, and glossy hydrated pink lips.
Interaction Element: A natural, clean human hand entering from off-screen bottom-right to gently poke her cheek.
Setting & Lighting: Clean out-of-focus cool-grey indoor background, large soft window lighting from front-right creating shallow natural nose shadow, high-key exposure, lifted shadows, low contrast, and authentic micro-pore skin texture.
Camera & Framing: 9:16 vertical orientation, fixed eye-level portrait (50-70mm equivalent lens, strictly NO wide-angle distortion, NO camera movement, NO pan/tilt/zoom). Face fills the entire frame.

summary:
A 7-second ultra-realistic 9:16 vertical smartphone portrait video at 60fps locked to Image 1. Fixed eye-level macro close-up of the blonde elf girl executing continuous, lifelike micro-expressions from relaxed parted lips to shy lip purse, playful side glance, and a vulnerable pouting expression as an off-screen hand gently pokes her soft cheek. Pure realistic ambient audio, no music. 8k photorealistic, 60fps.

retention_analysis:
<Subject 1> (single subject throughout): fully_preserved - East Asian facial features from Image 1, wet-look blonde hair, pointed elf ears, silver hoop earrings, amber eyes with catchlights, peach blush, glossy lips, and visible skin pores.
<Picture 1> (the ONLY character & lighting anchor): fully_preserved - exact frontal facial framing, soft window lighting balance, makeup finish, and skin translucency.

detailed_description:
[Shot 1] (00:00.000 - 00:07.000): 9:16 vertical smartphone portrait video, 60fps, fixed stationary camera at eye-level, 50-70mm equivalent focal length with natural human facial proportions (strictly NO barrel/wide-angle distortion, NO zoom, NO pan, NO shake). The face fills almost the entire frame. Clean out-of-focus cool-grey room background, soft diffuse window light from front-right casting delicate natural shadows, distinct rectangular window catchlights reflected in both amber pupils. Authentic high-end smartphone social media selfie aesthetic: lifted shadows, soft glowing skin with light natural beautification that strictly preserves real visible pores. Clean hand and finger anatomy. Negative Directives: strictly NO sudden expression morphing, NO exaggerated acting, NO plastic skin, NO blurry eyes, NO camera drift, NO text.

From 00:00.000 to 00:01.000 [Initial State]: <Subject 1> faces directly forward, gazing gently into the smartphone lens. Her glossy pink lips are slightly parted, subtly revealing the edge of her upper teeth in a relaxed, natural state with visible gentle breathing.

From 00:01.000 to 00:02.000 [Lip Purse & Shy Smile]: Her lips smoothly close and press inward into a subtle, sweet lip purse (minced lips), tightening her chin slightly into an adorable, shy micro-expression.

From 00:02.000 to 00:03.000 [Gaze Shift to Left]: Maintaining her soft pursed lips, her amber pupils smoothly glide toward screen-left (her right side) in an alert, lively glance as if noticing a movement nearby, while her head remains almost stationary.

From 00:03.000 to 00:04.000 [Gaze Returns to Center]: Her eyes smoothly glide back to look directly into the camera lens. Her lips relax from the purse back into a calm, gentle resting expression.

From 00:04.000 to 00:05.000 [Pout & Cheek Poke Interaction]: Her inner eyebrows gently knit together into a subtle, innocent furrow (slight eight-shape brow), her eyes turning puppy-dog innocent and vulnerable while her lower lip pouts slightly outward. Concurrently, a clean, natural index finger from an off-screen hand enters from the bottom-right corner and gently pokes into her left cheek (screen-right), creating a soft, natural skin indentation and puffing up her cheek slightly.

From 00:05.000 to 00:06.000 [Sustained Cheek Poke & Pouting Eye Contact]: The finger maintains its gentle press on her cheek. <Subject 1> holds her endearing, aggrieved, vulnerable pout while looking straight into the camera lens with glassy, innocent eyes.

From 00:06.000 to 00:07.000 [Finger Release & Peaceful Drift Outro]: The finger smoothly withdraws out of frame. Her cheek elasticity softly bounces back to normal; her eyebrows ease and relax, her lips part slightly, and her gaze peacefully glides toward the upper-left of the screen into a gentle, serene daydream state until 00:07.000.

overall_soundscape:
100% pure authentic smartphone microphone room tone: subtle soft indoor air flutter, faint gentle breath intake and exhale close to the microphone, subtle soft tactile skin-contact sound when the finger pokes the cheek. Strictly NO background music, NO non-diegetic audio.

non_diegetic_music:
None. Pure natural environmental diegetic soundscape only.
```

---

## 2. Simple emotion prompt demonstrating emergent micro-expressions (MiniMax H3 / Seedance 2.5 / Wan 3.0)

**Source**: [@stellarprtcol](https://x.com/stellarprtcol)  
**Model**: MiniMax H3, Seedance 2.5, Wan 3.0  
**Original post URL**: https://x.com/stellarprtcol/status/2092884823660441844  
**Date**: 2026-08-27

**Full prompt** (shared directly in the post):

```
A young girl crying and smiling through tears while saying goodbye.
```

*Note from author: No explicit micro-expression instructions, tears physics, or eye-movement directives were given. Models spontaneously produced details such as holding back tears, lip biting, swallow timing before first tear falls, bittersweet smile transitions, and natural eye contact.*

---

## Other recent activity

- The detailed Seedance 2.5 couple cheek-kiss reaction prompt from [@liyue_ai](https://x.com/liyue_ai) (2026-08-26) is already archived in [prompts/2026-08-26-micro-expressions.md](2026-08-26-micro-expressions.md).
- Ongoing comparisons and video shares highlighting improved natural acting / micro-expression capabilities of MiniMax H3 and Seedance 2.5 when given simple emotional context or tightly timed facial sequences.

---

## Usage Tips

- **Timed micro-sequence approach** (Tomw852 example): Break the clip into 1-second beats with precise facial actions (lip purse → gaze shift → return → pout + physical contact reaction → residual expression). Keep head almost still while eyes move first. Preserve exact reference identity and lighting.
- **Minimal emotion prompt approach** (stellarprtcol example): Modern models (MiniMax H3 / Seedance 2.5) can now fill in realistic micro-details (swallow before tear, lip bite, asymmetric smile onset) from a single high-level emotional description. Useful for testing model “acting intelligence”.
- Always lock character identity via reference image and explicitly forbid face redesign / age drift when using image conditioning.
- Prefer fixed or very slow camera moves so facial micro-movements remain readable.
- Emphasize natural time lags between eye, brow, mouth, and head actions; avoid simultaneous morphing of all features.
- For interaction prompts, describe the soft-tissue response (cheek indentation, bounce-back elasticity) to improve realism.

Previous high-quality sources:
- [prompts/2026-08-26-micro-expressions.md](2026-08-26-micro-expressions.md)
- [prompts/2026-08-25-micro-expressions.md](2026-08-25-micro-expressions.md)
- [prompts/2026-08-24-micro-expressions.md](2026-08-24-micro-expressions.md)
- [prompts/2026-08-22-micro-expressions.md](2026-08-22-micro-expressions.md)
- [prompts/2026-08-20-micro-expressions.md](2026-08-20-micro-expressions.md)
- [prompts/2026-08-17-micro-expressions.md](2026-08-17-micro-expressions.md)

---

**Last updated: 2026-08-27**
