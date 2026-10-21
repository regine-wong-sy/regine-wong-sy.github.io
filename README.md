# regine.rtis

Personal portfolio site. Single static page, no build step.

The hero is a live pathfinding demo: click the grid and the agent runs A* (8-directional, no corner cutting), drops collinear waypoints, then follows a Catmull-Rom spline through what's left.

## Run locally

Open `index.html` in a browser.

## Deploy

GitHub Pages, served from the `main` branch root.

## Structure

```
index.html   markup, styles and the canvas demo
img/         me.jpg (portrait) + project screenshots (behaviour-tree.png, deferred-renderer.png)
resume.pdf   linked from the contact section
```
