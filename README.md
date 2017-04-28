# Duck Keymap for VS Code

Some custom keymaps for VS Code. Quack.

## Which keybindings are added?

Command | Keymap | When
--------|--------|-----
editor.action.format | ctrl+k ctrl+f | editorTextFocus
editor.action.quickFix | ctrl+space | editorHasCodeActionsProvider && editorTextFocus && !editorReadonly
editor.emmet.action.wrapWithAbbreviation | ctrl+shift+a
workbench.action.files.saveAll | ctrl+shift+s
workbench.action.focusFirstEditorGroup | ctrl+,
workbench.action.reloadWindow | shift+f5
workbench.action.showErrorsWarnings | ctrl+shift+i
workbench.action.tasks.runTask | f4
workbench.action.terminal.focus | ctrl+.
workbench.action.terminal.focusNext | ctrl+;
workbench.action.terminal.focusPrevious | ctrl+shift+;
workbench.action.terminal.kill | ctrl+shift+/
workbench.action.terminal.new | ctrl+shift+'
workbench.action.terminal.toggleTerminal | ctrl+'

## License
[MIT](license.txt)
