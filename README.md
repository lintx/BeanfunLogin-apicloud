# BeanfunLogin

# 不要安装其他人发给你的apk等防止用心不良者盗号！！！

## 这是什么？
这是一个依托于`apicloud`平台开发的新枫之谷港区登录密码获取APP，支持iOS和安卓  

## 这能做什么？有什么用？
正确安装后，可以在手机中登录beanfun帐号，然后查看登录新枫之谷港区所需要的游戏帐号及一次性游戏密码。  
用处有：
- 帐号给朋友/代练上号，自己不在电脑前，又不想直接给beanfun帐号
- 害怕电脑上有病毒，不敢在电脑上登录beanfun帐号
- 其他

## 我是简体电脑，还不是要用beanfun登录器，不然怎么进游戏？
除了beanfun登录器，还有其他工具可以支持简体环境运行游戏，比如beanfun及市面上类似软件支持简体环境运行游戏其实都是使用的[Locale_Remulator](https://github.com/InWILL/Locale_Remulator)软件。或者你也可以使用我的另外一款软件[MapleStoryWebStart](https://github.com/lintx/MapleStoryWebStart)，该软件可以用于简体环境网页启动，在直接运行软件的时候可以作为单纯的游戏启动器使用。  

## 怎么安装？
这个东西安装起来还是需要一些耐心的。  
- 首先，我们需要在[apicloud官网](https://www.apicloud.com/studio3)注册帐号、下载开发工具并安装。  
- 然后，我们需要在手机上安装apicloud的官方apploader，打开[下载地址](https://docs.apicloud.com/Download/download)，打开后在中间部分选择`apploader`，然后在右下扫码安装。
    > iOS手机在安装后需要先打开一次，提示“未受信任的企业级开发者”之后到设置-通用-VPN与设备管理中找到“Kunming Union-Science...”，点开后下方显示“apploader”字样的话，点击“信任...”才能打开
- 然后你需要下载这个的源代码，下载方法是往上拉，找到绿色的`Code`按钮，点击后在打开界面选择`Download ZIP`即可下载源代码的zip压缩包，下载后记得解压
- 打开之前安装的apicloud开发工具，在apicloud开发工具左上角选择“打开文件夹”并定位到解压后的源码即可打开，此过程中可能需要创建app之类，按照提示操作
- 参考[apicloud官方文档](https://docs.apicloud.com/Dev-Tools/studio3-wifi-debug)将手机端的apploader连接到电脑上的开发工具，然后根据文档说明“全量”同步到手机端，如果手机端出现了beanfunlogin页面并有帐号密码输入框和登录按钮即表明安装成功
> 安装成功后理论上可以长时间使用，安卓手机用户可以自行参考文档编译成apk安装到手机，iOS端如果没有AppStore开发者帐号目前只有通过apploader运行一种方式。