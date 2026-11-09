# Shadow Triangles

Interactive 2D visualizations of similar triangles, in two tabs: **Shadows** and **Mirror**.
Open `index.html` in any browser (no build step, no install).

## Shadows tab

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

## Mirror tab

A mirror lies flat on the ground between a student and either a tree or a second student.
Because the angle of incidence equals the angle of reflection, the student's triangle
(eye, feet, mirror) is similar to the far triangle (top, base, mirror) once the top lines up.

- Drag the student, the mirror, or the tree/second student; drag the ○ handles to change heights.
- The light from the top (or the other student's eyes) is drawn bouncing off the mirror. When it
  misses the student's eye, a bracket shows by how much and the status says to step closer or back.
  **Move to the right spot** slides the student to where the reflection lines up.
- The solver shows H ÷ d₂ = e ÷ d₁ with the current numbers, warns when the triangles aren't
  similar yet, and can reveal the real height.
- **Flip one triangle over the mirror** draws both triangles from the mirror corner so you can see
  the small one fit inside the big one when lined up.
- Link straight to a tab with `index.html#shadows` or `index.html#mirror`.
