# Changelog

## Unreleased

- Fixed note title and content in the demo appearing center-justified
  (inherited from the hero section's centered layout) instead of
  left-justified, matching how markdown/notes actually render.
- Fixed the demo's Code and Checkbox-list toolbar buttons inserting
  visible placeholder text when nothing was selected, instead of
  leaving the cursor ready to type. Also fixed the footnote button
  using `innerHTML +=` to append its definition stub, which
  unnecessarily reparses the whole editor's content.
- Added a favicon (embedded, no extra file).
- Hero is now a single stacked column (text, then demo, then caption)
  instead of two-column, matching the requested layout.
- Demo card now has the full toolbar (heading levels, GitHub-style
  callouts, tables, footnotes, links/images/attachments) and a working
  Delete button with confirmation, ported directly from the real app —
  not a simplified stand-in.

## 1.0.0 — 2026-07-22

Initial release.

- One-page landing site: hero with a working embedded Writer/Markdown
  demo, "why" section, feature grid, Docker Compose get-started guide,
  footer links.
- Self-hosted Inter typeface and embedded logo — no external font or
  image requests at all.
- Monochrome window-control icons in the demo card (not macOS-style
  colored traffic lights).
