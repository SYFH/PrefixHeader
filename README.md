## PrefixHeader
最常用的宏定义

## 添加方法
点击项目 -> `Build Setting` -> 双击 `Prefix Header` -> 填写 `$(SRCROOT)/$(PROJECT_NAME)/PrefixHeader.pch`  
编译项目

## 相关的宏
1. 屏幕 & 尺寸   - 获取与判断
2. 系统版本      - 获取与判断
3. 系统时间      - 年月日, 时分秒, 毫秒微秒纳秒等
4. 测试日志打印
5. 颜色相关      - 系统默认, 自定义颜色
6. UI操作        - frame的x, y, width, height
7. 线程操作      - 安全的子线程与主线程操作
8. 一般路径 & 目录
9. 解决循环引用  - weak-strong dance
10. 其他...

## 注意事项
如果需要自己添加其他`.h`文件, 可以考虑创建一个`Macro.h`文件, 将需要的`.h`文件添加进去, 然后将汇总`Macro.h`文件添加进`PCH`文件中
