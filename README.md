# v免签监控
 
+ 软件名称：智慧66云-某信某支监控系统  
目前软件属于免费使用阶段，我们也不清楚能提供使用多久，一个服务器的运维与数据的存储会是一大笔支出，我们存放代码的服务器不知道还能承受多少用户的加入，如果有一天服务器无法承受用户的进入，我们将会停止新用户的进入，或者长期关停这个软件，这希望得到用户的理解与支持!如果您觉得这个软件对于您有一定的帮助，我希望能通行下方的二维码得到您的支持，当然您也可以选择别的支持方式，比如给我们点一个⭐⭐Star⭐⭐或者一个收藏，这样会给我们团队提供很大的信心支持!  
# 当前安排：
1.解决某付宝cookie掉线问题，目标达到N+1×24小时在线！
5月09日，当前测试中.....   
2.更新某信登陆问题！ 
# 软件下载地址
***  
监控下载地址：https://www.123pan.com/s/fjalVv-i4CQ3.html  
微信版本下载：https://www.123pan.com/s/fjalVv-WACQ3.html  
***  


V免签(非二开)在github上开源的，已经给你下载下来了，担心有后门的可以自己前往github下载！  
PC监控填写免签信息！  
单商户账号密码随意写  
多商户账号密码填写的不是QQ信息是免签的用户登陆账号，非后台账号(admib)  
有问题可以问，可帮助搭建！（有偿）QQ3281538031  
某信的监控，某信不退出就可一直监控!  
某支的监控，大概24小时左右需要重新登陆一次！因为某支的验证问题.  
CPU占用率低！  
某信监控能做到秒回调，某支大概有10秒左右的延迟！  
单商户无后门源码：https://www.123pan.com/s/fjalVv-nACQ3.html  
（不信的可以去github下载）

# 更新日志：
5月09日  
某付宝7×24小时监控在线测试（测试中）.技术支持：夏....科技（对方要求隐藏个人信息）   
5月04日  
某付宝7×24小时监控在线测试（失败）.欢迎各位大佬提供技术支持。     
4月26日  
增加nas服务器用户没有申请固定宽带导致的无法使用问题，更换了某付宝的验证模式，预计达到效果为7×24小时的监控在线（测试中）。  
4月17日  
修复免签源码不回调问题！  
4月04日  
解决CPU占用率在部分电脑居高不下的问题！已发布.  
4月03日  
添加监控软件掉线邮件通知！但未发布.  
4月02日  
修改昵称已被占用情况，完善个人隐私问题，隐藏服务ID.  
3月31日  
更新使用文档内容，优化界面BUG，但未发布.  
3月25日  
添加商家码的收款监控  

# 截图内容：
![G) @Z6DWHC~FHT72NIKTXBO](https://user-images.githubusercontent.com/62324707/226256325-8815adaa-65c1-4793-b644-280e7131bba8.png)
下载地址：https://www.123pan.com/s/fjalVv-i4CQ3.html   
Qq交流群：784641711  
作者QQ：3281538031  

# 源码安装教程
推荐使用宝塔面板安装，以下教程为宝塔面板安装教程，其他环境请参考自行配置

1、下载单商户无后门源码：https://www.123pan.com/s/fjalVv-nACQ3.html   
2、宝塔面板中新建网站，设置：  
 + 网站目录->运行目录 设置为public并保存
 + 伪静态 设置为thinkphp并保存
 + 默认文档 设置将index.html放在第一行并保存  
 
3、打开网站目录 config/database.php ，设置好您的mysql账号密码。    
4、导入数据库文件（位于根目录）vmq.sql到您的数据库。  
5、至此网站搭建完毕，请访问后自行修改配置信息！默认后台账号和密码均为admin   

# 监控安装教程
首先一个完整的安装包是这样的！  
![image](https://user-images.githubusercontent.com/62324707/229336836-685487b1-ccbb-45ce-a5cd-528d252dc635.png)  
接下来是手把手教学！  
+ 单商户  
1.打开【微信登陆破解.exe】与【智慧66云-微信监控.exe】或【智慧66云-支付宝监控.exe】  
2.如果是首次运行按照以下操作  
3.切换模式：单商户  
![image](https://user-images.githubusercontent.com/62324707/229337107-a67cd649-c3d2-4ef6-a03e-e329b5e221fb.png)  
4.填写个人信息，账号建议是QQ号，不易忘记！    
5.点击【保存信息】  
6.点击【注册账号】  
7.点击【登陆账号】  
8.点击【启动微信/支付宝监控】  
9.然后扫码登陆，如果出现版本过低，重启监控与微信，出现二维码后，点击【微信登陆破解.exe】的第二个按钮再扫码，如下图   
![image](https://user-images.githubusercontent.com/62324707/229337323-f2a80bdb-8f44-4a75-9cd9-eacadd91084d.png)    
10.日志中出现已连接表示成功.  
![image](https://user-images.githubusercontent.com/62324707/229337355-9fcd6196-42cb-4516-8f81-e730a7fa62ae.png)  
+ 多商户  
1.多商户账号密码填写的不是QQ信息是免签的用户登陆账号，非后台账号(admib)  ，也就是你的网址的user页面的登陆账号信息  
# 疑难解答  
1.为什么我的日志中没有【服务器已连接】？  
答：放置监控的文件夹缺少文件【add.dll】 

2.为什么监控不回调？  
答：检查心跳是否成功，检查心跳框的返回信息，按照心跳框操作.  

3.为什么提示我账号不存在或昵称被占用？  
答：账号不存在，先检查你的模式是不是准确的，昵称被占用是你把账号忘记了，联系作者修改信息.  

# 赞助      
目前软件属于免费使用阶段，我们也不清楚能提供使用多久，一个服务器的运维与数据的存储会是一大笔支出，我们存放代码的服务器不知道还能承受多少用户的加入，如果有一天服务器无法承受用户的进入，我们将会停止新用户的进入，或者长期关停这个软件，这希望得到用户的理解与支持!如果您觉得这个软件对于您有一定的帮助，我希望能通行下方的二维码得到您的支持，当然您也可以选择别的支持方式，比如给我们点一个星或者一个收藏，这样会给我们团队提供很大的信心支持!  

如果您选择二维码支持的方式,我希望您能备注您的信息,方便我们在日后的更新中感谢您!!!  

|赞助姓名|赞助方式|赞助金额 | 
|:------:|:------:|:------:|  
|吴**     |VX      |1.00    |
|黄*      |VX      |10.00   |
|向**     |ZFB     |8.88    |
|刘*      |VX      |15.00   |  
|张**     |VX      |10.00   |  
|张**     |VX      |20.00   |  
|赞助咖啡  |VX      |50.00   | 
|来自**雯  |zfb      |5.00   | 

![DNN0MM0MDDY {J9EP_)GSRX](https://user-images.githubusercontent.com/62324707/229338464-6f46d251-ab52-4dff-bd58-087e1695cf62.png)
