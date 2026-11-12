# RAA RER/REB deck (Compact EW System)

This repository is an 8-slide status deck (RIGHT&ABOVE, Compact EW System: drone detector + jammer), published with GitHub Pages:
https://dmitroavramenko.github.io/raa-rer-reb-deck/
The PDF is rebuilt automatically from `index.html` on every push: https://dmitroavramenko.github.io/raa-rer-reb-deck/RAA_RER-REB_2026-11.pdf

People request changes by mentioning `@claude` in a GitHub issue. Your job: make exactly the requested change to the slides, commit it, and reply briefly.

## Files

- `index.html` - the whole deck. Each slide is one `<section class="slide">...</section>` block, in order (slide N = the N-th `<section>`). Footer of each slide shows `NN / 08`.
- `<style>` at the top - shared brand CSS (classes `.bar`, `.kick`, `.abs`, `.ph`, `.cap`, `.lead`, `.cardt`, `.cardq`, `.tag`, `.foot` ...). Do not change it unless asked; reuse existing classes.
- The `<a class="dl">` link and the `<script>` right after `<body>` are the browser viewer (fit-to-width, PDF button). Never edit them.
- `assets/` - images, referenced as `assets/<name>`. `fonts/` - Onest and Russo One.
- `.github/workflows/` - never edit.

## Slide format

- Fixed canvas 297 x 167 mm (16:9, printed to PDF by headless Chrome). Positions are absolute in `mm` (`class="abs" style="left:..mm;top:..mm"`).
- Content must stay inside 14 mm side margins and above the footer. If text does not fit, shorten it rather than shrinking type below 9pt.
- Copy a neighbouring slide's markup when adding a new slide so it matches.

## Writing rules

- Language: English. Audience is a CEO/customer: plain words, no deep technical details unless asked.
- Brand is written `RIGHT&ABOVE` in text (no spaces), including the footer.
- Never use the em dash character (U+2014). Use a plain hyphen `-`.
- Keep a non-breaking space between a number and its unit (`10&nbsp;W`, `2.7&nbsp;GHz`).
- Do not invent numbers or test results. If a number is needed and not given, use a placeholder like `[__ m]`.
- Change only what was asked. Do not restyle or rewrite other slides.

## Adding, removing, reordering slides

- Add/remove/move whole `<section>` blocks, then update the `NN / TT` footer on every slide (TT = total slide count). The cover has no footer.

## Finishing

- Commit with a short message (for example: `Slide 3: shorten title`).
- Reply in the issue in the language the person wrote in: 1-3 lines on what changed, plus the link `https://dmitroavramenko.github.io/raa-rer-reb-deck/` and the PDF link. Mention the site and PDF update about 1-2 minutes after the change.
