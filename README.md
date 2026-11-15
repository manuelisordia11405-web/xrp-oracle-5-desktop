# XRP Oracle 5.0 — Desktop Edition

A wide-screen, static GitHub Pages research dashboard for XRP/USD. Uses public Coinbase Exchange candles and the Lightweight Charts CDN. No API keys or Kalshi account connection.

## Publish without changing your phone site
1. Create a **new public repository** on GitHub named `xrp-oracle-5-desktop`.
2. Upload **index.html** to the root of the new repository (not the ZIP file).
3. Open **Settings → Pages**, choose **Deploy from a branch**, `main`, `/ (root)`, and Save.
4. Once GitHub says the site is live, click **Visit site**. The expected address is `https://YOUR-USERNAME.github.io/xrp-oracle-5-desktop/`.

## Notes
- The displayed spot price and signals use Coinbase XRP/USD candles, not Kalshi settlement data.
- Enter the exact Kalshi threshold manually; verify settlement terms directly on Kalshi.
- Data refreshes about every 30 seconds. Signals are heuristic and not calibrated probabilities.
- Requires internet access for Coinbase and the chart library CDN.
