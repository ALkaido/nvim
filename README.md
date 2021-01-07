# 我的vim/neovim的配置文件

vim的配置文件的目录为`~/.vimrc`
neovim的配置文件的目录为`~/.config/nvim/init.vim`

## 环境
[coc.nvim](https://github.com/junegunn/vim-plug)
下载`coc.nvim`
`sudo su` 输入密码后进入root权限下后`curl -sL install-node.now.sh/lts | bash`   
nerd-fonts （arch系用户可以直接`sudo pacman -S nerd-fonts`）
### 安装
```
cd .config
git clone https://github.com/alkaido/nvim.git
```

最后`PlugInstall`

按键|映射|作用
-|-|-
`sl` | `set splitright<CR>:vsplit<CR>` | 向右分屏
`sh` | `set nosplitright<CR>:vsplit<CR>` | 向左分屏
`sj` | `set splitbelow<CR>:split<CR>` | 向下分屏
`sk` | `set nosplitbelow<CR>:split<CR>` | 向上分屏
`F4` | `call HeadFile()<CR>` | 添加头文件
`ctrl+n` | `:NERDTreeToggle<CR>` | 
`F5` | `call CompileRunGcc()<CR>` | 判断文件类型并编译
`ctrl+l` | `:set splitright<CR> :vsplit<CR> :term<CR>` | 向右分屏并打开终端
`ctrl+h` | `<C-h> <C-\><C-n><C-w>h` | 退出终端编辑模式并返回左侧屏幕
