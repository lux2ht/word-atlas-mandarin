# Word Atlas Mandarin · 普通话学习图鉴

**A picture for every word. Character stories to remember. Playful pinyin practice.**

**一词一画，用字形故事帮助记忆，在游戏中学习拼音。**

Word Atlas Mandarin is a planned adaptation of [Word Atlas · 词光](https://github.com/designfuchen/word-atlas) for children learning Mandarin, especially a seven-year-old who is more comfortable in English. We want to bring its illustrated learning style to Mandarin with a new collection of words, pictures, pronunciation, and examples.

Word Atlas Mandarin 计划将 [Word Atlas · 词光](https://github.com/designfuchen/word-atlas) 的插画学习方式用于普通话启蒙，尤其面向英语更熟练的七岁儿童。我们希望围绕普通话重新编写词汇内容、制作图片、配备发音和例句，让孩子通过熟悉的英语理解中文。

> **Current status:** The application and bundled dataset still teach English IELTS vocabulary. The Mandarin vocabulary cards, character-history illustrations, and pinyin module described below are planned features. This README records the direction of the adaptation.
>
> **当前状态：** 应用和随附词库仍是原项目的雅思英语学习版本。下文介绍的普通话词卡、汉字演变插画和拼音模块均为计划功能。本 README 用于说明项目的改造方向。

## Learning goals / 学习目标

Start with a small, curated beginner collection built around a child's everyday life: family, animals, food, numbers, school, and nature. Use HSK vocabulary as a reference for selection and later expansion. The first release prioritizes useful, familiar words over completing an exam syllabus.

从少量精选的入门词汇开始，围绕孩子熟悉的家庭、动物、食物、数字、学校和自然等主题展开。参考 HSK 词汇选择内容，并为后续扩展保留分级依据。首个版本优先帮助孩子掌握常用、熟悉的词语，不以完成考试大纲为目标。

Use **simplified Chinese first**, with English explanations and instructions as a bridge. Keep sessions short, feedback encouraging, and activities approachable for a young learner. Build on the existing app's spaced review and progress tracking as Mandarin content becomes available.

以**简体中文为主**，用英语解释和操作提示帮助孩子理解。每次学习简短轻松，反馈以鼓励为主，活动适合儿童参与。随着普通话内容逐步加入，改造现有应用的间隔复习和学习进度功能。

## Planned learning experience / 计划中的学习体验

### 1. Illustrated vocabulary / 插画词汇

Create a Mandarin-specific illustration for every target word, keeping the warm, consistent visual style that makes Word Atlas appealing. Pictures should connect a word with a clear object, action, or everyday scene that a child can understand.

为每个目标词语制作专属的普通话学习插画，延续 Word Atlas 温暖、统一的视觉风格。图片将词义与清楚的物体、动作或生活场景联系起来，帮助孩子看图理解。

Each planned word card brings together:

- Simplified characters and standard pinyin with tone marks.
- A clear English meaning and a child-friendly illustration.
- Mandarin pronunciation, with slow playback for beginners.
- A short Mandarin example with pinyin and an English translation.
- Simple picture matching, listening, and recall activities.

每张计划中的词卡包含：

- 简体汉字与带声调符号的规范拼音。
- 清楚的英语释义和适合儿童的插画。
- 普通话发音，以及适合初学者的慢速播放。
- 简短的中文例句、例句拼音和英语翻译。
- 看图配对、听音辨词和回忆练习。

### 2. Character stories and evolution / 汉字故事与字形演变

Help children remember characters by showing how their shapes developed. Where reliable references are available, use an illustrated sequence connecting the original subject or idea, documented earlier written forms, and the modern simplified character. Characters such as 日, 山, and 木 are useful starting points. Include older or traditional forms where they help explain the history.

通过展示字形的发展过程，帮助孩子记住汉字。在有可靠资料支持时，用连续插画连接最初描绘的事物或表达的概念、有记载的早期字形，以及现代简体字。可以从日、山、木等字入手，在有助于理解演变过程时展示古文字或繁体字形。

Some Chinese characters began as pictographs; many others combine components that suggest meaning and pronunciation. Explain those components in simple language too. For words made of several characters, distinguish each character's history from the meaning of the whole word.

一部分汉字起源于象形，许多汉字则由提示意义和读音的部件构成。也要用简单的语言解释这些部件。对于由多个汉字组成的词语，分别介绍单字的来历和整个词语的意思。

Historical illustrations must cite their sources. Creative memory stories can help where a historical explanation is unavailable or too complex, but must be labeled as **memory aids**, separate from documented character history. Generated artwork must follow reviewed reference material, and uncertain origins should remain identified as uncertain.

字形演变插画需要注明资料来源。当历史解释缺乏可靠依据或过于复杂时，可以提供创意记忆故事，但必须标明是**记忆辅助**，与有据可查的汉字历史区分开来。生成的图片应以经过审校的参考资料为依据，对尚无定论的字源保留说明。

### 3. Pinyin practice / 拼音练习

Add a separate pinyin learning module that connects sounds with familiar vocabulary:

- Initials (声母), finals (韵母), and combining them into syllables.
- The four tones and the neutral tone, with clear audio and visual tone contours.
- Listening and repetition, sound-to-pinyin matching, and tone recognition games.
- Short practice sessions that lead back to words the child is learning.

新增独立的拼音学习模块，把发音练习与熟悉的词汇联系起来：

- 学习声母、韵母，以及如何拼成音节。
- 通过清晰的示范音频和声调曲线，认识四声和轻声。
- 通过听读、跟读、听音选拼音和辨别声调等游戏进行练习。
- 每次安排简短练习，并与孩子正在学习的词语相互关联。

## Content sources and review / 内容来源与审校

[Chinese Word Atlas by scoresby13](https://github.com/scoresby13/chinese-word-atlas) is a candidate starting point for HSK vocabulary. It provides [JSON and CSV datasets](https://github.com/scoresby13/chinese-word-atlas/tree/main/data). Official HSK vocabulary resources and reputable dictionaries may also guide selection and verification. Imported or generated content needs review before becoming part of the children's curriculum.

[scoresby13 的 Chinese Word Atlas](https://github.com/scoresby13/chinese-word-atlas) 是 HSK 词汇的候选来源，提供 [JSON 和 CSV 词库](https://github.com/scoresby13/chinese-word-atlas/tree/main/data)。也可以参考官方 HSK 词汇资料和可靠词典进行选词与核对。导入或生成的内容需要经过审校，再纳入儿童学习内容。

Before adding content:

- Check simplified forms, English meanings, pinyin, pronunciation, examples, and suitability for children.
- Record the source, the HSK edition and level where applicable, and any modifications; verify coverage before making claims about it.
- Check reuse permissions before importing text, images, or audio, and retain required attribution. New distributed content must meet the repository's CC BY 4.0 contribution requirements.
- Use reliable character-history references, with documented history and invented mnemonics clearly distinguished.

加入内容前需确认：

- 核对简体字形、英语释义、拼音、发音、例句，以及内容是否适合儿童。
- 记录来源、适用的 HSK 版本与级别，以及所做的修改；核实覆盖范围后再作说明。
- 导入文字、图片或音频前确认使用许可，并保留所需署名。新增的分发内容须符合仓库关于 CC BY 4.0 的贡献要求。
- 汉字演变采用可靠资料，并明确区分有据可查的历史与创作的记忆口诀或故事。

## Roadmap / 开发路线

All milestones below are planned. The first goal is a useful beginner experience; broader HSK coverage follows after the learning approach has been tried with a child.

以下阶段均为计划。首先做出适合儿童使用的入门体验，再根据实际学习反馈扩展 HSK 内容。

| Milestone | Planned outcome | 阶段目标 |
| :--- | :--- | :--- |
| **1. Beginner atlas / 入门图鉴** | Select everyday words using HSK as a reference; create and review Mandarin word cards, illustrations, audio, and bilingual examples. | 参考 HSK 精选生活词汇，制作并审校普通话词卡、插画、音频和双语例句。 |
| **2. Characters and sounds / 字形与读音** | Add sourced character-story illustrations and the separate pinyin practice module, linked to the beginner vocabulary. | 加入有资料依据的汉字故事插画和独立拼音练习模块，与入门词汇关联。 |
| **3. Grow and review / 扩展与复习** | Expand HSK coverage gradually and adapt FSRS spaced review and the vocabulary galaxy to track Mandarin learning. | 逐步扩大 HSK 词汇覆盖，改造 FSRS 间隔复习和词汇星图，记录普通话学习进度。 |

## Existing foundation and visual reference / 现有基础与风格参考

The current Word Atlas foundation includes illustrated English vocabulary cards, UK/US audio, recall activities, FSRS spaced repetition, and a vocabulary galaxy. Progress is stored locally without an account, with backup export and import. These are foundations to adapt for Mandarin.

现有 Word Atlas 基础包含英语插画词卡、英美发音、回忆练习、FSRS 间隔复习和词汇星图。学习进度保存在本地，无需账号，并支持备份导出与导入。这些能力将作为普通话版本的改造基础。

The screenshot and demo links below show the **original English-learning project**, providing a visual reference for this adaptation. The hosted original may differ from the repository edition.

下方截图和演示链接展示的是**原版英语学习项目**，作为本项目的视觉参考。原项目在线版本可能与仓库版本有所不同。

![Original Word Atlas English vocabulary atlas / 原版 Word Atlas 英语词汇图鉴](docs/assets/atlas-desktop.jpg)

[Original website / 原项目网站](https://0xlei.tech/words/) · [Original introduction video / 原项目宣传片](docs/assets/launch.mp4)

The bundled [JSON](data/word-atlas.json) and [CSV](data/word-atlas.csv) still contain English vocabulary. The [dataset documentation](docs/dataset.md), [generation pipeline](docs/pipeline.md), and [learning model](docs/learning-model.md) describe the existing foundation. Existing text and illustrations were generated using AI, with speech synthesized using ElevenLabs; the collection has not been manually reviewed entry by entry.

随附的 [JSON](data/word-atlas.json) 和 [CSV](data/word-atlas.csv) 仍为英语词库。[词库说明](docs/dataset.md)、[内容生成流程](docs/pipeline.md)和[记忆模型](docs/learning-model.md)介绍的是现有基础。现有文字和插画由 AI 生成，语音使用 ElevenLabs 合成，整套内容尚未逐条人工审校。

## Local development / 本地开发

Requires **Node.js 20+** and npm. The repository includes the original image and audio collection, so the first download may take time. These commands start the current English-learning app.

需要 **Node.js 20+** 和 npm。仓库包含原项目的图片与音频，首次下载可能较久。以下命令启动的是当前的英语学习应用。

```bash
git clone --depth 1 https://github.com/lux2ht/word-atlas-mandarin.git
cd word-atlas-mandarin
npm ci
npm run dev
```

Open / 打开 **[http://localhost:5188](http://localhost:5188)**。

```bash
npm test             # Unit tests / 单元测试
npm run check:atlas  # Dataset and media validation / 词库结构与媒体校验
npm run build        # Production build in dist/ / 构建到 dist/
```

For deployment under a subpath, use `ATLAS_BASE=/words/ npm run build`. See the [deployment guide](docs/deployment.md).

子路径部署使用 `ATLAS_BASE=/words/ npm run build`，详见[部署文档](docs/deployment.md)。

**Stack / 技术栈:** React 19 · TypeScript · Vite · ts-fsrs · WebGL2

## Contributing / 参与贡献

Contributions to the Mandarin direction are welcome: selecting beginner vocabulary, reviewing pinyin and examples, finding reliable character-history references, and developing illustrations and learning activities. For content corrections, include the word or character, the issue, the proposed correction, and a reliable source.

欢迎围绕普通话学习方向参与贡献，包括精选入门词汇、审校拼音与例句、寻找可靠的字形演变资料，以及设计插画和学习活动。提交内容纠错时，请附上词语或汉字、具体问题、修改建议和可靠依据。

[Report an issue / 报告问题](https://github.com/lux2ht/word-atlas-mandarin/issues) · [Contribution guide / 贡献指南](CONTRIBUTING.md) · [Security policy / 安全政策](SECURITY.md)

## Credits and licensing / 致谢与授权

This adaptation builds on [Word Atlas · 词光](https://github.com/designfuchen/word-atlas), created by [@designfuchen](https://github.com/designfuchen). Thanks to the original contributors for the illustrated learning experience and open-source foundation, and to [scoresby13/chinese-word-atlas](https://github.com/scoresby13/chinese-word-atlas) for sharing a potential Mandarin vocabulary source.

本项目基于 [@designfuchen](https://github.com/designfuchen) 创建的 [Word Atlas · 词光](https://github.com/designfuchen/word-atlas)。感谢原项目贡献者提供插画学习体验和开源基础，也感谢 [scoresby13/chinese-word-atlas](https://github.com/scoresby13/chinese-word-atlas) 分享可供参考的普通话词汇资源。

| Scope / 范围 | License / 许可 |
| :--- | :--- |
| Application code / 应用代码 | [MIT](LICENSE) |
| Existing vocabulary text, illustrations, and word recordings / 现有词库文本、插画与词条录音 | [CC BY 4.0](CONTENT_LICENSE.md); attribution / 署名：`Word Atlas contributors — CC BY 4.0` |
| Third-party dependencies and fonts / 第三方依赖与字体 | Their respective licenses / 遵循各自许可 |

Preserve attribution and license links, and identify modifications when reusing content. Check each new source's terms before incorporating it into the Mandarin collection.

复用内容时，请保留署名和许可链接，并说明所做的修改。将新来源纳入普通话词库前，请逐项确认其授权条款。
