# Issues

## VSCodeVimSelection

### Unexpected behaviour: In visual mode (any) <code>`\<S-,\></code> does not take you to the start of the last selection

- **Describe the bug**: Mode: Visual/Visual-Line/Visual-Block <code>`\<S-,\></code> does not take you to the start of the last selection made in a visual mode.
- **To Reproduce**: Steps to reproduce the behavior:
  - Go to any visual mode
  - Go back to normal mode
  - Scroll down to another location
  - Enter a visual mode and press <code>`\<S-,\></code>
- **Expected behavior**: Ideally selection expands to start of last selection ![gif](vscodevimselection/vscodevimselection.gif)

Repository for issues created.

## Vim Change Hitory

- **Extension**: `vscodevim.vim`
- **Repo**: [Vim](https://github.com/VSCodeVim/Vim)
- Vim extension does not support moving over multiple changes in the change list with `ng;/,` where `n` is a number. ![gif](vscodevimchangehistory/Animation.gif)

### Move to first change in change list with `2g;`

- This line represents the first change in the change list.
- This line represents the second change in the change list.
- This line represents the third change in the change list.
