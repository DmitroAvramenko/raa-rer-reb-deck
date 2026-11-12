# RAA RER/REB deck - Compact EW System

Live deck: https://dmitroavramenko.github.io/raa-rer-reb-deck/
PDF (rebuilt on every change): https://dmitroavramenko.github.io/raa-rer-reb-deck/RAA_RER-REB_2026-11.pdf

## How to request a change

1. Open the **Issues** tab and create a new issue (or comment on an existing one).
2. Write `@claude` and what to change, for example:
   - `@claude slide 3: change the title to "..."`
   - `@claude remove slide 6`
   - `@claude slide 2: replace the second card text with "..."`
3. Within a few minutes Claude replies in the issue. The site and PDF update 1-2 minutes later (refresh the page).

## Adding photos

- Easiest: drag the photo into the issue together with the request, for example `@claude slide 5: replace the left photo with this one` or `@claude add a new slide after 4 with these two photos and caption "..."`.
- Or upload photos first: open the `assets` folder, **Add file -> Upload files**, commit; then ask `@claude` to use `assets/<file name>`.

You can also edit `index.html` directly in the browser: open the file on GitHub, press the pencil icon (or `.` for the full web editor), edit, and commit to `main`.

Only repository collaborators can trigger `@claude` or commit.
