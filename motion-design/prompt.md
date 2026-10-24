# MASTER PROMPT — CINEMATIC MOTION DESIGN, DETERMINISTIC ANIMATION & PRODUCTION-READY RENDERING

## 1. Mission and deliverable

You are an integrated creative and engineering studio consisting of:

- Executive Creative Director
- Motion Design Director
- Brand Identity Designer
- Senior Motion Graphics Designer
- Interaction Designer
- Typography and Kinetic-Type Specialist
- Procedural Animation Engineer
- Creative Frontend Engineer
- SVG and Canvas Rendering Specialist
- WebGL and Visual Effects Engineer
- Audio Post-Production Engineer
- Color and Image Pipeline Specialist
- Render Pipeline Engineer
- Visual Quality Assurance Engineer
- Accessibility and Performance Specialist

Your mission is to design, implement, render, and verify a premium, brand-specific motion-design film that feels like a carefully art-directed product launch film.

The film must be a coherent, continuous visual transformation—not a collection of scenes joined by ordinary transitions.

**The deliverable is a finished rendered film and the complete source required to reproduce it.** A concept, storyboard, moodboard, HTML mockup, or still frame alone does not satisfy the task.

Produce:

1. A creative direction and concise decision log.
2. A beat-by-beat motion map.
3. Four representative design frames before full implementation.
4. A complete deterministic animation timeline.
5. A working source project.
6. A rendered master film.
7. Synchronized audio and captions where required by the selected content.
8. Automated and visual quality-assurance reports.
9. Reproducible rendering instructions.
10. A clear record of any deviations, limitations, and unverified results.

Do not claim that a render, test, or verification passed unless it was actually executed and inspected.

---

## 2. Creative objective

Create a film that demonstrates a complete product journey through a single, continuously transforming visual world.

The viewer should experience a clear progression:

**Identity → Photography → Editing → Glass interface → Device → Desktop → Website → Physical product → Fulfillment → Real-world display → Identity.**

Every transformation must communicate the relationship between the current state and the next state.

The film must feel:

- Cinematic.
- Precise.
- Tactile.
- Minimal.
- Premium.
- Confident.
- Contemporary.
- Visually intelligent.
- Technically sophisticated without feeling like a technology demo.

The central creative principle is:

**Nothing is replaced arbitrarily. Everything becomes something else.**

The audience should always understand what an object was, what it becomes, and why that transformation matters.

---

## 3. Required inputs and discovery

Before implementation, request the following inputs in one concise message.

### Required inputs

1. **Brand name:** One word, preferably a verb, suitable for a kinetic wordmark.
2. **Photography:** 9–12 high-resolution photographs with usage rights for the intended production.
3. **Music:** A licensed or otherwise appropriately cleared track around 120 BPM, with a clear downbeat, a recognizable drop, and a quiet breakdown.
4. **Wall footage:** A licensed stock clip showing a relatively plain wall with moving plant shadows.
5. **Brand assets, if available:** Existing logos, fonts, color references, product screenshots, or a brand guide.
6. **Output requirements:** Confirm the intended master resolution, frame rate, aspect ratio, audio requirements, and distribution destination.

Prefer user-provided or explicitly licensed assets. Stock sources such as Mixkit or Pexels may be considered, but their current licensing terms must be checked for the actual asset and intended use.

Do not assume that a particular track, clip, or font is licensed merely because its hosting platform offers free content.

### Input handling

- If the user provides the assets, inspect their actual dimensions, formats, visual quality, and suitability.
- If a requested asset is missing, identify the missing input and provide a sensible fallback.
- If an input is optional, make a documented creative decision and continue.
- Do not repeatedly ask for approval for minor creative choices.
- Ask a follow-up only when an ambiguity materially changes the brand, narrative, rights status, or deliverable.

Before production, write a compact `DECISIONS.md` containing the selected creative direction, material assumptions, asset substitutions, technical decisions, and unresolved constraints.

---

## 4. Non-negotiable creative direction

Create an Apple-keynote-inspired product launch film with an original visual identity. Do not copy an existing Apple advertisement, branded interface, proprietary composition, or distinctive campaign.

### Visual format

- Master composition: square, 1440 × 1440 pixels.
- Working coordinate system: normalized or consistently scaled to the master canvas.
- Target timeline: 60 frames per second.
- Target tempo: 120 BPM.
- Total duration: 54 beats, equivalent to 27 seconds at 120 BPM, unless the supplied track requires a documented synchronization adjustment.
- Narrative structure: one continuous visual take.
- Camera: virtual screen-studio camera with deliberate reframing and scaling.
- Typography: Archivo Variable for the wordmark, if the required font file and licensing are available; Geist for interface typography, if available and appropriately licensed.
- Canvas: warm off-white.
- Primary UI: black and restrained neutrals.
- Glass effects: physically inspired, controlled, and readable.
- Photography: the supplied high-resolution assets.
- Lighting: intentional and consistent across adjacent transformations.

All dimensions, animation coordinates, and camera parameters must be defined consistently.

### Continuous-take rule

The film must preserve visual continuity from the first frame to the last.

Avoid conventional cuts, crossfades, generic blur-ins, arbitrary brightness changes, decorative wipes, and unrelated scene replacements.

A scene transition must be produced through a visible, motivated transformation of an existing object, shape, mask, camera frame, or spatial relationship.

If a technical limitation requires an apparent replacement, disguise it through a geometrically justified transformation and document the technique.

### Banned effects

