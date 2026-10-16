# Unified Whitespace Product Visual Language

This is the only visual-language reference for `ecommerce-aigc`. Apply the same whitespace product layout to every product, category, channel, and aspect ratio. Do not select, mix, or output other style regions, and do not produce multi-axis style scores.

> The complete Chinese counterpart is [region-visual-language.zh-CN.md](region-visual-language.zh-CN.md).

## Core visual relationship

`continuous low-interference base + exactly one complete flat 1:1 circle behind the product + one complete medium-to-large product + separate copy zone + one modern sans-serif family + soft grounding light`

“Lifestyle-friendly” means natural color temperature, approachable materials, and calm editorial rhythm. It must not be expressed through people, rooms, outdoor environments, or usage narratives.

## Composition

- Define the copy zone, product zone, and continuous whitespace before placing elements. Copy must never cover, intersect, or touch the product.
- The product is the only first visual entry. Place it on the center axis, a rule-of-thirds focal point, or the dominant side of a split layout; never reduce it to a corner thumbnail.
- Default to copy left/product right. Mirror only when the product orientation requires it. Portrait layouts may use copy above/product below while keeping the zones fully separate.
- Use stable horizontal and vertical relationships with mild asymmetry. Avoid strong diagonals, rotation, floating poses, speed cues, exaggerated perspective, and unnecessary edge cropping.
- Place all primary copy on one alignment axis. Keep supporting information near the main copy block rather than scattering labels around the product.
- Use one short headline, one subtitle, and zero to two supporting groups. If price, date, and CTA are required, combine them into one lower information block.

## Product scale and spacing

- Copy zone: about `28–38%` of canvas width. Product zone: about `45–60%`. Keep a visual gap equal to `4–7%` of the short canvas side.
- Typical product bounding box: `40–60%` of total canvas area. Tall products: `58–80%` of canvas height. Wide products: `55–72%` of canvas width. Avoid less than `30%` of canvas area unless the object shape requires it.
- Outer margin: `6–9%` of the short side. Minimum copy-to-product clearance: `4–6%`. Product-to-canvas-edge buffer: at least `3–5%`.
- Visible whitespace: roughly `35–50%`, including one continuous area large enough for the headline.
- Keep the product complete, sharp, and correctly proportioned. Never crop, hide, or reconstruct identity-critical features such as package name, logo, opening, handle, button, wheel, sole, or material seam.
- Ground the product with a soft contact shadow or a nearly invisible support plane. Do not fill space with props or a literal setting.

## Typography

- Prefer one family: a modern sans-serif, humanist sans, or neutral grotesk. For mixed Chinese and Latin text, choose compatible optical sizes and stroke weights.
- Headline: `Semibold 600–700`. Subtitle, body, and labels: `Regular/Medium 400–550`. The headline may be prominent, but its visual area must remain smaller than the product.
- Suggested relative sizes: headline `1`, subtitle `0.42`, body `0.26`; important numbers may be `0.50–0.70` of headline size.
- Headlines normally use one to three lines. Break Chinese at natural phrases of roughly `4–10` characters and English at `2–5` words.
- Headline leading: about `0.90–1.10` of type size. Body leading: about `1.30–1.55`.
- Default to left alignment and one shared vertical start line.
- Small CTA or labels may use a restrained pill, hairline border, or translucent plate, with at most two label treatments per poster. Never place the headline in a pill.
- Use near-black, deep grey, or a dark neutral derived from the product. Allow only one very small accent color.
- Exclude calligraphy, handwriting, decorative serif, condensed distortion, outlined type, 3D type, neon type, metallic type, and multiple shadows.

## Background and color

The background is neither untreated white nor a competing subject. It should improve product silhouette, material truth, and copy calmness through restrained hue relationships, controlled lightness, and stable geometry.

### Analyze before choosing color

Read six properties from the product reference:

1. dominant hue;
2. secondary hue;
3. lightness range;
4. saturation peak;
5. material reflectance: matte, suede, plastic, metal, glass, pearl, or highly reflective;
6. edge clarity, especially along white, highlight, transparent, black, and dark areas.

Summarize internally as: `[dominant color and lightness] + [material] + [most vulnerable edge] + [needs unity or separation]`.

