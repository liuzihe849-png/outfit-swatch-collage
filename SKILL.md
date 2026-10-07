---
name: outfit-swatch-collage
description: Turn a real outfit or lifestyle photograph into a swatch-card editorial collage, extracting visible colors and patterns into white labeled cards that are partially occluded by the original subject. Use for fashion palette and pattern photo compositions, not music-player or generic scrapbook effects.
---

# Outfit Swatch Collage

Keep the supplied photo full bleed and photographic. Translate its actual clothing, accessories and held-object colors/patterns into a small set of graphic swatch cards. Read [references/style-and-layering.md](references/style-and-layering.md) for the supplied reference's visual logic.

## Fresh-chat reference loading

Before production, read [fresh-chat visual contract](references/fresh-chat-visual-contract.md), inspect the bundled visual reference. For a generative preview, pass it together with the new user source to the image-generation call; for deterministic production, follow the bundled composition/script route and preserve source pixels. Do not assume earlier chat images are visible to the generator. Use this package as the style source; treat custom fields and occlusion choices as per-photo inputs.

## Inputs and analysis
Identify the raw source photo separately from a finished style reference. Preserve face, body, pose, garments, jewelry, props and architecture. Do not transplant the reference person's lifted leg or items into a new photo.
Before making an image, list the candidate swatches and their source objects. Use two or three when supported by the source, rather than inventing three colors. Select distinct colors/patterns that express the outfit, often a dominant pattern, a lighter supporting color and a small strong accent. Not every garment needs a card.

The approved style includes graphic motifs, not an all-solid palette. Include stripes and/or simple geometric shapes in at least two cards when making the default three-card composition; a third card may remain solid for contrast. If the source has an actual pattern, reconstruct it faithfully. For plain garments, build a clearly decorative graphic abstraction from their colors and material rhythm (for example knit-inspired parallel stripes or trouser-pleat-inspired broad bands); do not claim those graphics are printed on the original clothing and do not add them to the garments. Keep motifs flat, crisp and restrained, with distinct spacing or shapes across cards. Avoid unnecessary gradients.

Card labels are configurable. Preserve supplied wording. The user-approved default header is exactly PANTONE in bold black uppercase English, with a short English object-linked subtitle on each card. Do not use 色彩档案 or Chinese card labels unless explicitly requested. Disclose the proposed English subtitles in the layout plan. This is a reference-inspired graphic label, not a verified official color match; do not invent official color numbers, licensed matches or brand collaborations. Do not copy unrelated product names from the reference.

## Layout and layers
Choose upright, white rectangular cards with a generous graphic upper field and a shorter caption band. Bold black sans-serif header; smaller regular subtitle; minimal restrained card shadow. No frost, 3D plastic, torn paper, pins, tape or connecting-arrow information graphics.
Arrange a few cards in an asymmetric path through the image's negative space. Adapt card size to the subject and actual source margins; preserve the face and key clothing details. Do not place cards in a symmetrical surrounding sticker ring.

Layer order: source photograph → cards and their subtle shadows → selected original foreground masks. Hair, hands, sleeves, a shoe, bag or leg can overlap card edges where their original silhouettes naturally intersect. Restore only the required source foreground regions. Show enough of each card to read its swatch and useful label. Do not move or regenerate limbs to create overlap. Do not paste the whole person as a sticker with a white outline.

## Staged production
When the user asks first to analyze or form the Skill, deliver the analysis and files only. Generate a test only when requested. For a test, choose a suitable raw photo, explain palette/card/occlusion choices, produce one image, inspect it, then stop for the user's review. Do not continue to other styles or batch examples while this checkpoint is pending.
Use image generation for aesthetic previews if appropriate; for source-locked delivery, composite original pixels with masks and deterministic card typography. A generated photo edit does not establish pixel-level identity fidelity. Report an uncertain mask or source fidelity as preview, not final verified source-locked output.

## Acceptance
- Full-bleed original photo and recognizable source identity/pose/objects.
- Every swatch uses actual source colors; distinguish observed garment patterns from added graphic abstractions. Default multi-card designs include crisp stripes/geometric motifs rather than only solid blocks.
- White cards with crisp pattern/solid field, restrained shadows and strong readable type hierarchy.
- Asymmetric balanced layout; sufficient breathing room; no crowded face or decorative overload.
- Natural person/card occlusion; no fabricated body, props, outline or incorrect foreground shadow.
- User text correct; no fictitious official color number or copied unrelated case name.
- No unnecessary iPhone interfaces or new backgrounds.
Deliver the preview and a short checklist of any deficiencies. Human aesthetic approval is separate from Skill structural validation.

## Author and public reference

Created and maintained by **理智画** (GitHub: [liuzihe849-png](https://github.com/liuzihe849-png)). Inspect [the original sample](assets/reference-original.png) and read [sample scope and limitations](references/public-sample.md). The sample is a visual aid, not a user identity or proof of exact fidelity. Do not copy sample-specific defects into new outputs.
