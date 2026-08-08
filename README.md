# Wt-Position-Mono

A monospace equivalent of https://github.com/0b5vr/Wt-Position

## How to build

### Prerequisite

- Affinity
- Fontforge
- Node.js

### Steps

- 1, Export all chars in Wt-Position-Mono.af to `/glyphs`

- 2, Run:

```sh
npm install
node prepare-svg.js
fontforge --script main.pe
```
