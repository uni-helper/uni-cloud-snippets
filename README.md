# @uni-helper/uni-cloud-snippets-vscode

[![License](https://img.shields.io/github/license/uni-helper/uni-cloud-snippets-vscode)](https://github.com/uni-helper/uni-cloud-snippets-vscode/blob/main/LICENSE)

[![VSCode](https://vsmarketplacebadge.apphb.com/version-short/uni-helper.uni-cloud-snippets-vscode.png)](https://marketplace.visualstudio.com/items?itemName=uni-helper.uni-cloud-snippets-vscode)

[![OpenVSX](https://img.shields.io/badge/dynamic/json?color=brightgreen&label=OpenVSX&query=%24.version&url=https%3A%2F%2Fopen-vsx.org%2Fapi%2Funi-helper%2Funi-cloud-snippets-vscode)](https://open-vsx.org/extension/uni-helper/uni-cloud-snippets-vscode)

[改动日志](https://github.com/uni-helper/uni-cloud-snippets-vscode/blob/main/CHANGELOG.md)

想让 `uni-app` 开发变得更直观、高效？想要更好的 `uni-app` 开发体验？不妨看看 [uni-helper 主页](https://uni-helper.js.org) 和 [uni-helper GitHub Organization](https://github.com/uni-helper)！

## 插件特性

- uni-cloud 基本能力代码片段
- 参考 [uni-cloud 官方文档](https://uniapp.dcloud.net.cn/uniCloud/)
- 参考 [Vue.js 2 风格指南](https://v2.cn.vuejs.org/v2/style-guide/) 和 [Vue.js 3 风格指南](https://cn.vuejs.org/style-guide/)

**插件和文档的冲突之处，请以文档为准。**

插件源代码在 [uni-helper/uni-cloud-snippets-vscode](https://github.com/uni-helper/uni-cloud-snippets-vscode)。欢迎提交 ISSUE 和 PR 改进本插件。

## 使用

安装插件后重启 VSCode 即可。

## HTML

|API|Prefix|Description|
|-|-|-|
|`<unicloud-db>`|`unicloud-db`, `<unicloud-db>`|数据库查询组件。更多信息查看 <https://uniapp.dcloud.net.cn/uniCloud/unicloud-db>。|

## JavaScript/TypeScript

|API|Prefix|Description|
|-|-|-|
|`uniCloud.importObject()`|`uniCloud.importObject`|uniCloud 客户端获取云对象引用以调用云对象接口。更多信息查看 <https://uniapp.dcloud.net.cn/uniCloud/client-sdk>。|
|`uniCloud.callFunction()`|`uniCloud.callFunction`|uniCloud 客户端调用云函数。更多信息查看 <https://uniapp.dcloud.net.cn/uniCloud/client-sdk>。|
|`uniCloud.database()`|`uniCloud.database`|uniCloud 客户端获取云数据库实例。更多信息查看 <https://uniapp.dcloud.net.cn/uniCloud/client-sdk>。|
|`uniCloud.databaseForJQL()`|`uniCloud.databaseForJQL`|uniCloud 客户端获取云数据库实例（JQL 语法）。更多信息查看 <https://uniapp.dcloud.net.cn/uniCloud/client-sdk>。|
|`uniCloud.uploadFile()`|`uniCloud.uploadFile`|uniCloud 客户端上传文件到云存储。更多信息查看 <https://uniapp.dcloud.net.cn/uniCloud/client-sdk>。|
|`uniCloud.getTempFileURL()`|`uniCloud.getTempFileURL`|uniCloud 客户端获取云存储文件的临时路径。更多信息查看 <https://uniapp.dcloud.net.cn/uniCloud/client-sdk>。|
|`uniCloud.chooseAndUploadFile()`|`uniCloud.chooseAndUploadFile`|uniCloud 客户端选择文件并上传。更多信息查看 <https://uniapp.dcloud.net.cn/uniCloud/client-sdk>。|
|`uniCloud.getCurrentUserInfo()`|`uniCloud.getCurrentUserInfo`|uniCloud 客户端获取当前用户信息。更多信息查看 <https://uniapp.dcloud.net.cn/uniCloud/client-sdk>。|
|`uniCloud.init()`|`uniCloud.init`|uniCloud 客户端同时使用多个服务空间时初始化额外服务空间。更多信息查看 <https://uniapp.dcloud.net.cn/uniCloud/client-sdk>。|
|`uniCloud.addInterceptor()`|`uniCloud.addInterceptor`|uniCloud 客户端新增拦截器。更多信息查看 <https://uniapp.dcloud.net.cn/uniCloud/client-sdk>。|
|`uniCloud.removeInterceptor()`|`uniCloud.removeInterceptor`|uniCloud 客户端移除拦截器。更多信息查看 <https://uniapp.dcloud.net.cn/uniCloud/client-sdk>。|
|`uniCloud.interceptObject()`|`uniCloud.interceptObject`|uniCloud 客户端拦截云对象请求。更多信息查看 <https://uniapp.dcloud.net.cn/uniCloud/client-sdk>。|
|`uniCloud.onResponse()`|`uniCloud.onResponse`|uniCloud 客户端监听服务端（云函数、云对象、clientDB）响应。更多信息查看 <https://uniapp.dcloud.net.cn/uniCloud/client-sdk>。|
|`uniCloud.offResponse()`|`uniCloud.offResponse`|uniCloud 客户端移除监听服务端（云函数、云对象、clientDB）响应。更多信息查看 <https://uniapp.dcloud.net.cn/uniCloud/client-sdk>。|
|`uniCloud.onNeedLogin()`|`uniCloud.onNeedLogin`|uniCloud 客户端监听需要登录。更多信息查看 <https://uniapp.dcloud.net.cn/uniCloud/client-sdk>。|
|`uniCloud.offNeedLogin()`|`uniCloud.offNeedLogin`|uniCloud 客户端移除监听需要登录。更多信息查看 <https://uniapp.dcloud.net.cn/uniCloud/client-sdk>。|
|`uniCloud.onRefreshToken()`|`uniCloud.onRefreshToken`|uniCloud 客户端监听登录态更新事件。更多信息查看 <https://uniapp.dcloud.net.cn/uniCloud/client-sdk>。|
|`uniCloud.offRefreshToken()`|`uniCloud.ofRefreshToken`|uniCloud 客户端移除监听登录态更新事件。更多信息查看 <https://uniapp.dcloud.net.cn/uniCloud/client-sdk>。|
|`uniCloud.initSecureNetworkByWeixin()`|`uniCloud.initSecureNetworkByWeixin`|uniCloud 客户端在微信小程序安全网络请求发送之前与云函数握手。更多信息查看 <https://uniapp.dcloud.net.cn/uniCloud/client-sdk>。|
|`uniCloud.getFileInfo()`|`uniCloud.getFileInfo`|uniCloud 客户端使用阿里云公测版云存储链接获取商用版云存储链接。更多信息查看 <https://uniapp.dcloud.net.cn/uniCloud/client-sdk>。|
|`uniCloud.database()`|`uniCloud.database`|uniCloud 云函数/云对象获取云数据库实例。更多信息查看 <https://uniapp.dcloud.net.cn/uniCloud/cf-functions.html#unicloud-api%E5%88%97%E8%A1%A8>。|
|`uniCloud.databaseForJQL()`|`uniCloud.databaseForJQL`|uniCloud 云函数/云对象获取云数据库实例（JQL 语法）。更多信息查看 <https://uniapp.dcloud.net.cn/uniCloud/cf-functions.html#unicloud-api%E5%88%97%E8%A1%A8>。|
|`uniCloud.redis()`|`uniCloud.redis`|uniCloud 云函数/云对象获取 Redis 实例。更多信息查看 <https://uniapp.dcloud.net.cn/uniCloud/cf-functions.html#unicloud-api%E5%88%97%E8%A1%A8>。|
|`uniCloud.uploadFile()`|`uniCloud.uploadFile`|uniCloud 云函数/云对象上传文件到云存储。更多信息查看 <https://uniapp.dcloud.net.cn/uniCloud/cf-functions.html#unicloud-api%E5%88%97%E8%A1%A8>。|
|`uniCloud.downloadFile()`|`uniCloud.downloadFile`|uniCloud 云函数/云对象下载云存储文件到当前运行环境。更多信息查看 <https://uniapp.dcloud.net.cn/uniCloud/cf-functions.html#unicloud-api%E5%88%97%E8%A1%A8>。|
|`uniCloud.deleteFile()`|`uniCloud.deleteFile`|uniCloud 云函数/云对象删除云存储文件。更多信息查看 <https://uniapp.dcloud.net.cn/uniCloud/cf-functions.html#unicloud-api%E5%88%97%E8%A1%A8>。|
|`uniCloud.getTempFileURL()`|`uniCloud.getTempFileURL`|uniCloud 云函数/云对象获取云存储文件临时路径。更多信息查看 <https://uniapp.dcloud.net.cn/uniCloud/cf-functions.html#unicloud-api%E5%88%97%E8%A1%A8>。|
|`uniCloud.customAuth()`|`uniCloud.customAuth`|uniCloud 云函数/云对象使用云厂商自定义登录（仅腾讯云支持）。更多信息查看 <https://uniapp.dcloud.net.cn/uniCloud/cf-functions.html#unicloud-api%E5%88%97%E8%A1%A8>。|
|`uniCloud.callFunction()`|`uniCloud.callFunction`|uniCloud 云函数/云对象中调用另一个云函数。更多信息查看 <https://uniapp.dcloud.net.cn/uniCloud/cf-functions.html#unicloud-api%E5%88%97%E8%A1%A8>。|
|`uniCloud.importObject()`|`uniCloud.importObject`|uniCloud 云函数/云对象中调用另一个云对象。更多信息查看 <https://uniapp.dcloud.net.cn/uniCloud/cf-functions.html#unicloud-api%E5%88%97%E8%A1%A8>。|
|`uniCloud.httpclient.request()`|`uniCloud.httpclient`|uniCloud 云函数/云对象通过 HTTP 访问其他系统。更多信息查看 <https://uniapp.dcloud.net.cn/uniCloud/cf-functions.html#unicloud-api%E5%88%97%E8%A1%A8>。|
|`uniCloud.httpProxyForEip`|`uniCloud.httpProxyForEip`|uniCloud 云函数使/云对象用云厂商代理访问 HTTP 服务（仅阿里云支持）。更多信息查看 <https://uniapp.dcloud.net.cn/uniCloud/cf-functions.html#unicloud-api%E5%88%97%E8%A1%A8>。|
|`uniCloud.sendSms()`|`uniCloud.sendSms`|uniCloud 云函数/云对象发送短信。更多信息查看 <https://uniapp.dcloud.net.cn/uniCloud/cf-functions.html#unicloud-api%E5%88%97%E8%A1%A8>。|
|`uniCloud.getPhoneNumber()`|`uniCloud.getPhoneNumber`|uniCloud 云函数/云对象获取一键登录手机号。更多信息查看 <https://uniapp.dcloud.net.cn/uniCloud/cf-functions.html#unicloud-api%E5%88%97%E8%A1%A8>。|
|`uniCloud.init()`|`uniCloud.init`|uniCloud 云函数/云对象获取指定服务空间实例。更多信息查看 <https://uniapp.dcloud.net.cn/uniCloud/cf-functions.html#unicloud-api%E5%88%97%E8%A1%A8>。|
|`uniCloud.getRequestList()`|`uniCloud.getRequestList`|uniCloud 云函数/云对象获取当前实例正在处理的请求 ID 列表。更多信息查看 <https://uniapp.dcloud.net.cn/uniCloud/cf-functions.html#unicloud-api%E5%88%97%E8%A1%A8>。|
|`uniCloud.getClientInfos()`|`uniCloud.getClientInfos`|uniCloud 云函数/云对象获取当前实例正在处理的请求对应的客户端信息列表。更多信息查看 <https://uniapp.dcloud.net.cn/uniCloud/cf-functions.html#unicloud-api%E5%88%97%E8%A1%A8>。|
|`uniCloud.getCloudInfos()`|`uniCloud.getCloudInfos`|uniCloud 云函数/云对象获取当前实例正在处理的请求对应的云端信息列表。更多信息查看 <https://uniapp.dcloud.net.cn/uniCloud/cf-functions.html#unicloud-api%E5%88%97%E8%A1%A8>。|
