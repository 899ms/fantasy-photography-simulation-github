# Fantasy 摄影模拟

**FANTASY / 梵想美学 · 摄影与照片转译**

把地点与相机气质组织成同主题的摄影组图，每个地点独立成图，强调主图权重与现场关系。

**[快速开始](#start)** · **[下载与安装](#install)** · **[完整规则](fantasy-photography-simulation/SKILL.md)** · **[全部视觉 Skills](https://github.com/dacnay816y62-hub?tab=repositories)**

| 视觉示例 01 | 视觉示例 02 |
| :---: | :---: |
| ![Fantasy 摄影模拟 · 示例 1](examples/example-01.png) | ![Fantasy 摄影模拟 · 示例 2](examples/example-02.png) |

<a id="start"></a>

## 一分钟开始

| 你提供 | 这套 Skill 组织的交付 |
| --- | --- |
| 地点、题材、时间与相机气质 | 每个条目一张 3:4 摄影拼图，含 2–4 个同主题画面 |

```text
用 $fantasy-photography-simulation 做一张摄影组图：理光 GR 气质，雨后的街头与便利店灯光，地点是重庆山城步道。2–4 个画面围绕同一地点，主图要有明确权重。
```

**生成说明：** Skill 组织设计判断、提示词与执行流程；图片由当前环境中可用的图像工具生成或编辑。示例用于理解视觉方向，具体来源以本仓库记录为准，不能据此保证每次得到相同效果。

<a id="install"></a>

## 下载与安装

**[下载当前分支 ZIP](https://github.com/dacnay816y62-hub/fantasy-photography-simulation-github/archive/refs/heads/%E6%91%84%E5%BD%B1.zip)** · **[阅读 Skill 规则](fantasy-photography-simulation/SKILL.md)**

1. 下载并解压仓库。
2. 将仓库中的 `fantasy-photography-simulation/` 子文件夹放入当前助手支持的技能目录。
3. 安装文件夹命名为 **`fantasy-photography-simulation`**，确保入口是 `fantasy-photography-simulation/SKILL.md`。
4. 在支持技能调用的会话中使用 **`$fantasy-photography-simulation`**。如果列表未刷新，新开一个任务。

Codex CLI / IDE 的用户级目录是 `~/.agents/skills/`，项目级目录是 `.agents/skills/`；Windows 用户目录可写为 `%USERPROFILE%\.agents\skills\`。以 [OpenAI 官方安装说明](https://learn.chatgpt.com/docs/build-skills#where-codex-loads-local-skills) 为准。ChatGPT 与其他宿主请按各自的技能加载方式使用。

仓库名与调用名可能不同，以上以 `SKILL.md` 中的名称为准。安装不包含图像服务、账户或生成额度；实际出图取决于你使用的环境。

---

## What It Does

- 生成 `3:4` 竖版 AI 摄影拼图。
- 支持哈苏、徕卡、理光 GR 等不同相机气质。
- 支持编号批量输入，每个编号单独生成一张独立图片。
- 强制避免把多个地点混进同一张图。
- 优先表现地方生活、空间尺度、光线、材质和人物行为。
- 避免明信片视角、景点清单式 panel、高饱和旅游广告色和 AI 模特摆拍。

## Example Prompts

```text
徕卡 / 街头 / 北京胡同
哈苏 / 湖面与绿色 / 杭州西湖
理光 GR / 雨夜街头 / 重庆山城步道
```

批量输入：

```text
1、北京胡同
2、杭州西湖
3、重庆十八梯
4、大理洱海
5、敦煌沙洲夜市
```

## Repository Contents

- `fantasy-photography-simulation/` - 可安装的 Codex Skill 文件夹
- `fantasy-photography-simulation-skill-20260715.zip` - 打包好的 Skill 压缩包
- `examples/` - 示例输出图片

## Example Gallery

|  |  |  |  |
|---|---|---|---|
| ![](examples/example-01.png) | ![](examples/example-02.png) | ![](examples/example-03.png) | ![](examples/example-04.png) |
| ![](examples/example-05.png) | ![](examples/example-06.png) | ![](examples/example-07.png) | ![](examples/example-08.png) |
| ![](examples/example-09.png) | ![](examples/example-10.png) | ![](examples/example-11.png) | ![](examples/example-12.png) |
| ![](examples/example-13.png) | ![](examples/example-14.png) | ![](examples/example-15.png) | ![](examples/example-16.png) |

## Design Bias

The skill favors photobook-quality travel documentary photography:

- one dominant cover-grade main photo
- subdued saturation
- weighted shadows
- soft controlled highlights
- foreground occlusion
- edge crop
- layered depth
- off-center subjects

It explicitly avoids postcard aesthetics, tourism advertising, landmark checklists, high saturation, HDR texture, and generic stock-photo composition.

## FANTASY / 梵想美学

**让想象先被看见。** 将视觉判断与创作流程整理成可以继续使用的方法。

**[浏览全部视觉 Skills](https://github.com/dacnay816y62-hub?tab=repositories)** · [车窗里的风景](https://github.com/dacnay816y62-hub/window-scenery-skill) · [CINEMA DNA](https://github.com/dacnay816y62-hub/cinema-dna-21x9x3)
