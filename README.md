# nano-tools · promo-assets

展示物料归档仓库。nano-tools 矩阵中所有**营销 / 展示类**素材集中收纳于此，
**不混入工具仓库或门户仓库**（门户 `WB` 只放导航运行所需文件，工具仓库只放单文件工具）。

## 目录结构

```
promo-assets/
├── wb/          # 来自 WB 门户仓的推广物料（已迁出不入库运行）
│   ├── all_tools_100.png      # 100 工具墙
│   ├── banner_wide.png        # 宽幅横幅
│   ├── compare_card.png       # 竞品对比卡
│   ├── flag_gallery.png       # 50 旗舰工具墙
│   ├── promo_poster.png       # 主海报
│   ├── promo_poster@2x.png    # 主海报 2x
│   ├── square_social.png      # 方形社交图
│   ├── strip_compact.png      # 紧凑条幅
│   ├── og.svg                 # social-preview.png 的生成源
│   └── promo_svg/             # Ardot 导出源 SVG
└── profile/     # 来自 GitHub Profile 仓的展示物料
    ├── banner.svg
    ├── nano-tools-poster.png
    ├── nano-tools-poster.svg
    ├── social-preview.png
    ├── toolmap.png
    └── brand/                 # 品牌资源（logo / landing / slides）
```

## 说明

- 这些素材由 Ardot（`fileId 708097978964338`）生成 / 导出。
- 门户 `WB` 仅保留被 `index.html` 实际引用的运行文件：
  `index.html` / `favicon.svg` / `social-preview.png` / `manifest.webmanifest` / `sw.js`
  / `README.md` / `LICENSE` / `.gitignore` / `_test.js`。
- Profile 仓仅保留被其 `README.md` 引用的 `profile_header.png` 与 `all_tools_100.png`。
- 所有对外推广图统一在此归档，便于复用与版本管理。
