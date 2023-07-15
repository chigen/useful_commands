#tmux commands

## create a session
tmux new -s <session-name>

## detach a session
In a tmux session, press ctrl+b d, or enter: 
tmux detach

## list existing sessions
tmux ls

## attach a session
use session id:
tmux attach -t 0
use session name:
tmux attach -t <session-name>

## kill a session
use session id:
tmux kill-session -t 0
use session name:
tmux kill-session -t <session-name>

## switch a session
use, tmux switch + (id or name), to switch
