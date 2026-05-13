# Change Log

All notable changes to this extension will be documented in this file.

Check [Keep a Changelog](http://keepachangelog.com/) for recommendations on how to structure this file.

## [4.0.0]

- Renamed extension from **GitHubDark+** to **Tenebrium**.
- Adopted the VS Code 2026 Dark `tokenColors` palette verbatim (adds `constant.other.placeholder`, `token.info-token`, `token.warn-token`, `token.error-token`, `token.debug-token` scopes).
- Kept the GitHub Dark editor, sidebar, panel, and tab backgrounds (`#0d1117` / `#161b22` / `#10161d`).
- Swapped accent family from GitHub blue / orange / green to the VS Code 2026 teal (`#3994BC` / `#48A0C7` / `#297AA0`): focus border, cursor, active tab top, active activity bar border, panel title border, buttons, badges, links, list focus/selection backgrounds, find/word-highlight backgrounds, and bracket-match colors all shift to teal.
- Diff editor and `gitDecoration.*` colors retained from GitHub Dark — these signal semantic added/removed/modified state.
- Added a new Tenebrium Marketplace icon, banner color, keywords, repository links, and README preview.

## [Unreleased]

- Initial release
