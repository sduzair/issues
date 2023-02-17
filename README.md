# Issues

### Unexpected behaviour: In visual mode (any) <code>`\<S-,\></code> does not take you to the start of the last selection
**Describe the bug**
Mode: Visual/Visual-Line/Visual-Block
<code>`\<S-,\></code> does not take you to the start of the last selection made in a visual mode.

**To Reproduce**
Steps to reproduce the behavior:

1.  Go to any visual mode
2.  Go back to normal mode
3.  Scroll down to another location
4.  Enter a visual mode and press <code>`\<S-,\></code> 

**Expected behavior**
Ideally selection expands to start of last selection

![](https://github.com/sduzair/issues/blob/main/vscodevimselection/vscodevimselection.gif)
