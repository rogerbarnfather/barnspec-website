# Barnspec website

Part of [Barn](https://rogerbarnfather.github.io/barn-website/).

The website for [Barnspec](https://packagist.org/packages/rmb32/barnspec): an introduction, the
philosophy, a quick start and the documentation. Static HTML, no build step; open `index.html` in a
browser. Links between pages are relative, because GitHub Pages serves a project site from a subpath.

- `assets/base/`: the shared Barn website stylesheet. An identical copy of the main site's, checked by
  `bin/ci-all` in the suite folder. Don't edit it here.
- `assets/site.css`: Barnspec's own components.
- `assets/screens/`: real captures of the tool, 2× resolution, from a disposable barn with made-up
  hotel data. `spec-map` and `spec-work` are copies of the main site's.
- `docs/style-guide.md`: this site's style guide.
