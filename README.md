<p align="center"><img src="./assets/banner.svg" alt="XXD Panel 037 project banner" width="1200"></p>

<div align="center">

# 🦁 XXD Panel 037

### 把每段旅程做成一枚可收藏的流金珐琅徽章

[![Codex Skill](https://img.shields.io/badge/Codex-Skill-000000?style=flat-square)](./SKILL.md)
[![Modes](https://img.shields.io/badge/Modes-4-E7483E?style=flat-square)](#)
[![Output](https://img.shields.io/badge/Output-PNG-1A7A8C?style=flat-square)](#)

<strong>简体中文</strong> · <a href="README.en.md">English</a> · <a href="README.ja.md">日本語</a> · <a href="README.ko.md">한국어</a> · <a href="README.ar.md">العربية</a>

</div>

<div>

> 一枚徽章 · 源图珐琅色 · 白金属外框 · 流金细节 · 实体短影

决定性的轮廓与局部特征被压缩为一枚真实旅行徽章：源图衍生珐琅色格、金属分隔线、白色金属外框、克制流金细节、圆润厚度和短促实体投影。

## 为什么需要这套 Skill

这套风格依赖每一张源图，不是可替换内容的装饰预设。它遵循这条重构链：

```text
锁定身份与外轮廓 → 保住决定性轮廓与局部特征 → 简化为有结构意义的珐琅分区 → 建立真实金属分隔线与白色金属外框 → 增加克制流金、厚度、倒角和短促接触影 → 把目标语言标题嵌入徽章本体
```

如果换成无关照片后，辨识度、构造、位置、材质、颜色、留白与文案都不发生实质变化，结果就不属于这套 Panel。

## 视觉契约

- 从剪影、比例、姿态、开口、结构、局部特征或关系中保留至少三个源图专属线索。
- 构成一枚完整徽章：清晰珐琅分区、白色金属外描边、圆润倒角、克制可见厚度，以及浅色底面上的短促柔影。
- 提取源图中有生命力的色组；每个珐琅色都承担结构分区，金色只作为分隔线或有意义的局部强调。
- 珐琅光洁、饱满、轻微隆起且受光真实，但不得塑料化；金属反光细腻，不得廉价黄亮。
- 允许有源图依据的偏置、倾斜或局部延展，但整体必须稳定、精致、可收藏。

原始审美约束与拒绝项只存在于[原始提示词](references/037-source.md)；Skill 与运行适配器只处理本次交付变量。 [Skill 工作流](SKILL.md) · [英文运行适配器](references/xxd-panel-037-prompt.en.md)

## 样张 · 来自 X

> [小小东（@xiaoxiaodong01）](https://x.com/xiaoxiaodong01/status/2090799598336168140) · 2026-08-21<br>
> GPT2 x 鎏金珐琅 x 冰箱贴 x 美学提示词 x VOL.037

<table>
  <tr>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2090799598336168140"><img src="./assets/examples/sample-01.jpg" alt="XXD Panel 037 样张 1"></a></td>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2090799598336168140"><img src="./assets/examples/sample-02.jpg" alt="XXD Panel 037 样张 2"></a></td>
  </tr>
  <tr>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2090799598336168140"><img src="./assets/examples/sample-03.jpg" alt="XXD Panel 037 样张 3"></a></td>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2090799598336168140"><img src="./assets/examples/sample-04.jpg" alt="XXD Panel 037 样张 4"></a></td>
  </tr>
</table>

<p align="center"><a href="https://x.com/xiaoxiaodong01/status/2090799598336168140">查看原推文与完整提示词 →</a></p>

这些样张用于展示 037 的美学动机，不会把样张中的主体、构图、配色、文案或旧画幅变成生成参考或当前默认值。

## 原始提示词优先，而不是二次导演

`references/037-source.md` 是本项目唯一的创作与审美权威。Skill 不再额外总结或扩写它，也不会统一规划颜色、色板、美学动机、标题或微文案。原始提示词要求怎样处理颜色、材料、构图、留白与文字，GPT Image 2 就按那套逻辑执行。

模式与尺寸只覆盖原始提示词旧有的 3:4 上下双联容器：左右模式表达原图与设计转译之间的左右视觉关系，但不预设两块半幅或裁切框；在只要设计图和壁纸模式中，下方设计审美扩展到完整画布。除此之外，原始提示词全部保持有效。

## 四种可组合输出模式

模式可以单选或多选：`top-bottom`、`left-right`、`design-only`、`wallpaper-pack`。双联默认把原图、原始提示词、视觉关系和最终尺寸一次交给图像模型，由它直接生成完整画布；只有用户明确要求像素级分区或原片逐像素不变时，才使用确定性拼合。

上下或左右是视觉关系，不是固定的等分容器。区域比例、尺度、留白、交叠、裁切或环境延展由图像模型结合原图与最终画布自主判断，不做分界线、中线百分比或像素坐标检测。

普通成品尺寸同样可以多选：自动适配、跟随原图、1:1、3:4、4:3、4:5、5:4、2:3、3:2、9:16、16:9、21:9、5:7、7:5，或自定义比例／准确像素。没有静默默认尺寸；每个不同比例都会基于同一份原始提示词独立重构。

壁纸套装可选“连贯”或“四张独立”。连贯模式先生成一张定调图，其余设备同时参考原图与定调图重新构图；不会把一张图机械裁成四种尺寸。

## 文字方式

正式生图前只确认三种选择：

1. **模型根据原始提示词生成文字**：用户只指定语言或地区，文字内容、数量、气质与排版由 GPT Image 2 按原始提示词生成；所有文字都从当前图片的内容、气质或隐喻中自然生长。
2. **使用我的准确文字**：逐字传给图像模型，不改写、不翻译、不补标题；排版仍遵循原始提示词。
3. **不要文字**：严格禁止文字与伪文字。

外层 Skill 不再预编标题、微文案或文案包。文字语言与操作语言分开确认，不根据人物、场景或文件名猜测国家与受众。

## 完整画布优先与位图边界

图像模型负责整张成品的审美重构，双联也默认一次直出完整画布。`scripts/compose_panel.py` 只保留为条件明确的兜底、无创尺寸校准和只读审计工具，不再预先规划每次任务，也不评价审美是否成功。

全部交付为 PNG 位图。每次调用都在 `~/Desktop/xxd/` 下创建新任务；已配置图像通道只返回脱敏状态，不公开供应商、端点、凭据、请求头、提示词、响应或账户信息。SVG、HTML、Canvas、图表和程序绘图不能替代最终作品。

## 能力自适应问询与快捷参数

同一个 Skill 会根据宿主真正提供的交互能力选择界面，不会把文本符号伪装成可点击控件：

- **Claude Code 提供 `AskUserQuestion + multiSelect: true` 时**：模式和尺寸使用真正的 checkbox；文字方式与壁纸关系使用单选。常用尺寸会按方形、竖版、横版分组展示，并累计多组选项；自定义尺寸进入自由输入。
- **Codex 只提供 `request_user_input` 时**：它只用于文字方式、壁纸关系等互斥单选，不拿来伪装模式或尺寸多选。模式与尺寸改用清楚的组合输入。
- **没有交互工具时**：使用两轮文字问询。第一轮选择一个或多个模式；第二轮填写尺寸与文字方式。Skill 不显示假的 `- [ ]`，也不会为了获得表单要求用户切换 Plan mode。

默认第二轮只展示“智能推荐／跟随原图／常用比例／自定义”四个入口；只有选择常用比例时，才展开完整比例库：方形 `1:1`，竖版 `3:4、4:5、2:3、9:16、5:7`，横版 `4:3、5:4、3:2、16:9、21:9、7:5`。所有比例都可组合，也可直接输入准确像素。

全部设置都可以直接作为参数传入：

```text
/xxd-panel-037 photo.jpg --mode top-bottom,design-only --size auto,3:4,9:16 --text prompt --locale ja-JP
```

支持 `--mode`、可重复或逗号分隔的 `--size`、`--text prompt|exact|none`、`--locale`、`--copy`、`--wallpaper linked|independent`、`--wallpaper-size` 和 `--out`。参数齐全时跳过全部问询；参数不完整时只询问缺失项。

## 生图模型优先级

GPT Image 2 是默认首选，并继续执行本项目现有的高保真垫图、生成前确认整张画幅、双联一次生成完整画布、脚本仅作条件式兜底等逻辑。

当当前工具或已配置兼容通道确实可用，并能满足原图保真、整张成品比例、目标语言文字和连贯壁纸多图参考等要求时，也支持 Seedance 5.0 Pro、Nano Banana Pro（Gemini Image Pro）、Nano Banana 2（Gemini Image Flash）或其他兼容位图模型。备用模型只替换生成通道，不得改变模式、画幅、文案、语言、壁纸关系和完整画布优先策略。

如果没有合适的生图通道，Skill 会请用户启用生图工具或提供 API Key。用户主动提供的凭据可以用于当前任务，但不得在回复或日志中回显、展示或泄露；未经用户明确要求，不会长期保存凭据或修改供应商、账户、计费及全局路由配置。

## 开始使用

```bash
git clone https://github.com/nevertoday/xxd-panel-037.git
mkdir -p ~/.codex/skills
ln -s "$(pwd)/xxd-panel-037" ~/.codex/skills/xxd-panel-037
```

Claude Code 用户可把同一文件夹链接到 `~/.claude/skills/xxd-panel-037`. 安装后请重启 Agent 会话。

```text
$xxd-panel-037
Use this photograph, ask me for the modes and copy setting, then generate fresh raster outputs.
```

完整规格: [Skill 工作流](SKILL.md) · [原始风格档案](references/037-source.md) · [英文运行适配器](references/xxd-panel-037-prompt.en.md) · [中文运行适配器](references/xxd-panel-037-prompt.zh-CN.md)

## 关于 XXD

XXD 是小小东品牌名的缩写，本项目由小小东创建并维护： [@xiaoxiaodong01](https://x.com/xiaoxiaodong01).

## 支持与会员

### 深度咨询 · 299 元／小时

一对一深入咨询 Skills 的使用与工作流，通过微信联系小小东预约。 [WeChat](https://xiaoxiaodong.pages.dev/assets/wechat-qr.png)

### 小小东 Skills 用户交流群 · 99 元

一次付费加入 Skills 用户交流群，用于工作流分享和用户间讨论；不包含按小时计费的一对一咨询。

### 知识星球＋成员提示词库 · 699 元／年

知识星球和成员提示词库是一份会员费用：从任一入口开通后，通过微信联系小小东获取另一边的权益。

[Knowledge Planet](https://wx.zsxq.com/group/15554814142882) · [Member Prompt Library](https://vip.xiaoxiaodong.ai/)

<p align="center"><a href="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png"><img src="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png" alt="XXD WeChat" width="280"></a></p>

<div align="center"><strong>当决定性的轮廓穿过光泽，旅程就成为可以收藏的东西。</strong></div>

---

<div align="center">

## ☕ 支持这个开源项目

算力赞助请使用小小东自己的微信或支付宝赞赏码；赞助完全自愿，不改变开源项目的访问权限。


<table><tr>
<td align="center"><a href="https://colors.xiaoxiaodong.ai/docs/images/wechat-reward-qr.png"><img src="https://colors.xiaoxiaodong.ai/docs/images/wechat-reward-qr.png" alt="XXD WeChat reward" width="180"></a><br><strong>WeChat</strong></td>
<td align="center"><a href="https://colors.xiaoxiaodong.ai/docs/images/alipay-reward-qr.png"><img src="https://colors.xiaoxiaodong.ai/docs/images/alipay-reward-qr.png" alt="XXD Alipay reward" width="180"></a><br><strong>Alipay</strong></td>
</tr></table>

</div>
</div>
