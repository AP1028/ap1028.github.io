# Minecraft服务器

我尝试通过~~向电信客服大吼大叫~~ 友好的让电信客服把我们家的地址改成公网IP并把路由器改成桥接模式，从而实现端口映射和家用服务器的搭建。

然后，我就在我父亲的64G RAM，24核双路Xeon E3处理器，运行着 CentOS 7 的工作站上用KVM装了一个32G RAM，12核的Ubuntu虚拟机来跑服务器进程。

由于硬件性能充裕，我直接上了4个服务器进程。

我们可以在MC中建设完JZMF，甚至在MC中开毕业典礼，或是“线上返校”。

如果遇上任何问题(比如连接不上)，可以直接微信里ping我，或是把问题发往我的邮箱。(tian_yi_xia@qq.com)

## 1. 地址信息

### 1. JAVA版(v1.18.2)

1. **无政府公共生存服务器**(我懒得管且对服务器管理不太熟悉)

   地址：<u>**homeserver040322.ddns.net**</u>
   
2. **JZMF建设服务器**(一座JZMF坐落于超平坦大陆上)

   地址：<u>**homeserver040322.ddns.net:25566**</u>
   
3. **"JZMF-wild"**(与JZMF建设服务器一样拥有学校的结构，但是被用[Amulet](https://github.com/Amulet-Team/Amulet-Map-Editor)整体结构编辑放入了普通世界中)

   地址：<u>**homeserver040322.ddns.net:25567**</u>

### 2. 基岩版(v1.19.2)

1. **基岩版JZMF服务器**(同JAVA版的JZMF建设服务器)

   地址：<u>**homeserver040322.ddns.net**</u>

   端口号：<u>**19132**</u>

## 2. 国际版客户端安装教程

如果你不了解MC，不会安装国际版第三方客户端，可以参照以下教程。

我并不清楚网易版能否联机，因为我从来不用网易版。不过，我盲猜网易根本没有更新到 Java 1.18 和 Bedrock 1.19.

### 1. JAVA版(Windows/Mac/Linux)

#### 1. 客户端部署

对于Windows/Mac/Linux，请直接官网下载

[官网下载页面](https://hmcl.huangyuhui.net/download/)

[本站github.io下载](./HMCL-3.5.3.exe)

当你下载完后，把HMCL放入你想要存储它的文件夹，比如```D:\HMCL```

运行HMCL-X.X.X.exe，并完成游戏下载安装。(见下文)

所有的游戏文件都会放置在exe同目录下，比如在刚才那种情况，HMCL会生成```D:\HMCL\.minecraft```文件夹



对于安卓，有一个叫做HMCL-PE的东西，可以部分实现HMCL的功能，但仍然在开发早期阶段，有较大局限。

[GitHub下载页面](https://github.com/Tungstend/HMCL-PE/releases/tag/22.6.18-update)



#### 2. 使用HMCL下载并运行 Minecraft v1.18.2

打开HMCL

![startHMCL](C:\Users\Admin\Desktop\MinecraftServer\startHMCL.png)

点下载，然后下载1.18.2

如果你电脑性能不佳，可以考虑点入Optifine装最新版本的Optifine提高帧数

如果你对电脑性能有自信，想要装光影，也需要安装Optifine

其余全部均不安装

![install](C:\Users\Admin\Desktop\MinecraftServer\install.png)

然后点安装，等待下载完成

待安装完后，回到主页，点左上角"没有游戏账户"，选离线模式，然后输入任意用户名。

这个用户名会显示在游戏中，为了方便服务器管理，请输入姓名首字母+学号，如xty37

![login](C:\Users\Admin\Desktop\MinecraftServer\login.png)

登录后点左下角启动游戏，你就完成了。

待启动完毕，点多人游戏



### 2. 基岩版(Android)

直接点击[链接](http://dl7.692657.com/down/minecraft_v1.19.2.02_mod.apk)下载

安装完后，点击上方server，然后点击最下方按钮```Add Server```

输入相应的地址和端口号

![beserver](C:\Users\Admin\Desktop\MinecraftServer\beserver.jpg)

然后当你准备加入服务器前，它会强迫你登录微软账号

请遵守它的指示登录/注册账号，然后加入服务器











