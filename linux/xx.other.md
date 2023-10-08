



## 云计算

SaaS、PaaS 和 IaaS 是云计算中三种不同的服务模式，它们之间有以下的区别：

SaaS：SaaS （Software as a Service）是一种基于云计算的软件服务模式，提供的是软件应用程序，应用程序运行在供应商的云平台上。最常见的 SaaS 是 Web 应用程序，用户不需要在本地进行安装，只需要通过互联网访问服务提供商的应用程序即可，其服务模式以订阅付费为主。

PaaS：PaaS（Platform as a Service）是一种面向开发者的云服务模式，提供的是开发环境和开发平台，让开发者能够构建和部署自己的应用程序。PaaS 通常是基于 SaaS 提供商运行的，它们提供了开发者所需要的硬件、操作系统和数据库等基础设施，使得开发者只需关注业务逻辑的开发即可。

IaaS：IaaS（Infrastructure as a Service）是云服务中最底层的一种，提供的是虚拟化的计算、存储和网络资源等基础设施。通过 IaaS，用户可以获得一个灵活的、可扩展的计算平台，可以配置和管理其上运行的操作系统、应用程序和数据库等。IaaS 提供商通常会提供虚拟机、云存储等服务。

总的来说， SaaS、PaaS 和 IaaS 通过不同的角度向用户提供了不同层次的服务和能力，用户可以选择适合自己的服务模式，综合考虑服务的成本、灵活性、掌控性等因素进行选择和使用。





### MobaXterm

```
https://blog.csdn.net/weixin_44205779/article/details/123685547  # 登录SSH服务器

```

#### （2） 防止自动断开
默认情况下，MobaXterm 在一段时间内没有活动时（默认为 15 分钟）会自动断开 SSH 会话以保护您的安全。在 MobaXterm 编辑器中工作时，这可能会导致您的连接断开，并且您需要重新登录并重新开始您的工作。

您可以通过以下方式更改此设置：

打开 MobaXterm，并进入首选项菜单 Settings。

展开 SSH 菜单，并选择 Advanced SSH settings。

然后，找到 SSH keepalive 选项，并调整您需要的秒数。 SSH keepalive 确保您的 SSH 会话保持活动状态，也可以防止 SSH 会话因为没有交互而断开。

设置 “Seconds between keepalive transmissions” 值，通常可以在 60 秒到数百秒之间。 防止不活动断开的最佳设置取决于您的环境和个人偏好。

在更改后，单击 OK 按钮以保存更改。
此更改会延长 MobaXterm 会话断开的时间，允许您更长时间使用 SSH 会话。 请注意，更长时间的 SSH 会话也意味着安全性降低。确保只使用安全的网络和设置更长时间的 SSH 会话安全风险适度。





# Mac 命令
## 快捷键
Command+Option+Esc   强制退出程序
Command+c    		         复制
Command+v     		         粘贴
Command+Option+v            剪切

2.Mac下打开/usr/local目录
Mac下/usr/local目录默认是对于Finder是隐藏，如果需要到/usr/local下去，打开Finder，然后使用command+shift+G，在弹出的目录中填写/usr/local就可以了



# Window 
## 快捷键：
Win + L   % 锁屏


## 安装：

https://blog.csdn.net/qq_30091945/article/details/81154014  # 安装 ffmpeg


2.Word中插入gif
https://jingyan.baidu.com/article/8cdccae942bb23315413cdc2.html




4.翻墙后GlobalProtec(VPN)连不上（可以正常上网）

解决方法：
打开IE浏览器，设置 ——》internet选项 ——》连接——》局域网设置——》代理服务器。管理代理服务器。



youtube视频下载： https://github.com/kejimao/4k-video-downloader



### postman

https://blog.csdn.net/yy_demo/article/details/130603412



软件
（1）xmind绿色版：

https://ghpym.lanzous.com/iRqzhjjtx6b



### VScode
Ctrl + Shift + P     # 调出主命令框，输入 Markdown，应该会匹配到几项 Markdown相关命令。
Ctrl - K  +  v       # 调出实时预览框。



#### VScode 链接服务器


**vscode提示无法保存修改的文件**

```bash
# ==== 提示 ：
未能保存“sd_models.py”: 无法写入文件"vscode-remote://ssh-remote+192.168.250.33/home/sd_models.py"(NoPermissions (FileSystemError): Error: EACCES: permission denied, open '/home/sd_models.py')
```

```bash
# ==== 解决方案 ：
sudo chown -R   dbt   stable-diffusion-api_install2_timezone0
```






C++ 知识点： https://blog.csdn.net/xu_fu_yong/article/details/122948379?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522167991747216800180692925%2522%252C%2522scm%2522%253A%252220140713.130102334..%2522%257D&request_id=167991747216800180692925&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~baidu_landing_v2~default-1-122948379-null-null.142^v76^pc_new_rank,201^v4^add_ask,239^v2^insert_chatgpt&utm_term=c%2B%2B%E5%B8%B8%E8%A7%81%E9%9D%A2%E8%AF%95%E9%A2%98%E6%80%BB%E7%BB%93&spm=1018.2226.3001.4187





