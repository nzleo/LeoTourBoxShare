# TourBox Presets

TourBox `.tb` 预设归档。按**应用**和**版本**存放，可随使用习惯迭代更新。

同一作者的其他开源 → [LeoMDReader](https://nzleo.github.io/LeoMDReader/) · [Leo 风扇控制](https://nzleo.github.io/LeoMacFanControl/)

- 介绍页：https://nzleo.github.io/LeoTourBoxShare/
- 官方下载：[TourBox Preset](https://www.tourboxtech.com/oap/presets/?presetShareId=1282502239801446400)

## Leo 开源系列

| 项目 | 说明 |
| --- | --- |
| [TourBox × ChatGPT / Codex](https://nzleo.github.io/LeoTourBoxShare/) | TourBox 键位预设分享（本仓库） |
| [LeoMDReader](https://nzleo.github.io/LeoMDReader/) | 轻量 Markdown 阅读 / 编辑 |
| [Leo 风扇控制](https://nzleo.github.io/LeoMacFanControl/) | macOS 菜单栏温控 |

## 目录结构

```text
presets/
  <应用名>/
    <版本号>/
      *.tb
      README.md
docs/          # GitHub Pages 介绍页
```

## 当前预设

| 应用 | 版本 | 说明 | 官方分享 |
| --- | --- | --- | --- |
| [ChatGPT](presets/ChatGPT/) | [1.0.0](presets/ChatGPT/1.0.0/) | ChatGPT / Codex：模型、推理强度、活跃任务、审批、语音 | [打开](https://www.tourboxtech.com/oap/presets/?presetShareId=1282502239801446400) |

## 使用方式

1. 进入对应应用目录，下载目标版本的 `.tb` 文件  
2. 打开 TourBox Console → 预设列表 → 导入  
3. 按自己的快捷键与手感微调  

## 版本约定

- 同一应用下，数字版本递增（如 `1.0.0` → `1.1.0`）
- 大改键位或面向新软件能力时升主/次版本；小修快捷键升修订号
- 旧版本保留，方便回退
