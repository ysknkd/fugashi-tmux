
## Description

## Usage

```console
$ ln -s $HOME/.fugashi-tmux/.tmux.conf $HOME/.tmux.conf
$ ln -s $HOME/.fugashi-tmux/tmux-pane-border.sh /usr/local/bin/tmux-pane-border
```

```console
$ cat <<EOF >> .zshrc
## tmux
if [[ ! -n "\$TMUX" ]]; then
  tmux new-session && exit
fi
EOF
```
