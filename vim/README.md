# VIM配置文件

### 依赖插件：pathogen&vundle
- pathogen
```bash
mkdir -p ~/.vim/autoload ~/.vim/bundle && curl -LSso ~/.vim/autoload/pathogen.vim https://tpo.pe/pathogen.vim
```
- vundle
```bash
git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim
```
### 使用方法
先下载`.vimrc`文件：
```bash
wget https://raw.githubusercontent.com/asheroin/xxxrc/master/vim/.vimrc
```
打开vim，输入 `:BundleInstall`
