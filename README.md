# filex 简体中文语言包 / Simplified Chinese language pack

A community-maintained Simplified Chinese (`zh`) language pack for [filex](https://github.com/BRF-Tech/filex). Translations only: no executable code, permissions or runtime dependencies. Not an official BRF Tech translation.

## 安装 / Install

在 filex 管理后台进入 Plugins → Apps → Install an app → GitHub repository，输入 `chengjie/filex-lang-zh`，选择标签 `v1.5.2`。也可以从本仓库下载根目录的 `filex-app.json`，使用文件上传方式安装。安装后在账号语言设置选择中文。

In the filex admin panel, choose Plugins → Apps → Install an app → GitHub repository, enter `chengjie/filex-lang-zh` and tag `v1.5.2`. Alternatively, upload the root `filex-app.json`. Select Chinese in your account's language settings after installation.

## 兼容与范围 / Compatibility and scope

- Version **1.5.2**, validated against **filex v0.56.3 with filexnas extensions**: 6652/6652 applicable translation keys, zero validation errors or warnings. This count describes that exact source baseline; it is not a coverage claim for later filex releases.
- Covers the explorer, administration, public pages, server messages and notifications exposed by the host catalogue.
- Can also be installed on stock filex. Additional filexnas-only keys are ignored there. Missing strings in newer versions fall back to English.
- Does not translate third-party app menus (Office editor, draw.io, etc.) or native desktop menus.
- Uses locale `zh`; filex also matches saved `zh-CN` and `zh-Hans` preferences. This pack contains Simplified Chinese, not a separate Traditional Chinese translation.
- The stable app ID remains `filexnas-lang-zh` so existing installations can upgrade without installing a second Chinese pack.

## 维护 / Maintenance

Report translation issues through this repository's Issues, including the filex version, screen and suggested wording. Do not include private documents, credentials or unredacted production screenshots.

This repository distributes the manifest maintained in the filexnas project's `language-packs/zh/filex-app.json`. Keep one canonical translation source and export reviewed releases here. Preserve placeholder names, plural rules and message syntax. Validate against the intended source catalogue with filex's `scripts/i18n-validate.mjs --complete --plurals` before publishing.

Translations have automated syntax, placeholder, plural and coverage checks, plus representative UI checks; not every phrase has received independent human review. Corrections are welcome.

## License

MIT. See [LICENSE](LICENSE); upstream notices are retained.
