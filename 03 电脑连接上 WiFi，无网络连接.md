## 电脑连接上 WiFi，无网络连接
解决办法：

打开网络和 Internet 设置 > 更改设备器选项 > 除了 WLAN，将其他网络的 IPv4 都设置为自动获取 IP 及 DNS 服务器地址

接下来，查看 IP 地址，运行 ipconfig/all 命令（Windows，如果用的是 linux 系统，则用 ifconfig 或 ip addr)，就可以看到 IPv4 地址，子网掩码，默认网关，DNS 服务器。

默认网关没有，我就自己配置一个。

按照以上操作，能够上网了。
