# Shadowrocket CN Fast Rule

人在国内使用 Shadowrocket 时，很多老规则又大又慢，开着代理后容易出现国内 App 卡、国外网页慢、图片加载半天、内容发不出去的问题。

这套规则是轻量分流版本：国内和局域网直连，常见海外服务走代理，未知海外流量兜底走代理，再加一层轻量去广告。日常刷微信、抖音、淘宝、Chrome、Google、GitHub、YouTube 等场景会更顺一些。

## 下载地址

iPhone 直接打开下面这个链接：

https://raw.githubusercontent.com/401821988qqcom-svg/shadowrocket-cn-fast-rule/main/Shadowrocket_CN_Fast_AdBlock.conf

## 使用方法

1. 在 iPhone 上打开上面的下载链接。
2. 保存或复制为 `.conf` 配置文件。
3. 在 Shadowrocket 里导入配置。
4. Shadowrocket 首页把「全局路由」设置为「配置」，不要选「代理」。

## 规则特点

- 国内网站、国内 App、局域网直连，减少绕路。
- 海外内容默认走代理，避免国外网站漏走直连。
- 使用轻量广告规则，减少误伤和卡顿。
- 文件很小，不用 10MB+ 的老黑名单。

## 注意

YouTube App 内的视频广告通常无法只靠 Shadowrocket 域名规则完全拦截，因为广告和视频内容经常共用相近域名或同一套分发链路。
