# Shadow Triangles

An interactive 2D visualization of similar triangles formed by objects and their shadows.
Open `index.html` in any browser (no build step, no install).

- Drag the sun (or use the slider) to change the sun's angle θ. The sun's rays are drawn parallel.
- Drag the ○ handle on a person or the flagpole to change its height; drag the body to move it.
- Each object, its shadow, and the ray grazing its top form a right triangle; the table shows
  height ÷ shadow for each one, and they all match (they equal tan θ).
- **All the triangles, stacked** slides every triangle to share its shadow-tip corner, so the
  tops land on one line through the origin.
- **Real measuring error** rounds measurements and adds realistic error (fuzzy shadow edges,
  posture) so the ratios come out close but not identical, like real data from outside.
  "Measure again" re-rolls the error.
- **Mystery flagpole** hides the flagpole's height and solves for it from its shadow and the
  students' average ratio, then lets you reveal the real answer.
- Units toggle between feet/inches and meters.
