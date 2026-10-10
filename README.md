# Urban Analytical Collage

把建筑、街景、景观、场地或历史照片转换成建筑作品集风格的分析拼贴、城市分析长带和历史时间轴。

它不是给整张照片套滤镜，而是先识别真实主体，再通过裁切、重复、尺度变化、黑白复印、建筑线稿、半调网点和少量水彩重新组织画面。

## 能做什么

- **概念拼贴**：适合单张建筑、景观或场地照片。
- **分析长带**：适合多张现场照片或城市空间分析。
- **历史时间轴**：适合带有明确日期或先后顺序的图片素材。
- 默认采用强风格化处理，同时保留主体的识别度和真实空间关系。
- 不虚构建筑、日期、数据或分析结论。

## 安装

### 从 GitHub marketplace 安装

```bash
codex plugin marketplace add 5Yuechang/urban-analytical-collage-skill
```

随后在 ChatGPT 桌面版或 Codex 的 Plugins Directory 中选择 **Urban Analytical Collage** 并安装。

### 从本地目录安装

下载并解压本仓库，然后运行：

```bash
codex plugin marketplace add /absolute/path/to/urban-analytical-collage-skill
```

重启桌面应用后，从 Plugins Directory 安装该插件。

## 使用

上传建筑、街景、场地、景观或历史照片，然后输入：

```text
$urban-analytical-collage 把这张照片做成建筑作品集分析拼贴
```

如果不指定模式，Skill 会根据输入自动选择概念拼贴、分析长带或历史时间轴。

## 推荐提示词

```text
将照片转换为建筑作品集风格的分析拼贴。保留主建筑、地形、人物和关键空间关系，但不要保留原照片的完整构图。把画面拆成5–9个有意义的片段，使用摄影剪贴、高反差复印、建筑线稿、半调网点和少量水彩叠加等至少三种处理方式。设置一个放大的主视觉，其余片段以不同尺度错位重组。

使用暖白或浅灰纸张背景，保留50–70%留白；整体以黑白灰为主，只加入一种低饱和强调色。用路径、等高线、剖切线或轨迹线组织画面。避免完整平铺原图、只做黑白滤镜、彩色手账感、虚假分析文字、Logo和水印。
```

## 仓库结构

```text
.
├── .agents/plugins/marketplace.json
├── plugins/urban-analytical-collage/
│   ├── plugin.json
│   └── skills/urban-analytical-collage/
│       ├── SKILL.md
│       ├── agents/openai.yaml
│       └── references/style-recipes.md
└── README.md
```

## 说明

- 生成结果会保留来源图片的事实主体，但不会保留原始摄影构图。
- 没有提供准确文字时，Skill 会留白或省略标签，不会编造分析文本。
- 请确保你有权使用和发布上传的图片。