### Fixed background layering

- Background structure is always `continuous base color + one standard flat two-dimensional circle from one supporting hue family`.
- The base covers about `65–80%` and establishes whitespace and temperature. Prefer warm white, cool white, mist grey, cream, pale beige, oat, pale grey-pink, mist blue-grey, sage grey, or an extremely pale greyed category color. Avoid raw white and a base identical in lightness to the product.
- The circle covers about `12–28%` and separates edges or balances mass. Its saturation must be lower than the product’s dominant color, and its local contrast must not exceed the product’s identity-critical internal contrast.
- A low-lightness circle should cover only `8–18%`.
- Preserve `35–50%` continuous quiet space with no texture, flare, gradient, line decoration, or extra block.
- The product must retain the highest color recognizability, clearest identity edges, and strongest local light-dark structure.

## The single required circle

Every poster must use exactly one main support shape, and it must be a complete, standard, flat, solid two-dimensional circle.

### Non-negotiable geometry

- Width equals height exactly; aspect ratio is exactly `1:1`; horizontal and vertical radii are identical.
- The whole closed circumference stays inside the canvas. Never crop the circle at a canvas edge or show only a semicircle, arc, or gap.
- Only uniform scaling and planar translation are allowed. Adapt to product shape only by changing diameter and center position. Never adjust width and height independently; never stretch, squash, tilt, perspective-transform, mask, crop, or distort it.
- Use a uniform solid fill. Do not use gradients, light spots, texture, outline, drop shadow, inner shadow, volumetric light, highlight, thickness, or glow.
- The circle is not a sphere, disc, hole, window, planet, platform, or spatial device.

### Size and position

- Align the circle center to the product’s main visual mass, then offset only `3–8%` of the product-zone width or height toward the quieter side when necessary.
- Typical diameter: `75–95%` of product-zone width.
- Place the product in front of the circle. It may occlude the middle while continuous arcs remain visible at the sides, shoulders, or base. Occlusion does not permit geometric cropping; the underlying circle must remain complete.
- The product may extend `5–18%` beyond the circumference at the top, bottom, or one side.
- Keep logo, opening, handle, button, wheel, sole, and other identity-critical structures away from the circumference tangent.
- Keep the circle entirely outside the text-safe zone. If space is insufficient, reduce or move the circle; never crop it or convert it to an ellipse.

### Forbidden substitutes

No ellipse, semicircle, arch, rounded rectangle, capsule, sector, curved band, edge block, irregular curve, freeform field, gradient spot, 3D sphere, glass ball, glowing disc, radial gradient, halo, concentric circle, orbit, scan ring, node, tick mark, or dashboard instrument.

Fixed geometry order: `continuous base → one complete flat circle → product → realistic contact shadow`.

## Four color paths

Choose exactly one path per poster.

1. **Same-hue lightness contrast** — Extract the product hue, make the base much lighter and less saturated, then use a one-step darker same-family circle. Best for strong brand colors, quiet unity, and material-first presentation.
   - Burgundy product → warm white or pale grey-pink base + dusty rose circle.
   - Forest green product → oat or very pale green-grey base + sage-grey circle.
2. **Greyed complementary contrast** — Choose a complement or near-complement, heavily reduce saturation, and adjust lightness before using it as the circle. Best for weak edge separation or a saturated product.
   - Red-orange product → warm white base + grey teal-green circle.
   - Blue product → pale grey-beige base + grey terracotta or sand-brown circle.
3. **Low-saturation analogous color** — Use a neighboring hue with consistent temperature and gentle separation. Best for food, home, apparel, personal care, and everyday goods.
   - Yellow product → cream base + pale apricot or grey-orange circle.
   - Teal product → mist-blue base + pale grey-green circle.
4. **Neutral base plus low-lightness support** — Use warm white, light grey, beige, or stone with a small charcoal-grey, coffee-grey, deep blue-grey, dark green-grey, or grey-brown circle. Best for white, silver, glass, transparent, or low-edge-clarity products.

### Selection priority

Stop after the first matching condition:

