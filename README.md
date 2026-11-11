# Muse 数据自动备份和恢复 skill

封号数据秒恢复。每 3 天自动把记忆、规则、任务目标备份到 Google Drive。

## 怎么用

1. 下载 `muse-backup-skill.zip`：https://drive.google.com/uc?export=download&id=14gzvt3Wa0c2C-7gkbNOttBfHARj7ZeCz
2. 把 `muse-backup/` 发给你的 Muse，说：装上
3. Muse 问你点一个：拿回旧数据 / 保存现在的数据

## 能做什么

- 保存现在的数据：打包成固定名 `muse-backup.zip`，传到 Drive「Muse 备份」，推荐每 3 天一次，默认凌晨 3 点
- 拿回旧数据：同一 Google 账号，按固定名取回，直接合并（新号保留、旧的补进来、冲突以新号为准），重建任务目标

## 做不到

- 官方导出按钮点不了，聊天原文要自己手动导出
- 聊天原文不能恢复成聊天，只能进记忆
- 图片视频、密码密钥不备份

详情见 `muse-backup/README.md`。
