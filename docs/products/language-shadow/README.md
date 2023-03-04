<p align="center">
    <img width="400" src="./assets/logo-language-shadow.svg">
</p>

## 简介

文影 (Language Shadow) 是一个简单的翻译器，它通过 OCR 识别字幕文字，然后再使用本地翻译服务器进行翻译。它有以下特点：

- 完全离线、免费且开源(项目地址：https://github.com/rerender2021/language-shadow)
- 使用方便：解压缩后双击 exe 即可使用

![language-shadow-usage](./assets/language-shadow-usage.png)

演示视频见:

- [文影：实时英语字幕翻译](https://www.bilibili.com/video/BV1Cs4y1j7Qb/)

## 安装

- 运行环境要求：至少 Windows 10
- 下载地址（根据实际需要选择完整下载或仅升级）：https://github.com/rerender2021/language-shadow/releases/tag/1.1.0


## 功能说明

### 选择识别区

点击「 选择识别区 」，用鼠标「 自左上向右下 」选择一块区域，这块区域的文字将被识别并翻译：

![select-area](./assets/select-area.gif)

生成的字幕框可以拖动边缘来调整大小。

### 重置识别区

如果不小心选择识别区的时候失误，除了重新选择，还可以直接调整字幕框大小后，点击「 重置识别区 」：

![reset-area](./assets/reset-area.gif)

### 字幕置顶

默认情况下，生成的字幕框始终会在窗口最上层。如果这不是想要的，那么可以自己切换：

![set-topmost](./assets/set-topmost.gif)

### 自定义超时时间

默认情况下，如果 4s 都没能完成一次 OCR 文字识别或翻译，那么此次翻译将跳过。这个时间可根据自己的设备来调整，只需用文本编辑器打开`config.json`，编辑 `timeout` 后的数值：

![config-timeout](./assets/config-timeout.png)

注意单位是毫秒（ms）。

## 赞赏

`:)` 如果此软件值得赞赏，可以请作者看小说，一元足足可看八章呢。

<p align="left">
    <img width="300" src="../../assets/donate.jpg">
</p>


