# Signal / Portfolio — Md Mostak

A single-file personal portfolio themed around telecommunication and information theory.
Dark oscilloscope aesthetic, drifting bit particles, an FM wave packet that follows your
cursor (and flips bits near it — there's a live counter in the hero), TX ripple on click,
and a ⋮ menu on the left rail with all 13 sections.

**Files:** `index.html` (everything) + `profile.jpg` (your photo — you add this).

## Publish on GitHub Pages

1. Create a repository named `<your-username>.github.io` (or any repo name).
2. Upload `index.html` and a square photo named `profile.jpg` to the repo root.
3. Repo → **Settings → Pages** → Source: *Deploy from a branch* → Branch: `main` → Save.

Your site goes live at `https://<your-username>.github.io/` within a minute or two.
(If you used a differently-named repo, the URL is `https://<username>.github.io/<repo>/`.)

## Edit your content

- Open `index.html` and search for **`✎ EDIT`** — every editable spot is marked.
- Sections: Home · Education · Skills · Work · Volunteering · Hobbies · Interests ·
  Sports · Personality · Family · Life Goals · Self-Reflection · Contact.
- Each section contains **sub-section blocks** (timeline items, cards, chips, terminal
  lines). Copy-paste any block to add more entries.
- Skill bars: change the number in `style="--v:85%"`.
- Rotating hero roles: edit the `ROLES` array near the bottom of the file.
- Personality radar: retune the `<polygon id="radarPoly">` points (labels next to it).
- Social links + email appear twice: once in the left rail, once in the Contact section.

## Notes

- No frameworks, no build step, no trackers — plain HTML/CSS/JS.
- Respects `prefers-reduced-motion`; custom cursor auto-disables on touch devices.
- Bracketed text like `[Your University]` is a placeholder waiting for you.
