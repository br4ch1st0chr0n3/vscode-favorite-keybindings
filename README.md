# Purescript typed holes keybindings

* Add a typed hole for a word containing the cursor or a selection: `Ctrl` + `Alt` + `Z`
    * cursor inside `hey` -> `(hey :: ?_)`
    * selected `make good` -> `(make good :: ?_)`

* Remove the typed hole: `Ctrl` + `Alt` + `X`

This extension depends on

* [ryuta46.multi-command](https://marketplace.visualstudio.com/items?itemName=ryuta46.multi-command)
* [dbankier.vscode-quick-select](https://marketplace.visualstudio.com/items?itemName=dbankier.vscode-quick-select)

So, please, don't disable them!