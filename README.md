## sctmux

simple configuration for Tmux.



```BASH
# Clone sctmux
# Tmux reads $HOME/.tmux.conf and $HOME/.config/tmux/tmux.conf.
# Make sure $HOME/.tmux.conf doesnot exist
git clone git@github.com:davidzgli/sctmux.git ~/.config/tmux
# Clone pluging manager
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
# type this in terminal if tmux is already running
tmux source ~/.tmux.conf
```

**NOTE**
- If you don't use plugin manager *tmp*, comment out the *plugins* section
- If Your default shell is fish, or shell switching is configured in ~/.bashrc or ~/.bash_profile, comment out the two fish shell related commands.


Press prefix + I (capital i, as in Install) to fetch the plugin in Tmux. 




