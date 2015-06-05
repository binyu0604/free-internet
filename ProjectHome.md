本软件包为 7zip 自解压压缩包(仅简单打包Opera浏览器和wallproxy-plugins)。支持 Windows 各平台。

**ipv6版本仅供支持ipv6的教育网用户使用。请使用前尝试访问 http://ipv6.google.com 以确保对ipv6的正确支持。**

常见问题：
1.若安装了360系列软件，运行安装包前需要退出360。
2.为确保Opera设置文件正常工作，默认安装到 d:\freeinternetproject\ 且不可更改，务必确保D盘存在100MB以上可用空间
3.安装完毕请先测试 facebook.com 能否打开。若不能，a,打开任务管理器，查看是否存在 proxy.exe 进程，若不存在，运行 D:\FreeInternetProject\Opera\profile\Proxy\service\install.bat ，b,若存在，打开Opera浏览器按F12，确保“使用代理服务器”已被勾上

**安装新版本前务必卸载原有版本，卸载方法：**
在桌面右下角找到wallproxy图标右键退出，运行 uninstall.bat （**Win7/vista 下右键管理员权限**）以删除代理服务，删除 d:\freeinternetproject\ 文件夹。


**opera 版本不能移动解压后的文件夹，否则会出现错误。（Opera 配置文件不支持相对路径）**

**国内网络银行均不支持非 IE 浏览器**

~~hosts 文件将解压到 c:\Windows\system32\drivers\etc\ （c:代表当前 Windows 系统所在磁盘分区号 ）~~

软件包内各程序按原样提供，均来自于网络。~~包括 hosts 文件~~，代理程序(wallproxy-plugins)，浏览器三个部分。

鉴于国内网络环境复杂，不保证 hosts 和代理(wallproxy-plugins使用内置的公共服务端)可用性。若出现失效，~~请手动删除 c:\Windows\system32\drivers\etc\ 下的 hosts 文件~~，运行 uninstall.bat （Win7/vista 下右键管理员权限）删除代理服务，并在相应浏览器选项设置中关闭代理服务器。


**代理服务器的失效不会影响浏览器对普通网站提供远胜于 IE 的浏览体验。**

什么是 hosts？
http://zh.wikipedia.org/wiki/Hosts
http://baike.baidu.com/view/493742.html

什么是代理服务器？
http://baike.baidu.com/view/751.htm

这些浏览器有什么区别？
http://zh.wikipedia.org/wiki/浏览器



需要自己定制GAE代理：
https://code.google.com/p/goagent/
https://code.google.com/p/wallproxy-plugins/