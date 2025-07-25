# 静态资源仓库

> 本仓库资源仅供个人学习使用，禁止非法商用和恶意传播。

提供静态资源文件仓库，使用`jsdelivr`的`CDN` 进行加速访问，国内访问地址用`https://cdn.jsdelivr.net`。

## 图片目录

图片目录为`images`，采用`PicList`第三方客户端进行本地上传，客户端支持远程删除图片，图片类型转换，图片压缩，可作为个人图床使用。

## JS 目录

收录一些不常见的`npm`库中没有的 js 文件。

## CSS 目录

收录第三方`css`文件。

## Fonts 目录

1、收录常用中文字体源文件，可以直接完整引入，字体文件较大。

2、对收录的源文件进行中文分片处理，借助[`cn-font-split`](https://github.com/KonghaYao/cn-font-split)组件，将中文进行分片为很小的文件，然后根据页面实际字体，按需加载。

3、源文件在`fonts/original`目录下，对应的分片文件在`fonts/division`目录下。

4、字体文件分片后，每一个目录下都有一个与`目录同名的css`文件，可单独引入使用。

### 1. PingFangSC 多版本字体

> 注意：未经授权修改与使用 PingFang 字体是侵犯 Apple 公司版权的行为

感谢[`ACT-02`]('https://github.com/ACT-02')提供的`PingFang`多版本字体，包括 港体、澳体、繁体中文和简体中文。这些字体文件涵盖了六个不同的字重，适用于不同的设计需求。

#### 1. 字体字重

- **苹方-简 常规体**: PingFangSC-Regular

- **苹方-简 细体**: PingFangSC-Light

- **苹方-简 中黑体**: PingFangSC-Medium

- **苹方-简 极细体**: PingFangSC-Ultralight

- **苹方-简 中粗体**: PingFangSC-Semibold

- **苹方-简 纤细体**: PingFangSC-Thin

#### 2. 分片文件

借助[`cn-font-split`](https://github.com/KonghaYao/cn-font-split)组件，对`PingFang`字体进行了分片，分片目录：`fonts/division/PingFangSC`, 可直接引入对于目录下面的样式文件。

### 2. 鸿蒙字体
通过[华为开发者联盟](https://developer.huawei.com/consumer/cn/design/resource-V1)下载免费的鸿蒙字体，通过分片处理后，文件包很小，
分片目录：`fonts/division/HarmonyOS`, 可直接引入对于目录下面的样式文件。
