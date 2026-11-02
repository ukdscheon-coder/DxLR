# DxLR — GitHub → Vercel

DxI 9000 only. Future DxA analysis must stay in a separate module.

## GitHub
Create a new repository named `dxlr`, then upload the **contents** of this folder to the repository root. Keep `guide/` and `windows/` folders intact. Do not upload any patient records or real service logs into a public repository.

## Vercel
New Project → Import `dxlr` GitHub repository.
- Project name: `dxlr-dxi9000` (or `dxlr-app` if taken)
- Framework Preset: Other
- Root Directory: `./`
- Build Command: empty
- Output Directory: empty
- Environment Variables: none
Deploy. iPhone application: `/`. Windows browser application: `/windows/`.

## iPhone
Safari → the HTTPS deployment URL → Share → Add to Home Screen.

## Notes
This is a static browser/PWA package, not IPA or EXE. PDF/OCR libraries may require internet access. Actual iPhone device and Vercel deployment tests have not been completed. Device logs and confidential manuals should be processed locally and not committed to GitHub.
