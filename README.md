# 时空猫 · 免费在线工具

四个自己做的网页工具，**全部在浏览器里运行**：不用注册、不用安装，文件不上传。

| 工具 | 能干什么 | 地址 |
|---|---|---|
| 实时字幕翻译 | 麦克风 / 标签页音频 → 浏览器内识别 + 英中双语字幕，支持画中画悬浮窗 | https://translate.cosmocat.dev/ |
| 在线工具箱 | PDF、图片、开发小工具，9 款网页版，点开即用 | https://tools.cosmocat.dev/ |
| Craft 工具站 | 海报 / PDF / 矢量图的开源「平替」导航，标注在线可用与实测结论 | https://craft.cosmocat.dev/ |
| 开源游戏站 | 五子棋（AI 对手）/ 数独 / 2048 / 扫雷 / 俄罗斯方块，免下载 | https://games.cosmocat.dev/ |

## 为什么做成「浏览器内运行」

- **隐私**：音频、图片、PDF 不出本机，服务端拿不到你的文件。
- **免费**：算力用你自己的电脑，所以没有时长限制、没有会员墙。
- **代价也说清楚**：首次要下载模型；性能依赖设备；精度不如大厂云服务。

## 相关阅读

- 在线字幕翻译是怎么做出来的（含实测与边界）：https://cosmocat.dev/ai/posts/2026-10-24-browser-realtime-translation
- 博客主站：https://cosmocat.dev/

## 开源与致谢

在线字幕翻译基于 MIT 开源的 [AudioScript](https://github.com/niyongsheng/AudioScript) 生态，用 transformers.js + ONNX Runtime 在浏览器内复刻；游戏来自各自开源项目，版权归原作者。
