## 手摸手教你如何调式生产微信网页  


##### 背景
###### 大多数同学都遇到过刚刚这个功能还好好的,怎么忽然不能使用了呢?一般情况下,调试看看问题,然后解决问题即可.但是在已经上线的微信端则无法调试,这时候土办法就是在部署一套一样的环境,但是不一定能还原线上情况,这时候就需要使用微信调式工具<code>TBS Studio</code></p>
######  https://www.jianshu.com/p/f605d89b8287

引言
目前在微信公众号开发中大家都很了解微信开发者工具，在早期的微信开发者工具中有移动调试功能，让手机通过代理的方式开通移动调试，但是最新版本的微信开发者工具中移除了移动调试功能。


#### https://x5.tencent.com/tbs/guide/debug/download.html
####  在微信任意聊天窗口输入<code>  debugmm.qq.com/?forcex5=true<code>,然后打开网页会一闪而过或报错,都没关系. 

####  在微信任意聊天窗口输入 <code>http://debugtbs.qq.com/</code>,会出现以下设置界面. 


image.png

在微信公众号开发的实际过程中，因为网络部署、证书等种种原因会引起某些手机兼容性问题，这时候微信开发者工具就爱莫能助了，如何解决真机调试的问题，那就必须借助TBS Studio。

TBS Studio是什么
TBS Studio是面向基于TBS的Web开发者和移动应用开发商（包括微信、手Q，三方App等）打造的开发服务整体解决方案，以提升广大开发者在真机环境下的开发效率，并帮助开发者分析和优化网页的设计，主要功能有网页Inspector调试，网页性能分析等。
TBS Studio在哪里
TBS Studio 下载
TBS Studio如何使用

下载安装。
按照官方手册安装。

手机打开usb调试，连接到电脑






image.png


3.打开手机上的微信app并让微信保持在前台。
4.打开TBS Studio，点击启动检测。






image.png



tbs弹出确认，点击确定。






image.png


6.设定tbs的调试状态，公众号里选择普通网页。






image.png



使用微信扫二维码，根据提示操作，操作完成后重新开启微信app，打开要调试的公众号或h5链接。
8点击tbs的启动调试，得到如下界面。






image.png


9.找到要调试的连接点击对应的inspect，打开开发者工具，剩下的就和电脑chrome一样了，这里操作界面是和手机同步的。






image.png



over~~~~enjoy it。

作者：TarsL
链接：https://www.jianshu.com/p/f605d89b8287
来源：简书
简书著作权归作者所有，任何形式的转载都请联系作者获得授权并注明出处。
