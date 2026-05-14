# RestKit TikTok Verification Site

This small static site is for TikTok Developer URL verification and app review.

Use it if TikTok refuses to verify the Shopify `myshopify.com` URLs. A free GitHub Pages, Netlify, or Cloudflare Pages deployment can host these files without buying a domain.

## Files

- `index.html`: RestKit TikTok uploader overview.
- `terms.html`: Terms page for the TikTok app form.
- `privacy.html`: Privacy page for the TikTok app form.
- `tiktok-callback.html`: HTTPS Web callback page required by TikTok's Web redirect settings.
- `tiktokug6AuZAqmZJHLGX6avulJacSWTiNSrrJ.txt`: Earlier TikTok URL-prefix verification file.
- `tiktokjH5hqgPnRB7vJ4hOl4rGr1HnuSv1aqcz.txt`: Active TikTok URL-prefix verification file used on May 13, 2026.

## Important

The `.txt` verification file must contain the exact contents TikTok generated. If TikTok generates a new token, add the new `.txt` file and publish it before clicking Verify.

## After Publishing

Use the published URLs in TikTok:

```text
Website URL: https://rojas711-source.github.io/restkit-tiktok-verification/
Terms URL: https://rojas711-source.github.io/restkit-tiktok-verification/terms.html
Privacy URL: https://rojas711-source.github.io/restkit-tiktok-verification/privacy.html
Web redirect URI: https://rojas711-source.github.io/restkit-tiktok-verification/tiktok-callback.html
URL prefix to verify: https://rojas711-source.github.io/restkit-tiktok-verification/
```

Then upload the exact TikTok verification `.txt` file to this folder and click Verify in TikTok.
