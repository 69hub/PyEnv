# PyEnv
Python 虚拟环境

这里创建虚拟环境，只要是方便安装不同的packages。
env 中的 pyvenv.cfg 文件
	1. 可以配置本地 Python安装路径
	2. 可以设置是否使用本地中的packages
Lib\site-packages\.pth 文件可以添加本地包的位置
	一行一个路径


启动与关闭
CMD 运行 activate 脚本可以启动
	启动后效果设置只对本窗口有效，因为用的是set环境变量
	启动后可以直接使用pip安装packages
	
在打开的窗口中运行 deactivate.bat 可以关闭该 env

注意：如果使用VSCode, 直接配置 \Scripts 目录就好，VSCode可以加载 Activate.ps1 脚本完成相应的配置。
	  电脑一般默认不可以运行 .ps1 脚本，可能需要配置。

