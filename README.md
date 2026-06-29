# TG LinkKit

Compact Telegram client plugin for copying profile and chat links.

## What It Does

TG LinkKit adds a menu action for supported Telegram clients and copies useful formats:

- best available link;
- `https://t.me/...`;
- `@username`;
- `tg://resolve?...`;
- `tg://user?id=...`;
- Markdown mention;
- HTML mention;
- QR image URL;
- LinkKit card;
- Ultimate dossier.

## Compatibility

- App/plugin API: `>=12.5.1`
- Plugin SDK: `>=1.4.3.3`
- Target clients: AyuGram / exteraGram-compatible plugin runtimes
- Official Telegram without plugin runtime is not supported

## Install

Download `tg_linkkit.plugin` from this repository or from the latest release:

https://github.com/QZy-inf/tg-linkkit/releases/latest

Then import it in your client plugin manager.

## Privacy

TG LinkKit is local-only:

- no tokens;
- no external APIs;
- no telemetry;
- no servers;
- no Bot API.

It only reads the current Telegram client context and copies selected text to your clipboard.

## Version

Current version: `1.3.5`
