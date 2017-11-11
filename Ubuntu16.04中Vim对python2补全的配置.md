
打开终端，执行下列命令
```
wget -qO https://raw.github.com/ma5174/vim/master/setup.sh | sh -x
```
然后

```
sudo apt-get install vim-gtk3-py2
```

 
利用如下命令将python3切换为python2

```
sudo update-alternatives --config vim
```
可以用`vim --version`来查看结果，出现了`+python`就算成功了。
最后，安装`jedi-vim`

```
git clone --recursive https://github.com/davidhalter/jedi-vim.git  ~/.vim/bundle/jedi-vim
```

  
