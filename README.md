# CurrentTide-site

Public host for the CurrentTide Play-listing privacy policy.
Free GitHub Pages site (the main `CurrentTide` repo is private, which the free plan won't publish Pages from).

- Live URL (use this in Play Console): https://bluechrisgit.github.io/CurrentTide-site/
- `index.html` is a copy of `docs/index.html` from the private `CurrentTide` repo, which is rendered from `PRIVACY.md` by `./build_privacy_page.py`.

To update after a policy change:
```
cd ../CurrentTide
./build_privacy_page.py
cp docs/index.html ../CurrentTide-site/index.html
```
then commit + push here.
