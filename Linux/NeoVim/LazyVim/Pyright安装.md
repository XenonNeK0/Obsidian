## 安装HomeBrew
- 首先安装*HomeBrew*
```shell
sh -c "$(curl -fsSL https://raw.githubusercontent.com/Linuxbrew/install/master/install.sh)"
```
- 环境变量添加到*zsh*中
```shell
echo 'export PATH="/home/linuxbrew/.linuxbrew/bin:$PATH"' >> ~/.zshrc
source ~/.zshrc
```
- 给*brew*换源，编辑*zsh*配置文件
```shell
export HOMEBREW_BREW_GIT_REMOTE="https://mirrors.tuna.tsinghua.edu.cn/git/homebrew/brew.git"
export HOMEBREW_CORE_GIT_REMOTE="https://mirrors.tuna.tsinghua.edu.cn/git/homebrew/linuxbrew-core.git"
export HOMEBREW_API_DOMAIN="https://mirrors.tuna.tsinghua.edu.cn/homebrew-bottles/api"
export HOMEBREW_BOTTLE_DOMAIN="https://mirrors.tuna.tsinghua.edu.cn/homebrew-bottles"
```
- 安装pyright
```shell
brew install pyright
```
## LazyVim配置
- 在*LazyVim*中选择**python**语言选项
```LazyVim
:LazyExtras
```
- 在*python*选项下面按"x"
	- 如没有*python*
```LazyVim
/lang.pyhton
```
- 之后重新启动就可以自动下载