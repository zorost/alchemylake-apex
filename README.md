# alchemylake.com apex redirect

Serves `alchemylake.com` (and `www.`) via GitHub Pages and instantly forwards every path to the production app at `https://app.alchemylake.com`, preserving path, query, and hash.

DNS: apex A/AAAA records point to GitHub Pages anycast; `www` CNAME points to `zorost.github.io`.
