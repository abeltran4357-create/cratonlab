# CratonLab

Geology lab tools, built on solid ground.

Free, browser-based tools for undergraduate geology labs:

- Thin-section mineral ID (PPL/XPL properties), interference colors, textures
- Sedimentary structures reference
- Interactive stereonet (Schmidt/Wulff), fold axis (π) finder
- Structural calculators: orientation converter, three-point problem, true thickness, depth, Mohr circle
- Practice problems with worked solutions, printable worksheets, bubble answer sheets and a grader

Everything is a single static file (`index.html`) with no build step and no server.
Sources are linked on each card and listed in the page footer.

## Publish with GitHub Pages

1. Create a new public repository and upload `index.html` (and this README) to the root of the `main` branch.
2. In the repository, open **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**, branch `main`, folder `/ (root)`, and save.
3. After a minute the site is live at `https://<your-username>.github.io/<repo-name>/`.

## Custom domain (optional)

1. Buy the domain from any registrar.
2. In **Settings → Pages → Custom domain**, enter the domain and save. GitHub adds a `CNAME` file to the repo.
3. At your registrar, add the DNS records GitHub's Pages documentation lists for an apex domain or a `www` subdomain.
4. Back in **Settings → Pages**, tick **Enforce HTTPS** once it becomes available.
