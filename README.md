<p align="center">
  <img src="assets/liora.png" alt="" width="68" height="68">
</p>

<h1 align="center">Liora · 知光</h1>

<p align="center"><strong>让想法，成为生产力。</strong></p>
<p align="center">本地优先的知识库与 AI 工作台<br>Local-first knowledge, notes and AI, in one workspace.</p>

<p align="center">
  <a href="https://ai-turing.cn/"><strong>官方网站 / Website ↗</strong></a> ·
  <a href="#下载与开始"><strong>下载 macOS</strong></a> ·
  <a href="#english">English</a> ·
  <a href="https://github.com/sheely8989/liora-releases/releases">更新记录</a>
</p>

<a href="https://ai-turing.cn/">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/hero-dark.webp">
  <img src="assets/hero-light.webp" alt="Liora 官网：让想法成为生产力，展示真实知识工作台" width="1280">
</picture>
</a>

<p align="center">个人版免费 · 无内购 · 简体中文 / English / 日本語</p>

<a name="中文介绍"></a>

## 留住资料，也让知识用起来

用 Markdown 写作，用链接连接笔记，用自己的模型查阅资料、整理想法和执行任务。普通笔记与附件保存在你选择的本地文件夹里，核心编辑与资料管理可离线使用。

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/workspace-dark.webp">
  <img src="assets/workspace-light.webp" alt="Liora 本地 Markdown 工作台，使用自有演示笔记" width="1280">
</picture>

## 让 AI 带着你的知识工作

选择一篇笔记、几份资料或知识库范围提问，沿着来源引用核对答案。需要执行任务时，使用 Agent、Skills、工具与 MCP，把研究和写作接下去。

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/ai-knowledge-dark.webp">
  <img src="assets/ai-knowledge-light.webp" alt="Liora 知识库问答：示例回答、来源快照和资料引用" width="1280">
</picture>

## 桌面上的小伙伴，也能接住任务

选一只猫、兔子或虚拟伙伴，在桌面开始对话。后台任务只更新小小的椭圆进展；点击才展开，执行细节默认收起。同一段会话，也能回主窗口接着聊。

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/pet-dark.webp">
  <img src="assets/pet-light.webp" alt="桌宠的两种状态：默认收起的椭圆进展，以及点击后展开、执行过程仍折叠的会话" width="1280">
</picture>

## 从关键词，到更多线索

中英文全文检索、向量语义检索与混合检索，结合文件夹、类型、标签和文档关系找回资料。全文索引自动更新；语义检索与图谱需先在设置中配置和处理。

<img src="assets/search.webp" alt="中文全文检索演示：关键词、筛选条件和搜索结果" width="1280">

| 你的资料 | 你的工作方式 |
| --- | --- |
| **逐项导入**：支持 Obsidian、Notion 和常见文档；ZIP 解包总量上限 4 GB，处理过程显示进度。 | **技能市场**：浏览国内与国际来源，查看说明后安装 Skills，按需启停与卸载。 |
| **阅读与整理**：PDF、电子表格、OCR、双向链接、标签、属性、画布与任务日历。 | **开放扩展**：配置自己的模型、Agent、MCP、应用连接与自定义应用。 |
| **历史与备份**：回看版本、恢复内容，以开放格式导出和迁移。 | **本地保存**：笔记与附件留在本机；在线 AI 按需连接到你配置的服务。 |

