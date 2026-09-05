# LuckyLob · 小岛漫游

3D 小岛游戏，支持电脑键盘、手机横竖屏、虚拟方向键、跳跃、LOB 金币、背景音乐与复古音效。

公开体验：[进入 LuckyLob 小岛](https://luckylob-playground.drneo.chatgpt.site)。可直接转发给朋友，无需 GitHub 账户。

## 完整项目源码

本仓库以 `luckylob-playground-source.zip` 交付完整、可重建的项目快照。下载并解压后，进入 `luckylob-playground` 文件夹：

```sh
npm ci
npm run dev
```

构建：`npm run build`。Node.js 版本至少 22.13。

压缩包包含完整 app/lib/components 源码、依赖锁、GLB 蒙皮角色、音乐与测试；根目录的 GLB 和 MP3 另作素材预览备份。原始项目快照：`8cf5e9cc320fade3a4319b2f875eac90ca69de1e`。

## 操作

- 电脑：WASD／方向键移动，空格跳跃，拖动旋转，滚轮缩放。
- 手机：左侧方向键、右侧跳跃键，可同时操作；单指拖动视角，双指缩放。
- 触碰金币 +1 LOB，24 秒后刷新；音乐、音效可分别开关。

试玩 ID 和 LOB 数量仅保存在当前浏览器、当前网址，不跨设备同步，不属于真实 LuckyLob 账户资产。音乐与角色素材按用户授权用于本项目，未另外授予第三方再分发许可。
