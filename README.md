# kate_like_python_ide

folders:

~/.config/kate/lspclient/
~/.bin/

files:
~.bash_profile
~/.config/pycodestyle

```
[[ -f ~/.bashrc ]] && . ~/.bashrc

export PATH="${PATH}:~/.bin"
```
packages jls:
pikaur -S jedi-language-server python-pylint

pacman -S python-lsp-server autopep8 flake8 python-mccabe python-pycodestyle python-pydocstyle python-pyflakes python-pylint python-rope python-whatthepatch yapf
pip install pytoolconfig
