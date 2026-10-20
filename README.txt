BUILT DIFFERENT — PERSONAL TRAINING HQ

Files: index.html, app.js, sw.js, manifest.webmanifest, icon-192.png, icon-512.png.

INSTALL ON IPHONE
1. Upload all six files together to an HTTPS static web host (e.g. Netlify Drop or GitHub Pages). Keep them in the same folder.
2. Open your hosted URL in Safari on your iPhone.
3. Tap Share > Add to Home Screen > Add (or choose Open as Web App when offered).
4. Launch Built Different from your home screen.

EASIEST HOSTING: NETLIFY DROP
1. On a computer, unzip this package.
2. Go to https://app.netlify.com/drop and drag the unzipped fitcoach folder onto the upload area. Follow any account/setup prompts.
3. Open the generated HTTPS site URL on your iPhone in Safari and add it to your home screen.

DATA AND LIMITATIONS
- All data is stored locally in the browser/PWA using localStorage. No account, backend, or cross-device synchronization.
- Export JSON backups regularly from History. Import them to restore or transfer data.
- Clearing website data, deleting the app, or browser storage eviction can remove entries.
- Smart recommendations are rule-based, not AI model-generated or medically validated. Load suggestions use the last logged load, not full set-by-set performance.
- Log loads in kg. No Apple Health integration, notifications, or cloud backup.
- The app can work offline after its initial HTTPS installation, subject to browser cache behavior.
- Exercise targets are general; adjust for comfort, form, and individual needs.

VERSION 2 — AI COACH BRIDGE
The Coach tab copies workout context to ChatGPT. It does NOT contain a paid AI API or automatically synchronize with ChatGPT. Copy the response's JSON workout into the import box, preview, then approve. Quick Adjust works offline. The app stores data locally; back up before clearing browser data.
To update an existing deployment, upload this folder to the SAME hosting site/address and refresh the installed app online. If the address changes, browser data will not transfer; export backup first and import on the new site.

VERSION 3 MUSIC FEATURES
Music tab offers Spotify playlist search links matched to workout and manually selected music taste, plus saved playlist links. It does not log into Spotify, read listening history, or control playback. An actual Spotify account integration would require Spotify developer registration, OAuth PKCE, an exact HTTPS redirect URI, and user authorization.
Update the SAME hosted URL to retain your existing workout history. Music preferences are stored separately in browser local storage.
