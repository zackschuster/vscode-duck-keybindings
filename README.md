# Duck Keymap for VS Code

Some custom keymaps for VS Code. Quack.

## Which keybindings are added?

Command | Keymap | When
--------|--------|-----
editor.action.format | ctrl+k ctrl+f | editorTextFocus
editor.action.quickFix | ctrl+space | editorHasCodeActionsProvider && editorTextFocus && !editorReadonly
editor.emmet.action.wrapWithAbbreviation | ctrl+shift+a
workbench.action.closeOtherEditors | ctrl+shift+/
workbench.action.files.saveAll | ctrl+shift+s
workbench.action.focusFirstEditorGroup | ctrl+,
workbench.action.tasks.runTask | f1
workbench.action.terminal.focus | ctrl+.
workbench.action.terminal.toggleTerminal | ctrl+'
workbench.action.terminal.focusNext | ctrl+;
workbench.action.terminal.focusPrevious | ctrl+shift+;
workbench.action.terminal.new | ctrl+shift+'
workbench.action.terminal.kill | ctrl+shift+/
workbench.action.reloadWindow | shift+f5

## License
[MIT](license.txt)
