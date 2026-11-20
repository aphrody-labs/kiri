Patch queue of aphrody-labs/kiri. `series` lists the patches in order; each is a `git format-patch` mbox whose header names its purpose and
`Upstream-Status: carry | submitted <url> | merged <tag>`. fw-nt `tools/sync.ts` builds branch `aphrody` (main + series); `aphrody-release.yml`
builds the newest upstream tag + series. Upstream contributions need the maintainer's CLA: until then every patch is a carry.
