# Agent Radar Daily｜AI资讯最前沿资料库

这是《AI资讯最前沿》专栏的结构化情报底稿库，用于沉淀国内外 AI 商业、监管、Agent 技术、GitHub 开源生态、AI 投资与产品架构动态。

## 项目定位

本仓库不是普通 AI 新闻收藏夹，而是一个面向公众号内容生产和长期知识沉淀的 AI 行业情报底稿库。

核心目标是：

- 让 AI 资讯收集有稳定信源
- 让日报输出有固定模板
- 让国内外信息可以合并成公众号文章
- 让政策、投资、产品和技术动态可以被长期检索
- 让后续 AI 能读懂并复用本仓库内容

## 项目目标

- 追踪国外 AI 大厂产品与技术更新
- 追踪国内 AI 商业与监管动态
- 记录 AI Agent、MCP、CLI、Coding Agent、Skills 等技术趋势
- 关注中外 AI 政策和监管变化
- 关注 AI 一级市场与二级市场投资动态
- 为微信公众号《AI资讯最前沿》提供结构化底稿
- 构建可被 AI 检索和调用的长期知识库

## 日报核心结构

国外日报目前采用 9 大板块：

1. 今日最重要更新
2. 官方产品 / 技术更新
3. Agent 框架与协议动态
4. GitHub 热门或快速增长项目
5. 海外 AI 政策与监管动态
6. AI 投资与资本市场观察
7. 对 AI 产品架构与产业趋势的启发
8. 可沉淀进个人知识库的概念
9. 建议继续追问的问题

## 信源原则

本项目非常重视优质信源。默认原则是：

- 官方优先
- 英文原始信源优先
- 政策看政府、监管机构、法律文本和标准组织
- 投资看 SEC 文件、公司 IR、财报、公告、交易所文件和权威财经媒体
- GitHub 项目看官方仓库、release、README、issues、stars 和活跃度
- 社区内容只作为线索，不作为最终事实依据
- 重要结论必须尽量附来源链接
- 不确定内容必须明确标注

## 目录说明

- `reports/daily/overseas/`：国外日报
- `reports/daily/china/`：国内日报
- `reports/daily/merged/`：国内外合并日报
- `reports/weekly/`：周报复盘
- `reports/monthly/`：月度趋势复盘
- `sources/official/`：官方信源清单，包括海外 AI 公司、政策监管、投资市场
- `sources/github/`：GitHub 项目信源清单
- `sources/community/`：社区与二级信源清单
- `templates/`：日报、周报、合并稿模板
- `prompts/`：生成日报、合并文章、信源校验等提示词

## 当前目录结构

```text
agent-radar-daily/
├── README.md
├── reports/
│   ├── daily/
│   │   ├── overseas/
│   │   ├── china/
│   │   └── merged/
│   ├── weekly/
│   └── monthly/
├── sources/
│   ├── official/
│   ├── github/
│   └── community/
├── templates/
└── prompts/
```

## 推荐工作流

```text
国外日报生成
  ↓
国内日报生成
  ↓
存入 reports/daily/overseas 与 reports/daily/china
  ↓
使用 templates/daily-merged-template.md 合并
  ↓
形成 reports/daily/merged 下的公众号底稿
  ↓
再编辑成微信公众号《AI资讯最前沿》文章
```

## 重要文件

### 信源文件

- `sources/official/overseas-ai-companies.md`
- `sources/official/overseas-ai-policy.md`
- `sources/official/overseas-ai-investment.md`
- `sources/github/agent-frameworks.md`
- `sources/community/community-watchlist.md`

### 模板文件

- `templates/daily-overseas-template.md`
- `templates/daily-merged-template.md`

### 提示词文件

- `prompts/overseas-daily-prompt.md`
- `prompts/merge-to-wechat-article-prompt.md`
- `prompts/source-verification-prompt.md`

## 内容边界

本项目关注：

- AI 产品与技术更新
- AI Agent、Coding Agent、MCP、Skills、CLI、工作流自动化
- 海外与国内 AI 政策监管
- AI 一级市场与二级市场投资动态
- GitHub 开源生态
- 对 AI 产品架构和产业趋势的启发

本项目暂不重点关注：

- 纯学术论文
- 泛泛模型跑分新闻
- 低价值营销稿
- 未经证实的融资传闻
- 与 AI 产品、政策、投资和技术架构无关的泛资讯

## 投资内容免责声明

本仓库中的 AI 投资与资本市场内容仅用于行业研究和市场观察，不构成任何投资建议、买卖建议、价格预测或收益承诺。
