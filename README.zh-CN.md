# Awesome Claude Design Skills

[English](README.md)

给 **Claude Code、Codex 等编程 agent 用的开源设计 skill 和工具**:UI 与前端美化、设计系统、Figma 与设计工具 MCP、设计稿转代码、海报与品牌图。共 203 个仓库,每个都由 [Agent Skills Hub (agentskillshub.top)](https://agentskillshub.top) 读过 README 并做了安全评级。

带类型筛选的在线页面:**[https://agentskillshub.top/best/ai-design/](https://agentskillshub.top/best/ai-design/)** · 每 8 小时刷新

## 到底装哪个

我们实跑了其中 10 个(10 个出了结果),结论如下。[完整实测结果](#tested)在下面。

- 🥇 **想要不撞脸的设计: [taste-skill](https://github.com/Leonxlnx/taste-skill)**  
  两次产出都通过全部七项检查，和不装 skill 的页面几乎没有相同之处：自己的字体、偏冷的配色，第二次还用了橙色强调色。
- 🥈 **想要每次都不一样: [hallmark](https://github.com/Nutlope/hallmark)**  
  两次都通过全部七项检查，和默认风格相同处很少，而且两次产出彼此不同：一次扁平偏技术，一次是衬线标题的杂志风。
- 🥉 **想要一套固定风格: [nothing-design-skill](https://github.com/dominikmartn/nothing-design-skill)**  
  两次都是同一套点阵风格，和这里其他的都不像。这是它的目的，也是它的局限：记得检查手机版式，有一次会横向滚动。

**在静态页面上看不出区别:** skills (它讲的是动效；字体、配色和版式与不装 skill 的页面一致); Skills (两次产出四项全部与不装 skill 的页面相同).

不管选哪个：22 个页面里没有一个是老式的 AI 味（紫色渐变、渐变文字、emoji 图标、居中大标题），装不装 skill 都一样。现在的「撞脸」更安静：米白底配青绿、左边文字、右边一张状态卡片。

*排名规则：先看产出和不装 skill 时 Claude Code 做的页面有多少相同（标题字体、正文字体、强调色、背景），越少越靠前；再看七项页面检查，最后看 GitHub 星数。这量的是「像不像」，不是审美：请看图。每个 skill 做两遍，同一份需求。*


## 这些 skill 能做出什么

<table>
<tr>
<td align="center" valign="top" width="33%"><b>🎨 UI 与前端美化</b><br><sub>102 个仓库</sub><br><br><a href="https://github.com/diegomarino/tui-design"><img src="assets/previews/diegomarino__tui-design.jpg" width="260" alt="diegomarino/tui-design"></a><br><sub>让 agent 生成的界面更有设计感的规则和风格。</sub><br><a href="#type-ui"><b>查看列表 →</b></a></td>
<td align="center" valign="top" width="33%"><b>📐 设计系统</b><br><sub>54 个仓库</sub><br><br><a href="https://github.com/feimacode/open-design-agent-kit"><img src="assets/previews/feimacode__open-design-agent-kit.jpg" width="260" alt="feimacode/open-design-agent-kit"></a><br><sub>agent 遵循的设计令牌、主题和组件规范。</sub><br><a href="#type-system"><b>查看列表 →</b></a></td>
<td align="center" valign="top" width="33%"><b>🔌 Figma 与设计工具</b><br><sub>17 个仓库</sub><br><br><sub>让 agent 操作 Figma、Penpot、Canva 等设计工具。</sub><br><a href="#type-tool_mcp"><b>查看列表 →</b></a></td>
</tr>
<tr>
<td align="center" valign="top" width="33%"><b>🧱 设计稿转代码</b><br><sub>12 个仓库</sub><br><br><a href="https://github.com/nolangz/pixel2motion"><img src="assets/previews/nolangz__pixel2motion.gif" width="260" alt="nolangz/pixel2motion"></a><br><sub>把设计稿、截图、线框图转成前端代码。</sub><br><a href="#type-to_code"><b>查看列表 →</b></a></td>
<td align="center" valign="top" width="33%"><b>🖼 海报与品牌</b><br><sub>14 个仓库</sub><br><br><a href="https://github.com/beyondtahir/beyondartist"><img src="assets/previews/beyondtahir__beyondartist.jpg" width="260" alt="beyondtahir/beyondartist"></a><br><sub>海报、社交配图、Logo 和品牌素材。</sub><br><a href="#type-graphics"><b>查看列表 →</b></a></td>
<td align="center" valign="top" width="33%"><b>🔍 设计审查</b><br><sub>4 个仓库</sub><br><br><a href="https://github.com/evidence-codes/loom"><img src="assets/previews/evidence-codes__loom.gif" width="260" alt="evidence-codes/loom"></a><br><sub>设计审查:无障碍、一致性、AI 味。</sub><br><a href="#type-review"><b>查看列表 →</b></a></td>
</tr>
</table>

## 目录

- [🧪 端到端实测](#tested)
- [🎨 UI 与前端美化](#type-ui) (102)
- [📐 设计系统](#type-system) (54)
- [🔌 Figma 与设计工具](#type-tool_mcp) (17)
- [🧱 设计稿转代码](#type-to_code) (12)
- [🖼 海报与品牌](#type-graphics) (14)
- [🔍 设计审查](#type-review) (4)

## 什么样的仓库能上榜

1. 它帮 agent 做视觉设计:UI 与前端风格、设计系统、图形。没有 AI 的组件库、通用图片生成器不算。
2. 它是能安装或运行的软件,不是链接合集或空仓库。
3. 它有 README。没有 README 就没法评级。
4. 50 星及以上只看是否切题;50 星以下还要过 README 质量线(展示效果、一条命令上手、说清产出、文档完整),并且至少 5 星。

这些问题由决策模型逐个读 README 回答,不是人工挑选。卡在线上的仓库可能判到任一边,归错了请提 issue。

<a id="tested"></a>
## 🧪 端到端实测

2026-10-10 我们实跑了其中 10 个。每个在用完即删的沙箱里由 Claude Code（Claude Opus 5.5）调用，把同一个落地页做两遍：一个虚构的应用，文案固定，设计自由。不装 skill 的 Claude Code 也做了两遍。这里没有审美分。每个页面由浏览器测量：任何落地页都该通过的七项检查，以及让页面「撞脸」的四样东西（标题字体、正文字体、强调色、背景），分别和不装 skill 的页面比、和它自己的另一次产出比。

**发现:** 22 个页面里没有一个是老式的 AI 味（紫色强调色、渐变文字、emoji 图标、居中大标题），装不装 skill 都一样。现在的默认风格是米白底配青绿、衬线标题；10 个 skill 里有 2 个四项全部照搬，4 个只有一项或零项相同。每个 skill 在 7 项检查里至少通过 6.5 项。

[![The first screen of each skill's first build; the page built with no skill is top left.](https://agentskillshub.top/best-runs/design/compare.jpg)](https://agentskillshub.top/best-runs/design/compare.jpg)

*每个 skill 第一次产出的首屏；左上角是不装 skill 做的页面。*

| # | Skill | ★ | 与不装 skill 的页面相同（共 4 项） | 自己两次产出相同（共 4 项） | 页面检查通过（共 7 项） | 未通过 | 标题字体 |  |
|---|---|---|---|---|---|---|---|---|
| 1 | [taste-skill](https://github.com/Leonxlnx/taste-skill) | 93,722 | 0.5/4 | 3/4 | 7.0/7 | - | Geist | [证据](https://agentskillshub.top/best-runs/design/Leonxlnx__taste-skill.html) |
| 2 | [ui-ux-pro-max-skill](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill) | 134,020 | 0.5/4 | 3/4 | 6.5/7 | 手机上不横向滚动 | Varela Round | [证据](https://agentskillshub.top/best-runs/design/nextlevelbuilder__ui-ux-pro-max-skill.html) |
| 3 | [hallmark](https://github.com/Nutlope/hallmark) | 29,767 | 1.0/4 | 2/4 | 7.0/7 | - | Hanken Grotesk / Newsreader | [证据](https://agentskillshub.top/best-runs/design/Nutlope__hallmark.html) |
| 4 | [nothing-design-skill](https://github.com/dominikmartn/nothing-design-skill) | 2,808 | 1.0/4 | 4/4 | 6.5/7 | 手机上不横向滚动 | Doto | [证据](https://agentskillshub.top/best-runs/design/dominikmartn__nothing-design-skill.html) |
| 5 | [huashu-design](https://github.com/alchaincyf/huashu-design) | 24,688 | 1.5/4 | 1/4 | 7.0/7 | - | Archivo / Hind | [证据](https://agentskillshub.top/best-runs/design/alchaincyf__huashu-design.html) |
| 6 | [claude-design-system-prompt](https://github.com/Trystan-SA/claude-design-system-prompt) | 1,978 | 1.5/4 | 3/4 | 7.0/7 | - | Bricolage Grotesque | [证据](https://agentskillshub.top/best-runs/design/Trystan-SA__claude-design-system-prompt.html) |
| 7 | [baoyu-design](https://github.com/JimLiu/baoyu-design) | 4,260 | 2.0/4 | 2/4 | 7.0/7 | - | Instrument Serif / Young Serif | [证据](https://agentskillshub.top/best-runs/design/JimLiu__baoyu-design.html) |
| 8 | [styleseed](https://github.com/bitjaru/styleseed) | 973 | 2.0/4 | 1/4 | 7.0/7 | - | Figtree / Inter | [证据](https://agentskillshub.top/best-runs/design/bitjaru__styleseed.html) |
| 9 | [skills](https://github.com/emilkowalski/skills) | 44,260 | 4.0/4 | 4/4 | 7.0/7 | - | Fraunces | [证据](https://agentskillshub.top/best-runs/design/emilkowalski__skills.html) |
| 10 | [Skills](https://github.com/MengTo/Skills) | 6,666 | 4.0/4 | 4/4 | 7.0/7 | - | Fraunces | [证据](https://agentskillshub.top/best-runs/design/MengTo__Skills.html) |

[全部结果、提示词和脚本](https://github.com/zhuyansen/agent-skills-hub/blob/main/ops/design-runs/RESULTS.md) · [https://agentskillshub.top/best/ai-design/#test-results](https://agentskillshub.top/best/ai-design/#test-results)

<a id="type-ui"></a>
## 🎨 UI 与前端美化

[在在线页面打开这一类,按星数排序 →](https://agentskillshub.top/best/ai-design/#type-ui)

<table><tr>
<td align="center" valign="top"><a href="https://github.com/oil-oil/oil-ui"><img src="assets/previews/oil-oil__oil-ui.jpg" width="260" alt="oil-oil/oil-ui"></a><br><sub><a href="https://github.com/oil-oil/oil-ui">oil-oil/oil-ui</a></sub></td>
<td align="center" valign="top"><a href="https://github.com/vmc-inner-circle/k-style-ui-ux"><img src="assets/previews/vmc-inner-circle__k-style-ui-ux.jpg" width="260" alt="vmc-inner-circle/k-style-ui-ux"></a><br><sub><a href="https://github.com/vmc-inner-circle/k-style-ui-ux">vmc-inner-circle/k-style-ui-ux</a></sub></td>
<td align="center" valign="top"><a href="https://github.com/kimsh-1/deck-factory"><img src="assets/previews/kimsh-1__deck-factory.gif" width="260" alt="kimsh-1/deck-factory"></a><br><sub><a href="https://github.com/kimsh-1/deck-factory">kimsh-1/deck-factory</a></sub></td>
</tr></table>

| 仓库 | 星数 | 做什么 | 安全评级 |
|---|---:|---|---|
| [nextlevelbuilder/ui-ux-pro-max-skill](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill) | 147.7k | 提供设计智能、用于跨平台构建专业 UI/UX 的 AI skill | [SAFE](https://agentskillshub.top/skill/nextlevelbuilder/ui-ux-pro-max-skill/) |
| [Leonxlnx/taste-skill](https://github.com/Leonxlnx/taste-skill) | 112.8k | Taste-Skill：让 AI 具备审美，避免生成无聊、千篇一律的内容 | [SAFE](https://agentskillshub.top/skill/Leonxlnx/taste-skill/) |
| [emilkowalski/skills](https://github.com/emilkowalski/skills) | 55.7k | 设计师和工程师技能 | [SAFE](https://agentskillshub.top/skill/emilkowalski/skills/) |
| [Nutlope/hallmark](https://github.com/Nutlope/hallmark) | 52.3k | 适用于 Claude Code、Cursor 和 Codex 的反 AI 垃圾设计 skill。 | [SAFE](https://agentskillshub.top/skill/Nutlope/hallmark/) |
| [alchaincyf/huashu-design](https://github.com/alchaincyf/huashu-design) | 29.1k | Huashu Design：Claude Code 的 HTML 原生设计 skill，支持原型、幻灯片、动画、5维评审和 MP4 导出 | [SAFE](https://agentskillshub.top/skill/alchaincyf/huashu-design/) |
| [MengTo/Skills](https://github.com/MengTo/Skills) | 7.3k | 面向使用 Codex、Claude、Cursor 等 AI coding agents 的设计师和开发者的 agent skills | [SAFE](https://agentskillshub.top/skill/MengTo/Skills/) |
| [JimLiu/baoyu-design](https://github.com/JimLiu/baoyu-design) | 6.3k | 本地运行 Claude Design 作为 Agent Skill，支持 Cursor、Claude Code 等，生成自包含 HTML 的 UI 模拟稿、原… | [SAFE](https://agentskillshub.top/skill/JimLiu/baoyu-design/) |
| [Appllama/appllama-skills](https://github.com/Appllama/appllama-skills) | 5.0k | 构建者，而不只是研究者。将高收入应用模式转为原生品质移动界面的 agent skill。 | [SAFE](https://agentskillshub.top/skill/Appllama/appllama-skills/) |
| [nateherkai/scroll-craft](https://github.com/nateherkai/scroll-craft) | 4.8k | 用于构建沉浸式滚动驱动网站的 agent skill，支持 Codex、Claude Code 等编码 agents，也可作为 Claude Code 插件使… | [SAFE](https://agentskillshub.top/skill/nateherkai/scroll-craft/) |
| [oil-oil/oil-ui](https://github.com/oil-oil/oil-ui) | 3.1k | 探索不同方向，并排比较，再根据真实截图优化 AI UI 设计。 | [SAFE](https://agentskillshub.top/skill/oil-oil/oil-ui/) |
| [dickwu/apple-design-skill](https://github.com/dickwu/apple-design-skill) | 3.1k | 基于 Apple HIG 的跨平台 UI/UX 设计审查工具，支持 Flutter、Tauri、Electron、React Native，兼容 Claude… | [SAFE](https://agentskillshub.top/skill/dickwu/apple-design-skill/) |
| [dominikmartn/nothing-design-skill](https://github.com/dominikmartn/nothing-design-skill) | 2.9k | 用于生成遵循 Nothing 设计语言 UI 的 Claude Code skill。单色、排版、工业风。 | [SAFE](https://agentskillshub.top/skill/dominikmartn/nothing-design-skill/) |
| [bergside/typeui](https://github.com/bergside/typeui) | 2.2k | Build better UI with AI | [SAFE](https://agentskillshub.top/skill/bergside/typeui/) |
| [zanwei/design-dna](https://github.com/zanwei/design-dna) | 2.1k | 将参考界面（图片、截图、URL）转为量化的 Design DNA JSON，再用内容生成匹配界面。 | [SAFE](https://agentskillshub.top/skill/zanwei/design-dna/) |
| [Trystan-SA/claude-design-system-prompt](https://github.com/Trystan-SA/claude-design-system-prompt) | 2.1k | Reverse-engineered system prompt and skill library that turns an LLM into an opinionated, accessibility-aware, AI-slop-resistant design collaborator. | [SAFE](https://agentskillshub.top/skill/Trystan-SA/claude-design-system-prompt/) |
| [agiwhitelist/auteur](https://github.com/agiwhitelist/auteur) | 1.0k | Claude Code skill 以电影制作方式指导网站，涵盖提交清单、生成资源、构建和每次发布前执行的 anti-slop linter。 | [SAFE](https://agentskillshub.top/skill/agiwhitelist/auteur/) |
| [bitjaru/styleseed](https://github.com/bitjaru/styleseed) | 1.0k | Claude Code、Codex 和 Cursor 的开源设计方法引擎，含 23 个 agent skill，支持固定设计判断、多种语法、语义调色板、参考编… | [SAFE](https://agentskillshub.top/skill/bitjaru/styleseed/) |
| [superdesigndev/superdesign-skill](https://github.com/superdesigndev/superdesign-skill) | 974 | 面向 Claude Code、Cursor 和 coding agent 的设计 skill。将 AI 界面转为可发布前端。安装：npx skills add… | [SAFE](https://agentskillshub.top/skill/superdesigndev/superdesign-skill/) |
| [carmahhawwari/ui-design-brain](https://github.com/carmahhawwari/ui-design-brain) | 909 | Cursor skill 为 AI agent 提供 60+ 界面组件的实践、布局模式和设计系统规范，避免生成通用 UI。 | [SAFE](https://agentskillshub.top/skill/carmahhawwari/ui-design-brain/) |
| [xiaopu-ai/web-design](https://github.com/xiaopu-ai/web-design) | 814 | 用于设计美观一致网页的 Claude Code skill——先写规范，再写代码。 | [SAFE](https://agentskillshub.top/skill/xiaopu-ai/web-design/) |
| [AThevon/genjutsu](https://github.com/AThevon/genjutsu) | 777 | Claude Code、claude.ai、Cowork 的创意编程 skill，涵盖动效、微交互和设计系统；编码前确认交互方案，反对 AI 套路。 | [SAFE](https://agentskillshub.top/skill/AThevon/genjutsu/) |
| [ItsssssJack/power-design](https://github.com/ItsssssJack/power-design) | 769 | Claude 幻灯片 skill，包含 20 条品牌 DNA 设计原则。 | [SAFE](https://agentskillshub.top/skill/ItsssssJack/power-design/) |
| [joeseesun/qiaomu-design](https://github.com/joeseesun/qiaomu-design) | 683 | Claude Code设计顾问：反通用UI、风格试衣间、58个真实网站设计系统库 | [SAFE](https://agentskillshub.top/skill/joeseesun/qiaomu-design/) |
| [pulkitxm/claude-directory](https://github.com/pulkitxm/claude-directory) | 626 | Open-source AI interfaces built with Claude (Fable 5) including hero sections, GLSL shaders, design systems, animations, 3D components and and landin… | [SAFE](https://agentskillshub.top/skill/pulkitxm/claude-directory/) |
| [julianoczkowski/designer-skills](https://github.com/julianoczkowski/designer-skills) | 601 | 面向使用 AI 编程工具进行原型设计和构建的设计师的 agent skill 集合，编码设计流程，让 AI 遵循结构化路径而非随机输出。 | [SAFE](https://agentskillshub.top/skill/julianoczkowski/designer-skills/) |
| [INSANE0777/Awwwards-mcp](https://github.com/INSANE0777/Awwwards-mcp) | 553 | 开源 MCP server，为 Claude Code、Codex、Cursor、OpenCode、ZCode 提供网站参考，支持截图搜索和网站记录，免 AP… | [SAFE](https://agentskillshub.top/skill/INSANE0777/Awwwards-mcp/) |
| [codeswithroh/tastemaker](https://github.com/codeswithroh/tastemaker) | 538 | Claude Code skill，基于真实参考图和开发者持久化审美档案生成 UI，避免通用 AI 默认风格。 | [SAFE](https://agentskillshub.top/skill/codeswithroh/tastemaker/) |
| [ceorkm/mobile-app-ui-design](https://github.com/ceorkm/mobile-app-ui-design) | 524 | Claude Code 的专业移动应用 UI/UX 设计 skill | [SAFE](https://agentskillshub.top/skill/ceorkm/mobile-app-ui-design/) |
| [geekjourneyx/claude-design-card](https://github.com/geekjourneyx/claude-design-card) | 475 | 用于生成 14 种格式设计卡片的 Claude Code skill，涵盖平台封面、社交分享卡和编辑排版，遵循 Anthropic | [SAFE](https://agentskillshub.top/skill/geekjourneyx/claude-design-card/) |
| [senlindesign/taste-skill](https://github.com/senlindesign/taste-skill) | 458 | Claude Code skill——逆向拆解任意网站的设计风格：具体设计令牌与明确取舍（解释 WHY，而非只说 WHAT） | [SAFE](https://agentskillshub.top/skill/senlindesign/taste-skill/) |
| [educlopez/ui-craft](https://github.com/educlopez/ui-craft) | 447 | 面向 AI 编程 agent 的设计工程系统——以精工级质量交付 UI。安装为 agent skill。 | [SAFE](https://agentskillshub.top/skill/educlopez/ui-craft/) |
| [vmc-inner-circle/k-style-ui-ux](https://github.com/vmc-inner-circle/k-style-ui-ux) | 400 | 用一页 PRD 在约15分钟生成韩国应用风格移动端界面草稿的 Claude Code·Codex 插件 | [SAFE](https://agentskillshub.top/skill/vmc-inner-circle/k-style-ui-ux/) |
| [tenfoldmarc/website-builder-setup](https://github.com/tenfoldmarc/website-builder-setup) | 384 | 用 Claude Code 无需编程构建动画网站：一次安装包含 UI/UX Pro Max、Framer Motion 和 21st.dev。 | [SAFE](https://agentskillshub.top/skill/tenfoldmarc/website-builder-setup/) |
| [Adityaraj0421/naksha-studio](https://github.com/Adityaraj0421/naksha-studio) | 355 | 适用于 Claude Code、Cursor、Windsurf、Gemini CLI 和 Copilot 的虚拟设计团队，含26种角色、62个命令和设计知识。 | [SAFE](https://agentskillshub.top/skill/Adityaraj0421/naksha-studio/) |
| [referodesign/refero_skill](https://github.com/referodesign/refero_skill) | 347 | 面向 AI agents 的研究优先设计 skill，通过 Refero MCP 获取真实应用界面和流程。 | [SAFE](https://agentskillshub.top/skill/referodesign/refero_skill/) |
| [hylarucoder/benchmark-skill-ui-ux-pro-max](https://github.com/hylarucoder/benchmark-skill-ui-ux-pro-max) | 322 | 使用 Claude Code SDK 和 GLM 4.7，通过 ui-ux-pro-max Skill 自动生成100个落地页的基准测试项目 | [SAFE](https://agentskillshub.top/skill/hylarucoder/benchmark-skill-ui-ux-pro-max/) |
| [enmerasoftware/ai-design-check](https://github.com/enmerasoftware/ai-design-check) | 242 | AI 编码代理界面的设计规则和零依赖检查器，支持英语和土耳其语。 | [SAFE](https://agentskillshub.top/skill/enmerasoftware/ai-design-check/) |
| [originaleric/dig-ui-skill](https://github.com/originaleric/dig-ui-skill) | 230 | Dig 构建的供 agent 使用的 prompt-as-code 设计系统，适用于 Codex、Cursor 和 Claude Code，含目录、布局、区块… | [SAFE](https://agentskillshub.top/skill/originaleric/dig-ui-skill/) |
| [axiaoge2/Apple-Hig-Designer](https://github.com/axiaoge2/Apple-Hig-Designer) | 226 | 遵循 Apple Human Interface Guidelines 设计专业界面的 Claude Code skill | [SAFE](https://agentskillshub.top/skill/axiaoge2/Apple-Hig-Designer/) |
| [Nutlope/variate](https://github.com/Nutlope/variate) | 222 | 生成组件四种设计变体的紧凑型设计 skill，适用于 Claude Code、Codex CLI 和 opencode。 | [SAFE](https://agentskillshub.top/skill/Nutlope/variate/) |
| [jiji262/claude-design-skill](https://github.com/jiji262/claude-design-skill) | 217 | 可移植的 Claude skill，将 Claude 变成 HTML 产物设计专家，支持演示文稿、落地页、原型、动画和海报。改编自 Claude.ai 内部设… | [SAFE](https://agentskillshub.top/skill/jiji262/claude-design-skill/) |
| [3x-haust/oh-my-design](https://github.com/3x-haust/oh-my-design) | 213 | 为 Codex、Claude Code 和兼容 Pi 的 agent 设计认知循环：构框、发散、观察、重构 | [SAFE](https://agentskillshub.top/skill/3x-haust/oh-my-design/) |
| [Wholiver/swiftui-design-skill](https://github.com/Wholiver/swiftui-design-skill) | 209 | SwiftUI 前端设计 skill：6条规范、设计咨询、品牌资产指南和五维评审，支持 Claude Code、Cursor、Codex、OpenCode 等… | [SAFE](https://agentskillshub.top/skill/Wholiver/swiftui-design-skill/) |
| [dembrandt/dembrandt-skills](https://github.com/dembrandt/dembrandt-skills) | 190 | 高级 UX 与设计系统知识，让 AI agent 自动应用。 | [SAFE](https://agentskillshub.top/skill/dembrandt/dembrandt-skills/) |
| [ganavisk/nextlevelbuilder-ui-ux-pro-max-skill-Public](https://github.com/ganavisk/nextlevelbuilder-ui-ux-pro-max-skill-Public) | 190 | An AI SKILL that provide design intelligence for building professional UI/UX multiple platforms | [SAFE](https://agentskillshub.top/skill/ganavisk/nextlevelbuilder-ui-ux-pro-max-skill-Public/) |
| [yzfly/awesome-design-html](https://github.com/yzfly/awesome-design-html) | 184 | 115个品牌主题HTML设计，作为Claude Code skill（93网页+22个iOS，含20个中国展示）。一行安装，再说：“Linear风页面”“飞书… | [SAFE](https://agentskillshub.top/skill/yzfly/awesome-design-html/) |
| [touchine-ojo/OJO-Design-Skills](https://github.com/touchine-ojo/OJO-Design-Skills) | 175 | 适用于 Codex、Claude Code、ZCode 等 AI coding agent 的可复用 UI/UX 设计 skill | [SAFE](https://agentskillshub.top/skill/touchine-ojo/OJO-Design-Skills/) |
| [zeke/swiss-design-skill](https://github.com/zeke/swiss-design-skill) | 164 | 面向 AI agent 的瑞士国际主义风格设计系统 skill | [SAFE](https://agentskillshub.top/skill/zeke/swiss-design-skill/) |
| [Ilm-Alan/frontend-design](https://github.com/Ilm-Alan/frontend-design) | 163 | 适用于 Claude Code、Codex 和 Gemini CLI 的前端设计 skill。八种美学锚点，分别对应特定 CSS token。每次需求选一种。 | [SAFE](https://agentskillshub.top/skill/Ilm-Alan/frontend-design/) |
| [robonuggets/design-system](https://github.com/robonuggets/design-system) | 152 | 提供品牌参考，生成完整设计系统页面和一页 A4 品牌手册 PDF。 | [SAFE](https://agentskillshub.top/skill/robonuggets/design-system/) |
| [TheGoat395/Codex-Skills](https://github.com/TheGoat395/Codex-Skills) | 137 | Codex 优先的 Agent Skills 库，涵盖前端、网站、动效、无障碍、QA 和交付流程。 | [SAFE](https://agentskillshub.top/skill/TheGoat395/Codex-Skills/) |
| [HermeticOrmus/LibreUIUX-Claude-Code](https://github.com/HermeticOrmus/LibreUIUX-Claude-Code) | 124 | Claude Code 的 UI/UX 系统：71 个插件、93 个 agent、74 个 skill，涵盖设计、无障碍和前端工作流。 | [SAFE](https://agentskillshub.top/skill/HermeticOrmus/LibreUIUX-Claude-Code/) |
| [TidyFactor/Styler](https://github.com/TidyFactor/Styler) | 121 | Production-Stage Visual Design & In-Codebase UI Engineering Suite | [SAFE](https://agentskillshub.top/skill/TidyFactor/Styler/) |
| [ohmiler/gridgeist](https://github.com/ohmiler/gridgeist) | 120 | Gridgeist 将产品意图转化为严谨的视觉系统，避免千篇一律的 AI SaaS 风格。 | [SAFE](https://agentskillshub.top/skill/ohmiler/gridgeist/) |
| [SpaceZephyr/brand-design-md](https://github.com/SpaceZephyr/brand-design-md) | 117 | 为 AI agent 按需提供62个品牌设计语言的 Claude Code skill | [SAFE](https://agentskillshub.top/skill/SpaceZephyr/brand-design-md/) |
| [MickeyAlton33/web-designer-plugin](https://github.com/MickeyAlton33/web-designer-plugin) | 115 | 网页设计 skill，适用于 Claude Code。来自 38 个网站的 48 种模式，避免生成通用 AI 前端。 | [SAFE](https://agentskillshub.top/skill/MickeyAlton33/web-designer-plugin/) |
| [cth9191/taste-vault](https://github.com/cth9191/taste-vault) | 115 | 本地设计风格图库：输入截图，输出设计词汇和可粘贴的 Claude Code 简报。网页设计三步流程第 1 步。 | [SAFE](https://agentskillshub.top/skill/cth9191/taste-vault/) |
| [ihlamury/design-skills](https://github.com/ihlamury/design-skills) | 107 | 从设计系统提取的 UI 约束，用于配合 AI agent 构建像素级界面。 | [SAFE](https://agentskillshub.top/skill/ihlamury/design-skills/) |
| [yizhiyanhua-ai/fireworks-design](https://github.com/yizhiyanhua-ai/fireworks-design) | 107 | Claude Code 工作流：复现 ClaudeDesign，支持并行设计探索、面板评审、综合与对抗式优化，生成单个前端页面；双语 README | [SAFE](https://agentskillshub.top/skill/yizhiyanhua-ai/fireworks-design/) |
| [MaxHan7/frontend-ui-standards-skill](https://github.com/MaxHan7/frontend-ui-standards-skill) | 106 | 设计系统优先的前端 UI 实现 Codex skill | [SAFE](https://agentskillshub.top/skill/MaxHan7/frontend-ui-standards-skill/) |
| [Laith0003/ux-skill](https://github.com/Laith0003/ux-skill) | 99 | Claude Code、Cursor、Windsurf 设计引擎：确定性反 AI-slop 检查器（152 条规则）；离线运行，不调用 LLM，MIT。 | [SAFE](https://agentskillshub.top/skill/Laith0003/ux-skill/) |
| [albertirgi/replica](https://github.com/albertirgi/replica) | 99 | 根据参考重建 UI 并评分验证。Claude Code 等 coding agents 的 Agent Skill：捕获网站、截图或录屏，按布局、样式、像素和… | [SAFE](https://agentskillshub.top/skill/albertirgi/replica/) |
| [saifyxpro/ui-ux-design-pro-skill](https://github.com/saifyxpro/ui-ux-design-pro-skill) | 98 | AI配对、150+推理规则、CLI、18个平台模板；支持Claude、Cursor等；107种风格、127套配色、107种字体 | [SAFE](https://agentskillshub.top/skill/saifyxpro/ui-ux-design-pro-skill/) |
| [szilu/ux-designer-skill](https://github.com/szilu/ux-designer-skill) | 98 | 基于现代最佳实践（2026）的 UX/UI 设计指导 Claude Code skill | [SAFE](https://agentskillshub.top/skill/szilu/ux-designer-skill/) |
| [h3nryprod01/design-taste](https://github.com/h3nryprod01/design-taste) | 93 | Claude Code / Cowork 的前端设计规范，涵盖字体、配色、动效、组件与反套路。 | [SAFE](https://agentskillshub.top/skill/h3nryprod01/design-taste/) |
| [pedrojaques99/visant-skills-public](https://github.com/pedrojaques99/visant-skills-public) | 86 | Visant 的 Claude Code skills：反低质 UI 审计、动效、前端、文案，含可执行检测器。 | [SAFE](https://agentskillshub.top/skill/pedrojaques99/visant-skills-public/) |
| [awesome-skills/mobile-app-design](https://github.com/awesome-skills/mobile-app-design) | 85 | Claude Code 移动应用 UI/UX 设计 skill：iOS、Android、无障碍和 React Native 最佳实践 | [SAFE](https://agentskillshub.top/skill/awesome-skills/mobile-app-design/) |
| [Songzhi-lab/chinese-font-selector](https://github.com/Songzhi-lab/chinese-font-selector) | 83 | 中文字体选择 agent skill：可商用 CJK 字体库、场景选字矩阵、CJK-Latin 搭配规则，支持 Claude Code、Cursor、Kimi… | [SAFE](https://agentskillshub.top/skill/Songzhi-lab/chinese-font-selector/) |
| [kimsh-1/deck-factory](https://github.com/kimsh-1/deck-factory) | 80 | 一行意图 → 一份演示级深色编辑风 HTML 演示文稿。Claude Code skill。 | [SAFE](https://agentskillshub.top/skill/kimsh-1/deck-factory/) |
| [PyModel/niblet-skill-mcp](https://github.com/PyModel/niblet-skill-mcp) | 79 | 基于真实产品界面的 MCP server 和 design skill，用于编码 agent 的 UI 工作。两种工具，可通过 npx 安装。 | [SAFE](https://agentskillshub.top/skill/PyModel/niblet-skill-mcp/) |
| [haider-nawaz/liquid-glass-skill](https://github.com/haider-nawaz/liquid-glass-skill) | 78 | 用于使用 SwiftUI Liquid Glass 设计系统构建和迁移 Apple 平台应用的 Claude Code skill（iOS 26+、macOS… | [SAFE](https://agentskillshub.top/skill/haider-nawaz/liquid-glass-skill/) |
| [CaesiumY/ko-design-md](https://github.com/CaesiumY/ko-design-md) | 76 | 한국 브랜드의 디자인 언어를 출처가 달린 DESIGN.md 한 장으로 정리한 오픈 카탈로그 — Open catalog of Korean brands' design languages, one cited DESIGN.md per brand. | [SAFE](https://agentskillshub.top/skill/CaesiumY/ko-design-md/) |
| [AgriciDaniel/gogh](https://github.com/AgriciDaniel/gogh) | 70 | Gogh 是带来源引用的 Obsidian 工作中枢，将六种前端设计 skill 整合为一套供 AI coding agents 使用的技术栈。 | [SAFE](https://agentskillshub.top/skill/AgriciDaniel/gogh/) |
| [QingYunA/agent-html](https://github.com/QingYunA/agent-html) | 65 | 零依赖、单文件 HTML 设计系统与 agent skill，受 shadcn/ui 启发。完全离线、无需 npm，提供 6 种布局原型和 LLM 原子工具集。 | [SAFE](https://agentskillshub.top/skill/QingYunA/agent-html/) |
| [phazurlabs/sumi](https://github.com/phazurlabs/sumi) | 59 | Sumi——Claude Code 的 UX/UI 设计知识库：43 个 skill、168 份参考、37 个命令，反低质设计并提供可审计引用链。使用 /su… | [SAFE](https://agentskillshub.top/skill/phazurlabs/sumi/) |
| [Ilbie/Toss-Design-Skill](https://github.com/Ilbie/Toss-Design-Skill) | 58 | 参考 Toss Tech Design 文章制作的非官方 skill。 | [SAFE](https://agentskillshub.top/skill/Ilbie/Toss-Design-Skill/) |
| [stevembarclay/pencilplaybook](https://github.com/stevembarclay/pencilplaybook) | 58 | PencilPlaybook 是 Pencil.dev + Claude Code 的 UI Taste-Skill，结合感知心理学与资深设计约束，减少雷同… | [SAFE](https://agentskillshub.top/skill/stevembarclay/pencilplaybook/) |
| [frhscopex/design-skill-os](https://github.com/frhscopex/design-skill-os) | 57 | 面向 AI agent 的设计知识层，综合 10 多本设计书籍，生成明确意图的 UI/UX，避免套路。 | [SAFE](https://agentskillshub.top/skill/frhscopex/design-skill-os/) |
| [iamzifei/james-design](https://github.com/iamzifei/james-design) | 39 | 面向 Claude Code 的 UI 设计 skill：创建高保真 HTML 设计、原型、幻灯片和动画 | [SAFE](https://agentskillshub.top/skill/iamzifei/james-design/) |
| [nghiahsgs/skills-slides](https://github.com/nghiahsgs/skills-slides) | 36 | 5万多个独特 HTML 演示设计。零依赖。拒绝 AI 垃圾风。Claude Code skill。 | [SAFE](https://agentskillshub.top/skill/nghiahsgs/skills-slides/) |
| [regutierrez/ui-ux-skill](https://github.com/regutierrez/ui-ux-skill) | 31 | UI-UX skill，基于 ui-ux-pro-max-skill 分支，用 Python 重写 | [CAUTION](https://agentskillshub.top/skill/regutierrez/ui-ux-skill/) |
| [sva-admin/sv-academy-prom-design](https://github.com/sva-admin/sv-academy-prom-design) | 30 | Claude Code、Cowork 和 Cursor 的设计风格。Prom 是泰语“准备好”的意思。免费学习：loop.sv-academy.org | [SAFE](https://agentskillshub.top/skill/sva-admin/sv-academy-prom-design/) |
| [diegomarino/tui-design](https://github.com/diegomarino/tui-design) | 26 | 用于设计、模拟、构建和审计终端 UI 的 agent skill | [SAFE](https://agentskillshub.top/skill/diegomarino/tui-design/) |
| [jmlweb/storybook-vrhythm](https://github.com/jmlweb/storybook-vrhythm) | 22 | 供 coding agents 运行的 Storybook 基准网格：精确像素差审计与可视化叠加层 | [SAFE](https://agentskillshub.top/skill/jmlweb/storybook-vrhythm/) |
| [Nyx-abu/awwwards-ui-skill](https://github.com/Nyx-abu/awwwards-ui-skill) | 21 | 提升 AI 生成 UI 设计质量的 skill，教 Claude Code、Codex、Antigravity 构建涵盖动效、排版、色彩和 WCAG AA 的… | [SAFE](https://agentskillshub.top/skill/Nyx-abu/awwwards-ui-skill/) |
| [senlindesign/proof](https://github.com/senlindesign/proof) | 18 | Proof：Claude Code & Codex 的产品设计 skill，基于400+个真实产品页面，含8种页面类型、10个区块和4种风格，支持浅色与深色。 | [SAFE](https://agentskillshub.top/skill/senlindesign/proof/) |
| [Shawnchee/frontend-god-mode](https://github.com/Shawnchee/frontend-god-mode) | 16 | 将前端设计 skill 集成到一个 skill 中 | [SAFE](https://agentskillshub.top/skill/Shawnchee/frontend-god-mode/) |
| [marcosnovo/unslop-design](https://github.com/marcosnovo/unslop-design) | 16 | Claude Code等 agent skill：64项设计修复、UI评分脚本和你确认的前后对比。 | [SAFE](https://agentskillshub.top/skill/marcosnovo/unslop-design/) |
| [SandroHub013/awwwards-skill](https://github.com/SandroHub013/awwwards-skill) | 14 | Awwwards是评分体系，不是风格；Claude Code skill将设计40/易用30/创意20/内容10编为8阶段构建法，含18个参考、模板和可运行的… | [SAFE](https://agentskillshub.top/skill/SandroHub013/awwwards-skill/) |
| [narenkatakam/ux-audit](https://github.com/narenkatakam/ux-audit) | 14 | 为 AI 编程助手提供设计指导：12 项原则、13 份参考文档、7 份组件检查清单。支持 Claude Code、Cursor、Codex 和 Windsur… | [SAFE](https://agentskillshub.top/skill/narenkatakam/ux-audit/) |
| [justskill-ai/justskill-design](https://github.com/justskill-ai/justskill-design) | 12 | 用 coding agent 进行设计——这是 skill，不是产品：无需 MCP server、应用、账号、构建步骤或 npm install。 | [SAFE](https://agentskillshub.top/skill/justskill-ai/justskill-design/) |
| [LaoFeng-mouse/fantasy-mouse-ui](https://github.com/LaoFeng-mouse/fantasy-mouse-ui) | 11 | 适用于 Codex、Claude、Gemini、DeepSeek 和通用 Agents 的模型无关 Fantasy Mouse UI 设计插件 | [SAFE](https://agentskillshub.top/skill/LaoFeng-mouse/fantasy-mouse-ui/) |
| [ajantoniou/fable-design-system](https://github.com/ajantoniou/fable-design-system) | 10 | Fable 风格设计系统，适用于 AI coding agent、Claude、Opus 4.8、Codex、Cursor、Gemini、Antigravit… | [CAUTION](https://agentskillshub.top/skill/ajantoniou/fable-design-system/) |
| [linkonai2026-kr/design-on](https://github.com/linkonai2026-kr/design-on) | 10 | 一句话出网页；4制3审，检59种反模式；Impeccable、tasteskill、UI Skills、emil-skill；Claude Code/Code… | [SAFE](https://agentskillshub.top/skill/linkonai2026-kr/design-on/) |
| [sshahzaiib/senior-designer-skill](https://github.com/sshahzaiib/senior-designer-skill) | 10 | Claude Code 高级产品设计 skill：基于158份审核资料，构建研究驱动、无障碍且不千篇一律的UI，附质量评分清单。 | [SAFE](https://agentskillshub.top/skill/sshahzaiib/senior-designer-skill/) |
| [alwkala/Cinematic-Landing-Kit](https://github.com/alwkala/Cinematic-Landing-Kit) | 9 | 基于 context-and-memory package 的记忆驱动设计系统，指导任意 AI coding agent 生成滚动驱动的产品落地页。单个 HT… | [SAFE](https://agentskillshub.top/skill/alwkala/Cinematic-Landing-Kit/) |
| [ABC-xiaoxuan/award-level-web-design](https://github.com/ABC-xiaoxuan/award-level-web-design) | 8 | Agent skill：按 Awwwards/Webby/FWA 标准设计网页，通过 8 维截图自审循环改进（Claude Code、Codex、Cursor） | [SAFE](https://agentskillshub.top/skill/ABC-xiaoxuan/award-level-web-design/) |
| [SuanFishXYY/suanfish-design-system](https://github.com/SuanFishXYY/suanfish-design-system) | 8 | Suanfish Design System：7层33个AI设计agent，含REJECT机制；v2.5新增Path G（流式、工具调用、推理、引用、工件）。 | [SAFE](https://agentskillshub.top/skill/SuanFishXYY/suanfish-design-system/) |
| [yckonnnnn/zack-design-skills](https://github.com/yckonnnnn/zack-design-skills) | 8 | 8个设计技能+60条可执行判断标准，减少网页的AI感。支持Claude Code、Cursor、Codex。 | [SAFE](https://agentskillshub.top/skill/yckonnnnn/zack-design-skills/) |
| [joepUI/motion-ref-skill](https://github.com/joepUI/motion-ref-skill) | 7 | UI 动效设计 skill，含13类111种效果；按场景生成CSS/JS代码，支持 Claude Code、Codex、OpenClaw。 | [SAFE](https://agentskillshub.top/skill/joepUI/motion-ref-skill/) |
| [nabinkhair42/structural-grid-skill](https://github.com/nabinkhair42/structural-grid-skill) | 5 | 面向 AI coding agent 的 Structural Grid（Exposed Grid / Rail Layout）设计系统 skill。 | [SAFE](https://agentskillshub.top/skill/nabinkhair42/structural-grid-skill/) |
| [undsky/doudou-color-skill](https://github.com/undsky/doudou-color-skill) | 5 | 结合五行色彩哲学与现代色彩和弦，提供数字产品、品牌印刷和海报配色方案 | [SAFE](https://agentskillshub.top/skill/undsky/doudou-color-skill/) |

<a id="type-system"></a>
## 📐 设计系统

[在在线页面打开这一类,按星数排序 →](https://agentskillshub.top/best/ai-design/#type-system)

<table><tr>
<td align="center" valign="top"><a href="https://github.com/arla6ka/design.how"><img src="assets/previews/arla6ka__design.how.jpg" width="260" alt="arla6ka/design.how"></a><br><sub><a href="https://github.com/arla6ka/design.how">arla6ka/design.how</a></sub></td>
<td align="center" valign="top"><a href="https://github.com/ckryptickunal/OpenDesigner"><img src="assets/previews/ckryptickunal__OpenDesigner.jpg" width="260" alt="ckryptickunal/OpenDesigner"></a><br><sub><a href="https://github.com/ckryptickunal/OpenDesigner">ckryptickunal/OpenDesigner</a></sub></td>
<td align="center" valign="top"><a href="https://github.com/byadityaraj/designmd"><img src="assets/previews/byadityaraj__designmd.jpg" width="260" alt="byadityaraj/designmd"></a><br><sub><a href="https://github.com/byadityaraj/designmd">byadityaraj/designmd</a></sub></td>
</tr></table>

| 仓库 | 星数 | 做什么 | 安全评级 |
|---|---:|---|---|
| [nexu-io/open-design](https://github.com/nexu-io/open-design) | 107.0k | Claude Code、Codex、Cursor、DeepSeek Harness、OpenCode 的本地设计应用，支持生成与导出 HTML/PDF/PPT… | [SAFE](https://agentskillshub.top/skill/nexu-io/open-design/) |
| [Manavarya09/design-extract](https://github.com/Manavarya09/design-extract) | 5.0k | 一条命令提取网站设计系统：DTCG tokens、MCP server、多平台输出、Tailwind v4、Figma variables、shadcn/ui… | [SAFE](https://agentskillshub.top/skill/Manavarya09/design-extract/) |
| [bergside/design-md-chrome](https://github.com/bergside/design-md-chrome) | 3.2k | 基于 TypeUI 的 Chrome 扩展，可提取网站样式并为 AI 生成 DESIGN.md 文件和设计 skill | [SAFE](https://agentskillshub.top/skill/bergside/design-md-chrome/) |
| [plugin87/ux-ui-agent-skills](https://github.com/plugin87/ux-ui-agent-skills) | 3.2k | Turn Claude into a senior design architect: DTCG tokens, 52 components, WCAG 2.2 AA-AAA, 138 design systems, any-framework code, and 50 objective gat… | [SAFE](https://agentskillshub.top/skill/plugin87/ux-ui-agent-skills/) |
| [feimacode/open-design-agent-kit](https://github.com/feimacode/open-design-agent-kit) | 1.1k | 在 Copilot、Claude、Codex、Cursor 中制作海报、社交帖子、幻灯片和落地页，提供 198 套设计系统、检查及 PDF/PNG/Power… | [SAFE](https://agentskillshub.top/skill/feimacode/open-design-agent-kit/) |
| [dominikmartn/hue](https://github.com/dominikmartn/hue) | 898 | 开源 skill，可学习任意品牌并生成完整设计系统。支持 Claude Code 和 Codex。助手构建的 UI 均符合品牌。 | [SAFE](https://agentskillshub.top/skill/dominikmartn/hue/) |
| [AnxForever/stylekit](https://github.com/AnxForever/stylekit) | 797 | 开源 AI 生成 UI 视觉风格库：148 套风格，包含 design tokens、prompts、MCP、Agent Skill 和 npm CLI。 | [SAFE](https://agentskillshub.top/skill/AnxForever/stylekit/) |
| [op7418/dsh-guizang-design](https://github.com/op7418/dsh-guizang-design) | 754 | 归藏设计·DeepSeek Harness 插件：网页 PPT、图文卡片、网页排版、去 AI 味 skill；设计系统、作品库、内容工作流、语气档案 | [SAFE](https://agentskillshub.top/skill/op7418/dsh-guizang-design/) |
| [Railly/tinte](https://github.com/Railly/tinte) | 630 | 将设计系统编译为 Agent Plugin，提取视觉身份，生成 SKILL.md 与 tokens.css，检查绕过 tokens 的内容。 | [SAFE](https://agentskillshub.top/skill/Railly/tinte/) |
| [kwakseongjae/oh-my-design](https://github.com/kwakseongjae/oh-my-design) | 580 | 为 AI coding agent 提供设计系统：一条命令将公司 DESIGN.md 参考和 skill 安装到 Claude Code、Codex、Curs… | [SAFE](https://agentskillshub.top/skill/kwakseongjae/oh-my-design/) |
| [marvkr/better-design](https://github.com/marvkr/better-design) | 568 | 开源 MCP server 与 shadcn/ui registry：含31个主题、设计令牌、UI原则和WCAG规则，支持 Claude Code、Curso… | [SAFE](https://agentskillshub.top/skill/marvkr/better-design/) |
| [guiguiyan930-source/game-ui-design-workflow](https://github.com/guiguiyan930-source/game-ui-design-workflow) | 421 | 面向游戏 UI 设计的 Cursor Agent Skills 工作流，涵盖原型生成、风格切换、页面延展和组件拆解，通过 Spec-Kit 文档、视觉契约与资… | [SAFE](https://agentskillshub.top/skill/guiguiyan930-source/game-ui-design-workflow/) |
| [arla6ka/design.how](https://github.com/arla6ka/design.how) | 295 | design.how 的 agent skill 与设计系统：从应用构建设计系统，用 agent 发布 UI，并在 CI 中强制执行。 | [SAFE](https://agentskillshub.top/skill/arla6ka/design.how/) |
| [arvindrk/extract-design-system](https://github.com/arvindrk/extract-design-system) | 282 | 从公开网站提取设计令牌（颜色、字体、间距、圆角、阴影），生成 JSON 和 CSS 自定义属性，可作为 Claude、Cursor、Codex 的 agent… | [SAFE](https://agentskillshub.top/skill/arvindrk/extract-design-system/) |
| [oalanicolas/claude-design-premium](https://github.com/oalanicolas/claude-design-premium) | 281 | Claude Design 设计系统入门套件 | [SAFE](https://agentskillshub.top/skill/oalanicolas/claude-design-premium/) |
| [redongreen/uSpec](https://github.com/redongreen/uSpec) | 251 | 由 AI agent 直接生成 UI 组件设计系统文档，可渲染到 Figma 或 .md 文件，支持 Cursor、Claude Code 和 Codex。 | [SAFE](https://agentskillshub.top/skill/redongreen/uSpec/) |
| [uxKero/anydesign](https://github.com/uxKero/anydesign) | 242 | 分析图像、网站和 Figma 文件，生成包含令牌系统、组件清单和重建说明的结构化 design.md 的 Claude skill | [SAFE](https://agentskillshub.top/skill/uxKero/anydesign/) |
| [southleft/story-ui](https://github.com/southleft/story-ui) | 239 | AI 驱动的 Storybook story 生成器，支持任意框架、设计系统和 LLM 提供商 | [SAFE](https://agentskillshub.top/skill/southleft/story-ui/) |
| [senlindesign/claude2figma](https://github.com/senlindesign/claude2figma) | 207 | Claude Code + Figma 的约束层：4 个 skill 让 AI 遵循你的 Design System。组件保持关联，tokens 保持绑定，不… | [SAFE](https://agentskillshub.top/skill/senlindesign/claude2figma/) |
| [tsubotax/melta-ui](https://github.com/tsubotax/melta-ui) | 202 | 人类和 AI 都能读懂的设计系统，适用于 Claude Code 和 Cursor | [SAFE](https://agentskillshub.top/skill/tsubotax/melta-ui/) |
| [jamesrochabrun/Easel](https://github.com/jamesrochabrun/Easel) | 169 | Easel 是 Codex 和 Claude 的 macOS 工作区，支持 AI 产品设计与前端迭代，集成本地项目库、设计系统、Codex 对话、网页预览检查… | [SAFE](https://agentskillshub.top/skill/jamesrochabrun/Easel/) |
| [skydashnet/material-design-3-ui-skill](https://github.com/skydashnet/material-design-3-ui-skill) | 164 | 用于使用 Google Material Design 3、Material You、M3 Expressive、无障碍、适配布局和语义化设计令牌设计、评审与… | [SAFE](https://agentskillshub.top/skill/skydashnet/material-design-3-ui-skill/) |
| [bergside/design-md-figma](https://github.com/bergside/design-md-figma) | 156 | Figma 插件，提取本地样式规范并生成 DESIGN.md 和 SKILL.md，供 Claude Code、Codex、Cursor 等 AI 工具使用 | [SAFE](https://agentskillshub.top/skill/bergside/design-md-figma/) |
| [luongnv89/sleek-ui](https://github.com/luongnv89/sleek-ui) | 136 | The Unsplash of design systems for AI agents — re-skin your app with one URL | [SAFE](https://agentskillshub.top/skill/luongnv89/sleek-ui/) |
| [OpenLabs-so/oa-design](https://github.com/OpenLabs-so/oa-design) | 135 | Open Analytics 设计语言作为 agent skill：组件配方、类型检查源码、token CSS 和 CLI，适用于 Claude Code、C… | [SAFE](https://agentskillshub.top/skill/OpenLabs-so/oa-design/) |
| [ckryptickunal/OpenDesigner](https://github.com/ckryptickunal/OpenDesigner) | 124 | 面向 Claude、ChatGPT、Codex 和 Cursor 的开源插件，将简短回答转化为设计系统，使构建内容保持统一。 | [SAFE](https://agentskillshub.top/skill/ckryptickunal/OpenDesigner/) |
| [bluzir/claude-code-design](https://github.com/bluzir/claude-code-design) | 109 | 为 Claude Code 复现 Claude Design：用 skills、starters 和 Chrome DevTools MCP 创建 HTML… | [SAFE](https://agentskillshub.top/skill/bluzir/claude-code-design/) |
| [Devesh-Shirsath/spotkit](https://github.com/Devesh-Shirsath/spotkit) | 107 | Spotkit：Claude Code skill，将功能描述转为统一设计系统中的极简抽象 SVG 产品插图。 | [SAFE](https://agentskillshub.top/skill/Devesh-Shirsath/spotkit/) |
| [Bearisbug/Quilt](https://github.com/Bearisbug/Quilt) | 106 | AI-native infinite-canvas design tool: describe an app, get multi-screen HTML designs on an infinite canvas, click through them as a prototype, and l… | [SAFE](https://agentskillshub.top/skill/Bearisbug/Quilt/) |
| [southleft/figma-console-mcp-skills](https://github.com/southleft/figma-console-mcp-skills) | 96 | Figma Console MCP：Figma MCP server的Markdown skill，含令牌、变量、组件、WCAG审计、版本、FigJam、Sl… | [SAFE](https://agentskillshub.top/skill/southleft/figma-console-mcp-skills/) |
| [educlopez/design-bites](https://github.com/educlopez/design-bites) | 92 | 精选网站的 DESIGN.md 文件，解析设计系统，供 AI agents 使用。Sparkbites 出品。 | [SAFE](https://agentskillshub.top/skill/educlopez/design-bites/) |
| [jrpease/throughline](https://github.com/jrpease/throughline) | 80 | Throughline——连接设计与代码。Claude Code 插件，引导你从空白 Figma 文件构建同步、经过故事测试的组件库。 | [SAFE](https://agentskillshub.top/skill/jrpease/throughline/) |
| [birdseyevue/daisyui-mcp](https://github.com/birdseyevue/daisyui-mcp) | 77 | 基于公开 llms.txt 的 DaisyUI 组件文档本地 MCP 服务器 | [SAFE](https://agentskillshub.top/skill/birdseyevue/daisyui-mcp/) |
| [byadityaraj/designmd](https://github.com/byadityaraj/designmd) | 75 | 为 AI 编码工作流提取设计上下文，从任意 URL 提取颜色、字体、间距和断点，生成可移植的 DESIGN.md | [SAFE](https://agentskillshub.top/skill/byadityaraj/designmd/) |
| [qiuyiwu1989-star/opendesign](https://github.com/qiuyiwu1989-star/opendesign) | 74 | 1,486 个真实网页设计系统，提取为机器可读规范。面向 AI coding agents 的 MCP server。 | [SAFE](https://agentskillshub.top/skill/qiuyiwu1989-star/opendesign/) |
| [yuvrajangadsingh/brandmd](https://github.com/yuvrajangadsingh/brandmd) | 72 | 防止 Claude Code/Cursor 猜测 UI。将任意网站设计系统提取为符合规范的 DESIGN.md，通过官方 @google/design.md… | [SAFE](https://agentskillshub.top/skill/yuvrajangadsingh/brandmd/) |
| [jiemianduan/poster-style-transfer](https://github.com/jiemianduan/poster-style-transfer) | 69 | 用于提取海报设计系统并将其迁移到原创海报概念的开放 Agent Skill。 | [SAFE](https://agentskillshub.top/skill/jiemianduan/poster-style-transfer/) |
| [gregkozakiewicz/roast-my-design-system](https://github.com/gregkozakiewicz/roast-my-design-system) | 65 | AI 设计系统扫描器和 MCP 服务器，为仓库按 0-100 评分并生成修复提示。 | [SAFE](https://agentskillshub.top/skill/gregkozakiewicz/roast-my-design-system/) |
| [hakilee/design-farmer](https://github.com/hakilee/design-farmer) | 63 | 将设计系统质量从“尽力而为”变成可重复的工程流程的 agent skill。 | [SAFE](https://agentskillshub.top/skill/hakilee/design-farmer/) |
| [MohtashamMurshid/getdesign](https://github.com/MohtashamMurshid/getdesign) | 55 | 任意 URL 按需生成设计系统。五种形式，一个 agent：web、API、CLI、TypeScript SDK，以及可在 Claude Code、Codex… | [SAFE](https://agentskillshub.top/skill/MohtashamMurshid/getdesign/) |
| [hasi98/designpull](https://github.com/hasi98/designpull) | 55 | 用 AI 视觉从任意网站生成兼容 Google Stitch 的 DESIGN.md 文件。使用自有 Gemini、OpenAI、Claude 或 Ollam… | [SAFE](https://agentskillshub.top/skill/hasi98/designpull/) |
| [jubscodes/get-shit-pretty](https://github.com/jubscodes/get-shit-pretty) | 55 | 为 AI 编程工具做设计工程。品牌识别与设计项目，从策略到代码。 | [SAFE](https://agentskillshub.top/skill/jubscodes/get-shit-pretty/) |
| [natdexterra/work-with-design-systems](https://github.com/natdexterra/work-with-design-systems) | 53 | 从 Claude Code 检查、构建或扩展 Figma 设计系统；支持只读审计、WCAG 检查、组件评分，构建模式含变量绑定和 slots，可选 Phase… | [SAFE](https://agentskillshub.top/skill/natdexterra/work-with-design-systems/) |
| [lemonteaau/smartisan-ui-skill](https://github.com/lemonteaau/smartisan-ui-skill) | 38 | 用于构建 Smartisan OS 风格 UI 的 agent skill | [SAFE](https://agentskillshub.top/skill/lemonteaau/smartisan-ui-skill/) |
| [seungdori/web-stylebook-mcp](https://github.com/seungdori/web-stylebook-mcp) | 29 | 为 AI coding agents 提供评分设计方向、UI-state 方案和 WCAG 检查的 design tokens。确定性、离线、无需 API k… | [SAFE](https://agentskillshub.top/skill/seungdori/web-stylebook-mcp/) |
| [ake77-code/distill-design](https://github.com/ake77-code/distill-design) | 27 | 将任意网站提炼为 DESIGN.md——AI 可直接读取、用于生成符合品牌 UI 的纯文本设计规范。 | [SAFE](https://agentskillshub.top/skill/ake77-code/distill-design/) |
| [dgesteves/onsystem](https://github.com/dgesteves/onsystem) | 20 | 让 coding agents 遵循设计系统：检查颜色、原生元素和缺失 API，并提供修复；配置一次，monorepo 中所有应用生效。 | [SAFE](https://agentskillshub.top/skill/dgesteves/onsystem/) |
| [mmohajer9/video-to-ui](https://github.com/mmohajer9/video-to-ui) | 15 | 将 UI 屏幕录制转为设计数据、代码修改或可运行的 React 脚手架。Claude Code skill。 | [SAFE](https://agentskillshub.top/skill/mmohajer9/video-to-ui/) |
| [Eronred/designspec](https://github.com/Eronred/designspec) | 12 | 让 AI 编写的 UI 遵循设计系统：coding agents 遵循、CI 强制执行的 tokens 和 components 规范。 | [SAFE](https://agentskillshub.top/skill/Eronred/designspec/) |
| [imsaif/design-with-claude](https://github.com/imsaif/design-with-claude) | 11 | dwic 是终端内的产品设计工具。运行 npx dwic-audit 检查 WCAG 对比度、令牌偏移和结构缺口，由48名设计专家修复，并跨会话记住设计决策。 | [SAFE](https://agentskillshub.top/skill/imsaif/design-with-claude/) |
| [kalilfagundes/design-system-extractor-skill](https://github.com/kalilfagundes/design-system-extractor-skill) | 9 | Claude/Antigravity/Opencode AI skill，可从任意网站逆向分析设计系统，提取颜色、字体、间距和组件，生成交互式 HTML 文档。 | [SAFE](https://agentskillshub.top/skill/kalilfagundes/design-system-extractor-skill/) |
| [juanlara-aidev/macos-26-design](https://github.com/juanlara-aidev/macos-26-design) | 7 | macOS 26（Liquid Glass）可作为 Claude Code、Cursor 和 Gemini CLI 的即插即用 skill。 | [SAFE](https://agentskillshub.top/skill/juanlara-aidev/macos-26-design/) |
| [KunalKumarkkr01/design-system-extractor](https://github.com/KunalKumarkkr01/design-system-extractor) | 5 | 用Chrome DevTools MCP逆向网站设计系统，生成design.md和截图；支持agent skill、Claude Code插件、npx安装器。 | [SAFE](https://agentskillshub.top/skill/KunalKumarkkr01/design-system-extractor/) |
| [kenneives/design-token-bridge-mcp](https://github.com/kenneives/design-token-bridge-mcp) | 5 | 在 Tailwind、Figma、CSS 与 Material 3、SwiftUI、CSS Variables 之间转换设计令牌的 MCP server，用于… | [SAFE](https://agentskillshub.top/skill/kenneives/design-token-bridge-mcp/) |

<a id="type-tool_mcp"></a>
## 🔌 Figma 与设计工具

[在在线页面打开这一类,按星数排序 →](https://agentskillshub.top/best/ai-design/#type-tool_mcp)

| 仓库 | 星数 | 做什么 | 安全评级 |
|---|---:|---|---|
| [GLips/Figma-Context-MCP](https://github.com/GLips/Figma-Context-MCP) | 16.2k | 为 Cursor 等 AI 编程 agent 提供 Figma 布局信息的 MCP server | [SAFE](https://agentskillshub.top/skill/GLips/Figma-Context-MCP/) |
| [southleft/figma-console-mcp](https://github.com/southleft/figma-console-mcp) | 3.3k | 将你的设计系统作为 API。连接 AI 与 Figma，用于提取、创建和调试。 | [SAFE](https://agentskillshub.top/skill/southleft/figma-console-mcp/) |
| [arinspunk/claude-talk-to-figma-mcp](https://github.com/arinspunk/claude-talk-to-figma-mcp) | 676 | 支持 Claude Desktop、Claude Code、Cursor、Antigravity 等 AI 工具读取、分析和修改 Figma 设计的 Mode… | [SAFE](https://agentskillshub.top/skill/arinspunk/claude-talk-to-figma-mcp/) |
| [penpot/penpot-mcp](https://github.com/penpot/penpot-mcp) | 535 | Penpot 官方 MCP 服务器 | [SAFE](https://agentskillshub.top/skill/penpot/penpot-mcp/) |
| [moguzbulbul/blueprint-animation](https://github.com/moguzbulbul/blueprint-animation) | 432 | Claude Design skill：通过蓝图绘图逐步讲解动画化的改版前→改版后 UX 设计，作者 @moguzbulbul。 | [SAFE](https://agentskillshub.top/skill/moguzbulbul/blueprint-animation/) |
| [TranHoaiHung/figma-ui-mcp](https://github.com/TranHoaiHung/figma-ui-mcp) | 266 | AI 可通过 JavaScript 在 Figma 画布绘制 UI，并将现有设计读取为结构化数据。支持 Claude Code、Cursor、VS Code… | [SAFE](https://agentskillshub.top/skill/TranHoaiHung/figma-ui-mcp/) |
| [noemuch/bridge](https://github.com/noemuch/bridge) | 156 | 使用 Claude Code 在 Figma 中设计。Bridge 通过 WebSocket 将终端连接到 Figma Plugin API。 | [SAFE](https://agentskillshub.top/skill/noemuch/bridge/) |
| [alima-max/prototype-to-figma-skill](https://github.com/alima-max/prototype-to-figma-skill) | 142 | Claude skill：分析Claude Code原型，用搜索和Code Connect映射至Figma设计系统，逐状态生成画面并标注触发器、转换和边界情况 | [SAFE](https://agentskillshub.top/skill/alima-max/prototype-to-figma-skill/) |
| [hoangpm96/reqwise-figma-mcp](https://github.com/hoangpm96/reqwise-figma-mcp) | 106 | 配套 Figma plugin 的 MCP server，让 AI agents 安全读取和绘制 Figma canvas，提供结构化验证、默认安全绘图和多窗… | [SAFE](https://agentskillshub.top/skill/hoangpm96/reqwise-figma-mcp/) |
| [pmlaowangba-lab/laowangba-pmprototype-skill](https://github.com/pmlaowangba-lab/laowangba-pmprototype-skill) | 105 | 用于产品原型生成的 Codex skill，包含 IA、设计门禁、页面 UI YAML 和 Figma 工作流。 | [SAFE](https://agentskillshub.top/skill/pmlaowangba-lab/laowangba-pmprototype-skill/) |
| [youware-labs/figma-pilot](https://github.com/youware-labs/figma-pilot) | 105 | 通过代码执行让 AI agent 控制 Figma 的 MCP | [SAFE](https://agentskillshub.top/skill/youware-labs/figma-pilot/) |
| [HuolalaTech/huolala-figma-mcp](https://github.com/HuolalaTech/huolala-figma-mcp) | 85 | 货拉拉内部的 MCP 服务，可将 Figma 设计自动转换为高保真 UI 代码。 | [SAFE](https://agentskillshub.top/skill/HuolalaTech/huolala-figma-mcp/) |
| [alvinindra/figma-mcp-rust](https://github.com/alvinindra/figma-mcp-rust) | 79 | 用 Rust 构建的 Figma MCP，通过插件提供完整读写权限（无 REST API、无速率限制，含 73 个工具） | [SAFE](https://agentskillshub.top/skill/alvinindra/figma-mcp-rust/) |
| [AsifKabirAntu/figsor](https://github.com/AsifKabirAntu/figsor) | 73 | Figsor 是连接 Cursor 与 Figma 的 MCP server，支持通过聊天在 Figma 画布中创建和编辑设计。 | [SAFE](https://agentskillshub.top/skill/AsifKabirAntu/figsor/) |
| [pro-vi/designer](https://github.com/pro-vi/designer) | 61 | 用于 Claude Design 的 MCP / CLI | [SAFE](https://agentskillshub.top/skill/pro-vi/designer/) |
| [BIAsia/c2d2c](https://github.com/BIAsia/c2d2c) | 58 | 代码→设计→代码：Claude Code skills 连接 Figma 与生产代码库：d2c / c2d / ds-govern。安装：npx skills… | [SAFE](https://agentskillshub.top/skill/BIAsia/c2d2c/) |
| [runkids/figma-to-prompt](https://github.com/runkids/figma-to-prompt) | 8 | Figma 插件：将设计画板提取为结构化 JSON 和 AI 代码生成提示词 | [SAFE](https://agentskillshub.top/skill/runkids/figma-to-prompt/) |

<a id="type-to_code"></a>
## 🧱 设计稿转代码

[在在线页面打开这一类,按星数排序 →](https://agentskillshub.top/best/ai-design/#type-to_code)

<table><tr>
<td align="center" valign="top"><a href="https://github.com/precious112/caret-desktop"><img src="assets/previews/precious112__caret-desktop.gif" width="260" alt="precious112/caret-desktop"></a><br><sub><a href="https://github.com/precious112/caret-desktop">precious112/caret-desktop</a></sub></td>
</tr></table>

| 仓库 | 星数 | 做什么 | 安全评级 |
|---|---:|---|---|
| [onlook-dev/onlook](https://github.com/onlook-dev/onlook) | 27.2k | 面向设计师的开源 AI 优先开发工具，用 AI 可视化构建、设置样式和编辑代码。 | [SAFE](https://agentskillshub.top/skill/onlook-dev/onlook/) |
| [google-labs-code/stitch-skills](https://github.com/google-labs-code/stitch-skills) | 8.7k | 面向 Stitch MCP server 的 Agent Skills 库，遵循 Agent Skills 开放标准，兼容 Antigravity、Gemin… | [SAFE](https://agentskillshub.top/skill/google-labs-code/stitch-skills/) |
| [OpenCoworkAI/open-codesign](https://github.com/OpenCoworkAI/open-codesign) | 8.2k | 开源 Claude Design 替代，一键导入 Claude Code/Codex API key，Prompt 生成原型、幻灯片、PDF，支持多模型。 | [SAFE](https://agentskillshub.top/skill/OpenCoworkAI/open-codesign/) |
| [ZSeven-W/openpencil](https://github.com/ZSeven-W/openpencil) | 7.2k | 开源 AI 原生矢量设计工具，支持并发 Agent Teams。Design-as-Code。在实时画布上将提示词转换为 UI，替代 Pencil。 | [SAFE](https://agentskillshub.top/skill/ZSeven-W/openpencil/) |
| [nolangz/pixel2motion](https://github.com/nolangz/pixel2motion) | 2.6k | AI logo 动画 skill：把位图 logo 转成 SVG 动画、HTML 动画演示、GIF/视频预览和动效 QA 证据 | [SAFE](https://agentskillshub.top/skill/nolangz/pixel2motion/) |
| [kgoedecke/doop](https://github.com/kgoedecke/doop) | 1.9k | Paper.design 的开源替代方案。支持人类与 AI agent 实时协作设计的多人画布，内置 MCP。 | [SAFE](https://agentskillshub.top/skill/kgoedecke/doop/) |
| [oil-oil/draw-ui](https://github.com/oil-oil/draw-ui) | 550 | Claude Code skill：通过 ZenMux 使用 GPT Image 2 生成 UI 设计稿 | [SAFE](https://agentskillshub.top/skill/oil-oil/draw-ui/) |
| [lassejlv/loora](https://github.com/lassejlv/loora) | 144 | 可供 agent 编辑的画布设计工具。在画布上排列结构化 UI 节点，通过 MCP 连接 Claude、Codex、Cursor 或 opencode | [SAFE](https://agentskillshub.top/skill/lassejlv/loora/) |
| [ReScienceLab/super-prototyping](https://github.com/ReScienceLab/super-prototyping) | 92 | AI agent产品验证系统：创意→Logo→产品→品牌→发布视频。桌面应用，支持 Claude Code 和 Codex 的 skill。 | [SAFE](https://agentskillshub.top/skill/ReScienceLab/super-prototyping/) |
| [precious112/caret-desktop](https://github.com/precious112/caret-desktop) | 50 | Caret——覆盖真实代码的设计画布。点击标题重写、选颜色或拖动边缘，改动直接写入源文件。开源，可在本机运行。 | [CAUTION](https://agentskillshub.top/skill/precious112/caret-desktop/) |
| [sso-ss/vibe-ship-it](https://github.com/sso-ss/vibe-ship-it) | 12 | 设计师AI skill/agent，支持VS Code Copilot、Claude Code、OpenAI Codex；DESIGN.md提取网站设计系统。 | [SAFE](https://agentskillshub.top/skill/sso-ss/vibe-ship-it/) |
| [cychien/ezdesign](https://github.com/cychien/ezdesign) | 7 | The best way to design with AI agents. | [SAFE](https://agentskillshub.top/skill/cychien/ezdesign/) |

<a id="type-graphics"></a>
## 🖼 海报与品牌

[在在线页面打开这一类,按星数排序 →](https://agentskillshub.top/best/ai-design/#type-graphics)

| 仓库 | 星数 | 做什么 | 安全评级 |
|---|---:|---|---|
| [nexu-io/html-anything](https://github.com/nexu-io/html-anything) | 9.5k | 本地 AI agent 编写 HTML，支持 75 skill、9 种形式、沙箱预览和多格式导出；兼容 Claude Code、Cursor、Codex 等。 | [SAFE](https://agentskillshub.top/skill/nexu-io/html-anything/) |
| [kaankiziltug/logo-design-skill](https://github.com/kaankiziltug/logo-design-skill) | 6.5k | 面向 Claude、Gemini CLI、Codex 等 AI agent 的徽标设计 skill：原则、流程、SVG 制作、测试工具及 1,400+ 个徽标… | [SAFE](https://agentskillshub.top/skill/kaankiziltug/logo-design-skill/) |
| [yanliudesign/mono-color-skill](https://github.com/yanliudesign/mono-color-skill) | 3.6k | 单色编辑印刷图像 skill——暖色纸张、半色调摄影、灵活留白与克制排版。 | [SAFE](https://agentskillshub.top/skill/yanliudesign/mono-color-skill/) |
| [op7418/logo-generator-skill](https://github.com/op7418/logo-generator-skill) | 2.4k | logo-generator-skill | [SAFE](https://agentskillshub.top/skill/op7418/logo-generator-skill/) |
| [joeseesun/qiaomu-mondo-poster-design](https://github.com/joeseesun/qiaomu-mondo-poster-design) | 1.4k | 生成海报、书籍封面、专辑封面等设计作品，支持电影海报、读书笔记、公众号封面和小红书配图。含AI提示词优化、风格对比、图生图，默认9:16竖版。 | [SAFE](https://agentskillshub.top/skill/joeseesun/qiaomu-mondo-poster-design/) |
| [kubai087/kubai-icons](https://github.com/kubai087/kubai-icons) | 633 | 一个 Claude skill，以统一风格绘制动态图标，支持悬停动效或静态 SVG。 | [SAFE](https://agentskillshub.top/skill/kubai087/kubai-icons/) |
| [neonwatty/logo-designer-skill](https://github.com/neonwatty/logo-designer-skill) | 198 | 用于通过引导式探索和迭代创建及优化 SVG 标志的 agent skill。 | [SAFE](https://agentskillshub.top/skill/neonwatty/logo-designer-skill/) |
| [SpaceZephyr/design-buddy](https://github.com/SpaceZephyr/design-buddy) | 188 | Design Buddy：用于品牌设计系统、GPT-image-2 图像、图表、信息图、Logo、幻灯片、微信排版和社交图片的视觉制作 Agent Skills | [SAFE](https://agentskillshub.top/skill/SpaceZephyr/design-buddy/) |
| [dososo/blcaptain-style-skill](https://github.com/dososo/blcaptain-style-skill) | 187 | 图文卡片生成 Skill：内容→海报级组图（小红书3:4/公众号封面）；1引擎+3种视觉语言：静纸 Still Paper、实证 Signal Proof、图… | [SAFE](https://agentskillshub.top/skill/dososo/blcaptain-style-skill/) |
| [dacnay816y62-hub/fantasy-dongfang-jianyuehaibao](https://github.com/dacnay816y62-hub/fantasy-dongfang-jianyuehaibao) | 126 | 东方文化编辑海报 v2 Codex skill：Image 2 出图、中文标题精炼、真实文化物证、A/B/C 测试 | [SAFE](https://agentskillshub.top/skill/dacnay816y62-hub/fantasy-dongfang-jianyuehaibao/) |
| [luji12/daily-photo-playground](https://github.com/luji12/daily-photo-playground) | 83 | 将日常照片重构为3:4高饱和情绪化编辑海报的 Codex skill | [SAFE](https://agentskillshub.top/skill/luji12/daily-photo-playground/) |
| [dacnay816y62-hub/regional-culture-poster](https://github.com/dacnay816y62-hub/regional-culture-poster) | 69 | 将中国地域文化转化为克制、当代的大字海报与编辑海报，非旅游宣传。 | [SAFE](https://agentskillshub.top/skill/dacnay816y62-hub/regional-culture-poster/) |
| [beyondtahir/beyondartist](https://github.com/beyondtahir/beyondartist) | 67 | AI design skill for freelancers, content creators and digital marketers. Think like a designer. Execute like an artist. | [SAFE](https://agentskillshub.top/skill/beyondtahir/beyondartist/) |
| [dabodamjan/poster-maker](https://github.com/dabodamjan/poster-maker) | 13 | Claude Code 的 AI 传单和海报生成器，描述设计即可获取可编辑 HTML/CSS，并导出高清 PNG 或 PDF。 | [SAFE](https://agentskillshub.top/skill/dabodamjan/poster-maker/) |

<a id="type-review"></a>
## 🔍 设计审查

[在在线页面打开这一类,按星数排序 →](https://agentskillshub.top/best/ai-design/#type-review)

| 仓库 | 星数 | 做什么 | 安全评级 |
|---|---:|---|---|
| [Owl-Listener/designer-skills](https://github.com/Owl-Listener/designer-skills) | 3.3k | 设计技能集合：用于设计的 agentic skills、commands 和 plugins，涵盖研究、系统、UI、交互和交付。 | [SAFE](https://agentskillshub.top/skill/Owl-Listener/designer-skills/) |
| [kylezantos/design-motion-principles](https://github.com/kylezantos/design-motion-principles) | 1.5k | 用于动效设计审查的 Claude Code skill，基于 Emil Kowalski、Jakub Krehel 和 Jhey Tompkins 训练，提供… | [SAFE](https://agentskillshub.top/skill/kylezantos/design-motion-principles/) |
| [funboy322/avoid-ai-design](https://github.com/funboy322/avoid-ai-design) | 157 | 审查并重写 AI 生成的前端，去除紫色渐变、奶油+陶土色和单色默认样式。附零依赖扫描器，是 avoid-ai-writing 的设计对应工具。 | [SAFE](https://agentskillshub.top/skill/funboy322/avoid-ai-design/) |
| [evidence-codes/loom](https://github.com/evidence-codes/loom) | 8 | 面向 AI 网站的设计工作流：真实截图、设计采用、沉淀规范、安全预览；基于 impeccable 适配 Claude Code。 | [SAFE](https://agentskillshub.top/skill/evidence-codes/loom/) |

**安全评级**是 Agent Skills Hub 对仓库 README 和安装步骤的评级。*待评级*表示目录还没评到它。

预览图是各项目 README 里图片的缩小副本,只收录采用宽松许可证的项目,版权归原作者所有。来源和许可证见 [assets/previews/NOTICE.md](assets/previews/NOTICE.md)。如需移除请提 issue。

## 相关合集

- [zhuyansen/awesome-claude-video-skills](https://github.com/zhuyansen/awesome-claude-video-skills), [zhuyansen/awesome-codex-ppt-skills](https://github.com/zhuyansen/awesome-codex-ppt-skills) —— 同样做法的合集。

## 推荐仓库

提一个 issue 附上 GitHub 链接。它会走和每个条目一样的评审;决定上不上榜的是上面的规则,不是星数。

---

机器可读版本:[`data/skills.json`](data/skills.json)。生成于 2026-11-10。
