# flutter-template

一个Flutter模板工程，用于快速创建Flutter项目。  
预先配置了大部分常用插件，以及常用的一些代码片段。  
后面将会持续更新代码及文章。

本项目基于以下环境创建，如果你的版本不同，可能会出现不兼容情况，请自行解决。

```
# flutter --version
Flutter 3.10.0 • channel stable • https://github.com/flutter/flutter.git
Framework • revision 84a1e904f4 (4 months ago) • 2023-05-09 07:41:44 -0700
Engine • revision d44b5a94c9
Tools • Dart 3.0.0 • DevTools 2.23.1
```

## 快速开始

1. 克隆项目

    ```shell
    git clone "git@github.com:jifengg/flutter-template.git"
    ```
2. 编译并运行项目
   
   ```shell
   cd flutter-template
   flutter pub get
   # 第一次运行，建议加上-v，可以查看详细的编译过程，以及出问题时可以看到详细报错信息。
   flutter run -v
   ```

3. 修改包名及组织名  
   本项目的org=com.woniufun , package=flutter_template。  
   假设你要替换为org=com.example.app , package=my_app_name。  
   请使用你熟悉的IDE打开本项目，按照以下步骤进行全局文本替换：
   - `flutterTemplate` -> `myAppName`，此处驼峰形式为ios和macos系统的PRODUCT_BUNDLE_IDENTIFIER；
   - `flutter_template` -> `my_app_name`，此处修改为包名，建议使用常规包名，不要出现中文等符号；
   - `com.woniufun` -> `com.example.app`；


## Flutter相关资源:

- [Lab: 入门指南](https://flutter.cn/docs/codelabs)
- [Cookbook: 官方实用教程合集，帮助你解决编写 Flutter 应用中的常见问题。](https://flutter.cn/docs/cookbook)

## 文章列表

- 项目初始化
  - [修改图标](docs/init.md#修改图标)