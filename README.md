# nirvana-services

Static website for Nirvana IT Support. The site is served directly from the repository root; it has no build step or runtime dependencies.

## Deploy to Vercel

1. Import this repository in Vercel.
2. Set the project root directory to the repository root.
3. Deploy. `vercel.json` disables the build step and publishes the repository root, where `index.html` is the homepage. Future pushes to the connected branch deploy automatically.

To preview locally, open `index.html` in a browser or serve the repository root with any static file server.
