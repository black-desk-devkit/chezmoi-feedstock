# chezmoi-feedstock

Conda feedstock for [chezmoi](https://chezmoi.io).

Builds a fully static binary (`CGO_ENABLED=0`) for `linux-64` and `osx-arm64`.

## Update procedure

1. Bump `version` in `recipe/recipe.yaml`
2. Update `sha256` (from `curl -L <tarball-url> | sha256sum`)
3. Reset `build.number` to `0` on version bump
4. Commit to `main` — CI builds and uploads to
   [prefix.dev/black-desk](https://prefix.dev/black-desk)
