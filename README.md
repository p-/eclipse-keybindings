# eclipse-keybindings package for Atom

This [Atom](https://atom.io/) package provides [Eclipse IDE](https://eclipse.org/) key mappings for Atom. Currently the Eclipse shortcuts are directly mapped to existing Atom commands.

## Installing

Use the Atom package manager, which can be found in the Settings view or
run `apm install eclipse-keybindings` from the command line.

## Supported keybindings

Mac users: press `⌘` instead of `Ctrl` (same as in Eclipse on Mac).

### General
* `Ctrl-Shift-R` Open Resource (Eclipse) / Find File (Atom)
* `Ctrl-Shift-S` Save All
* `Ctrl-3` Quick Access (Eclipse) / Command Palette (Atom)
* `Ctrl-H` Find in Project (same on Mac)
* `Ctrl-E` Quick Switch Editor (Eclipse) / Find in Buffer (Atom)

### Source Editor
* `Ctrl-Shift-F` Format Code (Eclipse) / Auto Indent (Atom)
* `Alt-↑` Move line Up
* `Alt-↓` Move line Down
* `Ctrl-L` Go to line...
* `Ctrl-D` Delete line
* `Ctrl-Alt-↓` Duplicate lines
* `Ctrl-Alt-J` Join lines
* `Ctrl-O` Show Outline (Eclipse) / File Symbols (Atom)
* `Ctrl-Shift-X` Upper Case
* `Ctrl-Shift-Y` Lower Case
* `Ctrl-Shift-P` Go to matching bracket
* `Ctrl-Shift-C` Toggle Comments
* `Alt-Shift-↑` Select inside brackets
* `Alt-/` Autocomplete (not on Mac)
* `Ctrl-/` Toggle Comment (already the Atom default)

These keybindings might conflict with keybindings of other installed Atom packages. (You can find out which ones by using the Keybinding Resolver: `Ctrl-.`)

## Issues / Features

### Known issues
* The [Emmet](https://atom.io/packages/emmet) package overwrites several keybindings used by eclipse-keybindings.
* Some actions are also mapped to other keybindings so the eclipse keybinding won't show up next to the menu entry.
* `Ctrl-D` is also bound to `find-and-replace:select-next`
* `Ctrl-/` Toggle Comment is mapped to a different key combination on non-english layouts (see: [Atom Keymap Issue](https://github.com/atom/atom-keymap/issues/37)).

### Request features
If you request a new keybinding please specify which Atom command should be executed when the keys are pressed. The full Atom Command Palette is available by pressing `Ctrl-3`.

Please note that Atom might not (yet) have a corresponding functionality for a specific Eclipse command.
