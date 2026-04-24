# PocketMine-MP 1.26.13

Maintained **PocketMine-MP 4.x** fork with support for **Minecraft: Bedrock Edition 1.26.13** (protocol 944).

Based on the [Benedikt05/PocketMine-MP](https://github.com/Benedikt05/PocketMine-MP) legacy branch, with the `bedrock-protocol` dependency pinned to the [sirelves/BedrockProtocol `26.13` branch](https://github.com/sirelves/BedrockProtocol/tree/26.13).

## Supported client versions

| Minecraft Bedrock | Protocol | Status |
| --- | --- | --- |
| 1.26.10 | 944 | ✅ supported |
| 1.26.11 (hotfix) | 944 | ✅ supported |
| 1.26.12 (hotfix) | 944 | ✅ supported |
| 1.26.13 (hotfix) | 944 | ✅ supported — advertised version |

Since 1.26.11/12/13 are client hotfixes without protocol changes, the server accepts all four client builds and advertises `1.26.13` in ping/MOTD.

## Quick start

1. Download the prebuilt `PocketMine-MP.phar` from [Releases](https://github.com/sirelves/PocketMine-MP/releases).
2. Download the [PMMP PHP binary](https://github.com/pmmp/PHP-Binaries/releases/tag/pm4-latest) for your platform and extract it to `./bin/php7/`.
3. Run `./start.sh`.

Full build-from-source instructions in [BUILDING.md](./BUILDING.md).

## Disclaimer

This repository is **not** maintained by the original PocketMine-MP developers. [pmmp/PocketMine-MP](https://github.com/pmmp/PocketMine-MP) has no relation with this project.

Do not open issues at the upstream PMMP repository for problems encountered with this fork.

- Upstream (legacy maintainer): [Benedikt05/PocketMine-MP](https://github.com/Benedikt05/PocketMine-MP)
- Protocol library fork: [sirelves/BedrockProtocol](https://github.com/sirelves/BedrockProtocol)
- Support Discord: https://discord.gg/KQVR3UUCv4

## License

LGPL-3.0 — same as upstream.
