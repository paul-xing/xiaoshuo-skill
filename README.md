# xiaoshuo — 中文网络小说创作体系

拥有15年从业经验的资深网文主编视角的小说创作 Skill。擅长将模糊灵感转化为完整世界观、人物小传、剧情大纲与章节。适用起点 / 晋江 / 番茄等平台的玄幻、言情、悬疑、科幻、都市类型。

> 从灵感到大纲到章节的全流程服务：一句话卖点 → 世界观设定 → 人物小传 → 剧情大纲 → 章节写作。

## 功能

- **一句话卖点**：提炼这本书最吸引读者的核心创意
- **世界观设定**：完整、自洽、可扩展的世界规则
- **人物小传**：主角、盟友、反派的多维人物卡
- **剧情大纲**：英雄之旅 12 阶段 + 三幕结构 + LOCK 系统
- **章节写作**：节奏紧凑、爽点密集、章节钩子、伏笔管理
- **叙事结构参考**：见 `references/narrative-structures.md`（英雄之旅 12 阶段、LOCK 系统、三幕结构、短剧爆点节奏）

## 安装

### Claude Code

```sh
mkdir -p ~/.claude/skills
git clone https://github.com/paul-xing/xiaoshuo-skill.git ~/.claude/skills/xiaoshuo
```

### Codex

```sh
mkdir -p ~/.codex/skills
git clone https://github.com/paul-xing/xiaoshuo-skill.git ~/.codex/skills/xiaoshuo
```

### 通用（~/.agents）

```sh
mkdir -p ~/.agents/skills
git clone https://github.com/paul-xing/xiaoshuo-skill.git ~/.agents/skills/xiaoshuo
```

安装后在新会话中可用。在对话中直接说「用 xiaoshuo skill 帮我创作这部网络小说的世界观、大纲和章节」即可触发。

## 使用流程

1. **一句话卖点** — 根据你的故事梗概提炼核心卖点
2. **世界观设定** — 构建完整自洽的世界规则
3. **人物小传** — 主角/盟友/反派的人物设计
4. **剧情大纲** — 英雄之旅 12 阶段 + 章节节奏表
5. **章节写作** — 逐章输出，每章留钩子

每一步完成后询问你的意见，确认后才进入下一步。

## 目录结构

```
xiaoshuo/
├── SKILL.md                        # Skill 主文件（角色设定、创作原则、工作流程）
├── agents/
│   └── openai.yaml                 # 模型接口展示信息
└── references/
    └── narrative-structures.md     # 叙事结构参考（英雄之旅 12 阶段等）
```

## 参考书目

- 布莱克·斯奈德《救猫咪》— 电影节拍表
- 克里斯托弗·沃格勒《作家之旅》— 英雄之旅 12 阶段
- 詹姆斯·斯科特·贝尔《大师写作课》— LOCK 系统 + 三幕结构
- 查理《写好短剧》— 短剧节奏和爆点密度

## License

MIT
