# HOSGram

**An unofficial Telegram client for HarmonyOS NEXT — with real notifications.**

HOSGram is a native HarmonyOS NEXT app (ArkTS/ArkUI) built on [TDLib](https://github.com/tdlib/td), Telegram's official client library. It is made for Huawei phones and tablets that no longer run Android apps.

> ⚠️ HOSGram is **not** an official Telegram app and is not affiliated with, endorsed by, or connected to Telegram. It uses the Telegram API. A Telegram account is required.

## Features

- 🔔 **Notifications when the app is closed** through Huawei Push Kit
- 📞 Voice and video calls
- 🎤 Voice messages with a Telegram-style player: auto-play next, pause/resume, 1X / 1.5X / 2X, listened state
- 💬 Private chats, groups, channels, comments, reactions, polls, stickers, GIFs
- 📁 Your Telegram chat folders
- 📍 Location and Live Location
- 📷 Photos, videos and files up to 2 GB (4 GB with Telegram Premium)
- 🔐 Two-Step Verification, sign-up for new accounts, QR login
- 🛡 Proxy support (SOCKS5 / MTProto), available before sign-in
- 🌙 Night mode and color themes
- 👥 Up to 3 accounts
- 🌐 English and Simplified Chinese
- 🔞 Content that Telegram marks as sensitive is hidden

## Screenshots

<!-- Add screenshots from screenshots/ready here (no private chats) -->

## Install

- **AppGallery**: coming soon (outside the Chinese mainland).
- Huawei IDs registered in the Chinese mainland cannot see AppGallery apps that are released only outside China. Those users need a developer install.

## How notifications work

Telegram sends an encrypted Web Push to a small HOSGram notification server, which forwards it to Huawei Push Kit and then to your device. The server does not store message content. See the [Privacy Policy](https://hosgram-push.duckdns.org/privacy).

## Support

The notification server costs about $5 a month. If HOSGram is useful to you, you can support it through the [Telegram channel](https://t.me/HOSGram_HMOS). Thank you! 🙏

## Privacy

- Your messages go directly between your device and Telegram.
- The notification server keeps only a Huawei Push token and a random device ID.
- Privacy Policy: https://hosgram-push.duckdns.org/privacy

## Credits

- [TDLib](https://github.com/tdlib/td) (Boost Software License 1.0)
- [tgcalls](https://github.com/TelegramMessenger/tgcalls) for calls

Developer: Lun Rithy, Cambodia 🇰🇭
