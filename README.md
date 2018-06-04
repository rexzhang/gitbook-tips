# Mac 开发常用软件安装

## Mac 开发常用软件安装 {#mac-开发常用软件安装}

### 基本原则 {#基本原则}

* App 安装源的优先级: App Store &gt;&gt; homebrew &gt;&gt; 有签名的软件
* 没有签名的软件不要安装
* 不得安装破解软件

### 准备工作 {#准备工作}

* 注册 Apple ID[https://appleid.apple.com/account](https://appleid.apple.com/account)

### 新机器准备流程 {#新机器准备流程}

务必单线程串行执行

1. 使用 Apple ID 激活 Mac
2. App Store 安装 xcode
3. 命令行安装 xcode CLI 组件`xcode-select —install`
4. 安装 homebrew
   1. [https://brew.sh/index\_zh-cn.html](https://brew.sh/index_zh-cn.html)
   2. /usr/bin/ruby -e "$\(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install\)"
5. 安装 homebrew cask
   1. [https://caskroom.github.io/](https://caskroom.github.io/)
   2. `brew tap caskroom/cask`
   3. `brew tap buo/cask-upgrade`
6. 安装 homebrew Casks of Drivers
   1. [https://github.com/caskroom/homebrew-drivers](https://github.com/caskroom/homebrew-drivers)
   2. `brew tap caskroom/drivers`

### Python {#python}

#### 安装 py3、py2 解释环境 {#安装-py3、py2-解释环境}

`brew install python3 python@2`

#### 建立虚环境 {#建立虚环境}

**python3**

`virtualenv venv`

**python2**

`virtualenv -p python2 venv`

### 前端工具 {#前端工具}

`brew install bower`

### 数据库 {#数据库}

#### PostgreSQL {#postgresql}

`brew cask install postgres pgadmin4`

#### Redis {#redis}

`brew install redis`

#### 网络工具 {#网络工具}

`brew cask install wireshark`

### 通过 App Store 安装的常用软件 {#通过-app-store-安装的常用软件}

* Slack
* 印象笔记
* Valentina Studio
* PG Commander
* 网易有道词典
* WeChat \(微信\)
* 企业微信
* QQ
* Amphetamine \(禁止锁屏\)
* 截图\(Jietu\)

### 通过 brew 安装的常用软件 {#通过-brew-安装的常用软件}

#### 系统增强 {#系统增强}

`brew cask install iterm2 java karabiner-elements cheatsheet betterzip`

#### 开发相关 {#开发相关}

`brew cask install atom dash filezilla beyond-compare postman sourcetree visual-studio-code`

#### 效率相关 {#效率相关}

`brew cask install alfred workflowy typora`

#### 其他常用 {#其他常用}

`brew install htop midnight-commander`

`brew cask install google-chrome firefox`

### 需要官网下载安装的常用软件 {#需要官网下载安装的常用软件}

* pycharm
* vmware fusion
* seafile[https://www.seafile.com/download/](https://www.seafile.com/download/)

### Brew 触发更新软件操作 {#brew-触发更新软件操作}

`brew upgrade`

`brew cu -a`

