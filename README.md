# Bloom · Placement Study Planner PWA

This package contains the web/PWA version of Bloom. The original Bloom interface and planner logic are preserved; the PWA layer adds an installable web-app manifest and a service worker for offline app-shell caching.

## Free publishing with GitHub Pages

1. Create a new GitHub repository, for example `bloom-placement-planner`.
2. Upload everything in this folder to the repository root. `index.html` must be at the repository root.
3. In GitHub, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`, then save.
6. Wait for GitHub Pages to publish the site.
7. Open the generated HTTPS URL in Chrome.
8. In Chrome, use the browser's **Install Bloom** / **Install app** option when it appears in the menu or address bar.

The app stores planner state locally in the browser. It does not include a server or user account system.

## Important

PWA installation and service workers require a secure context. GitHub Pages provides HTTPS, so it is suitable for this package.