以上为真实应用界面，使用演示资料。截图展示当前开发版本，实际功能以所安装版本为准。完整动态展示请访问[官方网站](https://ai-turing.cn/)。

## 下载与开始

**当前公开版本：v0.1.14**（2026-10-28 核实）。

| 你的 Mac | 安装包 |
| --- | --- |
| Apple Silicon · M 系列芯片 | [下载 arm64 DMG](https://github.com/sheely8989/liora-releases/releases/download/v0.1.14/Liora-0.1.14-arm64.dmg) |
| Intel · x64 | [下载 x64 DMG](https://github.com/sheely8989/liora-releases/releases/download/v0.1.14/Liora-0.1.14-x64.dmg) |

[查看最新版本与 ZIP 包](https://github.com/sheely8989/liora-releases/releases/latest)。Windows 与移动版尚未开放下载。

1. 打开 DMG，将 Liora 拖入“应用程序”。
2. 创建或选择本地知识库，开始写作或导入已有资料。
3. 需要 AI 时，在“设置 → 模型配置”中连接自己的模型服务。

AI 模型服务可能单独收费。在线 AI 会把相关对话与选中的内容发送给所配置的服务商；本地保存不等于离线推理。

<details>
<summary><strong>展开完整功能与使用说明（中文）</strong></summary>

Liora · 知光是一款本地优先的个人知识管理桌面应用，将 Markdown 笔记、双向链接、知识图谱、资料集合、可视化创作、任务日历和可配置的 AI 助手整合在一起。适合搭建个人知识库、整理学习与研究资料、管理项目笔记，以及持续记录日常想法。

基础笔记与本地资料管理可离线使用，无需注册 Liora 云账号。AI 和第三方连接按需配置。

### 功能一览

#### 写作与日常记录

- **Markdown 与可视化编辑**：在可视化编辑和 Markdown 源码之间切换，支持斜杠菜单、块拖动、表格、公式、脚注、代码块，以及本地图片粘贴、拖入和尺寸调整。
- **每日笔记与模板**：按日期记录，使用带日期变量、标签和属性的模板快速新建笔记。
- **笔记整理**：文件夹、标签、收藏、书签、标签页、笔记移动与复制，以及可预览的内容提取和合并。
- **阅读与展示**：文档大纲、字数统计、录音附件、Markdown 幻灯片，以及带附件的静态网站导出。

#### 知识关联与检索

- **双向链接与块引用**：使用 `[[笔记]]` 连接内容，查看反向链接、出链、未链接提及和悬停预览。
- **关系图谱**：通过局部图谱与全库图谱探索笔记之间的联系。
- **全文、语义与混合检索**：检索中英文全文，或通过向量查找相近含义，配合类型、标签、属性、文件夹和日期筛选。全文索引自动更新；语义检索需要先配置向量模型并手动运行向量化。用于关联检索的图谱需手动构建，当前整理文档引用、标签与文件夹关系，不自动推断实体。
- **结构化资料集合**：自定义属性，使用表格、列表、卡片和看板视图，结合筛选、排序与只读计算列整理资料。

#### 画布、表格与可视化创作

- **知识画布**：把笔记、文字和图片放到同一画布，支持分组、连线和 JSON Canvas 导入导出。
- **白板、思维导图与流程图**：梳理想法、绘制流程，支持 Mermaid 图表；白板可导出 PNG / SVG。
- **电子表格**：在知识工作台中编辑表格，配合资料导入处理结构化信息。

#### 任务与日历

- **待办管理**：未排期任务、日期与时间安排、截止时间、重复任务、完成状态和来源笔记关联。
- **日 / 周 / 月日历**：在清单与日历中查看安排，使用应用运行期间的任务提醒。
- **Google 日历**：桌面端配置自己的 Google OAuth 客户端并授权后，可只读查看主日历事件；编辑事件可跳转 Google 日历。

#### 资料导入与阅读

- **导入中心**：文件、文件夹和 ZIP 批量导入。ZIP 解包总量上限 4 GB，文件逐项处理并显示进度；导入后的正文、图片与附件保存到正式知识库。支持预览、目录保留、追加标签、重复检测、增量更新、报告和受冲突检查保护的批次撤销。
- **笔记应用迁移**：支持 Obsidian、Notion 导出包、Evernote / 印象笔记 ENEX、Google Keep Takeout、Bear / Craft 的 Markdown 或 TextBundle、Logseq 和 Roam 等来源。
- **常用文件格式**：Markdown、TXT、HTML、DOCX、PDF、CSV / TSV / DSV、XLSX、ODS、OPML、EPUB，以及 Trello JSON。不同格式的转换范围不同；复杂版式、数据库关系、公式和插件能力不保证完整复原。
- **PDF 与 OCR**：本地阅读、文本搜索、逐页 OCR，校对后保存带原文件与页码的摘录。扫描件的 OCR 在阅读工具中执行，导入时不会自动识别。
- **网页资料收集**：粘贴网页 HTML 或文本，整理正文并保留来源 URL 和快照。

#### AI 对话与 Agent

- **模型服务自选**：配置服务商、模型和凭据，支持兼容 Chat Completions、Responses 或 Anthropic Messages 的自定义接口，并提供连接测试。
- **知识库问答**：选择当前笔记、指定资料或知识库范围，结合检索到的来源回答，查看来源引用；支持将单来源回复审阅后保存为新笔记或替换来源正文。
- **Agent 工作流**：流式回复、工具执行详情、补充要求、消息排队、上下文压缩，以及保存在本地的会话历史。
- **项目与文件上下文**：按项目组织对话、设置工作目录，通过 `@` 引用项目文件。
- **自定义助手与技能**：创建 Agent，从国内或国际技能源浏览、查看并安装完整 Skills，管理启停与卸载。也可复用自己的 Markdown Skills，配置 HTTP 工具，并接入 MCP、提示词与扩展。第三方技能不代表官方认证。
- **桌宠对话**：在桌面发起会话，后台任务默认只显示椭圆进展；点击才展开对话，执行过程仍默认折叠。同一会话可回主窗口继续。

知识库范围问答关闭文件与 Shell 等执行工具；通用 Agent 模式可按任务使用本机文件和工具，工作目录不构成文件访问沙箱。AI 需要用户自行配置模型服务，相关对话与选中的内容会发送给该服务；本地存储不代表离线推理。

#### 应用连接与资料同步

- **应用连接目录**：包含 Notion、Confluence、Wikipedia、Google Drive、OneDrive、Box、SharePoint、Gmail、Outlook、Google Calendar、Slack、Microsoft Teams、GitHub、Linear、Jira 和 Asana。
- **按需调用工具**：连接后发现实际可用工具，可限制允许的工具，并为对话选择连接。各服务支持的搜索、读取或写入能力不同，取决于适配范围、账号权限与服务方。
- **自定义 MCP**：连接远程 MCP 服务或本机 stdio 程序。
- **Confluence 同步到本地**：为自建 Server / Data Center 配置 REST API 与 PAT，选择空间或页面，单向拉取 Markdown 和附件，支持定时同步与冲突处理。
- **企业微信 Agent**：配置 API 模式机器人、绑定项目和允许使用的成员后，可从企业微信发起对话，记录保存在 Liora 的项目会话中；主机需保持在线。

应用连接用于按需访问外部服务，不代表所有来源都会自动导入或持续同步。第三方功能需要相应凭据、网络与账号权限。

#### 本地数据、历史与备份

- **自选知识库目录**：创建、打开或切换本地知识库，按项目或用途分别保存资料。
- **普通 Markdown 文件**：普通文件夹对应磁盘目录，笔记正文保存为 `.md`，附件独立保存。已有受管理 Markdown 的外部正文修改会在下次读取时更新索引；新增外部文件仍需导入。
- **自动保存与历史版本**：查看版本差异、固定重要版本、恢复旧版本，并使用回收站与本地恢复点。
- **导出与迁移**：开放格式资料导出，完整笔记 ZIP 备份包含笔记、模板、历史版本及相关附件。
- **个人局域网访问**：在主机开启后，同一局域网的设备可通过浏览器和访问码使用同一知识库；主机需保持运行。

笔记 ZIP 备份不包含 AI 会话和模型凭据。名为“保险柜”的文件夹使用数据库保存内容，当前尚未加密。局域网访问不是跨设备自动同步，也不提供实时协同。

#### 工作台外观

支持跟随系统、白天、晚上和卡漫风格，以及工作区布局保存、恢复与标签页固定。

### 下载与开始使用

前往 **[最新版本](https://github.com/sheely8989/liora-releases/releases/latest)**，按发行说明选择对应安装包。

截至 2026-10-28，已核对的公开版本为 **v0.1.14**，提供 **macOS Apple Silicon arm64** 与 **Intel x64** 两种安装包。Windows 和移动版尚未开放下载；实际可用版本以 Releases 中的安装包为准。

1. 下载 `.dmg`，打开后将 Liora 拖入“应用程序”。
2. 首次启动时创建或选择一个 Liora 知识库。已有 Markdown / Obsidian 资料请通过导入中心添加。
3. 创建第一篇笔记，或导入已有资料；需要 AI 时再到“设置 → 模型配置”填写自己的服务信息。
4. 已安装正式版可在“设置 → 应用更新”检查新版本。

`.zip` 包含应用，也用于自动更新；`.blockmap` 与 `latest-mac.yml` 是更新辅助文件，无需手动安装。

### 当前范围

Liora 正处于早期迭代，具体功能以所安装版本为准。跨设备自动同步、实时协作和知识库加密尚未提供；移动端仍在开发。静态网站导出不包含托管服务，Obsidian 资料导入也不包含其社区插件运行环境。

本仓库用于发布 Liora 安装包、更新文件和产品说明，应用源码另行维护，不在此仓库公开。

</details>

## English

**Liora is a local-first knowledge and AI workspace.** Write in Markdown, connect notes, search Chinese and English text, ask questions grounded in selected sources, and extend your workflow with Agents, Skills and MCP. A desktop companion keeps task updates compact until you choose to open the conversation.

The personal edition is free, with no in-app purchases. Bring your own AI provider; that provider may charge for usage. Relevant content is sent to the provider when online AI is used.

**macOS v0.1.14 is available for Apple Silicon and Intel Macs.** [Download the latest release](https://github.com/sheely8989/liora-releases/releases/latest) · [Visit the website](https://ai-turing.cn/?lang=en). Windows and mobile downloads are not available yet. Screenshots show a development build with demonstration material; available features depend on your installed version.

<details>
<summary><strong>Explore all features and usage notes</strong></summary>

Liora is a local-first desktop app for personal knowledge management. It combines Markdown notes, bidirectional links, knowledge graphs, collections, visual tools, task planning and configurable AI assistants. Use it to build a personal knowledge base, organize research, keep project notes and capture everyday ideas.

Core notes and local reference material work offline, without a Liora cloud account. AI services and third-party connections are optional.

### Features

#### Writing and daily notes

- **Markdown and visual editing**: switch between a visual editor and Markdown source. Use slash commands, draggable blocks, tables, math, footnotes, code blocks, and pasted or dropped local images with adjustable sizing.
- **Daily notes and templates**: create date-based notes and reusable templates with date variables, tags and default properties.
- **Note organization**: folders, tags, favorites, bookmarks, tabs, moving and copying notes, plus previewable content extraction and merging.
- **Reading and presentation**: document outlines, word counts, audio recording attachments, Markdown slides and static website export with attachments.

#### Connected knowledge and search

- **Bidirectional links and block references**: connect notes with `[[wikilinks]]`, inspect backlinks and outgoing links, find unlinked mentions and preview linked notes on hover.
- **Knowledge graphs**: explore connections in local and whole-library graph views.
- **Full-text, semantic and hybrid search**: search Chinese and English text or find related meanings with vectors, with type, tag, property, folder and date filters. Full-text indexes update automatically. Semantic search requires an embedding model and manual vectorization; relationship search requires a manually built graph of document references, tags and folders. It does not infer entities.
- **Structured collections**: define properties and organize material in table, list, card or kanban views with filtering, sorting and read-only calculated columns.

#### Canvas, spreadsheets and visual thinking

- **Knowledge canvas**: combine notes, text and images with groups and connections; import and export JSON Canvas.
- **Whiteboards, mind maps and flowcharts**: develop ideas visually, create Mermaid diagrams and export whiteboards as PNG or SVG.
- **Spreadsheets**: edit tables alongside your notes and use the import tools to work with structured information.

#### Tasks and calendar

- **Task planning**: manage unscheduled tasks, dates and time slots, deadlines, recurring tasks, completion status and links to source notes.
- **Day, week and month views**: review plans in a list or calendar, with reminders while the app is running.
- **Google Calendar**: configure your own Google OAuth desktop client to view primary-calendar events read-only. Open Google Calendar to edit an event.

#### Importing and reading material

- **Import center**: import files, folders and ZIP archives, with a 4 GB total extracted ZIP limit and progress as files are processed one by one. Imported text, images and attachments are saved in the knowledge base. Includes previews, folder preservation, tags, duplicate detection, incremental updates, reports and conflict-checked batch undo.
- **Migration from note apps**: import supported exports from Obsidian, Notion, Evernote / Yinxiang ENEX, Google Keep Takeout, Bear / Craft Markdown or TextBundle, Logseq and Roam.
- **Common formats**: Markdown, TXT, HTML, DOCX, PDF, CSV / TSV / DSV, XLSX, ODS, OPML, EPUB and Trello JSON. Conversion coverage varies; complex layouts, database relations, formulas and plugins may not be reproduced fully.
- **PDF and OCR**: read PDFs locally, search text, run OCR page by page and save reviewed excerpts linked to the original file and page. Scanned PDFs use the reading tool's OCR; import does not run OCR automatically.
- **Web capture**: paste HTML or text, clean up the content and retain the source URL and snapshot.

#### AI conversations and agents

- **Bring your own model service**: configure providers, models and credentials, including custom endpoints compatible with Chat Completions, Responses or Anthropic Messages. Test connections in settings.
- **Knowledge Q&A**: choose the current note, selected material or a knowledge-base scope, then inspect the retrieved sources behind an answer. Review single-source responses before saving them as new notes or replacing the source text.
- **Agent workflows**: streaming responses, tool execution details, follow-up instructions, queued messages, context compaction and locally stored conversation history.
- **Projects and file context**: group conversations into projects, choose working directories and reference project files with `@`.
- **Custom assistants and skills**: create agents; browse Chinese and international skill sources, inspect and install full skill packages, and enable, disable or remove them. Reuse your own Markdown Skills and connect HTTP tools, MCP servers, prompts and extensions. Third-party skills are not automatically certified by Liora.
- **Desktop companion chat**: start conversations from a pet on your desktop. Background tasks use a compact progress pill until clicked; execution details stay collapsed when opened. Continue the same conversation in the main window.

Scoped knowledge Q&A disables execution tools such as file and shell access. General Agent mode can use local files and tools for a task; its working directory is not a filesystem sandbox. AI requires a model service configured by the user. Relevant conversations and selected content are sent to that service; local storage does not mean offline inference.

#### App connections and source sync

- **Connection catalog**: Notion, Confluence, Wikipedia, Google Drive, OneDrive, Box, SharePoint, Gmail, Outlook, Google Calendar, Slack, Microsoft Teams, GitHub, Linear, Jira and Asana.
- **On-demand tools**: discover available tools, restrict which tools are allowed and select connections for a conversation. Search, read and write capabilities vary by integration, account permissions and provider.
- **Custom MCP**: connect remote MCP services or local stdio programs.
- **Confluence to local files**: configure REST API access and a PAT for self-hosted Server / Data Center, choose spaces or pages, and pull Markdown and attachments with scheduled one-way sync and conflict handling.
- **WeCom agent access**: configure an API-mode bot, a project and allowed members to start conversations from WeCom. History stays in Liora project conversations; the host must remain online.

Connections provide on-demand access to external services. They do not imply automatic import or continuous sync for every source. Third-party features require the relevant credentials, network access and account permissions.

#### Local data, history and backups

- **Choose your knowledge-base folder**: create, open and switch between local libraries for different projects or purposes.
- **Ordinary Markdown files**: regular folders map to disk directories, note bodies are saved as `.md` files and attachments are stored separately. External edits to managed Markdown bodies update the index on the next read; new external files still need to be imported.
- **Autosave and version history**: compare revisions, pin important versions, restore earlier content and use the trash and local recovery checkpoints.
- **Export and migration**: export material in open formats or create a full notes ZIP backup with notes, templates, revision history and related attachments.
- **Personal LAN access**: enable access on the host, then use the same knowledge base from another device's browser with an access code. The host must stay running.

Notes ZIP backups do not include AI conversations or model credentials. Folders called “Vaults” use database storage and are not currently encrypted. LAN access is not automatic cross-device sync or real-time collaboration.

#### Workspace appearance

Choose system, light, dark or illustrated themes. Save and restore workspace layouts and pin tabs.

### Download and get started

Visit the **[latest release](https://github.com/sheely8989/liora-releases/releases/latest)** and choose an installer listed in its release notes.

As checked on October 28, 2026, the public release is **v0.1.14**, with native **Apple Silicon arm64** and **Intel x64** installers for macOS. Windows and mobile downloads are not available yet. Releases list the versions currently available.

1. Download the `.dmg`, open it and drag Liora into Applications.
2. Create or select a Liora knowledge base on first launch. Add existing Markdown or Obsidian material through the import center.
3. Write your first note or import your files. Configure your own AI provider in model settings when needed.
4. Existing release installations can check for updates in Settings → App Updates.

The `.zip` contains the app and is also used for automatic updates. `.blockmap` and `latest-mac.yml` support the updater and do not need manual installation.

### Current scope

Liora is in early development; available features depend on the installed version. Automatic cross-device sync, real-time collaboration and knowledge-base encryption are not yet available. Mobile apps remain in development. Static website export does not include hosting, and importing Obsidian material does not provide an Obsidian community-plugin runtime.

This repository distributes Liora installers, update files and product information. Application source code is maintained separately and is not published here.

</details>

---

<p align="center"><a href="https://ai-turing.cn/"><strong>在官网查看完整体验 / Explore the full website ↗</strong></a></p>

本仓库仅提供安装包、更新文件与产品介绍，应用源码另行维护。
