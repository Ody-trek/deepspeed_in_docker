# deepspeed_in_docker








PS:
能够成功使用ping命令到达一个IP地址，但无法通过SSH连接，通常是因为目标机器或容器没有运行SSH服务（sshd）

-->确认SSH服务运行状态：确保你尝试连接的机器上的SSH服务（sshd）正在运行。你可以通过运行service ssh status（对于基于systemd的系统）或者/etc/init.d/ssh status（对于老旧系统）来检查。

-->重启SSH服务：尝试重启SSH服务以应用任何更改，使用service ssh restart或者/etc/init.d/ssh restart。



