# Micro-Expression Prompts - 2026-11-17

Four full, sourced prompts from X (search window: 2026-11-15 to 2026-11-17 UTC). Texts are copied verbatim from the posts. Prompts already collected in the 2026-11-16 file (@ou_zhen599 “Reeds” / “Water Temperature Gone Wild” / “There’s No Time”; @PixelAigc 李安《色・戒》片断复刻; @abxxai sandstone sea cave; @john87445528《隔墙有眼》) and the 2026-11-15 file are excluded.

## Prompt 1 — 李安《色・戒》参考生图规范提示词，四种模型对比 (MiniMax H3)

- **Source**: [@PixelAigc](https://x.com/PixelAigc) (PixelAIGC)
- **Model**: MiniMax H3
- **Original post URL**: https://x.com/PixelAigc/status/2122291412507201888
- **Posted**: 2026-11-16T11:31:17.000Z
- **Note**: 与 2026-11-16 文件中的《色・戒》片断复刻不是同一条提示词。作者说明这次用的是「参考生图的规范提示词」，并在文生视频里使用同一条；主帖上传的是文生视频作品，LoRA `minimax_h3_turbo_4step_ema_ckpt850.safetensors`，强度 1，6 步，15 秒，用时 14 分钟。作者用相同提示词对比四种模型，认为文生视频更胜一筹。微表情写在分镜里，例如 “one corner of her mouth shifts in an extremely faint, almost invisible smile that does not reach her eyes”，以及 “He does not blink until the line ends。”

~~~
subject_definitions:
<Subject 1> is the woman in <Picture 1>, Wang Jiazhi (Mrs. Mai): a woman in her mid-twenties with curled shoulder-length hair, a dark-patterned qipao, composed features over fear and calculation in her eyes, and a light, soft, tightly stretched voice.
<Subject 2> is the man in <Picture 2>, Mr. Yi: a man around thirty in a dark suit, with a cold, suspicious, heavily guarded face and a low, slow, deliberate voice.

summary:
[reference generation] The target video is a twenty-five-second, seven-shot dialogue scene in a cramped 1940s Shanghai hotel room. <Subject 1> and <Subject 2> stand half a step apart in the half-lit room and test each other through six hushed lines of Chinese dialogue, cut in strict shot-reverse-shot on a fixed 180-degree axis, and ends on rain sliding down the window glass with no dialogue.

retention_analysis:
<Subject 1> (appears in [Shot 1], [Shot 3], [Shot 5], [Shot 6]): fully_preserved - her identity, curly hair, dark-patterned qipao, and restrained facial features are retained, and her voice stays light, soft, and tightly controlled.
<Subject 2> (appears in [Shot 1], [Shot 2], [Shot 4], [Shot 6]): fully_preserved - his identity, dark suit, cold guarded expression, and low slow voice are retained.
detailed_description:
The target video is shot on 35mm film in a restrained period-drama style: low-saturation warm-brown tones, weak rainy daylight from the window meeting a single bedside lamp, the frame divided half in soft light and half in heavy shadow, shallow depth of field, visible film grain, natural unretouched skin, 24fps. The camera never crosses the 180-degree axis, every transition is a hard cut, and no shot uses a whip pan, arc, or handheld movement.

[Shot 1] A static two-person medium-close shot frames <Subject 1> and <Subject 2> standing in the narrow center of the room, the door just shut behind them. <Subject 1> wears the dark-patterned qipao, her curled hair catching a thin edge of window light; <Subject 2> stands half a step opposite in his dark suit, shoulders squared, chin slightly lowered. Rainlight seeps through the window seam and lays a pale band across the mottled wallpaper. Neither moves; the air between them stays still. <Subject 1> (S1) says in a light, soft, tightly controlled voice, barely above a whisper, as if afraid of being overheard: <d>[Chinese] 这地方，没人会来打扰我们。</d> Her lips close and she holds his gaze without blinking.

[Shot 2] At 00:04.000, the shot cuts to a close-up of <Subject 2> (S2). The bedside lamp lights one side of his face while the other falls into shadow. His gaze travels slowly across her face, his jaw tight, his whole body braced. He says in a low, slow, deliberate voice with no warmth: <d>[Chinese] 你选这里，胆子很大。</d> His eyes stay fixed on her after the last word.

[Shot 3] At 00:08.000, the shot cuts back to a shoulder-and-neck close-up of <Subject 1> (S1), framed from the side that keeps the axis intact. Her fingers curl tighter into the hem of her qipao, knuckles paling against the fabric, and her lashes tremble once before she steadies them. She answers in the same soft, controlled voice, a faint effort audible beneath it: <d>[Chinese] 我以为，你愿意冒这个险。</d> Her chin lifts a fraction at the end of the line.

[Shot 4] At 00:12.000, the shot cuts to an extreme close-up of <Subject 2>'s eyes. His pupils contract slightly as suspicion and testing cross his gaze, the lower lid tense, a muscle moving at the corner of his jaw. The lamp reflection sits as a small hard point in each eye. He says, quieter and slower than before: <d>[Chinese] 你到底想要什么？</d> He does not blink until the line ends.

[Shot 5] At 00:16.000, the shot cuts to a medium close-up of <Subject 1> (S1), half of her face in shadow from the window frame. She raises her eyes slowly to meet his look, and one corner of her mouth shifts in an extremely faint, almost invisible smile that does not reach her eyes. She says in the same light, soft voice, now with a thread of controlled nerve: <d>[Chinese] 我想要的，你心里清楚。</d> Her gaze stays level and does not drop.

[Shot 6] At 00:20.000, the shot cuts to a two-person medium close-up, both of them in frame on the same side of the axis as [Shot 1]. The camera pushes in with small amplitude at very slow speed, tightening the space between them while neither moves. <Subject 2> (S2) says in a low murmur, almost to himself: <d>[Chinese] 那就别后悔。</d> The frame continues to compress until their shoulders nearly fill the width.

[Shot 7] At 00:23.000, the shot cuts to a static close-up of rain running down the window glass in slow crooked lines, the blurred room behind it falling out of focus. No figure is visible. The shot holds unmoving to the final frame, with no fade and no blackout.

overall_soundscape:
Steady rain falls beyond the window and a thin draft creaks the old iron window frame at irregular intervals. Fabric rustles when she grips the qipao hem, and the tight, boxy room reverb sits on every sound, with muffled silence from the corridor outside. Breathing stays low and controlled throughout.

non_diegetic_music:
N/A
~~~

## Prompt 2 — 《大话西游》经典「爱你一万年」片段 (MiniMax H3)

- **Source**: [@PixelAigc](https://x.com/PixelAigc) (PixelAIGC)
- **Model**: MiniMax H3
- **Original post URL**: https://x.com/PixelAigc/status/2122330838146961559
- **Posted**: 2026-11-16T14:07:57.000Z
- **Note**: 作者说明本地 MiniMax H3、turbo LoRA 6 步文生视频、540P 直出，25 秒，用时 19 分半，显卡 4070 16G。情绪从戒备、嘲讽转为震撼与含泪；近景写「眼眶微红」，紫霞特写写「眼神动摇……嘴唇轻颤，眼底泛起泪光」。

~~~
# MiniMax H3 中文提示词｜25秒，《大话西游》经典“爱你一万年”片段，中文对白，16:9，24fps，2K

output_spec:
画幅16:9，时长25秒，24fps，2K，电影画面质感，无字幕，无水印，无画面文字，人物面部稳定，五官清晰自然，动作连贯，镜头节奏克制。

integrated_multimodal_description:
《大话西游之大圣娶亲》经典喜剧电影质感，荒凉山寨石洞内部，石壁粗粝，烛火摇晃，低饱和复古色彩，轻微胶片颗粒，苍凉又深情的氛围。紫霞仙子执剑与至尊宝近距离对峙，画面中只有紫霞仙子、至尊宝、长剑、火把与石壁背景。

人物设定：
紫霞仙子：年轻女子，古装女侠造型，眼神倔强又带伤感，手持长剑，剑身横在至尊宝面前，情绪从戒备、嘲讽逐渐转为震撼与含泪。
至尊宝：年轻男子，略带不羁的古装造型，头发微乱，表情从无奈转为认真、悲怆，最后深情告白。

[Shot 1] 00:00-00:05
景别：中近景双人同框。
运镜：固定机位，轻微手持呼吸感。
画面：紫霞仙子持剑横在至尊宝颈前，两人站在石洞中央，烛火从侧后方照亮人物轮廓。紫霞盯着至尊宝，剑尖停在他胸前，动作克制。
台词（紫霞，冷声带笑）：“你以为我不敢杀你？”

[Shot 2] 00:05-00:11
景别：至尊宝近景。
运镜：硬切，镜头缓慢push in。
画面：至尊宝看着紫霞，表情由吊儿郎当变得认真，眼眶微红，背景烛火虚化成暖光斑。
台词（至尊宝，语气郑重）：“曾经有一份真诚的爱情放在我面前，我没有珍惜。”

[Shot 3] 00:11-00:17
景别：双人中近景。
运镜：硬切，轻微缓慢推镜。
画面：紫霞握剑的手微微发紧，至尊宝站在她面前，没有后退，两人目光牢牢相接，石洞内火光轻晃。
台词（至尊宝，声音低沉）：“等我失去的时候，我才后悔莫及。”

[Shot 4] 00:17-00:21
景别：紫霞特写。
运镜：硬切，定镜。
画面：紫霞眼神动摇，剑尖缓缓下垂，嘴唇轻颤，眼底泛起泪光，原本的倔强被击中。
台词（至尊宝，画外音）：“人世间最痛苦的事，莫过于此。”

[Shot 5] 00:21-00:25
景别：双人近景。
运镜：镜头极慢zoom in，收束在两人对视。
画面：至尊宝看着紫霞，紫霞的剑已经放下，两人之间空气安静，烛火映在脸上，画面深情定格。
台词（至尊宝，轻声）：“如果非要加一个期限，我希望是——一万年。”

overall_soundscape:
石洞空旷风声，火把燃烧声，长剑轻微金属声，衣料摩擦声，人物呼吸声，环境底噪自然，不盖对白。

non_diegetic_music:
低沉忧伤的二胡与箫声，旋律缓慢苍凉，音量低，只在对白空隙增强情绪，不抢人声。
~~~

## Prompt 3 — 神龙政变·长生殿逼宫（武则天）(MiniMax H3)

- **Source**: [@PixelAigc](https://x.com/PixelAigc) (PixelAIGC)
- **Model**: MiniMax H3
- **Original post URL**: https://x.com/PixelAigc/status/2122356408004084062
- **Posted**: 2026-11-16T15:49:33.000Z
- **Note**: 作者说明本地 MiniMax H3，用 PIKA H3 Flex LoRA 6 步加速，权重 1，544P，25 秒（提示词按 30 秒写，为确保输出质量压缩成 25 秒），用时 21 分钟。开篇即要求「摒弃舞台剧式夸张表演，冲突依靠神态、呼吸、眼神张力、人物气场推进」，并在分镜中给出 AU 辅助（AU4 眉毛轻压、AU23 嘴唇收紧、AU5 上眼睑抬高）。泪水写成先「眼底泛起水光，但还没有落泪」，再在面部极近特写里「眼眶迅速蓄满泪水，一滴泪珠缓缓从苍老脸颊滑落」。结尾重申「依靠微表情、眼神、人物气场烘托紧张氛围」。

~~~
# 30秒写实电影质感｜神龙政变·长生殿逼宫剧情短片
## 一、整体基础设定
生成一支30秒、中式古装写实电影质感、原生同步中文对白的历史剧情短片。
画幅为宽银幕20:9，写实电影摄影，24fps观感，轻微细腻35mm胶片颗粒，压低数码锐化。
场景设定武周末年洛阳皇宫长生殿内，深色描金梁柱、厚重暗紫色丝绒帷幔、青铜烛台、古朴地砖。拂晓时分，清冷微弱天光从高处窗棂斜照进大殿，烛火摇曳，空气中浮着淡淡的烟尘。刚刚经历杀伐，殿内气氛紧绷肃杀。
整体画面色调克制沉郁：暗紫、古铜、炭灰、褪色朱红，走正史写实风格。杜绝仙侠特效、浮夸影楼古装、现代物件、商业广告质感。
摒弃舞台剧式夸张表演，冲突依靠神态、呼吸、眼神张力、人物气场推进，是老臣以大势规劝女皇还政，不是粗暴武力咆哮。

## 二、故事内核&表演基调
核心冲突：神龙政变成功诛杀二张之后，八十岁宰相张柬之带领禁军来到长生殿，当面逼迫已经大权旁落的武则天交出皇权、传位太子。一边是耄耋老臣，隐忍多年、意志坚定；一边是叱咤半生、骤然被夺权，从震惊、强作威严，慢慢认清大势已去。
表演基调：张柬之举止恭敬，语气沉稳坚定，有理有据，不带狂妄；武则天从骤然惊醒的错愕、女皇式的威压质问，一步步转为心力交瘁、万般无奈。情绪轨迹：张柬之：沉稳肃穆→恳切强硬；武则天：惊惶震怒→心存侥幸→无力认命。戏剧重心落在权力交接那一瞬间无声的拉扯。

## 三、人物一致性
### 张柬之
80岁东亚老年男性，身形清瘦腰背依旧挺直，面容布满深刻皱纹，花白胡须，眼神沉静锐利，自带饱经世事的沧桑。身穿武周时期宰相绛色朝服，官帽规整，衣料厚重垂顺。
声线：苍老沉稳厚重男声，语速不快，字句清晰有力，态度恭谨却立场绝不动摇。

### 武则天
78岁东亚老年女性，鬓发花白，脸上布满岁月纹路，身着深紫色寝居便式宫装，刚从睡梦中惊起，发髻微乱，褪去平日全副帝王盛装，依旧残存女皇气场，眼神锐利。保留真实皮肤纹理，拒绝过度美颜。
声线：略带沙哑苍老女声，一开始带着帝王的威严怒意，后面声调缓缓下沉，透出疲惫无力。

全局人物约束
两人全程面孔、年龄、发型、服饰保持不变，禁止面部漂移、五官变形，不模仿影视剧中已知演员长相。
严格遵守180度轴线：张柬之位于画面左侧，武则天位于画面右侧，二人相隔约两米，视线对接，站位固定不互换。

## 四、分镜头时序模块
【镜头一｜0.0‑6.3秒】
85mm人像镜头，张柬之胸部以上近景，三分之二侧脸朝向画面右侧武则天。背景虚化晃动的帷幔与青铜烛台，极浅景深。
摄影机近乎完全固定，只保留极其细微的手持呼吸感，无推拉、环绕、升降运镜。
0.0‑2.9秒：老人身姿挺拔，眉头微敛，花白长须随着微弱呼吸轻微起伏，目光稳稳看向女皇，神色肃穆，没有半分张狂。
表情辅助：AU4眉毛轻压，AU23嘴唇收紧。
2.9‑6.3秒：微微躬身，做出臣子觐见姿态，语气平稳却不容退让。
张柬之声色沉稳：
“二张谋反作乱，臣等奉太子之令，已将二人诛杀。”
台词说完立刻硬切，无淡入淡出。

【镜头二｜6.3‑17.6秒】
硬切至武则天越肩近景，张柬之朝服肩头作为模糊前景占据画面左下角1/5。武则天处在画面中央偏右，胸部以上构图，背景是被风吹动的丝质帷幔。
摄影机基本固定，仅有几乎察觉不到的轻微呼吸晃动；随着女皇心神动摇，镜头极其缓慢微小向前推进。
6.3‑9.6秒：武则天猛地惊起，眉心骤然紧锁，双眼睁大，胸口急促起伏，睡意全无，带着上位者被冒犯的震怒。
表情辅助：AU5上眼睑抬高，AU4眉心下压。
9.6‑13.2秒：强压下慌乱，努力维持女皇威仪，目光锐利盯住张柬之，声音带着惊魂未定的质问。
武则天语气威严，带着怒气：
“是谁在宫外作乱？！”
13.2‑17.6秒：听完叛乱已经平定，眼底闪过一丝震动，肩膀微微垮下，内心开始意识到局势已经失控，眼底泛起水光，但还没有落泪。卡点硬切。

【镜头三｜17.6‑24.1秒】
硬切回张柬之近景，焦段、光线、机位与镜头一完全一致。武则天的画外音从画面右侧传来。
17.6‑19.8秒：张柬之眼神没有丝毫躲闪，神情依旧平静，没有被女皇的气势震慑。
20.0‑22.0秒：下颌微微收紧，语气恳切，但立场丝毫不松，摆出无可逆转的现实。
22.0‑24.1秒：微微低头行礼，说出最关键的诉求。
张柬之继续沉稳进言：
“太子不可再返回东宫，请陛下传位于太子。”

【镜头四｜24.1‑30.0秒】
硬切至武则天面部极近特写，相比前一个镜头机位更加靠近脸部。
24.1‑26.6秒：眉毛内侧向上挤压，眼眶迅速蓄满泪水，一滴泪珠缓缓从苍老脸颊滑落，鼻翼微微颤动，嘴唇无力的轻抖。
26.6‑30.0秒：女皇的眼神彻底失去往日锋芒，头颅微微低下，一股深深的无力席卷全身，声音疲惫沙哑。
武则天语气低沉、心力交瘁：
“事已至此……便依你们所言。”
台词结束定格武则天落寞失神的面部0.3秒，短片直接收尾，不做淡出。

## 五、声音设计
原生生成中文对白，区分两位说话人，口型与每一个音节准确同步。
张柬之人声：苍老厚重男声，情绪轨迹：肃穆冷静→有理有据→坚定规劝。语速平缓，不靠音量压迫，依靠话语本身的分量。
武则天人声：苍老沙哑女声，情绪轨迹：惊醒震怒→强撑威严→大势已去、满心疲惫。
保留真实人声细节：沉重呼吸、气息起伏、苍老的颤音，禁止过度降噪。
环境音：长生殿空旷的回声，远处隐约传来甲胄轻微碰撞声，烛火噼啪微弱声响，大殿安静底噪。
禁止背景音乐、配乐、旁白、夸张戏剧音效。

## 六、影像限制
禁止字幕、水印、logo以及任何可读文字。
禁止额外第三人、场景中途切换、人物服饰发型发生变化、人脸漂移。
禁止美颜磨皮、仙侠滤镜、夸张大幅度肢体动作、嘶吼尖叫、慢动作、环绕镜头、急速推拉。
禁止目光涣散漂移、口型错位、嘴唇粘连、过度虚假流泪。
整体风格写实历史古装，武周服饰器物符合时代特征，不要唐宋服饰混搭，拒绝CG游戏质感。

## 七、核心主旨重申
短片重点刻画权力交接最后一刻沉重无声的博弈，依靠微表情、眼神、人物气场烘托紧张氛围，不用花哨运镜，还原八十岁老臣张柬之孤注一掷，逼迫一代女皇武则天还政李唐这一历史性瞬间。
~~~

## Prompt 4 — “Turn up the sound of the ocean a little.” (MiniMax H3)

- **Source**: [@ou_zhen599](https://x.com/ou_zhen599) (Loriel.AI)
- **Model**: MiniMax H3
- **Original post URL**: https://x.com/ou_zhen599/status/2122363415851356554
- **Posted**: 2026-11-16T16:17:24.000Z
- **Note**: 完整提示词在主帖 https://x.com/ou_zhen599/status/2122363103388340365 的回复中；以下为回复原文。作者标注 Made with Krea 2 + MiniMax-H3 ComfyUI。表演写成 “looks toward the lens with slightly tightened lower eyelids and parted lips”，以及 “Her eyes re-lock the camera from beneath the sunglasses edge; pupils settle first, then the outer eye corners curve slightly”。

~~~
MiniMax-H3 prompt👇
For the target video, at 0.00 seconds into the target video, <Picture 1> (from [Shot 1]) is fully referenced.

integrated_multimodal_description: [Shot 1] Live-action, realistic cinematic, 16:9, a 15-second I2VA single-take beach video. The first frame fully preserves <Picture 1> as the same adult woman over 20, same face, hairstyle, white over-ear headphones, sunglasses, black cropped T-shirt, bikini bottom, patterned beach blanket, beach sand, sea waves, sea-grass shadows, portable speaker, and warm golden backlight. The entire video stays on the same beach blanket and its immediate surrounding radius. No scene change, no extra person, and no off-screen person appears visually; the off-screen person exists only as the implied listener in her gaze and spoken lines.

[00:00-00:02.000] The first frame is already moving. The camera starts low near the edge of the beach blanket, with tassels, sand grains, and the white headphone cable in the foreground. It pushes in quickly with a slight handheld breathing shake toward her braced hand, waist, and upper torso. She is seated diagonally on the front-right side of the blanket, body three-quarter facing the camera, right hand braced behind her, one leg naturally bent, ocean on frame-left and sea grass behind on frame-right. Her right palm presses into the blanket, shoulders and back engage, and her body leans half an inch forward. The headphone cable sways lightly. Through the sunglasses, she looks toward the lens with slightly tightened lower eyelids and parted lips, as if she has just noticed someone approaching. The shirt fabric shows one brief natural micro-inertia response from the bracing movement.

[00:02.000-00:04.500] The camera holds an intimate close shot from chest to jawline with shallow depth of field. Focus shifts from the white headphone cable to her fingers, then to her lips and the lower edge of the sunglasses. She slowly removes one side of the headphones: fingertips press the ear cup, then slide through her hair; hair tips follow with delayed motion. Her gaze avoids the lens for half a beat, then lifts toward the camera from above the sunglasses edge. The adult woman with a low, soft, breathy English voice (S1) says: <d>[English] You came this close... for the music, or for me?</d> The first half is quieter, with a half-beat pause after “this close,” and “for me” falls softly without exaggerated seduction.

[00:04.500-00:06.800] She suddenly throws her gaze toward the ocean on the left. Her shoulders and waist twist together within the seated pose. The camera follows her sightline with one short whip-like shake, passing silver reflections and tiny foam on the waves, then immediately trucks back to catch her side face, neck line, chest area, and arm. During the twist and sudden stop, the shirt fabric shows a second natural delayed micro-movement caused by shoulder-waist inertia; the headphone cable brushes lightly across the shirt, then swings back slowly. For a moment, her eyes look blankly toward the sea; lashes catch a golden rim, her mouth corner relaxes, and the mood shifts from teasing to genuinely enjoying the sea wind.

[00:06.800-00:10.800] The camera begins a bullet-time-like slow half-orbit from her right-front side, moving no more than 120 degrees around her upper body while lowering slightly. As she keeps looking toward the sea, she slowly lowers her body backward: her right hand changes support from behind her to the blanket edge, fingers catch the tassels, elbow bends, waist and abdomen release first, and shoulder blades settle after. Sea-grass shadows slide over her cheek, collarbone, shirt fabric, and abdomen. Her eyes look to the sea first, then lower with her lashes, then check from the corner to confirm the camera is still there. A very thin smile appears without fully opening. She says quietly: <d>[English] Don’t rush. Let the wind finish first.</d> “Don’t rush” is low and controlled, “Let the wind” is lighter, and “finish first” trails shortly. Her breathing is clearly visible here: chest and abdomen rise subtly with a slow inhale, shirt folds open slightly with breath and then settle back.

[00:10.800-00:12.800] As she continues lying back, her right elbow slips lightly on the sandy edge of the blanket and tassels. Her body drops backward by half an inch, then immediately stabilizes with abdomen, shoulders, back, and left hand. The camera drops with her, then performs a rebound variable-speed move, tilting downward from a diagonal close angle toward her chest, collarbone, lips, and lower sunglasses edge. This third close-up peak stays action-driven: the chest area shows a short natural micro-tremor caused by the backward drop and sudden self-stabilization, then it is pressed down by one slow exhale. Shirt folds stretch, rebound, and settle realistically. Her eyes re-lock the camera from beneath the sunglasses edge; pupils settle first, then the outer eye corners curve slightly, and the corner of her mouth shows a small victorious smile.

[00:12.800-00:15.000] The camera becomes the off-screen person’s close POV and holds static. She is now lying on the patterned beach blanket. One side of the headphones hangs near her neck while the other side remains on; the white headphone cable sways lightly over the shirt and blanket. With her fingers, she pushes the sunglasses down slightly and looks directly into the lens. Her expression shifts from teasing to lazy control. Her breathing slows, her lips part, and she says in a lower, closer English voice: <d>[English] Now... let me sunbathe.</d> There is a half-beat pause after “Now,” and “let me sunbathe” is light, slow, and faintly smiling. The ending holds on her close view lying on the blanket: ocean reflections flicker across the sunglasses, hair lifts gently in the sea breeze, her chest rises and falls slowly with natural breathing, and the wave sound gradually overpowers the faint music leaking from the headphones. The final image keeps the sea light, wind, and breathing afterglow, with no cut to black and no fade-out.

Fluid and physical effects remain grounded: thin wave foam on the left advances and retreats along the sand edge, breaking into tiny droplets that glitter in low-angle light; damp sand reflects warm golden points. The sea breeze blows from left-front toward right-rear, moving her hair with roots responding first and tips lagging. The headphone cable swings in a small pendulum motion. Blanket tassels fall back after being pulled by wind and fingers. When her palm presses into the blanket, sand grains collapse slightly and tassels flatten before springing up; when her elbow slips, the blanket forms small dragged wrinkles and shallow sand marks. All chest-area micro-movements occur only from three physical triggers: bracing forward, twisting and stopping, and lying back then stabilizing. They remain realistic, restrained, supported by clothing, and never exaggerated.

Lighting and color: warm golden beach light from late afternoon toward early evening. Key illumination comes from ocean reflection and side-back sunlight from the upper-left of frame, around 4300K-5000K. Warm beach bounce softly fills her face, while hair, shoulders, neck, and sunglasses edges carry golden rim highlights. Sea-grass shadows form small moving patterns over the sand, blanket, and her body. Color grade: Warm Golden Beach Film Grade, with amber-gold highlights #F6C66B, sandy midtones #D8B07A, deep red patterned blanket #8E2F24, silver-blue ocean reflection #BFD7D9, and deep but not crushed black T-shirt #111111. Skin remains naturally warm peach; highlights are soft and not overexposed; shadows lean warm brown. Contrast is medium, saturation controlled, with real film grain and clear coastal air.

Negative constraints: no cut to black, no fade-out, no scene change, no extra person, no off-screen person entering frame, no subtitles, no watermark, and no extra text. Preserve the same character identity, facial features, hairstyle, outfit, headphones, sunglasses, beach blanket, and seaside environment continuously. No broken face, no eye drift, no exaggerated mouth shape, no abnormal teeth, no body deformation, no extra fingers or limbs, no exaggerated chest distortion, no clothing clipping, and no broken or randomly flying headphone cable. All allure must come from real action, breathing, inertia, eye behavior, and body-weight shifts.

overall_soundscape: Continuous ocean waves, light sea wind, soft sand friction, blanket tassels brushing under her fingers, and faint low-volume music leaking from the headphones stay present across the take. The headphone cable adds small fabric-contact sounds, and the blanket rustles subtly as her hand, elbow, and body weight shift. Her spoken English lines are close and breathy in the shot, while the off-screen person never responds.

non_diegetic_music: N/A
~~~

## Usage tips

- @PixelAigc 的长生殿逼宫提示词把冲突压在近景和极近特写里，明确要求「不用花哨运镜」，并用 AU 编码辅助毫米级表情（AU4 / AU5 / AU23）。泪水按生理顺序写：先「眼底泛起水光，但还没有落泪」，再在最后特写里让一滴泪缓缓滑落，同时禁止「过度虚假流泪」。本地参数：PIKA H3 Flex LoRA 6 步、权重 1、544P、时长压缩为 25 秒。
- @PixelAigc 的「爱你一万年」把情绪变化写进分镜：至尊宝近景「表情由吊儿郎当变得认真，眼眶微红」；紫霞特写「眼神动摇，剑尖缓缓下垂，嘴唇轻颤，眼底泛起泪光」。本地参数：turbo LoRA 6 步、540P、25 秒。
- @PixelAigc 的《色・戒》参考生图版把微表情写成可执行的小动作，例如「嘴角极轻微、几乎看不见的笑，但笑意不到眼睛」，以及「整句台词说完之前不眨眼」。作者用同一条提示词对比四种模型，认为文生视频明显更好；示例参数为 `minimax_h3_turbo_4step_ema_ckpt850.safetensors`、强度 1、6 步、15 秒。
- @ou_zhen599 延续眼睛先动、头和嘴随后跟上的写法：先「pupils settle first, then the outer eye corners curve slightly」，再写嘴角和呼吸；并强调 “All allure must come from real action, breathing, inertia, eye behavior, and body-weight shifts.”

Last updated: 2026-11-17
