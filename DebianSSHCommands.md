# Debian SSH Commands

## tmux

### List and Attach

- tmux ls (list sessions)
- tmux attach -t session_name (attach to session)
- tmux detach (detach from session)

### Creation

- tmux new -s session_name -n window_name (create new session with window name)
- tmux new -s session_name (opens new session name)

### Rename

- tmux rename-session -t session_name new_session_name (rename session)
- tmux rename-window -t window_name new_window_name (rename window)

### Kills

- tmux kill-window -t window_name (kill window)
- tmux kill-session -t session_name (kill session)
- tmux kill-session -a (kill all sessions)
- tmux kill-server (kill server)

### In Session Commands

- Ctrl + b + d (detach from session)
- Ctrl + b + c (create new window)
- Ctrl + b + n (next window)
- Ctrl + b + p (previous window)
- Ctrl + b + w (list windows)
- Ctrl + b + , (rename window)
- Ctrl + b + & (kill window)
- Ctrl + b + % (split window horizontally)
- Ctrl + b + " (split window vertically)
- Ctrl + b + arrow (move between panes)
- Ctrl + b + x (kill pane)
- Ctrl + b + z (toggle zoom)
- Ctrl + b + [ (enter copy mode)
- Ctrl + b + ] (paste from buffer)
- Ctrl + b + : (command prompt)
- Ctrl + b + ? (list shortcuts)
- Ctrl + b + o (move to next pane)
- Ctrl + b + ; (move to previous pane)
- Ctrl + b + { (move pane left)
- Ctrl + b + } (move pane right)
- Ctrl + b + ! (move pane to new window)
- Ctrl + b + Ctrl + o (rotate windows)