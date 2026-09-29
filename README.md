# lhg-writing · 中文写作

[English](#english) | [中文](#中文)

---

## English

**Chinese Writing** produces clear, opinionated, human-sounding Chinese prose. AI writing flaws are treated as a taxonomy of writing problems — hollow phrasing, corporate jargon, over-structuring, no personality, vague diction — not as something to merely "hide from detectors." The goal is writing quality itself.

### Workflow

1. **Scope** — confirm genre (WeChat article / blog / Xiaohongshu / Q&A / docs), audience, and desired effect.
2. **Style fingerprint** — from 1–3 of the user's own pieces, build a *measurable* style card (sentence-length distribution, function-word tics, punctuation habits, paragraph rhythm, person/tense, rhetorical patterns, emotional arc) instead of vague praise like "sharp prose." Method: computational stylometry (Mosteller & Wallace 1964; Burrows' Delta; Huang et al. 2024 LIP).
3. **Outline → sections** — outline first, then write section by section, under the hard constraints of **Orwell's six rules** (1946): no dead metaphors, short words over long ones, cut every cuttable word, active voice, everyday Chinese over jargon, and clarity over rules.
4. **AI-flavor diagnosis** — check against a Chinese AI-tell fingerprint library (self-authored entries; methodology inspired by community practice): graded signals (strong/medium/weak) with verbatim quotes, e.g. overused "不是 X 而是 Y", hedge-stacking, template openings ("随着 AI 技术的发展…"), hollow blessing closings ("愿你…"), forced uplift, fake anecdotes, concept-stacking without specifics.
5. **False-positive guardrails** — single rhetorical devices are fine; only density counts. When in doubt, don't flag.
6. **Consistency check** — terminology, person, tense, numbers, and stance across sections.
7. **Fact check** — two passes: de-AI the prose first, then verify nothing was invented (no fabricated details, numbers, or quotes).

### Output

Final draft · AI-flavor diagnosis table (quote → signal strength → fix & reason) · style fingerprint card · consistency checklist · change notes.

### Compatibility

Pure process description in Markdown — no dependency on any specific agent platform. Portable to any environment that supports Markdown instructions (Claude Code, Codex, Doubao, Workbuddy, etc.).

### Operating principles

- Facts, numbers, and quotes must have sources; unwarranted detail is cut, never invented.
- Diagnosis prefers false negatives over false positives.
- Style is described with measurable features, not mystical adjectives.
- Standpoint: quality first, not "evading detection."

### Theoretical grounding

Orwell (1946) · Mosteller & Wallace (1964) · Burrows' Delta (2002) · Huang et al. (2024) LIP · blader/humanizer (MIT) · a16zcrypto "The habits of AI writing."

### License

MIT — see [LICENSE](LICENSE).

---

## 中文

**中文写作**：写出清晰、有观点、有人味的中文。AI 写作的通病不是"像机器"，而是放大了人类写作的老毛病：空洞表达、商业套话、过度结构化、没有个性、措辞模糊。**本 skill 的立场：目标是写作质量本身，而不是"躲避 AI 检测"**——把所谓 AI 味特征当作一套写作问题分类来用。

### 流程

1. **定体裁与读者** — 公众号长文 / 博客 / 小红书 / 知乎回答 / 文档，给谁看、要达到什么效果。
2. **风格指纹提取** — 用用户 1–3 篇代表作产出**可测量的风格指纹卡**（句长分布、高频虚词与口头禅、标点习惯、段落节奏、人称视角、常用句式、情绪曲线），不用"文笔犀利"这类玄学描述。方法：计算风格学（Mosteller & Wallace 1964；Burrows' Delta；Huang et al. 2024 LIP）。
3. **大纲→逐节写作** — 先出大纲再逐节写，全程受 **Orwell 六规则**（1946）硬约束：不用陈词滥调、能短不用长、能删就删、主动语态、日常中文优先于黑话、清楚优先于规则。
4. **AI 味诊断** — 按自研中文指纹库逐处检查并引用原句，信号分强/中/弱三级："不是 X 而是 Y"滥用、反复让步两头讨好、万能套话开头、"愿你"式祝福收尾、强行拔高、模板化假故事、概念扎堆缺具体等。
5. **防误判阈值** — 单次修辞是好文笔，只看密度；拿不准的宁可不报。
6. **一致性校验** — 术语、人称、时态、数字口径、观点前后统一。
7. **事实核查** — 两遍处理：先改写去 AI 味，再检查没有编造不存在的事实、数字、引用。

### 产出

成稿 · AI 味诊断表（原句 → 信号强度 → 改法与理由）· 风格指纹卡 · 一致性检查清单 · 修改说明。

### 兼容性

纯流程 Markdown，不依赖任何特定平台，可移植到豆包智能体、Workbuddy 等支持 Markdown 指令的环境。

### License

MIT — 详见 [LICENSE](LICENSE)。

---


## 出品：刘洪光

本 skill 由真人出镜 IP「刘洪光」（安徽合肥）出品，归属 [lhg-skills](https://github.com/lhg-skills)。

- GitHub 主页：https://github.com/lhg-skills —— 全部 skill 开源在此，欢迎 star
- 视频号：搜「刘洪光实名上网」
- 微信：lhgsmsw
