注意:
1.运行程序前,请先修改test_main.py文件中的设备IP、端口、用户名、密码，并修改HCNetSDK库文件的绝对路径。
  对应的变量名为：DEV_IP、DEV_PORT、DEV_USER_NAME、DEV_PASSWORD、HCNETSDK_DLL_PATH。
2.请将所有文件拷贝至HCNetSDK库文件所在的路径下运行。
3.在Linux环境下，请用sudo命令执行，需管理员权限来创建日志路径。
4.HCNetSDK库必须与运行PC的位数保持一致，如：PC为64位操作系统需HCNetSDK 64位版本。
5.增加了播放库码流解析功能,码流解析回调函数在playctrl.py文件DisplayCBFun。

Python版本：2.7.3
在Python代码当前路径运行cmd或terminal，执行命令：python test_main.py
