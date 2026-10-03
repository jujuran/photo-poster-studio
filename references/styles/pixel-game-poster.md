# Pixel Game Poster

## Intent

Rebuild one photograph as deliberate pixel art rather than applying a low-resolution filter. Preserve the subject's recognizable silhouette, face anchors, pose, clothing colors, important objects, and scene relationship on a hard pixel grid.

## Choose a substyle

- `8-bit`: Use large pixels, simple silhouettes, and roughly 8–24 visible colors for an early arcade or handheld feel.
- `16-bit`: Use this default when no substyle is named. Allow roughly 24–64 colors, richer shading, and more facial or material detail.
- `isometric`: Rebuild the scene as a compact 2:1 isometric environment. Use a 1:1 canvas when requested; otherwise keep the 4:5 poster format.
- `rpg-ui`: Place the pixel subject inside an original role-playing interface with one portrait or scene window and a few readable status elements. Do not imitate a specific game's interface.

## Format and composition

- Use a strict 4:5 vertical canvas except for a user-requested 1:1 isometric scene.
- Render with square, consistently sized pixel blocks and hard nearest-neighbor edges.
- Use no anti-aliasing, subpixel blur, vector-smooth curves, painterly blending, or depth-of-field blur.
- Build forms through clustered pixels, stepped diagonals, controlled dithering, and a limited palette derived from the source.
- Keep the main subject large enough to recognize. Do not reduce a face to unreadable noise merely to appear retro.
- Simplify the environment without replacing it with an unrelated fantasy world.

## Typography and interface

- Use a short user-provided title when available. Otherwise use a neutral visible-subject label or omit text.
- Use one readable bitmap type family and keep letters on the same pixel grid.
- In `rpg-ui`, use only visually supported or clearly fictional neutral labels. Never invent real names, statistics, locations, dates, affiliations, or game logos.
- Do not include copyrighted characters, franchise marks, console branding, or a recognizable existing game's UI unless the user supplies authorized material and explicitly requests it.

## Acceptance checks

- Pixel blocks remain crisp at every edge, with no smoothing or mixed-resolution patches.
- The chosen substyle is visually clear and uses a restrained palette.
- The source subject and important objects remain recognizable.
- Text is readable pixel lettering rather than garbled decorative marks.
- The result is one flat poster or scene, not a device mockup or screenshot frame.

## Avoid

Blurred upscaling, anti-aliased edges, random mosaic filters, voxel 3D, inconsistent pixel sizes, full-spectrum gradients, illegible UI text, copied game interfaces, copyrighted sprites, unrelated fantasy props, and duplicate faces.
