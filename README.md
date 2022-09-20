# Purescript keybindings for typed holes

* Insert a typed hole for a word containing the cursor or a selection: `Ctrl` + `Alt` + `Z`
  * cursor inside `hey` -> `(hey :: ?_)`
  * selected `make good` -> `(make good :: ?_)`

* Remove the typed hole: `Ctrl` + `Alt` + `X`

This extension depends on

* [ryuta46.multi-command](https://marketplace.visualstudio.com/items?itemName=ryuta46.multi-command)
* [chunsen.bracket-select](https://marketplace.visualstudio.com/items?itemName=chunsen.bracket-select)

So, please, don't disable them!
