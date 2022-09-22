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

- `Ctrl+b` `arrow-up`
- `Ctrl+b` `arrow-dowm`
- `Ctrl+b` `arrow-left`
- `Ctrl+b` `arrow-right`

**Scroll Up**

`Ctrl+b` `[` `arrow-key` or `Ctrl+b` `[` `PgUp/PgDn`

**Exit Scroll Mode**

`q`

## Additional Information
- https://tmuxcheatsheet.com/
