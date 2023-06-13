# 青年大学习自动化完成
每周一下午1点自动完成青年大学习，并通过Pushplus推送青年大学习完成截图+视频地址

**注**: Pussplus最近崩溃较多，后期将添加Server酱微信推送或企业微信通知功能

## 使用方法
1. [Fork本仓库](https://github.com/ooyq/dxx-helper)

2. 选择Fork后的仓库 -> **Settings** -> **Secrets and Variables** -> **Action** -> **New repository secret**, 添加Secrets变量如下:

|Name|Value|Required|
|:---:|:---:|:---:|
|**token**|需要 https 抓包，配置好环境后进入青年大学习，找到任意发往 https://dxx.scyol.com/api/* 的请求，请求头中即有所需的 token|√|
|**pushplus_token**|[pushplus](https://pushplus.plus) 官网申请，免费微信消息推送|×|

## 推送效果
<img src="https://github.com/ooyq/dxx-helper/assets/120553430/798bf6ee-27bb-430c-aecc-2811e496bac67" height="500" width="300" />
