# eclipse-keybindings package for Atom

This [Atom](https://atom.io/) package supports some basic [Eclipse IDE](https://eclipse.org/) text editor key mappings. Currently the Eclipse shortcuts are directly mapped to existing Atom commands.

## Supported keybindings

Mac users: press `Cmd` instead of `Ctrl` (same as in Eclipse on Mac).

* `Ctrl + Shift + F`: Format Code (Eclipse) / Auto Indent (Atom)
* `Alt + Up`: Move line Up
* `Alt + Down`: Move line Down
* `Ctrl + L` Go to line...
* `Ctrl + D` Delete line
* `Ctrl + Alt + Down`: Duplicate lines
* `Ctrl + Alt + J`: Join lines
* `Ctrl + Shift + /` Toggle Comment (already the Atom default)

These keybindings might conflict with keybindings of other installed Atom packages. (You can find out which ones by using the Keybinding Resolver: `Ctrl + .`)

## Issues / Features

### Known issues
* `Ctrl + D` is also bound to `find-and-replace:select-next`
* `Ctrl + Shift + /` Toggle Comment seems to be mapped to a different key combination on non-english layouts

### Request features
If you request a new keybinding please specify which Atom command should be executed when the keys are pressed. The full Atom Command Palette is available by pressing `Ctrl + Shift + P`.

Please note that Atom might not (yet) have a corresponding functionality for a specific Eclipse command.
