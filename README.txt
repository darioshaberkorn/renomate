RenoMate Australia - app MVP

This is a Progressive Web App (PWA).

To run locally for testing:
1. In this folder, start a local web server. Example with Python 3:
   python3 -m http.server 8080
2. Open http://localhost:8080/ in a browser.

To install on iPhone:
- Host the folder on an HTTPS web host (Vercel/Netlify/GitHub Pages, etc.).
- Open the HTTPS URL in Safari.
- Tap Share -> Add to Home Screen.

The MVP stores project data in the browser's localStorage. Use Project -> Export backup to save a JSON backup.
