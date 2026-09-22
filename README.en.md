# DaD: Rogue Trader

Public data for updating Dark and Darker: Rogue Trader.

[Русский](README.md)

Branch `master`:

- `manifest.json` - versions of the program, content, and the proxy list
- `content/item_labels.json`, `content/attribute_labels.json`, `content/market_filters.json`
- `proxies.json`

The archive is not committed. It sits in the GitHub Release for the tag from `manifest.json` (`app.tag`, file `app.file`).

## Minimum requirements

- Windows 10 or newer, 64-bit
- [.NET 10 Desktop Runtime](https://aka.ms/dotnet/10.0/windowsdesktop-runtime-win-x64.exe). It is not included in the archive.

The tooltip recognition overlay uses DirectML and needs a GPU with DirectX 12.

## Install and update

Download latest `DadRogueTrader-win-x64.zip` from the [GitHub Release](https://github.com/etspring/dad_rtrader/releases).

1. Install the runtime from the list above if you do not have it yet.
2. Extract the archive into its own folder. `DadRogueTrader.exe` and the rest of the files are at the root, with no extra nested folder.
3. Run `DadRogueTrader.exe`.

To update, close the program and extract the new archive into the same folder, replacing existing files. Settings stay in `%AppData%\DadRogueTrader`.

## Bugs and features

If you find a bug or have an idea for an improvement, feel free to open an [Issue](https://github.com/etspring/dad_rtrader/issues).
