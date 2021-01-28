# EpicMoMiraiG
辅助Mirai进行独立启动，并增加辅助功能 / Help Mirai start independly and add more fuction help Mirai or other programs
## 现有的功能
- 更新Mirai最新源（包含MiraiHTTP，MiraiCore，MiraiConsole，MiraiConsole前端）
- 自动安装并启动Mirai，且无需用户自己操作（相当于一个Mirai自动启动器）
- 自动获取Mirai HTTP的相关信息（ServerIP，Port，Key）
- 颜色区分不同命令
- 日志功能
## 预计加入的功能
- 静默启动（为仅需要QQ发送信息的软件使用）
- 可以自定义配置
- 为每个插件设置独立的更新渠道，可以自动更新（EMG会提供一个下载器）
- 为HTTP开发者直接接入
- 图形化管理插件
等等
## EMG命令（emg [verb][noun]）
 输入emg help以获得帮助
- emg start：开启Mirai
- emg clear: 清空屏幕
- emg getServerIP: 获得HTTP的ServerIP
- emg getServerPort: 获得HTTP的Port
- emg getServerKey：获得HTTP的Key



## 使用方法

1. 打开软件，点击“更新源”
2. 点击“更新”（进入需要点击下载）
3. 输入emg start(报错请重启即可)

## 版本更新

Beta 0.2:

- 修复登录错误逻辑
- 加入对HTTP-api的更多支持
- 画了更多的饼
- 加入账户管理

Beta 0.1:

- 构建EMG核心，暂定为EMG-Core