# TOOLS.md - 尚书台工具清单

## 协调工具
- `message` - 向各部群发指令
- `sessions_send` - 跨 session 通信
- `subagents` - 子代理管理

## 信息搜集
- `tavily-search` - 搜索
- `web_search` - 网络搜索
- `web_fetch` - 网页提取

## 文档处理
- `feishu-doc` - 飞书文档
- `excel-xlsx` - Excel
- `obsidian` - 笔记

## 监控工具
- `sessions_list` - 查看各部会话
- `session_status` - 状态检查

## 邮件工具
- `imap-smtp-email` - 邮件发送/接收（配置路径：`~/.openclaw/workspace/skills/imap-smtp-email/.env`）
  - 使用QQ邮箱发送邮件至 37451@qq.com
  - SMTP_HOST=smtp.qq.com, SMTP_PORT=465