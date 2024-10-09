# 0x01 🌟 前言
WX信息提取工具 本人原创 禁止反编译改代码发出去圈钱！！！  
呕心沥血 国庆研究了好几天 才兼容全版本 尊重原创！！！

## 0x02 🔍 读取PID
使用以下命令找到wx客户端的 PID：

```bash
tasklist | find /I "WeChat.exe"
```
![image](https://github.com/user-attachments/assets/39e96dfb-9c31-4ea9-b768-9b9952828a54)


接着使用 `procdump64.exe` 通过 CMD 输入以下命令：

```bash
procdump64.exe -accepteula -ma 你的PID
```

这样你将得到一个类似 `xxxxx.exe_241009_163416.dmp` 的文件。

## 0x05 💻 软件提取
直接打开软件选择 .dmp 文件即可获取。


![image](https://github.com/user-attachments/assets/1766a055-63f7-40db-b096-7dd96ab1ecf8)
