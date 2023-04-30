# Tmux
### Installation
Keep your `.tmux.conf` in the `~/` directory.

Install `tmux` with the following from your preferred repository. I use apt : 
```
$ sudo apt install tmux
```
</br>

### Completion for Tmux
I recommend installing `bash-completion` . : 
```
$ sudo apt install bash-completion
```
Then add the tmux completion tool `imomaliev/tmux-bash-completion` to it for tab completion of the CLI-arguments.
<br/> 


### Plugins
I use the [tmux-plugins](https://github.com/tmux-plugins/tpm) plugin manager to make working in tmux more managable.
- `tmux-plugins/tmux-resurrect` to save tmux sessions in between reboots 
- `tmux-plugins/tmux-continuum` saves tmux environment and restores the server
- `jrihon/tmux-theme` custom theme, forked from `catppuccin/tmux`
