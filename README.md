Xtest 介绍
--------------------
Xtest 是一款专为移动端打造的自动化测试工具，用户可以方便的使用Xtest进行脚本的录制和回放。
同时，xtest工具录制的脚本可以在utest官网上千款设备上进行回放。

联系我们 
------------------
QQ交流群： 277740123

商务合作QQ：800016094

官网地址：[http://utest.qq.com/](http://utest.qq.com/)


常见问题解答
------------------------------
### 1.启动失败：JDK配置原因

Xtestserver 启动后出现如下错误之一，表明jdk的环境配置有问题，请检测javac -version检测一下(不是 java -version)，
正常的jdk的path应该是：%java_home%/bin(先配置好java_home的路径)
![image](https://github.com/TencentXtest/Xtest/raw/master/images/%E5%9B%BE%E7%89%871.png)
![image](https://github.com/TencentXtest/Xtest/raw/master/images/%E5%9B%BE%E7%89%872.png)
![image](https://github.com/TencentXtest/Xtest/raw/master/images/%E5%9B%BE%E7%89%873.png)
### 2.无法找到已连接设备：ADB端口被抢占

无法检测到设备，可能是其他软件抢占adb导致，请关闭手机助手类软件再次尝试。
![image](https://github.com/TencentXtest/Xtest/raw/master/images/%E5%9B%BE%E7%89%874.png)

### 3.启动正常，上传APK失败
请检查xtestserver的安装目录xserver_public\xserver_public\temp\下是否有“5x-....apk”生成，如果有，
则是网络原因导致上传云端失败。如果没有，有可能是jdk配置出现了问题，请重新配置jdk环境变量。然后重启xtestserver.bat服务再试
![image](https://github.com/TencentXtest/Xtest/raw/master/images/%E5%9B%BE%E7%89%875.png)

### 4.获取MAC地址失败
启动后出现如下错误日志，请检测环境变量path里面是否将getmac的路径配置进去（默认安装完windows系统后会自动配置%SystemRoot%\system32），
如果没有，请加入进去，具体位置win7为：C:\Windows\System32。重启服务即可解决。

![image](https://github.com/TencentXtest/Xtest/raw/master/images/%E5%9B%BE%E7%89%876.png)
![image](https://github.com/TencentXtest/Xtest/raw/master/images/%E5%9B%BE%E7%89%877.png)

其他
-----------------
如果您还有其他问题，请加入联系我们的qq，技术问题也可以直接在github上建立issues
https://github.com/TencentXtest/Xtest/issues