1. White, pale grey, transparent, glass, silver, or reflective product → neutral base plus low-lightness support.
2. Weak silhouette separation or highly saturated dominant hue → greyed complementary contrast.
3. Strong brand hue with already-clear edges → same-hue lightness contrast.
4. Food, home, apparel, personal care, or everyday product needing warmth → low-saturation analogous color.
5. Multicolor product → select the largest or most brand-critical dominant hue, then retain only one quiet secondary hue; keep the rest neutral.

## Product-to-background rules

- **Dark product:** light warm white, pale grey, beige-grey, or light same-hue base; circle darker than the base, lighter and greyer than the product.
- **White or pale-grey product:** never use equal-lightness pure white. Use mushroom grey, grey-beige, mist blue-grey, sage grey, or pale terracotta, with a clear lightness step at the brightest edge.
- **Highly saturated product:** keep it as the only saturation peak. Use a greyed same-hue or greyed complement; do not repeat the bright product color across the background.
- **Warm product:** for separation use cool grey, grey teal-green, or mist blue-grey; for unity use cream, sand, pale apricot, or pale terracotta.
- **Cool product:** for separation use warm grey, pale beige, oat, grey apricot, or pale terracotta; for unity use very pale blue-grey, grey teal, or pale green-grey.
- **Metal:** use stone, grey-beige, cool white, or mist grey and separate through temperature. Preserve real gold or rose-gold highlights; add no gold aura or black-gold stage.
- **Glass, transparent, reflective:** provide mild temperature and lightness contrast plus a real contact shadow. Avoid outline, white glow, radial flare, and repeated reflection texture.
- **Suede, leather, matte:** use large soft color areas, mild temperature contrast, and soft side light; do not imitate the material with background texture.
- **Multicolor packaging:** extract one quiet, low-saturation secondary hue for the circle. Do not reproduce all package colors, stripes, or patterns.

## Background combination library

Hex values clarify direction and should be adjusted to the actual product exposure. “Support” always means the single complete flat `1:1` circle.

