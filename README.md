# CSS Mastery Challenges

Two CSS exercises: a keyframe animation and a z-index / positioning layout.

**Author:** Ibrahim Mackey
**Live pages (CODD):**
- Challenge 1: https://codd.cs.gsu.edu/~imackey1/web/INC/INC3/challenge1.html
- Challenge 2: https://codd.cs.gsu.edu/~imackey1/web/INC/INC3/challenge2.html

## Challenge 1: Animating the Answer
- `@keyframes moveFraction` moves the fraction `3/4` through three stages using `transform: translate()`:
  - 0%: yellow, `translate(-355px, 60px)`
  - 50%: `translate(0px, 60px)`
  - 100%: red, `translate(0px, 0px)`
- The animation starts 1 second after load via `animation-delay: 1s` in the `#answer` rule.
- `#question` has a hover effect (highlight and slight scale).

## Challenge 2: I (heart) NY T-Shirt
- The `img` uses `position: relative` to sit 10px to the right of its default spot.
- `.first`, `.heart` and `.last` use `position: absolute` inside a positioned container, with `z-index` placing them above the shirt.
- Finishing touches: border and padding frame, `box-shadow` on the shirt, and a background color on the container.

## Files
| File | Purpose |
|------|---------|
| `challenge1.html` | Animation challenge (embedded stylesheet) |
| `challenge2.html` | Positioning and z-index challenge (embedded stylesheet) |
| `tshirt.svg` | Plain white t-shirt image used by challenge 2 |

## Run locally
Open either HTML file in a modern browser. Keep `tshirt.svg` in the same folder as `challenge2.html`.
