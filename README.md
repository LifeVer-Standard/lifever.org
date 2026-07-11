# lifever.org

The website for [LifeVer](https://github.com/LifeVer-Standard/LifeVer) — the Semantic Life Versioning standard, a framework for tracking personal accomplishments and significant life events the way software projects track releases.

Live at **[lifever.org](https://lifever.org)**.

## What's here

This repo is the marketing/documentation site only. It's a single self-contained static page (`index.html`, Tailwind + Chart.js via CDN, no build step) that explains the standard and includes an interactive demo of a sample changelog.

The standard itself — `SPEC.md`, versioned independently of this site — lives in [LifeVer-Standard/LifeVer](https://github.com/LifeVer-Standard/LifeVer). That's the canonical source; nothing here should duplicate its text.

## Development

Open `index.html` directly, or serve the directory with any static file server. There's no build step.

## Deployment

Deployed to Cloudflare via `wrangler.jsonc`.

## License

This site's content is licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) — see [LICENSE.md](./LICENSE.md).

## Contributing

Issues and PRs are welcome. Site changes (copy, styling, the demo) belong here; changes to the standard itself belong in [LifeVer-Standard/LifeVer](https://github.com/LifeVer-Standard/LifeVer).
