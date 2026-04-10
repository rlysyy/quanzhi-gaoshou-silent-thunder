# LEARNINGS.md
# 学习记录 - 纠正、知识缺口、最佳实践
# 自动捕获同类错误，避免反复犯错

---

## 使用说明

当以下情况发生时，记录到此文件：
1. 用户纠正你的错误（"不对..."、"应该是..."）
2. 发现知识缺口（用户提供了你不知道的信息）
3. 发现最佳实践模式

### 记录格式

```markdown
## [LRN-YYYYMMDD-XXX] 类别
**记录时间**: ISO-8601 时间戳
**优先级**: low | medium | high | critical
**状态**: pending
**领域**: frontend | backend | infra | tests | docs | config

### 摘要
一句话描述学到的内容

### 详情
完整上下文：发生了什么、哪里错了、正确做法

### 建议行动
具体的修复或改进措施

### 元数据
- 来源: conversation | error | user_feedback
- 相关文件: path/to/file.ext
- 标签: tag1, tag2
- 参见: LRN-20250110-001
---
```

---

## [LRN-20260313-001] role-boundary
**记录时间**: 2026-03-13T06:26:00+08:00
**优先级**: high
**状态**: resolved
**领域**: workflow

### 摘要
尚书令越权直接处理具体事务，陛下纠正：尚书令应统管六部，不直接处理具体事务。

### 详情
- 陛下旨意：搜索安装 self improving agent
- 错误：尚书令直接执行搜索、安装、配置
- 正确做法：尚书令应分派工部执行，自身负责统筹与奏报

### 建议行动
今后工作流程：
1. 接收陛下旨意
2. 研判归属部门（此例为工部🔧技能管理）
3. 分派对应部门执行
4. 跟踪进度并汇总奏报

### 元数据
- 来源: user_feedback
- 相关文件: AGENTS.md, SOUL.md
- 标签: role, delegation, workflow
---

*记录开始*
