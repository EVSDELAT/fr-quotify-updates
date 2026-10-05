# FR-Quotify macOS updates

This public repository contains signed macOS installers and the Sparkle appcast for **FR-自動化報價單系統**. The application source code is kept in a separate private repository.

- Sparkle feed: <https://raw.githubusercontent.com/EVSDELAT/fr-quotify-updates/main/appcast.xml>
- Installers and signed update ZIPs: [Releases](https://github.com/EVSDELAT/fr-quotify-updates/releases)
- Supported platform: Apple silicon Mac, macOS 13 or later.

Versions through 2.0.12 have no Sparkle updater. Install 2.0.14 manually once; then use **檢查更新** to install 2.0.15 and later versions.

Release artifacts are signed with the FR-Quotify macOS code-signing identity and Sparkle EdDSA key. The private signing key, source code, customer data, and license secrets are not stored here.
