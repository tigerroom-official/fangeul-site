# Landing page assets

The landing page reuses the Fangeul app's marketing-v5 image crops, taken from
actual screen-shot-v3 captures. Images are copied without visual changes.
`source-manifest.json` records the upstream capture paths, crop coordinates,
and hashes. The bubble icon comes from marketing-v5/images/fangeul-icon.png.
All paths in the manifest are relative to the upstream app repository.

The hero's video background is a CSS illustration. It contains no artist,
group, platform logo, or video content. Personalized examples use “Fangeul”.
The theme capture retains the paid options' lock indicators.

Manrope and Barlow Condensed are served locally, with their SIL Open Font
License files alongside them. Korean uses the system sans-serif font.

Deployment still uses the root index.html. No build step is required.
