# eclipse-keybindings package for Atom

The [Atom](https://atom.io/) package eclipse-keybindings supports some basic [Eclipse IDE](https://eclipse.org/) text editor key mappings. Currently the Eclipse shortcuts are directly mapped to existing Atom commands.

## Supported keybindings

For Mac users: press `Cmd` instead of `Ctrl` (same as in Eclipse on Mac).

* `Ctrl + Shift + f`: Format Code (Eclipse) / Auto Indent (Atom)
* `Alt + Up`: Move line Up
* `Alt + Down`: Move line Down
* `Ctrl + l` Go to line...
* `Ctrl + d` Delete line
* `Ctrl + Shift + /` Toggle Comment (already the Atom default)

These keybindings might conflict with keybindings of other installed Atom packages. (You can find out which ones by using the Keybinding Resolver: `Ctrl + .`)

## Issues / Features

### Known issues
* `Ctrl + d` is also bound to `find-and-replace:select-next`

### Request features
If you request a new keybinding please specify which Atom command should be executed when the keys are pressed. The full Atom Command Palette is available by pressing `Ctrl + Shift + P`.

Please note that Atom might not (yet) have a corresponding functionality for all Eclipse commands.
