# Style recipes

Use only the section matching the chosen composition mode.

## Default intensity: strong

Unless the user asks for subtle treatment, do not preserve the original frame. First identify 3–6 factual anchors, then rebuild the page from those anchors.

Strong transformation recipe:

1. Extract 5–9 source-derived fragments.
2. Choose one hero anchor and enlarge it to roughly 1.4–2.2 times the visual weight of the next-largest fragment.
3. Show source material through at least three media treatments: photo cutout, threshold photocopy or silhouette, traced linework, halftone, or watercolor wash.
4. Mix hard, torn, dry-brush, and feathered edges. Avoid uniform masking.
5. Keep 50–70% of the page as paper field.
6. Add one structural graphic gesture that connects the fragments.

The same object or landmark may appear more than once when each appearance uses a different crop or graphic treatment. This is editorial repetition, not a new factual element.

## Shared palette and texture

- Paper: warm white `#F7F5EF` or cool white `#F5F6F4`
- Ink: near black `#171717`
- Mid-gray: `#77746F`
- Accent options: ochre `#D3A447`, brick red `#9B342E`, dusty lavender-blue `#AAB2C8`
- Treatment: 70–90% grayscale, bold threshold contrast in selected fragments, photocopy grain, halftone or newsprint damage, cut-paper and dry-brush edges, sparse graphite lines, low-opacity watercolor bleed

Use one accent family per output unless the user supplies a palette. Accent should occupy roughly 7–15% of the image and should define hierarchy, not tint the whole photograph.

Choose one profile:

- **Archival ochre:** warm white, charcoal gray, faded sepia, ochre blocks; calm and archaeological.
- **Critical red:** hard black-and-white photocopy, brick-red outlines or cuts, occasional signal yellow; confrontational and urban.
- **Ethereal infrastructure:** cool gray, black linework, dusty lavender-blue washes; speculative and atmospheric.

## Mode A: concept collage

Use for one building, site, landscape, or hero scene.

Composition:

- Landscape or square canvas unless the user specifies otherwise.
- Central collage island occupies about 35–55% of the canvas.
- Preserve the main subject as the visual anchor but isolate and enlarge it; layer 4–8 differently treated supporting crops around, behind, and through it.
- Do not use an intact source frame as the island. Use negative space to sever and reconnect the fragments.
- Let one assertive line system, pipe bundle, path, contour stroke, or sectional cut connect fragments.
- Abstract scale silhouettes or diagram marks may be added as graphic notation, but not as documentary evidence.

Prompt scaffold:

```text
Use case: style-transfer
Asset type: architecture portfolio concept collage
Primary request: Transform the supplied image into a minimalist architectural analytical collage.
Input images: Image 1 is the edit target and factual subject reference.
Subject: Preserve the original building/site, its defining silhouette, visible materials, terrain, and spatial relationships.
Style/medium: strongly deconstructed architectural montage combining photographic cutouts, high-contrast threshold photocopy, traced linework, halftone/newsprint damage, irregular paper masks, and restrained translucent watercolor wash.
Composition/framing: dismantle the source into 5–9 fragments; one enlarged hero anchor plus 4–8 supporting crops; one asymmetric collage island occupying about 45% of a warm-white canvas; at least 55% clean negative space; deliberate scale jumps and broken perspective between fragments; one structural graphic gesture connecting the composition.
Color palette: 75–85% grayscale with one restrained <ACCENT> accent family covering 7–15% of the page and defining the hierarchy.
Text: <quoted exact text, or "none">
Constraints: Preserve recognition, not the source frame. Recompose through extraction, crop, duplication, scale shifts, masking, overlap, thresholding, line tracing, texture, and annotation. No continuous photo fragment may exceed roughly one third of the collage area. Use at least three distinct graphic treatments. Do not invent buildings, landscape features, data, dates, or conclusions.
Avoid: intact source photo as background, filtered-photo look, beige texture pasted over the whole image, decorative circles floating over a panorama, full-bleed photo, glossy 3D render, colorful scrapbook look, saturated gradients, heavy drop shadows, dense pseudo-text, logos, watermark, signature.
```

## Mode B: analysis strip

Use for multiple views, urban conditions, or a site-analysis board.

Composition:

- A long, low reconstructed band crosses the middle third of the page; it must not be one continuous panorama.
- Use 7–12 staggered fragments. Overlap by 8–25%; mix crisp blocks, threshold silhouettes, line-drawn gaps, irregular masks, and two or three soft fades.
- Use 3–6 thin vertical or dotted leader lines above and below the band.
- Scale figures may punctuate the strip but must not become the subject.
- An optional vertical title can sit at the far left. Keep annotations short and sourced.

Prompt scaffold:

```text
Use case: style-transfer
Asset type: urban/site analysis board
Primary request: Combine the supplied site photographs into a restrained architecture-portfolio analysis strip.
Input images: Each supplied image is a factual site view; preserve its recognizable architecture, streets, vegetation, and topography.
Style/medium: aggressively edited grayscale documentary fragments, hard threshold photocopy, line-traced architecture, cut-paper and dry-brush masks, halftone damage, sparse technical notation, and optional abstract scale silhouettes.
Composition/framing: rebuild the site as a low horizontal narrative band from 7–12 staggered fragments; one hero landmark enlarged and allowed to break the band; 8–25% overlaps; varied scales and edge treatments; 55–65% clean paper field; one structural trajectory or contour gesture plus 3–6 fine leaders.
Color palette: 75–85% grayscale plus one restrained <ACCENT> family used for outlines, one block, and a few focal details.
Text: Use only this exact supplied title/callout text: <VERBATIM TEXT>. If none is supplied, leave caption areas blank rather than inventing copy.
Constraints: Preserve the site's factual landmarks and left-to-right logic, not the original camera composition. No intact panoramic background. Use at least three graphic treatments. Maintain believable geometry inside each fragment; editorial scale changes between fragments are allowed.
Avoid: filtered panorama, uniform beige overlay, decorative circles without hierarchy, fake analytics, fabricated labels, collage stickers, torn-paper rainbow colors, bold shadows, full-bleed background, logos, watermark, signature.
```

## Mode C: historical timeline

Use only when the user provides an ordered sequence or dated evidence.

Composition:

- Place the chronological band in the lower half or lower third.
- Move left-to-right from earliest to latest.
- Use thin vertical year markers and one restrained baseline or rising trajectory line.
- Let architecture, machinery, crowds, maps, or documents form the visual evidence beneath each supplied date.
- Keep year labels prominent enough to read; keep descriptions concise.

Prompt scaffold:

```text
Use case: style-transfer
Asset type: architecture portfolio historical timeline
Primary request: Convert the supplied dated images into a minimalist chronological urban-development collage.
Input images: Each image is evidence for the user-supplied date or period; preserve its factual subject and assigned order.
Style/medium: black-and-white archival photo montage, crisp cutouts, subtle photocopy texture, thin architectural rules, restrained editorial typography.
Composition/framing: left-to-right chronological band in the lower half of a warm-white canvas; thin vertical date markers; one restrained <ACCENT> trajectory line; dense evidence near the baseline with generous open space above.
Color palette: grayscale with one muted <ACCENT> line and minimal matching highlights.
Text: Render only these exact dates and captions: <VERBATIM DATES AND CAPTIONS>.
Constraints: Keep the supplied chronology. Do not add events, dates, statistics, causal claims, or buildings not present in the sources.
Avoid: illegible microtext, invented captions, decorative icons, glossy infographic styling, bright multicolor coding, logos, watermark, signature.
```

## Iteration prompts

Make one correction at a time and repeat invariants.

- Too colorful: `Reduce all imagery to near-monochrome; retain only the existing accent family at under 10% coverage. Keep subject geometry and composition unchanged.`
- Too full: `Increase clean warm-white negative space to about 55%; compress the collage into a lower, narrower horizontal band. Keep every source subject recognizable.`
- Subject drift: `Restore the principal subject's original silhouette, facade rhythm, terrain, and visible spatial relationships. Change only collage treatment and masking.`
- Fake text: `Remove all invented or illegible text. Keep only the exact supplied wording; otherwise leave clean blank label zones.`
- Too polished: `Replace glossy rendering with documentary photo grain, cut-paper masks, faint photocopy texture, thin graphite linework, and restrained watercolor haze.`
- Not stylized enough: `Dismantle the remaining continuous photograph. Rebuild it from 6–9 isolated fragments with deliberate scale jumps. Render the hero as a crisp photo cutout, two supports as hard threshold photocopies, one as traced linework, and one as a translucent wash. Increase clean paper field to at least 55%. Remove any decorative line that does not organize the hierarchy.`
- Too coherent: `Break the original camera perspective between fragments while preserving believable geometry inside each fragment. Enlarge the hero anchor, crop supporting evidence more aggressively, and introduce one dry-brush gap through the former panorama.`

## Final QA checklist

- Principal subject and defining geometry remain recognizable.
- No unsupported building, event, date, analysis claim, statistic, or label appears.
- Negative space is intentional and substantial.
- Palette is predominantly grayscale with only one restrained accent.
- The image reads as an architectural analysis board, not a scrapbook or cinematic render.
- The original camera frame has been dismantled; no large intact photo remains.
- At least three clearly different media treatments are visible.
- Hero and supporting fragments have intentionally different scales and edge treatments.
- Exact text is correct and legible, or omitted when accuracy cannot be achieved.
- No logo, watermark, signature, or source-brand imitation appears.