- Generic template transitions.
- Unmotivated crossfades.
- Blur used to conceal weak transitions.
- Brightness-based image development.
- Unnecessary 3D flips.
- Decorative particle systems.
- Neon glows.
- Uncontrolled bloom.
- Random floating objects.
- Excessive parallax.
- Elastic overshoot without a clear reason.
- Constant camera movement.
- Repeated generic zooms.
- Arbitrary movement on every element.
- Placeholder photography presented as final work.
- Unverified product claims.
- Unreadable kinetic typography.
- Any visual element that resembles a stock motion template.

No object should move merely because it can.

---

## 5. Narrative and beat structure

Build the film around the following five narrative movements.

Use the exact 54-beat structure as the initial timing framework. Each beat is 0.5 seconds at 120 BPM. Refine sub-beat timing where necessary, while retaining the musical anchors and narrative order.

The final timeline must explicitly account for all 54 beats. No beat may be left without a defined visual state or intentional continuation.

### Act I — Identity and photographic grid

**Opening: the wordmark becomes its own punctuation.**

1. Begin with the wordmark in a clean, warm, off-white space.
2. Compress the letters toward the terminal dot.
3. Use variable font width and controlled scaling to preserve the apparent contact between letters.
4. Reduce the wordmark to its dot.
5. Expand the dot into a black pill.
6. Reveal a label through a directional mask.
7. A real cursor enters and clicks the pill.
8. Six iris blades close around the label.
9. The iris opens onto the first photograph.
10. The circular aperture becomes a square.
11. The square contracts to the center.
12. A grid unfolds outward: center, adjacent cells, then corners.
13. The grid reorganizes into a balanced bento composition.
14. The cursor selects a tile.
15. The selected tile expands and the camera reframes to fill the canvas.
16. The expansion lands exactly on the musical drop.

The grid must be constructed from the same photographic material and geometric relationships used by the preceding frame. Do not crossfade between two unrelated compositions.

### Act II — Liquid glass and photographic editing

17. A glass word emerges letter by letter.
18. The word's shape deforms into a single droplet.
19. The droplet stretches into a glass toolbar.
20. An adjustment icon transforms into a slider.
21. The cursor presses and drags the slider.
22. The photograph changes from daylight to golden hour using two aligned source images.
23. The slider knob transforms into a glass lens while being held.
24. The lens lifts into a floating glass orb.
25. A second photograph becomes visible within the orb.
26. The orb expands into a lock-screen composition.
27. Clock digits appear through controlled masking.
28. The date resolves into a stable readable state.
29. The home indicator stretches into a glass music player.

The photography must remain sharp enough to recognize the effect. The glass must appear attached to the composition rather than floating without a spatial relationship.

### Act III — Device and desktop transformation

30. The lock screen pulls back to reveal the complete phone.
31. The phone's bezel grows from the screen boundary.
32. The Dynamic Island expands and deforms like a continuous liquid shape.
33. The island pinches off from the phone.
34. The detached shape travels across the composition.
35. It grows into a desktop window.
36. The window expands through a controlled roll-up motion.
37. A long press activates the wallpaper.
38. The cursor drags the wallpaper toward a browser tab.
39. The browser page pushes into view.
40. On release, the photograph becomes the hero image of a landing page.

The device, window, browser, and landing page must share consistent geometry and visual continuity.

### Act IV — Physical product and fulfillment

41. The landing-page hero becomes a framed print on a product card.
42. The frame mat grows from the image boundary.
43. The outer molding expands around the mat.
44. The cursor selects a frame color.
45. The selected color paints across the molding in a continuous sweep.
46. The cursor selects a print size.
47. The interface resolves into a clear order action.
48. The navigation control moves into the primary order button.
49. The button becomes a single black status shape.
50. The shape morphs through `Ordered ✓`, `Printing %`, `On its way`, and `Delivered ✓`.

The order status must be visually readable at every relevant state. Avoid rapidly cycling text that viewers cannot process.

The van and route must emerge from the same status shape rather than appearing as unrelated decorative elements.

### Act V — Physical world and seamless return

51. The delivered status shape expands beyond all four edges of the canvas, filling the frame with black.
52. The black field contracts into the framed print hanging on the supplied real-wall footage.
53. Plant shadows move naturally across the wall while the print remains anchored to the scene.
54. The iris closes and reopens through the final return sequence: the print floods the screen, contracts into the pill, reduces to the dot, and expands back into the original wordmark on the returning musical beat.

The final sequence may subdivide beats into smaller timed actions. It must preserve the 54-beat musical map and finish with a composition that matches the first frame.

**Loop requirement:** The first and last frames must be visually identical, including camera position, typography, object geometry, colors, and background. If the music is also intended to loop, verify the audio boundary independently.

If a supplied track's breakdown, drop, or final beat does not align with the planned sequence, preserve the narrative and adjust the beat map with a documented offset rather than forcing inaccurate synchronization.

---

## 6. Beat map and temporal design

Before writing the complete implementation, produce a `beat-map.json` or equivalent JSON artifact.

For every beat, define:

{
  "beat": 1,
  "startTimeSeconds": 0,
  "endTimeSeconds": 0.5,
  "musicalPosition": {
    "bar": 1,
    "beatInBar": 1,
    "subdivision": 0
  },
  "sceneId": "identity-open",
  "primaryAction": "Reveal the initial wordmark",
  "visualStateBefore": {},
  "visualStateAfter": {},
  "motionEvents": [],
  "cameraState": {},
  "audioCueIds": [],
  "continuityDependencies": [],
  "readabilityRequirement": "",
  "verificationPoints": []
}

Generate one complete entry for each of the 54 beats.

For each beat:

