# Tmux opener

This script (when put in the .bashrc of a server) will open a tmux session whenever a connection is initiated.

It checks for $SSH and $TMUX (so as not to nest) and attaches to the next available session - this may be an active session that was detached or a fresh session

