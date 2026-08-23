# `CoreCoder` 二次开发版

> 原项目：[he-yufeng/CoreCoder](https://github.com/he-yufeng/CoreCoder)

## 新增功能

- **Auto-accept** 模式改为可选，在默认模式下，诸如`bash`、`write_file`、`edit_file`的关键工具调用需要用户手动确认。通过`/auto`启动。
- 新增**Plan**模式，在该模式下，CoreCoder将会先构建执行计划，仅当用户确认计划后才会执行shell命令、编辑等工具调用。