![Firefox 157+](https://img.shields.io/badge/Firefox-157%2B-FF7139?logo=firefoxbrowser&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-Only-FF7139)

# Orangefox - Firefox Orange Theme

A minimalist orange theme for Firefox 157: `userChrome.css` + `userContent.css`.

The bookmarks toolbar displays icons only, with bookmark titles appearing in tooltips when hovering over them.

## Features

- Orange interface color scheme instead of the default purple
- Compact bookmarks toolbar: icons only, no text
- Bookmark titles displayed in tooltips on hover
- Styling for internal Firefox pages (`userContent.css`)
- No extensions or JavaScript required CSS only

## Installation

### 1. Enable custom stylesheets

1. Open `about:config`
2. Search for `toolkit.legacyUserProfileCustomizations.stylesheets`
3. Set its value to `true`

### 2. Locate your profile folder

Open `about:support` and click **Open Folder** next to **Profile Folder**.

Default locations:

| OS | Path |
|---|---|
| Windows | `%APPDATA%\Mozilla\Firefox\Profiles\<profile>\` |
| Linux | `~/.mozilla/firefox/<profile>/` |
| macOS | `~/Library/Application Support/Firefox/Profiles/<profile>/` |

### 3. Copy the files

Copy the `chrome` folder from this repository into your Firefox profile folder.

If a `chrome` folder already exists, add the files to it (make a backup of your existing files first).

### 4. Restart Firefox

Completely close Firefox and launch it again.
