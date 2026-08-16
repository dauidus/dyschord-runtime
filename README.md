# Dyschord Runtime Images

This repository is the public distribution owner for Dyschord self-host runtime
images. It contains no application source, credentials, user data, or deployment
configuration.

Published images:

- `ghcr.io/dauidus/dyschord-runtime/backend-suite:<version>`
- `ghcr.io/dauidus/dyschord-runtime/web:<version>`
- `ghcr.io/dauidus/dyschord-runtime/gifbox:<version>`
- `ghcr.io/dauidus/dyschord-runtime/clamav:<version>`
- `ghcr.io/dauidus/dyschord-runtime/january-embed-shim:<version>`

Each immutable release tag supports `linux/amd64` and `linux/arm64`. Publication
copies only verified runtime manifests from the read-only staging registry and
ends with an anonymous pull check.
