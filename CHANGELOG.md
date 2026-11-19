# CHANGELOG.md · 仓库级变更

## 2026-11-19 · 盘点复核：维持不加机器层

- 复核结论：本仓仍是 4 个 md、0 个 `docs/`、几乎没有内链，`check_repo` 在此确实无可查项
  → **维持 2026-11-18 的决定，不接 repo-kit**。外链仍由 `link-rot.yml`（lychee 周检）覆盖
- 已知副作用（本次记录在案）：`audit-spec.ps1` 以 `schema/taxonomy.json` / `schema/kit.lock.json`
  判别仓库，本仓两者皆无，因此在舰队盘点里**不出现**；这是有意取舍，不是遗漏
- `AGENTS.md` 基线行更新至本次提交

## 2026-11-18 · 外链巡检 + 移除失效条目

- 新增 `.github/workflows/link-rot.yml`：每周 lychee 巡检全部 md 外链，失败自动开/追 issue（有缓存、不阻塞 PR）
- **移除 `code-audit-playbook` 条目**：该仓已由本人删除（2026-11-18 确认），索引随之移除
- 说明：本仓不加 repo-kit 机器层——只有 4 个 md、几乎没有内链，`check_repo` 在此查不到东西

## 仓库 · 2026-10-09 · 补录 code-audit-playbook

- 「🧠 思维 / 方法论」补录 **`code-audit-playbook`**（原链接已失效）（系统性代码审计方案）

## 仓库 · 2026-10-09 · 建库

### 建库

- 建立索引仓库（纯文档、零代码），收录下列项目：
- 收录：思维 / 方法论、内容 / 资料库、实用指南与生活杂项
- 🔒 私有仓库在索引中标注、不提供对外链接

