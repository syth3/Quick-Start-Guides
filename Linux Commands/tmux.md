# tmux Quick Start Guide

## Session Management
**Creating a session**
```
tmux new -s <session_name>
```
**Attaching to a Session**
```
tmux attach -t <session_name>
```
**Detaching from a Session Without Closing it**

`Ctrl+b` `d`

**List tmux Sessions**
```
tmux ls
```

## Window Management
**Split pane vertically**

`Ctrl+b` `"`

**Split Pane Horizontally**

`Ctrl+b` `%`

**Switch Active Pannel**

`Ctrl+b` `arrow-key`

**Scroll Up**

`Ctrl+b` `[` `arrow-key` or `Ctrl+b` `[` `PgUp/PgDn`

**Exit Scroll Mode**

`q`

**Open New Window**

`Ctrl+b` `c`

**Switch Window by Number**

`Ctrl+b` `<number 0-9>`

**Rename Window**

`Ctrl+b` `,`

## Additional Information
- https://tmuxcheatsheet.com/
