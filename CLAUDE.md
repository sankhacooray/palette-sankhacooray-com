# palette.sankhacooray.com

Single-file site (`index.html`, all CSS inline) on GitHub Pages: pushing `main` deploys. See README.md.

## Lighthouse
<!-- lighthouse-optimized: 2026-10-31 -->
Baseline (mobile): performance 74, accessibility 100, best-practices 100, SEO 100.
Fixed: Google Fonts CSS loads non-blocking (`media=print` swap + noscript), unused DM Sans 300 dropped; `--text-muted` raised to ≥4.5:1 in both themes (specimen label).
Left: gtag/shared-script findings are handled centrally; GitHub Pages can't set cache headers.
