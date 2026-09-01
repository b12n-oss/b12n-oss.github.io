# b12n-oss.github.io

The organization homepage for [b12n-oss](https://github.com/b12n-oss), served
at <https://b12n-oss.github.io/>.

`b12n` is a numeronym for `burinchoomnuan`: the first letter, the twelve in
between, then the last. The same trick as `i18n` and `k8s`.

## What is here

```
index.html    the whole page, self-contained
favicon.svg   the mark, at favicon size
assets/       the mark as standalone files, for avatars and anywhere else
```

One hand-written file with no build step and no dependencies, because a
homepage that says three things does not need a pipeline. It renders from
`index.html` exactly as committed.

Open `index.html` in a browser to preview it. There is nothing to install and
nothing to compile.

## Design

The palette is the same copper the
[mcp-tkx docs site](https://b12n-oss.github.io/mcp-tkx/) uses, read off that
site's own stylesheet rather than matched by eye: `#ff7a3d` in dark and
`#c8430c` in light, on a `#0d1117` ground. That stylesheet names the accent
"Copper, solder and wire, the material of", which the interlocking rings suit.

The mark is two rings that genuinely interlock rather than overlap. One passes
over at the top crossing and under at the bottom, which is the whole idea:
two parties joined by a protocol.

The page follows the viewer's `prefers-color-scheme`.

## Publishing

GitHub Pages serves `main` from the repository root. A push to `main` is a
deploy, so there is no workflow and nothing to trigger.
