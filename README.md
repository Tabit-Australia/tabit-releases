# Tabit downloads

The current Windows release, and the update listing the app checks.

- **[Download Tabit](https://github.com/Tabit-Australia/tabit-releases/releases/latest)** — grab the `-setup.exe` from the latest release and run it.
- `latest.json` is read by the app to find out whether a newer version exists. It carries the version, the download link, and a SHA-256 the app verifies before running anything.

Windows will warn that the publisher is unknown, because the installer is not
code-signed yet. Choose **More info**, then **Run anyway**.

The source lives in a separate private repository.
