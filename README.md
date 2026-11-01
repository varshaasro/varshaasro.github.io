# varshaasro.github.io

Shared static assets for apps published under this developer account — kept in one small public
repo (no app source code) so the same files can serve every app via GitHub's special
`<username>.github.io` "user site," which is hosted at the domain's root rather than under a
`/reponame/` path.

- **`app-ads.txt`** — [authorized digital sellers](https://iabtechlab.com/ads-txt/) declaration for
  ad networks (AdMob). One shared file covers every app registered under the same AdMob account;
  add a line for each additional ad network/account as needed. Must stay at the repo root.
- **`backgammon/privacy-policy.html`** — Privacy policy for the BackGammon app
  ([varshaasro/PopularGames](https://github.com/varshaasro/PopularGames)). Each future app gets its
  own subfolder the same way.

Each app's "Developer Website" field (App Store Connect / Play Console) should point at
`https://varshaasro.github.io` so ad-network crawlers find `app-ads.txt` here.
