# Archer Bowman – website

Static GitHub Pages site for the mobile game **Archer Bowman: Bow & Arrow**.
Live at https://osmanraifgunes.github.io/archer-bowman-home/

| File | Use |
|---|---|
| `index.html` | landing page (store buttons, features, screenshots, trailer) |
| `privacy.html` | privacy policy → Play Console, App Store Connect, AdMob |
| `terms.html` | terms of use |
| `support.html` | FAQ + contact → App Store support URL / Play contact website |
| `404.html` | not-found page (absolute `/archer-bowman-home/` paths) |
| `app-ads.txt` | AdMob seller line (only counts at a domain root, see below) |
| `assets/` | CSS, icons and screenshots (copied from the game repo `stores/` + `project/assets/icons/`) |

No build step. Publish: GitHub → Settings → Pages → Deploy from branch `main` / root.

`app-ads.txt` is only read from the root of the developer website domain
(`https://<domain>/app-ads.txt`). A project page lives under `/archer-bowman-home/`, so for AdMob
either use a custom domain for this repo or put the same file into a `osmanraifgunes.github.io` user-site repo.
