# Ecommerce AIGC Skill / 电商 AIGC Skill

A bilingual Codex skill for generating ecommerce posters, hero banners, visual directions, and image-generation prompts in one unified whitespace product layout.

本仓库提供中英文双语 Codex Skill，用统一的留白产品版式生成电商海报、商品首屏、视觉方案和图像提示词。

## Files / 文件结构

```text
ecommerce-aigc/
├── SKILL.md                                  # English skill entrypoint
├── SKILL.zh-CN.md                            # 中文 Skill 入口
├── agents/
│   └── openai.yaml                           # UI metadata / 界面元数据
└── references/
    ├── region-visual-language.md             # English visual-language reference
    └── region-visual-language.zh-CN.md       # 中文视觉语言 reference
```

## Core visual invariant / 核心视觉约束

Every output uses:

- a continuous light low-interference base;
- one complete medium-to-large product;
- a separate copy zone;
- one restrained modern sans-serif family;
- exactly one complete flat solid `1:1` circle behind the product;
- soft diffuse lighting and a realistic contact shadow;
- no people, rooms, props, or literal lifestyle scene.

所有输出统一使用：

- 连续的浅色低干扰基础底色；
- 一个完整、中至大比例的商品；
- 与商品完全分离的文字区；
- 一套克制的现代无衬线字体；
- 商品背后唯一一个完整、平面、实色、严格 `1:1` 的二维正圆；
- 柔和漫射光与真实接触阴影；
- 不出现人物、房间、道具或真实生活场景。

## Usage / 使用方式

Use `ecommerce-aigc/SKILL.md` as the standard Codex entrypoint. It routes to the English reference. Chinese readers may use `ecommerce-aigc/SKILL.zh-CN.md`, which routes to the complete Chinese reference.

将 `ecommerce-aigc` 文件夹放入 Codex skills 目录。英文环境以 `SKILL.md` 为标准入口；中文环境可直接阅读 `SKILL.zh-CN.md`，并使用对应中文 reference。

The language variants describe the same design system. They are maintained as parallel documents rather than mixed line by line, keeping prompts readable and easy to copy.

两个语言版本描述同一套设计系统，采用独立文件而非逐行混排，便于阅读、复制和后续维护。
