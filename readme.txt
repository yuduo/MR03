
1.<<MTools.exe>> 驱动器配置软件

2.<<MTools运行依赖包1.exe>> 、<<MTools运行依赖包2.exe>>，驱动器配置软件运行依赖包。

3.<<固件VX_X.bin>> 驱动器固件，X_X表示固件版本号

4.<<Flash loader Demo>>是windows平台固件更新程序

5.对于ROS用户，<<ros驱动包>>是驱动器的ros驱动节点，在ros系统中运行这个包可以获取驱动器上传数据同时控制电机运动。

6.对于ROS用户，<<串口udev规则>>里面文件用于将驱动器附带的串口设备映射成ros驱动里面的ttyUSB001，请根据实际情况将用户名xiaoqiang改成实际系统用户名，然后把文件拷贝到/dev/udev/rules.d/里面，注意在linux系统中需要将用户增加到Dailout用户组才能获取串口使用权限。