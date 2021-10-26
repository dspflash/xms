## XMS 物流管理系统 (http://3ucs.com)
源代码文件太多(90%以上的代码都是使用3UCS BizTool 自动化工具生成，给个性化定制节省了大量的时间，带来了极大的便利，参见http://3ucs.com/x)，而安装包带有完整源代码，安装完成后源代码在安装目录下（xms文件夹，直接下载release的exe安装包，简单方便）。

升级时可将新的代码直接覆盖xms文件夹的代码

现在您可以使用xone客户端了，超轻量级云应用客户端，高颜值高效灵活稳定(http://3ucs.com/dl56.html)

## 简介
XMS是开源的C/S、B/S双架构物流管理系统，。
三优物流是什么？

三优物流是以AI人工智能为核心的新一代物流云服务平台。

以“货物”为中心

以“流通”为主线

无缝衔接“货物”的生产、仓储、销售、运输、配送等环节

紧密连接生产者、物流商、用户

让供需更顺畅

让流通更透明

……
 
AI人工智能配载

AI人工智能排线

AI人工智能配送

AI人工智能语音交互
 
## 特性
- C/S、B/S双架构，完美运行于手机客户端、电脑客户端和主流浏览器
- 部署简单方便
- 个性化开发定制简单快捷
- 多语言支持(可修改成任意语言版本，修改语言包即可)

## 依赖性
- 3UCS xPlus(http://3ucs.com/x/)
- MySQL

## 演示地址及截图：http://56.3ucs.com
网页登录例图

![](https://dspflash.github.io/res/xms/web0.png)

3UCS XOne客户端登录例图

![](https://dspflash.github.io/res/vtiger/crmgifXOne.gif)

3UCS NISU客户端登录例图

![](https://dspflash.github.io/res/vtiger/crmgif.gif)

手机客户端登录例图

![](https://dspflash.github.io/res/vtiger/prjmobile.gif)

## 部署与使用
可参考ERP视频资料

音视频演示(3UCS ERP安装部署) http://3ucs.com/video.php?vid=45

音视频演示(3UCS ERP基础功能) http://3ucs.com/video.php?vid=42

音视频演示(x+网页版安装部署) http://3ucs.com/video.php?vid=53

## 源代码说明
Files & Dirs
#BizTool生成的代码文件
1) 	xx.xpj
- BizTool配置文件，"xx"为对应于数据库表名（若保存时设有新名称则是新的文件名）
- bizxml project files, auto saved by biztool
	
2)	xx.xml, xx_GBDEDIT.xml, xx_GBDV.xml, xx_GBOPE.xml, xx_GBOPV.xml
- 自动生成的单页面文件（页面上部分为编辑，下部分为ListView之类的显示）
- auto generated files use 'x'.xpj by biztool

3)	xx_V.xml(数据显示视图页面view), xx_Ve.xml(数据编辑修改页面Edit), xx_Vpg.xml(显示记录数、分页、页码), xx_Vpgop.xml(翻页操作), xx_Vh.xml(编辑，一般无需修改hide for edit), xx_Vs.xml(查询条件代码search for view), xx_Vv.xml(显示视图代码 listctrl etc, for view)
- 自动生成的双页面代码文件
- auto generated files(2 pages, one for view and one for edit)
	
4)	xx_ops.xml
- 自定义的弹出式菜单代码
	
5)	index.xml prjm.xml prjtask.xml common.xml
- 用户根文件
- user root layouts.	
	
6)	??_V?m.xml,??_V?m.xml
- 手工编辑修改的代码文件（原始文件为xx_V?.xml文件）
- manual composed files(modified according to ??_V?.xml)
	
rule/		xlogic files invoked in "3)" files

lan/		language files

install/	install scripts and instructions

## 多语言版本
修改语言包（lan文件夹下文件）即可。

## 个性化定制
直接修改源代码或使用BizTool工具载入配置文件（xpj）修改后重新生成代码
参考 视频演示(3UCS ERP二次开发培训视频2017) http://3ucs.com/video.php?vid=46

## 在线沟通 Discuss
可点击图片与我们在线沟通交流<br/>
Contact us at <a href="http://3ucs.com/xchat/index.php?enterurl=http%3A%2F%2Fgithub.crm.3ucs.com%2F" target="_blank"><img src="http://3ucs.com/images/livechat.png" alt="Chat 在线客服"/></a> if you have feedback, questions or want to chat. 