| Product color | Unified/soft option | Separation option | Text/accent | Guardrail |
|---|---|---|---|---|
| Pure or ivory white | Mushroom `#E8E3DA` + warm beige-grey `#CFC6B8` | Mist blue-grey `#DDE4E6` + blue-grey `#A9B7BC` | Charcoal `#292927` | Never use raw white. |
| Cream or pale beige | Oat `#EFE5D5` + sand beige `#D5C0A4` | Pale grey-green `#E1E6DF` + sage `#A8B3A3` | Deep coffee-grey `#403831` | Preserve a clear edge step. |
| Light or mid grey | Warm white `#F5F1E9` + mushroom `#BDB5AA` | Pale grey-pink `#EFE4E3` + dusty rose `#C5A2A3` | Near-black `#242424` | Use temperature contrast. |
| Black or charcoal | Bone `#F2EEE5` + warm grey `#C8BFB2` | Pale blue-grey `#E0E6E8` + blue-grey `#9EADB3` | Black + tiny product accent | Never use a full black ground. |
| Silver or gunmetal | Cool white `#F0F2F1` + stone `#C5C9C6` | Warm beige-grey `#ECE5D9` + grey-brown `#B5A38D` | Graphite `#303332` | No metallic glow. |
| Deep brown | Cream `#F4EBDD` + caramel-grey `#C29E7D` | Mist blue-grey `#DDE4E4` + grey teal `#9EAFAC` | Deep coffee `#3A2D26` | Cool grey can reduce heaviness. |
| Camel or khaki | Oat `#F0E5D3` + sand brown `#CDB18D` | Pale blue-grey `#E1E7E8` + blue-grey `#A8B8BD` | Coffee-grey `#463B32` | Avoid an all-yellow cast. |
| Bright red | Warm white `#F7F0E8` + pale grey-red `#D8AAA5` | Pale grey-green `#E3E8DF` + grey teal-green `#9EAF9C` | Deep red `#7C2425` | Avoid festive red-green clash. |
| Burgundy | Pale grey-pink `#F0E1E0` + dusty rose `#C69799` | Warm beige-grey `#EEE7DB` + grey teal-green `#A5B0A0` | Burgundy `#692D35` | Gold only as a tiny accent. |
| Pink | Warm white `#F7F0EA` + dusty pink `#D8B8B6` | Pale grey-green `#E2E8E1` + sage `#AAB5A6` | Berry-grey `#713E4D` | Lower background saturation. |
| Coral | Pale apricot `#F5E5D9` + grey coral `#D2A092` | Mist teal `#DDE8E6` + grey blue-green `#9CB7B3` | Deep brown-grey `#493936` | Avoid bright cyan-coral clash. |
| Orange | Cream `#F5E9D7` + pale grey-orange `#D8AF82` | Mist blue-grey `#DCE6E9` + grey blue `#9FB3BC` | Charcoal | Product remains saturation peak. |
| Yellow | Ivory `#F6F0DB` + grey apricot `#D8C496` | Pale blue-grey `#E1E8EB` + grey violet-blue `#A9AFC0` | Deep grey `#30302C` | Do not repeat vivid yellow. |
| Gold or champagne | Warm white `#F3EDE3` + champagne beige `#CCB99D` | Stone `#E2E1DD` + charcoal brown `#777068` | Deep coffee-black `#312C28` | No aura or luxury stage. |
| Green | Very pale green-grey `#E7EBE3` + sage `#AAB69F` | Warm grey-pink `#EFE2DF` + grey terracotta `#C39D91` | Deep green `#29483A` | Complement must be greyed. |
| Forest green | Oat `#EEE5D6` + grey olive `#AAA68B` | Pale grey-pink `#EEE2E2` + dusty rose `#BF9FA1` | Forest `#203E32` | Keep the base light. |
| Olive | Sand beige `#EEE3CF` + khaki grey-green `#B2AE8F` | Grey mauve `#E8E0E5` + muted mauve `#B3A0AD` | Deep olive `#454734` | No outdoor scene. |
| Mint or sage | Warm white `#F4F0E7` + pale green-grey `#BCC9BA` | Pale apricot `#F0E2D4` + grey apricot `#D1AE91` | Deep green-grey `#405247` | Circle one step darker. |
| Teal | Mist blue `#E1E9E9` + grey teal `#9CB7B4` | Pale terracotta `#EEE0D8` + grey orange-brown `#C49C86` | Deep teal `#28505A` | Avoid travel-poster blue-orange. |
| Pale blue | Cool white `#F1F3F1` + mist blue-grey `#AFC3CC` | Pale beige-apricot `#F1E6D6` + grey terracotta `#C4A18C` | Deep blue-grey `#334B57` | A warmer base can sharpen edges. |
| Royal blue | Pale blue-grey `#E1E7EC` + grey blue `#9CABBF` | Warm beige-grey `#EEE5D8` + pale grey-orange `#C6A58B` | Navy `#233A59` | Never copy royal-blue saturation. |
| Navy | Warm white `#F3EEE5` + sand grey `#CEC0AC` | Pale grey-apricot `#EEE3D4` + grey terracotta `#BE9B86` | Navy `#233246` | Warm light base reduces heaviness. |
| Purple | Pale grey-violet `#E9E4EC` + muted violet `#B1A4B8` | Pale yellow-beige `#F1E9D2` + grey olive `#B3AD8E` | Deep violet-grey `#4B3A55` | Complement becomes beige/olive. |
| Lavender | Cool white `#F2F1F3` + pale grey-violet `#C5BCCF` | Pale grey-green `#E4E8DF` + sage `#AAB39E` | Deep grey-violet `#51495B` | Use a darker support step. |
| Fluorescent/high saturation | Neutral white `#F2F1EC` + greyed same hue | Pale neutral grey `#E5E5E2` + greyed near-complement | Charcoal + product accent | No second fluorescent hue. |
| Glass/transparent | Mist blue-grey `#DDE4E7` + blue-grey `#A7B5BC` | Warm beige-grey `#E8E1D6` + coffee-grey `#AA9E8E` | Deep grey `#303536` | Use lightness, temperature, shadow. |
| Iridescent/rainbow | Neutral cool white `#EFEFEE` + one mist grey `#C2C7C8` | Warm grey `#ECE6DD` + one grey violet/blue | Near-black | Never repeat rainbow color shifts. |
| Multicolor packaging | Warm white `#F3F1EB` + one greyed secondary hue | Beige-grey `#E9E4DB` + one greyed complement | Darkest package neutral | Extract one support hue only. |

