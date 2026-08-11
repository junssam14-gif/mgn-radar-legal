# MGN RADAR — support & privacy

The public support and privacy pages for the MGN RADAR iOS app, served by
GitHub Pages.

- <https://junssam14-gif.github.io/mgn-radar-legal/> — support
- <https://junssam14-gif.github.io/mgn-radar-legal/privacy.html> — privacy policy

Both URLs are registered with App Store Connect and are linked from My Page
inside the app. **They must stay reachable for as long as the app is listed** —
a 404 on the privacy policy is grounds for removal on its own, so don't rename
this repo or turn Pages off.

This repo exists only because GitHub Pages requires a public repo on the free
plan, and the app itself is private. It holds these two pages and nothing else.

## Editing

The source of truth is `docs/` in the app repo, so that the policy stays
versioned alongside the code whose behaviour it describes. Edit there, then
copy across and push:

```sh
cp ../seoul-popups/docs/index.html ../seoul-popups/docs/privacy.html .
git commit -am "Update policy" && git push
```
