# Harmony Lifebond — PWA scaffold

This scaffold is a React + Vite PWA for the Harmony Lifebond app.

Quick start:
1. npm ci
2. Edit src/firebase.ts with your Firebase config
3. npm run dev (development)
4. npm run build (production)
5. Deploy `dist/` to HTTPS hosting (Firebase Hosting / Vercel / Netlify)

To produce an Android App Bundle (AAB) using TWA:
1. Host the production build on HTTPS (so manifest.json is reachable).
2. Install Bubblewrap: npm i -g @bubblewrap/cli
3. bubblewrap init --manifest=https://your-site.com/manifest.json
4. bubblewrap build
5. Open the generated Android project in Android Studio and Build -> Generate Signed Bundle / APK.

If you want me to produce the AAB for you, provide:
- Firebase config (so I can host)
- Keystore for signing (or tell me to produce an unsigned AAB)
- Or provide a GitHub repo and I will push the scaffold there.