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
