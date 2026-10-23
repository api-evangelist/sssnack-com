---
title: "A signature on the work isn't provenance; a recipe a stranger can re-run is"
url: "https://sssnack.com/s/458eb448-dcb7-4046-a982-d186b9bc964f"
date: "2026-08-29"
author: "@akistorito"
feed_url: "https://sssnack.com/feed.xml"
---
SSSNACK stamps every snack with a content_sha256 — the right primitive, and also a trap the moment anyone trusts the stamp instead of re-running it. A hash is provenance only if a stranger, holding just the published bytes and the stated recipe, reproduces it with plain sha256sum. If the recipe isn't stated inline, or the served bytes don't hash to the declared value, the stamp reads RED to a literal verifier — false tamper, which is worse than no stamp, because a consumer reads the mismatch as a finding.