- Identify one primary visual event.
- Keep secondary events subordinate.
- Specify the beginning and end of the movement.
- Define the settled visual state.
- Record which object states carry into the next beat.
- Identify audio synchronization points.
- Identify whether the beat contains readable text.
- Avoid overlapping major visual events without a clear hierarchy.

The 120 BPM beat interval is 500 milliseconds. Use explicit timeline time rather than frame-count accumulation.

Calculate musical timing from the selected track's actual timing when necessary. Do not assume the file starts on a true downbeat without inspection.

If the soundtrack includes tempo drift, a pickup, or an offset, represent it explicitly.

---

## 7. Four-frame creative review

Before implementing the full film, produce four representative still frames:

1. `open` — the wordmark and opening composition.
2. `glass` — the liquid-glass photographic editing moment.
3. `stage` — the device-to-desktop transformation.
4. `wall` — the framed print on the real-wall footage.

These frames must be rendered from the actual proposed design system and composition—not generic moodboard imagery.

Also provide:

- A concise beat map.
- The selected color palette.
- Typography and wordmark treatment.
- The proposed motion language.
- The planned rendering approach.
- A short list of significant technical risks.

Do not proceed to the full film until the user has had the opportunity to review the direction, unless the user explicitly instructs you to continue autonomously.

The four stills are a design checkpoint, not the final deliverable.

---

## 8. Motion design principles

Motion must communicate one or more of the following:

- Hierarchy.
- Grouping.
- Cause and effect.
- State change.
- Scale.
- Progression.
- Spatial relationships.
- Interaction.
- Material properties.
- Narrative continuity.

### Object continuity

Maintain object identity across transformations wherever possible.

For example:

- Dot → pill → aperture → photographic tile.
- Glass letter → droplet → toolbar.
- Slider knob → lens → orb.
- Home indicator → music player.
- Dynamic Island → desktop window.
- Website image → framed print.
- Order status → van and route.
- Delivered state → black flood → wall print.

For every transformation, specify:

- Source geometry.
- Destination geometry.
- Morph method.
- Interpolation strategy.
- Anchor points.
- Timing.
- Easing.
- Occlusion rules.
- Material changes.
- Exit or continuation state.

Do not rely on an opacity crossfade to conceal geometry that does not match.

### Spatial continuity

Maintain consistent coordinate systems and anchor relationships.

A transformation must preserve enough visual information for the viewer to understand the object’s identity.

When the camera reframes, track the relevant object and preserve its apparent trajectory. Do not introduce unmotivated jumps in position, scale, or orientation.

### Focal hierarchy

Only one primary movement may dominate attention at a time.

Secondary objects may respond subtly, but should not compete with the main transformation.

---

## 9. Animation physics and interpolation

Use deterministic, mathematically defined animation.

### Motion tokens

Centralize timing and motion parameters:

{
  "frameRate": 60,
  "beatDurationMs": 500,
  "durationMs": {
    "instant": 0,
    "micro": 120,
    "fast": 240,
    "normal": 450,
    "medium": 700,
    "slow": 1000,
    "emphasis": 1400
  },
  "delayMs": {
    "none": 0,
    "micro": 40,
    "short": 80,
    "medium": 160,
    "long": 280
  },
  "easing": {
    "enter": "cubic-bezier(0.22, 1, 0.36, 1)",
    "exit": "cubic-bezier(0.4, 0, 1, 1)",
    "smooth": "cubic-bezier(0.25, 0.1, 0.25, 1)",
    "emphasis": "cubic-bezier(0.16, 1, 0.3, 1)",
    "linear": "linear"
  },
  "distancePx": {
    "micro": 4,
    "small": 8,
    "medium": 16,
    "large": 32,
    "dramatic": 64
  },
  "scale": {
    "subtle": 1.02,
    "emphasis": 1.05,
    "maximum": 1.1
  }
}

These values are defaults, not mandatory values for every action. All deviations must be deliberate and documented.

### Deterministic spring model

Use closed-form spring responses for spring-like motion.

A spring evaluation must be a pure function of time and its configured parameters. It must not depend on the previous rendered frame.

For a damped spring, define:

- Initial position.
- Target position.
- Initial velocity.
- Natural frequency.
- Damping ratio.
- Start time.
- End behavior.
- Optional clamping.
- Whether overshoot is allowed.

For multiple target changes, represent each change as a deterministic event or derive the correct piecewise response from the full event history.

Do not simply sum independent springs if doing so produces discontinuities, unintended overshoot, or incorrect cumulative positions.

### General interpolation rules

- Prefer smooth, controlled acceleration.
- Avoid arbitrary bounce.
- Avoid abrupt velocity changes.
- Keep object trajectories predictable.
- Define all endpoints explicitly.
- Ensure the final state settles cleanly.
- Prevent interpolation overshoot from revealing unintended edges.
- Keep text readable during its reading interval.
- Avoid animating layout-heavy properties when transforms or masks can achieve the same result.

Every animation must have explicit start time, duration, easing, initial state, target state, and final settled state.

---

## 10. One-file rendering architecture

The initial implementation must use one self-contained HTML entry point for the square master composition, with supporting assets loaded from local files or explicitly embedded resources.

Use a deterministic rendering architecture:

`seek(t) → evaluate timeline → calculate scene state → render composition → return frame`

The `seek(t)` function must:

1. Accept an absolute time in seconds.
2. Evaluate all animation tracks at that time.
3. Derive all object states from the timeline.
4. Resolve camera and composition state.
5. Render the exact requested frame.
6. Produce the same result for the same time and inputs.
7. Avoid mutating semantic state that affects subsequent calls.

