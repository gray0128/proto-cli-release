# proto CLI Releases

Official prebuilt binaries for the Prototype Manager CLI (`proto`).

## Supported Platforms

- **macOS arm64**: `proto-aarch64-apple-darwin`
- **Linux x86_64**: `proto-x86_64-unknown-linux-gnu`

## Install / Upgrade

Download the latest release binary from [Releases](https://github.com/gray0128/proto-cli-release/releases/latest), make it executable, and move it into your `PATH`:

```bash
chmod +x proto-aarch64-apple-darwin
sudo mv proto-aarch64-apple-darwin /usr/local/bin/proto
```

Once installed, upgrade with:

```bash
proto version check
proto upgrade
```
