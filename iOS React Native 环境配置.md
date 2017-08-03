## 1.安装Homebrew

```
ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)
```


## 2.安装Node.js

```
brew install node
```

## 3.设置npm镜像

```
npm config set registry https://registry.npm.taobao.org --global
npm config set disturl https://npm.taobao.org/dist --global
```

## 4.安装React Native的命令行工具

```
npm install -g react-native-cli
```

## 5.安装Watchman

```
brew install watchman
```

## 6.安装Flow 

```
brew install flow
```

## 7.创建ReactNative 应用
```
react-native init  项目名称 --version 0.44.3
```
## 8.运行项目

命令行
```
cd projectPath(工程目录)
react-native run-ios
```
xcode 打开
进入项目目录，打开iOS文件夹 使用xcode打开 .xcodeproj 文件



