> 安装Homebrew软件包管理工具：

`ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`

> 安装npm和node.js

> 安装watchman（非必须）：用于监控bug文件和文件变化；并且可以触发指定的操作

`brew install watchman`

> 安装flow（非必须）:flow是JavaScript的静态文件检查器，方便找出代码只能够存在的类

`brew install flow`

> 安装react-native

`npm install -g yarn react-native-cli`

> 初始化react-native项目

`react-native init smileyqpReactnative`

##### 关于Android版本

> 安装android-sdk

`brew cask install android-sdk`或者 `brew install android-sdk`

> 配置.bash_profile（mac中）

`cd ~`

`vim ~/.bash_profile`添加`android-sdk`的路径`export ANDROID_HOME=/usr/local/share/android-sdk`

`source`该文件`source ~/.bash_profile`

可以`echo $ANDROID_HOME`查看是否配置好

> 安装genymotion，android第三方模拟器

 [https://www.genymotion.com/fun-zone/](https://link.jianshu.com/?t=https%3A%2F%2Fwww.genymotion.com%2Ffun-zone%2F)

<https://www.genymotion.com/download/>

> ios上刷新cmd+R

> React_native版本管理

`react-native —version`

`npm update -g react-native-cli `

> 查询react-native的npm包的最新版本

`npm info react-native`

> 升级或者降级版本

`npm install --save react-native@版本号`
