# Chenura Gajanayake — Profile

A polished, responsive personal profile page built with plain HTML, CSS, and JavaScript. It is ready to deploy as a static GitHub Pages site.

## Local preview

No build step or dependencies are required. From the repository root, start any local static server:

```bash
python -m http.server 8000
```

Then open [http://localhost:8000](http://localhost:8000) in a browser. Stop the server with `Ctrl+C`.

## Deploy to GitHub Pages

1. Push the repository to GitHub.
2. Open **Settings → Pages** in the repository.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the `master` branch and the `/ (root)` folder, then click **Save**.
5. Wait for the Pages workflow to finish. GitHub will display the published URL in the same Pages panel.

Because the site uses relative asset paths and no server-side features, it can also be hosted from any static hosting provider.
