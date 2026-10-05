# fabric

A repo manifest that checks out the gyre dependency set as one workspace laid out on the sides of a hexagon.

## Use

`default.xml` gives each project a path, most of them on a numbered side, with its own remote and its own revision, so a project that omits either fails at init rather than inheriting a default. The libraries a build links are pinned to release tags. This repository holds the manifest and nothing else.

## Build and run

```sh
repo init -u https://github.com/V-Sekai-fire/fabric
repo sync
```

## Licence

MIT. See `LICENSE`.
