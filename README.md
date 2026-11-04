# Static website

A responsive Arvumi feature showcase built with plain HTML and CSS. It uses
Arvumi’s navy and blue palette and Soft Loop mark. No dependencies or build step.

Edit `index.html` for content and `style.css` for appearance. Preview with
`python3 -m http.server 8000`, then open http://localhost:8000.

The six feature summaries link to the Arvumi documentation. They describe platform
capabilities; this template itself is static and makes no API requests. The logo
and favicon are bundled locally in `soft-loop.png`.

Connect this repository to an Arvumi team and create a project. Leave the build,
install, root and output settings blank: Arvumi detects a static site automatically.
The default output directory is the repository root. Only keep files here that
are intended to be public; never commit secrets or private documents.
