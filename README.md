<img width=88 src="https://oncadence.com/badge-ai4sm/" />  

**本站由 Ethan Huang 维护**  
**视频号: 跟着Ethan学敏捷**  
**邮箱:** <a href="mailto:me@ethanhuang.com" target="_blank"> <font color = blue><u><b>me@ethanhuang.com</b></u></font></a>  
**主站:** <a href="https://oncadence.com/cn" target="_blank"> <font color = blue><u><b>https://oncadence.com</b></u></font></a>  
<br>
<img width=88 src="https://oncadence.com/robot/" />
<br>
## 1. 需要用到的AI大模型和工具

|编号|大模型/工具|说明|
|----|------|-----|
|1   |<a href="https://chatgpt.com" target="_blank">ChatGPT</a>|1. 需要番强<br>2. 贵：免费版限制多;Plus版USD20/月;Pro版USD200/月<br>3. 对于中国的数据投喂，与墙外水平相当<br>4. 使用Markdown语法的Prompt时，对对话的假设空间小<br>5. 中规中矩的少林派 |
|2   |<a href="https://chat.deepseek.com" target="_blank">DeepSeek</a>|1. 微信登录即可<br>2.便宜，与阿里云、千问结合可低成本训练自己的聊天机器人<br>3. 国内数据投喂良好，洞察有深度<br>4. 可使用更贴近自然语言的对话方式，但是对上下文的假设空间大<br>5. 飘逸的无党派|
|3   |<a href="https://www.sublimetext.com/download" target="_blank">'Sublime Text'编辑器</a><br>|免费的 Markdown 编辑器，编写 Prompt 首选<br>|
|4   |<a href="https://www.markdownguide.org/cheat-sheet/" target="_blank">Markdown语法小抄在线版</a><br><a href="https://www.markdownguide.org/assets/markdown-cheat-sheet.md" target="_blank">Markdown 语法小抄下载</a>|Markdown语法小抄，下载的文件可以用上面的 Sublime 打开|
<br>

## 2. 驾驭AI必备 - 有效提示词之SPARK范式
###  2.1 SPARK范式说明

| 元素 | 功能 | 描述 | 最佳实践 |
| --- | --- | --- | --- |
| **S - Situation 情境（Context）** | 提供背景和情境 | 建立问题空间和情境 | • 无指令：不要写任务指令，只描述背景<br>• 使用 {}：用 {粘贴完整的背景和概念} 作为占位符，让用户动态填写，提高模板可复用性 |
| **P - Purpose 目的（Objective）** | 明确任务输出目标 | 聚焦输出内容 | • 指令清晰：一句话一个指令<br>• 动词导向：使用动词引导的指令<br>• 关键要求：添加关键要求描述（例如 INVEST 原则） |
| **A - Action Role 行动角色（Role Assignment）** | 设置专业角色 | 模拟接近实际业务需求的思维模式 | • 专业角色：指定具备任务相关技能的角色<br>• 领域：强调角色的专业领域 |
| **R - Rule 规则（Task Rules）** | 建立行为和风格标准 | 确保输出内容一致、专业、可用 | • 示例：给出示例帮助 AI 理解<br>• 特定行为：将“请尽可能清楚描述”改为“必须提供至少三个场景”<br>• 质量要求：如有质量标准，明确说明 |
| **K - Knowledge Format 知识格式（Output Format）** | 定义输出格式 | 帮助模型保持输出一致性 | • 模板：指定句式/结构模板 |
<br>

###  2.2 SPARK范式示例

```
# S - Situation 情境（Context）
## 我们正在开发一款帮助用户一站式规划旅行的应用：
- 轻松规划所有旅行活动。
- 包括航班、火车、交通工具、餐饮、娱乐活动等。
- 提供智能、时尚和可定制的旅行体验。
## 我们获得了一份高层的产品需求文档，但该文档没有经过专业编写。
---
# P - Purpose 目的（Objective）
## 请阅读我稍后提供的PRD文档
## 将PRD文档转化为符合INVEST原则的用户故事列表。
---
# A - Action Role 行动角色（Role Assignment）
## 你是一个经验丰富的Scrum产品负责人
## 你擅长设计思维，具备良好的用户同理心
## 你是用户体验设计的专家
## 你擅长BDD和ATDD，能够将模糊概念转化为可执行的用户故事
## 确保开发团队有明确的目标、价值和验收标准。
---
# R - Rule 规则（Task Rules）
请遵循以下行为和风格标准：
## 用户故事质量
- 使用标准格式：“作为[角色]，我想要[目标]，以便[收益]”
- 每个故事必须清晰表达其价值（V）和可测试性（T）
- 将模糊、情感化的语言（如“有趣”，“感觉良好”）转化为面向行为或功能的语言
- 仅输出用户故事内容，不生成不必要的解释
- 用户故事粒度必须具体且可执行
- 覆盖背景概念中提到的所有关键功能或场景

## INVEST原则清单（附录）
检查每个故事的资格标准

| 原则代码   | 描述                                           |
| ---------- | ---------------------------------------------- |
| **I – 独立** | 故事应能独立完成，而不依赖其他故事                |
| **N – 可协商** | 可协商，不应为固定的规格描述                       |
| **V – 有价值** | 必须对用户或业务具有明确价值                       |
| **E – 可估算** | 可估算工作量或复杂度                             |
| **S – 小**   | 足够小，可以在一个Sprint内完成                    |
| **T – 可测试** | 具有可验证的验收标准或条件                        |
---
# K - Knowledge Format 知识格式（Output Format）
## 请按照编号列表格式整理结果，每个用户故事使用标准句型：
用户故事1
作为...，
我想...，
以便...

用户故事2
作为...，
我想...，
以便...
## 以纯文本格式输出所有用户故事
```
<br>
