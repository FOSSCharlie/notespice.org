# notespice.org

[#notespiceorg](#notespiceorg)

The landing page for [Notespice](https://github.com/FOSSCharlie/notespice),
a self-hosted, database-less notes app.

**Live site:** [notespice.org](https://notespice.org)

## What's here

[#whats-here](#whats-here)

This repo is just one file: `index.html`. No build step, no
dependencies to install, no framework — open it in a browser and
that's the whole site.

The page includes a working miniature version of the real editor right
in the hero section (type some markdown, toggle Writer/Markdown, watch
it render) so visitors can try the interface before installing
anything.

## Local preview

[#local-preview](#local-preview)

Since it's a single static file, you can preview it by opening
`index.html` directly in a browser, or serve it locally with whatever
you have handy, e.g.:

```
python3 -m http.server 8000
```

then visit `http://localhost:8000`.

## Deployment

[#deployment](#deployment)

The site is hosted on **GitHub Pages**, deployed straight from the
`main` branch of this repo (root folder). Pushing to `main` updates
the live site automatically — no CI/CD pipeline required.

The custom domain (`notespice.org`) is configured via:

- A `CNAME` file in this repo (added automatically by GitHub when the
  custom domain is set in **Settings → Pages**)
- DNS `A` records at the domain registrar pointing to GitHub Pages'
  IP addresses

## Related

[#related](#related)

- [FOSSCharlie/notespice](https://github.com/FOSSCharlie/notespice) —
  the Notespice app itself (Docker image, source code, releases)

## Changelog

[#changelog](#changelog)

See [CHANGELOG.md](./CHANGELOG.md) for a history of changes to this
site.

## License

[#license](#license)

MIT — same as the Notespice app. See the
[main repo's license](https://github.com/FOSSCharlie/notespice/blob/main/LICENSE).
