# Wine in motion

An interactive 2D wine bottle with a self-contained liquid simulation. Open `index.html` in a modern browser. No installation, build step, external libraries, or internet connection is required.

## Controls

- Drag around the bottle to rotate it with a mouse, pen, or touch.
- Use the rotation slider or 45-degree buttons for controlled turns.
- Adjust the fill level from 15% to 85%.
- Pause, resume, reset, or return the bottle upright.
- Keyboard: left/right arrows rotate, Space pauses, and R resets.

## Physics

A hybrid FLIP/PIC particle and grid solver handles gravity, pressure projection, moving walls, and numerical viscosity. The bottle is corked, so the wine stays contained through complete rotations. A fixed particle count represents the liquid volume until the fill level changes.

This is a real-time 2D approximation, not an engineering-grade simulation. Fluid resolution, numerical damping, and rotation limits balance stability and performance.

## Files

- `index.html` — the complete page, styles, drawing, and simulation.
- `.nojekyll` — serves the files directly on GitHub Pages.

No analytics or external network requests are included in the page.
