# Leybound native update feed

This public repository hosts the signed Windows update feed and release assets for Leybound.

The launcher reads `latest-native.json` and its detached Ed25519 signature, then downloads the
matching release asset. Source code is kept in a separate private repository; this repository is
only the public update channel.

Do not edit release assets by hand. Use the Leybound release pipeline so the manifest and signature
stay in sync.
