
- 2026-04-07: 卷宗私密助手返回 txt 的一类根因是 agent 使用了旧的 session skills snapshot，磁盘上新增的 docx/pdf/zip-redaction 技能未进入当前会话；清理 /Users/hero/.openclaw/agents/feishu-jz/sessions/sessions.json 中该 agent 旧会话映射后可强制下次按最新技能重建。
