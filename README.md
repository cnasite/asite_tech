# Asite Intelligence — Preview Site (Roma)

The asite.tech showcase flow rebuilt in Asite's **Roma** visual language — a strict,
fully achromatic editorial system where red survives only in the Asite logo, error
states, and the Asite Intelligence accent (Neo Red).

## Pages
- `index.html` — landing / workspace chooser
- `gate.html` — AI Coworkers access gate
- `coworkers.html` — "Meet your Asite Coworker" agent hub
- `wir-coach.html` — WIR Coach experience (Work Inspection Request create form + AI readiness)

## Structure
Self-contained. No external dependencies.

```
asite_tech/
├── index.html
├── gate.html
├── coworkers.html
└── assets/
    ├── roma.css          # Roma design system (tokens + components)
    ├── app.css           # showcase layout
    ├── fonts/            # Inter + JetBrains Mono (woff2)
    └── logos/           # verbatim Asite logo set
```

## Deploy (GitHub Pages)
Push this folder to a repo and enable Pages, or serve the folder root. All asset
paths are relative, so it works from any subpath.

## Notes
- Flow: `index.html` → `gate.html` → `coworkers.html`.
- The gate accepts any non-empty value (front-end prototype; wire real auth server-side).
- Agent "Open experience" links are placeholders — individual agent experiences are a
  future build.
