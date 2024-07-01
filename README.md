# VideoAutoPublish

VideoAutoPublish 是套基于 Electron + Api 实现的非自动化测试的发布方案，[抖音](https://creator.douyin.com)，[小红书](https://creator.xiaohongshu.com)，[视频号](https://channels.weixin.qq.com)，等平台短视频自动发布的创作者工具。

## 功能

1. 基于Electron实现多账号登录态管理
2. 目前实现了WebSocket方式调用(当前我自己的用途是个别的平台的小插件),可自行通过IPC通信实现前端可视化界面
3. 支持抖音、小红书、视频号平台的视频发布，可扩展其他三方视频发布平台
4. 抖音支持自定义封面、话题、标题、定时发布、合集、POI
5. 视频号支持自定义封面、标题、话题、短标题、POI、合集、定时发布
6. 小红书支持自定义封面、标题、官方话题、POI、定时发布
7. 支持检查已授权账号登录态、更新已授权账号用户信息
8. 封装了平台话题、合集、POI、小程序等查询接口

## 区别

1. 不是基于 selenium、playwright这种自动化方案实现上传及发布
2. 采用各创作者中心Api方式进行发布（较自动化方案发布速度更快）

## 软件界面

![](https://github.com/JuanFaC/video_auto_publish/blob/main/Screen/20240701110939.png?raw=true)

## 微信扫码交流

![](https://github.com/JuanFaC/video_auto_publish/blob/main/Screen/20240701111125.png?raw=true)

## 温馨提示

此页面仅作学习交流用，仅可用于查找资料，请勿做任何违法的事。所有资源均来自互联网，非盈利目的，不保证可用，不定时更新修改，仅供大家交流学习使用，出现一切问题概不负责。
