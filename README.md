# NEXCALL iPhone prototype

## What works in this prototype
- Premium responsive dialer UI
- SIM-call handoff using the iPhone `tel:` URL scheme
- Demo contacts and call-history screens
- SIP settings form (draft-only; no real SIP registration)
- PWA manifest and service worker for Add to Home Screen

## Install on iPhone
1. Upload the contents of this folder to a GitHub repository (or your existing GitHub Pages site).
2. Enable GitHub Pages over HTTPS.
3. Open the published URL in Safari on iPhone.
4. Tap Share -> Add to Home Screen.

## Important limitations
This is a frontend prototype, not a native iOS calling app. A website/PWA cannot replace the iPhone Phone app, become the default dialer, access carrier call audio, or reliably receive background SIP calls. Real SIP calling requires a native iOS app (Swift/CallKit/PushKit plus a SIP/WebRTC stack and a SIP provider). iOS carrier calls are handed off to the Phone app via `tel:`. Call recording is restricted by iOS and applicable law.
