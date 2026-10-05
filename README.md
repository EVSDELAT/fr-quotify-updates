# FR-Quotify macOS updates

This public repository contains signed macOS installers and the Sparkle appcast for **FR-自動化報價單系統**. The application source code is kept in a separate private repository.

- Sparkle feed: <https://evsdelat.github.io/fr-quotify-updates/appcast.xml>
- Installers and signed update ZIPs: [Releases](https://github.com/EVSDELAT/fr-quotify-updates/releases)
- Supported platform: Apple silicon Mac, macOS 13 or later.

The current 2.0.12 application has no Sparkle updater. Install the first Sparkle-enabled release manually once. Subsequent releases can be checked from the application's **檢查更新** command.

Release artifacts are signed with the FR-Quotify macOS code-signing identity and Sparkle EdDSA key. The private signing key, source code, customer data, and license secrets are not stored here.
