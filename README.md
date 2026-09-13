# book-sources

Legado（阅读 App）书源。

## 搬山人小说网

- 站点：https://www.banshanren.com
- 功能：搜索、详情、目录（兼容有/无分卷两种排版）、正文、发现页（8 个分类，支持翻页）
- 无需登录、无需付费，正文游客全开（已抽查到完结书大结局）

### 一键导入

```
legado://import/bookSource?src=https%3A%2F%2Fcdn.jsdelivr.net%2Fgh%2Fwdfkymd%2Fbook-sources%4001f2c79f54740b1848f1fabfc42d17df47e20ce0%2Fbanshanren.json
```

手机浏览器打开上面这行，或转成二维码扫码。

### 网络导入

书源管理 → 右上角 ⋮ → 网络导入，粘贴：

```
https://cdn.jsdelivr.net/gh/wdfkymd/book-sources@01f2c79f54740b1848f1fabfc42d17df47e20ce0/banshanren.json
```

### 已知限制

- 无封面：站方图片是 AES 加密的，App 解不了（加密已破解，但书源只能填 URL，接解密代理才有图，暂不折腾）
- 发现页/分类页无简介：站结构如此，搜索结果和书详情页有简介

## 爱丽丝书屋

- 站点：https://www.alicesw.com
- 功能：搜索、详情、目录（独立目录页）、正文、发现页（排行 + 30 个分类，支持翻页）
- 备注：搜索无封面，封面从详情页取；目录有分卷标题行，会混在章节列表里

### 网络导入

```
https://cdn.jsdelivr.net/gh/wdfkymd/book-sources@f9e8b7517ebb620644d6e2f44552223b26b50cd7/alicesw.json
```

## 第一版主

- 站点：https://m.diyibanzhu5.online（WAP 站；主域名 m.diyibanzhu.me 套了 Cloudflare，用不了）
- 功能：搜索（POST）、详情、目录、正文（下一章链）、发现页（5 个榜单）
- 备注：无封面（WAP 站只有占位图）、无简介（列表页结构如此，详情页有简介）；目录原站是倒序，规则里已反转；镜像域名会轮换，被墙就去发布页 https://www.quan--er.com/ 找新域名，只改源里两个 URL 前缀即可

### 网络导入

```
https://cdn.jsdelivr.net/gh/wdfkymd/book-sources@e8eacdf26e41f07ac253e9108f3d6a9a5ef39138/diyibanzhu.json
```
