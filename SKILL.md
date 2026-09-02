---
name: photo-poster-studio
description: Create one separate art-directed poster from each supplied photograph using a named visual style. Use for photo-to-poster transformations, editorial covers, or reusable poster-style treatments; do not use for collages unless a selected style explicitly requires one.
---

# Photo Poster Studio

Turn every source photograph into its own finished poster using a selected style from the style catalog. Never blend rules from different styles unless the user explicitly requests a hybrid.

## Choose a style

Use the style named by the user. If no style is named and the request matches one catalog entry clearly, use that entry. Otherwise present the available styles briefly and ask the user to choose.

Available styles:

- `quiet-editorial-split`: A strict 3:4 vertical poster with a faithful photograph in the top half and a small, minimal handmade paper illustration in the bottom half. Pass [references/styles/quiet-editorial-split.md](references/styles/quiet-editorial-split.md) to the image tool verbatim. Do not rewrite, summarize, expand, translate, or remove any wording.

## Shared workflow

1. Identify the source photographs and keep their order. Unless the selected style says otherwise, the expected output count equals the source-photo count.
2. Inspect every photograph before editing. Record only visually supported details: main subject, pose, important objects, spatial relationships, dominant colors, lighting, and environmental cues. Do not invent names, places, dates, or narrative facts.
3. Read only the reference for the selected style. When the catalog marks it as verbatim, pass the reference text unchanged; otherwise compose a photograph-specific editing prompt from its rules.
4. Process each photograph independently with the available image-generation or image-editing tool. Supply exactly one source photograph per generation unless the selected style explicitly requires more. Ask for one flat poster image, not a contact sheet, product mockup, or presentation scene.
5. Verify every output using the selected style's acceptance checks. If one output clearly fails a structural requirement, retry only that poster with a concise correction naming the failure.
6. Return successful posters as separate images labeled by source order or original filename. Do not merge them for presentation.

If a referenced photograph is unavailable, ask the user to attach it again rather than reconstructing it from description alone.

## Adding styles

Keep each substantial style in its own file under `references/styles/`. Add one concise catalog entry above describing its distinguishing visual structure and linking to the file. Put shared behavior here and style-specific composition, palette, typography, and exclusions in the style file. Avoid duplicating an existing style under a new name when a small optional variation would suffice.
