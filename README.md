# iterm2-配置
## 配置主题
#### 只需要修改 .zshrc 文件中的 ZSH_THEME="xx" 属性即可。
#### 我目前使用的主题是：spaceship
#### 1.下载主题文件：
git clone https://github.com/denysdovhan/spaceship-prompt.git "$ZSH_CUSTOM/themes/spaceship-prompt" --depth=1
#### 2.创建软连接
ln -s "$ZSH_CUSTOM/themes/spaceship-prompt/spaceship.zsh-theme" "$ZSH_CUSTOM/themes/spaceship.zsh-theme"
#### 3.修改zsh配置
vim ~/.zshrc
#### 4.修改：
ZSH_THEME="spaceship"
#### 5.生效：
source ~/.zshrc
## 下载Oh-My-Zsh
curl方式
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
或者使用wget：
sh -c "$(wget https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh -O -)"
## 配置命令自动提示
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
## 配置语法高亮显示
brew install zsh-syntax-highlighting
## 配置autojump
brew install autojump
## seadra--pokemonsay安装
$ git clone http://github.com/possatti/pokemonsay  

$ cd pokemonsay  

$ ./install.sh
### 最后将zshrc.yaml修改成.zshrc替换～目录下同名文件。如有报错按照相关提示修改最后几行配置选项
![展示1](https://github.com/YiLin008/iterm2-config/blob/main/show1.jpg)
![展示2](https://github.com/YiLin008/iterm2-config/blob/main/show2.jpg)

