# STARLOG privacy

Public privacy policy for Google Play, and a static landing page on the same site.

**Privacy (Play Console):** https://rudolfsteinerai.github.io/starlog-privacy/

**Landing:** https://rudolfsteinerai.github.io/starlog-privacy/app.html

`index.html` is the privacy policy, so the Play Console URL stays the same. `app.html` is the marketing page.

The policy describes Android PIN encryption at rest, and the web archive: an optional PIN encrypts that archive in the browser (WebCrypto PBKDF2 and AES-GCM). The web archive is secure only when a vault exists. A legacy hash-only lock stays locked, with plaintext entries, until migrate. Biometric unlock is Android-only.

Source of truth for Android product wording remains `PRIVACY.md` in [StarLog-android](https://github.com/RudolfSteinerAI/StarLog-android). Web PIN wording follows StarLog web pull request #14.
