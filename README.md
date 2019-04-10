# React-native

## test write about update use 

### 版本号字段
|字段名称|字段意义|字段样例|文件位置|
| :-:|:-:|:-:|:-:|
|versionCode| 大版本号| 5 | Android在build.gradle中的versionCode字段 、IOS为XCode中的version字段|
|versionName| 小版本号|5.0.5| Android在version.js中的 androidVersionName字段、IOS为version.js中的iosVersionName字段 |

### 服务器字段（JSON文件：记录最新版本信息）
|字段名称|字段意义|字段类型|字段值（样例）|
|:-:|:-:|:-:|:-:|
|appName|应用（APP）名称|String|超级APP|
|versionCode|大版本号|int|2|
|versionName|小版本号|String|2.0.1|
|urlAppAND|Android-APK下载链接|String| http://127.0.0.1/DL/staffapp.apk|
|mustUpdate|是否强制更新|boolean|true|
|sizeAND|文件大小|String|13.56M|
|urlZipAllAndroid|Android-bundle压缩包下载链接|String|http://127.0.0.1/DL/androidBundle.zip|
|updateInfo|本次更新内容|String|1. 修复Android8.0解析包错误的BUG  |
