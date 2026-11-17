# bekzhan.com

Personal portfolio. One plain HTML file (blueprint / technical-drawing style), hosted on GitHub Pages.

| What to change | Where |
|---|---|
| Name, intro, buttons | `index.html`, the `HOME: intro` block |
| Tabs (Projects, About, Contact…) | `index.html`, each `<section class="sheet">` (copy one to add a tab) |
| Project cards | `index.html`, Projects section (`id="p-001"` etc.) |
| Numbered balloons on the drawing | `index.html`, `<svg class="drawing balloons">` (`data-target` = card id) |
| Colors, fonts | `index.html`, the `<style>` block at the top |
| CV button | add `cv.pdf` here, then un-comment the button in `index.html` |

`css/`, `js/` and `projects/project-template.html` are from the first version; the main page no longer uses them.

Preview locally: just double-click `index.html`.
