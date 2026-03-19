# Seedance 2.0 关键词专项方法论

> 本文从 935 条社区验证的优质 Seedance 2.0 提示词中，针对五个高频高效关键词进行深度拆解：
> **逼真（Realistic）· 超写实（Hyper-realistic）· CGI/VFX · 一镜到底（One-shot）· 高度详细多镜头电影级（Cinematic Multi-shot）**
>
> 每个关键词提供：核心定义、触发条件、写作公式、关键技巧、典型范例、常见错误和画质标签组合。

---

## 目录

1. [逼真 / 超写实（Photorealistic / Hyper-realistic）](#一逼真--超写实photorealistic--hyper-realistic)
2. [CGI / VFX 特效级](#二cgi--vfx-特效级)
3. [一镜到底（One-shot / Continuous Shot）](#三一镜到底one-shot--continuous-shot)
4. [高度详细多镜头电影级（Cinematic Multi-shot）](#四高度详细多镜头电影级cinematic-multi-shot)
5. [关键词组合与叠加策略](#五关键词组合与叠加策略)
6. [画质标签层级体系](#六画质标签层级体系)
7. [实战模板库](#七实战模板库)

---

## 一、逼真 / 超写实（Photorealistic / Hyper-realistic）

### 1.1 核心定义

"逼真/超写实"追求的是**照片级真实感**——让 AI 生成的视频看起来像真实摄影机拍摄的实景画面。
核心不是"好看"，而是"像真的"。

### 1.2 什么时候用

- 纪录片/野生动物场景
- 日常生活/情感/浪漫类
- 写实人物动作（格斗、瑜伽、舞蹈）
- 产品展示（需要真实材质质感）
- 新闻/灾难/现实事件模拟

### 1.3 核心写作公式

```
[真实感锚定词] + [场景设定（含自然光源）] + [具体物理/材质微细节] + [真实摄影参数] + [风格标签]
```

**五层结构：**

| 层次 | 内容 | 示例 |
|------|------|------|
| 第 1 层：锚定词 | 开头用"超写实/逼真"锚定风格 | `Ultra-realistic wildlife documentary footage.` |
| 第 2 层：场景 + 自然光 | 场景描述 + 真实光源条件 | `黎明时分的雪地森林，金色日出光线从树冠缝隙倾泻` |
| 第 3 层：物理微细节 | 材质、纹理、物理反馈 | `呼吸在冰冷空气中形成小白雾，皮肤纹理可见，汗珠反射微光` |
| 第 4 层：摄影参数 | 镜头、光圈、景深 | `85mm lens, f/1.8, shallow depth of field, DSLR realism` |
| 第 5 层：风格标签 | 锚定画质标签 | `cinematic bokeh, film grain, natural lighting` |

### 1.4 关键技巧

#### 技巧 1：用真实摄影设备参数锚定真实感

写实类 prompt 的**杀手锏**是指定真实的摄影设备和参数，这会强烈暗示 Seedance 生成实拍质感的画面：

| 参数类型 | 常用值 | 效果 |
|---------|--------|------|
| 镜头焦距 | 35mm（标准）/ 85mm（人像）/ 24mm（广角） | 控制透视关系和空间感 |
| 光圈 | f/1.8（浅景深）/ f/4（适中）/ f/8（全锐利） | 控制景深虚化程度 |
| 相机类型 | DSLR / IMAX / Panavision / RED | 锚定画面质感等级 |
| 帧率 | 24fps（电影感）/ 60fps（流畅）/ 120fps（极速慢动作） | 控制运动质感 |
| 色彩科学 | Dolby Vision HDR / 广色域 / LOG 调色 | 控制色彩还原度 |

**示例：**
```
写实风格，电影级写实，8K，35mm 镜头，浅景深，柔和自然日光。
```

#### 技巧 2：微观物理细节是真实感的核心

逼真类 prompt 与其他类型最大的区别在于**微观物理细节的堆叠**——这些细节是人眼判断"真假"的潜意识依据：

| 类别 | 微细节示例 |
|------|-----------|
| 皮肤 | 皮肤纹理、毛孔、汗珠光泽、血管隐约可见 |
| 呼吸 | 胸腔微微起伏、呼吸与动作同步、寒冷中呼气成雾 |
| 毛发 | 发丝随风飘动、睫毛投下细微阴影、耳边碎发被微风撩起 |
| 衣物 | 布料随身体运动自然褶皱、汗湿的衣料贴合皮肤 |
| 环境 | 灰尘颗粒在光束中缓慢飘浮、雨滴在表面碎裂成微小水花 |
| 物理力 | 肌肉线条在发力时自然浮现、轮胎变形、泥土爆溅弧线 |

**关键原则：** 写 3-5 个微细节就够了，不要堆砌太多——挑选最能体现"真实感"的细节。

#### 技巧 3：自然光 > 人工光

逼真类场景中，**自然光描写**远比人工布光更重要：

| 光线类型 | 描写方式 | 适用场景 |
|---------|---------|---------|
| 黄金时刻 | `golden sunrise lighting` / `金色日出光线` | 纪录片、户外 |
| 午后斜阳 | `warm golden sunlight spilling through blinds` | 室内情感 |
| 阴天散射 | `overcast soft diffused light` | 写实街景 |
| 月光 | `dim moonlight, cool blue tones` | 夜景 |
| 逆光 | `side backlighting outlines contours` | 人物轮廓 |

**错误做法：** 在纪录片场景中使用"霓虹灯""聚光灯""全息网格"等人工光源。

#### 技巧 4：纪录片风格锚定

将 prompt 锚定到真实的纪录片拍摄风格，是实现逼真感的最有效捷径之一：

```
自然手持纪录片摄影机，浅景深，电影慢动作。
旁白（BBC 风格平静语气）："在寂静的雪毯之下，生命悄然延续……"
```

**有效的纪录片锚定词：**
- `natural handheld documentary camera`
- `BBC-style narration`
- `National Geographic quality`
- `DSLR realism`
- `authentic [环境] sounds`

### 1.5 典型范例

#### 范例 A：超逼真野生动物纪录片

```
Ultra-realistic wildlife documentary footage.
A red fox moves cautiously along the edge of a snowy forest at dawn.
Its breath forms small clouds in the freezing air.
Beneath the snow, faint movements reveal a hidden vole tunneling just below the surface.
The fox tilts its head, listening carefully.
Suddenly it leaps high into the air and dives headfirst into the snow,
emerging seconds later with the vole in its jaws.
Natural handheld documentary camera, shallow depth of field, cinematic slow motion,
snow particles scattering through the air, dramatic golden sunrise lighting,
authentic winter forest sounds.

Narration (calm BBC-style voice): "Beneath the silent blanket of snow, life continues unseen…"
```

**拆解：**
- 锚定词：`Ultra-realistic wildlife documentary footage`
- 自然光：`dramatic golden sunrise lighting`
- 微细节：`breath forms small clouds`、`snow particles scattering`
- 摄影参数：`natural handheld documentary camera, shallow depth of field`
- 纪录片锚定：`BBC-style voice` 旁白

#### 范例 B：超写实情感短片

```
15 秒电影感日剧纯爱暧昧短片，超写实画质，
温暖的午后金色阳光透过百叶窗洒在并排的课桌上，
细微灰尘颗粒在光束中缓慢飘浮，旧木桌面，
极度自然的细微动作、呼吸、和眼神张力，
角色全程保持一致的面容、服装和发型，无变形无漂移无伪影，
真实的胸腔微微起伏与呼吸同步，
浅景深，奶油般模糊的背景，温暖的胶片颗粒，8K 锐利。

0-4s：极缓的中景推向特写，男孩写字的手悬停，铅笔微颤，
      睫毛在温暖午后光线下投下细微阴影。
4-9s：女孩感知到视线，耳边碎发被微风撩起 0.5 秒，
      喉结微微一滚（男孩），呼吸同步。
9-15s：极致特写双人面部，女孩缓缓转头，
      先是怔愣惊讶，然后害羞低头 0.3 秒，轻轻咬下唇，
      脸颊和耳垂泛起樱花粉，瞳孔微微放大。
```

**拆解：**
- 锚定词：`超写实画质`
- 微细节密集：`睫毛阴影`、`铅笔微颤`、`喉结滚动`、`耳垂泛红`、`瞳孔放大`
- 摄影参数：`浅景深, 8K, 胶片颗粒`
- 自然光：`温暖的午后金色阳光透过百叶窗`

### 1.6 常见错误

| 错误 | 正确做法 |
|------|---------|
| ❌ 堆砌大量画质标签但没有物理细节 | ✅ 减少标签，增加 3-5 个微观物理细节 |
| ❌ 写实场景使用霓虹灯/全息投影等人工光源 | ✅ 使用自然光源（日出、窗光、月光） |
| ❌ 只写"逼真"而不指定摄影参数 | ✅ 补充镜头焦距、景深、相机类型 |
| ❌ 微细节过多（10个以上），模型无法全部渲染 | ✅ 精选 3-5 个最有辨识度的细节 |
| ❌ 动作描写过于夸张（不符合物理规律） | ✅ 保持动作自然合理 |

### 1.7 画质标签组合

**推荐组合（选 4-6 个）：**
```
Ultra-realistic / Hyper-realistic / Photorealistic
+ 8K / 4K
+ 35mm lens / 85mm lens（根据场景选择）
+ shallow depth of field / cinematic bokeh
+ film grain / warm film grain
+ natural lighting / DSLR realism
```

---

## 二、CGI / VFX 特效级

### 2.1 核心定义

"CGI/VFX"追求的是**好莱坞视觉特效级别的视觉冲击**——能量爆炸、粒子风暴、体积光效、数字化碎裂。
核心不是"像真的"，而是"震撼到极致"。

### 2.2 什么时候用

- 能量对决/超能力战斗
- 变形/机甲/超级英雄
- 科幻场景（赛博朋克、太空、未来城市）
- 奇幻法术/魔法阵
- 电影预告片风格

### 2.3 核心写作公式

```
[比例/时长] + [角色与对手描述] + [动态镜头序列] + [能量特效描述] + [VFX/CGI 标签 + 体积光/粒子标签]
```

**五层结构：**

| 层次 | 内容 | 示例 |
|------|------|------|
| 第 1 层：格式参数 | 比例、时长、风格定调 | `16:9 ratio, epic multi-shot cinematic blockbuster, 12 seconds` |
| 第 2 层：主体描述 | 角色外观 + 对手/环境 | `黑色霓虹赛博忍者，双手持发光武士刀 vs 巨型半透明全息外星领主` |
| 第 3 层：动态镜头序列 | 每个镜头的动作 + 镜头运动 | `Dynamic shots: fast vertical tracking, 360° camera, bullet-time close-ups` |
| 第 4 层：能量特效 | 色彩 + 形态 + 运动 + 物理影响 | `neon vortex slash, glitches and explodes into digital shards and sparks` |
| 第 5 层：VFX 标签 | 体积光 + 粒子 + 好莱坞锚定 | `Epic Hollywood VFX, volumetric neon lighting, high-intensity trailer style` |

### 2.4 关键技巧

#### 技巧 1：用"好莱坞"作为品质锚定词

在 VFX 类 prompt 中，`Hollywood` 是最强的品质锚定词——它直接告诉 Seedance："我要的是最高级别的视觉特效"。

**有效锚定短语：**
- `Epic Hollywood VFX`
- `Hollywood-style visual effects and award-winning direction`
- `high-intensity trailer style`（预告片风格）
- `cinematic blockbuster`（大片风格）
- `high-end CGI energy effects`

#### 技巧 2：体积光（Volumetric Lighting）是 VFX 的标志

`Volumetric lighting`（体积光）是区分 VFX 级和普通画质的**最关键单一标签**。它让光线在空气中可见（如丁达尔光、光柱、雾中光束），极大提升画面层次感：

| 体积光变体 | 适用场景 |
|-----------|---------|
| `volumetric neon lighting` | 赛博朋克/科幻 |
| `volumetric magic lighting` | 奇幻/法术 |
| `volumetric god rays` | 日落/神话 |
| `volumetric fog` | 恐怖/悬疑/森林 |
| 丁达尔光（Tyndall effect） | 仙侠/神话/教堂 |

#### 技巧 3：能量特效的"四要素"描写法

每一个能量特效都应该从四个维度来描写，才能让 Seedance 精确渲染：

| 维度 | 示例 |
|------|------|
| **色彩** | 蓝色水龙、金色闪电、暗紫邪气、霓虹绿 |
| **形态** | 漩涡、光柱、冲击波、粒子火花、数字碎片 |
| **运动方式** | 螺旋上升、向外扩散、高速旋转、脉冲闪烁 |
| **物理影响** | 地面炸裂、碎石飞溅、空气扭曲、装甲碎裂 |

**错误做法：** `他释放了一道强大的能量攻击` ← 太抽象
**正确做法：** `他双掌推出一道炽蓝色能量光柱，光柱螺旋旋转向前推进，沿途地面炸裂翻起碎石，碎石在蓝色光芒中化为尘埃` ← 四要素齐全

#### 技巧 4：AIARTGALLARY 模板公式（最高效的 VFX prompt 模板）

这个模板来自社区中 VFX 类 prompt 产出最稳定的创作者，可以直接复用：

```
16:9 ratio, epic multi-shot cinematic blockbuster [时长]-second fight video.
[角色A描述] fights [角色B描述] in [环境描述].
Dynamic shots: [镜头1描述], [镜头2描述], [镜头3描述],
epic [高潮镜头描述] where [最终动作 + 特效高潮].
Epic Hollywood VFX, volumetric [类型] lighting,
dramatic camera moves, high-intensity trailer style.
```

### 2.5 典型范例

#### 范例 A：赛博忍者对战全息外星人

```
16:9 ratio, epic multi-shot cinematic blockbuster 12-second fight video.
A sleek black-neon cyber ninja with dual glowing katanas fights a giant translucent
holographic alien overlord with energy whips and teleport dashes
in a raining cyberpunk Tokyo street.
Dynamic shots: fast vertical tracking as she wall-runs up buildings,
circling 360° camera around whip clashes,
bullet-time close-ups of katana slices through holograms,
epic low-to-high sweeping shot climax where she unleashes a neon vortex slash
that glitches and explodes the overlord into digital shards and sparks.
Epic Hollywood VFX, volumetric neon lighting,
dramatic camera moves, high-intensity trailer style.
```

#### 范例 B：战士毁灭打击（结构化分段式）

```
Subject/Character: A massive 7-foot warrior in heavy battle-scarred dark armor,
wielding a giant glowing crimson two-handed greatsword.

Environment/Setting: An ancient battlefield littered with broken weapons and scorched earth.
Dark moody sky with dim lightning. Smoke and floating embers fill the air.

Action: The warrior charges forward with unstoppable momentum,
swings the greatsword in a devastating overhead arc,
slamming it into the ground — sending a catastrophic shockwave outward.

Shot Breakdown:
Shot 1 (0-5s): Wide establishing shot — warrior stands still.
Shot 2 (5-10s): Fast dynamic rotating tracking shot — warrior mid-charge.
Shot 3 (10-15s): Aggressive forward camera push — sword slams into ground, shockwave.

Lighting: Strong crimson energy lighting from the sword.
Dark cinematic dusk tones in the environment.

Style: cinematic, ultra high detail, intense pacing, fast motion,
dynamic composition, film-like motion, high-end CGI energy effects, atmospheric particles.
```

### 2.6 常见错误

| 错误 | 正确做法 |
|------|---------|
| ❌ 只写"有特效"但不描述特效的具体表现 | ✅ 用四要素法描写每个特效（色彩+形态+运动+影响） |
| ❌ 堆砌太多不同类型的特效 | ✅ 15 秒内聚焦 2-3 种核心特效 |
| ❌ 特效与角色动作脱节 | ✅ 特效是动作的延伸（挥剑→剑气→冲击波→碎石） |
| ❌ 忽略体积光标签 | ✅ 必须包含 `volumetric lighting` 的某个变体 |
| ❌ 没有"好莱坞/大片"品质锚定 | ✅ 至少包含一个品质锚定短语 |

### 2.7 画质标签组合

**推荐组合（选 4-6 个）：**
```
Epic Hollywood VFX / high-end CGI energy effects
+ volumetric [neon/magic/fog] lighting
+ atmospheric particles / energy trails
+ cinematic / ultra high detail
+ dramatic camera moves / dynamic composition
+ high-intensity trailer style / cinematic blockbuster
```

---

## 三、一镜到底（One-shot / Continuous Shot）

### 3.1 核心定义

"一镜到底"是指整段视频**无剪辑、无切换**，由一个连续不断的镜头完成所有画面。
核心不是"多个镜头"，而是"一条不间断的镜头运动路径"。

### 3.2 什么时候用

- 变形/机甲组装序列（变形过程不能被打断）
- 追逐场景（飞车、奔跑、飞行）
- 穿越式镜头（从室外穿过窗户到室内）
- 沉浸式 POV 视角（第一人称逃亡/探索）
- 灾难/末日场景（连续事件链）
- 炫技型运镜展示

### 3.3 核心写作公式

```
[一镜到底声明] + [相机类型/模式] + [连续动作流动描写（动词链驱动）] + [物理环境细节]
```

**四层结构：**

| 层次 | 内容 | 示例 |
|------|------|------|
| 第 1 层：声明 | 明确标注一镜到底 | `一镜到底，无剪辑。` / `Single shot, one take, no cuts.` |
| 第 2 层：相机模式 | FPV/手持/IMAX | `Camera Mode: FPV first-person perspective follow` |
| 第 3 层：动词链 | 用动态动词串联镜头轨迹 | `camera dives → locks on → slingshots ahead → whips back → blasts outward` |
| 第 4 层：环境交互 | 镜头穿越时的物理反馈 | `碎石飞溅、雾气穿透、气流震动` |

### 3.4 关键技巧

#### 技巧 1：必须明确声明"一镜到底"

这是最重要的一步——如果不明确声明，Seedance 默认会生成多镜头剪辑的视频。

**有效声明方式：**
- 中文：`一镜到底，无剪辑。`
- 英文：`Single shot, one take, no cuts.`
- 在标题中：`（单次连续镜头）`
- 在 FORMAT 中：`FORMAT: 15s / continuous shot`
- 在运镜段中：`【运镜】单镜头：一镜到底，无剪辑。`

**建议在 prompt 中出现至少 2 次声明**（开头 + 运镜段或结尾），确保模型理解。

#### 技巧 2：动词链驱动叙事

一镜到底类 prompt 的核心写法是**用连续的动态动词描写镜头运动轨迹**，而非分镜表格：

**动词链模式：**
```
镜头从 [起点] 俯冲而下 → 锁定 [主体] → 在 [路径] 上弹射前进 →
猛然回旋 → 紧贴 [细节] → 穿过 [障碍] → 最终向外炸开，
揭示 [终点场景]
```

**高频动态动词：**
| 中文 | 英文 | 效果 |
|------|------|------|
| 俯冲 | dives | 速度感、冲击 |
| 锁定 | locks on | 聚焦主体 |
| 弹射 / 甩出 | slingshots | 加速、动感 |
| 猛然回旋 | whips back | 节奏变化 |
| 紧贴 | drops tight to | 微距跟随 |
| 穿过 | darts through / passes through | 空间穿越 |
| 向外炸开 | blasts outward | 揭示、开阔 |
| 环绕 | orbits | 立体展示 |
| 无缝穿过 | seamlessly passes through | 玻璃/窗户穿越 |

#### 技巧 3：镜头运动轨迹要有"空间逻辑"

一镜到底的镜头必须在物理空间中有**合理的运动路径**——观众的心理模型需要能跟上：

**好的轨迹设计：**
```
极广角坠落 → 震颤推至半身特写 → 变身时环绕 → 拉远仰拍全身
```
每一步都有清晰的空间位移：下→近→绕→远

**差的轨迹设计：**
```
特写面部 → 俯瞰全城 → 微距手部 → 航拍山脉
```
空间跳跃太大，单个镜头无法在物理上完成这些转换

#### 技巧 4：穿越式镜头（Dheepan Ratnam 技法）

社区中最精彩的一镜到底 prompt 使用了**穿越式镜头**——镜头物理性地穿过一个介质（窗户、水面、布帘），实现内外场景的无缝转换：

**穿越式镜头模式：**
```
镜头无缝穿过一块玻璃/窗户/水面 → 进入一个完全不同的空间 →
在新空间中滑行 → 再次穿过另一个出口离开
```

**典型示例：**
```
镜头以与马匹疾驰相同的速度，无缝地穿过窗帘的缝隙，
进入马车内部——烛光摇曳的安静空间。
镜头飘过乘客的面孔，捕捉微妙表情，
然后无缝地从对面的窗户穿出，回到疾驰的外部世界。
```

#### 技巧 5：FPV 第一人称 + 呼吸感

一镜到底类 prompt 中，**FPV（第一人称视角）+ 手持呼吸感** 是最强的沉浸感组合：

```
【运镜】
单镜头：一镜到底，无剪辑。
摄影机模式：FPV 第一人称视角跟随。
呼吸感：手持拍摄，全程保持轻微的、如呼吸般的镜头浮动，增强临场感。
动态轨迹：高速俯冲跟随 → 轨道环绕 → 急推特写 → 低角度英雄仰拍
```

#### 技巧 6：时间轴与一镜到底的兼容写法

虽然一镜到底不用分镜，但可以使用时间轴来标注**同一长镜头内的阶段变化**：

```
【时间轴】（全程一镜到底，以下为同一长镜头内的时间段）
0-3s：高空坠落，衣物猛烈飘动，面部表情坚毅
3-6s：远处金属零件高速飞来汇聚，形成前臂护甲
6-9s：胸甲合拢、肩甲锁定、腿部装甲包裹，机械咔嗒声密集
9-12s：头盔闭合，HUD 点亮，完整机甲成形
12-15s：机甲调姿，喷射器启动，超级英雄着陆姿态
```

### 3.5 典型范例

#### 范例 A：飞车追逐穿越悬崖之城

```
Speeder chase across a cliff city (single continuous shot)

From a monumental cliffside city carved into stone,
the camera dives toward a tiny streak of light ripping along a narrow ledge-road.
Lock-on: a speeder hugging the wall at insane speed.
The camera slingshots ahead, whips back,
then drops tight to the rear thrusters: heat haze, grit snapping off the ledge,
warning lights flashing.
A collapsing balcony rains debris; the rider snaps a last-inch swerve
under a falling arch, then threads through hanging laundry lines
and open windows in one fluid line.
The camera darts through the same openings, staying glued to the motion.
One final bend and sudden calm:
the camera blasts outward into a reveal of the city opening onto
a boundless waterfall-fed valley, mist turning into rainbow.
```

**拆解：**
- 声明：标题中 `(single continuous shot)`
- 动词链：`dives → lock-on → slingshots → whips → drops → darts → blasts`
- 空间逻辑：从高处俯冲 → 跟随赛道 → 穿过建筑 → 炸出到开阔山谷
- 环境交互：`heat haze, grit snapping, collapsing balcony debris, mist into rainbow`

#### 范例 B：大天使变形（中文结构化一镜到底）

```
【核心主题】写实奇幻风格大天使变身，自由落体 + 圣光 + 翅膀实体化

【人物基础设定】深蓝色紧身飞行服的男性特工，面容冷峻

【氛围与画质】IMAX 胶片摄影机，Panavision C 系列镜头（35mm, f4）。
低饱和灰蓝主调，真实胶片颗粒感，边缘轻微柔焦。

【运镜】
单镜头：一镜到底，无剪辑。
动态轨迹：开场极广角坠落 → 震颤推至半身特写 → 变身时环绕 → 拉远仰拍全身。
呼吸感：手持拍摄，全程保持轻微的、如呼吸般的镜头浮动，增强临场感。

【时间轴】
0-3s：万米高空自由落体，衣物猛烈飘动，双眼紧闭
3-6s：发光羽毛从背部涌出，白金色翅膀骨架展开
6-9s：翅膀完全展开（翼展 5 米），逆光圣光炸裂
9-12s：白金机甲装甲从翅膀根部向躯干扩展，能量纹路流动
12-15s：变身完成，翅膀猛然拍击空气，悬停于云层之上

【声效】风切声、金属锁定声、翅膀拍击空气的沉重低频
```

### 3.6 常见错误

| 错误 | 正确做法 |
|------|---------|
| ❌ 没有明确声明"一镜到底/无剪辑" | ✅ 至少声明 2 次 |
| ❌ 使用"Shot 1 / Shot 2"分镜写法 | ✅ 用时间轴或动词链描写连续路径 |
| ❌ 镜头运动路径空间跳跃太大 | ✅ 确保每段位移在物理上可连续 |
| ❌ 全程匀速运动，缺乏节奏变化 | ✅ 加入加速/减速/突然平静的节奏转换 |
| ❌ 没有指定相机类型 | ✅ 指定 FPV / 手持 / IMAX 等 |
| ❌ 15 秒内穿越太多场景 | ✅ 聚焦 1-2 个空间，通过运动路径制造变化 |

### 3.7 画质标签组合

**推荐组合（选 4-6 个）：**
```
一镜到底 / Single shot, one take, no cuts
+ FPV / first-person perspective（可选）
+ IMAX film camera / Panavision（高端质感）
+ 8K / cinematic texture
+ 手持呼吸感抖动 / handheld breathing-like shake
+ film grain / low-saturation tone
```

---

## 四、高度详细多镜头电影级（Cinematic Multi-shot）

### 4.1 核心定义

"高度详细多镜头电影级"追求的是**专业电影分镜脚本级别的精确控制**——每个镜头都有明确的时间码、景别、运镜方式、动作和特效。
核心是"精确控制每一秒的画面"。

### 4.2 什么时候用

- 战斗/动作场景（需要多角度展示）
- 广告/商业片（每 2 秒一个视觉冲击）
- MV/音乐视频（镜头卡 beat）
- 体育运动（多角度展示同一动作）
- 任何需要"完整叙事弧线"的复杂场景

### 4.3 核心写作公式

三种模板可供选择：

#### 模板 A：FORMAT + Shot List（最规范）

```
Concept: [概念名称]
FORMAT: [时长] / [镜头数] SHOTS / [类型标签]
STYLE: [风格标签1], [风格标签2], ...

Shot 01 (0:00-0:02): [景别] - [动作描述] - [镜头运动] - [特效/光影]
Shot 02 (0:02-0:04): ...
Shot 03 (0:04-0:07): ...
...
Shot N (0:XX-0:YY): ...
```

#### 模板 B：中括号时间码分镜（中文偏好）

```
【风格】：[风格描述]
【时长】：[X] 秒
【场景】：[场景描述]

[00:00-00:05] 镜头 1：[镜头名称]
[场景/动作/运镜/特效 描述]

[00:05-00:10] 镜头 2：[镜头名称]
[场景/动作/运镜/特效 描述]

[00:10-00:15] 镜头 3：[镜头名称]
[场景/动作/运镜/特效 描述]
```

#### 模板 C：结构化分段式（最完整）

```
Subject/Character: [角色描述]
Environment/Setting: [环境描述]
Action: [核心动作概述]

Shot Breakdown:
Shot 1 (0-5s): [景别] — [描述]
Shot 2 (5-10s): [景别] — [描述]
Shot 3 (10-15s): [景别] — [描述]

Lighting: [光影方案]
Style: [风格标签]
Duration: [时长]
Audio Note: [声效/音乐]
```

### 4.4 关键技巧

#### 技巧 1：每个 Shot 的"三要素"

每个镜头内部都应该包含三个核心要素：

| 要素 | 描述 | 示例 |
|------|------|------|
| **场景/动作** | 这个镜头里发生什么 | `武士拔刀出鞘，蓝色水龙凭空出现` |
| **景别/运镜** | 镜头怎么拍 | `中景缓慢推近 → 特写面部` |
| **特效/光影** | 视觉效果怎么呈现 | `蓝色光芒照亮周围雾气，地面水纹荡漾` |

**错误做法：** `Shot 1: 武士站在森林里` ← 只有场景，没有运镜和特效
**正确做法：** `Shot 1: 中景，武士在月光迷雾森林中沉下重心，拔刀出鞘。镜头缓慢推近。蓝色水龙凭空出现围绕身体旋转，光芒照亮周围落叶。` ← 三要素齐全

#### 技巧 2：镜头数量与时长的匹配

| 视频时长 | 推荐镜头数 | 每个镜头平均时长 | 适用类型 |
|---------|-----------|----------------|---------|
| 10 秒 | 2-3 个 | 3-5 秒 | 情感、叙事 |
| 12 秒 | 3-4 个 | 3-4 秒 | 动作、广告 |
| 15 秒 | 3-6 个 | 2.5-5 秒 | 战斗、MV、体育 |

**关键原则：** 每个镜头不短于 2 秒（太短模型无法渲染），不长于 7 秒（太长缺少变化）。

#### 技巧 3：镜头间的景别对比

连续的镜头应该有**景别变化**，避免连续使用同一景别：

**好的景别节奏：**
```
Shot 1: 远景（建立场景）→ Shot 2: 中景（展开动作）→ Shot 3: 特写（高潮）
Shot 1: 特写（细节）→ Shot 2: 全景（揭示）→ Shot 3: 中景（结尾）
```

**差的景别节奏：**
```
Shot 1: 中景 → Shot 2: 中景 → Shot 3: 中景  ← 缺乏对比
```

**常见景别组合模板：**

| 模板名 | Shot 序列 | 适用场景 |
|--------|----------|---------|
| 经典三段 | 远景→中景→特写 | 通用 |
| 冲击式 | 特写→远景→特写 | 悬疑揭示 |
| 史诗式 | 俯瞰→全景→中景→特写 | 奇幻/战争 |
| 广告式 | 产品特写→爆炸远景→360°环绕→定格特写 | 商业 |
| 运动式 | 远景→主观视角→慢动作特写→定格 | 体育 |

#### 技巧 4：用真实导演/品牌/电影作为风格锚点

多镜头电影级 prompt 中，引用真实的**导演风格、摄影品牌、电影参考**能极大提升画面品质：

| 锚定类型 | 示例 | 效果 |
|---------|------|------|
| 导演风格 | 韦斯·安德森对称构图、大卫·芬奇暗调 | 整体美学方向 |
| 摄影品牌 | Vogue editorial, Valentino 大片 | 高端时尚质感 |
| 电影参考 | 好莱坞大片、IMAX 体验、获奖导演 | 制作级别锚定 |
| 格式参考 | 预告片风格、电影分镜脚本 | 剪辑节奏锚定 |

#### 技巧 5：光影方案的镜头间变化

优秀的多镜头 prompt 不仅每个 Shot 有不同的光影，还有**镜头间的光影递进**：

```
Shot 1: 冷青色月光（建立紧张氛围）
Shot 2: 能量爆发时暖橙色火光（冲突升级）
Shot 3: 蓝橙色光芒交织（高潮碰撞）
```

### 4.5 典型范例

#### 范例 A：霓虹饺子快递员（6 镜头 Shot List）

```
Concept: Neon Dumpling Courier
FORMAT: 15s / 6 SHOTS / action-comedy rooftop chase
STYLE: Rainy night market megacity, lantern reds, cyan neon, steam clouds,
wet tile roofs, practical comedy timing, ultra-detailed food steam and reflections

Shot 01 (0:00-0:02): High-angle establishing —
Courier bursts out of a steaming dumpling kitchen skylight onto wet rooftops,
bamboo steamer strapped to back, neon signs reflecting on rain-slicked tiles.

Shot 02 (0:02-0:04): Side-tracking dolly —
Sprint across a narrow roof bridge, dumplings bouncing in the steamer,
steam trails behind like a comet tail in cyan neon light.

Shot 03 (0:04-0:07): Low-angle under glass floor —
Leaps across a gap, camera catches boots through a transparent walkway,
lanterns swinging below, rain streaking the glass.

Shot 04 (0:07-0:10): Over-shoulder pursuit —
Rival courier on a neon skateboard gaining fast,
sparks off a metal track, reflection doubled in puddle.

Shot 05 (0:10-0:13): Crane shot rising —
Courier grabs a dangling lantern wire, swings over a night market crowd,
aerial view of steaming food stalls creating fog layer below.

Shot 06 (0:13-0:15): Frontal hero landing —
Sticks the landing on a glowing dumpling shop sign,
holds up steamer triumphantly, steam and neon flare around silhouette.
```

#### 范例 B：真人漫改呼吸法对决（3 镜头中文模板）

```
真人漫改 · 呼吸法对决（15 秒 · 超燃特效版）
【核心焦点】：水之呼吸（蓝色水龙） VS 雷之呼吸（金色闪电），真人极速决斗。
【风格】：好莱坞真人漫改电影质感，暗黑武士风，4K 超清，极致快剪，粒子光效炸裂。
【时长】：15 秒
【场景】：月光下的迷雾森林，泥泞地面，落叶。

[00:00-00:05] 镜头 1：水之旋律序章 · 起手势
年轻武士月光下沉下重心，缓慢拔刀出鞘，刀身流水般蓝光涌动。
蓝色水龙凭空出现，缠绕身体旋转上升，高压水流四溅。
镜头：中景缓慢环绕 → 推近面部特写。

[00:05-00:10] 镜头 2：雷之闪光 · 冲锋
金发剑士化作金色闪电残影，Z 字形高速突进，每一步炸裂地面。
金色电弧如蛇般沿着身体蜿蜒，焦灼落叶升起。
镜头：快速跟拍侧面 → 子弹时间特写。

[00:10-00:15] 镜头 3：水雷相撞 · 终音
双刀正面碰撞，蓝色水龙与金色闪电交汇炸裂，
形成能量风暴，冲击波向四面八方扩散，泥土和光芒填满画面。
画面在极致光芒中结束。
镜头：正面广角 → 冲击波特效全景。
```

### 4.6 常见错误

| 错误 | 正确做法 |
|------|---------|
| ❌ 镜头描述只有动作没有运镜 | ✅ 每个 Shot 必须标注景别和镜头运动 |
| ❌ 连续多个镜头用同一景别 | ✅ 镜头间要有景别对比（远→近→特写） |
| ❌ 6 个镜头但每个只分配 2 秒（内容塞不下） | ✅ 根据复杂度分配时长，关键镜头给更多时间 |
| ❌ 没有光影变化，所有镜头同一色调 | ✅ 设计镜头间的光影递进 |
| ❌ 只写了分镜但没有整体风格定调 | ✅ 开头必须有 STYLE / 风格段 |

### 4.7 画质标签组合

**推荐组合（选 4-8 个）：**
```
cinematic / cinematic blockbuster
+ 4K / 8K ultra-high definition
+ HDR / Dolby Vision（可选）
+ film grain / 胶片颗粒感
+ volumetric light / 丁达尔光效（可选）
+ dramatic lighting / cinematic lighting
+ [类型专属标签]（如 Hollywood VFX / realistic style / epic scale）
```

---

## 五、关键词组合与叠加策略

### 5.1 互斥关系

| 组合 | 是否兼容 | 说明 |
|------|---------|------|
| 一镜到底 + 多镜头 | ❌ **互斥** | 根本的结构差异，不能同时使用 |
| 逼真 + CGI/VFX | ⚠️ **需谨慎** | 可以结合（如"真实的人在 VFX 环境中"），但不能自相矛盾 |
| 逼真 + 一镜到底 | ✅ **兼容** | 手持纪录片 + 一镜到底 = 极致沉浸感 |
| 逼真 + 多镜头 | ✅ **兼容** | 纪录片多角度拍摄 |
| CGI + 一镜到底 | ✅ **兼容** | 机甲变形 + 一镜到底 = 最震撼的变形序列 |
| CGI + 多镜头 | ✅ **兼容** | 好莱坞大片标准组合 |

### 5.2 高效组合推荐

| 组合 | 适用场景 | 效果 |
|------|---------|------|
| **超写实 + 一镜到底** | 灾难POV、手持纪录片、真实事件模拟 | 极致沉浸感 |
| **CGI + 一镜到底** | 变形序列、机甲组装、超级英雄变身 | 最震撼的变形效果 |
| **CGI + 多镜头** | 动作战斗、奇幻对决、预告片 | 好莱坞级大片 |
| **超写实 + 多镜头** | 婚礼摄影、体育纪录片、时尚大片 | 高端质感 |
| **CGI + 超写实 + 多镜头** | 写实科幻战斗（如"高速格斗"） | 顶级制作（prompt 最复杂） |

### 5.3 叠加时的优先级

当多个关键词叠加时，按以下优先级分配 prompt 空间：

```
1. 结构选择（一镜到底 vs 多镜头）  ← 决定整体组织方式
2. 风格锚定（逼真 vs CGI）          ← 决定视觉方向
3. 画质标签                          ← 决定渲染品质
4. 细节描写                          ← 填充内容
```

---

## 六、画质标签层级体系

从 935 条 prompt 中总结出的四层画质标签体系：

### Level 1：基础级（任何 prompt 都应包含）
```
cinematic, 4K, film grain
```

### Level 2：进阶级（优质 prompt 的标准配置）
```
8K, ultra-realistic, shallow depth of field, volumetric lighting
```

### Level 3：专业级（模拟真实电影摄影）
```
IMAX film camera simulation
Panavision C-series lens
35mm / 85mm focal length, f/4 aperture
Dolby Vision HDR
anamorphic flare（变形宽银幕光晕）
65mm film texture
120fps high frame rate
cinematic wide color gamut
```

### Level 4：极致级（全栈堆叠，仅用于最复杂的场景）
```
8K UHD + Dolby Vision HDR + cinematic wide color gamut
+ IMAX film camera + Panavision lens
+ 120fps + film grain + shallow DOF
+ volumetric lighting + atmospheric particles
```

### 各关键词推荐的标签层级

| 关键词 | 推荐层级 | 说明 |
|--------|---------|------|
| 逼真/超写实 | Level 2-3 | 重点在摄影参数（镜头、景深、自然光） |
| CGI/VFX | Level 2 | 重点在 VFX 锚定词（Hollywood, volumetric） |
| 一镜到底 | Level 2-3 | 重点在相机类型（FPV, IMAX, 手持） |
| 多镜头电影级 | Level 2-4 | 根据复杂度选择，最高可用 Level 4 |

---

## 七、实战模板库

### 模板 1：逼真纪录片（连续叙事型）

```
Ultra-realistic [类型] documentary footage.
[主体] [动作] in [环境] at [时间/光线条件].
[微细节1]。[微细节2]。[微细节3]。
[关键动作描述]。
Natural handheld documentary camera, shallow depth of field,
cinematic slow motion, [环境音效描述].

Narration ([旁白风格]): "[旁白文本]"
```

### 模板 2：CGI 战斗大片（AIARTGALLARY 模板）

```
16:9 ratio, epic multi-shot cinematic blockbuster [时长]-second fight video.
[角色A外观描述] fights [角色B外观描述]
in [环境描述].
Dynamic shots: [镜头1运动方式 + 动作],
[镜头2运动方式 + 动作],
[镜头3运动方式 + 动作],
epic [高潮镜头] where [终极动作 + 特效描述].
Epic Hollywood VFX, volumetric [类型] lighting,
dramatic camera moves, high-intensity trailer style.
```

### 模板 3：一镜到底变形序列（标签分段式）

```
【核心主题】[变形类型]，[变形方式]
【人物基础设定】[外貌/服装描述]
【场景环境】[地点], [天气/氛围]
【氛围与画质】IMAX 胶片质感，[镜头型号]（[焦段], [光圈]）。
  [色调描述]，真实胶片颗粒感。
【运镜】
  单镜头：一镜到底，无剪辑。
  摄影机模式：FPV 第一人称视角跟随。
  动态轨迹：[起始运镜] → [中段运镜] → [高潮运镜] → [结尾运镜]
【时间轴】
  0-3s：[阶段1描述]
  3-6s：[阶段2描述]
  6-9s：[阶段3描述]
  9-12s：[阶段4描述]
  12-15s：[阶段5描述]
【声效】[声效描述]
```

### 模板 4：多镜头电影级（FORMAT + Shot List）

```
Concept: [概念名称]
FORMAT: [时长] / [N] SHOTS / [类型] / no dialogue
STYLE: [风格标签1], [风格标签2], [风格标签3], [风格标签4]

Shot 01 (0:00-0:XX): [景别] — [场景+动作+运镜+特效]
Shot 02 (0:XX-0:XX): [景别] — [场景+动作+运镜+特效]
Shot 03 (0:XX-0:XX): [景别] — [场景+动作+运镜+特效]
...
Shot N (0:XX-0:YY): [景别] — [场景+动作+运镜+特效]
```

### 模板 5：超写实情感短片（中文分时段）

```
[时长] 秒电影感 [风格类型] 短片，超写实画质，
[光线描述]，[环境细节]，
极度自然的细微动作、呼吸、和眼神张力，
角色全程保持一致的面容、服装和发型，
浅景深，[色彩描述]，胶片颗粒，8K 锐利。

0-[X]s：[景别]，[动作描述]，[微表情细节]。
[X]-[Y]s：[景别变化]，[情绪发展]，[物理微细节]。
[Y]-[Z]s：[高潮/结尾]，[情感定格]，[环境呼应]。

音效/氛围：[环境音] + [情绪音乐] + [具体声效]。
```

---

## 附录：快速查找表

### 关键词 → 推荐结构

| 关键词 | 推荐结构 | 理由 |
|--------|---------|------|
| 逼真/超写实 | 连续叙事段落 | 自然流畅，像真实拍摄手记 |
| CGI/VFX | 多镜头 Shot List 或连续叙事 | 需要精确控制每个特效 |
| 一镜到底 | 动词链连续叙事 或 标签分段+时间轴 | 不能分镜，只能描述连续路径 |
| 多镜头电影级 | FORMAT + Shot List 或 时间码分镜 | 需要精确控制每个镜头 |

### 关键词 → 核心差异化技巧

| 关键词 | 最核心的 1 个技巧 |
|--------|-----------------|
| 逼真/超写实 | **微观物理细节**（3-5 个可感知的真实世界细节） |
| CGI/VFX | **体积光标签**（`volumetric lighting` 是 VFX 感的开关） |
| 一镜到底 | **动词链驱动**（用连续动态动词描写镜头轨迹） |
| 多镜头电影级 | **每个 Shot 三要素**（动作+运镜+特效/光影） |

### 关键词 → 绝对不能少的标签

| 关键词 | 必备标签 |
|--------|---------|
| 逼真/超写实 | `ultra-realistic` + `shallow depth of field` + `[镜头参数]` |
| CGI/VFX | `Epic Hollywood VFX` + `volumetric lighting` |
| 一镜到底 | `single shot, one take, no cuts` + `[相机类型]` |
| 多镜头电影级 | `cinematic` + `[分辨率]` + `film grain` |

---

## 六、负向提示词 & 通用禁止标签

> 从 935 条优质 prompt 中提取的完整负向标签体系。负向提示词用于**排除不需要的画面元素、限制内容边界、保障技术质量**，是 prompt 的"防护栏"。

### 6.1 核心原则

1. **正向描述优先**：Seedance 2.0 更擅长理解"要什么"而非"不要什么"。能用正向描述的尽量用正向。
2. **否定句需谨慎**：`不要移动` → 改为 `保持静止`；`不要模糊` → 改为 `sharp focus, crisp details`。
3. **负向标签是补充而非主体**：负向标签放在 prompt 末尾作为"安全网"，不要把 prompt 写成一堆否定。
4. **关键排除需要强调**：真正重要的排除（如 2D 动画中排除 3D）需要**首尾各声明一次**，形成"三明治"结构。

### 6.2 通用禁止标签（每条 prompt 建议追加）

#### 🔒 基础安全三件套（必加）

**中文版（推荐用于中文叙事 prompt 末尾）：**
```
禁止生成字幕、LOGO、水印。画面稳定流畅，无闪烁无重影。
```

**英文版（推荐用于英文 prompt 末尾）：**
```
No subtitles, no watermarks, no text overlays. Stable, flicker-free footage.
```

> ⚠️ 这是出现频率最高的通用标签组合，几乎所有高质量 prompt 都以此收尾。

#### 📋 完整通用禁止标签模板

**中文完整版：**
```
画面稳定流畅，无闪烁无重影，人物结构正常，动作自然不僵硬，4K 高清细节清晰。
禁止生成字幕、LOGO、水印。
```

**英文完整版：**
```
Stable, smooth footage. No flickering, no ghosting. Normal human body proportions.
Natural, non-rigid movements. 4K sharp details. No subtitles, no watermarks, no text overlays.
```

### 6.3 分类负向标签清单

#### A. 画质 / 技术类（Quality / Technical）

| 负向标签（英文） | 负向标签（中文） | 作用 | 推荐场景 |
|---|---|---|---|
| `no watermark` | `无水印` | 排除水印 | **所有类型** |
| `no subtitles` | `无字幕` / `禁止字幕` | 排除字幕 | **所有类型** |
| `no text` / `no text overlays` | `无文字` / `无文字叠加` | 排除画面文字 | **所有类型** |
| `no LOGO` | `无LOGO` | 排除品牌标识 | **所有类型** |
| `non-flickering` / `flicker-free` | `无闪烁` / `不闪烁` | 防止画面闪烁 | 特效类、高动态类 |
| `non-stuttering footage` | `运镜流畅无卡顿` | 防止画面卡顿 | 运动类、一镜到底 |
| `highlights not overexposed` | `高光不过曝` | 防止高光溢出 | 逼真类、强光场景 |
| `no ghosting` | `无重影` | 消除运动残影 | 快速运动、特效类 |
| `stable footage` | `画面稳定` | 防止画面抖动 | **所有类型** |

#### B. 人物 / 角色类（Character）

| 负向标签（英文） | 负向标签（中文） | 作用 | 推荐场景 |
|---|---|---|---|
| `normal human body proportions` | `人物结构正常` / `正常人体比例` | 防止人体变形 | **所有含人物的类型** |
| `natural, non-rigid movements` | `动作自然不僵硬` | 防止动作僵硬 | **所有含人物的类型** |
| `without deformation, drift, or artifacts` | `无变形、无漂移、无伪影` | 角色一致性保护 | 多镜头、长视频 |
| `stable, non-distorting character faces` | `稳定不变形的角色面部` | 面部稳定性 | 特写镜头、CGI |
| `without exaggeration or robotic feel` | `不夸张、不机械` | 口型/表情自然性 | 有台词的场景 |
| `do not imitate any real person` | `不模仿任何真实人物` | 知识产权保护 | 写实/半写实风格 |

#### C. 内容安全类（Content Safety）

| 负向标签（英文） | 负向标签（中文） | 作用 | 推荐场景 |
|---|---|---|---|
| `no gore` | `无血腥` | 排除血腥内容 | 打斗/武侠/动作类 |
| `no blood` | `无血液` | 排除血液画面 | 打斗/武侠/动作类 |
| `no graphic violence` | `无血腥暴力` | 排除暴力画面 | 打斗/武侠/动作类 |
| `no injury detail` | `无受伤细节` | 排除伤痕展示 | 格斗/武术类 |
| `no negative guidance` | `无负面引导` | 内容价值观安全 | 所有涉及冲突的类型 |
| `no dangerous actions` | `无危险动作` | 排除高危行为展示 | 动作类、极限运动 |
| `Prohibited: firearms, fighting, chasing, crime` | `禁止：枪支、打斗、追逐、犯罪元素` | 内容合规 | 喜剧类、生活类 |

#### D. 运动 / 节奏类（Motion / Pacing）

| 负向标签（英文） | 负向标签（中文） | 作用 | 推荐场景 |
|---|---|---|---|
| `no dialogue` / `no spoken dialogue` | `无对白` / `全程无对白` | 纯视觉叙事 | 沉浸式、运动类、MV |
| `no cuts` | `无剪辑` | 一镜到底 | 一镜到底类（必加） |
| `no breaks` | `无间断` | 连续拍摄 | 一镜到底、长镜头 |
| `no slow motion` | `无慢动作` | 保持全速 | 硬核格斗、速度感 |
| `no pauses between moves` | `招式之间无停顿` | 动作连贯 | 武术/格斗/舞蹈 |
| `no fancy moves` | `没有花哨招式` | 动作写实 | 写实格斗、拳击 |
| `no redundant shots` | `无冗余镜头` | 精准剪辑 | 快节奏多镜头 |
| `no discontinuity` | `零卡顿、不连贯` | 动作衔接顺畅 | 复杂运动序列 |
| `do not include background music` | `不包含背景音乐` | 纯音效/环境音 | 写实风、ASMR 向 |

#### E. 风格 / 渲染类（Style / Rendering）

| 负向标签（英文） | 负向标签（中文） | 作用 | 推荐场景 |
|---|---|---|---|
| `absolutely no 3D. Ever.` | `绝无3D成分，永远如此` | 严禁 3D 渲染 | 2D 手绘动画（必加） |
| `not sterile or graphics-like` | `非无菌化、非图形化` | 避免数码/CG 感 | 逼真类、纪录片风 |
| `non-digital focus aesthetic` | `非数字化焦点美学` | 避免数码味 | 胶片风、年代感 |
| `Prohibit magical transitions` | `禁止魔幻过渡` | 限制过渡方式 | 延时摄影、纪实类 |
| `no explosions` | `无爆炸` | 排除爆炸效果 | 非战斗类变身/变形 |
| `non-English text on screen is forbidden` | `禁止画面中出现非英文文字` | 语言控制 | 面向英语市场 |

### 6.4 按关键词类型的推荐负向标签组合

#### 🎯 逼真 / 超写实类

```
without deformation, drift, or artifacts,
without exaggeration or robotic feel,
highlights not overexposed,
not sterile or graphics-like,
stable smooth footage,
no subtitles, no watermarks, no text overlays.
```

**核心逻辑**：保护真实感 → 排除数码/CG 味 + 排除人体变形 + 保护光影自然

#### 🎯 CGI / VFX 特效类

```
stable, non-distorting character faces,
smooth and non-distorted movements,
stable and non-flickering picture,
smooth and non-stuttering footage,
normal human body proportions,
no gore, no blood, no injury detail,
no subtitles, no watermarks, no LOGO.
```

**核心逻辑**：保护特效质量 → 面部稳定 + 动作流畅 + 画面不闪烁 + 内容安全

#### 🎯 一镜到底类

```
no cuts, single continuous shot,
no breaks, no discontinuity,
no dialogue,
no slow motion,
no redundant shots,
highlights not overexposed,
stable smooth footage,
no subtitles, no watermarks.
```

**核心逻辑**：保护连续性 → 无剪辑声明 + 无中断 + 动作连贯 + 画面稳定

#### 🎯 多镜头电影级类

```
no dialogue throughout,
no pauses between moves,
without deformation, drift, or artifacts,
normal human body proportions,
natural non-rigid movements,
no gore, no graphic violence,
Prohibited: any text, subtitles, LOGO, watermark.
```

**核心逻辑**：保护叙事纯粹 → 无对白 + 角色一致 + 动作连贯 + 内容安全 + 画面干净

#### 🎯 2D 手绘动画类

```
Pure hand-drawn 2D cartoon animation only — absolutely no 3D. Ever.
（首尾各强调一次，形成三明治结构）
Pure 2D. Hand-drawn. No 3D. Ever.
```

**核心逻辑**：极度聚焦风格排除，用**重复强调**代替标签堆砌

#### 🎯 延时摄影 / 纪实类

```
Prohibit magical transitions,
Absolutely prohibit collapse, explosion, sudden disappearance,
stable footage, smooth temporal progression,
no watermark, no subtitles, no text overlay.
```

**核心逻辑**：保护物理真实 → 禁止魔幻变化 + 禁止突变 + 时间流畅

### 6.5 负向标签使用技巧

#### 技巧 1：放置位置决定效力

| 位置 | 频率 | 效果 | 适用场景 |
|---|---|---|---|
| **Prompt 最末尾** | ~60%（最常见） | 作为"安全网"统一收尾 | 画质标签、文字/水印排除 |
| **Prompt 开头/FORMAT 行** | ~20% | 作为格式预设约束 | `no dialogue`、`no cuts` |
| **嵌入具体段落中** | ~15% | 针对特定动作/场景精确约束 | `no pauses`、`no blood` |
| **独立 Constraints 段** | ~5% | 系统性质量控制 | 技术质量标签集合 |

**最佳实践**：
```
[开头] FORMAT: 15s / no dialogue / single continuous shot
[中间] ...动作描写... no pauses between strikes, no fancy moves...
[末尾] Stable, flicker-free footage. No subtitles, no watermarks, no text overlays.
```

#### 技巧 2：三明治强调法（用于关键排除）

当某个排除**极其重要**时，在 prompt 首尾各声明一次：

```
[开头] Pure hand-drawn 2D cartoon animation only — absolutely no 3D. Ever.
[中间] ...大段内容描述...
[末尾] Pure 2D. Hand-drawn. No 3D. Ever.
```

> 适用场景：2D 排除 3D、一镜到底排除剪辑、写实排除 CG 感

#### 技巧 3：否定+肯定对照法

将负向和正向描述配对使用，效果更强：

| 否定（排除） | 肯定（替代） | 组合写法 |
|---|---|---|
| `no slow motion` | `full-speed action` | `full-speed action, no slow motion` |
| `no fancy moves` | `raw, brutal fighting` | `raw brutal fighting, no fancy moves` |
| `no 3D` | `pure hand-drawn 2D` | `pure hand-drawn 2D only — no 3D` |
| `no dialogue` | `purely visual storytelling` | `purely visual storytelling, no dialogue` |
| `no cuts` | `single continuous shot` | `single continuous shot, no cuts, no breaks` |

#### 技巧 4：中英文力度差异

| 语言 | 常用表达 | 力度排序（弱→强） |
|---|---|---|
| **英文** | `no ...` / `without ...` / `non-...` / `Prohibited:` / `forbidden` / `absolutely no ... Ever.` | `without` < `no` < `Prohibited` < `absolutely no ... Ever.` |
| **中文** | `无...` / `不包含...` / `禁止...` / `绝对禁止...` / `严格避免...` | `无` < `不包含` < `禁止` < `绝对禁止` |

**建议**：普通排除用 `no` / `无`；重要排除用 `Prohibited` / `禁止`；关键排除用 `absolutely no ... Ever.` / `绝对禁止`。

### 6.6 负向标签频次 Top 10（从 935 条 prompt 统计）

| 排名 | 负向标签 | 出现次数 | 类别 |
|---|---|---|---|
| 1 | `no dialogue` / `无对白` / `全程无对白` | 8 | 运动/节奏 |
| 2 | `Prohibited: subtitles, LOGO, watermark` / `禁止：字幕、LOGO、水印` | 6 | 画质/技术 |
| 3 | `no cuts` / `无剪辑` | 6 | 运动/节奏 |
| 4 | `no text, watermarks, or subtitles` / `无文字、水印或字幕` | 4 | 画质/技术 |
| 5 | `no gore` / `无血腥` | 4 | 内容安全 |
| 6 | `absolutely no 3D` / `绝无3D` | 4 | 风格/渲染 |
| 7 | `no blood` / `无血液` | 3 | 内容安全 |
| 8 | `no graphic violence` / `无血腥暴力` | 3 | 内容安全 |
| 9 | `non-flickering` / `无闪烁` | 2 | 画质/技术 |
| 10 | `no slow motion` / `无慢动作` | 2 | 运动/节奏 |

### 6.7 常见错误 & 避坑指南

| ❌ 错误写法 | ✅ 正确写法 | 原因 |
|---|---|---|
| `Don't show any people walking` | `Empty street, no pedestrians` | 否定句改正向描述 + 简洁标签 |
| `不要模糊` | `sharp focus, crisp details` | 用正向画质标签替代否定 |
| `no bad quality` | `cinematic quality, 4K, sharp details` | "bad quality"太模糊，用具体正向标签 |
| 整条 prompt 全是"不要..." | 70% 正向 + 30% 负向标签收尾 | 负向标签只是补充，不是主体 |
| `no blood no gore no violence no weapons` | `no gore, no graphic violence` | 避免过度堆砌，合并同类项 |
| 负向标签散落在 prompt 各处 | 集中放在末尾（或首尾+末尾） | 统一位置便于模型理解和管理 |
| 只写一次"no 3D" | 首尾各一次"absolutely no 3D. Ever." | 关键排除需要重复强调 |

### 6.8 速查：场景 → 推荐负向标签套餐

| 场景类型 | 基础安全三件套 | 额外推荐标签 |
|---|---|---|
| 日常 / 生活 | ✅ 必加 | `normal proportions` + `natural movements` |
| 动作 / 打斗 | ✅ 必加 | `no gore, no blood` + `no discontinuity` + `smooth footage` |
| 武侠 / 仙侠 | ✅ 必加 | `no gore` + `no pauses` + `stable faces` |
| 科幻 / 特效 | ✅ 必加 | `non-flickering` + `non-stuttering` + `stable faces` |
| 一镜到底 | ✅ 必加 | `no cuts, no breaks` + `no slow motion` + `no dialogue` |
| 多镜头快剪 | ✅ 必加 | `no dialogue` + `no redundant shots` + `stable proportions` |
| 2D 手绘 | ✅ 必加 | `absolutely no 3D. Ever.`（首尾各一次） |
| 延时摄影 | ✅ 必加 | `no magical transitions` + `no collapse/explosion` |
| 广告 / 产品 | ✅ 必加 | `stable` + `no flicker` + `highlights not overexposed` |
| 恐怖 / 悬疑 | ✅ 必加 | `no gore` + `no graphic violence`（Seedance 有内容限制） |
| 纪录片风 | ✅ 必加 | `not sterile or graphics-like` + `natural movements` |
| 婚纱 / 情感 | ✅ 必加 | `without deformation` + `natural expressions` + `no robotic feel` |
