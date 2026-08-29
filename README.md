# kevinle.tech (v1, archived)

> Deprecated. This is the first version of my portfolio, kept for reference.
> The site it powered has moved on, and this repo is no longer deployed.

My cybersecurity portfolio. Case-file theme, with a Minecraft GUI mode you can
toggle in the top right.

Hand-written HTML, CSS and vanilla JS. No framework, no build step, no npm.

## Files

```
index.html              structure
assets/css/dossier.css  default theme
assets/css/gui.css      Minecraft skin, layered on data-theme="gui"
assets/js/casefiles.js  all of the content
assets/js/app.js        routing + rendering
```

## Notes

- Writeup fields accept ``` fenced code blocks, so decompiled source can be
  pasted in raw. It gets escaped, not executed.
- `redacted: true` blacks out a finding's mod name and version, used while
  something was still unpatched.
- Theme choice is saved to `localStorage` and applied before first paint.
- The whole thing prints cleanly, so it can be attached to an email as a PDF.
