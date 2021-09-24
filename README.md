## 功能点介绍
1. 实现截取某个控件并生成image的功能。
2. 实现MP4格式视频流的播放和暂停以及获取某一帧（视频流截图）的功能。
3. 实现m3u8格式视频流的播放和暂停以及获取某一帧（视频流截图）的功能。

## 注意事项
1. 播放视频时需要配置info.plist中的NSAppTransportSecurity，否则可能会出现视频无法播放的问题。
2. 在视频播放页面push到别的页面时需要停止视频的播放，否则视频会一直在播放。

## 代码介绍
1. MMScreenshotsManager中封装了三种截屏方法。
2. MMVideoPlayer中封装了一个简单的视频播放器。
3. 调用示例在对应的ViewController中，可供参考。

## 代码运行效果预览
### imageView截图
<img src="https://vkceyugu.cdn.bspapp.com/VKCEYUGU-f92a0e71-a10b-4097-af0d-93aa474b1716/a91d08d0-ff95-40ea-9357-1d3aa8c0456a.jpeg" width="220" height="400" >

### MP4格式视频流截屏
<img src="https://vkceyugu.cdn.bspapp.com/VKCEYUGU-f92a0e71-a10b-4097-af0d-93aa474b1716/cc1ee8df-4cdc-4e59-b140-66b5de6e210a.jpeg" width="220" height="400" >
### m3u8格式视频流截屏
<img src="https://vkceyugu.cdn.bspapp.com/VKCEYUGU-f92a0e71-a10b-4097-af0d-93aa474b1716/51598260-54d9-49c3-8041-88bce207a4a7.jpeg" width="220" height="400" >

## License
- 如果您发现了bug请尽可能详细地描述系统版本、手机型号和复现步骤等信息 提一个issue.
- 如果您有什么好的建议也可以提issue,大家一起讨论一起学习进步...
- [有兴趣可以加下创建的QQ群:812144991(因为工作很忙所以可能问问题没人回答!!)](//shang.qq.com/wpa/qunwpa?idkey=ebd8d6809c83b4d6b4a18b688621cb73ded0cce092b4d1f734e071a58dd37c26) <a target="_blank" href="http://wpa.qq.com/msgrd?v=3&uin=294005139&site=qq&menu=yes"></a>
- The MIT License (MIT)      Copyright (c) 2014 KEENTEAM
