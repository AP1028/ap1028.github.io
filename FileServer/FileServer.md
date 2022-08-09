# 公共文件中转服务器/投递服务器

由于我被各种服务限制(比如微信最大传输文件大小为1G，QQ文件大小超限)等事情影响，导致我无法向我的朋友发送[极其优秀且富有教育意义的航天模拟游戏](https://ap1028.github.io/ProjectNebula#ksp)，于是我决定在我已持续运行近一个月的服务器中添置更多功能来解决类似的问题。

于是，我搭建一个<u>云文件投递服务器</u>。我可以让别人把我需要的文件上传至我的服务器，或是让别人去我的服务器上下载我提供的文件。

本服务器同时使用SMB服务和HTTP服务，以下是对于使用的详细说明。

[2022/08/09]	**请不要使文件夹中的留存文件大小之和超过200G，**不然可能会导致服务器崩溃。

## 1. SMB服务的使用

为了安全，本服务需要用户名和密码。

**地址：**```homeserver040322.ddns.net```

***用户名和密码按需分配***

### 1. Windows

<u>理论上</u>，这个功能“开箱即用”。

1. 打开文件资源管理器，点击最上方地址栏，输入```\\homeserver040322.ddns.net```

![Input](C:\Users\tianyixia\Documents\GitHub\ap1028.github.io\FileServer\Input.png)

2. 双击```[指定文件夹名]```，输入用户名和密码

![Display](C:\Users\tianyixia\Documents\GitHub\ap1028.github.io\FileServer\Display.png)

3. 此后，你已经成功进入共享文件夹，可以 Drag & Drop 或是用快捷键。

4. 如果你需要更加方便地使用它，可以退回```\\homeserver040322.ddns.net```，右击```[指定文件夹名]```，选择```显示更多选项```*[仅有Win11才需要]*-->```映射网络驱动器```

![WebDrive](C:\Users\tianyixia\Documents\GitHub\ap1028.github.io\FileServer\WebDrive.png)

### 2. iPadOS / iOS

1. 打开```文件```

![ipad](C:\Users\tianyixia\Documents\GitHub\ap1028.github.io\FileServer\ipad.png)

2. 点击```...```，然后点```连接服务器```

![select](C:\Users\tianyixia\Documents\GitHub\ap1028.github.io\FileServer\select.png)

3. 跟随指示，输入用户名和密码

![ipadpasswd](C:\Users\tianyixia\Documents\GitHub\ap1028.github.io\FileServer\ipadpasswd.png)

4. 公共文件夹会出现在```已共享```，可以由此快速访问

![ipadfinal](C:\Users\tianyixia\Documents\GitHub\ap1028.github.io\FileServer\ipadfinal.png)

### 3. 安卓

安卓需要第三方软件，但是目前为止，所有测试都不成功:(

请等待后续消息。

## 2. HTTP服务的使用

这个服务只用于下载，暂时无法实现上传功能。 (我不会[doge])

1. 在任何浏览器中输入地址 ```homeserver040322.ddns.net:[指定端口号]```，你会看见一些文件和目录。(HTTP服务和SMB服务使用同一目录)
2. 点击文件，即可下载文件。