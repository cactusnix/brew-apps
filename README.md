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

[社交类](###社交类)

[音乐类](###音乐类)

[视频类](###视频类)

[图片类](###图片类)

[下载类](###下载类)

[解压类](###解压类)

[开发工具](###开发工具)

[其他类](###其他类)


### 社交类

**QQ** 

```shell
$ brew cask install qq
```

**微信** 

```shell
$ brew cask install wechat
```
   
### 音乐类

**网易云音乐**  

```shell 
$ brew cask install neteasemusic
```

**QQ音乐**

```shell 
$ brew cask install qqmusic
```

### 视频类

**IINA(视频播放器)** 

```shell
$ brew cask install iina
```

### 图片类

**pap.er(自动更换壁纸工具)** 

```shell
$ brew cask install paper
```

### 下载类

**motrix(完美替代迅雷的下载器)** 

```shell
$ brew cask install motrix
```

### 解压类

**keka**

```shell
$ brew cask install keka
```

### 开发工具

**iTerm2(终端)**

```shell
$ brew cask install iterm2
```

**terminus(终端)** 

```shell
$ brew cask install terminus
```

**IDEA(Java的idea)**

```shell
$ brew cask install intellij-idea
```

**data-grip(jetbrains的数据库管理工具)**

```shell
$ brew cask install datagrip
```

**Visual Studio Code** 

```shell
$ brew cask install visual-studio-code
```
**Google Chrome** 

```shell
$ brew cask install google-chrome
```

**postman(网络请求工具)** 

```shell
$ brew cask install postman
```

### 其他类

**腾讯柠檬清理** 

```shell
$ brew cask install tencent-lemon
```

**Clipy(剪贴板工具)** 

```shell
$ brew cask install clipy
```

**qlstephen(增强Mac空格预览的能力，可以以文本方式预览一些文件)** 

```shell
$ brew cask install qlstephen
```

**Cakebrew(Homebrew可视化)** 

```shell
$ brew cask install cakebrew
```

**launchrocket(service可视化-系统设置里面)目前已不可用**
 
```shell
$ brew cask install launchrocket
```

## Mac Apple Store

对于那些只提供Mac Apple Store下载的软件，我们如果也需要通过brew进行安装的话，就需要安装mas，具体介绍可以在官网查看。
[mas](https://github.com/mas-cli/mas)

`brew install mas`

## Tips

1. 要经常更新hombrew, 会更新本身包信息以及对应的一些cask信息（可能包、cask的下载地址都会有所变化），这样之后brew的包才能正确，brew cask才能及时更新到最新的版本，同时不会出现校验错误。
2. 关于Java的版本问题，建议使用openJDK。技术永远在更新，然而我们似乎永远在停留。
