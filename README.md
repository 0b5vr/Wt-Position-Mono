# Wt-Position-Mono

A monospace equivalent of https://github.com/0b5vr/Wt-Position

## How to build

### Prerequisite

- Affinity Designer
- Fontforge
- Node.js

### Steps

- 1, Export all chars in Wt-Position-Mono.afdesign

- 2, Run the commends:

```sh
node prepare-svg.js
fontforge --script main.pe
```
