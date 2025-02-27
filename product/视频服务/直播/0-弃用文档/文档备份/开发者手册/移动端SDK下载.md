本章节提供视频直播/点播DEMO下载，直播和点播为同一份DEMO和SDK，接口使用方式基本相同。直播DEMO使用方式请参考[快速体验](https://cloud.tencent.com/doc/product/267/快速体验)章节。
## 下载地址

**注：以下为直播/点播 SDK DEMO的下载地址，欢迎安装体验。**

直播/点播 SDK还在紧张的内测中。内测期间SDK申请条件如下：

1、您的移动端产品没直播功能，但是产品有一定的用户存量，并有音视频相关开发经验，需集成直播功能的。或，您的产品是纯粹直播型产品（如、映客、斗鱼），需要集成我们的SDK的。
2、已经认证并开通腾讯云直播服务。
3、有阅读WIKI文档解决问题习惯。
4、点播平台用户需要移动端SDK进行播放的。

若您满足以上条件，欢迎联系我们（QQ群:538797442）。我们将在近期开放SDK的下载，感谢等待。谢谢！



| 系统 | 版本 | 下载地址 | 
|---------|---------|---------|---------|
| iOS | 1.4.2.180 |  ![](//mccdn.qcloud.com/static/img/96240acaa7936727d75609a983262a27/image.png)|
| Android|1.5.1.301 | [下载](https://mccdn.qcloud.com/static/archive/5afff09d6b40a48db78243c24c5ca651/rtmpdemo-1.5.1.301.apk.zip)|

## 变更历史
1.5.1
1.Android推流支持硬件加速
2.MP4和HLS点播支持硬件解码
3.解决与互动直播的库冲突
4.点播增加重连机制
5.修复过去一周测试团队发现的若干bug

1.5.0
1.重构推流和播放器SDK，提高SDK的稳定性
2.增加GOP设置参数，秀场场景下推荐3秒（默认值）
3.解决跟AVGSDK的符号冲突问题
4.修复横屏推流中的崩溃问题
5.修复过去一周测试团队发现的若干bug

1.4.2
1.支持MP4 和 HLS 在线点播
2.不再使用aar作为android sdk的打包方式，改为传统的jar+lib模式
3.android sdk新增arm64模式
4.修复过去一周测试团队发现的若干bug


1.4.1
1.提升推流性能，提升声音编解码性能
2.增加FLV点播支持
3.修复若干bug

1.3.1
1.提升播放性能
2.优化缓存策略，提供多种参数配置
3.推流端增加水印支持
4.修复若干bug

1.2.1
1.优化美颜/美白效果
2.iOS和安卓增加硬件解码支持，iOS增加硬件编码支持
3.修复若干bug

1.1.1
1.推流SDK支持RTMP协议，并支持美颜/美白、分辨率设置等功能
2.播放SDK支持FLV/RTMP协议，支持画面裁剪，支持横竖屏切换
