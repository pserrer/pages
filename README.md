# pages

Public pages served by GitHub Pages from `docs/` (deployed by
`.github/workflows/pages.yml` on every push to `main` that touches `docs/`).

| Page | URL |
| --- | --- |
| Owsley's Odyssey — privacy policy | https://pserrer.github.io/pages/privacy.html |
| Yours, — privacy policy | https://pserrer.github.io/pages/yours/privacy.html |

The Yours, policy is rendered from `src/lib/privacy-policy.ts` in
`pserrer/mail`, which is the binding text the app shows in Settings. When that
file changes, update `docs/yours/privacy.html` to match.
