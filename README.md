# cross-border-bi-project

Amazon 美国站 FBA 数据分析与 BI 学习开发项目。

## 目标和当前状态
学习跨境电商业务，使用 **MySQL 8.4 + Metabase** 建立四张业务报表，并练习借助 AI 修改报表。当前处于仓库初始化阶段，尚无可运行 BI 原型；四张报表具体定义与指标公式仍待确认。

## 成员分工
- 用户：学习、定义业务问题、核对数据与验收。
- 哥哥：关键技术方案复核、SQL/模型质量检查。
- ChatGPT：业务/技术教学、任务拆解、复盘。
- Codex：按任务修改仓库、记录日志、提交代码。

## 网页优先流程
在 ChatGPT/Codex 中选择 GitHub 仓库，描述任务；AI/Codex 使用分支修改并发起 PR，在 `docs/operation-log.md` 写操作记录。GitHub 是正式版本。用户按需审核并合并；日常无须 VS Code 手工上传。只有运行数据库、调试 SQL/Metabase 时才需本地或云端运行环境。

## 文档导航
- [项目范围](docs/project-scope.md)
- [协作规范](CONTRIBUTING.md)
- [决策记录](docs/decisions.md)
- [操作日志](docs/operation-log.md)
- [独立学习进度仓库模板](docs/learning-repo-template.md)

## 数据安全
真实经营明细、客户个人信息、账户密码和 API 密钥不提交到仓库；演示尽量使用脱敏或合成数据。
