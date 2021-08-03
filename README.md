### Quick start

```bash
$ ln -s <source_file> <target_file>

# use start.sh (under repo's dir)

$ sh start.sh

# e.g. (under $HOME)

$ ln -s dotfiles/vim/.vimrc .vimrc
```



### Q&A

#####1. 保存时自动格式化没生效 ?

如果是手动安装vim-prettier，需要进入vim/vim-prettier目录执行yarn install

步骤如下:

```bash
cd ~/.vim/bundle/

git clone https://github.com/prettier/vim-prettier

cd vim-prettier cd inside prettier root directory and do yarn install or npm install
```

