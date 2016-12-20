# Duck Keymap for VS Code

Some custom keymaps for VS Code. Quack.

## Which keybindings are added or removed?

Command | Keymap | When
--------|--------|-----
editor.action.format | ctrl+k ctrl+f | editorTextFocus
-editor.action.format | shift+alt+f | editorTextFocus
editor.emmet.action.wrapWithAbbreviation | ctrl+shift+a
workbench.action.closeOtherEditors | ctrl+shift+/
workbench.action.files.saveAll | ctrl+shift+s
-workbench.action.files.saveAs | ctrl+shift+s
workbench.action.focusFirstEditorGroup | ctrl+
workbench.action.terminal.focus | ctrl+.
-editor.action.quickFix | ctrl+.
editor.action.quickFix | ctrl+space | editorHasCodeActionsProvider && editorTextFocus && !editorReadonly
workbench.action.terminal.toggleTerminal | ctrl+'
-workbench.action.terminal.toggleTerminal | ctrl+`
workbench.action.terminal.focusNext | ctrl+;
workbench.action.terminal.focusPrevious | ctrl+shift+;
workbench.action.terminal.new | ctrl+shift+'
-workbench.action.terminal.new | ctrl+shift+`
workbench.action.terminal.kill | ctrl+shift+/
-workbench.action.quickOpen | ctrl+e
workbench.action.reloadWindow | shift+f5

## License
[MIT](license.txt)
