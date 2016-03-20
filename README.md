# React
learn react

## start native react
### Install Homebrew
[Homebrew]
$ /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

### Install node
$ brew install node
### Install watchman
$ brew install watchman
### Install react-native cli
$ npm install -g react-native-cli

### Create project
$ react-native init [project name]

Note:
To run your app on iOS:
   cd /Users/SimonKu/React/ReactTest
   react-native run-ios
   - or -
   Open /Users/SimonKu/React/ReactTest/ios/ReactTest.xcodeproj in Xcode
   Hit the Run button
To run your app on Android:
   Have an Android emulator running (quickest way to get started), or a device connected
   cd /Users/SimonKu/React/ReactTest
   react-native run-android

   在 iOS 端，现在你可以在 Xcode 里面打开这个新项目 (AwesomeProject/AwesomeProject.xcodeproj)，然后使用 ⌘+R 来简单的构建和运行这个项目。这样做也会开启允许代码实时渲染的 Node 服务器。有了它你可以通过在模拟器里面按住 ⌘+R 来看你的更改，而不用在 Xcode 里面重新编译。

   在 Android 端，在 AwesomeProject 里面运行 react-native run-android 来在你的模拟器设备上面安装生成的应用，并且开启允许代码实时渲染的 Node 服务器。为了看到你的更改你必须打开震动菜单（摇动你的设备或者按住设备上面的菜单按钮，在模拟器上面按住 F2 或者 Page Up，在 Genymotion 上面按住 ⌘+M），然后点击 Reload JS。

   在这篇教程里面我们会开发一个简单版本的电影应用，该应用可以获取电影院里面的 25 部电影，并且将它们显示在 ListView 里面。

### 目前看到的教程
http://wiki.jikexueyuan.com/project/react-native/tutorial.html

[getting start native react]
[getting start native react]:https://facebook.github.io/react-native/docs/getting-started.html#content
[Homebrew]:http://brew.sh/
