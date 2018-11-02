## vim-dictionary：VIM 词表收集

Author: [Jayli](https://github.com/jayli)

收集了一份常用编程语言的 VIM 词表，插件安装后不用做任何配置即可生效，词典文件在`vim-dictionary/dict/{&filetype}.*`

只要保持`{&filetype}.*`作为该语言的词表文件即可，后缀不限

### 安装

#### 基于 [Pathogen.vim](https://github.com/tpope/vim-pathogen) 安装（VIM7 & 8)

	cd ~/.vim/bundle/
	git clone https://github.com/jayli/vim-dictionary.git

#### - 基于 [Vundle.vim](https://github.com/VundleVim/Vundle.vim) 安装（VIM7 & 8）

在`.vimrc`中添加下面代码，进入`vim`后执行`:PluginInstall`

	Plugin 'jayli/vim-dictionary'

#### 基于 VIM8 可以直接安装

	git clone https://github.com/jayli/vim-dictionary.git \
		~/.vim/pack/dist/start/vim-dictionary

Done!

**配合 [Vim-EasyComplete](https://github.com/jayli/vim-easycomplete) 一起使用体验最佳!**




