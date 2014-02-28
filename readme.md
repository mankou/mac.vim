# 说明
该库为mac下的vim备份 创建自2014-02-28 21:43:32
其前身是我原来linux下vim的配置 后来改了改 规范了下 又纳入mac

# 使用说明
1. 将该目录拷备到家目录下 并改名为.vim
2. 对vimrc做映射(这样做的目的是linux下.vimrc与.vim目录不在一个目录下，用git不好进行版本控制，所以这里做了软链接)
    cd ~
	rm .vimrc (或者把.vimrc移到其它目录免得这里操作失误又回不去了)
	ln -s .vim/.vimrc .vimrc


# buglist
