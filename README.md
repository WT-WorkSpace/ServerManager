# ServerManager
这里记载了团队内部的服务器管理规则
#### 系统配置：

|   系统    | Ubuntu 20.04                                        |
| :-------: | :---------------------------|
|    CPU    | i9-13900K                                           |
| 电脑内存  | 128g                                                |
|    GPU    | 2 * Nvidia RTX4090                                  |
|  GPU内存  | 24g*2                                               |
|   CUDA    | cuda-10.2，cuda-11.3，cuda12.0  由管理员安装        |
| Anaconda  | 各用户自行安装                                      |
| pytorch等 | 各用户自行安装(注意：安装**对应cuda**版本的pytorch) |





#### 服务器使用

* [服务器怎么连接？](./doc/服务器连接工具.md)
* [服务器使用规则](./doc/服务器使用规则.md)
* [数据共享](./doc/数据共享.md)
* [普通用户如何使用cuda](./doc/cuda使用.md)
* [模型训练注意事项](./doc/模型训练注意事项.md)
  

#### 管理员必看
* [内网穿透如何搭建？](./doc/阿里云FRP内网穿透详细教程.md)
* [服务器管理员具备的基本命令](./doc/ubuntu管理员常用命令.md)
