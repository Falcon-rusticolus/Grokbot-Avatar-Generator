# Grokbot Avatar Prompt Template

Use this template with the built-in `image_gen` tool. Replace every bracketed field with observations from the user's photo. Keep the locked description unchanged.

```text
Use case: stylized-concept with identity preservation
Asset type: square social-media avatar, single character

Input images and roles:
- Image 1: grokbot style reference 01. Lock the flat 2D rendering language, chibi facial proportions, hair massing, cat-ear construction, and clean color blocking.
- Image 2: grokbot style reference 02. Primary composition lock: square close-up, head tilt, ear placement, charcoal background, cropped shoulders.
- Image 3: grokbot style reference 03. Reinforce the same silhouette, pose, face, eye shape, hair shading, and framing as Image 2.
- Image 4: user source photo. Use only identity cues: hair color, hairstyle and length, skin tone, face-shape tendency, glasses or one distinctive accessory. Do not copy its background, lighting, camera angle, pose, expression, or detailed clothing.

Primary request:
Transform the person in Image 4 into the exact chibi cat-eared avatar language shared by Images 1–3. Keep the result recognizably based on Image 4 while matching the reference style, head pose, and composition almost exactly.

Identity mapping:
- Hair base color: [exact hair color]
- Hairstyle and length: [short/medium/long, fringe direction, volume, texture simplified into large flat shapes]
- Skin tone: [light/medium/deep, converted to a smooth low-saturation flat tone]
- Face-shape cues: [round/oval/angular tendency, kept within the oversized chibi head]
- Distinctive feature to retain: [glasses / earrings / hair clip / freckles / none; simplify to one flat graphic cue]
- Clothing cue: [optional single neckline or accessory cue; otherwise use the default cream scalloped collar]

Locked composition:
Square 1:1 canvas. Extremely tight head-and-upper-shoulder portrait. Head and hair occupy about 80–90% of the image width and about 90% of the height. The chin sits near the lower part of the frame; only a small area of shoulder and scalloped cream collar is visible at the lower left. No hands, no torso, no full body. Softly tilt the head about 12–18 degrees toward the lower-left of the canvas, with a slight three-quarter turn. Place one large cat ear at the upper left and the other at the upper right, with the right ear partly covered by hair. Fill the frame with the head rather than centering a small figure.

Locked face and features:
Oversized, soft, slightly flattened chibi face. No human ears. No eyebrows, eyelashes, nose, or mouth. Exactly two solid opaque black vertical capsule-shaped eyes, tall and rounded, with no white sclera, no pupils, no highlights, and no eyelashes; follow the head tilt so one eye sits slightly lower than the other. Add one small pale-pink oval blush low on each cheek. Do not turn the eyes into large anime eyes.

Locked hair and cat ears:
Use only large, clean, angular hair masses with a few pointed locks. Sweep a heavy fringe across the forehead, frame the face with long side locks, and keep the outer silhouette simple and graphic. Add at most one darker same-hue flat shadow shape and one very pale flat crescent highlight. Make the cat ears large, soft triangles with slightly rounded tips and muted pink inner-ear shapes; they must read as part of the hair, not realistic animal ears. Do not copy the reference characters' hair colors.

Locked rendering:
Crisp 2D flat vector-like illustration with matte low-saturation pastel colors. Large flat color blocks, clean edges, no outline stroke. Absolutely no gradients, gloss, texture, grain, photorealism, 3D shading, soft airbrush, detailed strand lines, or complex lighting. The image should feel like simple paper-cut animation character art.

Background:
Solid matte charcoal (#232221), completely flat and empty, matching Images 2 and 3. Do not copy the user's background. Use warm off-white (#F7F6F4) only if the user explicitly asks for the light-background variant.

Clothing:
Only a simple cream/off-white top and a restrained scalloped or ruffled collar at the neck and lower-left edge. No detailed outfit, patterns, logos, jewelry set, or extra props. [Optional: retain one simplified signature accessory only if it is essential to the person's identity.]

Constraints:
Exactly one character. Keep the face, ears, hair, and shoulders in the same close-up arrangement as the references. No text, no watermark, no border, no extra objects, no second person, no hands, no open mouth, no ordinary anime eyes, no photorealism, no outline art, no bright saturated colors, no invented clothing details. Do not copy the hair color or identity of the reference characters; use the identity cues from Image 4 only.
```
