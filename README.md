### Quick start

```bash
$ ln -s <source_file> <target_file>

# use start.sh (under repo's dir)

$ sh start.sh

# e.g. (under $HOME)

$ ln -s dotfiles/vim/.vimrc .vimrc
```

### Issues:
 - YouCompleteMe unavailable no module named frozendict 
 - YouCompleteMe unavailable no module named future

### Solution:
```
cd ~/.vim/bundle/YouCompleteMe
git submodule update --init --recursive
```

[前端开发工具流](https://github.com/metaczen/blog/issues/1)
