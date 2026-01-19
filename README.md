# vibe-coding-skills
ai 编程中有用 skills

## OpenCode 全局配置位置

全局 opencode skills 配置路径：`~/.config/opencode/skills/`

### 当前项目 skills

- `dev-workflow/` - 自用项目开发工作流规范
- `skill-creator/` - 创建新 skill 的指导工具

### 更新全局配置

当修改项目中的 skill 文件后，需要同步到全局配置：

```bash
cp <skill>/SKILL.md ~/.config/opencode/skills/<skill>/SKILL.md
```

例如：
```bash
cp dev-workflow/SKILL.md ~/.config/opencode/skills/dev-workflow/SKILL.md
```