# Seekly

Seekly 是 [NodeSeek](https://www.nodeseek.com) 社区的**非官方第三方 iOS 客户端**，与 NodeSeek 官方没有任何隶属关系。帖子、评论等内容均来自站点，版权归原作者所有。

本仓库只发布打包好的 IPA，下载见 [Releases](../../releases)。最低支持 iOS 16.0。

## 两个版本怎么选

| 文件 | 签名 | 适合谁 |
| --- | --- | --- |
| `Seekly-<版本>-unsigned.ipa` | 无签名 | 绝大多数人。用 TrollStore、AltStore / SideStore、Sideloadly、爱思助手或自己的证书签名后安装。 |
| `Seekly-<版本>-adhoc.ipa` | 开发者 Ad Hoc 签名 | 仅限已登记 UDID 的设备，其他设备装不上。 |

### 无签名版安装

- **TrollStore**：直接用 TrollStore 打开 IPA 安装，永久有效。
- **AltStore / SideStore / Sideloadly**：用自己的 Apple ID 签名安装。免费 Apple ID 签的包 7 天后需要重签。
- **自有证书**：用任意签名工具重签即可。

重签后 Bundle ID 或 App Group 可能被签名工具改掉，桌面小组件可能读不到主 App 的数据，这不影响 App 本身使用。

## 隐私

App 不含任何统计、广告或追踪 SDK，开发者没有服务器。登录在 NodeSeek 自己的网页中完成，App 不读取、不存储账号密码。
