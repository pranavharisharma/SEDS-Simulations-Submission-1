# Week 2 — The Sandbox

Cellular automata with falling sand and water.

- **Spec:** [`week2.pdf`](./week2.pdf) — read it first, it is the authority.
- **Template:** [`temp.py`](./temp.py) — runs as-is, but the physics is missing.
  One `NotImplementedError` in `SandSim.update()`: sand fall/slide and water
  spread. Fire, smoke, and wood are the bonus.
- **Setup:** see the [root README](../README.md).

**Due: EOD, 23rd September 2026.**

## Your brief goes here

**Replace this file with your assignment brief.** It must contain your answers to
**Question 1** and **Question 2**.
1.The swap grid is a copy of the current grid and not fully filled with zeroes as than all stationary particles remain in the same position and we do not need to rewrite the code to place the stationary cells too.A grain that does not move would simply dissapear in the next frame if it was not a copy.
2.When it is fixed left to right the sand piles on the left will slide away from a peak first before the right and this will cause piles leaning heavily to one side.

Half a page is plenty.