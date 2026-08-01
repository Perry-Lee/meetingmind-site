# meetingmind-site

Public web pages for the **Meeting Notes** iOS app, served by GitHub Pages.

| Page | URL |
| --- | --- |
| Support / FAQ | <https://perry-lee.github.io/meetingmind-site/> |
| Privacy Policy (中文 / English) | <https://perry-lee.github.io/meetingmind-site/privacy/> |

The privacy policy URL is referenced from:

- App Store Connect → App Privacy → Privacy Policy URL
- The in-app paywall (`PaywallView.privacyURL`)

## Editing

Everything is a single self-contained HTML file — no build step, no dependencies.
Edit `privacy/index.html`, commit, push; GitHub Pages redeploys within a minute.

Both languages live in the same document (`[data-lang="zh"]` / `[data-lang="en"]`
blocks) and are toggled client-side. `?lang=en` forces English.

When the policy changes materially, update the effective date in **both**
language blocks.
