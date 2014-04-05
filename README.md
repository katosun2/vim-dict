VIM字典仓库
============

  - css.dic CSS 2.1规范
  - javascript.dic
  - node.dic Node.js
  - php.dic

安装
----

**Vundle** 方式安装

在`_vimrc`或/`.vimrc`中加入

	Plugin 'katosun2/vim-dict'

重启VIM后运行`:PluginInstall`就能完成安装了。

**常规** 方式安装

将dict目录移动到`$VIM/vimfiles`目录。

然后在你的`_vimrc`或/`.vimrc`中加入以下内容

	autocmd filetype javascript set dictionary+=$VIMFILES/bundle/vim-dict/dict/javascript.dic
	autocmd filetype javascript set dictionary+=$VIMFILES/bundle/vim-dict/dict/node.dic
	autocmd filetype css set dictionary+=$VIMFILES/bundle/vim-dict/dict/css.dic
	autocmd filetype php set dictionary+=$VIMFILES/bundle/vim-dict/dict/php.dic

使用方法
---------

在输入模式下按`<ctrl-x>_<ctrl-k>`即可看到提示内容了

TODO
-----



