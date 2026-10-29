eBOSS & RPTACS Demo (installable web app)

RUN
1. Serve this folder with any local web server, for example:
   - VS Code Live Server: right-click index.html > Open with Live Server
   - Python: python -m http.server 8080   then open http://localhost:8080/
2. The app opens automatically because the page is index.html.
3. Click "Tutorial" in the header for a step-by-step guide.

INSTALL
- Chrome / Edge: click "Install app" in the header, or the install icon in the address bar.
- Android: browser menu > Install app / Add to Home screen.
- iPhone / iPad (Safari): Share > Add to Home Screen.
After the first load it works offline.

NOTES
- Must be served over http://localhost, http://127.0.0.1 or https:// for install and offline mode.
  Opening index.html by double-clicking (file://) works, but cannot be installed.
- All records and compressed photos are saved in the browser's IndexedDB on this device.
- After changing files, bump CACHE in sw.js (eboss-rptacs-v2, ...) so installed copies update.
