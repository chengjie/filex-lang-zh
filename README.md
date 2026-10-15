# Simplified Chinese language pack for filex

A community-maintained Simplified Chinese (`zh`) language pack for [filex](https://github.com/BRF-Tech/filex). Translations only: no executable code, permissions or runtime dependencies. Not an official BRF Tech translation.

## Installation

In the filex admin panel, choose Plugins → Apps → Install an app → GitHub repository, enter `chengjie/filex-lang-zh` and tag `v0.1.0`. Alternatively, upload the root `filex-app.json`. Select Chinese in your account's language settings after installation.

## Compatibility and scope

- Version **0.1.0**, validated against **filex v0.56.3 with filexnas extensions**: 6653/6653 applicable translation keys, zero validation errors or warnings. This count describes that exact source baseline; it is not a coverage claim for later filex releases.
- Covers the explorer, administration, public pages, server messages and notifications exposed by the host catalogue.
- Can also be installed on stock filex. Additional filexnas-only keys are ignored there. Missing strings in newer versions fall back to English.
- Does not translate third-party app menus (Office editor, draw.io, etc.) or native desktop menus.
- Uses locale `zh`; filex also matches saved `zh-CN` and `zh-Hans` preferences. This pack contains Simplified Chinese, not a separate Traditional Chinese translation.
- The stable app ID remains `filexnas-lang-zh` so existing installations can upgrade without installing a second Chinese pack.

## Version numbering

The public release series starts at **0.1.0**. It includes the translations previously maintained as 1.5.3; the lower version number does not mean older translations. The app ID remains `filexnas-lang-zh`. Existing 1.x installations may need to uninstall the old language pack and install 0.1.0 explicitly. Normal update checks may not offer a lower version. Language preferences remain saved; select Chinese again if needed. Do not install a second copy with the same ID. Historical GitHub tags remain available.

## Maintenance

Report translation issues through this repository's Issues, including the filex version, screen and suggested wording. Do not include private documents, credentials or unredacted production screenshots.

This repository distributes the manifest maintained in the filexnas project's `language-packs/zh/filex-app.json`. Keep one canonical translation source and export reviewed releases here. Preserve placeholder names, plural rules and message syntax. Validate against the intended source catalogue with filex's `scripts/i18n-validate.mjs --complete --plurals` before publishing.

Translations have automated syntax, placeholder, plural and coverage checks, plus representative UI checks; not every phrase has received independent human review. Corrections are welcome.

## License

MIT. See [LICENSE](LICENSE); upstream notices are retained.
