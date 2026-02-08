# BMad 短剧生产扩展包

将你的 AI 变成一个面向竖屏短剧的“生产工作室”，内置钩子优化、冲突工程与节奏控制的专业 Agent 与工作流。

inspired by [BMad-Expansion-Pack-Creative-Writing](https://github.com/DrBalls/BMad-Expansion-Pack-Creative-Writing)
 

## 📚 概览

该扩展包在 BMad-Method 上提供一套专为短剧（竖屏、微集、强留存）打造的工具。无论是 1 分钟的爆款短片还是 60–100 集的系列叙事，都能用“结构公式 + 情绪工程 + 可执行提示词”快速落地并提高完成率。

### 关键特性
- 🎬 **短剧专用 Agent**：钩子、冲突、结构、视觉提示词一体化
- ⚡ **病毒式留存公式**：内置“开头 3 秒”与冲突密度规则
- 📉 **节奏优化**：保证信息密度与情绪价值的工作流
- 📝 **竖屏脚本**：符合移动端观看习惯的模板与输出格式
- 🎭 **专业模板**：系列大纲、钩子蓝图、角色原型等

## ✍️ 包含的 Agents

### 短剧核心（新增）
1. **Short Drama Structurer**：掌控 60–100 集结构、节奏与留存公式
2. **Conflict Engineer**：制造强冲突、反转与情绪爆点
3. **Hook Specialist**：优化“开头 3 秒”与高光镜头选取
4. **Novel Adapter**：长篇小说 → 竖屏短剧的改编与场景压缩

### 叙事支持团队
5. **Plot Architect**：故事结构与叙事一致性
6. **Character Psychologist**：角色动机与情绪逻辑
7. **World Builder**：世界观与舞台设定
8. **Editor**：脚本润色与对白优化
9. **Dialog Specialist**：短促有力的对话打造

### 其它支持
10. **Beta Reader**：观众反应模拟
11. **Genre Specialist**：类型套路与市场趋势分析

## 🚀 安装

### BMad 安装器
```bash
npx bmad-method install
# 在扩展包列表选择 “Short Drama Pack”
```

### 手动安装
1. 克隆或下载本扩展包
2. 复制到你的 BMad 安装目录：
   ```bash
   cp -r bmad-short-drama-production/* ~/bmad-method/expansion-packs/bmad-short-drama-production/
   ```
3. 运行安装器注册扩展包：
   ```bash
   bmad register-pack short-drama-production
   ```

## 💡 使用

### Quick Start
```bash
# 加载短剧生产团队
bmad load team short-drama

# 激活核心 Agents
bmad activate short-drama-structurer
bmad activate hook-specialist
```

### Core Workflows
- **viral-short-creation**：从概念到钩子优化脚本的全流程
- **series-structuring**：规划 80–100 集系列并设计悬念位
- **conflict-injection**：为平淡场景注入高强度冲突
- **hook-optimization**：最大化“前 3 秒”的留存
- **novel-to-short-drama**：长篇 → 竖屏短剧的改编（60–100 集）
- **standalone-episode**：单集自洽的短剧，强钩子与明确爽点
- **recurring-protagonist-series**：固定主角的连载系列，保持人设与视觉一致

### CLI Examples
```bash
# 长篇改编 → 短剧
bmad run workflow novel-to-short-drama --synopsis "Long-form romance synopsis" --visual-style "cinematic"

# 独立单集
bmad run workflow standalone-episode --premise "CEO vs Secretary public showdown" --genre "modern romance" --visual-style "cinematic"

# 固定主角连载
bmad run workflow recurring-protagonist-series --premise "revenge arc" --genre "business competition" --episodes 20 --persona "cold CEO" --archetype "anti-hero" --visual-style "high-contrast"
```

## 📋 关键组件

### Templates
- `short-drama-outline-tmpl.yaml`：100 集系列宏观结构
- `viral-hook-tmpl.yaml`：开头钩子设计蓝图
- `episode-script-tmpl.yaml`：竖屏剧本格式
- `novel-adaptation-plan-tmpl.yaml`：长篇改编计划模板

### Featured Checklists
- **Viral Potential**：钩子强度、节奏速度、冲突密度
- **Structure**：开头钩子、中段冲突、结尾悬念
- **Production**：视觉可行性、道具需求、演员限制
- **Novel Adaptation**：长篇改编为短剧的关键门槛
- **Standalone Episode**：单集的钩子/冲突/节奏质检
- **Recurring Protagonist Consistency**：主角与视觉一致性
- **Hook A/B Test**：钩子变体测试流程

## 🎯 典型场景

### 竖屏系列（60–100 集）
- 长尾留存的宏观结构规划
- 付费点/悬念工程设计
- 跨微集的角色弧线管理

### 爆款短片（TikTok/Reels）
- “开头 3 秒”优化
- 小屏视觉叙事
- 趋势融合与套路应用

### 剧本修复
- 节奏分析与加速
- 为平场景注入冲突
- 对白更短更狠的改写

## 📎 进一步阅读
- 快速上手：[quick-start-guide.md](file:///e:/workspace/bmad-short-drama-production/marketing/en/quick-start-guide.md)
- 发布介绍：[launch-article.md](file:///e:/workspace/bmad-short-drama-production/marketing/en/launch-article.md)
- 技术规格：[technical-specifications.md](file:///e:/workspace/bmad-short-drama-production/marketing/en/technical-specifications.md)
- 使用案例：[use-cases.md](file:///e:/workspace/bmad-short-drama-production/marketing/en/use-cases.md)
- 常见问题（FAQ）：[faq.md](file:///e:/workspace/bmad-short-drama-production/marketing/en/faq.md)
- CLI 速查表：[cli-cheatsheet.md](file:///e:/workspace/bmad-short-drama-production/marketing/en/cli-cheatsheet.md)
- 平台作战手册（TikTok/Reels/Shorts）：[platform-playbooks.md](file:///e:/workspace/bmad-short-drama-production/marketing/en/platform-playbooks.md)
- Agent：[novel-adapter.md](file:///e:/workspace/bmad-short-drama-production/agents/novel-adapter.md)
- 工作流：[novel-to-short-drama.yaml](file:///e:/workspace/bmad-short-drama-production/workflows/novel-to-short-drama.yaml)、[standalone-episode.yaml](file:///e:/workspace/bmad-short-drama-production/workflows/standalone-episode.yaml)、[recurring-protagonist-series.yaml](file:///e:/workspace/bmad-short-drama-production/workflows/recurring-protagonist-series.yaml)
- 示例输出（大纲/钩子/提示词）：[examples/](examples/)
