# klar-clinic-ds

A standalone, token-driven **design system** reconstructed from the Klar Clinic
(Dr Sophie Lantz Stockholm) site — rebuilt cleanly from scratch, depending on
nothing but a single stylesheet.

- **`style.css`** — the single source of truth: design tokens (`:root`),
  reset & base, layout primitives, components, token-mapped utilities,
  responsive breakpoints, and a `.dark` theme.
- **`design-system/design-system.html`** — a living style guide that renders
  every token and component live from `/style.css`.
- **`index.html`** — the clinic site re-skinned onto the design system
  (markup, scripts, images, and content preserved).

## Run locally

Serve the directory root (pages reference `/style.css` as a root-absolute path):

```bash
python3 -m http.server
```

Then open <http://localhost:8000/> and the style guide at
<http://localhost:8000/design-system/design-system.html>.
