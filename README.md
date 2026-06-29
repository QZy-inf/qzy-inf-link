# TG LinkKit

Compact Telegram client plugin for copying profile and chat links.

![version](https://img.shields.io/badge/version-1.3.9-black)
![license](https://img.shields.io/badge/license-MIT-blue)
![runtime](https://img.shields.io/badge/plugin%20SDK-%3E%3D1.4.3.3-2ea44f)

## What It Does

TG LinkKit adds a menu action for supported Telegram clients and copies useful formats:

- best available link;
- `https://t.me/...`;
- `@username`;
- `tg://resolve?...`;
- `tg://user?id=...`;
- Markdown mention;
- HTML mention;
- native Telegram QR, when supported by the client;
- LinkKit card;
- type-aware entity info for users, bots, groups, supergroups and channels;
- Ultimate dossier.

## Compatibility

- App/plugin API: `>=12.5.1`
- Plugin SDK: `>=1.4.3.3`
- Target clients: AyuGram / exteraGram-compatible plugin runtimes
- Official Telegram without plugin runtime is not supported

## Install

Download `tg_linkkit.plugin` from the latest release:

https://github.com/QZy-inf/tg-linkkit/releases/latest

Then import it in your client plugin manager.

## Repository

- `tg_linkkit.plugin` - plugin file.
- `README.md` - quick overview and install notes.
- `CHANGELOG.md` - version history.
- `LICENSE` - MIT license.
- `SECURITY.md` - security and privacy notes.

## Privacy

TG LinkKit is local-only:

- no tokens;
- no external APIs;
- no telemetry;
- no servers;
- no Bot API.

It only reads the current Telegram client context and copies selected text to your clipboard.

## Author

- Author: QZy
- Telegram: https://t.me/qzy_moderator
- GitHub: https://github.com/QZy-inf/tg-linkkit
- Updates: https://t.me/QZyinfo
- Support: https://t.me/Qvless
- QZy VPN: https://connect.qzybot.space
- QZy VPN Bot: https://t.me/QZy_vpn_bot
- License: MIT

## Version

Current version: `1.3.9`

## License

MIT. See `LICENSE`.
