# Clinical Exam Coach

A single-page study tool for the 7CL504 clinical exam (MSc Integrative Counselling and Psychotherapy).

## Deploy on Render

1. In Render, choose **New > Static Site** (or **New > Blueprint** to use `render.yaml`).
2. Connect this GitHub repository.
3. Leave the build command empty and set the publish directory to `.`.
4. Deploy. Every push to `main` redeploys automatically.

## Notes

- Progress is saved in the browser. Use **Export progress** and **Import progress** (page footer) to move it between devices.
- "Copy marking prompt" copies a rubric-based marking prompt to paste into Claude.
- The site sends a `noindex` header so search engines do not list it. Anyone with the link can still open it.
