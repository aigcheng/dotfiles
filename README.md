### Quick start

```bash
$ ln -s <source_file> <target_file>

# use start.sh (under repo's dir)

$ sh start.sh

# e.g. (under $HOME)

$ ln -s dotfiles/vim/.vimrc .vimrc
```

### Q&A

##### 1. 保存时自动格式化没生效 ?

如果是手动安装 vim-prettier，需要进入 vim/vim-prettier 目录执行 yarn install

步骤如下:

```bash
cd ~/.vim/bundle/

git clone https://github.com/prettier/vim-prettier

cd vim-prettier cd inside prettier root directory and do yarn install or npm install
```
