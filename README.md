# Portfolio Website

A static portfolio site with a homepage and six project pages.

## Structure

```
index.html                     (homepage)
project-loft-bed.html
project-lunabotics.html
project-machine-shop.html
project-nylok.html
project-robotics-research.html
project-spring-car.html
images/                        (all photos and logos)
videos/                        (all video clips)
```

## Publishing with GitHub Pages

1. Create a new repository on GitHub (public, so Pages can serve it for free).
2. Upload everything in this folder to the repo (drag-and-drop on github.com,
   or `git add . && git commit -m "Initial site" && git push` if using the
   command line).
3. In the repo, go to **Settings > Pages**.
4. Under "Build and deployment", set **Source** to "Deploy from a branch",
   choose the `main` branch and the `/ (root)` folder, then save.
5. GitHub will give you a URL like `https://<username>.github.io/<repo-name>/`
   within a minute or two.

## Notes

- `index.html` is required to be named exactly that for it to load as the
  homepage automatically.
- Several images in `images/` are 15-22MB, which is much larger than a web
  photo needs to be (they look like uncompressed screenshots/photos straight
  from a phone). The site will work as-is, but pages will load slowly. It's
  worth running the biggest ones through a compressor (e.g. tinypng.com)
  before or after publishing — that won't require touching the HTML, since
  the filenames would stay the same.
