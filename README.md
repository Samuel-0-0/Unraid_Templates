# Unraid_Templates
Templates for Unraid

## ioBroker 说明
需要自己修改网络及其他相关配置。

iobroker文件夹中：

custom_packages.list所列用于自动安装包，

sources.list为Debian阿里源，

pre_script用于修改npm源为淘宝源，

post_script用于修改Debian阿里源以及安装convert，

如果需要，将文件复制到容器对应的iobroker文件夹中，然后`重新安装`一次容器。