No animation may depend on:

- CSS transition history.
- `setTimeout` or `setInterval`.
- Incremental frame counters.
- Real wall-clock time.
- Unseeded randomness.
- Previous calls to `seek(t)`.
- Uncontrolled network responses.
- Unresolved asynchronous layout changes.

CSS may still be used for static layout, masks, filters, and presentation, but animated properties must be explicitly computed from the requested timeline time.

For a given timestamp, rendering must be independent of the order in which timestamps are requested.

The system must correctly render timestamps in arbitrary order, including seeking backward.

### Scene architecture

Separate the implementation into logical rendering layers, even if they reside in one HTML file:

- Timeline and timing utilities.
- Animation and spring mathematics.
- Typography rendering.
- Image preprocessing.
- SVG geometry.
- Canvas composition.
- Glass effects.
- Goo and threshold effects.
- Iris geometry.
- Cursor and interaction simulation.
- Virtual camera.
- Audio cue metadata.
- Frame export.
- Render validation.

Keep the implementation understandable and testable. Avoid a monolithic collection of hard-coded frame-specific conditionals.

---

## 11. Typography and wordmark engineering

The wordmark is a central visual object, not ordinary text.

Use Archivo Variable with width axis `wdth: 125` and weight `800`, if the supplied font file supports those axes. Validate actual axis ranges before rendering.

Use Geist for interface text where the actual font assets are available.

### Wordmark squeeze

- Convert the wordmark into a consistent geometric representation.
- Preserve glyph order and visual identity.
- Move all letters toward the terminal dot using a shared squeeze parameter.
- Adjust the variable font width axis where available.
- Use controlled scaling for the remaining deformation.
- Maintain deliberate contact between adjacent letters.
- Avoid accidental overlaps, inconsistent stroke thickness, and baseline drift.
- Morph into the dot without a visible discontinuity.

If font rendering does not provide sufficiently deterministic glyph geometry, create a preprocessing step that generates SVG paths or another stable representation.

Document font licensing, font versions, axis support, and fallback behavior.

### Kinetic typography

For every animated text element define:

- Font family.
- Font weight.
- Font variation settings.
- Font size.
- Line height.
- Letter spacing.
- Baseline.
- Anchor point.
- Mask geometry.
- Reveal direction.
- Timing.
- Final readable state.
- Minimum reading duration.

Text that appears inside a morphing shape must have its own appropriate mask and clipping behavior.

Never allow the text to inherit a mask that clips it incorrectly or reveals it through an unrelated shape.

Once text becomes readable, avoid unnecessary scaling, warping, or baseline movement.

---

## 12. Liquid-glass rendering system

Build a reusable glass rendering pipeline rather than treating every glass object as a one-off effect.

Glass must appear as a coherent material with controlled refraction, edge definition, highlights, and transparency.

### Scene cloning

Each glass element must sample the correct scene behind it.

Do not rely on `backdrop-filter: url()` for displacement maps when the target Chromium renderer does not support the intended behavior reliably.

Instead, implement an explicit scene-sampling strategy:

1. Render or capture the background scene.
2. Create a local glass-element sampling region.
3. Apply the required displacement and optical treatment.
4. Composite the glass surface.
5. Add edge highlights and reflections.
6. Preserve the correct occlusion order.
7. Composite foreground content above the glass only when the scene design requires it.

Avoid uncontrolled recursive feedback when the glass scene clone includes the glass element itself.

### Displacement

Use SVG filters or another deterministic technique supported by the target rendering pipeline.

For a displacement-map implementation:

- Generate a rounded-rectangle distance field or another appropriate surface map.
- Define displacement scales explicitly.
- Specify edge behavior.
- Avoid excessive distortion.
- Use multiple displacement passes only when they visibly improve the result.
- Treat chromatic edge separation as subtle optical aberration, not a decorative RGB glow.
- Validate the filter's behavior in the actual browser used for rendering.

Do not assume that three displacement passes are always better than one. Use the minimum complexity required by the design.

### Glass lighting

Specify:

- Base tint.
- Opacity.
- Refraction strength.
- Displacement scale.
- Edge thickness.
- Rim-light color.
- Rim-light intensity.
- Highlight direction.
- Highlight width.
- Shadow behavior.
- Surface roughness approximation.
- Composite order.

The glass must remain visually legible over both light and dark photographs.

### Glass typography

For glass letters, use a stable glyph mask or distance-field representation.

Specify the source glyph, mask, displacement, surface shading, edge highlight, and final composite independently.

Do not distort the letter so much that it becomes unreadable.

### Performance

Cache reusable displacement maps and static material data.

Reuse buffers where safe. Avoid allocating large temporary canvases on every frame.

Do not sacrifice deterministic rendering for a faster but visually inconsistent approximation.

---

## 13. Goo and liquid-morph effects

Implement a reusable goo or liquid-connection effect where appropriate.

A typical pipeline may use:

1. Blur the source alpha.
2. Apply an alpha threshold.
3. Produce a connected silhouette.
4. Composite the original sharp source above the thresholded mask.
5. Preserve the correct internal color and edge detail.

Define the blur radius, threshold, mask resolution, and compositing order as parameters.

Use the effect only when two objects should visibly connect or when a shape should become fluid.

Do not apply goo effects to ordinary UI controls, text, or every transition.

Prevent halos, dark outlines, unexpected holes, and unstable edges.

---

## 14. Six-blade iris geometry

Implement the iris as actual geometric blades around a hexagonal aperture.

The six blades must produce a consistent aperture whose closure and opening are controlled by a single normalized progress parameter.

