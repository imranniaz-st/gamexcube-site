# Block Buster Games

Static website for **Block Buster Games** by Bicodev (Android package `com.blockbustergames.block_buster_games`). It is plain HTML and CSS, with no build step, and is meant to be served at [games.bicodev.com](https://games.bicodev.com) with GitHub Pages.

GitHub Pages should publish the `main` branch from the repository root (`/`).

## Pages

- `/` — landing page for the offline Android puzzle collection (Match Cube, Cube Filling, and a Game Hub of ten mini-games), including a coming-soon Google Play link for package `com.blockbustergames.block_buster_games`
- `/privacy-policy.html` and `/privacy-policy/` — privacy policy (last updated November 20, 2026)
- `/terms.html` — terms of use (last updated November 20, 2026)
- `/app-ads.txt` — AdMob authorization file, served at the site root
- `/404.html` — page not found
- `CNAME` — custom domain `games.bicodev.com`
- `.nojekyll` — tells GitHub Pages not to run Jekyll

Fonts in `fonts/` are self-hosted (Sora and Source Sans 3, SIL Open Font License).

## DNS and GitHub Pages

At the DNS provider for **bicodev.com**, add a CNAME record:

| Type | Host / name | Target |
| --- | --- | --- |
| CNAME | `games` | `imranniaz-st.github.io` |

Then enable GitHub Pages for this repository:

1. Open **Settings → Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Set the branch to **main** and the folder to **/ (root)**.
4. The custom domain is `games.bicodev.com` (this repository already contains a `CNAME` file).
5. Turn on **Enforce HTTPS** after GitHub finishes issuing the certificate.

The certificate is issued only after `games.bicodev.com` points at `imranniaz-st.github.io`. DNS changes can take a while to show up. When Pages is live, AdMob fetches `https://games.bicodev.com/app-ads.txt`.

## Contact

info.iosnapk@gmail.com
