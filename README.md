# Daclock-Cloud
Use colock config service online。Power by tencent cloud。
## 1 该版本从腾讯云服务器拉取配置，实现实时天气、三天天气、节日得读取。
## 2 该版本移除静态天气图标数组，采用SPIFFS方式存储，节省代码空间，方便后续维护更多功能。
## 3 增加两种时钟样式：1、可读取1~9.bmp文件字体，通过本地配置页面上传bmp即可。增加纯文字模式和模拟时钟模式。
## 4 优化断网重连机制，测试中。
## 5 降低光敏的敏感度，避免闪烁。
## 6 对常规时间显示增加秒的进度显示。
## 7 为确保API的安全，只提供bin文件，不提供源码。可直接用flash_download_tool下载到ESP32中使用。
