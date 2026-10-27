# AIOMetadata + Parent Config (personal build)

This branch only holds the build workflow. Every 6 hours it takes the newest
[cedya77/aiometadata](https://github.com/cedya77/aiometadata) release, applies the
commits on [`feat/parent-config`](../../tree/feat/parent-config), checks the merge,
and publishes `ghcr.io/mlp2069/aiometadata:latest` for arm64.

Not supported upstream: report bugs to cedya77 only if they also happen on the
official image. If a release stops the patch from applying, the build fails and the
previous `latest` stays in place.
