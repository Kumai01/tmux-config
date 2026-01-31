# tmux-config

`mkdir -p ~/.tmux/plugins/tpm`

`git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm`

`mkdir -p ~/.tmux/conf`

`git clone https://github.com/Kumai01/tmux-config.git ~/.tmux/conf`

`echo 'source-file ~/.tmux/conf/tmux.conf' >> ~/.tmux.conf`

to source changes: 

`tmux source-file ~/.tmux.conf`

to install plugins: `<leader> + I` in tmux
to update plugins: `<leader> + U` in tmux

