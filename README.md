# Roll — legal documents

Public hosting for Roll's privacy policy and terms, because App Store Connect
requires a reachable privacy policy URL and GitHub Pages on the free tier only
serves from a public repository. The app's source stays private.

**These files are generated.** The source of truth is `MacroFit/Legal/*.md` in
the app repository, which is what the app itself bundles and renders offline —
one document, so the hosted copy and the in-app copy cannot drift apart.

To update: edit the Markdown in the app repo, then

    python3 scripts/build-legal.py ../roll-legal

and commit here. Never edit the HTML by hand.

- [Privacy policy](https://lashap28.github.io/roll-legal/privacy.html)
- [Terms of use](https://lashap28.github.io/roll-legal/terms.html)