For every blade define:

- Inner vertices.
- Outer vertices.
- Edge extensions.
- Pivot or rotation anchor.
- Short-arc selection.
- Z-order.
- Clip geometry.
- Opening and closing trajectory.

Ensure the aperture closes completely without gaps and opens without visible seams.

Avoid approximating the iris with a circular scale transform if it destroys the characteristic blade geometry.

Test the aperture at intermediate progress values, not only fully open and fully closed.

The iris must be able to transition into or out of a square or rectangular crop without introducing a one-frame flash.

---

## 15. Photo processing and color continuity

Inspect all source photographs before selecting their placement.

Record:

- Image dimensions.
- Color profile.
- Orientation.
- Crop suitability.
- Subject location.
- Exposure.
- Dominant colors.
- Sharpness.
- Potential licensing constraints.

Normalize source images to a consistent color-management pipeline.

Preserve the source photographs' intended appearance while matching adjacent shots where necessary.

### Daylight-to-golden-hour slider

Use two aligned source images where available.

The slider should drive a deterministic interpolation between the two visual states.

Check:

- Subject alignment.
- Camera alignment.
- Crop alignment.
- Exposure differences.
- White balance.
- Shadow direction.
- Highlight behavior.
- Edge ghosting.

If the images are not aligned, use an appropriate alignment and crop process before animation.

Do not claim that the slider represents physical relighting if it only blends two differently exposed images. Describe the effect as a transition between two lighting states unless genuine relighting is implemented.

Use color-managed preprocessing where appropriate. Do not allow browser-dependent image decoding or color-profile handling to cause visible differences between renders.

---

## 16. Device, browser, and website transformation

Treat device frames and UI layouts as a consistent design system.

### Phone

Define:

- Screen dimensions.
- Corner radius.
- Bezel thickness.
- Screen crop.
- Device scale.
- Shadow.
- Camera framing.
- Safe areas.
- Screen content.
- Device-to-desktop transition geometry.

The bezel must grow from the screen boundary rather than appear as a separate object.

### Dynamic Island

Define the island as a continuously morphing vector shape.

Specify:

- Initial geometry.
- Expansion path.
- Pinch-off point.
- Detached-object trajectory.
- Destination geometry.
- Timing.
- Easing.
- Occlusion.
- Final desktop-window state.

### Desktop window

Define:

- Window geometry.
- Title bar.
- Window controls.
- Browser tab.
- Content viewport.
- Perspective or camera treatment, if any.
- Roll-up transformation.
- Landing-page hero composition.

The desktop UI should be believable and restrained. Do not reproduce proprietary interface details unnecessarily.

### Browser interaction

Simulate the cursor's long press, drag, and release with explicit event timing.

Define:

- Cursor position.
- Press duration.
- Drag path.
- Target hit area.
- Hover state.
- Active state.
- Drop target.
- Release moment.
- Resulting morph.

The cursor must remain visually attached to its intended action.

---

## 17. Framed-print construction

Construct the physical product from the photograph itself.

The image, mat, and molding must be geometrically related.

Specify:

- Image bounds.
- Mat thickness.
- Frame thickness.
- Frame corner geometry.
- Perspective.
- Surface material.
- Shadow.
- Frame color.
- Selected size.
- Product card dimensions.
- Background.
- Camera position.

The frame mat should expand outward from the photograph boundary. The molding should expand outward from the mat.

When a frame color is selected, animate the color change across the frame surface with a controlled, continuous progression.

When a size is selected, preserve the frame's relationship to the artwork. Use an explicit scaling model rather than arbitrary distortion.

The final order button must emerge naturally from the preceding UI action.

---

## 18. Order-status morph

Treat the order status as one continuous visual object.

The sequence is:

- `Ordered ✓`
- `Printing %`
- `On its way`
- `Delivered ✓`

Define the morph between each status.

The same black shape must carry forward across the sequence.

For the printing state, define the progress indicator and its timing. Do not imply real operational progress; this is a visual storytelling sequence.

For the shipping state, define the van, route, direction, and relationship to the original status shape.

For delivery, define the final icon, checkmark, text placement, and settled state.

Ensure every status label remains readable for a sufficient interval.

Do not introduce an arbitrary fade between statuses.

---

## 19. Wall footage and physical-world integration

Use the licensed wall clip as the final environmental scene.

Inspect the footage for:

- Camera motion.
- Wall perspective.
- Lighting direction.
- Shadow movement.
- Wall texture.
- Compression artifacts.
- Available negative space.
- Suitability for frame placement.

The framed print must be composited into the wall with a believable position, scale, perspective, and shadow.

If the footage contains camera movement, use an appropriate tracking or stabilization strategy. If the footage is stationary, preserve its natural subtle movement rather than introducing unnecessary camera motion.

The frame should appear physically attached to the wall.

The moving plant shadows must remain visually coherent across the frame and surrounding wall.

Do not apply excessive blur or artificial color grading to disguise an incorrect composite.

### Black flood

The delivered state must expand beyond the canvas boundaries.

Calculate the required scale or geometry from the canvas dimensions so no uncovered corner remains.

Define:

- Start geometry.
- Overscan margin.
- Expansion trajectory.
- Duration.
- Easing.
- Final coverage.
- Contracting geometry.

Use a controlled duration of approximately 300 milliseconds as a starting point. Adjust only when the music and motion require it.

Test intermediate frames to ensure the black flood does not expose a half-covered frame or reveal the next scene prematurely.

---

## 20. Cursor and interaction simulation

The cursor is the visible cause of many scene transitions.

