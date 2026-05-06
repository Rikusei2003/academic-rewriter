# Academic Rewriter —— 让你的论文"闻不出 AI 味儿"

> 别人用 AI 写论文，你用 AI 让它读起来不像 AI 写的。🤫

---

## 这玩意干嘛的？

把一读就知道是 ChatGPT 写的学术文本，变得像人类自己敲出来的。

两个模式，一键切换：

| 模式 | 触发词 | 效果 |
|------|--------|------|
| 🎓 **学术润色** | `[polish]` | 逻辑更严密、表达更学术，该严谨的地方帮你补上 |
| 🥷 **去 AI 化** | `[enhance]` | 消除 AI 特有的"光滑感"，带点人类写作的自然啰嗦 |

默认不加标签就走润色模式。

---

## 怎么用？

把 `SKILL.md` 丢进你的 Claude Code skills 文件夹，然后：

```
[enhance] 基于深度学习的目标检测算法在复杂场景下…
```

没有标签也行，默认帮你润色。

---

## 牛在哪？

- 🌏 **中英文通吃** —— 两种语言各有专门的处理策略，不是粗暴翻译
- 🔒 **术语丝不动** —— API 路径、代码片段、专有名词全部原样保留
- 🧹 **净输出** —— 只返回改写后的文本，绝不多逼逼一句废话
- ✅ **自带审查** —— 内置 AI 味道检查清单，输出前自我审查一遍

---

## 原理一句话

中文走"冗余注入 + 词汇降级 + 口语化"，英文走"英译中 → 中文塑形 → 机械回译"，利用中文语法的"模具效应"断层式切断英文 AI 特征。

---

## 谁做的？

一个有 AI 检测焦虑的学术打工人。更多分享见小红书 👇

[📕 我的小红书主页](https://www.xiaohongshu.com/user/profile/61f54fa30000000010008a14?channel_type=web_note_detail_r10&parent_page_channel_type=web_profile_board&xsec_token=ABa_IiYoaOfWBtWam6lrTb4-wb0swjQ3kMXAkkRfNDkCc=&xsec_source=pc_note&wechatWid=73ccaa15501db316b29f52bf2dfdcb30&wechatOrigin=menu)
