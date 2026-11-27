JARVIS AI — ANDROID STARTER BUILD 0.1

WHAT THIS BUILD DOES
- Iron Man-inspired mobile interface
- Hindi / English / Odia language selector
- Microphone input where browser support is available
- Text input
- Spoken demo replies using device text-to-speech
- Basic offline app shell after it has been installed and cached

IMPORTANT
This is the first UI + voice prototype. It is NOT yet connected to a real AI model.
It does not have always-on "Hey Jarvis", full phone control, live internet search,
or a secure AI backend yet. Those are later phases.

HOW TO TEST QUICKLY ON YOUR PHONE
1. Extract this ZIP into a folder named jarvis-ai.
2. To install as a proper web app, the files must be hosted on an HTTPS website.
   A simple option is GitHub Pages:
   - Sign in to github.com in Chrome.
   - Create a new public repository named jarvis-ai.
   - Upload index.html, styles.css, app.js, manifest.json and service-worker.js
     to the repository root.
   - In repository Settings > Pages, enable deployment from the main branch / root.
   - Wait for the published Pages URL.
3. Open the published HTTPS URL in Chrome on Android.
4. Allow microphone access when asked.
5. Chrome menu (three dots) > Install app (or Add to Home screen).
6. Open JARVIS from your home screen.

VOICE NOTES
- Speech recognition browser support varies. If microphone input fails, use the
  text field for now and check Chrome microphone permission.
- Recognition may require internet and may send audio to a browser speech service.
- Odia speech recognition and spoken output depend on Android/browser language
  service and installed voice support. The app's language selector requests or-IN.
- If Odia voice output is unavailable, install/update an Odia speech voice if your
  Android Text-to-speech engine offers one.

NEXT BUILD
Connect a small secure backend to an AI API. Never paste a private API key into
app.js or any file uploaded to a public repository.
