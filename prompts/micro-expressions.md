# Seedance 2.5 & MiniMax H3 人物微表情提示词合集

> 所有内容均来自 X (Twitter) 真实用户分享，保留完整来源与日期，不做任何编造。

## 1. Seedance 2.5 — 强忍哭泣 → 情绪崩溃 → 衣领遮脸

**来源**: [@PixelAigc](https://x.com/PixelAigc/status/2087325691918549391) (2026-08-11)  
**模型**: Seedance 2.5  
**原帖**: https://x.com/PixelAigc/status/2087325691918549391

```
使用参考图作为起始帧。保持角色完全一致：年轻东亚女性，灰色无袖上衣，大号细银圈耳环，柔和阴天光线，完全模糊的海岸背景。保持细微连续的手持镜头漂移。全程头发被风轻轻吹动。动作序列：
主体强忍哭泣。嘴唇紧紧抿住，下巴颤抖，胸口因急剧吸气而起伏。泪水在眼中积聚但未落下。
情绪崩溃。眼睛紧闭，嘴巴张开抽泣。泪水从双颊主动滑落。头部微微向下倾斜。
灰色上衣前领从画面底部边缘被向上直接拉起，布料自然拉伸变形，覆盖住她的下巴、嘴巴和鼻子。布料在面部特征上自然变形。画面中不得出现任何手、手指或手臂。
布料自然松开并落下，回到锁骨位置。她的脸重新露出，眼睛微微睁开向下看，嘴巴张开，沉重疲惫地喘息。
```

---

## 2. Seedance 2.5 — 一镜到底分手微表情（高细节）

**来源**: [@VeraVCreates](https://x.com/VeraVCreates/status/2087387543566491802) (2026-08-12)  
**模型**: Seedance 2.5（作者实测 2.5 在微表情真实感上明显优于 2.0 / Grok / Kling v3）  
**原帖**: https://x.com/VeraVCreates/status/2087387543566491802

**核心结构摘要**（完整版非常长，包含外观锁定、灯光、镜头、时间分段、负面约束，建议直接去原帖查看回复中的完整提示词）：

- 15秒、16:9、一镜到底
- 只拍女主 Mora 的脸部微表情递进（强装镇定 → 被一句话刺穿 → 强忍眼泪说 “Please don't”）
- 男方仅以模糊肩膀出现在前景右侧
- 强调生理顺序：眼周 → 嘴唇 → 下颌
- 泪水先积聚在下眼睑，再自然滑落，不突然出现

**关键时间分段示例**：

```
[0-3 SECONDS | BEFORE SAYING IT]
The shot begins in a stable medium close-up. Mora looks at her off-screen lover without speaking. She takes one shallow breath but does not fill her lungs; her collarbones and shoulders move only slightly. ... Her mouth corners remain level, but the left corner pulls downward almost imperceptibly.

[3-6 SECONDS | HIS ONE SENTENCE]
... When Mora hears the word “stay,” her eyes shift downward toward the table while her head remains still. About 0.3 seconds later, she raises her gaze back... Her breathing stops for half a second; her nostrils tighten slightly rather than flare. ... She swallows once...

[6-9 SECONDS | THE FIRST BREAK]
... She blinks quickly once, trying to push the tears back. Before the blink, there is already a very thin wet shine in her left lower eyelid. After the blink, the tear does not fall immediately...

[9-12 SECONDS | THE TEAR FALLS]
... Once the tear builds beneath her left eyelashes, the first tear falls naturally and slowly down her left cheek, leaving an irregular wet trail...

[12-15 SECONDS | REFUSING COMFORT]
... Mora: “Please don’t.” After speaking, she does not turn around, leave, or cry loudly. The final frame remains a close-up of her face...
```

完整详细版本请直接访问原帖。

---

## 3. Seedance 2.5 — 七种微表情控制（羞嗔、傲娇、闷气、警告、心冷、委屈、挣扎）

**来源**: [@MrLarus](https://x.com/MrLarus/status/2088189059206156647) (2026-08-14)  
**模型**: Seedance 2.5  
**原帖**: https://x.com/MrLarus/status/2088189059206156647

作者强调：锚定人物形象后，把情绪触发、眼神神态和身体反应设计好，每一段用独立情境 + 视线、呼吸、动作和停顿。

**作者公开的微表情提示词框架**（可直接迁移到 2.5）：

1. 确立毫米级动作边界（眼睑、嘴角牵动控制在极小幅度，额头等区域绝对静止）
2. 遵循生理传导顺序（先变眼周 → 再变口唇 → 最后微调下颌）
3. 赋予情绪物理惯性（前一阶段的眼眶红润与泪光需在后一阶段缓慢减弱并保留残留）
4. 采用正向参数约束（保持真实皮肤纹理、维持恒定景别等）

参考结构示例（作者此前公开）：

```
生成9:16竖版人物头肩部特写微表情视频，一镜到底无剪辑。全程严格保持人物形象、服饰妆容及背景光线一致。情绪轨迹：克制高兴→笑意迟疑→湿润感初现→压抑伤心→强压哭意→含泪释怀→平静收回。控制要点：先变眼周再变嘴唇，所有动作控制在毫米级；第4阶段起眼部逐渐出现湿润反光并延续至结尾缓慢减弱，禁止流泪滑落或突然红眼消失；画面要求真实摄影质感，保留毛孔与发丝细节，禁止滤镜感、磨皮过度及镜头推拉摇移。
```

---

## 4. MiniMax H3 vs Seedance 2.5 对比（分手片段微表情）

**来源**: [@Pluvio9yte](https://x.com/Pluvio9yte/status/2087920615072453046) (2026-08-13)  
**原帖**: https://x.com/Pluvio9yte/status/2087920615072453046  
**结论**: 同样提示词下，Seedance 2.5 明显人物对微表情控制的更好

（具体提示词未在主帖公开，但视频可直接对比两者差异）

---

## 使用建议（来自这些帖子的共性）

- **时间分段 + 动作链** 比单纯写“微笑/悲伤”有效得多
- 具体写：瞳孔轻微震动/收缩、唇角不易察觉抽动、眼眶泛红但不立刻流泪、喉结滚动、呼吸短促不稳、眉心浅蹙旋即展开等
- 约束词：自然、克制、渐进、无夸张、不变形、面部稳定
- Seedance 2.5 近期用户反馈在“犹豫、泪水自然积聚而非突然出现、呼吸与眼部联动、毫米级变化”上明显提升

---

*Last updated: 2026-08-17*  
*All content attributed to original X posts with direct links.*
