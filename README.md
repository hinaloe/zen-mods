## Zen Mods

The draft zen browser's mods by @hinaloe.

## Features

- [Colored container tab](./container_bgcolor/README.md)

## How to use (for developers)

1. Clone this repository.
2. [Create userChrome.css](https://docs.zen-browser.app/guides/live-editing)
3. Add `@import url("path/to/zen-mods/all-themes.css");` to your userChrome.css file. (You can use `file://` scheme or relative path)
4. Or add `@import url("path/to/zen-mods/<feature>/chrome.css");` to your userChrome.css file.
5. Restart Zen Browser.

> [!WARNING]
> `preferences.json` is not working for this way. but you can override `chrome.css` directly.