## Contrast checks

- At thumbnail size, the product must remain the first visual entry. If the circle appears first, reduce its saturation, size, or boundary contrast.
- In grayscale, identity-critical edges must remain separate from adjacent background.
- Not every edge needs high contrast, but logo, opening, handle, button, wheel, sole, cap, and other identity structures must be clear.
- The copy background must be quieter than the support area. Never place a headline across the circle boundary.
- Correction order is fixed: `base lightness → temperature → uniform circle resize → circle move → slightly stronger contact shadow`.

## Reusable background prompt

```text
First analyze the reference product: dominant hue [fill], secondary hue [fill], overall lightness [light/mid/dark], highest-saturation area [fill], material reflectance [matte/suede/plastic/metal/glass/pearl], and the edge most likely to disappear [fill]. The product must retain the highest color recognizability, clearest identity structures, and strongest local light-dark organization.

Keep the background abstract and spacious; it must not become a room, tabletop, stage, horizon, or photographic environment. Use exactly one color path: [same-hue lightness contrast / greyed complementary / low-saturation analogous / neutral base plus low-lightness support]. Use [specific color and approximate hex] as a continuous base covering about 65–80%. Behind the product place exactly one complete flat two-dimensional standard circle in [support color and hex], covering about 12–28%, only to separate [specific edge] or balance visual mass. If the circle is dark, limit it to 8–18%. Add no transition field, second block, orbit, node, line, or other geometry.

The circle’s width and height are strictly equal, its aspect ratio is exactly 1:1, every radius is equal, and its full closed circumference stays inside the canvas. Its diameter is 75–95% of the product-zone width. Align its center to [main product mass] and, only if necessary, offset it [direction] by 3–8% of the product-zone width. Adapt only through uniform diameter changes and planar movement. Never stretch, squash, rotate, perspective-transform, mask, crop, or deform it.

Use a uniform solid two-dimensional fill with no gradient, flare, texture, outline, shadow, inner shadow, volumetric light, highlight, thickness, or glow. Place the product in front; it may occlude the middle and extend 5–18% beyond the circumference. Product occlusion does not mean geometric cropping: the underlying circle remains complete. Keep key structures away from the tangent and the circle out of the text-safe zone.

Preserve 35–50% continuous quiet area. If edge separation is weak, correct only by adjusting background lightness, temperature, uniformly resizing the circle, moving the circle, or slightly strengthening the contact shadow.

Exclude ellipses, semicircles, arches, rounded rectangles, capsules, sectors, curved bands, irregular curves, freeform fields, gradient spots, spheres, glass balls, glowing discs, radial gradients, halos, concentric circles, orbits, scan rings, nodes, tick marks, dashboards, photographic textures, and recognizable scenes.
```

## Product image and lighting

- Use a clear front, three-quarter, or category-natural angle. Preserve the source silhouette, proportions, orientation, color, material, brand, and structure.
- Use soft diffuse light, slight rim separation, and a realistic contact shadow.
- Avoid mirror-like glare, heavy vignette, dramatic spotlight, exaggerated perspective, motion, or unsupported structure changes.
- Add no people, hands, rooms, furniture, plants, windows, streets, landscapes, tabletop props, or narrative action.
- If truly necessary, allow one small material detail, swatch, or close-up occupying no more than `8–15%`.

## Dense-information adaptation

Keep all required information within the same design system:

- one headline and one shared alignment axis;
- selling points combined into one compact list;
- price, date, offer, and CTA combined into one lower group;
- reduce secondary type and decoration before reducing product size;
- no parameter wall, badge cluster, explosion sticker, or multiple competing headlines.

## Generation prompt template

