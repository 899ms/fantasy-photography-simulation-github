# fantasy-photography-simulation

`fantasy-photography-simulation` 是一个 Codex Skill，用于把地点、题材、相机气质或编号列表转成 AI 摄影组图提示与出图流程。

它的目标不是生成旅游宣传照或单张风景海报，而是生成带有摄影集叙事感的竖版拼图：每张图由 2-4 个同地点、同主题、同调色的摄影 panel 组成，并强调主图权重、暗部层次、真实现场感和克制色彩。

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

## Install

把整个 `fantasy-photography-simulation/` 文件夹复制到你的 Codex skills 目录中，或解压：

```text
fantasy-photography-simulation-skill-20260715.zip
```

压缩包和可安装目录都包含在本仓库中。

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
