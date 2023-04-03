# rust.vim installation
git clone https://github.com/rust-lang/rust.vim ~/.vim/pack/plugins/start/rust.vim

# black.vim installation
mkdir -p ~/.vim/pack/python/start/black/plugin \
&& mkdir -p ~/.vim/pack/python/start/black/autoload \
&& curl https://raw.githubusercontent.com/psf/black/stable/plugin/black.vim -o ~/.vim/pack/python/start/black/plugin/black.vim \
&& curl https://raw.githubusercontent.com/psf/black/stable/autoload/black.vim -o ~/.vim/pack/python/start/black/autoload/black.vim

# vim-go installation
git clone https://github.com/fatih/vim-go.git ~/.vim/pack/plugins/start/vim-go
