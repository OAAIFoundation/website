# The Open Agentic AI Foundation

这是一个静态网站，用于展示开放代理式人工智能基金会（Open Agentic AI Foundation）的使命、战略支柱、项目计划、成员组织与社区资源。站点包含首页与关于页面，内容结构一致，并支持多语言切换。

## 概览

该基金会被定位为一个全球联盟，通过共享标准、资金支持与治理机制，推动安全、开放、可互操作的 Agentic AI 发展。网站强调公开路线图、社区参与以及多区域项目计划。

## 首页内容（index.html）

- Hero：使命宣言、主要行动入口与关键指标。
- 动态时间线：季度里程碑（安全基准、互操作标准、全球峰会）。
- 使命：开放协议、安全与保障、包容性治理。
- 战略支柱：基础设施（参考架构）、标准（互操作与信任）、影响力（生态项目）。
- 项目计划：2024-2025 的 Open Agent Safety Benchmark、Interoperability Lab、Global Builder Summits、Open Impact Fund 等。
- 成员组织：AWS、Anthropic、Block、Bloomberg、Cloudflare、Google、Microsoft、OpenAI。
- 社区：开放与中立治理、安全优先实践、全球化参与。
- 资源：路线图、社区论坛、资助计划。
- 参与号召：加入联盟或浏览资源。

## 关于页面内容（about.html）

- 基金会概览与使命。
- 战略支柱（章程）与成员组织。
- 资源板块：路线图、社区与资金支持入口。

## 国际化

站点通过 `data-i18n` 属性与语言切换器实现多语言。翻译内容位于 `assets/js/app.js`，并通过 `localStorage` 的 `oaif-lang` 键持久化。支持语言包括英语、简体中文、繁体中文、日语与法语。

## 项目结构

- `index.html`：首页。
- `about.html`：关于页面。
- `assets/css/style.css`：全局样式。
- `assets/js/app.js`：语言切换、平滑滚动与导航状态逻辑。

## 本地预览

直接用浏览器打开 `index.html`，或使用任意静态文件服务器提供目录服务。

## 许可协议

MIT。详见 `LICENSE`。
