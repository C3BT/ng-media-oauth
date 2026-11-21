# ng-media-oauth

Two static pages that satisfy Google's requirement for a public **app home page**
and **privacy policy** on the OAuth consent screen of Google Cloud project
`newsletter-demo-491109` (app name: *NG Media Automation*).

Served by GitHub Pages at **https://oauth.ng-boutique.com**.

- `index.html` - app home page
- `privacy.html` - privacy policy
- `CNAME` - custom domain claim

## Do not delete this repo or disable Pages without first removing the DNS record

`oauth.ng-boutique.com` is a CNAME to `c3bt.github.io`. If this Pages site stops
serving the domain while that DNS record still exists, the subdomain becomes
claimable by someone else on GitHub Pages (**subdomain takeover**) and they could
serve arbitrary content on an ng-boutique.com address. Retire in this order:

1. Delete the `oauth` CNAME record in Cloudflare.
2. Only then delete this repo / disable Pages.

The domain is also registered under GitHub's verified domains, which blocks another
account from claiming it; keep that verification in place.

## Source of truth

Edit the pages in the `agentic-workflows` repo at `frontend/ng-media-oauth/`, then
copy them here. Nothing secret belongs in this repo - it is public.
