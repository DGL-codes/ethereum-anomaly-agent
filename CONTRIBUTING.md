# 提交与协作说明

所有开发内容通过 Pull Request 合并到 `main`，不要直接在 `main` 分支开发。

## 基本流程

1. 将仓库 fork 到自己的 GitHub 账户。
2. clone 自己 fork 的仓库。
3. 从最新的 `main` 创建新分支，例如 `feature/data-fetcher`、`feature/agent-ui` 或 `fix/api-cache`。
4. 完成一项相对独立的工作后提交并 push 到自己的 fork。
5. 在 GitHub 上向本仓库的 `main` 分支发起 Pull Request。

每个 PR 应尽量只解决一个问题，并在描述中说明：做了什么、如何运行或验证、是否还有已知问题。页面改动请附截图。

推荐先创建 Draft PR，方便另一位同学及时查看和讨论；完成自测后再标记为 Ready for review。
