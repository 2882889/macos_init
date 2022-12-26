## mac 新机器配置

### 安装 Xcode

### 安装 clashX

### 安装 homebrew

安装前需要给终端设置代理

```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
// 执行配置
echo '# Set PATH, MANPATH, etc., for Homebrew.' >> /Users/wanxin3/.zprofile
echo 'eval "$(/opt/homebrew/bin/brew shellenv)"' >> /Users/wanxin3/.zprofile
eval "$(/opt/homebrew/bin/brew shellenv)"
```

### 安装 iterm2

brew install iterm2

### 安装 zsh

sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"

### 安装 rectangle

brew install rectangle

### 安装 bob

brew install bob

### 安装 cliclick

brew install cliclick

用来模拟鼠标和键盘，用在alfred


### 安装 cocoapod

sudo gem install cocoapods -v 1.8.4

### 安装 git-lfs

brew install git-lfs

### 生成公钥

ssh-keygen -t rsa -C "your_sina_id@mail.com"

### 安装node.js

官网下载安装包安装
