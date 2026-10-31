# EDGE-space 安卓版

EDGE // SPACE 主站的安卓套壳包，打开即为主站页面（本地内置最新版主站 index.html，联网后 Supabase 登录、积分等功能正常使用）。

## 下载

- EDGE-space.apk（本仓库根目录）
- 包名：com.edge.space
- 版本：1.0（versionCode 1）
- 应用名：EDGE

## 手机支持

- 最低支持 Android 7.0（minSdk 24），目标 Android 13（targetSdk 33），未设最高版本上限。
- 也就是说：Android 7.0 及以上都能装，老手机（例如 Android 12）和新手机都能用；低于 Android 7.0 的老机型装不上。
- 权限只有联网（INTERNET）和查看网络状态（ACCESS_NETWORK_STATE），没有其他敏感权限。

## 包里是什么

- 拆包已核验：assets/index.html 与 2026-10-28 主站最新版（提交 d1cd281，660648 字节）逐字节一致，不是旧版页面。
- 内置页面里没有爱发电内容（爱发电早已注销，主站也早已去掉）。
- 壳子本身是 WebView 打开本地页面，线上功能仍需联网。

## 安装

1. 在手机上下载本仓库的 EDGE-space.apk。
2. 允许安装未知来源应用后安装即可。
3. 首次打开如提示联网权限，允许即可。

## 注意

- 本包未经上架应用商店，属自发分发，安装时系统提示未知来源属正常现象。
- 如后续主站更新，APK 里的内置页面不会自动跟着变，需重新打新包。
