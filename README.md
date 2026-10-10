# mc-pack

The VizzySMP server resource pack, served by GitHub Pages.

- Java: https://jonathankristiansen63-byte.github.io/mc-pack/VizzySMP.zip
- Bedrock (for Geyser's `packs` folder): https://jonathankristiansen63-byte.github.io/mc-pack/VizzySMP.mcpack
- SHA-1 of the Java pack: [`VizzySMP.sha1`](VizzySMP.sha1)

`server.properties`:

```properties
resource-pack=https://jonathankristiansen63-byte.github.io/mc-pack/VizzySMP.zip
resource-pack-sha1=<contents of VizzySMP.sha1>
require-resource-pack=true
```

The link stays the same on every update; only the SHA-1 changes.

Don't edit the packs here. They are built by `VizzyHalloween/pack/build_pack.py` and
published with `VizzyHalloween/pack/publish_pack.py`.
