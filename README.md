# 主题包下载

300 个 Shopify 主题包，按标签分成 4 组，每人 75 个（原有 25 个 + 新增 50 个）。

打开 **index.html**（或 GitHub Pages 地址），选自己的标签，下载对应的主题包。

| 标签 | 主题范围 | 数量 |
| --- | --- | --- |
| cqz | theme31 – theme55、theme131 – theme180 | 75 |
| hyl | theme56 – theme80、theme181 – theme230 | 75 |
| lh  | theme81 – theme105、theme231 – theme280 | 75 |
| mcy | theme106 – theme130、theme281 – theme330 | 75 |

## 怎么用

1. 打开下载页，点自己标签下的「下载 themeXX.zip」
2. Shopify 后台 → 在线商店 → 主题 → 添加主题 → 上传 zip 文件

每个包都是完整的 427 个文件，根目录为 `layout/theme.liquid`，可直接上传，不需要解压再打包。

## 每个主题的差异

所有主题共用同一套模板文件（sections / snippets / layout 完全一致），只有下面这些不同：

- `config/settings_data.json` — 配色、字体、页宽、圆角、区块间距、阴影
- `sections/header-group.json` — 顶部公告条与滚动条文案
- `templates/index.json` — 首页区块里写死的 5 个配色值（区块顺序完全一致）
- `assets/local-*.jpg` — 6 张配图（每个主题都不一样）

支付相关配置（购物车抽屉、结账按钮、支付图标等 127 项）全部保持一致，未做任何改动。

## 配色

300 个主题使用 300 套互不重复的配色：

- theme31 – theme130：20 个色相 × 5 个深度
- theme131 – theme330：40 个色相 × 5 个深度（与上一批零重复）

字体、页宽、圆角、区块间距、阴影在 10 套字体与多档形状参数间轮换。
