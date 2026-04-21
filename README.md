# ifollowtrend.github.io

Landing page for Shorts Bot, my personal short-form video tool. Hosts the privacy policy
and terms of service that TikTok's developer program requires when registering an app.

## Pages
- `index.html` — overview of what Shorts Bot does
- `privacy.html` — privacy policy
- `terms.html` — terms of service

## TikTok URL verification

When TikTok's developer dashboard issues a signature file (something like
`tiktok-developers-site-verification.txt` or `tiktokXXXXXXXX.txt`), drop it in the repo
root alongside `index.html` and push. GitHub Pages redeploys in under a minute; then
click **Verify** back in the TikTok dashboard.
