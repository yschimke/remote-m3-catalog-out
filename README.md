# remote-m3-catalog generated output

This repository stores generated branches for the `remote-m3` design catalog — the Remote Compose
rendition of the M3 Wear OS Apps Design Kit. Source and workflow definitions live in
[remote-m3-catalog](https://github.com/yschimke/remote-m3-catalog), which was split out of
[wear-m3-catalog](https://github.com/yschimke/wear-m3-catalog).

| Branch | Written by | What it holds |
| --- | --- | --- |
| `design-artifacts/remote-m3` | `design-artifacts.yml`, `parity-issues.yml` | the importable bundle preview.coo.ee serves at `/remote-m3/` |
| `design-parity/remote-m3` | `design-parity.yml` | the design-parity board |
| `design-parity/reference` | `design-parity-import.yml` | the Figma reference cache parity reads |
| `compose-preview/*` | `compose-preview.yml` | the visual-diff baseline and PR renders |
| `snapshot-probe/remote-m3` | `remote-snapshot-probe.yml` | the androidx.dev snapshot probe's state |
| `remote-compose-cmp-maven` | `publish-remote-compose.yml` | a credential-free Maven repository for the vendored Remote Compose CMP port (`ee.schimke.remotecompose:*`) |

Nothing here is edited by hand.