```text
Create a [aspect ratio] ecommerce poster for [product name] using the unified clean whitespace product layout. [Product] is the only subject. Preserve the reference silhouette, proportions, orientation, colors, package copy, brand mark, materials, and key structures exactly. Do not change product identity or add substitutes. Show the complete product at 40–60% of canvas area; for a tall product use 58–80% of canvas height, and for a wide product use 55–72% of canvas width.

Use [copy left/product right / copy right/product left / copy above/product below]. Copy occupies 28–38%, product 45–60%; keep the zones fully separate, outer margin 6–9%, copy-to-product clearance 4–6%, and continuous visible whitespace 35–50%.

Read the product first: dominant hue [fill], secondary hue [fill], overall lightness [fill], saturation peak [fill], material [fill], vulnerable edge [fill]. Choose exactly one path [same-hue / greyed complement / low-saturation analogous / neutral plus low-lightness support] because [unity / edge separation / warmth / pale or reflective edge clarity].

Use [base color and hex] over 65–80% of the background. Behind the product place exactly one [support color and hex] complete standard flat two-dimensional circle covering 12–28%; if dark, limit it to 8–18%. The geometry order is continuous base → single complete circle → product → realistic contact shadow. Add no second block, transition field, orbit, node, or other geometry.

The circle width and height are equal, aspect ratio exactly 1:1, all radii equal, full circumference closed and entirely inside the canvas. Diameter is 75–95% of product-zone width, center aligned to [main mass], optional offset [direction] by 3–8%. Adapt only by uniform scaling or planar movement. No stretching, squashing, perspective, tilt, crop, mask, or deformation.

Use uniform solid fill with no gradient, light spot, texture, outline, shadow, inner shadow, highlight, volume, thickness, or glow. Place the product in front; it may cover the middle and extend 5–18% beyond the circumference. Keep key structures away from the tangent and keep the circle out of the text-safe zone.

Place exact copy in the quiet base area: [verbatim required copy]. Use one modern sans-serif family, Semibold 600–700 headline and Regular/Medium 400–550 supporting type, left aligned on one axis. Relative sizes approximately 1 : 0.42 : 0.26. Use near-black or deep grey with at most one tiny muted accent.

Use soft diffuse light, slight rim separation, and a realistic contact shadow. The result is approachable, clear, natural, modern, and restrained, with the product seen before the copy.

After generation, verify: the product remains first at thumbnail size; key edges separate in grayscale; there is exactly one complete flat 1:1 circle; the entire circumference is inside the canvas; no alternate shape or second block appears; the headline does not cross the circle.
```

## Negative constraints

```text
lifestyle scene, people, hands, blurred person background, room, furniture, plants, window view, street, outdoor landscape, real tabletop, props, full-frame photographic background, shallow-depth environment, narrative action, substitute products, altered silhouette, altered proportions, altered color or material, changed logo or structure, copy over product, copy touching product, multiple headlines, scattered copy, more than two font families, product too small, product cropped, dead white background, flat single-color background without hierarchy, high-saturation background, multiple bright blocks, multiple competing hues, vivid complementary clash, rainbow gradient, neon glow, support color more saturated than product, second background block, transition block, ellipse, semicircle, partial arc, broken circle, arch, rounded rectangle, capsule, sector, curved band, irregular curve, freeform block, gradient spot, stretched circle, flattened circle, perspective circle, tilted circle, cropped circle, masked circle, distorted circle, sphere, glass ball, thick disc, glowing disc, radial gradient, halo, concentric circles, orbit, scan ring, node, ticks, dashboard, calligraphy, handwriting, decorative serif, outlined type, 3D type, metallic type, multiple shadows, explosion sticker, badge cluster, parameter wall, floating product, luxury showroom, dramatic spotlight, heavy vignette, strong diagonal, rotation, speed lines, exaggerated perspective
```

## Final checklist

1. Is it the same product, with identity structures, colors, materials, and brand preserved?
2. Is the product the first visual entry, complete, and within the recommended size range?
3. Are product and copy zones fully separate with sufficient clearance and continuous whitespace?
4. Is there one font system, one alignment axis, and a restrained hierarchy?
5. Does the background use one coherent color path rather than dead white, noise, or a scene?
6. Is there exactly one complete standard flat solid `1:1` circle behind the product, entirely inside the canvas and undeformed?
7. Are all substitute shapes, second blocks, orbits, and nodes absent?
8. Are people, lifestyle scenes, props, promotional collage, and parameter dashboards absent?
9. Are all required words, numbers, dates, units, prices, and marks exact?

If any answer is no, correct that variable directly. Never add a scene, decoration, or new visual style as a workaround.