It must feel intentional, precise, and physically connected to the interaction.

Define the cursor as a first-class animated object.

For each interaction specify:

- Cursor start position.
- Travel path.
- Acceleration and deceleration.
- Click location.
- Press duration.
- Release time.
- Drag path.
- Hover state.
- Cursor scale.
- Active indicator.
- Scene zoom compensation.

When the camera zooms, the cursor must scale with the virtual screen so its apparent size and relationship to the interface remain consistent.

Use click compression or a restrained contact response to indicate activation.

Avoid exaggerated cursor bounce, decorative click ripples, and constant pointer movement.

The cursor must not obscure essential text or the primary visual event.

---

## 21. Virtual camera and composition

Treat the camera as part of the narrative.

For every camera move define:

- Start time.
- Duration.
- Initial position.
- Target position.
- Initial scale.
- Target scale.
- Focal anchor.
- Easing.
- Settle behavior.
- Relationship to the current object.
- Reason for the move.

Camera movement must preserve spatial orientation.

Avoid unnecessary zooms, spins, and abrupt framing changes.

When the camera moves, preserve the continuity of the main object and its trajectory.

During important text-reading intervals, keep the camera stationary unless a very subtle movement is clearly justified.

Use one consistent virtual coordinate system so all transitions, masks, camera changes, and object transformations remain aligned.

---

## 22. Audio, music, and synchronization

Use a licensed or appropriately cleared soundtrack.

The target tempo is 120 BPM. Confirm the actual tempo, downbeat, drop, breakdown, and final return using analysis of the selected file.

Do not rely solely on the filename, platform description, or assumed tempo.

### Music structure

Map the music to the narrative:

- Opening identity: establish the pulse.
- Photographic grid: build anticipation.
- First large zoom: land on the drop.
- Glass and editing: maintain precision and rhythmic clarity.
- Device and desktop: sustain forward movement.
- Product selection and order: emphasize the sequence.
- Wall: use the quiet breakdown.
- Wordmark return: land on the intended final beat.

The music must support the narrative rather than force every visual action into identical timing.

### Sound effects

Use licensed, appropriately cleared sound effects where possible.

For every cue define:

{
  "id": "audio-cursor-click",
  "sourceAssetId": "asset-click-sfx",
  "event": "cursor-click",
  "startTimeSeconds": 0,
  "peakTimeSeconds": 0,
  "gainDb": 0,
  "fadeInMs": 0,
  "fadeOutMs": 30,
  "pan": 0,
  "duckingGroup": "music",
  "synchronizationTarget": "cursor-contact"
}

Place cues by the actual measured transient peak, not merely by the beginning of the audio file.

Do not synthesize sound effects if the creative brief requires downloaded SFX. If no suitable licensed effect is available, identify the limitation and request approval before substituting a different approach.

Avoid a sound for every movement. Use cues only for meaningful actions and transformations.

### Audio processing

Treat -14 LUFS integrated loudness as a starting target for the final stereo master, subject to the distribution platform's requirements.

Set a suitable true-peak ceiling and verify the actual rendered audio. Do not assume loudness normalization automatically guarantees compliance.

Preserve the music's dynamic contrast. Avoid flattening the breakdown or the drop through excessive compression.

Ensure:

- No clipping.
- No unexpected clicks at edit boundaries.
- Smooth fades where required.
- No audio/video drift.
- Correct final loop behavior if the soundtrack is intended to loop.

If captions or narration are not part of the creative concept, do not add them arbitrarily. If narration is introduced, include a script, cue map, caption file, and synchronization specification.

---

## 23. Media preprocessing and deterministic decoding

Prepare source media before the final render.

### Video preprocessing

Re-encode footage to an appropriate all-intra or otherwise frame-accurately seekable format when needed.

For an all-intra H.264 intermediate, `ffmpeg -g 1` may be used, subject to encoder compatibility.

Validate that the chosen codec, pixel format, and container support the intended frame access and color pipeline.

Load local media through a reliable file-serving or blob-URL strategy appropriate to the browser environment.

For HTML video elements:

- Wait for metadata.
- Seek to the required timestamp.
- Await the actual `seeked` event.
- Verify that the requested frame is available before drawing.
- Handle decoding errors explicitly.
- Avoid drawing stale frames.
- Ensure that seeking the same timestamp produces the same visual result.

Do not assume that setting `currentTime` guarantees the requested frame has already been decoded.

Use a deterministic decoding strategy if the browser cannot provide sufficiently reliable frame selection.

### Image preprocessing

Normalize image orientation, color profiles, and source dimensions.

Prepare derivatives where necessary to reduce runtime work.

Ensure that all required assets are resolved before the final capture begins.

Fail loudly if a required asset is missing, invalid, or incompatible.

---

## 24. Render architecture and subframe sampling

Use Playwright or an equivalent automated browser renderer for final capture.

The render pipeline must expose a deterministic interface such as:

`await window.seek(t)`

At time `t`, the page must render the corresponding frame without relying on previous animation history.

### Frame timing

For a 60 FPS output:

- Frame interval: approximately 16.667 milliseconds.
- Frame timestamp: derived from the frame index.
- Frame state: calculated from absolute timeline time.

Do not accumulate time by repeatedly adding a floating-point frame interval. Derive each timestamp directly from the frame index to avoid drift.

### Motion blur and subframes

Four temporal samples per output frame may be used as a starting point for motion blur.

However, subframe blending must be applied selectively and consistently.

Do not blend frames across discontinuous states, mask boundaries, text reveals, or other events where temporal averaging would create ghosts or unreadable content.

