# vim_config

## vim 配置
git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim  
cd \/tempdir/ git clone https://github.com/tomasr/molokai.git && cp -r molokai/colors ~/.vim/
```bash

```

## vim复制到系统剪贴板
vim --version | grep "clipboard"  
clipboard前面有一个小小的减号，说明不支持。sudo apt-get install vim-gtk3  

## vim 列编辑
1. ctrl + v　选择编辑列
2. shift + i （I) 编辑模式
3. 按两次Esc显示编辑内容

## vim 折叠｜展开
1. vim 折叠方式  
   * manual 手工定义折叠
   * indent 更多的缩进表示更高级的折叠(目前使用)
   * expr 用表达式定义折叠
   * syntax 用语法高亮定义折叠
   * diff 对没有更改的文本进行折叠
   * marker 对文中标志折叠

2. 打开与折合
   * zc 折叠
   * zC 对所在范围内所有嵌套折叠点进行折叠
   * zo 展开折叠
   * zO 对所在范围内所有嵌套的折叠点展开
   * [z 到当前打开折叠开始处
   * ]z 到当前打开折叠末尾处
   * zj 向下移动．到达下一个折叠开始处．关闭折叠也被计入
   * zk 向上移动到前一折叠的结束处．关闭折叠也被计入．
