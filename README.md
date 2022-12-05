# flutter_demo
### 在线文档（中文可能存在版本差异，以英文为准）
```
中文  https://dart.cn
英文  https://docs.flutter.dev
```
### 相关资料
- https://www.jianshu.com/p/36fe7c450442
- https://api.flutter-io.cn/
- https://api.flutter-io.cn/flutter/widgets/widgets-library.html#classes
- https://bruno.ke.com/page/

### 目录结构说明
|      文件/目录      | 说明                                      |
|-----------------|:----------------------------------------|
|   .dart_tool    | 记录了一些dart工具库所在的位置和信息(不要提交)              |
|     android     | 包含Android特定文件的Android子工程(android平台相关代码) |
|       ios       | 包含ios特定文件的ios子工程（ios平台相关代码）             |
|       lib       | flutter应用源文件目录，我们自己写的Dart文件都放进此文件夹中     |
|      test       | 用于存放测试代码                                |
|   .gitignore    | git忽略配置文件                               |
|  pubspec.lock   | 当前项目依赖所生成的文件                            |
|  pubspec.yaml   | 当前项目的一些配置文件，包括依赖的第三方库、图片资源文件等           |
|    README.md    | READEME文件                               |
```
lib
├── common  一些工具类，如通用方法类、网络接口类、保存全局变量的静态类等
├── models  Json文件对应的Dart Model类会在此目录下
├── states  保存APP中需要跨组件共享的状态类
├── routes  存放所有路由页面类
└── widgets APP内封装的一些Widgets组件都在该目录下
```