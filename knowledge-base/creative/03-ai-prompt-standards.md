# AI Prompt Standards for Ruka Creative Work

## 1. Prompt structure

A reliable prompt should state, in this order:
1. **Task:** create, edit, clean, convert, mock up, extend, or isolate.
2. **Reference roles:** which image is the base, style reference, or replacement.
3. **Preservation rules:** what must remain exactly the same.
4. **Requested changes:** the only attributes allowed to change.
5. **Composition:** angle, framing, perspective, subject placement.
6. **Output:** aspect ratio, pixel dimensions, file format, transparency, and intended use.
7. **Quality controls:** edge quality, detail fidelity, lighting, and artifact avoidance.

## 2. Strict preservation language

Use when the user wants an existing design retained:
- “Use the uploaded image as the absolute visual reference.”
- “Preserve the original design, silhouette, geometry, proportions, composition, spacing, colors, and all existing details.”
- “Do not redesign, reinterpret, simplify, add, remove, or relocate any element.”
- “Change only the specifically requested element; keep everything else unchanged.”

Do not use strict preservation language when the user explicitly requests a new design, a different silhouette, or a style adaptation. In those cases, define which characteristics should be preserved and which should change.

## 3. Vector-cleanup prompt checklist

Include:
- Smooth continuous vector-like contours.
- Consistent stroke width and clean joins.
- Controlled Bézier curves.
- Crisp solid fills and sharp edges.
- No jagged edges, rough nodes, bumps, dents, kinks, wobble, pixelation, or staircase artifacts.
- No unintended shadows, gradients, textures, or extra details.
- Preserve source geometry and colors.

If the target is Image Trace, explain that contours should be simple and clean enough to avoid unnecessary trace nodes. Do not claim the generated image is a native vector path unless an actual vector file is produced.

## 4. Mockup prompt checklist

Specify:
- Exact product type and shape.
- Which uploaded image supplies the artwork.
- Whether artwork must be identical on front and back.
- Material, size, closure/lid, and construction.
- Required angles and human interaction, if any.
- Scene, lighting, and background.
- Explicit exclusions.

## 5. Image output checklist

Specify output requirements explicitly:
- Aspect ratio (e.g. 4:5 or 1080:1350).
- Pixel dimensions or resolution target.
- Transparent background when needed.
- PNG or other required format.
- Isolated subject versus full scene.
- Intended destination: social post, mockup, large print, or vector tracing.

## 6. Prompt quality rule

Avoid contradictory instructions. For example:
- “Keep everything identical” conflicts with “change the silhouette.”
- “Transparent background” conflicts with a request for a fully styled tabletop scene.
- “No extra objects” conflicts with requesting a bowl, cutlery, and props.

Resolve conflicts by stating the exact preservation boundary and the exact permitted change.
