## PrefixHeader
最常用的宏定义

## 添加方法
点击项目 -> `Build Setting` -> 双击 `Prefix Header` -> 填写 `$(SRCROOT)/$(PROJECT_NAME)/PrefixHeader.pch`
编译项目

## 注意事项
如果需要自己添加其他`.h`文件, 可以考虑创建一个`Macro.h`文件, 将需要的`.h`文件添加进去, 然后将汇总`.h`文件添加进PCH文件中
