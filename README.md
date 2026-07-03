# 火柴男孩配图

一个面向中文文章正文配图的 Codex skill 仓库。

核心特点：

- 16:9 横版正文配图
- 默认 300 ppi 输出
- 纯白背景、黑色手绘线稿、少量红橙蓝批注
- 固定角色为手绘火柴男孩，而不是黑色小怪物
- 强调“小男孩承担核心动作”，避免只做装饰

## 仓库内容

- `ian-xiaohei-illustrations/`
  - 已更新为小男孩版本的技能定义
  - 包含 `SKILL.md`、`agents/`、`references/`、`assets/`

## 安装

使用 Codex 自带的 skill installer：

```bash
python3 "$HOME/.codex/skills/.system/skill-installer/scripts/install-skill-from-github.py" \
  --repo king9050/stick-boy-illustrations \
  --path ian-xiaohei-illustrations
```

安装后重启 Codex 以加载新技能。

## 说明

当前发布版本保留了原技能目录名 `ian-xiaohei-illustrations`，这样可以减少已安装环境的兼容性风险；但技能内部角色设定、提示词模板和质检规则已经切换到“小男孩”版本，并加入了 `300 ppi` 输出约束。
