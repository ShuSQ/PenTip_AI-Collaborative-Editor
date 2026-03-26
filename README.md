#  ✒️ **笔头PenTip**

>笔头PenTip是一款桌面端 Markdown 编辑器，
>为一种新的写作方式而设计，
>让思考、描述与优化，在同一个流动的过程中自然发生
>AN editor shaped by vibe coding.
>Think. Write. Evolve.

![video](https://github.com/user-attachments/assets/2291924d-90e7-4b90-811a-c72b97b64f03)

## 📦 安装使用

Download the latest version:
- macOS: [PenTip-0.1.0-macos-arm64.dmg](https://github.com/ShuSQ/PenTip_AI-Collaborative-Editor)
- Or build from source:

```bash
git clone https://github.com/ShuSQ/PenTip_AI-Collaborative-Editor.git
cd pentip

⚡ Quick Start
1. Open or create a markdown file  
2. Start writing  
3. Talk to AI directly in your document 
```

**当前仅支持在Apple M 芯片（Apple Silicon M-series）设备上运行。**

<img width="1282" height="860" alt="15na0b9-pentip_screenShot" src="https://github.com/user-attachments/assets/5e0ed449-8257-475e-88e9-a23c3df32e3a" />


不同于在编辑器与 AI 对话之间来回切换，PenTip 将 AI 融入写作本身，让你的想法在书写过程中自然生长。


## **✨ 为什么是 PenTip**

写作不仅是文字，更是思考的过程。
想法往往是不完整的、零散的、不断变化的。

PenTip 的目标，是支持这个过程，而不是打断它。保持专注，不被打断，在同一个空间里思考与写作，让想法在形成过程中持续演进。

## **⚡ 核心能力**

**1.✍️ AI 协作写作**

应用内嵌了模型对话能力，可以通过右下角的会话唤起，直接与AI在文档汇中写作，完成更多的事情。
提问、扩展、优化、重构，无需离开编辑器；

<img width="1320" height="860" alt="1nkatxy-模型支持" src="https://github.com/user-attachments/assets/6f6e044a-4959-4779-bf2d-e2bc2ef87c3a" />

支持选中关键词句高亮，引用要点与模型展开更聚焦的讨论和优化：

<img width="1320" height="860" alt="aj5jff-选词喂给AI" src="https://github.com/user-attachments/assets/9e9ee031-a1b2-433a-a7ea-da41cc78a58f" />

不同的模型都可以作为写作者，所有思考和会话，都会基于上下文来做展开和有深度的进行。

**提供多种模型：**

提供从开箱即用到深度自定义的灵活模型方案：默认即可食用DeepSeek Chat；也可下载本地小模型，或通过API接入常用的云端模型，以适应不同场景的需求。

* `DeepSeek Chat`默认开箱即用；
* `Qwen2.5 3B` `Llama3.2 3B` `DeepSeek R1 Local`可下载本地模型；
* `GPT-5.4` `Gemini 3 pro` `Gemini 3 flash`等可配API自定义接入模型；

<img width="213" height="322" alt="1ngv74r-模型选择列表" src="https://github.com/user-attachments/assets/31a7cbb3-ce76-4c1a-8943-5db514ec4965" />



**2.🧩Skills能力支持**

把“思考方式”变成“可复用能力”。从 skills.sh 一键添加能力，支持自定义、修改与沉淀，将高频思考转化为工具。

<img width="240" height="284" alt="l17mni-发现skill" src="https://github.com/user-attachments/assets/74d37ee3-a29d-496a-b143-b92d079fb954" />


同时支持"/"快捷能力。在写作过程中，随时调用能力完成单个语句任务，而不需要绑定全局的Skill生效场景，用完即走，一切自然发生。

<img width="210" height="320" alt="108el4q-slash面板" src="https://github.com/user-attachments/assets/e79c1745-34bb-43c4-a5e4-248fc1d3078a" />

无需切换模式，一切自然发生。

**内置8款skills助力协作：**

通过内置Skill满足创作中的快速输入需求，并提供轻量管理能力，让会话更灵活、更高效。


<img width="213" height="322" alt="7fuzw-添加skill" src="https://github.com/user-attachments/assets/1a19542e-d22b-43bc-8718-5deba4656b5d" />


**3.📝原生 Markdown**

简洁、结构化的写作体验。支持markdown语法， `.md` 文件的查看、编辑与导出，以及图片和视频格式内容的插入。

**4.🌗基础体验**

在更多的细化场景中，进行了体验的打磨和改进：
- Status Item，更快开始，更快启动；
  
<img width="150" height="183" alt="xoinf3-statusbar" src="https://github.com/user-attachments/assets/b0599dfa-99bd-4017-a112-f0c78a7f3db0" />

- 自动保存，不会丢失任何的关键改动；

- 历史记录，总是可以找到打开过的文档；
  
<img width="1320" height="860" alt="1q995ix-历史记录" src="https://github.com/user-attachments/assets/49a24ada-57b9-414e-9956-6e1310658ab8" />

- Snapshot，可以通过关键对比洞察文档变化，随时会滚到改动前的版本；
  
<img width="1320" height="860" alt="m2clz2-snapshot" src="https://github.com/user-attachments/assets/1981b14e-6321-4430-92b0-85a87118cb06" />

- 深浅色适配，提供夜间视力友好的输入界面；
  
<img width="1320" height="860" alt="1rjmfl5-深色模式" src="https://github.com/user-attachments/assets/9dbff6de-9ee9-4e80-af13-12f63208a3fb" />

- 会话式创建，直接从一句话描述灵感开始，剩下的交给模型展开；
  
<img width="1320" height="860" alt="i0ptt3-会话式创建" src="https://github.com/user-attachments/assets/509dcfe7-1896-4b61-8c76-91a0135c3afe" />

- 口袋模式，无需markdown预览对照，直接编辑预览效果，所见即所编辑；
  
<img width="660" height="860" alt="x5jis4-口袋模式" src="https://github.com/user-attachments/assets/d64b2d04-f078-4fdf-90ac-3e82c462a526" />

- 即使模型不断演进，我们依然希望保留一种有生命力的体验，并通过NOMONO的状态去连接这一切。

https://github.com/user-attachments/assets/d005cc7e-c339-4482-9f3b-bc368d2cada4



大多数工具，帮助你润色已经清晰的想法。PenTip 希望帮助你发现那些尚未成形的想法。让思考不断延展，创意持续发生。




