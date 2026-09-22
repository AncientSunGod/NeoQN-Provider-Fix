# NeoQN Provider Fix — ready-to-upload build

This bundle is for NeoQN v2.2.0 and keeps the main APK unchanged.

The provider override includes:
- NovelArrow filter fixes
- NovelFire chapter fallback/fix
- Novel Phoenix
- NeoQN-2.2.0-compatible WTR-LAB provider with Cloudflare/WebView fallback

Important: do NOT replace the WTR-LAB source with the latest upstream WtrLabProvider.kt. The included WTR-LAB implementation is adapted to NeoQN v2.2.0's API.

## GitHub

Upload these two files to the repository root:
- `provider-overrides.zip`
- `.github/workflows/build.yml`

Then run Actions → Build NeoQN Fixed Providers → Run workflow.
