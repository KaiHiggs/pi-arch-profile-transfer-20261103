# Temporary Pi profile transfer

Download the sanitized Arch bundle from the [release](https://github.com/KaiHiggs/pi-arch-profile-transfer-20261103/releases/tag/transfer-20261103).

On Arch Linux:

```bash
curl -fLO https://github.com/KaiHiggs/pi-arch-profile-transfer-20261103/releases/download/transfer-20261103/pi-arch-profile-20261103.tar.gz
curl -fLO https://github.com/KaiHiggs/pi-arch-profile-transfer-20261103/releases/download/transfer-20261103/pi-arch-profile-20261103.tar.gz.sha256
sha256sum -c pi-arch-profile-20261103.tar.gz.sha256
tar -xzf pi-arch-profile-20261103.tar.gz
cd pi-arch-profile-20261103
cat README.md
# Install the listed prerequisites, then:
bash install.sh
~/.local/bin/pi-arch
```

No credentials or history are included. MCP and Remnic require fresh configuration. This installs a Pi profile, not an LLM server.

This repository is public and temporary. Delete it manually after transfer. Public copies can persist after deletion.
