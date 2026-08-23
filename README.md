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

完整审美约束与拒绝项写在 Skill 和生产提示词中；它们保留原始提示词的审美动机，但不会把历史 3:4 画布变成隐藏默认值。 [SKILL.md](SKILL.md) · [production prompt](references/xxd-panel-037-prompt.en.md)

## 样张 · 即将补充

`assets/examples/` 只会放入项目作者确认过的本风格成品；未确认前不使用其他风格作为占位。

## 四种可组合输出模式

可以用 `1`、`1+3`、`1、2、4` 或 `全部` 选择一个或多个模式；`全部` 每张源图输出 7 张 PNG：三种普通模式各一张，外加四张壁纸。

| 模式 | 未指定尺寸 | 成果物 |
| --- | --- | --- |
| `top-bottom` | 源图自适应 `W×2H` | 上方完整源图＋下方变化设计，严格 50/50 |
| `left-right` | 源图自适应 `2W×H` | 左侧完整源图＋右侧变化设计，严格 50/50 |
| `design-only` | 源图自适应 `W×H` | 只显示变化设计，不出现原照片 |
| `wallpaper-pack` | 设备分别标注尺寸 | 手机、iPad、电脑、儿童手表四张独立 PNG |

壁纸可选连贯或独立。连贯套装先批准一张定调图，所有设备都共同参考原图与这同一锚点，绝不裁切或串联衍生图；独立套装每张只参考原图。

## 文案与语言

正式生成前确认自动文案、准确自定义文案或无文字；语言跟随目标受众而不是命令语言，用户给出的准确文案逐字保留。

本项目的文案规则： 以目标语言使用一个极短地点、主体、主题或旅行情绪标题，沿外框弧排、嵌成珐琅字、穿过负形或成为金属铭牌；最多增加两个有依据的微型元素。

## 几何、位图与可信边界

普通模式未指定尺寸时按源图自适应；双联严格 50/50，全部交付为 PNG 位图。每次调用都在 `~/Desktop/xxd/` 下创建新任务，绝不泄露私密生成路线信息。

已配置的位图桥只输出脱敏状态，绝不暴露服务方、端点、凭据、请求头、提示词、响应或账户信息。SVG、HTML、Canvas、图表和程序绘图都不能代替最终位图作品。

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

完整规格: [Skill 工作流](SKILL.md) · [原始风格档案](references/037-source.md) · [英文生产提示词](references/xxd-panel-037-prompt.en.md) · [中文生产提示词](references/xxd-panel-037-prompt.zh-CN.md)

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
