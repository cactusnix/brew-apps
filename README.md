# brew-apps
🍭Awesome list of applications can be installed by homebrew.

## Homebrew 的介绍
简而言之，就是Mac的包管理工具。具体的可以查看官网。
[Homebrew](https://brew.sh/index_zh-cn)

## 开发的包
brew最基本的功能就是安装开发需要的包以及工具，比如mysql、tomcat、java、node、python、go等等都可以通过brew进行安装。在此就不一一列举。

`brew install XXX`

## 非 Mac Apple Store
除了可以安装包以外，homebrew也可以安装带有UI的app，在此列出可以通过brew cask安装的app，对应英文名字，方便大家进行安装，不用频繁的进行 `brew search XXX`。

网易云音乐 `brew cask install neteasemusic`

QQ `brew cask install qq`

微信 `brew cask install wechat`

腾讯柠檬清理 `brew cask install tencent-lemon`

Visual Studio Code `brew cask install visual-studio-code`

Clipy(剪贴板工具) `brew cask install clipy`

postman(网络工具) `brew cask install postman`

pap.er(自动更换壁纸工具) `brew cask install paper`

keka(解压缩工具) `brew cask install keka`

Google Chrome `brew cask install google-chrome`

IINA(视频播放器) `brew cask install iina`

iTerm(终端) `brew cask install iterm2`

terminus(终端) `brew cask install terminus`

IDEA(Java的idea) `brew cask install intellij-idea`

qlstephen(增强Mac空格预览的能力，可以以文本方式预览一些文件) `brew cask install qlstephen`

Cakebrew(Homebrew可视化) `brew cask install cakebrew`

launchrocket(service可视化-系统设置里面) `brew cask install launchrocket`

motrix(完美替代迅雷的下载器) `brew cask install motrix`


## Mac Apple Store
对于那些只提供Mac Apple Store下载的软件，我们如果也需要通过brew进行安装的话，就需要安装mas，具体介绍可以在官网查看。
[mas](https://github.com/mas-cli/mas)

`brew install mas`

## Tips
1. 要经常更新hombrew, 会更新本身包信息以及对应的一些cask信息（可能包、cask的下载地址都会有所变化），这样之后brew的包才能正确，brew cask才能及时更新到最新的版本，同时不会出现校验错误。
2. 关于Java的版本问题，建议使用openJDK。技术永远在更新，然而我们似乎永远在停留。
