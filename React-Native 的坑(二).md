 ## 下载项目
```
    cd Desktop
    git clone https://github.com/CatalystCode/NutritionDoctor

    cd NutritionDoctor
    // 如果已经有 node_modules 文件夹，就不要下面的操作了
    npm install
```
## 运行报错 React/RCTBundleURLProvider.h file not found
到目录下面的 package.json 文件， 作以下改动
```
    "react": "16.0.0-alpha.6",
    "react-native": "0.44.3",
```

## 编译通过，运行出错 Undefined is not an object (evaluating CameraManager.Aspect) 
```
    react-native link
```

## 运行，先把模拟器关掉(不关没试)
```
    // 或者直接到工程目录下iOS文件夹，用xcode打开
    react-native run-ios
```