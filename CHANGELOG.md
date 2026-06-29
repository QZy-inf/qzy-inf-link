# Changelog

## 1.3.9 - 2026-06-29

- Added type-aware entity info for users, bots, groups, supergroups and channels.
- Ultimate dossier now includes relevant visible counters for chats/channels when Telegram exposes them: subscribers/members/participants, online, admins, banned/kicked and approximate message index.
- Added separate `Entity info` menu action for copying only target type and available counters.
- Kept personal-only fields out of channel/chat output and chat/channel-only counters out of user output.
- Marked estimated numeric counters with `≈` where Telegram does not provide an exact total.

## 1.3.8 - 2026-06-29

- Fixed `show_id = false` privacy behavior: numeric IDs/deep links no longer leak through Best link, QR, Markdown/HTML mention, menu headers or debug.
- Replaced external QR image URL flow with native Telegram QR best-effort and clipboard fallback.
- Removed third-party QR API usage from the plugin runtime.
- Switched JSON-lite card output to safe `json.dumps(..., ensure_ascii=False, indent=2)`.
- Softened Ultimate dossier wording around visible client data and Bot API.
- Improved username enrichment for chats/channels when the initial client context is minimal.

## 1.3.7 - 2026-06-29

- Updated plugin author to `@qzy_moderator`.
- Added updates channel: `https://t.me/QZyinfo`.
- Added support contact: `https://t.me/Qvless`.
- Added QZy VPN bot link: `https://t.me/QZy_vpn_bot`.

## 1.3.6 - 2026-06-29

- Added About block inside plugin settings.
- Added visible GitHub link in plugin settings.
- Added author, license and QZy VPN links to plugin settings.
- Fixed remaining old card/template wording.

## 1.3.5 - 2026-06-29

- Final public branding: TG LinkKit.
- Public repository: `QZy-inf/tg-linkkit`.
- Plugin metadata: `__id__ = "tg_linkkit"`, `__name__ = "TG LinkKit"`.
- Compact GitHub structure with only the useful root files.

## Earlier 1.x Work

- Added custom bottom-sheet menu with fallback.
- Added collectible username detection.
- Added QR URL, LinkKit card and Ultimate dossier formats.
- Added Russian and English UI.
- Added settings, presets and custom card templates.
- Added custom QZy sticker-pack icon: `QZy44/0`.
