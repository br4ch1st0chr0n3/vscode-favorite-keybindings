# Purescript typed holes keybindings

* Add a typed hole for a word containing the cursor or a selection: `Ctrl` + `Alt` + `Z`
    * cursor inside `hey` -> `(hey :: ?_)`
    * selected `make good` -> `(make good :: ?_)`

* Remove the type hole: `Ctrl` + `Alt` + `X`

## Dependencies

* [ryuta46.multi-command](https://marketplace.visualstudio.com/items?itemName=ryuta46.multi-command)
* [dbankier.vscode-quick-select](https://marketplace.visualstudio.com/items?itemName=dbankier.vscode-quick-select)