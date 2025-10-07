# TaskMate (Web)

Static build of the app for GitHub Pages. Serves files from the `web/` folder.

## Deploy (GitHub Pages)
1. Push code to a public repo on GitHub (main branch).
2. The included workflow `.github/workflows/deploy.yml` publishes the `web/` folder to Pages.
3. In repo Settings → Pages, Source should be GitHub Actions.
4. After the workflow finishes, your site will be available at:
   `https://<your-user>.github.io/<repo-name>/`.

## Notifications
- Web Notifications require HTTPS and the page to be open.
- Go to Settings → Enable Notifications → Test Notification.

For background notifications when the app is closed, use the Capacitor (Android) build instead.
