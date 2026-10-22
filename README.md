# Purisorn Portfolio

Recovered from the public Vercel deployment at <https://purisorn.vercel.app/> on 2026-10-22.

## Current structure

- `index.html` — portfolio landing page
- `bep.html`, `fastwork.html`, `gable.html`, `aiprojects.html` — case studies
- `resume.pdf` — current downloadable resume
- `images/` — deployed image assets

The recovered site is a buildless static project. Open `index.html` through a local HTTP server; no package installation or build step is required.

## Next implementation

1. Add a recruiter-focused print stylesheet and a clear **Download portfolio PDF** action.
2. Route downloads through a Vercel function so successful downloads can be counted.
3. Store the counter in durable storage and expose a private reporting view.
4. Connect this source to GitHub and then attach the repository to the existing Vercel project.

