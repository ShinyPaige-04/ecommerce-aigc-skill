---
name: ecommerce-aigc
description: Create e-commerce posters, banners, product heroes, visual directions, and image-generation prompts exclusively in a consistent whitespace product layout. Use when a product must remain dominant through clean product-copy separation, restrained sans-serif typography, and a product-adaptive background with exactly one complete flat 1:1 circle behind the product rather than a lifestyle scene or dead white canvas; do not use for copywriting-only requests unrelated to visual design.
---

# Ecommerce AIGC

Create e-commerce visuals in one unified style: a clean whitespace product layout. Apply this style to every product and category. Do not select, blend, score, or mention alternative style regions.

> Chinese entrypoint: [SKILL.zh-CN.md](SKILL.zh-CN.md). Chinese visual-language reference: [references/region-visual-language.zh-CN.md](references/region-visual-language.zh-CN.md).

## Unified style invariant

Every output must use all of the following:

- a light, low-interference layered background whose hue, lightness, and temperature are derived from the product rather than defaulted to pure white;
- one complete, medium-to-large product as the first visual entry;
- a separate text zone that never covers the product;
- one modern sans-serif family with a restrained hierarchy;
- one background color path, consisting of one base neutral or pale hue plus exactly one supporting hue rendered as a complete flat 1:1 circle behind the product;
- soft diffuse lighting, subtle rim separation, and a realistic contact shadow;
- no people, hands, rooms, furniture, plants, outdoor scenery, photographic environment, or narrative lifestyle scene.

Read [references/region-visual-language.md](references/region-visual-language.md) whenever planning, prompting, generating, or reviewing a visual. It is the only visual-language reference for this skill.

## Supported modes

Choose the smallest mode that fulfills the request. Combine modes when useful.

### Direct

Turn product information, assets, campaign goals, required copy, channel, and format into a production-ready whitespace-product visual direction.

### Prompt

Convert the direction into a structured image-generation prompt. Describe product preservation, proportions, layout regions, background, typography, information grouping, lighting, and exclusions.

### Generate

When the user requests an actual visual, use the available image-generation capability. Do not stop at a prompt.

### Review

Check whether a result follows the unified layout. Identify the largest mismatch first and revise only the variables causing it.

## Input handling

Use supplied product images, logos, verified claims, prices, dates, required copy, brand colors, audience, channel, aspect ratio, and prohibited elements.

- Treat the product image as the visual source of truth. Preserve its silhouette, proportions, orientation, colors, materials, logo, packaging text, and structural details.
- Never invent prices, discounts, certifications, test results, ingredients, specifications, endorsements, logos, or claims.
- Preserve required wording, numbers, units, currency symbols, dates, punctuation, and capitalization exactly.
- Do not block concepting because optional inputs are missing. Use conservative assumptions and label them briefly.
- Ask only when a missing input materially prevents completion, such as an absent product image that must be preserved exactly.

## Workflow

### 1. Parse the brief

Identify the product, required assets and copy, verified selling points, campaign objective, audience, channel, aspect ratio, language versions, and prohibited content.

### 2. Lock product identity

Before styling, list the product features that must not change. Give product preservation higher priority than background, typography, decoration, or atmosphere.

If exact product fidelity matters, prefer compositing the original transparent product asset into the layout. Image generation may reconstruct small labels, logos, seams, and mechanisms.

### 3. Apply the unified layout

Use the reference to set:

- product and text zones;
- product scale and safety margins;
- continuous whitespace;
- exactly one complete, standard, flat 1:1 circle behind the product;
- typography hierarchy and shared alignment;
- information grouping;
- soft grounding light and shadow.

Do not adapt the poster into a lifestyle photograph, luxury still life, energetic promotional collage, or technical dashboard, even when the product category commonly uses those styles.

### 4. Resolve background and color

Analyze the product before naming colors. Record its dominant hue, secondary hue, lightness range, saturation peak, material reflectance, and edge clarity. Then choose exactly one path from the reference:

1. same-hue lightness contrast;
2. greyed complementary or near-complementary contrast;
3. low-saturation analogous color;
4. neutral base with a small low-lightness supporting field.

Build the background only as `continuous base color → exactly one complete flat 1:1 circle → product → realistic contact shadow`. Specify the base and circle colors, approximate hex values when useful, coverage, diameter, center position, overlap, and separation purpose. Keep the base at roughly `65–80%`, the circle at `12–28%`, and a darker low-saturation circle within `8–18%`. Preserve `35–50%` continuous quiet space. Do not add a transition shape, second color block, orbit, node, line decoration, or additional background geometry.

The circle must be a mathematically standard two-dimensional circle: width equals height, aspect ratio is exactly `1:1`, and every radius from the center is equal. Keep the full closed circumference inside the canvas. Use uniform solid fill with no gradient, texture, outline, shadow, inner shadow, highlight, depth, perspective, or glow. It must not read as a sphere, disc, hole, window, planet, platform, or spatial device.

