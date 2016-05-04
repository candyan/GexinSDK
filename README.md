GetuiSDK(GexinSDK)
========

[个推 SDK](http://docs.getui.com/pages/viewpage.action?pageId=589866)

### Install

使用 [CocoaPods-depend](https://github.com/candyan/cocoapods-depend) 插件

``` pod depend add GetuiSDK ```

或者在 `Podfile` 文件下添加

``` pod 'GetuiSDK' ```

由于不太经常关注更新，如果发现有新版更新欢迎PR。Thx

###Changelog

####1.4.2 (2016-04-26)

- 修复大批量消息接收时，UI卡顿问题。
- 分离获取IDFA版本和不获取IDFA版本，供开发者选择。
- 支持后台运行，默认关闭，需开发者自主开启。

####1.4.1 (2016-03-21)

- 修复若干已知bug，提升SDK稳定性;
- 支持角标自增设置，增加setBadge和resetBadge接口;
- 停用stopSdk、retrivePayloadById接口;
- 修改接收透传消息回调接口;

####1.3.2（2015-12-28）
- 修复若干bug，使SDK更加稳定

####1.3.1 (2015-11-27)

- 添加自定义事件上报 API 接口
- 修改 Xcode 使用 `Enable Address Sanitizer` 运行闪退 Bug
- 修复若干 Bug，使 SDK 更加稳定
