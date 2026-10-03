# AI in Education — The Learning Lab

An interactive static website based on AI_in_Education_Visual_Edition.pptx, with a university education focus and a proposed pilot for Kazakhstan.

## Run locally

From this folder, run:

    python3 -m http.server 8000 --directory dist

Then open http://localhost:8000 in your browser. JavaScript modules need an HTTP server; double-clicking index.html is not supported.

## Edit

- dist/index.html: header and hero
- dist/app.js: research sections, charts, country tabs and learning workflow
- dist/models.js: the interactive Three.js neural network and AI processor
- dist/style.css: responsive styling and motion
- dist/assets/references.json: 22 references extracted from presentation notes

Three.js and Lucide are bundled locally. Google Fonts loads online with system-font fallbacks. No backend or live AI API is required. The study dialogue is explicitly a scripted illustration.

## Content

The data and limitations follow the supplied presentation, dated 3 October 2026. This is a desk-study website, not a report of a completed local experiment. The 12-week pilot is a proposal. Product pricing and eligibility are labelled as a presentation snapshot. The source assignment informed the research structure; its separate written-report deliverables were not treated as a request to create a new report.

## Interaction and accessibility

Drag a model to rotate; use arrow keys when the canvas is focused; use Ctrl/Command + scroll or + / - to zoom. Model controls allow switching, pausing and resetting. Reduced-motion preferences pause automatic rotation and remove reveal transitions. Devices without WebGL receive a conceptual illustration. Country and workflow tabs support left/right arrow keys, Home and End.

Artwork is supplied conceptual AI-generated imagery from the presentation. Three.js uses the MIT license; Lucide uses the ISC license. See the license files in dist/assets.
