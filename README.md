<img width=88 src="https://oncadence.com/badge-ai4sm/" />  

**本站由 Ethan Huang 维护**  
**视频号: 跟着Ethan学敏捷**  
**邮箱:** <a href="mailto:me@ethanhuang.com" target="_blank"> <font color = blue><u><b>me@ethanhuang.com</b></u></font></a>  
**主站:** <a href="https://oncadence.com/cn" target="_blank"> <font color = blue><u><b>https://oncadence.com</b></u></font></a>  
<br>
<img width=88 src="https://oncadence.com/robot/" />
<br>
---
## 1. 准备你的 AI 工具箱
### 1.1 需要用到的AI大模型和工具

|编号|大模型/工具|说明|是否必须|
|----|------|-----|-----|
|1   |<a href="https://chatgpt.com" target="_blank">ChatGPT</a>|1. 需要番强<br>2. 贵：免费版限制多;Plus版USD20/月;Pro版USD200/月<br>3. 对于中国的数据投喂，与墙外水平相当<br>4. 使用Markdown语法的Prompt时，对对话的假设空间小<br>5. 中规中矩 |是    |
|2   |<a href="https://vip.nioai.pro" target="_blank">NIOAI AI壳子</a>|1. 不需要番强就可以用 chatgpt<br>2. 便宜：RMB888/年, 使用 ChatGPT Pro<br>3. 也支持其他大模型，如Cloude<br>4. 与番强类似，有证册漏洞<br>5. 偶尔不稳定<br>6. 设计网站的人很二<br>7. 数据安全没保障 - 偶尔会搜到别人的数据<br>8. 个人科研使用,尤其在国际化/英文场景很推荐|是    |
|3   |<a href="https://chat.deepseek.com" target="_blank">DeepSeek</a>|1. 微信登录即可<br>2.便宜，与阿里云百炼结合可低成本训练自己的聊天机器人<br>3. 国内数据投喂良好，洞察有深度<br>4. 可使用更贴近自然语言的对话方式，但是对上下文的假设空间大<br>5. 有点傻|是    |
|4   |<a href="https://chat.qwen.ai" target ="_blank">Qwen(通义千问)</a>|1. 不限流量<br>2. 便宜，与阿里云百炼完美结合可低成本训练自己的聊天机器人<br>3. 国内数据投喂良好，洞察有深度<br>4. 没有deepseek傻|是    |
|5   |<a href="https://chatboxai.app/en#download" target ="_blank">Chatbox - 你自己的 AI 聊天机器人</a>|1. 免费<br>2. 兼容大部分主流大模型<br>3. 使用方便<br>4. 配置大模型稍有门槛|否   |
|6   |<a href="https://www.sublimetext.com/download" target="_blank">'Sublime Text'编辑器</a><br>|免费的 Markdown 编辑器，编写 Prompt 首选<br>|是   |
|7   |<a href="https://www.markdownguide.org/cheat-sheet/" target="_blank">Markdown语法小抄在线版</a><br><a href="https://www.markdownguide.org/assets/markdown-cheat-sheet.md" target="_blank">Markdown 语法小抄下载</a>|Markdown语法小抄，下载的文件可以用上面的 Sublime 打开|是    |
|8   |<a href="https://blockthis.xyz" target ="_blank">12VPN</a>|1. 稳定的番强梯子<br>2. 除了贵没缺点|否    |

<br>
<br>

### 1.2 NIOAI.pro "AI壳子"设置   
1.2.1. 打开<a href="https://vip.nioai.pro" target="_blank">NIOAI</a>" AI壳子"，选”Open AI",然后点“点击进入”
<br>
<img width=688 src=" https://oncadence.com/nioai-1/" />
<br>
<br>
1.2.2. 点”注册”，注册一个新账号
<br>
<img width=688 src=" https://oncadence.com/nioai-2/" />  
<br>
<br>
<img width=688 src=" https://oncadence.com/nioai-3/" />
<br>
1.2.3. 回到<a href="https://vip.nioai.pro" target="_blank">NIOAI</a>" AI壳子"，拉到底部找到 ChatGPT 天体验卡，微信加客服要免费兑换码”
<br>
<br>
<b><font color ="red">请在上课当天使用兑换码，</font></b><br>
<b><font color ="red">因为免费的体验卡只有一天生效时间</font></b>
<br>
<br>
<img width=688 src=" https://oncadence.com/nioai-4/" />
<br>
<br>
1.2.4. 回到 ChatGPT 入口，右上角”兑换会员“，输入兑换码后即可使用
<br>
<img width=688 src=" https://oncadence.com/nioai-5/" />
<br>
<br>
<br>
### 1.3 Chatbox 你自己的 AI 聊天机器人设置
<br>
1.3.1. Chatbox 和阿里百炼结合，可以配置 qwen 和 DeepSeek，变成自己的专属 AI 聊天机器人
<br>
<img width=688 src="https://oncadence.com/chatbox/" />
<br>
<br>
1.3.2. 登录阿里云，找到<a href="https://www.aliyun.com/product/bailian" target="_blank">阿里百炼</a>，点击“免费体验”
<br>
<br>
**需要注册阿里云账号，后续会产生一些费用**  
<br>
<br>
<img width=688 src="https://oncadence.com/bailian1/" />
<br>
<br>
1.3.3. 在百炼界面，点击左下角“密钥管理”
<br>
<img width=688 src="https://oncadence.com/bailian2/" />
<br>
<br>
1.3.4. 在密钥管理界面，点击右上角“创建API-KEY”，创建成功后将 API-KEY 保存起来
<br>
<img width=688 src="https://oncadence.com/bailian3/" />
<br>
<br>
1.3.5. 访问<a href="https://chatboxai.app/en" target="_blank"> Chatbox AI 主页</a> 找到下载中心，下载 Chatbox app 并安装
<br>
<img width=688 src="https://oncadence.com/chatbox0/" />
<br>
<br>
1.3.6. 在 Chatbox app 右下角，点击 Settings
<br>
<img width=688 src="https://oncadence.com/chatbox1/" />
<br>
<br>
1.3.7. 在 Model Provider 中, 添加一个新的 Model Provider，名字为”Aliyun“。在右侧依次输入：
<br>
- API Key : 之前保存的”阿里百炼“ API Key
- API Host： https://dashscope.aliyuncs.com/compatible-mode/v1
- 最下面的 Model，手动新增两个：
<br>
  qwen3-235b-a22b (qwen)
  <br>
  deepseek-r1-0528 (DeepSeek)
  <br>
- 在 API Key 一栏右侧，点击”Check"按钮
- 成功后，Chatbox 就配置完成了
<br>
<br>
<img width=688 src="https://oncadence.com/chatbox2/" />
<br>
参见<a href="https://bailian.console.aliyun.com/?spm=5176.12818093_47.console-base_product-drawer-right.dsfm.1a5a2cc916muTl&tab=doc#/doc/?type=model&url=2880896" target ="_blank">阿里云的Chatbox Model Provider 配置官方文档< /a>
<br>
<br>
---
<br>
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
