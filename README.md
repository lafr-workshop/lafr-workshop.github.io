# Learning and Formal Methods for Robotics (LAFR) — IROS 2026 Workshop

Website for the **Learning and Formal Methods for Robotics** workshop at IROS 2026 (Pittsburgh, PA, September 27, 2026).

## GitHub Pages setup

1. **Push this repo to GitHub** (e.g. `https://github.com/yourusername/IROS-2026-Workshop`).

2. **Enable GitHub Pages**
   - Open the repo on GitHub → **Settings** → **Pages**.
   - Under **Build and deployment**:
     - **Source:** Deploy from a branch
     - **Branch:** `main` (or your default branch), folder **/ (root)**.
   - Save. GitHub will build and deploy within a minute or two.

3. **View the site**  
   Your workshop site will be at:
   ```text
   https://<your-username>.github.io/IROS-2026-Workshop/
   ```
   (Replace `<your-username>` and `IROS-2026-Workshop` with your GitHub username and repo name.)

### Notes

- The **`.nojekyll`** file in the repo tells GitHub Pages to serve the site as plain HTML (no Jekyll), so `index.html` and assets work as-is.
- To use **local photos** (e.g. speaker/organizer headshots), add image files under `images/` and point the `<img>` tags in `index.html` to `images/Filename.jpg`. See `images/README.md` for suggested filenames.
