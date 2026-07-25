# 浮光艺志 | Chronicle of Artistry

> 偏向历史叙事与时间沉淀的感觉。分析汇总各种艺术风格，以 Markdown 为主进行体系化架构与链接。

## 项目定位

一个体系化的艺术风格知识库，按时间线、地域、媒介等多维度梳理人类艺术史中的主要风格与流派，配合图片资料进行视觉化呈现。

## 目录结构

```
Chronicle-of-Artistry/
├── README.md                    # 项目总览与导航
├── TIMELINE.md                  # 艺术史总时间线（快速索引）
├── assets/                      # 图片与媒体资源
│   ├── covers/                  # 各风格封面图
│   └── artworks/                # 代表作品图片（按风格子目录）
│
├── 01-ancient/                  # 古代艺术 (史前 – 5世纪)
│   ├── README.md
│   ├── prehistoric.md           # 史前艺术
│   ├── egyptian.md              # 古埃及艺术
│   ├── greek.md                 # 古希腊艺术
│   └── roman.md                 # 古罗马艺术
│
├── 02-medieval/                 # 中世纪艺术 (5世纪 – 14世纪)
│   ├── README.md
│   ├── byzantine.md             # 拜占庭艺术
│   ├── romanesque.md            # 罗马式艺术
│   └── gothic.md                # 哥特式艺术
│
├── 03-renaissance/              # 文艺复兴 (14世纪 – 16世纪)
│   ├── README.md
│   ├── early-renaissance.md     # 早期文艺复兴
│   ├── high-renaissance.md      # 盛期文艺复兴
│   └── mannerism.md             # 风格主义
│
├── 04-baroque-rococo/           # 巴洛克与洛可可 (17世纪 – 18世纪中叶)
│   ├── README.md
│   ├── baroque.md               # 巴洛克
│   └── rococo.md                # 洛可可
│
├── 05-neoclassicism-romanticism/ # 新古典主义与浪漫主义 (18世纪末 – 19世纪中叶)
│   ├── README.md
│   ├── neoclassicism.md         # 新古典主义
│   └── romanticism.md           # 浪漫主义
│
├── 06-modern-19c/               # 19世纪现代萌芽
│   ├── README.md
│   ├── realism.md               # 现实主义
│   ├── impressionism.md         # 印象派
│   ├── post-impressionism.md    # 后印象派
│   ├── neo-impressionism.md     # 新印象派 / 点彩派
│   ├── symbolism.md             # 象征主义
│   ├── pre-raphaelite.md        # 前拉斐尔派
│   └── art-nouveau.md           # 新艺术运动
│
├── 07-modern-20c/               # 20世纪现代主义
│   ├── README.md
│   ├── fauvism.md               # 野兽派
│   ├── expressionism.md         # 表现主义
│   ├── cubism.md                # 立体主义
│   ├── futurism.md              # 未来主义
│   ├── dada.md                  # 达达主义
│   ├── surrealism.md            # 超现实主义
│   ├── abstract.md              # 抽象艺术 (康定斯基 / 蒙德里安)
│   ├── abstract-expressionism.md # 抽象表现主义
│   ├── pop-art.md               # 波普艺术
│   ├── minimalism.md            # 极简主义
│   ├── conceptual-art.md        # 概念艺术
│   ├── op-art.md                # 欧普艺术
│   └── bauhaus.md               # 包豪斯
│
├── 08-postmodern-contemporary/  # 后现代与当代 (1960s – 至今)
│   ├── README.md
│   ├── postmodernism.md         # 后现代主义
│   ├── installation.md          # 装置艺术
│   ├── performance.md           # 行为艺术
│   ├── land-art.md              # 大地艺术
│   ├── neo-expressionism.md     # 新表现主义
│   ├── digital-art.md           # 数字艺术
│   ├── street-art.md            # 街头艺术
│   └── ai-art.md                # AI 生成艺术
│
├── 09-eastern/                  # 东方艺术体系
│   ├── README.md
│   ├── chinese-traditional.md   # 中国传统绘画（工笔/写意/山水/花鸟）
│   ├── chinese-modern.md        # 中国近现代艺术
│   ├── japanese.md              # 日本艺术（浮世绘/琳派/侘寂）
│   ├── korean.md                # 韩国艺术
│   ├── indian.md                # 印度艺术
│   └── islamic.md               # 伊斯兰艺术
│
├── 10-cross-cutting/            # 跨时代主题专题
│   ├── README.md
│   ├── color-theory.md          # 色彩理论演变
│   ├── composition.md           # 构图法则
│   ├── medium-evolution.md      # 媒介演变（壁画→油画→数字）
│   ├── patronage.md             # 赞助体系与艺术市场
│   └── women-in-art.md          # 女性艺术家
│
├── 11-millennium-nostalgia/     # ★ 千禧怀旧美学（重点章节）
│   ├── README.md
│   ├── y2k.md                   # Y2K 千禧未来风
│   ├── vaporwave.md             # 蒸汽波
│   ├── synthwave.md             # 合成器浪潮 / Retrowave
│   ├── frutiger-aero.md         # Frutiger Aero 水晶拟物风
│   ├── dreamcore-weirdcore.md   # 梦核与怪核 / 阈限空间
│   └── acid-graphics.md         # 酸性设计
│
└── references/                  # 参考资料与外部链接
    ├── books.md                 # 推荐书目
    ├── museums.md               # 博物馆与在线资源
    └── glossary.md              # 术语表
```

## 每篇风格文档模板

每个 `.md` 风格文件建议包含以下结构：

```markdown
# 风格名称 (英文名)

## 概述
- 时间跨度：
- 发源地：
- 核心理念：

## 历史背景
（社会、政治、技术背景）

## 视觉特征
- 色彩：
- 构图：
- 笔触/技法：
- 题材：

## 代表艺术家与作品
| 艺术家 | 代表作 | 年代 | 图片 |
|--------|--------|------|------|
|        |        |      |      |

## 影响与传承
（对后续流派的影响）

## 图片画廊
<!-- 放置在 assets/artworks/风格名/ 下 -->

## 延伸阅读
- [链接]()
```

## 分类维度

本项目采用多维度交叉索引：

| 维度 | 说明 |
|------|------|
| **时间线** | 按历史时期纵向排列（主线） |
| **地域** | 西方 / 东方 / 非洲 / 美洲 |
| **媒介** | 绘画 / 雕塑 / 建筑 / 摄影 / 数字 |
| **主题** | 宗教 / 肖像 / 风景 / 静物 / 抽象 |
| **手法** | 写实 / 表现 / 抽象 / 象征 / 装饰 |

## 图片管理约定

- 图片统一存放在 `assets/` 目录下
- 封面图：`assets/covers/{style-name}.jpg`
- 作品图：`assets/artworks/{style-name}/{artist}-{work}.jpg`
- 文档内使用相对路径引用：`![alt](../assets/artworks/...)`
- 大图建议控制在 1MB 以内，缩略图 200KB 以内

## 进度追踪

- [x] 项目架构设计
- [ ] 古代艺术章节
- [ ] 中世纪艺术章节
- [ ] 文艺复兴章节
- [ ] 巴洛克与洛可可章节
- [ ] 新古典主义与浪漫主义章节
- [ ] 19世纪现代萌芽章节
- [ ] 20世纪现代主义章节
- [ ] 后现代与当代章节
- [ ] 东方艺术体系章节
- [ ] 跨时代主题专题

---

## 作者

**李平江** (Pingjiang Li)

## 许可证

本项目采用 [MIT License](LICENSE) 开源。

---

*浮光掠影，艺志千年。*
