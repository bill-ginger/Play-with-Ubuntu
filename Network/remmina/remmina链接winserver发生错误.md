# remmina链接winserver发生错误

当我使用remmina用rdp连接Windows Server主机的时候，报出了以下错误

![rdp-problem](remmina-rdp.png)

是说H264解码器无法解码对应颜色深度。

解决方法是在终端里键入```remmina -n```或者点击顶栏的remmina图标选择新的连接，然后色深选择增强色(16位)，连接即可

[这里](https://unix.stackexchange.com/questions/440803/remmina-cant-remote-into-windows-server)是关于这个问题的详细讨论
