# YoudaoDict

自制有道词典 Chrome 扩展，使用[有道词典 api](http://ai.youdao.com/)

## 安装

https://chrome.google.com/webstore/detail/llopmojlajjdmeilflefogagfolbndme


## 申请有道智云 API

申请地址：https://ai.youdao.com/

1. 有道智云 -> 自然语言翻译 -> 翻译实例 -> 创建实例 -> 文本翻译服务

2. 有道智云 -> 语音合成TTS -> TTS实例 -> 创建实例 -> 语音合成服务

3. 有道智云 -> 应用管理 -> 我的应用 -> 创建应用 -> 绑定服务 -> 选择步骤1和2创建的两个服务 -> 获取此应用的`应用ID`和`应用密钥`


## 在扩展设置页面填写上步中的应用ID和密钥

![menu](media/youdao-dict-options.png)

![page](media/youdao-dict-option-page.png)


## 开发

```shell
npm install
npm run build
```

在 Chrome 扩展页面点击载入开发中的扩展，选择 `build` 目录。

## 功能

* 点击扩展图标输入进行翻译
* 双击或按设置的按键(默认为 CTRL)对选择区域进行翻译
* 添加生词至有道单词本
* 添加个人有道词典 key

## 版权 LICENSE

* MIT
