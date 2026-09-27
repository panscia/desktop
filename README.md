# Panscia desktop — releases

Signed and notarized macOS builds of the Panscia node, published here as
GitHub Releases. Installed apps read `latest-mac.yml` from the latest
published release to update themselves.

Source is not kept in this repository.

`.github/workflows/smoke-arm64.yml` launches a release's Apple Silicon
build on an Apple Silicon runner and keeps a screenshot and the app log as
the run's artifact. Run it by hand from the Actions tab with the version.
