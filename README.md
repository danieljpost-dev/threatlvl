# threatlvl.danieljpost.dev

Public site for ThreatLVL, built with [Zola](https://www.getzola.org/) and deployed to GitHub
Pages by `.github/workflows/static.yml`.

## Local development

```sh
zola serve      # http://127.0.0.1:1111
zola build      # output in public/
```

## Generated files — do not edit

| Path | Source |
|---|---|
| `content/features/_index.md` | `Clients/ThreatLVL/plans/features/*.md` in the notes vault |
| `sass/_variables.scss` | `shared-css/src/variables.css` (canonical branding) |

Both are produced by `Clients/ThreatLVL/bin/features-build`. Edit the sources and re-run it;
changes made here are overwritten.
