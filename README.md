# relief-site

The public site for **Relief — CBT Reframing Tool**, served by GitHub Pages at
**<https://faridjafarlee.github.io/relief-site/>**.

It is a static site: no build step, no framework, no JavaScript dependencies. Every page is
hand-checked HTML committed directly to `main`, and GitHub Pages serves `main` at the root.

## What is here

| area | pages |
|---|---|
| Cognitive distortions | `distortions.html` plus one page each for the ten distortions — `all-or-nothing-thinking`, `catastrophizing`, `mind-reading`, `fortune-telling`, `emotional-reasoning`, `should-statements`, `labeling`, `discounting-the-positive`, `overgeneralization`, `personalization` |
| Guides | `how-to-reframe-negative-thoughts.html`, `how-to-stop-catastrophizing.html`, `thought-record.html` |
| App-status tracking | `cbt-apps-still-maintained.html`, `youper-shutting-down.html` |
| For professionals | `for-therapists.html` |
| Policy and press | `privacy.html`, `press.html`, `verify-privacy.html` |
| Translations | `de/`, `es/`, `it/`, `ja/`, `ko/`, `pt-br/`, `uk/` |

The distortion pages and the sitemap are generated from the app's own localisation catalogs, so the
terminology on the site matches the terminology in the app rather than drifting from it. The
generators live in the app repository, not here.

## Files that must not be deleted

Three files look like clutter and are not:

- **`google315704e8cb7f2ad3.html`** — Google Search Console ownership token. Deleting it revokes
  verification for the property.
- **`ba66843c187831636cb0cdf78ff0e307.txt`** — IndexNow key. The endpoint re-validates against this
  file on every submission, so removing it silently breaks submissions to Bing, Yandex, Seznam and
  Naver.
- **`sitemap.xml`** — declared in `robots.txt` and submitted to Search Console.

## The app

Relief is a CBT thought record for iOS: write the thought, weigh the evidence for and against it,
write a balanced version. It has no AI in it, and no server — entries are encrypted on the device
and there is no account to create.

<https://apps.apple.com/us/app/relief-cbt-reframing-tool/id6762535735>

## Licence

The site content is the app's own documentation and marketing material, published so that the pages
it links to from the App Store listing are permanently reachable. It is not a template and is not
intended for reuse.
