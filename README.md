# Business Analytics Organization Website

Website for the Business Analytics Organization (BAO) at the University of Illinois Chicago. The site was generated with Hugo, and the HTML served by GitHub Pages lives in `docs/`.

## Getting Started

Open the repository folder in VS Code. If you need a local copy, clone the fork:

```bash
git clone https://github.com/petite-alice/BusinessAnalyticsOrganization.github.io.git bao-site
cd bao-site
```

In VS Code, select **Terminal → New Terminal** and start the local server from the repository folder. You’ll need Python 3.

```bash
python3 -m http.server 8000 --bind 127.0.0.1 --directory docs
```

Open [http://127.0.0.1:8000/](http://127.0.0.1:8000/) while the server is running. Press **Control+C** to stop it.

Edit [the homepage](docs/index.html), [the About page](docs/about/index.html), or [the Contact page](docs/contact/index.html) in VS Code. Save the file and refresh your browser to see your changes.

## Deploy on GitHub Pages

In your fork, go to **Settings → Pages** and select **Deploy from a branch**. Choose **`main`** and **`/docs`**, then click **Save**. After deployment, the public URL appears in Pages settings.

If the public URL includes the repository name after `github.io`, links starting with `/` may need the repository prefix. The local preview works at the domain root.