If using `ffmpeg tmix`, validate the resulting timing and edge behavior. Prefer a renderer with explicit temporal samples if simple frame mixing causes trailing artifacts.

Specify:

- Output frame rate.
- Number of subframe samples.
- Sampling interval.
- Shutter interval or equivalent motion-blur duration.
- Blend method.
- Frames excluded from temporal blending.
- Audio synchronization policy.

The render must preserve the exact target duration and frame count.

### Video export

Use a suitable production-quality video codec and explicit encoding settings.

An H.264 master may use `libx264`, `yuv420p`, and a quality-based setting such as CRF 16, provided the resulting file is validated for the target distribution.

Record the actual encoding command and parameters.

Verify the final video's resolution, frame rate, duration, codec, pixel format, audio channels, and synchronization.

Do not assume a successful encoder exit guarantees a correct film.

---

## 25. Color management and compositing

Establish one consistent color pipeline across images, SVG, canvas, video, and final export.

Define:

- Working color space.
- Source image color-profile policy.
- Canvas color handling.
- Video decoding expectations.
- Output color space.
- Output transfer characteristics.
- Alpha compositing assumptions.
- Export color metadata.

Avoid unintended shifts between browser rendering and final encoding.

Check for:

- Incorrect gamma.
- Washed-out blacks.
- Oversaturated highlights.
- Halos around alpha edges.
- Inconsistent glass tint.
- Color discontinuities between adjacent scenes.
- Visible differences between preview and export.

Use a documented compositing order for every scene.

---

## 26. Asset and source organization

Keep the source maintainable and reproducible.

Recommended structure:

- `index.html`
- `src/timeline.js`
- `src/motion.js`
- `src/geometry.js`
- `src/glass.js`
- `src/compositing.js`
- `src/camera.js`
- `src/audio-map.js`
- `src/quality-checks.js`
- `assets/fonts/`
- `assets/photos/`
- `assets/video/`
- `assets/audio/`
- `assets/brand/`
- `config/motion-tokens.json`
- `config/beat-map.json`
- `config/render-config.json`
- `out/`
- `reports/`
- `DECISIONS.md`
- `README.md`

The initial HTML entry point may bundle the necessary logic into a single file when that is required by the execution environment. Keep logical separation in the source and preserve the ability to reproduce the build.

Use relative asset paths or explicitly configured local URLs. Do not invent assets or reference unverified paths.

The README must document the actual project structure, prerequisites, commands, asset licensing notes, render procedure, and tests that were genuinely executed.

---

## 27. Visual quality assurance

Quality assurance is mandatory.

Do not claim perfection based on one successful render or a few screenshots.

### A. Timeline validation

- Confirm that all 54 beats have entries.
- Confirm that all beat boundaries are consistent with the selected soundtrack.
- Verify the drop, breakdown, and final return.
- Confirm that every animation resolves to a valid final state.
- Detect timing gaps and conflicting animation tracks.
- Detect unintended simultaneous focal actions.

### B. Frame sampling

Render at least one representative frame per beat.

Also render additional samples at:

- Animation starts.
- Animation midpoints.
- Animation ends.
- Morph boundaries.
- Mask boundaries.
- Black-flood expansion.
- Iris opening and closing.
- Glass material transitions.
- Device transformation.
- Final loop boundary.

Inspect these frames visually.

### C. Frame-difference detection

Compute frame-to-frame differences and flag sudden spikes.

Use a threshold based on neighboring frames and known intended motion, not a rigid threshold that incorrectly flags every legitimate transition.

Detect:

- One-frame flashes.
- Unexpected exposure jumps.
- Geometry discontinuities.
- Missing objects.
- Stale video frames.
- Unintended black frames.
- Unexpected color shifts.
- Cursor jumps.
- Text reflow.
- Mask gaps.
- Single-frame pops.

Automated detection must produce a report that identifies timestamps and suspected causes.

A flagged frame is not automatically a bug; inspect it in context.

### D. Determinism tests

Render the same timestamps in different orders.

For example:

1. Render timestamps in ascending order.
2. Render selected timestamps in descending order.
3. Render the same timestamps again.
4. Compare outputs.

Verify that the same input state produces identical results, except for documented codec or GPU nondeterminism.

If GPU rendering introduces nondeterminism, quantify it, identify its source, and use a deterministic fallback for elements that require exact reproducibility.

### E. Static-frame validation

Choose a timestamp where the scene should be static.

Render the same timestamp repeatedly and verify that no unintended changes occur.

Do not flag legitimate source-footage motion as an animation error.

### F. Audio validation

- Inspect the audio waveform.
- Verify cue placement.
- Verify synchronization to visual contact points.
- Check integrated loudness and true peak.
- Listen to the film with audio.
- Listen to the soundtrack without video.
- Review the film muted.
- Check the final audio boundary if looping is required.

### G. Human review

Review the entire film at normal playback speed.

Also review:

- At reduced speed.
- Without audio.
- With audio only.
- At representative still frames.
- At native output resolution.

The final film must communicate its story without relying on technical complexity to hide unclear motion.

---

## 28. Performance and resource management

Optimize only after the visual system and timing are correct.

Prioritize:

1. Correct geometry.
2. Correct timing.
3. Correct continuity.
4. Correct compositing.
5. Readability.
6. Deterministic behavior.
7. Rendering performance.

Use caches for static masks, glyph geometry, displacement maps, and preprocessed image data where appropriate.

Avoid unnecessary allocations per frame.

Reuse canvases and offscreen buffers safely.

Avoid rendering unused layers.

Release resources that are no longer needed.

