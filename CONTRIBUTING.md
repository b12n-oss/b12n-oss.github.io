# Contributing

This repository is the [b12n-oss](https://github.com/b12n-oss) homepage, served
at <https://b12n-oss.github.io/>. Corrections are welcome, especially typos, a
dead link, or a project description that has gone out of date.

## Previewing a change

There is nothing to install and nothing to compile. Open `index.html` in a
browser and you are looking at the deployed page exactly as it renders.

```sh
open index.html
```

## The one rule

Keep it a single hand-written file with no build step. A homepage that says
three things does not need a pipeline, and the moment it grows a generator it
grows a way to break. If a change seems to need tooling, open an issue first
and say what it is for.

The rest, in rough order of how often it comes up:

- **Both colour schemes.** The page follows `prefers-color-scheme`. Check a
  change in dark and in light before opening a pull request.
- **The palette is matched, not chosen.** Copper is read off the
  [mcp-tkx docs site](https://b12n-oss.github.io/mcp-tkx/) stylesheet: `#ff7a3d`
  in dark, `#c8430c` in light, on a `#0d1117` ground. Do not adjust these by eye.
- **The mark lives in `assets/`.** `favicon.svg` and the inline SVG in
  `index.html` need to stay in step with it.
- **Projects are listed here and on the org profile.** The same list lives in
  [`b12n-oss/.github`](https://github.com/b12n-oss/.github). Update both, or say
  in the pull request that you did not.

## Deploying

GitHub Pages serves `main` from the repository root, so a merge to `main` is the
deploy. There is no workflow and nothing to trigger.

## Conduct

Everyone here follows the [Code of Conduct](CODE_OF_CONDUCT.md).
