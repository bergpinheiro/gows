# GOWS

WhatsApp golang based engine for [WAHA](https://waha.devlike.pro/) — **binary repository**.

This repository hosts binary releases built from a private fork of
[devlikeapro/gows-plus](https://github.com/devlikeapro/gows-plus). The original GOWS engine is
developed by [devlikeapro](https://github.com/devlikeapro) and is available for the
[**WAHA PRO**](https://waha.devlike.pro/pricing/) tier.

## Release channels

| Tag | Channel | Contents |
| --- | --- | --- |
| `v1.0.x` | stable (Latest) | production engine — no calls feature |
| `call1.0.x` | calls (pre-release) | stable + voice-calls feature (place/answer/reject/hangup, PCM media stream, WebRTC bridge) |

Each release ships `gows-amd64`, `gows-arm64`, `gows.proto` and `THIRD-PARTY-LICENSES.md`.

## Credits

- **[devlikeapro](https://github.com/devlikeapro)** — original GOWS engine and the
  [WAHA](https://waha.devlike.pro/) project this engine serves.
- **[whatsmeow](https://github.com/tulir/whatsmeow)** by Tulir Asokan — the WhatsApp Web
  multidevice protocol library (MPL-2.0). Fork with the patches used in these builds:
  [bergpinheiro/whatsmeow](https://github.com/bergpinheiro/whatsmeow).
- **[meowcaller](https://github.com/purpshell/meowcaller)** by Rajeh Taher (purpshell) — WhatsApp
  VoIP library powering the calls channel (MIT). *(call builds only)*
- **[Pion](https://github.com/pion)** — WebRTC stack for the live-call bridge (MIT). *(call builds only)*

Full attribution and license texts: see the `THIRD-PARTY-LICENSES.md` asset attached to every release.
