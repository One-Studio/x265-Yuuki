# x265-Yuuki

从 [x265 Yuuki变异版原项目](https://github.com/msg7086/x265-Yuuki-Asuna) 搬运得到，并用 JSdelivr 作为CDN加速，使用工具 [ReleaseDelivr](https://github.com/One-Studio/ReleaseDelivr)

## 最新版下载链接：

https://cdn.jsdelivr.net/gh/One-Studio/x265-Yuuki@master/dist/x265-Yuuki.7z

## 某个版本的下载链接

通过下面的API接口获取历史版本号，比如 `3.4+1-g07e3381df+31`，下载链接：

https://cdn.jsdelivr.net/gh/One-Studio/x265-Yuuki@3.4+1-g07e3381df+31/dist/x265-Yuuki.7z

## 本搬运仓库API：

版本号：https://cdn.jsdelivr.net/gh/One-Studio/x265-Yuuki@master/version

下载链接（ `/n` 分割）：https://cdn.jsdelivr.net/gh/One-Studio/x265-Yuuki@master/download_link

API接口 Json格式：https://cdn.jsdelivr.net/gh/One-Studio/x265-Yuuki@master/api.json

| API          | 类型     | 含义                                          |
| ------------ | -------- | --------------------------------------------- |
| Version      | string   | 版本号                                        |
| VersionList  | []string | 历史版本                                      |
| ReleaseTime  | string   | 最新版本的发布时间 (格式2020-10-20T12:16:01Z) |
| Checktime    | string   | 搬运时检查的时间                              |
| DownloadLink | []string | 下载链接                                      |
| Format       | int      | 格式(1=7z, 2=zip)                             |
| ReleaseNote  | string   | 更新日志                                      |
