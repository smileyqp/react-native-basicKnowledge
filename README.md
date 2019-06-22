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

![image-20190622145753668](/Users/yqp/Library/Application Support/typora-user-images/image-20190622145753668.png)

![image-20190622145814087](/Users/yqp/Library/Application Support/typora-user-images/image-20190622145814087.png)

> 移动端着合格做背景颜色很好看`#F5FCFF`

##### Flexbox布局

> Flexbox弹性盒子模型
>
> - 浮动布局
> - 各种机型屏幕的适配
> - 水平和垂直居中
> - 自动分配宽度

> css中常规布局是基于块和内联流

![image-20190622152326038](/Users/yqp/Library/Application Support/typora-user-images/image-20190622152326038.png)

![image-20190622152822472](/Users/yqp/Library/Application Support/typora-user-images/image-20190622152822472.png)

![image-20190622153141480](/Users/yqp/Library/Application Support/typora-user-images/image-20190622153141480.png)

![image-20190622153416436](/Users/yqp/Library/Application Support/typora-user-images/image-20190622153416436.png)

![image-20190622153446934](/Users/yqp/Library/Application Support/typora-user-images/image-20190622153446934.png)

![image-20190622153756380](/Users/yqp/Library/Application Support/typora-user-images/image-20190622153756380.png)

![image-20190622153908965](/Users/yqp/Library/Application Support/typora-user-images/image-20190622153908965.png)

![image-20190622154051839](/Users/yqp/Library/Application Support/typora-user-images/image-20190622154051839.png)

![image-20190622154254363](/Users/yqp/Library/Application Support/typora-user-images/image-20190622154254363.png)

![image-20190622154438665](/Users/yqp/Library/Application Support/typora-user-images/image-20190622154438665.png)

!image-20190622154358061](/Users/yqp/Library/Application Support/typora-user-images/image-20190622154358061.png)

![image-20190622154420618](/Users/yqp/Library/Application Support/typora-user-images/image-20190622154420618.png)

> 获取当前屏幕的宽度高度以及分辨率

```shell
var Dimensions = require('Dimensions');
export default class App extends Component {
  render() {
    return (
      <View style={styles.container}>
        <Text style={styles.welcome}>当前窗口的宽度：{Dimensions.get('window').width}</Text>
        <Text style={styles.instructions}>当前窗口的高度：{Dimensions.get('window').height}</Text>
        <Text style={styles.instructions}>当前窗口的分辨率：{Dimensions.get('window').scale}</Text>
      </View>
    );
  }
}
```

![image-20190622161836311](/Users/yqp/Library/Application Support/typora-user-images/image-20190622161836311.png)

![image-20190622162157491](/Users/yqp/Library/Application Support/typora-user-images/image-20190622162157491.png)

![image-20190622162351136](/Users/yqp/Library/Application Support/typora-user-images/image-20190622162351136.png)

![image-20190622173141637](/Users/yqp/Library/Application Support/typora-user-images/image-20190622173141637.png)

![image-20190622173227692](/Users/yqp/Library/Application Support/typora-user-images/image-20190622173227692.png)

![image-20190622173325037](/Users/yqp/Library/Application Support/typora-user-images/image-20190622173325037.png)

![image-20190622173411728](/Users/yqp/Library/Application Support/typora-user-images/image-20190622173411728.png)

![image-20190622173449919](/Users/yqp/Library/Application Support/typora-user-images/image-20190622173449919.png)

 