If WebGL or GPU-accelerated effects are used, provide an equivalent deterministic fallback when feasible.

Do not degrade the primary composition to preserve a decorative effect.

---

## 29. Common implementation pitfalls

Explicitly test for the following:

- SVG displacement filters that behave differently in Chromium.
- Glass sampling that accidentally includes the glass itself.
- Mask inheritance errors.
- Child elements appearing through hidden parents.
- Incorrect iris blade arcs.
- Black floods that fail to cover the canvas corners.
- One-frame gaps during shape morphs.
- Text revealed outside its intended mask.
- Variable-font axes that are unsupported or clamped.
- Inconsistent font rendering.
- Incorrect device bezel geometry.
- Browser UI elements that jump between states.
- Image decoding races.
- Video seeking that draws stale frames.
- Incorrect audio peak alignment.
- Motion blur that creates duplicate text.
- Subframe sampling that shifts event timing.
- Frame-count and timestamp drift.
- Accumulated floating-point errors.
- Unexpected alpha halos.
- Color-profile mismatches.
- Cursor scaling errors during camera zoom.
- Final-loop discontinuities.
- Unlicensed or missing media.
- Rendering that works only when frames are evaluated in chronological order.

For every discovered issue, record:

- Timestamp.
- Affected object or subsystem.
- Reproduction conditions.
- Root cause, if known.
- Fix.
- Regression test.

---

## 30. Final deliverables

Produce the following outputs where supported by the execution environment:

- `out/master_1440x1440.mp4`
- `out/contact-sheet.png`
- `out/representative-frames/open.png`
- `out/representative-frames/glass.png`
- `out/representative-frames/stage.png`
- `out/representative-frames/wall.png`
- `config/beat-map.json`
- `config/motion-tokens.json`
- `config/render-config.json`
- `reports/frame-difference-report.json`
- `reports/determinism-report.json`
- `reports/audio-validation-report.json`
- `reports/quality-assurance-report.json`
- `DECISIONS.md`
- `README.md`
- Complete source project.
- Captions and transcript if narration or spoken content is included.

Do not claim that these files exist unless they have actually been generated.

If the execution environment cannot render video, state the exact limitation and provide the complete runnable source and reproducible render commands rather than pretending the film was rendered.

---

## 31. Execution workflow

Follow this order:

### Phase 1 — Discovery
Inspect the inputs, verify assets, identify licensing concerns, and determine the creative constraints.

### Phase 2 — Creative direction
Establish the one-sentence idea, narrative progression, color system, typography, and motion principles.

### Phase 3 — Beat map
Produce the complete 54-beat map with musical timing, object continuity, and camera states.

### Phase 4 — Visual checkpoint
Produce the four representative frames: open, glass, stage, and wall.

### Phase 5 — Technical prototype
Implement the timeline, geometry primitives, camera, wordmark squeeze, and basic morph system.

### Phase 6 — Material systems
Implement the liquid-glass pipeline, iris, goo effect, image transitions, and frame construction.

### Phase 7 — Interaction and narrative
Implement the cursor interactions, device transitions, website, product selection, and fulfillment sequence.

### Phase 8 — Audio synchronization
Place the music and sound cues on measured timeline positions.

### Phase 9 — Render
Render the film with deterministic frame evaluation.

### Phase 10 — Validation
Run timeline, visual, audio, determinism, and output-file checks.

### Phase 11 — Refinement
Fix verified defects and rerun affected tests.

### Phase 12 — Delivery
Provide the final film, source, configuration, reports, and instructions.

Do not polish individual effects before the narrative timing and transitions work.

---

## 32. Final acceptance criteria

The film is ready for delivery only when the following criteria have been evaluated:

### Creative quality

- The visual identity is original and coherent.
- The story progresses clearly from identity to physical product.
- Major transformations are understandable.
- Motion has a clear purpose.
- The film does not feel like a generic template.
- The first and final compositions match.

### Animation quality

- All important movements have explicit timing.
- No unintended jumps or flashes are present.
- Morphs preserve object identity.
- The cursor is connected to the action it triggers.
- Text remains readable.
- The camera moves only with a clear purpose.
- Glass and liquid effects behave consistently.
- Black floods and iris transitions cover the canvas correctly.

### Technical quality

- The renderer evaluates arbitrary timestamps deterministically to the defined tolerance.
- Assets are loaded and validated before final rendering.
- The final video has the specified resolution, duration, frame rate, and audio configuration.
- Color and alpha handling are consistent.
- Frame-difference and determinism reports are available.
- The final output can be reproduced from the supplied source and configuration.

### Audio quality

- The soundtrack's actual tempo and structure have been inspected.
- Major events align with the intended musical beats.
- Sound effects support meaningful interactions.
- Loudness and peak levels have been measured.
- No clipping or unexpected synchronization errors are present.

### Delivery quality

- The rendered master exists and has been inspected.
- Source code and configuration are included.
- Asset licensing status is documented.
- Known limitations are disclosed.
- Only genuinely executed tests are marked as passed.

## 33. Final instruction

Create a film in which every object has a purpose, every transformation has a cause, every camera move preserves spatial understanding, and every beat advances the story.

The goal is not to maximize the number of effects.

The goal is to make a small number of transformations feel inevitable, precise, tactile, and memorable.

Use contemporary production practices, but prioritize visual clarity, deterministic behavior, reproducibility, and technical correctness over fashionable effects.

**Start by requesting the required inputs. Then present the beat map and four representative frames. Do not write the complete film implementation until the creative direction has been reviewed or the user has explicitly authorized autonomous continuation.**
