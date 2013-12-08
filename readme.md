# 说明
该库为linux下的vim备份 创建自2013.12.08

# 使用说明
1. 将该目录拷备到家目录下 
2. 对vimrc做映射(这样做的目的是linux下.vimrc与.vim目录不在一个目录下，用git不好进行版本控制，所以这里做了软链接)
    cd ~
	rm .vimrc (或者把.vimrc移到其它目录免得这里操作失误又回不去了)
	ln -s .vimrc .vim/.vimrc


# buglist
1. 目前vimwiki插件并没有用pathogen插件控制起来，当时（20131208）把vimwiki相关插件放入bundle下vimwiki插件不能正常工作，后来我重新下载vimwiki插件，然后通过`:so %` 安装，功能正常。所以现在这里这样吧，以后有时间再整理
2. 其它由pathogen 控制的插件反正至少启动vim没错误，但是否能正常工作我也不知道
