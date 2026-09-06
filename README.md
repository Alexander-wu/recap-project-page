# ReCAP project page

Static, dependency-free project page suitable for GitHub Pages, Netlify, or any
basic web server.

Preview locally:

```bash
python3 -m http.server 8000
```

Run the command from this directory, then open `http://localhost:8000`.

The page is intentionally not deployed automatically. Because the manuscript
is under double-blind review, verify the author and affiliation policy before
publishing it publicly.

## BridgeV2 qualitative examples

The rollout gallery includes three BridgeV2 validation examples. Each contains
one observed frame and 32 future predictions, with identical actions and seed
for Full Context and ReCAP. The examples were selected from 24 candidates by
relative mean LPIPS improvement, then visually reviewed; they are qualitative
examples, not full-validation-set averages. PSNR badges exclude the observed frame.
The task descriptions are episode metadata, not language inputs to the model.
GIFs use all 33 original frames, resized for display, with no temporal interpolation.
Per-case metrics and protocol metadata are recorded in `assets/gifs/cases.json`.
