# My Skills

个人 Agent Skills 仓库，兼容 `npx skills` 安装方式。

## Skills

| Skill | Description |
| --- | --- |
| `skill-forge-shouffin` | Skill 脚手架生成器，用于创建、设计和验证 Agent Skill。 |

## Install

```bash
# List available skills
npx skills add zhdhnsfdx/my-skill --list

# Install one skill
npx skills add zhdhnsfdx/my-skill --skill skill-forge-shouffin

# Install all skills
npx skills add zhdhnsfdx/my-skill --skill '*'
```

## Structure

```text
skills/
  <skill-name>/
    SKILL.md
    README.md
    references/
    rules/
    workflows/
```
