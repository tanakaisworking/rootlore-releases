# Rootlore update manifests

This repository holds the update manifests that the Rootlore Mac app and the `rootlore` CLI read:

- `latest.json`: read by the app at launch and from "Check for Updates…"
- `cli-latest.json`: read by `rootlore update`

The source code and the release files are in [tanakaisworking/rootlore](https://github.com/tanakaisworking/rootlore). Download the app from its [latest release](https://github.com/tanakaisworking/rootlore/releases/latest).

Every update is checked against the public key built into the app, and files that do not match are not installed. Releases up to 0.0.8 also remain here so older versions can still update.
