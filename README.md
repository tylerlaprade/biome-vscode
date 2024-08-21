# Biome Extension for VS Code

[![](https://img.shields.io/visual-studio-marketplace/v/biomejs.biome?color=374151&label=Visual%20Studio%20Marketplace&labelColor=000&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIGZpbGw9Im5vbmUiIHZpZXdCb3g9IjAgMCAxMDAgMTAwIj48bWFzayBpZD0iYSIgd2lkdGg9IjEwMCIgaGVpZ2h0PSIxMDAiIHg9IjAiIHk9IjAiIG1hc2stdHlwZT0iYWxwaGEiIG1hc2tVbml0cz0idXNlclNwYWNlT25Vc2UiPjxwYXRoIGZpbGw9IiNmZmYiIGZpbGwtcnVsZT0iZXZlbm9kZCIgZD0iTTcwLjkxMiA5OS4zMTdhNi4yMjMgNi4yMjMgMCAwIDAgNC45Ni0uMTlsMjAuNTg5LTkuOTA3QTYuMjUgNi4yNSAwIDAgMCAxMDAgODMuNTg3VjE2LjQxM2E2LjI1IDYuMjUgMCAwIDAtMy41NC01LjYzMkw3NS44NzQuODc0YTYuMjI2IDYuMjI2IDAgMCAwLTcuMTA0IDEuMjFMMjkuMzU1IDM4LjA0IDEyLjE4NyAyNS4wMWE0LjE2MiA0LjE2MiAwIDAgMC01LjMxOC4yMzZsLTUuNTA2IDUuMDA5YTQuMTY4IDQuMTY4IDAgMCAwLS4wMDQgNi4xNjJMMTYuMjQ3IDUwIDEuMzYgNjMuNTgzYTQuMTY4IDQuMTY4IDAgMCAwIC4wMDQgNi4xNjJsNS41MDYgNS4wMWE0LjE2MiA0LjE2MiAwIDAgMCA1LjMxOC4yMzZsMTcuMTY4LTEzLjAzMkw2OC43NyA5Ny45MTdhNi4yMTcgNi4yMTcgMCAwIDAgMi4xNDMgMS40Wk03NS4wMTUgMjcuMyA0NS4xMSA1MGwyOS45MDYgMjIuNzAxVjI3LjNaIiBjbGlwLXJ1bGU9ImV2ZW5vZGQiLz48L21hc2s+PGcgbWFzaz0idXJsKCNhKSI+PHBhdGggZmlsbD0iIzAwNjVBOSIgZD0iTTk2LjQ2MSAxMC43OTYgNzUuODU3Ljg3NmE2LjIzIDYuMjMgMCAwIDAtNy4xMDcgMS4yMDdsLTY3LjQ1MSA2MS41YTQuMTY3IDQuMTY3IDAgMCAwIC4wMDQgNi4xNjJsNS41MSA1LjAwOWE0LjE2NyA0LjE2NyAwIDAgMCA1LjMyLjIzNmw4MS4yMjgtNjEuNjJjMi43MjUtMi4wNjcgNi42MzktLjEyNCA2LjYzOSAzLjI5N3YtLjI0YTYuMjUgNi4yNSAwIDAgMC0zLjUzOS01LjYzWiIvPjxnIGZpbHRlcj0idXJsKCNiKSI+PHBhdGggZmlsbD0iIzAwN0FDQyIgZD0ibTk2LjQ2MSA4OS4yMDQtMjAuNjA0IDkuOTJhNi4yMjkgNi4yMjkgMCAwIDEtNy4xMDctMS4yMDdsLTY3LjQ1MS02MS41YTQuMTY3IDQuMTY3IDAgMCAxIC4wMDQtNi4xNjJsNS41MS01LjAwOWE0LjE2NyA0LjE2NyAwIDAgMSA1LjMyLS4yMzZsODEuMjI4IDYxLjYyYzIuNzI1IDIuMDY3IDYuNjM5LjEyNCA2LjYzOS0zLjI5N3YuMjRhNi4yNSA2LjI1IDAgMCAxLTMuNTM5IDUuNjNaIi8+PC9nPjxnIGZpbHRlcj0idXJsKCNjKSI+PHBhdGggZmlsbD0iIzFGOUNGMCIgZD0iTTc1Ljg1OCA5OS4xMjZhNi4yMzIgNi4yMzIgMCAwIDEtNy4xMDgtMS4yMWMyLjMwNiAyLjMwNyA2LjI1LjY3NCA2LjI1LTIuNTg4VjQuNjcyYzAtMy4yNjItMy45NDQtNC44OTUtNi4yNS0yLjU4OWE2LjIzMiA2LjIzMiAwIDAgMSA3LjEwOC0xLjIxbDIwLjYgOS45MDhBNi4yNSA2LjI1IDAgMCAxIDEwMCAxNi40MTN2NjcuMTc0YTYuMjUgNi4yNSAwIDAgMS0zLjU0MSA1LjYzM2wtMjAuNjAxIDkuOTA2WiIvPjwvZz48cGF0aCBmaWxsPSJ1cmwoI2QpIiBmaWxsLXJ1bGU9ImV2ZW5vZGQiIGQ9Ik03MC44NTEgOTkuMzE3YTYuMjI0IDYuMjI0IDAgMCAwIDQuOTYtLjE5TDk2LjQgODkuMjJhNi4yNSA2LjI1IDAgMCAwIDMuNTQtNS42MzNWMTYuNDEzYTYuMjUgNi4yNSAwIDAgMC0zLjU0LTUuNjMyTDc1LjgxMi44NzRhNi4yMjYgNi4yMjYgMCAwIDAtNy4xMDQgMS4yMUwyOS4yOTQgMzguMDQgMTIuMTI2IDI1LjAxYTQuMTYyIDQuMTYyIDAgMCAwLTUuMzE3LjIzNmwtNS41MDcgNS4wMDlhNC4xNjggNC4xNjggMCAwIDAtLjAwNCA2LjE2MkwxNi4xODYgNTAgMS4yOTggNjMuNTgzYTQuMTY4IDQuMTY4IDAgMCAwIC4wMDQgNi4xNjJsNS41MDcgNS4wMDlhNC4xNjIgNC4xNjIgMCAwIDAgNS4zMTcuMjM2TDI5LjI5NCA2MS45NmwzOS40MTQgMzUuOTU4YTYuMjE4IDYuMjE4IDAgMCAwIDIuMTQzIDEuNFpNNzQuOTU0IDI3LjMgNDUuMDQ4IDUwbDI5LjkwNiAyMi43MDFWMjcuM1oiIGNsaXAtcnVsZT0iZXZlbm9kZCIgb3BhY2l0eT0iLjI1IiBzdHlsZT0ibWl4LWJsZW5kLW1vZGU6b3ZlcmxheSIvPjwvZz48ZGVmcz48ZmlsdGVyIGlkPSJiIiB3aWR0aD0iMTE2LjcyNyIgaGVpZ2h0PSI5Mi4yNDYiIHg9Ii04LjM5NCIgeT0iMTUuODI5IiBjb2xvci1pbnRlcnBvbGF0aW9uLWZpbHRlcnM9InNSR0IiIGZpbHRlclVuaXRzPSJ1c2VyU3BhY2VPblVzZSI+PGZlRmxvb2QgZmxvb2Qtb3BhY2l0eT0iMCIgcmVzdWx0PSJCYWNrZ3JvdW5kSW1hZ2VGaXgiLz48ZmVDb2xvck1hdHJpeCBpbj0iU291cmNlQWxwaGEiIHZhbHVlcz0iMCAwIDAgMCAwIDAgMCAwIDAgMCAwIDAgMCAwIDAgMCAwIDAgMTI3IDAiLz48ZmVPZmZzZXQvPjxmZUdhdXNzaWFuQmx1ciBzdGREZXZpYXRpb249IjQuMTY3Ii8+PGZlQ29sb3JNYXRyaXggdmFsdWVzPSIwIDAgMCAwIDAgMCAwIDAgMCAwIDAgMCAwIDAgMCAwIDAgMCAwLjI1IDAiLz48ZmVCbGVuZCBpbjI9IkJhY2tncm91bmRJbWFnZUZpeCIgbW9kZT0ib3ZlcmxheSIgcmVzdWx0PSJlZmZlY3QxX2Ryb3BTaGFkb3ciLz48ZmVCbGVuZCBpbj0iU291cmNlR3JhcGhpYyIgaW4yPSJlZmZlY3QxX2Ryb3BTaGFkb3ciIHJlc3VsdD0ic2hhcGUiLz48L2ZpbHRlcj48ZmlsdGVyIGlkPSJjIiB3aWR0aD0iNDcuOTE3IiBoZWlnaHQ9IjExNi4xNTEiIHg9IjYwLjQxNyIgeT0iLTguMDc2IiBjb2xvci1pbnRlcnBvbGF0aW9uLWZpbHRlcnM9InNSR0IiIGZpbHRlclVuaXRzPSJ1c2VyU3BhY2VPblVzZSI+PGZlRmxvb2QgZmxvb2Qtb3BhY2l0eT0iMCIgcmVzdWx0PSJCYWNrZ3JvdW5kSW1hZ2VGaXgiLz48ZmVDb2xvck1hdHJpeCBpbj0iU291cmNlQWxwaGEiIHZhbHVlcz0iMCAwIDAgMCAwIDAgMCAwIDAgMCAwIDAgMCAwIDAgMCAwIDAgMTI3IDAiLz48ZmVPZmZzZXQvPjxmZUdhdXNzaWFuQmx1ciBzdGREZXZpYXRpb249IjQuMTY3Ii8+PGZlQ29sb3JNYXRyaXggdmFsdWVzPSIwIDAgMCAwIDAgMCAwIDAgMCAwIDAgMCAwIDAgMCAwIDAgMCAwLjI1IDAiLz48ZmVCbGVuZCBpbjI9IkJhY2tncm91bmRJbWFnZUZpeCIgbW9kZT0ib3ZlcmxheSIgcmVzdWx0PSJlZmZlY3QxX2Ryb3BTaGFkb3ciLz48ZmVCbGVuZCBpbj0iU291cmNlR3JhcGhpYyIgaW4yPSJlZmZlY3QxX2Ryb3BTaGFkb3ciIHJlc3VsdD0ic2hhcGUiLz48L2ZpbHRlcj48bGluZWFyR3JhZGllbnQgaWQ9ImQiIHgxPSI0OS45MzkiIHgyPSI0OS45MzkiIHkxPSIuMjU4IiB5Mj0iOTkuNzQyIiBncmFkaWVudFVuaXRzPSJ1c2VyU3BhY2VPblVzZSI+PHN0b3Agc3RvcC1jb2xvcj0iI2ZmZiIvPjxzdG9wIG9mZnNldD0iMSIgc3RvcC1jb2xvcj0iI2ZmZiIgc3RvcC1vcGFjaXR5PSIwIi8+PC9saW5lYXJHcmFkaWVudD48L2RlZnM+PC9zdmc+&logoColor=0098FF)](https://marketplace.visualstudio.com/items?itemName=biomejs.biome)
[![](https://img.shields.io/visual-studio-marketplace/v/biomejs.biome?color=374151&label=Open%20VSX%20Registry&labelColor=000&logo=data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0idXRmLTgiPz4KPHN2ZyB2aWV3Qm94PSI0LjYgNSA5Ni4yIDEyMi43IiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciPgogIDxwYXRoIGQ9Ik0zMCA0NC4yTDUyLjYgNUg3LjN6TTQuNiA4OC41aDQ1LjNMMjcuMiA0OS40em01MSAwbDIyLjYgMzkuMiAyMi42LTM5LjJ6IiBmaWxsPSIjYzE2MGVmIi8+CiAgPHBhdGggZD0iTTUyLjYgNUwzMCA0NC4yaDQ1LjJ6TTI3LjIgNDkuNGwyMi43IDM5LjEgMjIuNi0zOS4xem01MSAwTDU1LjYgODguNWg0NS4yeiIgZmlsbD0iI2E2MGVlNSIvPgo8L3N2Zz4=&logoColor=0098FF)](https://open-vsx.org/extension/biomejs/biome)
[![Discord](https://img.shields.io/discord/1132231889290285117?logo=discord&logoColor=white&label=Discord&labelColor=000)](https://discord.gg/BypW39g6Yc)


The **Biome extension for Visual Studio Code** brings first-class support for 
Biome in VS Code and VS Code-based editors. By integrating with Biome's
language server, the extension provides the following features:

- 💾 Format on save
- 🚜 Code refactoring
- 💡 Inline suggestions and quick fixes

## Installation

The Biome extension for VS Code is available on the Visual Studio Marketplace
and the Open VSX Registry.

- 📦 [Visual Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=biomejs.biome) (recommended for *VS Code* users)
- 📦 [Open VSX Registry](https://open-vsx.org/extension/biomejs/biome) (recommended for *VSCodium* users)

## Documentation

The documentation for the extension is available on the [official website](https://biome.dev/).

- [📖 Documentation](https://biomejs.dev/reference/vscode/).

## License

This open source project is dual-licensed under the [MIT License](LICENSE-MIT) and the [Apache License, Version 2.0](LICENSE-APACHE).