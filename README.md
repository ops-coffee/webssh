# webssh

## 说明

这个仓库里没有代码，不过你可以通过下边的文章来自己实现

## 主页

[https://blog.ops-coffee.cn/webssh](https://blog.ops-coffee.cn/webssh)

## 视频

[![WebSSH](images/10.png)](https://youtu.be/clMiPO5G_HM)

## 文章

- [Django实现WebSSH操作Kubernetes Pod](https://blog.ops-coffee.cn/webssh/jumpserver-kubernetes-web-terminal-ssh-stream)
- [Kubernetes WebSSH终端窗口自适应Resize](https://blog.ops-coffee.cn/webssh/jumpserver-web-terminal-kubernetes-ssh-resize)
- [Django实现WebSSH操作物理机或虚拟机](https://blog.ops-coffee.cn/webssh/jumpserver-web-terminal-ssh-paramiko-stream)
- [堡垒机的核心武器：WebSSH录像实现](https://blog.ops-coffee.cn/webssh/jumpserver-web-terminal-monitor-asciinema-audit)
- [堡垒机WebSSH进阶之实时监控和强制下线](https://blog.ops-coffee.cn/webssh/jumpserver-web-terminal-monitor-and-disconnect)
- [WebSSH画龙点睛之lrzsz上传下载文件](https://blog.ops-coffee.cn/webssh/jumpserver-web-terminal-lrzsz-file-scp-zmodem)

## 功能

1. 交互式命令执行，支持 vim\top 之类的指令
2. 所有的操作都会被录像，方便审计回放
3. 管理员可以实时监控用户操作，必要的时候给强制踢下线
4. 支持 zmodem 协议，可以使用 lrzsz 命令上传下载文件
5. 窗口自适应，会根据浏览器窗口大小动态调整后端输出终端大小
