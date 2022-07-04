# My Favorite Hotkeys

Hotkeys are intended to support quick jumping over big chunks of code.

There is many ways how you can jump between lines.
- `F3` / `Shift` + `F3` - is swiss knife in many situations, see "Context-dependency" section
- `Ctrl` + `[` / `Ctrl` + `]` - jumps between occurences of text under cursor
- `Ctrl` + `Shift` + `[` / `Ctrl` + `Shift` + `]` - similar to previous, but adds occurence to current selection. It uses multi-cursors and allows to quickly manage copy-pasted code
- `Alt` + `;` / `Alt` + `'` - jumps between found problems in file
- `Ctrl` + `;` / `Ctrl` + `'` - demands `alefragnani.bookmarks` extension and allows to jump between bookmarks in the same file
- And always remember default `F1` key which is the quickest way to get into command palette, which is also a file finder!

## Context-dependency

Same `F3`/`Shift` + `F3` behaves differently in diffirent cases.
- If in diff or in simple editor and have no selection or search widget, they jump between changes
- If there is selection, they jump between occurences of selected text
- If there is search widget, they jump between searched string
