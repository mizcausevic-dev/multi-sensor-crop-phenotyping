# Multi-Sensor Crop Phenotyping Platform

Deterministic 34-second explainer of an example multi-sensor crop phenotyping pass. Observable traits only. Uncertainty stays visible. Not a yield guarantee and not a genotype readout.

**Review status:** conceptual, source-informed working brief. Not a certified engineering design.

## Watch

Live preview, once Pages is serving the `pages` branch: https://mizcausevic-dev.github.io/multi-sensor-crop-phenotyping/

Open `index.html`. The film is 1,020 frames at 30 fps, indexed 0-1019. Display fonts load from the Fontsource CDN, with system fonts as the fallback. The SIL license is in `fonts/OFL-1.1.txt`.

- Space: play or pause
- Left and right arrows: one frame
- Home and End: the ends
- `?frame=430` opens that still
- `?play=0` stays paused

If the browser asks for reduced motion, the film does not autoplay. Chapter buttons still jump to a still.

## What you are looking at

1. **0-5 s.** An example research plot and a ground vehicle with a boom across three plots, following a planned route.
2. **5-10 s.** Image, environment, and position as separate streams, with one example clock and calibration markers.
3. **10-17 s.** Enlarged, slowed canopy section. Occluded and missing regions stay marked unobserved.
4. **17-25 s.** Canopy coverage on observed cells, visible pod counts, and a five-plant comparison with a human reference.
5. **25-34 s.** Time compression across five example visits, then a held view of the whole example system.

## Source boundary

Mechanism source: USDA ARS project [448131](https://www.ars.usda.gov/research/project/?accnNo=448131), checked 20 Oct 2026. The project describes a multi-sensor platform on an unmanned ground vehicle for soybean, pea, and dry bean, including route planning and pod detection.

The same project also describes yield models and genomic selection as separate objectives. This film does not depict those objectives. Dimensions, clocks, environmental words, and counts are staging. See `safeguards-Cursor.md`.

The Medium essay is `medium-article-Cursor.md`.

## Repo

- `index.html` is the player and the safeguards in selectable text.
- `explainer.js` draws each frame from the frame index only.
- Display fonts load from the Fontsource CDN. The SIL Open Font License text is in `fonts/OFL-1.1.txt`.

No build step. GitHub Pages serves this directory from the `pages` branch.
