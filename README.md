# QuietByte site

Landing page for https://github.com/quietbytehq, served by GitHub Pages.

## Add or update a project

Edit `projects.json` only. Each entry:

```json
{
  "name": "My App",
  "tagline": "One line.",
  "description": "Two sentences max.",
  "status": "released | development | planned",
  "version": "v0.1.0",
  "platforms": ["Linux", "Windows"],
  "license": "Apache-2.0",
  "repo": "https://github.com/quietbytehq/my-app",
  "download": "https://github.com/quietbytehq/my-app/releases/latest"
}
```

Leave out `repo`/`download` while a project is private; the card shows "Coming soon".

## Publish

1. Create a public repo named `quietbytehq.github.io` in the org.
2. Put `index.html`, `projects.json`, `README.md` in the root of `main`.
3. Settings > Pages > Deploy from branch > `main` / root.
4. Site appears at https://quietbytehq.github.io
