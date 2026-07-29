# palashpanchal03.github.io

Personal portfolio — [palashpanchal03.github.io](https://palashpanchal03.github.io)

A single-file, scroll-driven site. No framework, no build step, no npm: all the
CSS, 2D canvas and WebGL live inside `index.html`.

```
.
├─ index.html            ← the whole site
└─ assets/
   ├─ metal-human.mp4    ← hero background loop
   └─ metal-human.jpg    ← poster still / finale figure source
```

## Local preview

```bash
python -m http.server 5599
```

Then open <http://localhost:5599>.

Serve it rather than opening `index.html` directly — on `file://` the browser
refuses to read pixels out of `metal-human.jpg`, so the finale figure falls back
to a procedurally generated silhouette instead of the real photo. Everything
else works either way.

## Credits

Hero video and poster still © [GetLayers](https://getlayers.ai).
