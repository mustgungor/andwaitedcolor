ANDWAITED COLOR ARCHIVE — Safari/PWA build

WHAT THIS FIXES
- iPhone/iPad Safari touch sizing and safe-area spacing
- 16px search input to prevent unwanted iOS zoom
- Clipboard API on HTTPS, with execCommand fallback
- If Safari still blocks copy, a manual-copy sheet opens with the text pre-selected
- PWA manifest + Apple touch icon
- Offline cache after first HTTPS visit

IMPORTANT
A PWA/service worker cannot run from file://. Publish this folder on any HTTPS static host.

FASTEST DEPLOY
1. Upload the entire folder to a static host (Netlify, Vercel, Cloudflare Pages, GitHub Pages, etc.).
2. Open the HTTPS URL in Safari.
3. iPhone/iPad: Share > Add to Home Screen.

ENTRY FILE
index.html
