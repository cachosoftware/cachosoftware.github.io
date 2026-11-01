# cachosoftware.github.io

Developer website for Cacho Software apps (GitHub Pages).

- `app-ads.txt` – AdMob authorized sellers (must stay at the domain root).
- `tempo/privacy/` – Tempo privacy policy (HTML + PDF). Generated in the
  Tempo repo by `tool/privacy_policy/generate_privacy_policy.py`; copy
  `docs/privacy-policy.html` → `tempo/privacy/index.html` and the PDF next to it.
- `madrid/privacy/` – Madrid Audioguía privacy policy (HTML transcribed from
  the madrid-tour repo's `assets/store/privacy_policy.pdf`, which sits next to it).
  Keep both in sync when the policy changes.
- `madrid/support/` – Madrid Audioguía support page (App Store "Support URL").
- `cachosoftware_icon.png` – Studio logo (nav, hero, favicon, share image).
- `index.html` – Studio home page. Lists every app with its store link; the
  ES/EN toggle uses `.es` / `.en` spans (default from the browser language).
- `salamanca/icon.png`, `chessologic/icon.png` – Store icons (512 px) used on
  the home page, copied from the salamancatour and royal_study repos.
