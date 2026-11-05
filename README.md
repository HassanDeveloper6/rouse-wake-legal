# Rouse — legal and support pages

Public pages for the Rouse alarm app, served with GitHub Pages:
https://hassandeveloper6.github.io/rouse-wake-legal/

| Page | URL | Used for |
|---|---|---|
| Privacy Policy | /privacy.html | App Store + Google Play privacy policy URL, in-app link |
| Terms of Use | /terms.html | App Store description (subscriptions), in-app link |
| Support | /support.html | App Store support URL, Google Play website |
| Delete account | /delete-account.html | Google Play "Delete account URL" |
| Finish sign-in | /finish-signin.html | Continue URL of the email sign-in link |

**Do not edit these files by hand.** They are generated from `src/features/legal/legal.json` in the
app repo (the same text the app shows). Change the text there, then run `yarn legal:build` in the
app repo and commit this repo.