Center the circle on the product's main visual mass, then offset its center only `3–8%` of the product-zone width toward the quieter side when needed. Set the circle diameter to roughly `75–95%` of the product-zone width. Adapt to every product shape only by changing the circle's diameter and center position; never change width and height independently, stretch, squash, tilt, crop, mask, or distort the circle.

Place the product in front so it may occlude the circle's middle and extend `5–18%` beyond the circumference. Occlusion by the product does not permit geometric cropping: the underlying circle must still be complete. Keep identity-critical structures away from the circumference tangent, and keep the circle fully outside the text-safe zone. Explicitly forbid ellipses, semicircles, arches, rounded rectangles, capsules, sectors, curved bands, irregular curves, freeform fields, gradient spots, spheres, glowing discs, concentric circles, orbits, scan rings, and nodes.

When the product edge loses separation, correct in this order: adjust the adjacent background lightness; shift its color temperature; reposition or resize the support field; strengthen the natural contact shadow slightly. Do not solve separation with an outline, glow, hard halo, saturated clash, or extra color family.

Use the combination library in the reference as a decision aid, not a fixed palette. The source product remains authoritative; adapt the suggested colors to its actual hue and exposure.

### 5. Fit required information without changing style

Required content is authoritative. When information is dense:

- keep one headline and one shared text axis;
- combine selling points into one compact list instead of separate cards;
- group price, date, and CTA into one lower information block;
- reduce secondary type before shrinking the product;
- do not introduce a second layout system, extra font family, parameter wall, or badge cluster.

### 6. Build the generation prompt

Write prompts in descending priority:

1. deliverable and aspect ratio;
2. product identity and preservation requirements;
3. product size, orientation, and placement;
4. text zone and exact copy;
5. chosen color path and complete background specification: base color, the single circle color, strict `1:1` width-height equality, full uncropped circumference, circle diameter, center position, product overlap, coverage, text-zone separation, and edge-separation purpose;
6. typography family, weight, alignment, and relative hierarchy;
7. lighting, materials, and contact shadow;
8. explicit scene and decoration exclusions.

### 7. Handle on-image text

- Keep display copy short when exact raster text rendering is not guaranteed.
- Reserve a complete text-safe area separate from the product.
- Use supplied copy verbatim and do not silently rewrite it.
- If critical text is inaccurate, regenerate or recommend a separate typesetting pass.
- For multiple language versions, create separate outputs and preserve the complete language-specific copy in each.

### 8. Review the result

Check in this order:

1. product identity and required logo or packaging details;
2. required text, numbers, dates, and language;
3. product as first visual entry;
4. separation between product and text;
5. product-edge separation from the adjacent background, including a quick grayscale check;
6. one coherent background color path with no dead white, competing hue, scene cue, or decorative color noise;
7. exactly one complete flat standard circle behind the product, with width equal to height, a true `1:1` ratio, full circumference inside the canvas, and no stretch, squash, crop, mask, perspective, or deformation;
8. no second background shape, transition field, orbit, node, ellipse, semicircle, arch, rounded rectangle, capsule, sector, curved band, irregular curve, gradient spot, sphere, or glowing disc;
9. typography hierarchy and legibility;
10. unsupported claims, extra objects, artifacts, or malformed text.

Revise the largest mismatch first. Do not reset the style or add a scene to solve a layout problem.

## Default response format

Adapt detail to the request. For a full visual direction, use:

```yaml
creative_direction:
  objective: ""
  visual_entry: "product"
  composition: "whitespace product layout"
  product_scale: ""
  typography: ""
  background_palette:
    product_color_read: ""
    selected_path: ""
    base_color: ""
    circle_color: ""
    circle_geometry: "complete flat standard circle; width equals height; exact 1:1 ratio"
    circle_diameter: "75–95% of product-zone width"
    circle_center_position: "align to main visual mass; optional 3–8% offset"
    product_circle_overlap: "product in front; may extend 5–18% beyond circumference"
    circle_integrity_check: "single circle, full circumference inside canvas, uncropped and undeformed"
    edge_separation_strategy: ""
    quiet_space: "35–50% continuous area"
  information_hierarchy: ""
  lighting: ""
  text_safe_area: ""
generation_prompt: ""
negative_constraints:
  - ""
assumptions:
  - ""
```

Omit irrelevant sections for small requests. Do not output style-region labels or four-dimensional style scores.

## Quality bar

A successful result should:

- be immediately recognizable as the same whitespace-product design system across different categories;
- preserve product identity and all mandatory information;
- keep the product visually dominant without crowding the canvas;
- use simple, readable, consistently aligned typography;
- adapt color to the product through one explicit, internally consistent background path while keeping the background subordinate;
- remain executable by an image-generation model or visual designer;
- contain no lifestyle scene or competing visual grammar.
