---
name: photo-poster-studio
description: Turn supplied photographs into separate art-directed posters using a catalog of editorial, cinematic, modernist, print, paper-craft, and archival styles. Use for photo-to-poster transformations, editorial covers, exhibition graphics, keepsake posters, or reusable visual treatments; do not use for ordinary photo retouching or multi-photo collages unless a selected style explicitly permits them.
---

# Photo Poster Studio

Turn every source photograph into its own finished poster using a selected style from the style catalog. Never blend rules from different styles unless the user explicitly requests a hybrid.

## Choose a style

Use the style named by the user. If no style is named, recommend one style when the subject and intended mood make the choice clear. State the recommendation in one sentence and proceed. If two or more styles fit equally well, present no more than three relevant options and ask the user to choose. If the user says to decide for them, choose the best match without asking again.

Match styles using these signals:

- Quiet, poetic, publication-led, or strong negative space: `quiet-editorial-split`
- Film-like, dramatic, travel, street, landscape, or emotional portrait: `cinematic-story-poster`
- Graphic, architectural, fashion, product, brand, or information-led: `swiss-photo-grid`
- Energetic, musical, youthful, event-led, or deliberately retro: `risograph-pulse`
- Warm, personal, family, pet, food, craft, or travel-journal: `paper-cut-diary`
- Exhibition, artwork, object study, historical, documentary, or archival: `museum-archive`

Available styles:

- `quiet-editorial-split`: A strict 3:4 vertical poster with a faithful photograph in the top half and a small, minimal handmade paper illustration in the bottom half. Pass [references/styles/quiet-editorial-split.md](references/styles/quiet-editorial-split.md) to the image tool verbatim. Do not rewrite, summarize, expand, translate, or remove any wording.
- `cinematic-story-poster`: A 2:3 film-poster treatment that preserves identity while using cinematic grading, atmospheric depth, and restrained title-card typography. Read [references/styles/cinematic-story-poster.md](references/styles/cinematic-story-poster.md).
- `swiss-photo-grid`: A 4:5 modernist poster built from one photograph, asymmetric grid logic, bold geometric fields, and disciplined sans-serif typography. Read [references/styles/swiss-photo-grid.md](references/styles/swiss-photo-grid.md).
- `risograph-pulse`: A 3:4 high-energy print poster using two or three inks, coarse halftones, paper grain, and controlled registration drift. Read [references/styles/risograph-pulse.md](references/styles/risograph-pulse.md).
- `paper-cut-diary`: A 4:5 tactile keepsake poster combining a faithful photo window with paper-cut shapes, tape, handwritten micro-notes, and warm negative space. Read [references/styles/paper-cut-diary.md](references/styles/paper-cut-diary.md).
- `museum-archive`: A 3:4 exhibition poster that treats the photograph as a catalogued artifact with generous margins, quiet labeling, and archival restraint. Read [references/styles/museum-archive.md](references/styles/museum-archive.md).

## Shared workflow

1. Identify the source photographs and keep their order. Unless the selected style says otherwise, the expected output count equals the source-photo count.
2. Inspect every photograph before editing. Record only visually supported details: main subject, pose, important objects, spatial relationships, dominant colors, lighting, and environmental cues. Do not invent names, places, dates, or narrative facts.
3. Read only the reference for the selected style. When the catalog marks it as verbatim, pass the reference text unchanged; otherwise compose a photograph-specific editing prompt from its rules. Treat the style's default aspect ratio as authoritative unless its reference explicitly allows alternatives.
4. Process each photograph independently with the available image-generation or image-editing tool. Supply exactly one source photograph per generation unless the selected style explicitly requires more. Ask for one flat poster image, not a contact sheet, product mockup, or presentation scene.
5. Never invent factual title text. Use user-provided wording when available. Otherwise use neutral, visibly supported text or omit optional copy. Do not fabricate names, dates, locations, brands, credits, or event details.
6. Verify every output using the selected style's acceptance checks. If one output clearly fails a structural requirement, retry only that poster with a concise correction naming the failure.
7. Return successful posters as separate images labeled by source order or original filename. Do not merge them for presentation.

If a referenced photograph is unavailable, ask the user to attach it again rather than reconstructing it from description alone.

## Adding styles

Keep each substantial style in its own file under `references/styles/`. Add one concise catalog entry above describing its distinguishing visual structure and linking to the file. Put shared behavior here and style-specific composition, palette, typography, and exclusions in the style file. Avoid duplicating an existing style under a new name when a small optional variation would suffice.
