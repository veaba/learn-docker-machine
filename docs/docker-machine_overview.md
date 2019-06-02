# Docker Machine 概览

您可以使用Docker Machine：
- 在Mac或Windows上安装并运行Docker
- 配置和管理多个远程Docker主机
- 供应群集群

## 什么是Docker Machine？
Docker Machine是一个工具，它允许您在虚拟主机上安装Docker Engine，并使用Docker Machine命令管理主机。您可以使用机器在本地Mac或Windows设备、公司网络、数据中心或云提供商（如Azure、AWS或Digital Ocean）上创建Docker主机。

使用`docker-machine`命令，可以启动、检查、停止和重新启动托管主机，升级docker客户机和守护进程，并配置docker客户机与主机对话。

将Machine CLI指向正在运行的托管主机，您可以直接在该主机上运行`docker`命令。例如，运行`docker-machine env default`指向名为`default`的主机，按照屏幕上的说明完成`env`设置，运行`docker ps`，`docker run hello world`等等。

在Docker v1.12之前，机器是在Mac或Windows上运行Docker的唯一方法。从测试版程序和Docker v1.12开始，Mac版的Docker桌面和Windows版的Docker桌面都可以作为本机应用程序提供，在较新的台式机和笔记本电脑上，这是更好的选择。我们鼓励您试用这些新应用程序。Docker Desktop for Mac和Docker Desktop for Windows的安装程序包括Docker Machine，以及Docker Compose。


## 为什么要用它？

## Docker Engine 和Docker Machine 有什么区别？

## 下一步