# istdas.github.io
Intelligent, Sovereign &amp; Trustworthy Data, AI and Services

## How to update this page

All page content lives in [`index.md`](index.md). No HTML/CSS knowledge is needed.

- Group name, subtitle, tagline: edit the values in the front matter (the section between the `---` markers at the top of the file).
- Topics: add or edit entries under `topics:` — each has `label`, `title`, and `description`.
- People: add or edit entries under `people:` — each has `name`, `role`, an optional `url` (personal homepage, shown as a link on the name), and an optional `tag`.
- Meetings: add or edit entries under `meetings:` — each has `label`, `name`, an optional `description` (overview), `dates`, `location`, `contact`, and an optional `note`. To add a future meeting, copy the whole block of the first one and edit the values.
- Main text (About ISTDAS): edit the Markdown text after the closing `---`.

The design (colors, fonts, layout) lives in [`_layouts/default.html`](_layouts/default.html). You normally don't need to touch it.

Pushing to the `main` branch triggers a GitHub Pages build, and the changes go live at https://istdas.github.io within a minute or two.
