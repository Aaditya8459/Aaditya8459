# Publish the reference-matched GitHub profile

1. Open https://github.com/Aaditya8459/Aaditya8459 (the profile README repository).
2. Upload `README.md`, the `assets/` folder, and `.github/workflows/snake.yml` at the repository root.
3. Commit to the default branch (the workflow currently listens to `main`; if your default branch has another name, edit the `push.branches` value in `snake.yml`).
4. Open the repository's **Actions** tab and run **Generate contribution snake** once.
5. The workflow publishes the animated snake to the `output` branch. The README embeds that SVG.
6. Check the rendered README and adjust any third-party image service if it is temporarily unavailable.

The banner GIF is included locally in `assets/`; the README does not depend on a remote image host for its main artwork.
