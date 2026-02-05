# OpenCode Skill 配置路径说明

## 全局配置目录
- **路径**：`~/.config/opencode/skills/`
- **作用**：对所有项目生效的 skill
- **当前技能**：
  - skill-creator
  - dev-workflow

## 项目本地配置目录
- **路径**：`.opencode/skills/`
- **作用**：仅对当前项目生效的 skill（会覆盖全局同名 skill）
- **当前技能**：
  - dev-workflow

## 项目文档目录
- **路径**：`dev-workflow/`
- **作用**：项目中的普通文档目录，不会被 OpenCode 自动加载
- **说明**：用于存放项目开发流程规范的文档

## 更新流程
1. 修改项目本地配置：`.opencode/skills/dev-workflow/SKILL.md`
2. 同步到全局配置：`cp .opencode/skills/dev-workflow/SKILL.md ~/.config/opencode/skills/dev-workflow/SKILL.md`
3. 提交项目变更
