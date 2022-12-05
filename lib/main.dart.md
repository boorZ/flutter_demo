```aidl
import 'package:flutter/material.dart';

/*
* 这里相当于Android中的Application类
* StatelessWidget表示无状态控件
* */

class MyApp extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
/*
* MaterialApp表明app的风格是Material Design风格的
* 这里我们可以配置app的主题相关属性比如颜色，按钮风格等等，类似于Android中的style文件
* */
    return MaterialApp(
      title: 'Flutter Demo',
/*主题相关配置
* 这里我们可以配合app整体的主题样式，比如整体颜色，控件默认的样式等
* */
      theme: ThemeData(
/*这个地方就类似于Android中的style文件配置，主要就是主题的配置*/
        primarySwatch: Colors.blue,
        visualDensity: VisualDensity.adaptivePlatformDensity,
      ),
/*home指定了启动后显示的页面
* 类似于我们在AndroidManifest中配置启动页面
* */
      home: MyHomePage(title: 'Flutter Demo Home Page'),
    );
  }
}

```