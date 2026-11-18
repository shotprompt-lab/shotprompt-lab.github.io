# AI 镜头关键词与视频参考

更新日期：2026-11-17  
用途：文生视频、图生视频、AI 分镜设计及镜头提示词编写。

网页版本：[AI 镜头参考台](./index.html)

本库按实际设计镜头的顺序整理，覆盖景别、视角、运镜、运动质感、构图、光学、灯光、色彩、风格、表演、环境运动、连续性、声音与剪辑。它是一份通用视觉语言库，不代表所有生成模型都提供相同的控制能力。

## 网页播放检查

本地 HTML 中有 **119 / 190 条词目**配有页内来源。通过本地 HTTP 打开，计入已试播通过的 YouTube 来源后，有 **148 条词目**配有页内来源。网页中的实时播放状态以当前网络与浏览器为准。

对当前入库素材按媒体地址去重。**103 个直链成功解码首帧**，其中包括本次用于替换的 4 个 Pexels 片段。成功解码首帧表示媒体响应可读取，完整播放状态以网页点击后的结果为准。

| 入口 | 检查结果 | 推荐对照 |
|---|---|---|
| [《黑客帝国》MP4](https://ohiostate.pressbooks.pub/app/uploads/sites/252/2021/03/Matrix_tilt.mp4) | HTTP 403 | 可用同条下的 Runway 俯仰动图对照 |
| [《大白鲨》MP4](https://ohiostate.pressbooks.pub/app/uploads/sites/252/2021/03/jaws_dollyzoom.mp4) | HTTP 403 | [滑动变焦几何示意](https://commons.wikimedia.org/wiki/File:Contra-zoom_aka_dolly_zoom_animation.gif) |
| [StudioBinder 视频](https://www.youtube.com/watch?v=uSslqR3DuK8) | YouTube 嵌入信息 HTTP 404 | 可用对应条目里的光学教程或实拍例 |

网页顶部的「加载检查」可切换查看失败、仅原站／有条件、直链已检查和本页已加载。Pexels 使用发布方提供的公开 MP4，素材可在原发布页追溯。

## YouTube 点播

网页内选择「加载检查 → 逐条试播 YouTube」可重跑检查。播放条件随访问者的网络和浏览器而异。

**2026-11-18 · Edge 本地 HTTP 实测**。33 条原本需通过 HTTP 新增播放能力的词目共用一组 YouTube 来源。这组入库链接按 URL 去重后共检查 **24 个**。播放器时间前进至少 0.65 秒才记为通过。**22 个播通，2 个返回 150**。错误说明见 [YouTube 播放器 API](https://developers.google.com/youtube/iframe_api_reference#onError)。

两条嵌入失败的原链接仍可在发布站查看。受影响的 4 个词目已改用公开素材作为默认来源，其中 **4 个已通过 Edge 点播**。

| 词目 | 默认替代素材 | 试播状态 |
|---|---|---|
| 中远景／膝上景 | [林荫路行走 · 中远景过渡](https://www.pexels.com/video/a-woman-walking-towards-the-camera-5823532/) | Edge 已播通 |
| 近景／中近景 | [出镜讲解 · 中近景](https://www.pexels.com/video/woman-talking-in-front-of-camera-8048249/) | Edge 已播通 |
| 头顶空间 | [会议交谈 · 紧头顶空间](https://www.pexels.com/video/a-medium-close-up-of-a-woman-talking-at-a-meeting-8519380/) | Edge 已播通 |
| 主镜头 | [多人围桌 · 主镜头构图参考](https://www.pexels.com/video/people-sitting-at-table-talking-together-5899980/) | Edge 已播通 |

### 去重后的 YouTube 试播记录

| 视频入口 | 对应词目 | Edge 结果 |
|---|---|---|
| [AyML8xuKfoc](https://www.youtube.com/watch?v=AyML8xuKfoc) | 中远景／膝上景、近景／中近景、头顶空间、主镜头 | 错误 150 |
| [wLfZL9PZI9k](https://www.youtube.com/watch?v=wLfZL9PZI9k) | 平视、荷兰角／倾斜构图 | 播通 |
| [87e4DN-86NE](https://www.youtube.com/watch?v=87e4DN-86NE) | 摄影机滚转 | 播通 |
| [uDqjIdI4bF4](https://www.youtube.com/watch?v=uDqjIdI4bF4) | 平缓起停、次级运动、重量与惯性 | 播通 |
| [ynk4vJa-VaQ](https://www.youtube.com/watch?v=ynk4vJa-VaQ) | 慢动作 | 播通 |
| [hUmZldt0DTg](https://www.youtube.com/watch?v=hUmZldt0DTg) | 三分法构图 | 播通 |
| [qQNiqzuXjoM](https://www.youtube.com/watch?v=qQNiqzuXjoM) | 视线空间、双人镜头 | 播通 |
| [uKLaRLAdRw4](https://www.youtube.com/watch?v=uKLaRLAdRw4) | 持续跟焦 | 播通 |
| [n1EKLvdUSac](https://www.youtube.com/watch?v=n1EKLvdUSac) | 主光、补光、轮廓光 | 播通 |
| [WXo77dlisVM](https://www.youtube.com/watch?v=WXo77dlisVM) | 底光 | 播通 |
| [r2nD_knsNrc](https://www.youtube.com/watch?v=r2nD_knsNrc) | 柔光、硬光 | 播通 |
| [FYJeBMwOtz0](https://www.youtube.com/watch?v=FYJeBMwOtz0) | 画内实景灯光、有来源依据的布光 | 播通 |
| [zuwnNSgb3p8](https://www.youtube.com/watch?v=zuwnNSgb3p8) | 负补光 | 播通 |
| [z40GSfq5Scc](https://www.youtube.com/watch?v=z40GSfq5Scc) | 黑白影像、复古影像、黑色电影风格 | 播通 |
| [bK6ldnjE3Y0](https://www.youtube.com/watch?v=bK6ldnjE3Y0) | 黑白影像 | 播通 |
| [LP8IeuG7reY](https://www.youtube.com/watch?v=LP8IeuG7reY) | 柔和高光过渡 | 播通 |
| [kA244xewjcI](https://www.youtube.com/watch?v=kA244xewjcI) | 电影写实、35 毫米胶片质感 | 播通 |
| [_cMxraX_5RE](https://www.youtube.com/watch?v=_cMxraX_5RE) | 风格化三维动画 | 播通 |
| [9AGaECt9j4g](https://www.youtube.com/watch?v=9AGaECt9j4g) | 走位与起停 | 播通 |
| [FVR8zz8ci2k](https://www.youtube.com/watch?v=FVR8zz8ci2k) | 主镜头 | 错误 150 |
| [U_tqB4IZvMk](https://www.youtube.com/watch?v=U_tqB4IZvMk) | 拟音 | 播通 |
| [TO0cke22rgM](https://www.youtube.com/watch?v=TO0cke22rgM) | 动作匹配剪辑 | 播通 |
| [488th30k738](https://www.youtube.com/watch?v=488th30k738) | 叠化、淡入／淡出 | 播通 |
| [fT5rRPMnka0](https://www.youtube.com/watch?v=fT5rRPMnka0) | J 型剪辑、L 型剪辑 | 播通 |

## 使用说明

- **按项目保存关键词池。** 点击网页版右上角的池名，选择「新建项目池」并命名，也可用下拉菜单切换已有项目池。词目卡片上的「加入池」勾选属于当前项目池。项目池分别保存在当前浏览器，原有勾选可在「默认关键词池」中找到。
- **单独导出当前项目池。** 在池窗口点击「导出 Markdown」或「导出 Excel」。Markdown 用分类标题和分隔线分组。Excel 的「词目」和「视频来源」两张表都连续排列同类词目，并用底色与上边框标出每组开头。Excel 中的参考链接可点击。
- **视频参考。** 观察列标出要看的动作或视觉效果。参考分为独立片段、教程章节和相近参考。需联网访问媒体，源站播放条件以打开时为准。

- **中英文列是关键词对照。** 表格中的提示词示例均为自拟，可直接作为镜头描述使用，也可以替换主体、地点及动作后组合使用。
- **文生视频先交代画面，再描述变化。** 写明主体、场景、动作、景别与主要运镜，随后补充光线和质感。
- **图生视频重点描述变化。** 参考图已经给出外观、构图与光线时，提示词优先说明主体动作、环境运动、摄影机运动及时间发展。[参考：Runway 图生视频提示指南](https://help.runwayml.com/hc/en-us/articles/48324313115155-Image-to-Video-Prompting-Guide)
- **关键词用于表达视觉意图。** 精确焦距、运动角度、秒数与人物一致性不能仅靠文字保证；平台提供对应设置、参考图、首尾帧或运动参考时，应结合这些控制使用。
- **景别名称存在地区和工作习惯差异。** 中英文不总是一一对应。对取景范围有要求时，直接补充“全身入画”“腰部以上”“胸部以上”“只见眼睛”等可见边界。
- **方向要有参照。** “画面左／右”指观众看到的左右；“人物左／右”指人物自身左右。摄影机横移方向以其起始朝向为参照；有歧义时补充运动起点、经过位置和结束画面。
- **先建立一个清楚的主要动作。** 初次生成可只用一种主要运镜，之后再逐项增加表演、环境与光线细节。复杂组合应写出先后关系。
- **负面词取决于模型。** 部分模型偏好正向描述，甚至不支持否定表达；不要把负面词清单当作所有平台通用的结尾。[参考：Runway 提示指南](https://help.runwayml.com/hc/en-us/articles/39789879462419-Gen-4-Video-Prompting-Guide)

## 01. 景别与取景范围

景别控制主体在画面中的大小。以下采用常见英文缩写，并以实际裁切范围说明中文含义。[参考：Adobe 镜头类型与角度](https://www.adobe.com/uk/creativecloud/video/production/cinematography/camera-shots-and-angles.html)

| 中文关键词 | English | 含义 | 可直接使用的提示词示例 | 视频入口与观察重点 |
|---|---|---|---|---|
| 极远景／大远景 | Extreme wide shot / Extreme long shot, EWS / ELS | 环境占绝大部分，人物很小，强调尺度。 | 极远景，一名旅人站在辽阔雪原中央，人物只占画面很小一部分，远处群山完整展开。 | 独立片段。[Runway 动图](https://help.runwayml.com/hc/article_attachments/47313504717843)。潜水艇在海底峡谷中所占的画幅比例 |
| 远景 | Wide shot / Long shot, WS / LS | 同时交代人物和较大范围的周围环境。 | 远景，一名女子穿过空旷车站，画面保留站台、轨道和远处建筑。 | 独立片段。[Runway 动图](https://help.runwayml.com/hc/article_attachments/47313504717203)。人物全身和周围地貌同时可见 |
| 全身景／全景 | Full shot, FS | 主体从头到脚完整入画。 | 人物全身入画，鞋子和头顶完整可见，一名舞者在空旷排练室里缓慢转身。 | 独立片段。[Runway 动图](https://help.runwayml.com/hc/article_attachments/47313504716179)。从头到脚入画，比较人物与环境的占比 |
| 中远景／膝上景 | Medium wide shot / Medium long shot, MWS / MLS | 常取人物膝部以上，兼顾肢体和环境。 | 膝部以上的中远景，一名男子站在门口整理外套，保留双手和门框。 | 章节／多例。[StudioBinder 视频](https://www.youtube.com/watch?v=AyML8xuKfoc)。定位 Medium Full Shot，观察膝上取景。默认替代：[林荫路行走 · 中远景过渡](https://www.pexels.com/video/a-woman-walking-towards-the-camera-5823532/) |
| 中景 | Medium shot, MS | 通常取腰部以上，适合对话及手部动作。 | 腰部以上中景，一名厨师低头揉面，双手在画面下方清晰可见。 | 独立片段。[Runway 动图](https://help.runwayml.com/hc/article_attachments/47313504715539)。观察腰以上动作的可见范围 |
| 近景／中近景 | Medium close-up, MCU | 通常取胸部以上，突出表情并保留少量姿态。 | 胸部以上近景，一名女子听到声音后缓慢抬眼，肩部和面部动作清楚可见。 | 章节／多例。[StudioBinder 视频](https://www.youtube.com/watch?v=AyML8xuKfoc)。定位 Medium Close-Up，观察胸部以上的取景。默认替代：[出镜讲解 · 中近景](https://www.pexels.com/video/woman-talking-in-front-of-camera-8048249/) |
| 特写 | Close-up, CU | 面部或单个物件占据主要画面。 | 面部特写，一位老人轻轻微笑，眼角纹理清晰，背景柔和虚化。 | 独立片段。[Runway 动图](https://help.runwayml.com/hc/article_attachments/47313515593875)。象脸占据大部分画面 |
| 大特写／极端特写 | Extreme close-up, ECU | 只呈现眼睛、嘴唇、指尖等局部细节。 | 眼睛大特写，画面只呈现双眼和少量鼻梁，瞳孔中映出窗户的亮光。 | 独立片段。[Runway 动图](https://help.runwayml.com/hc/article_attachments/47313504712979)、[Pexels 片段](https://www.pexels.com/video/an-extreme-close-up-of-a-woman-s-face-9756613/)。只取眼部与邻近区域 |

## 02. 机位高度、角度与人物视角

机位高度、朝向和角色视点可以分别组合。例如“低机位、侧面、全身景”同时描述三个不同维度。

| 中文关键词 | English | 含义 | 可直接使用的提示词示例 | 视频入口与观察重点 |
|---|---|---|---|---|
| 平视 | Eye-level shot | 摄影机位于接近主体眼睛的高度。 | 平视中景，摄影机与坐着的男子眼睛等高，男子平静地看向对面的人。 | 章节／多例。[StudioBinder 视频](https://www.youtube.com/watch?v=wLfZL9PZI9k)。定位 Eye Level，比较镜头与眼睛的高度 |
| 低角度仰拍 | Low-angle shot | 摄影机低于主体，向上拍摄。 | 低角度仰拍，一名登山者站在岩石上，身后是开阔天空。 | 独立片段。[Runway 动图](https://help.runwayml.com/hc/article_attachments/47313515601555)。从下方看人物，观察主体上方留出的背景 |
| 高角度俯拍 | High-angle shot | 摄影机从较高位置向下拍摄主体。 | 高角度俯拍，一名孩子独自站在宽阔庭院里，地面占据大部分背景。 | 独立片段。[Runway 动图](https://help.runwayml.com/hc/article_attachments/47313504721939)。从上方斜看人物阵形 |
| 垂直俯视／顶视 | Overhead shot / Top-down shot / Bird’s-eye view | 摄影机从主体正上方向下看。 | 垂直俯视一张木桌，双手从画面下方进入，缓慢展开一张旧地图。 | 独立片段。[Runway 动图](https://help.runwayml.com/hc/article_attachments/47313504725011)。垂直看下方主体，观察结构如何变成平面图案 |
| 贴地视角 | Ground-level shot | 摄影机接近地面，高度本身不决定是否仰拍。 | 摄影机贴近地面，平行拍摄雨后路面，一双皮鞋从画面左侧走向右侧。 | 相近参考。[FXI 动态例](https://www.fxi.studio/tutorials/prompt-recipes/low-tracking)。以贴地跟拍作机位高度参考。[FXI 低机位跟拍 MP4](https://assets.fxi.studio/generations/oss/camera-moves/low-tracking-v7.mp4) |
| 极低角度仰视 | Worm’s-eye view | 从极低位置向上看，突出高度与压迫感。 | 极低角度仰视，摄影机位于高楼之间，建筑边缘向天空中央汇聚。 | 独立片段。[Runway 动图](https://help.runwayml.com/hc/article_attachments/47313504725651)。从坑底向上看，墙壁向天空开口汇聚 |
| 航拍视角 | Aerial shot / Drone shot | 从空中观察场景，可俯视，也可斜向拍摄。 | 高空斜向航拍，一条公路沿海岸延伸，汽车在道路上缓慢前行。 | 独立片段。[Runway 动图](https://help.runwayml.com/hc/article_attachments/47313515599123)、[Pexels 片段](https://www.pexels.com/video/flying-a-drone-over-the-mountain-forest-5607842/)。先看高空俯瞰，再看实拍飞行中的位置变化 |
| 正面 | Frontal view / Front-facing shot | 面向主体正面拍摄。 | 正面近景，一名女子面对摄影机，视线停在镜头旁边，缓慢呼吸。 | 相近参考。[Pexels 片段](https://www.pexels.com/video/close-up-view-of-woman-s-face-5493842/)。观察近正面时面部在画幅中的位置 |
| 侧面 | Profile shot / Side view | 从人物侧面观察，突出轮廓。 | 人物侧面特写，鼻梁和下颌轮廓清晰，男子看向画面右侧。 | 独立片段。[Pexels 片段](https://www.pexels.com/video/side-view-of-a-woman-s-face-in-close-up-footage-4829037/)。观察鼻梁和下颌形成的侧面轮廓 |
| 四分之三侧面 | Three-quarter view | 介于正面与纯侧面之间，能看到面部正面和侧面。 | 四分之三侧面近景，女子略微背向窗户，转头看向画面左侧。 | 相近参考。[Pexels 片段](https://www.pexels.com/video/headshot-of-woman-looking-up-10050974/)。参考人物斜向镜头时面部的可见份量，角度随动作改变 |
| 背面 | Rear view / Shot from behind | 从主体背后拍摄。 | 背面全身景，一名旅人面向远山站立，衣摆在风中轻轻摆动。 | 独立片段。[Runway 动图](https://help.runwayml.com/hc/article_attachments/47313504734355)。从背后看人物走向走廊深处 |
| 过肩镜头 | Over-the-shoulder shot, OTS | 前景保留一人的肩部，拍摄其面对的人或事物。 | 越过前景男子的右肩，拍摄对面女子的近景，男子肩部柔和虚化。 | 独立片段。[Runway 动图](https://help.runwayml.com/hc/article_attachments/47313504727955)。肩部在前景，视线落在角色面前的景物 |
| 主观镜头 | Point-of-view shot, POV | 画面模拟角色看到的内容。 | 第一人称主观视角，人物沿走廊前进，一只手从画面下方伸出推开门。 | 独立片段。[Runway 动图](https://help.runwayml.com/hc/article_attachments/47313504732051)。角色的手从画面下方进入 |
| 荷兰角／倾斜构图 | Dutch angle / Canted angle | 摄影机绕光轴倾斜，画面地平线不水平。 | 倾斜构图，走廊的垂直线明显偏斜，人物站在远端，气氛紧张。 | 章节／多例。[StudioBinder 视频](https://www.youtube.com/watch?v=wLfZL9PZI9k)。定位 Dutch Angle，留意水平线和垂直线一起倾斜 |

“倾斜构图”是画面状态；“摄影机滚转”是让这一倾斜状态随时间变化的运动。[参考：Adobe 荷兰角说明](https://www.adobe.com/creativecloud/video/production/cinematography/camera-shots-and-angles/dutch-angle-shot.html)

## 03. 摄影机运动

运镜最好同时写清楚移动方式、方向、速度和结束画面。下面的例句使用摄影术语加可见变化描述。[参考：Google 视频提示指南的摄影机运动说明](https://cloud.google.com/vertex-ai/generative-ai/docs/video/video-gen-prompt-guide)

| 中文关键词 | English | 含义 | 可直接使用的提示词示例 | 视频入口与观察重点 |
|---|---|---|---|---|
| 固定机位 | Locked-off camera / Static shot | 摄影机位置和朝向保持不变。 | 摄影机固定不动，人物从画面左侧走到右侧，只有人物和窗帘在运动。 | 独立片段。[Runway 动图](https://help.runwayml.com/hc/article_attachments/47313515634835)。观察画面边界与建筑自身的运动 |
| 推近 | Dolly in / Push in | 摄影机实际向主体靠近。 | 摄影机沿正前方缓慢推近女子，从腰部以上中景推进到面部特写。 | 独立片段。[Runway 动图](https://help.runwayml.com/hc/article_attachments/47313515615379)、[Vanity Fair 实拍](https://www.vanityfair.com/video/watch/reverse-film-school-what-happens-when-a-movie-has-no-camera-operator)。看主体变大及前后层次变化，实拍段搜索 dollying in |
| 拉远 | Dolly out / Pull back | 摄影机实际远离主体，逐渐展示更多空间。 | 摄影机从人物背后缓慢拉远，逐渐显露整座空旷大厅。 | 独立片段。[Runway 动图](https://help.runwayml.com/hc/article_attachments/47313504750227)。从作画的手逐渐揭示工作室 |
| 水平摇摄 | Pan left / Pan right | 摄影机位置不变，向左或向右转动。 | 摄影机原地向右缓慢摇摄，从窗边的花瓶转向门口站立的男子。 | 独立片段。[Runway 动图](https://help.runwayml.com/hc/article_attachments/47313504738835)。从湖岸摇向小船，观察镜头朝向 |
| 上下俯仰 | Tilt up / Tilt down | 摄影机位置不变，向上或向下转动。 | 摄影机位置与高度保持不变，从人物鞋部缓慢向上摇摄，最后将面部置于画面中央。 | 独立片段。[Runway 动图](https://help.runwayml.com/hc/article_attachments/47313504744723)、[《黑客帝国》MP4](https://ohiostate.pressbooks.pub/app/uploads/sites/252/2021/03/Matrix_tilt.mp4)。对照向上摇与向下摇，观察视线扫过的范围 |
| 横向平移 | Truck left / Truck right | 摄影机整体向左或向右移动。 | 摄影机向右平移，透过依次掠过的前景柱子，显露远处静止的人物。 | 独立片段。[Runway 动图](https://help.runwayml.com/hc/article_attachments/47313515618323)、[B站中文视频](https://www.bilibili.com/video/BV1MDBQB9Exn/)。官方例同时侧跟，中文教程可对照摇与移。[FXI 横移 MP4](https://assets.fxi.studio/generations/oss/camera-moves/truck-right-v7.mp4) |
| 垂直升降 | Pedestal up / Pedestal down | 摄影机整体上下移动，可保持朝向不变。 | 摄影机从桌面高度垂直升高至人物眼睛高度，朝向始终保持水平。 | 独立片段。[Runway 动图](https://help.runwayml.com/hc/article_attachments/47313504754579)。高度随香水瓶上升，观察摄影机位置 |
| 侧向跟拍 | Side tracking shot | 摄影机在主体侧面随其移动。 | 摄影机与骑行者保持相同速度，从侧面平行跟拍，骑行者始终位于画面中央。 | 独立片段。[FXI 动态例](https://www.fxi.studio/tutorials/prompt-recipes/side-tracking)、[Runway 动图](https://help.runwayml.com/hc/article_attachments/47313515618323)。观察摄影机与主体平行移动时的相对位置。[FXI 侧向跟拍 MP4](https://assets.fxi.studio/generations/oss/camera-moves/side-tracking-v7.mp4) |
| 背后跟拍 | Follow shot / Tracking from behind | 摄影机从主体后方随其前进。 | 摄影机从男子背后平稳跟随，男子沿狭窄走廊前进，与摄影机距离保持稳定。 | 独立片段。[FXI 动态例](https://www.fxi.studio/tutorials/prompt-recipes/follow-ots)。观察肩背与前方行进路线在画面里的关系。[FXI 背后跟拍 MP4](https://assets.fxi.studio/generations/oss/camera-moves/follow-ots-v7.mp4) |
| 前方领拍 | Leading shot / Tracking backward | 摄影机位于主体前方，后退拍摄迎面移动的主体。 | 摄影机面向奔跑者平稳后退，持续拍摄其正面，保持腰部以上中景。 | 章节／多例。[FXI 示例索引](https://github.com/fueledximagination/fxi-camera-moves#all-43-camera-moves)、[Runway 动图](https://help.runwayml.com/hc/article_attachments/47313515630995)。在 FXI 找 Reverse tracking，Runway 示例可辅助看随步速移动。[FXI 前方领拍 MP4](https://assets.fxi.studio/generations/oss/camera-moves/reverse-tracking-v7.mp4) |
| 弧形移动／环绕 | Arc shot / Orbit shot | 摄影机围绕主体沿弧线移动。 | 摄影机围绕静止女子缓慢移动，从正面经过她的右侧，最后停在侧面近景。 | 独立片段。[Runway 动图](https://help.runwayml.com/hc/article_attachments/47313515624083)。静物保持居中，背景因观察方位改变而滑动 |
| 摇臂运动 | Crane shot / Jib shot | 摄影机升降或沿较大弧线移动，常用于空间揭示。 | 摄影机从人物身旁缓慢升高并越过其头顶，逐渐显露后方的巨大广场。 | 独立片段。[Runway 动图](https://help.runwayml.com/hc/article_attachments/47313504755859)、[FXI 动态例](https://www.fxi.studio/tutorials/prompt-recipes/crane-up)。对照自上而下及由低处升高两种揭示。[FXI 摇臂升高 MP4](https://assets.fxi.studio/generations/oss/camera-moves/crane-up-v7.mp4)、[FXI 摇臂下降 MP4](https://assets.fxi.studio/generations/oss/camera-moves/crane-down-v7.mp4) |
| 航拍推进 | Aerial push-in | 摄影机在空中向明确目标靠近。 | 航拍摄影机沿河流上空平稳靠近远处村庄，村庄在画面中逐渐变大，最后以村庄为主要取景。 | 章节／多例。[FXI 示例索引](https://github.com/fueledximagination/fxi-camera-moves#all-43-camera-moves)。在 Drone/Crane 找 Drone push in。[FXI 航拍推进 MP4](https://assets.fxi.studio/generations/oss/camera-moves/drone-push-in-v7.mp4) |
| 无人机飞越 | Drone flyover / Aerial flyover | 摄影机从空中经过并越过场景或主体。 | 无人机沿河流平稳向前飞行，越过树林上空，随后显露远处村庄。 | 独立片段。[Pexels 片段](https://www.pexels.com/video/flying-a-drone-over-the-mountain-forest-5607842/)。观察飞越林地时树冠从画面下方连续通过 |
| 穿行镜头 | Fly-through shot | 摄影机沿明确空间路径穿过开口或场景。 | 摄影机缓慢穿过敞开的窗户，进入室内，最后停在桌上的信封前。 | 独立片段。[Pexels 片段](https://www.pexels.com/video/drone-flying-through-a-small-window-in-an-abandoned-building-12992120/)。观察窗洞边框靠近后退出画面，室内空间随之出现 |
| 变焦放大／缩小 | Zoom in / Zoom out | 通过改变焦距收窄或扩大视角；摄影机是否移动另行指定。 | 摄影机位置固定，缓慢变焦放大墙上的钟表，最后让表盘占据整个画面。 | 章节／多例。[Vanity Fair 实拍](https://www.vanityfair.com/video/watch/reverse-film-school-what-happens-when-a-movie-has-no-camera-operator)、[FXI 动态例](https://www.fxi.studio/tutorials/prompt-recipes/slow-zoom-in)。在实拍文字稿搜 slow zoom，再比较 dollying in；辅助例为放大。[FXI 缓慢变焦放大 MP4](https://assets.fxi.studio/generations/oss/camera-moves/slow-zoom-in-v7.mp4)、[FXI 缓慢变焦缩小 MP4](https://assets.fxi.studio/generations/oss/camera-moves/slow-zoom-out-v7.mp4) |
| 急速变焦 | Crash zoom / Snap zoom | 突然快速变焦，强调某个细节。 | 镜头从人物中景突然快速变焦放大，结束在惊讶的双眼特写。 | 独立片段。[Runway 动图](https://help.runwayml.com/hc/article_attachments/47313515627795)。变色龙从较松画幅迅速进入脸部特写 |
| 甩镜／快速摇摄 | Whip pan | 摄影机快速水平转动，途中出现明显运动模糊。 | 摄影机从左侧男子快速向右甩动，短暂的运动模糊后停在门口的女子身上。 | 独立片段。[Runway 动图](https://help.runwayml.com/hc/article_attachments/47313504763155)。第一次构图到第二次构图之间的短暂模糊 |
| 滑动变焦／眩晕效果 | Dolly zoom / Vertigo effect | 摄影机推拉与反向变焦配合，主体大小近似不变，空间透视变化。 | 摄影机缓慢后退并同步变焦放大，人物面部大小近似不变，身后的走廊空间感明显变化。 | 独立片段。[《大白鲨》MP4](https://ohiostate.pressbooks.pub/app/uploads/sites/252/2021/03/jaws_dollyzoom.mp4)、[大学教材](https://ohiostate.pressbooks.pub/introfilm/chapter/cinematography-ii/)。留意警长的脸和后方海滩尺度的不同变化。页内示范：[滑动变焦几何示意 · Mike1024](https://upload.wikimedia.org/wikipedia/commons/c/c7/Contra-zoom_aka_dolly_zoom_animation.gif) |
| 摄影机滚转 | Camera roll / Roll rotation | 摄影机围绕镜头光轴旋转。 | 摄影机朝向人物保持不变，画面缓慢顺时针旋转，地平线逐渐倾斜。 | 章节／多例。[视频](https://www.youtube.com/watch?v=87e4DN-86NE)。定位 Roll，观察地平线绕画面中心转动 |

推近与变焦、摇摄与横移应分别使用。较复杂的运动可以写成“从哪里开始—经过哪里—最后看见什么”。[参考：Runway 运镜术语与示例](https://help.runwayml.com/hc/en-us/articles/47313504791059-Camera-Terms-Prompts-Examples)

## 04. 运动质感、速度与时间表现

这类词描述运动的感觉或时间呈现，可以与上一类运镜组合。

| 中文关键词 | English | 含义 | 可直接使用的提示词示例 | 视频入口与观察重点 |
|---|---|---|---|---|
| 平稳稳定器运动 | Smooth gimbal movement / Stabilized tracking | 平滑、稳定地移动，减少可见晃动。 | 摄影机以平稳的稳定器运动跟随人物穿过大厅，画面高度保持稳定。 | 独立片段。[Runway 动图](https://help.runwayml.com/hc/article_attachments/47313515632147)。比较位置持续移动时画面高度和方向的平滑程度 |
| 轻微手持 | Subtle handheld movement | 带少量自然晃动，形成现场观察感。 | 轻微自然的手持摄影，摄影机近距离跟随人物整理行李。 | 章节／多例。[Vanity Fair 实拍](https://www.vanityfair.com/video/watch/reverse-film-school-what-happens-when-a-movie-has-no-camera-operator)。定位同一句对白的 tripod 与 handheld 两个版本。[FXI 轻微手持 MP4](https://assets.fxi.studio/generations/oss/camera-moves/handheld-shot-v7.mp4) |
| 强烈手持晃动 | Shaky handheld camera | 较明显、不规则的晃动，表现混乱或急迫。 | 手持摄影机在拥挤人群中跟随奔跑者，步伐带来明显上下晃动。 | 独立片段。[Runway 动图](https://help.runwayml.com/hc/article_attachments/47313504764179)。观察不规则抖动和镜头不断重新抓住主体的过程 |
| 缓慢漂移 | Slow camera drift / Gentle drifting movement | 很轻、很慢的持续位移。 | 摄影机在静止人物身旁轻缓向左漂移，前景树叶与背景产生细微视差。 | 相近参考。[FXI 动态例](https://www.fxi.studio/tutorials/prompt-recipes/side-tracking)。参考小幅侧向位移，漂移幅度与节奏需按自身镜头收敛 |
| 匀速运动 | Constant-speed movement | 在镜头内保持相对稳定的移动速度。 | 摄影机以恒定速度沿长廊向前移动，门框依次从画面两侧掠过。 | 章节／多例。[FXI 示例索引](https://github.com/fueledximagination/fxi-camera-moves#all-43-camera-moves)。找 Truck left 或 Truck right，观察中段横移节奏 |
| 平缓起停 | Ease in / Ease out | 摄影机逐渐加速或减速，起停较柔和。 | 摄影机从静止开始缓慢加速推近，接近人物后逐渐减速，最后平稳停下。 | 章节／多例。[视频](https://www.youtube.com/watch?v=uDqjIdI4bF4)。找 Slow In and Slow Out，观察起步和停止前的间距 |
| 慢动作 | Slow motion | 让主体动作的时间表现变慢。 | 慢动作特写，舞者转身时头发和裙摆缓缓展开，细小动作清楚可见。 | 独立片段。[视频](https://www.youtube.com/watch?v=ynk4vJa-VaQ)。水滴变形被慢动作展开 |
| 延时摄影 | Time-lapse | 把较长时间内的变化压缩呈现。 | 固定机位延时摄影，云层快速掠过山峰，山谷中的阴影逐渐移动。 | 独立片段。[Pexels 片段](https://www.pexels.com/video/a-time-lapse-of-a-picturesque-golden-hour-4767572/)。比较云层和地面阴影在短时间内的变化 |
| 运动延时 | Hyperlapse | 在时间压缩的同时，摄影机明显改变位置。 | 运动延时镜头，摄影机沿街道持续向前推进，天空云层与街上人流快速变化。 | 独立片段。[Pexels 片段](https://www.pexels.com/video/hyperlapse-sunrise-on-cloudy-sky-industrial-and-forest-landscape-with-drone-16152745/)。除时间压缩外，观察无人机造成的视点变化 |
| 速度渐变 | Speed ramp / Speed ramping | 播放速度在实时、慢速或快速之间平滑过渡。 | 奔跑画面开始为正常速度，跃起瞬间逐渐进入慢动作，落地后逐渐恢复实时速度。 | 章节／多例。[Adobe 变速教学](https://helpx.adobe.com/ph_fil/premiere-pro/how-to/slow-down-video.html)。比较同一段动作速度变化前后的节奏 |
| 时间重映射 | Time remapping | 重新安排原始素材各时刻在成片中的对应时间，可实现加速、减速、定格或倒放，常用于后期。 | 后期对同一段奔跑素材进行时间重映射：先正常播放，跃起时定格片刻，随后继续向前播放。 | 章节／多例。[Adobe 变速教学](https://helpx.adobe.com/ph_fil/premiere-pro/how-to/slow-down-video.html)。观察关键帧附近播放速度和源画面的对应变化 |

“摄影机缓慢移动”和“人物慢动作”是不同控制。延时与速度渐变也可在后期制作；模型对精确变速时点的执行可能需要迭代。

## 05. 构图与空间层次

构图词建议与主体所在位置、视线方向一起写。

| 中文关键词 | English | 含义 | 可直接使用的提示词示例 | 视频入口与观察重点 |
|---|---|---|---|---|
| 居中构图 | Centered composition | 主体位于画面中心。 | 人物居中站在走廊尽头，头部与身体保持在画面中央。 | 独立片段。[Runway 动图](https://help.runwayml.com/hc/article_attachments/47313515598611)。人物与体育馆中心轴的关系 |
| 对称构图 | Symmetrical composition | 画面两侧的结构形成对称关系。 | 正面对称构图，人物站在中央楼梯上，两侧扶手和门窗对称展开。 | 独立片段。[Runway 动图](https://help.runwayml.com/hc/article_attachments/47313504735251)。看两侧楼梯与扶手的镜像关系 |
| 三分法构图 | Rule of thirds | 主体放在画面三分线附近。 | 人物位于画面右侧三分线附近，左侧保留远山与天空。 | 章节／多例。[StudioBinder 视频](https://www.youtube.com/watch?v=hUmZldt0DTg)。定位 Rule of Thirds，留意主体在三分线附近 |
| 负空间／留白 | Negative space | 主体周围保留较大面积的简洁空间。 | 人物位于画面下方偏左，大片空白墙面占据右侧，构图安静疏离。 | 独立片段。[Runway 动图](https://help.runwayml.com/hc/article_attachments/47313504736403)。大面积空白衬托微小车辆 |
| 引导线 | Leading lines | 用道路、墙面、轨道等线条引向主体。 | 铁轨从画面下方延伸至远处人物，形成清晰的视觉引导线。 | 独立片段。[Runway 动图](https://help.runwayml.com/hc/article_attachments/47313504733075)。道路的线条将视线引向动作 |
| 框中框 | Frame within a frame | 使用门窗等在画面内部框住主体。 | 透过敞开的门框拍摄室内人物，门框完整包围远处的女子。 | 独立片段。[Runway 动图](https://help.runwayml.com/hc/article_attachments/47313504734355)。走廊结构在画面内部形成第二层边框 |
| 前景遮挡 | Foreground occlusion / Foreground framing | 用近处物体部分遮挡画面，形成观察感和层次。 | 透过虚化的树叶拍摄人物，树叶只遮挡画面边缘，人物面部保持可见。 | 相近参考。[Runway 动图](https://help.runwayml.com/hc/article_attachments/47313504727955)。肩膀占据画面边缘，作为前景局部遮挡参考 |
| 前中后景分层 | Foreground–midground–background layering | 在不同距离安排元素，建立纵深。 | 前景是花枝，中景是窗边人物，后景是远处山脉，三个空间层次清晰。 | 独立片段。[Runway 动图](https://help.runwayml.com/hc/article_attachments/47313504771731)。在古董店内挑出近、中、远三个距离层次 |
| 视线空间 | Look room / Nose room | 在人物看向的一侧保留空间。 | 人物位于画面左侧并看向右方，右侧保留充足视线空间。 | 章节／多例。[StudioBinder 视频](https://www.youtube.com/watch?v=qQNiqzuXjoM)、[StudioBinder 示例页](https://www.studiobinder.com/blog/what-is-an-eyeline-match/)。观察人物视线一侧留下的画幅，以及与下一镜头的对应 |
| 头顶空间 | Headroom | 控制头顶与画面上边缘的距离。 | 胸部以上近景，人物头顶保留少量空间，头部位置在整个镜头中稳定。 | 相近参考。[StudioBinder 视频](https://www.youtube.com/watch?v=AyML8xuKfoc)。按景别章节比较人物头顶到画框的距离。默认替代：[会议交谈 · 紧头顶空间](https://www.pexels.com/video/a-medium-close-up-of-a-woman-talking-at-a-meeting-8519380/) |
| 紧凑构图 | Tight framing | 主体填满较多画面，减少周围空间。 | 紧凑的面部特写，额头接近画面上缘，脸部占据绝大部分画面。 | 独立片段。[Runway 动图](https://help.runwayml.com/hc/article_attachments/47313504712979)。看被裁掉的区域和留下的细节 |
| 画面内运动方向 | Screen direction | 明确主体在二维画面中的移动方向。 | 人物始终从画面左侧向右侧行走，沿途依次经过窗户与门口。 | 章节／多例。[StudioBinder 示例页](https://www.studiobinder.com/blog/what-is-continuity-editing-in-film/)。查 Screen Direction 或 180-Degree Rule，比较切镜前后运动方向 |

## 06. 镜头、焦点与光学效果

焦距、距离和画幅共同影响取景。透视关系主要由观察位置决定；“广角感”“长焦压缩感”用于提示外观时，最好补充近远物体的关系。[参考：Canon 焦距与视角](https://files.canon-europe.com/files/webcontent/rf-lens-world/knowledge/focus/index.html)、[Canon 透视说明](https://files.canon-europe.com/files/webcontent/rf-lens-world/knowledge/perspective/index.html)

| 中文关键词 | English | 含义 | 可直接使用的提示词示例 | 视频入口与观察重点 |
|---|---|---|---|---|
| 广角镜头感 | Wide-angle lens look | 较宽视角，近距离取景时近大远小的关系明显。 | 近距离广角取景，前景人物与远处建筑形成明显大小差异，街道向远处延伸。 | 章节／多例。[Vanity Fair 实拍](https://www.vanityfair.com/video/watch/reverse-film-school-what-happens-when-a-movie-has-no-camera-operator)、[StudioBinder 视频](https://www.youtube.com/watch?v=uSslqR3DuK8)。在实拍文字稿定位 wide lens，看近距离拍摄时前后人物间距 |
| 标准镜头感 | Normal lens look / Standard lens look | 采用较自然、适中的视角呈现主体。 | 标准镜头视角，人物面部比例自然，保留适量室内环境。 | 章节／多例。[StudioBinder 示例页](https://www.studiobinder.com/blog/focal-length-camera-lenses-explained/)。定位 Standard Lenses 及该页镜头教学视频，比较适中的视角 |
| 长焦镜头感 | Telephoto lens look | 常配合远距离窄视角取景，呈现空间压缩感。 | 从远处以长焦取景，人物身后远山显得靠近，层叠山脉在画面中紧密排列。 | 章节／多例。[Vanity Fair 实拍](https://www.vanityfair.com/video/watch/reverse-film-school-what-happens-when-a-movie-has-no-camera-operator)、[大学教材](https://ohiostate.pressbooks.pub/introfilm/chapter/cinematography-ii/)。在实拍文字稿定位 longer lens，课程教材另有《毕业生》长焦段落 |
| 微距 | Macro shot / Macro lens | 近距离表现细小主体及表面细节。 | 微距特写，一只蜜蜂停在花蕊上，细小绒毛和花粉颗粒清楚可见。 | 独立片段。[Runway 动图](https://help.runwayml.com/hc/article_attachments/47313515589907)、[Pexels 片段](https://www.pexels.com/video/droplets-of-water-sliding-from-a-leaf-5210311/)。观察翅膀／水滴纹理和合焦范围 |
| 浅景深 | Shallow depth of field | 清晰范围较窄，主体前后较易虚化。 | 浅景深人物特写，眼睛清晰，身后的街灯柔和虚化。 | 独立片段。[Runway 动图](https://help.runwayml.com/hc/article_attachments/47313504778259)。主体与背景的清晰度差异 |
| 深景深／全景深取向 | Deep depth of field / Deep focus | 较大前后范围保持可接受的清晰度。 | 深景深风景镜头，近处野花、中景木屋和远山都保持清晰。 | 独立片段。[Runway 动图](https://help.runwayml.com/hc/article_attachments/47313504771731)。近处陈设到远处窗户仍能分辨细节 |
| 焦点转移／拉焦 | Rack focus / Focus pull | 清晰焦点由一个距离位置转移到另一个位置。 | 摄影机固定，焦点从前景桌上的钥匙缓慢转移到后景门口的人物。 | 独立片段。[Runway 动图](https://help.runwayml.com/hc/article_attachments/47313515641107)、[Vanity Fair 实拍](https://www.vanityfair.com/video/watch/reverse-film-school-what-happens-when-a-movie-has-no-camera-operator)。对照厨师的手与远处食客，实拍文字稿定位 rack focus |
| 持续跟焦 | Focus tracking | 随主体距离变化持续调整焦点，保持指定主体清晰。 | 人物向摄影机缓慢走近，焦点持续跟随其双眼，面部始终清晰。 | 章节／多例。[视频](https://www.youtube.com/watch?v=uKLaRLAdRw4)。观察移动主体眼睛保持合焦，作为持续跟焦参考 |
| 前景虚化 | Out-of-focus foreground | 让靠近摄影机的物体虚化，突出后方主体。 | 前景花枝柔和虚化，后方窗边女子的面部保持清晰。 | 独立片段。[Runway 动图](https://help.runwayml.com/hc/article_attachments/47313504727955)。靠近镜头的肩部与远处环境的清晰度差 |
| 散景／虚化光斑 | Bokeh | 描述失焦区域的视觉质感，常见为柔和光斑。 | 夜间人像，人物清晰，远处灯光形成柔和圆形散景光斑。 | 相近参考。[Runway 动图](https://help.runwayml.com/hc/article_attachments/47313504778259)、[StudioBinder 示例页](https://www.studiobinder.com/blog/what-is-an-anamorphic-lens-definition/)。前者看虚化观感，后者看镜头散景对照 |
| 变形宽银幕镜头风格 | Anamorphic lens look | 模拟变形镜头的一些视觉特征，如椭圆散景与横向眩光。 | 变形宽银幕镜头风格，背景灯光呈椭圆散景，明亮灯源产生轻微横向蓝色眩光。 | 章节／多例。[StudioBinder 示例页](https://www.studiobinder.com/blog/what-is-an-anamorphic-lens-definition/)、[StudioBinder 视频](https://www.youtube.com/watch?v=uSslqR3DuK8)。定位 Anamorphic，观察椭圆散景与横向光带 |
| 镜头眩光 | Lens flare | 强光进入镜头后形成光斑、光带等。 | 夕阳位于人物身后，摄影机略微移动时出现轻柔镜头眩光。 | 章节／多例。[Veo 视频示例](https://deepmind.google/models/veo/prompt-guide/)。找越野拉力赛示范，留意镜头朝向亮处时的光斑。页内示范：[Veo 越野拉力 · 眩光参考](https://storage.googleapis.com/gdm-deepmind-com-prod-public/media/media/veo__veo-3__off-road.mp4) |
| 柔焦效果 | Soft-focus look | 让边缘与高光呈柔和扩散的外观。 | 柔焦人像，面部轮廓轻柔，高光略微扩散，眼神仍可辨认。 | 独立片段。[Runway 动图](https://help.runwayml.com/hc/article_attachments/47313515639955)。观察整体边缘和高光的柔化 |
| 鱼眼镜头风格 | Fisheye lens look | 极宽视角伴随明显曲线畸变。 | 鱼眼镜头风格，狭小房间被宽广呈现，画面边缘的直线弯曲。 | 章节／多例。[StudioBinder 示例页](https://www.studiobinder.com/blog/focal-length-camera-lenses-explained/)。定位 Fisheye，比较画面边缘线条弯曲 |

景深不是亮度，散景也不等于把整张图变模糊。应明确“谁清晰、谁虚化”。[参考：Canon 景深说明](https://files.canon-europe.com/files/webcontent/rf-lens-world/knowledge/depth-of-field/index.html)

术语区别：Follow-focus system 通常指跟焦器或调焦系统，可用于持续跟焦或拉焦；表达画面目标时，可写“人物靠近时双眼持续清晰”（Keep the subject’s eyes in focus as they approach）。

## 07. 灯光方向、软硬与造型

灯光描述可以按“光从哪里来—阴影多硬—暗部保留多少”组织。主光、补光和轮廓光描述的是各自作用。[参考：ARRI 灯光手册](https://www.arri.com/en/learn/lighting/lighting-handbook)

| 中文关键词 | English | 含义 | 可直接使用的提示词示例 | 视频入口与观察重点 |
|---|---|---|---|---|
| 主光 | Key light | 负责主体主要照明与造型的光。 | 柔和主光从人物左前方照来，面部右侧形成自然阴影。 | 章节／多例。[StudioBinder 视频](https://www.youtube.com/watch?v=n1EKLvdUSac)。先看只开主光时亮面与阴影的位置 |
| 补光 | Fill light | 调整主光造成的暗部亮度和反差。 | 人物右侧使用轻微补光，暗部保留细节，同时维持面部立体感。 | 章节／多例。[StudioBinder 视频](https://www.youtube.com/watch?v=n1EKLvdUSac)。观察加入补光后暗侧被抬亮的幅度 |
| 侧光 | Side lighting | 光源从主体侧面照来，强调形体。 | 侧光照亮人物半边脸，另一侧较暗，皮肤与衣物纹理清楚。 | 章节／多例。[StudioBinder 示例页](https://www.studiobinder.com/blog/basics-of-film-lighting-techniques/)。找 Direction，比较侧向与正向来光 |
| 逆光 | Backlighting | 光源来自主体后方，主体处于摄影机与光源之间。 | 夕阳从人物身后照来，前方补光很弱，头发边缘明亮。 | 独立片段。[Runway 动图](https://help.runwayml.com/hc/article_attachments/47313504715539)、[Pexels 片段](https://www.pexels.com/video/a-silhouette-of-a-person-standing-in-front-of-a-sunset-28554552/)。先看后方被照亮的空气，再看主体暗面 |
| 轮廓光 | Rim light / Edge light | 在主体边缘形成亮线，帮助分离背景。 | 深色背景前，一道柔和轮廓光勾勒人物肩膀和头发边缘。 | 章节／多例。[StudioBinder 视频](https://www.youtube.com/watch?v=n1EKLvdUSac)、[Runway 动图](https://help.runwayml.com/hc/article_attachments/47313504715539)。对照第三盏光与逆光例里肩部边缘的高光 |
| 顶光 | Top lighting | 光从主体上方照来。 | 单一顶光照亮桌边男子，眼窝与下颌下方形成较深阴影。 | 章节／多例。[StudioBinder 示例页](https://www.studiobinder.com/blog/basics-of-film-lighting-techniques/)。在 Direction 段比较光源位于人物上方时的阴影 |
| 底光 | Underlighting | 光从主体下方照来。 | 手电筒从面部下方照亮人物，鼻部阴影向上投射，气氛不安。 | 相近参考。[StudioBinder 示例页](https://www.studiobinder.com/blog/basics-of-film-lighting-techniques/)、[视频](https://www.youtube.com/watch?v=WXo77dlisVM)。在来光方向示范中找低位光源，优先观察鼻影方向 |
| 柔光 | Soft light | 阴影边界过渡柔和。 | 阴天柔光照亮人物，面部阴影边缘平缓，肤色自然。 | 章节／多例。[StudioBinder 视频](https://www.youtube.com/watch?v=r2nD_knsNrc)、[StudioBinder 示例页](https://www.studiobinder.com/blog/basics-of-film-lighting-techniques/)。找 Light Quality，观察阴影边缘过渡 |
| 硬光 | Hard light | 阴影边界清晰、过渡较窄；整体明暗反差还受补光和环境反射影响。 | 强烈硬光从侧上方照来，人物在墙上投下边界清晰的影子。 | 章节／多例。[StudioBinder 视频](https://www.youtube.com/watch?v=r2nD_knsNrc)、[StudioBinder 示例页](https://www.studiobinder.com/blog/basics-of-film-lighting-techniques/)。找 Hard Light，观察边界较清楚的投影 |
| 窗光 | Window light | 将窗户方向的光作为主要可见照明依据。 | 清晨窗光从画面左侧进入室内，照亮人物的侧脸与桌面。 | 独立片段。[Pexels 片段](https://www.pexels.com/video/a-woman-standing-by-the-window-7277929/)、[Pexels 片段](https://www.pexels.com/video/a-woman-looking-out-the-window-8991334/)。观察窗面到人物及周围室内的亮度变化 |
| 画内实景灯光 | Practical lighting | 画面中可见的台灯、路灯等参与照明。 | 桌上台灯是画面中的主要光源，暖光照亮人物双手和下半张脸。 | 独立片段。[视频](https://www.youtube.com/watch?v=FYJeBMwOtz0)。观察画内灯具，以及它和周围区域光线的关系 |
| 有来源依据的布光 | Motivated lighting | 布光方向和性质与场景中的光源相呼应。 | 人物面部光线与右侧壁炉方向一致，暖光随火焰轻微变化。 | 章节／多例。[视频](https://www.youtube.com/watch?v=FYJeBMwOtz0)。同一实拍教程比较画内光源和额外布光的方向 |
| 高调布光 | High-key lighting | 整体较明亮、暗部较浅，光比通常较低。 | 高调布光的明亮室内，人物面部阴影浅淡，白色背景保留细节。 | 章节／多例。[StudioBinder 示例页](https://www.studiobinder.com/blog/film-lighting/)。定位 High Key 部分及页内视频，观察较浅的阴影 |
| 低调布光 | Low-key lighting | 较大面积处于暗部，重点区域被选择性照亮。 | 低调布光，一束侧光照亮人物眼睛和脸颊，其余空间沉入深色阴影。 | 章节／多例。[StudioBinder 示例页](https://www.studiobinder.com/blog/film-lighting/)。定位 Low Key 部分及页内视频，观察较大的暗部面积 |
| 剪影 | Silhouette | 主体较暗，主要依靠外轮廓辨认。 | 日落逆光剪影，两个人站在山脊上，面部细节隐藏，轮廓清晰可辨。 | 独立片段。[Pexels 片段](https://www.pexels.com/video/a-silhouette-of-a-person-standing-in-front-of-a-sunset-28554552/)。辨认落日前的人物轮廓及被压暗的面部细节 |
| 体积光／可见光束 | Volumetric lighting / Light shafts | 光束在雾气或悬浮颗粒中变得可见。 | 薄雾弥漫的室内，阳光穿过高窗形成可见光束，光束中尘埃缓慢漂浮。 | 独立片段。[Pexels 片段](https://www.pexels.com/video/sunlight-shining-through-forest-trees-15365455/)、[Pexels 片段](https://www.pexels.com/video/view-of-dust-particles-in-sun-light-5561385/)。沿树间光路观察可见光束，在尘埃素材里看微粒 |
| 斑驳光影 | Dappled light | 光透过叶片等遮挡，在主体上形成不规则明暗。 | 树叶过滤阳光，在人物肩部和地面形成轻微移动的斑驳光影。 | 独立片段。[Pexels 片段](https://www.pexels.com/video/sun-dappled-leaves-swaying-in-summer-breeze-37469480/)。看阳光穿叶时亮斑随叶面方向改变 |
| 负补光 | Negative fill | 减少暗侧反射光，让阴影和轮廓更明确。 | 人物右侧暗部较深，左侧窗光柔和，面部保持明确的明暗分界。 | 章节／多例。[视频](https://www.youtube.com/watch?v=zuwnNSgb3p8)。观察减少反射补光后，暗侧如何变深 |

高调不等于过曝，低调不等于整体欠曝；柔光和硬光也不是灯光亮度的高低。

## 08. 时间、色彩与明暗风格

以下词用于控制画面的总体倾向；色温数字要结合白平衡理解，直接写可见颜色往往更明确。

| 中文关键词 | English | 含义 | 可直接使用的提示词示例 | 视频入口与观察重点 |
|---|---|---|---|---|
| 黄金时刻 | Golden hour | 日出后或日落前常见的低角度暖光氛围。 | 黄金时刻的海边，低角度暖阳照亮人物侧脸，地面投下细长影子。 | 独立片段。[Pexels 片段](https://www.pexels.com/video/a-time-lapse-of-a-picturesque-golden-hour-4767572/)。观察低太阳高度下的暖色高光 |
| 蓝调时刻 | Blue hour | 日出前或日落后常见的冷蓝环境光氛围。 | 蓝调时刻的城市街道，天空深蓝，橱窗暖光与冷色环境形成对比。 | 独立片段。[Pexels 片段](https://www.pexels.com/video/aerial-view-of-cityscape-during-twilight-40281337/)。观察天光偏蓝时与人工照明的对比 |
| 阴天漫射光 | Overcast daylight | 云层使日光更均匀、阴影较柔和。 | 阴天街景，天空提供均匀柔光，人物面部明暗过渡自然。 | 独立片段。[Pexels 片段](https://www.pexels.com/video/urban-street-scene-with-overcast-sky-35424962/)。观察阴天街景中柔和的明暗过渡 |
| 暖色调 | Warm color palette / Warm tones | 画面偏向琥珀、橙、黄等暖色。 | 室内采用温暖琥珀色调，木质家具与人物肤色自然协调。 | 章节／多例。[StudioBinder 示例页](https://www.studiobinder.com/blog/movie-color-palette-ridley-scott/)。选《火星救援》相关案例，观察橙暖色在画面中的占比 |
| 冷色调 | Cool color palette / Cool tones | 画面偏向蓝、青等冷色。 | 清晨室内以冷蓝灰色为主，窗外光线清冷，人物静坐在床边。 | 章节／多例。[StudioBinder 示例页](https://www.studiobinder.com/blog/movie-color-palette-david-fincher/)。选《龙纹身的女孩》相关案例，对照蓝灰色环境 |
| 低饱和 | Muted colors / Desaturated palette | 色彩较克制，鲜艳程度降低。 | 低饱和城市街景，灰蓝建筑与褪色衣物形成安静的整体色彩。 | 章节／多例。[StudioBinder 示例页](https://www.studiobinder.com/filmmaking-techniques-color-theory-in-film/)、[StudioBinder 示例页](https://www.studiobinder.com/blog/color-grading-vs-color-correction-process/)。定位 Saturation，比较偏灰、低纯度的色彩 |
| 高饱和 | Saturated colors / Vibrant palette | 色彩鲜明、浓烈。 | 高饱和夏日街景，红色遮阳伞、蓝色天空与黄色墙面鲜明可辨。 | 章节／多例。[StudioBinder 示例页](https://www.studiobinder.com/filmmaking-techniques-color-theory-in-film/)、[StudioBinder 示例页](https://www.studiobinder.com/blog/color-grading-vs-color-correction-process/)。对照 Saturation 里的高纯度色彩 |
| 高对比 | High contrast | 亮部与暗部差异明显。 | 高对比黑白人像，侧脸被明亮光线照亮，背景保持深黑。 | 章节／多例。[StudioBinder 示例页](https://www.studiobinder.com/blog/basics-of-film-lighting-techniques/)。看灯光对比段，比较亮面和深阴影落差 |
| 低对比 | Low contrast | 亮暗差异较温和。 | 低对比雾天风景，远山和天空柔和相接，阴影浅淡。 | 独立片段。[Runway 动图](https://help.runwayml.com/hc/article_attachments/47313515639955)。观察雾中灰阶较接近的视觉效果 |
| 冷暖对比 | Warm–cool contrast | 不同区域使用暖色与冷色形成关系。 | 人物被暖色台灯照亮，身后窗外是冷蓝夜色，冷暖分区清晰。 | 独立片段。[Pexels 片段](https://www.pexels.com/video/rainy-city-street-at-night-with-reflections-30169690/)。对照冷色环境与橙暖灯光在同一画面中如何并存 |
| 黑白影像 | Black-and-white / Grayscale | 以黑、白和灰阶呈现画面，用明暗、纹理和形状组织画面。 | 黑白影像，雨后石板路反射路灯，人物穿深色外套走过。 | 章节／多例。[《第三人》预告](https://www.youtube.com/watch?v=z40GSfq5Scc)、[《奥本海默》预告](https://www.youtube.com/watch?v=bK6ldnjE3Y0)。看《第三人》修复预告的黑白灰阶，另可对照《奥本海默》预告中的黑白段落 |
| 单色影像 | Monochrome | 以单一色相的深浅变化呈现画面，也可包括黑白灰阶影像。 | 棕褐色单色影像，旧车站与人物统一呈现为同一棕色的深浅层次，保留衣物和墙面纹理。 | 章节／多例。[StudioBinder 示例页](https://www.studiobinder.com/blog/movie-color-palette-david-fincher/)、[StudioBinder 示例页](https://www.studiobinder.com/filmmaking-techniques-color-theory-in-film/)。找 Monochromatic 案例，比较同色系亮度与深浅的层次 |
| 柔和高光过渡 | Soft highlight roll-off | 高亮区域向白色过渡较平缓。 | 人物站在明亮窗边，面部高光过渡柔和，白衬衫仍保留纹理。 | 独立片段。[视频](https://www.youtube.com/watch?v=LP8IeuG7reY)。看亮面接近纯白时各级明暗的过渡 |

## 09. 影像媒介与整体风格

风格词最好配合具体的光线、色彩和运动描述。单独写“电影感”会留下较大的解释空间。

| 中文关键词 | English | 含义 | 可直接使用的提示词示例 | 视频入口与观察重点 |
|---|---|---|---|---|
| 写实摄影 | Photorealistic / Live-action look | 接近实拍的人物、材质和空间表现。 | 写实摄影风格，自然皮肤纹理，真实衣物褶皱，人物在日常室内轻轻转头。 | 相近参考。[StudioBinder 示例页](https://www.studiobinder.com/blog/a24-cinematography/)、[Pexels 片段](https://www.pexels.com/video/a-woman-standing-by-the-window-7277929/)。实拍和风格目标参考，观察肤质、衣料、自然光和布景细节 |
| 电影写实 | Cinematic realism | 用构图、布光、色彩和运动组织写实画面。 | 电影写实风格，克制低饱和色彩，柔和侧光，缓慢推近窗边人物。 | 章节／多例。[《过往人生》预告](https://www.youtube.com/watch?v=kA244xewjcI)、[StudioBinder 示例页](https://www.studiobinder.com/blog/a24-cinematography/)。观察真实场景里克制的构图、色彩与人物表演 |
| 纪录片观察感 | Observational documentary style | 自然场景、非夸张表演及现场观察式摄影。 | 纪录片观察风格，轻微手持，工匠专注修理木椅，自然室内光。 | 独立片段。[NFB 短片](https://www.nfb.ca/film/lonely_boy/)。观察 NFB 纪录短片《Lonely Boy》里的现场人物与自然反应 |
| 35 毫米胶片质感 | 35mm film look | 模拟胶片颗粒、色彩和高光外观。 | 35 毫米胶片质感，细腻颗粒，柔和高光，略低饱和的城市黄昏。 | 独立片段。[《过往人生》预告](https://www.youtube.com/watch?v=kA244xewjcI)、[柯达拍摄说明](https://www.kodak.com/en/motion/blog-post/past-lives/)。先看 A24《过往人生》预告的运动影像，再用柯达资料核对 35mm 胶片 |
| 复古影像 | Vintage film look / Retro look | 使用特定年代的服装、场景和影像特征。 | 复古影像，褪色暖调、轻微胶片颗粒，人物坐在旧式火车车厢里。 | 章节／多例。[《第三人》预告](https://www.youtube.com/watch?v=z40GSfq5Scc)。以修复版《第三人》观察旧年代实拍、光影和颗粒；预告受修复与编码影响 |
| 黑色电影风格 | Film noir style | 常见低调布光、强阴影与悬疑都市氛围。 | 黑色电影风格，黑白高对比，百叶窗阴影落在侦探脸上。 | 独立片段。[《第三人》预告](https://www.youtube.com/watch?v=z40GSfq5Scc)。《第三人》预告可看强对比照明、斜线和都市夜景 |
| 超现实 | Surreal / Dreamlike | 以非日常的空间和事件形成梦境感。 | 超现实梦境，人物走在浅水覆盖的室内，天花板倒映远处云层，动作缓慢。 | 章节／多例。[Veo 视频示例](https://deepmind.google/models/veo/prompt-guide/)、[Runway 动图](https://help.runwayml.com/hc/article_attachments/47313515639955)。找结晶花和暮色场景，观察现实逻辑被有意改变的方式。页内示范：[Veo 月尘梦境](https://storage.googleapis.com/gdm-deepmind-com-prod-public/media/media/veo__veo-3__moon-dust.webm) |
| 二维动画 | 2D animation | 以二维平面图形表现运动，可采用逐帧绘制、矢量补间或其他二维动画方式。 | 二维动画风格，平面角色与背景，人物在风中抬头，动作连贯。 | 独立片段。[NFB 短片](https://www.nfb.ca/film/here_and_there/)、[NFB 作者专题](https://blog.nfb.ca/blog/2026/05/19/a-cat-a-strange-visitor-a-cow-a-frog-and-a-little-girl-the-world-of-cordell-barker/)。从 NFB 短片观察平面造型与逐帧动作 |
| 二维手绘动画 | Hand-drawn 2D animation | 呈现逐帧绘制的二维线条与色块外观。 | 二维手绘动画风格，清晰轮廓线，柔和色块，人物在风中抬头。 | 章节／多例。[NFB 作者专题](https://blog.nfb.ca/blog/2026/05/19/a-cat-a-strange-visitor-a-cow-a-frog-and-a-little-girl-the-world-of-cordell-barker/)、[Runway 动图](https://help.runwayml.com/hc/article_attachments/47313504733075)。在 NFB 作者专题中选《The Cat Came Back》的播放器，另有 AI 手绘外观例 |
| 定格动画 | Stop-motion animation | 呈现逐帧摆拍般的动作和材质感。 | 黏土定格动画风格，小人逐帧迈步，手工表面纹理清楚可见。 | 独立片段。[NFB 定格短片](https://www.nfb.ca/film/unlaced/)。观看 NFB《Unlaced》，注意纸材质和逐格动作。页内示范：[Veo 定格动画风格](https://storage.googleapis.com/gdm-deepmind-com-prod-public/media/media/veo__veo-3__camper.webm) |
| 三维动画 | 3D animation | 以三维角色与场景的动画外观呈现，可采用写实或风格化表现。 | 三维动画，小机器人在工作台上转身挥手，体积、遮挡和空间关系清晰。 | 独立片段。[Blender 短片](https://studio.blender.org/projects/charge/?asset=6211)。观看 Blender Studio《Charge》，看三维场景、角色和空间用光 |
| 风格化三维动画 | Stylized 3D animation | 对三维造型、比例、材质或运动进行风格化处理。 | 风格化三维动画，简洁造型，柔和材质，小机器人在工作台上转身挥手。 | 独立片段。[Blender 短片](https://studio.blender.org/blog/sprite-fright-premiere/)。观看 Blender Studio《Sprite Fright》，看造型夸张与统一色彩 |

“35mm film look”通常是在描述胶片外观；“35mm lens”是在描述镜头焦距，两者含义不同。

## 10. 人物动作、表演与交互

用可见动作表达情绪，并注明动作由谁执行。多人物场景可以使用“左侧女子”“戴帽男子”等稳定标识。

| 中文关键词 | English | 含义 | 可直接使用的提示词示例 | 视频入口与观察重点 |
|---|---|---|---|---|
| 细微表情变化 | Subtle facial expression change | 用小幅面部变化表现情绪。 | 女子先保持平静，随后嘴角轻轻抬起，眼神逐渐放松，动作幅度克制。 | 相近参考。[Pexels 片段](https://www.pexels.com/video/close-up-footage-of-a-woman-smiling-at-camera-8170683/)、[Pexels 片段](https://www.pexels.com/video/close-up-shot-of-a-woman-with-expressive-face-4128381/)。观察嘴角、眼睛和面部的细小变化，情绪幅度依片段而异 |
| 视线转移 | Gaze shift / Eye movement | 明确眼睛先看哪里、再看哪里。 | 人物先低头看信封，再缓慢抬眼看向画面右侧门口。 | 独立片段。[Pexels 片段](https://www.pexels.com/video/headshot-of-woman-looking-up-10050974/)。观察眼睛与头部先后抬起的时机 |
| 转头回望 | Head turn / Look back | 明确头部转动及结束方向。 | 人物身体保持朝前，听到声音后缓慢把头转向左肩后方，最后停住。 | 独立片段。[Pexels 片段](https://www.pexels.com/video/businesswoman-turning-and-looking-back-10040758/)。对照肩部与头部转动先后 |
| 自然呼吸 | Subtle breathing | 胸肩和身体出现轻微连续运动。 | 人物静坐，胸肩随呼吸轻微起伏，眼睛自然眨动。 | 相近参考。[Pexels 片段](https://www.pexels.com/video/close-up-footage-of-a-woman-deep-breathing-8995333/)。观察呼吸带动的肩颈和胸廓，实拍动作较明显 |
| 走位与起停 | Blocking / Walk and stop | 规定人物空间路线、速度和停止位置。 | 女子从门口走向窗边，在窗前停下，身体转向窗外。 | 章节／多例。[StudioBinder 视频](https://www.youtube.com/watch?v=9AGaECt9j4g)、[Pexels 片段](https://www.pexels.com/video/a-woman-entering-a-doorway-5379126/)。看走位示范，再看片段中人物穿过门框时与空间的关系 |
| 明确手部交互 | Hand–object interaction | 说明手与物体的接触及动作顺序。 | 男子伸出右手，握住桌上杯子的把手，平稳提起杯子并停在胸前。 | 独立片段。[Pexels 片段](https://www.pexels.com/video/hand-grabbing-cup-13675326/)。观察手指接触杯子、抓握与抬离桌面的动作 |
| 多人顺序动作 | Sequential character actions | 用先后关系区分各个人物动作。 | 左侧女子先点头，随后右侧男子把信封推向她，两人保持原有座位。 | 章节／多例。[Runway 示例页](https://help.runwayml.com/hc/en-us/articles/41748090660499-Creating-Multi-Character-Dialogues-with-Act-Two)、[StudioBinder 示例页](https://www.studiobinder.com/blog/blocking-and-staging-scenes/)。定位双人车内对白或场面调度案例，观察两个动作如何依次接上 |
| 入画与出画 | Enter frame / Exit frame | 指定主体从画面哪侧进入或离开。 | 人物从画面右侧进入，在中央停留片刻，随后从左侧离开。 | 相近参考。[Pexels 片段](https://www.pexels.com/video/a-woman-entering-a-doorway-5379126/)、[Runway 动图](https://help.runwayml.com/hc/article_attachments/47313515598611)。用进门素材和体育馆入画素材看角色如何越过画面边界，出画用反向思路设计 |
| 次级运动 | Secondary motion | 衣物、头发等跟随主要动作变化。 | 女子转身，头发与外套下摆稍晚跟随摆动，停止后逐渐回落。 | 章节／多例。[视频](https://www.youtube.com/watch?v=uDqjIdI4bF4)、[Pexels 片段](https://www.pexels.com/video/close-up-of-a-woman-posing-on-a-windy-day-8370090/)。定位 Secondary Action 与 Follow Through；实拍可看发丝滞后 |
| 重量与惯性 | Weight and inertia / Grounded movement | 让身体运动体现支撑、重心和缓冲。 | 人物从低台跳下，双脚落地后膝盖自然弯曲，身体短暂下沉再站稳。 | 章节／多例。[视频](https://www.youtube.com/watch?v=uDqjIdI4bF4)、[Pexels 片段](https://www.pexels.com/video/a-woman-running-exercise-along-the-riverside-3048883/)。定位 Timing、缓冲与重叠动作；实拍留意落脚时重心和支撑 |
| 渐变式情绪 | Gradual emotional transition | 情绪通过连续动作变化形成。 | 人物先皱眉凝视屏幕，读完后肩膀慢慢放松，最后露出轻微笑容。 | 相近参考。[Pexels 片段](https://www.pexels.com/video/close-up-shot-of-a-woman-with-expressive-face-4128381/)、[Pexels 片段](https://www.pexels.com/video/close-up-footage-of-a-woman-smiling-at-camera-8170683/)。拆看表情变换与笑容形成，情绪转折需结合上下文设计 |
| 双人互动 | Character interaction / Two-person blocking | 明确人物间距离、朝向和相互动作。 | 两人隔桌而坐，女子将照片推到桌面中央，男子低头看照片后抬头看她。 | 独立片段。[Pexels 片段](https://www.pexels.com/video/a-man-and-a-woman-talking-while-standing-8293303/)、[Pexels 片段](https://www.pexels.com/video/a-woman-talking-to-a-client-while-making-hand-gestures-at-a-document-8844306/)。观察朝向、视线和手势怎样维持双人互动 |

## 11. 环境运动与动态细节

环境运动可以单独发生，也可以由人物动作引起。画面中的运动方向和力量关系应相互协调。

| 中文关键词 | English | 含义 | 可直接使用的提示词示例 | 视频入口与观察重点 |
|---|---|---|---|---|
| 微风 | Gentle breeze | 空气流动带来小幅、柔和的变化。 | 微风从窗外吹入，薄窗帘缓慢摆动，人物额前碎发轻轻移动。 | 独立片段。[Pexels 片段](https://www.pexels.com/video/wind-blowing-the-curtain-854116/)。看布料轻微起伏及风停后的回落 |
| 阵风 | Gust of wind | 短时增强的风带来较明显变化。 | 一阵风从左侧吹来，人物衣摆向右扬起，随后逐渐回落。 | 独立片段。[Pexels 片段](https://www.pexels.com/video/strong-winds-on-trees-5904897/)。看强风阶段枝叶摆动幅度如何扩大 |
| 漂浮尘埃 | Floating dust particles | 小颗粒缓慢运动，常在光束中可见。 | 窗边光束中，细小尘埃缓慢漂浮，室内其余部分保持安静。 | 独立片段。[Pexels 片段](https://www.pexels.com/video/view-of-dust-particles-in-sun-light-5561385/)。观察小颗粒在光路里的漂浮 |
| 雾气流动 | Drifting fog / Moving mist | 半透明雾层缓慢改变空间遮挡关系。 | 薄雾沿地面缓慢流动，远处树干时隐时现。 | 独立片段。[Pexels 片段](https://www.pexels.com/video/sunlight-over-fog-in-forest-14096474/)。观察林中雾层密度和遮挡变化 |
| 水面涟漪 | Water ripples | 水面受接触或风影响产生扩散波纹。 | 一滴水落入浅池，圆形涟漪从落点向外扩散，倒影随之轻微扭曲。 | 独立片段。[Pixabay 片段](https://pixabay.com/videos/rain-raindrops-ripples-puddle-356687/)。看同心波纹从落点扩散，及多组波纹叠加 |
| 降雨 | Falling rain / Rain streaks | 雨滴运动并与地面或物体产生反应。 | 雨滴持续落在石板路上，细小水花溅起，积水中的倒影轻微破碎。 | 独立片段。[Pexels 片段](https://www.pexels.com/video/street-in-city-during-heavy-rain-and-storm-at-night-12518558/)。看雨幕、地面反光与远处能见度 |
| 飘雪 | Falling snow | 雪花在不同距离和速度下运动。 | 雪花缓慢飘落，近处雪花略大，远处雪花细小，人物肩部逐渐积雪。 | 独立片段。[Pexels 片段](https://www.pexels.com/video/view-of-falling-snow-11057928/)。观察不同景深的雪花大小与速度 |
| 烟雾 | Drifting smoke / Rising smoke | 烟随浮力与空气流动上升和扩散。 | 熄灭的蜡烛上方，一缕细烟缓慢上升，随后随室内气流轻轻飘散。 | 独立片段。[Pexels 片段](https://www.pexels.com/video/a-smoke-trail-from-a-burning-incense-7311798/)。看线状烟流上升后卷曲、散开 |
| 热气／水雾 | Steam / Condensation mist | 热水附近的水蒸气凝结成细小水滴，形成可见白色水雾。 | 热茶上方的白色水雾缓慢上升，随后向窗户方向轻轻飘散。 | 独立片段。[Pexels 片段](https://www.pexels.com/video/a-cup-of-hot-drink-7241005/)。观察热饮上方的热气扩散 |
| 火焰闪动 | Flickering flame | 火焰形状和照明随时间变化。 | 壁炉火焰自然跳动，墙面和人物侧脸上的暖光轻微变化。 | 独立片段。[Pexels 片段](https://www.pexels.com/video/close-up-view-of-flickering-candle-flame-29688811/)。观察火焰轮廓及亮度起伏 |
| 动作带起尘土 | Dust kicked up by motion | 环境运动与人物或车辆动作存在因果关系。 | 奔跑者的脚步带起细小尘土，尘土在身后短暂悬浮后落下。 | 章节／多例。[Runway 示例页](https://help.runwayml.com/hc/en-us/articles/39789879462419-Gen-4-Video-Prompting-Guide)。在 Scene Motion 找机械公牛奔跑和身后扬尘示范 |
| 树叶摇动 | Swaying foliage / Rustling leaves | 枝叶随风出现分层次运动。 | 近处树叶轻轻摇动，远处树冠缓慢起伏，整体风向保持一致。 | 独立片段。[Pexels 片段](https://www.pexels.com/video/sun-dappled-leaves-swaying-in-summer-breeze-37469480/)。观察叶片及枝条随风反复摆动 |
| 反射随动 | Moving reflections / Coherent reflections | 水面、玻璃或金属反射随相关运动变化。 | 人物从橱窗前走过，玻璃中的倒影随人物同步移动。 | 独立片段。[Pexels 片段](https://www.pexels.com/video/an-elderly-woman-looking-at-herself-over-a-glass-window-5642578/)、[Pixabay 片段](https://pixabay.com/videos/rain-raindrops-ripples-puddle-356687/)。左例看玻璃反射和人物对应，右例看水面反射受波纹扰动 |

## 12. 叙事用途与镜头组织

这些词描述镜头在叙事中的作用，并不都对应某种固定景别。单镜头生成时，可先用它们规划分镜，再分别生成素材。

| 中文关键词 | English | 含义 | 可直接使用的提示词示例 | 视频入口与观察重点 |
|---|---|---|---|---|
| 建立镜头／交代镜头 | Establishing shot | 交代故事发生的地点、环境或空间关系。 | 城市车站的建立镜头，完整展示入口、广场和来往人群，清楚交代地点。 | 独立片段。[Runway 动图](https://help.runwayml.com/hc/article_attachments/47313515598611)。体育馆先交代整体空间，人物随后入画 |
| 环境空镜 | Environment shot / Atmospheric shot | 以环境、景物及氛围为主的画面。 | 无人物的雨后巷道，积水映出路灯，远处薄雾缓慢移动。 | 独立片段。[Pexels 片段](https://www.pexels.com/video/serene-rainy-day-in-empty-urban-alley-37014836/)。空巷中由地面、建筑和天气建立气氛 |
| 揭示镜头 | Reveal shot | 随运镜或遮挡变化，让关键信息逐渐出现。 | 摄影机向右横移，前景墙壁逐渐离开画面，显露墙后停着的一辆旧车。 | 独立片段。[Runway 动图](https://help.runwayml.com/hc/article_attachments/47313504750227)、[Runway 动图](https://help.runwayml.com/hc/article_attachments/47313504727955)。从手部拉远显露作画空间，或从肩后显露海岸地形 |
| 插入镜头／细节镜头 | Insert shot | 强调信件、手机、手部等叙事细节。 | 信封插入镜头，画面只见双手缓慢抽出一张折叠照片。 | 独立片段。[Pexels 片段](https://www.pexels.com/video/a-person-getting-keys-on-the-table-7986194/)、[StudioBinder 示例页](https://www.studiobinder.com/camera-shots/framing/insert-shot/)。手取钥匙可作局部素材，对照教学页的叙事用法 |
| 反应镜头 | Reaction shot | 展示人物对事件的反应。 | 女子反应特写，她看向画外，笑容逐渐消失，随后轻轻吸气。 | 章节／多例。[StudioBinder 示例页](https://www.studiobinder.com/blog/shot-reverse-shot-cutaways-coverage/)。定位 Reaction Shot，观察切到旁人后的表情信息 |
| 切出镜头 | Cutaway shot | 暂时离开主要动作，展示相关环境或旁观者。 | 雨滴敲打窗台的近景，窗外人影模糊经过，作为室内对话的切出素材。 | 章节／多例。[StudioBinder 示例页](https://www.studiobinder.com/blog/cutaway-shot/)。定位文章中的电影案例与教学视频，观察切离主要动作时展示的信息 |
| 双人镜头 | Two-shot | 两个人同时出现在一个镜头中。 | 腰部以上双人镜头，两人并排站在窗边，女子看向窗外，男子转头看她。 | 独立片段。[Pexels 片段](https://www.pexels.com/video/a-man-and-a-woman-talking-while-standing-8293303/)、[StudioBinder 视频](https://www.youtube.com/watch?v=qQNiqzuXjoM)。两名角色同框，比较彼此位置和朝向 |
| 主镜头 | Master shot | 较完整覆盖一场戏的主要动作和人物关系。 | 固定全景完整拍摄两人进入房间、交谈并落座的过程，保留整体空间关系。 | 章节／多例。[StudioBinder 视频](https://www.youtube.com/watch?v=AyML8xuKfoc)、[StudioBinder 视频](https://www.youtube.com/watch?v=FVR8zz8ci2k)。定位 Master Shot，观察单一宽画幅怎样覆盖整场关系。默认替代：[多人围桌 · 主镜头构图参考](https://www.pexels.com/video/people-sitting-at-table-talking-together-5899980/) |
| 连续长镜头 | Long take | 相对于作品整体剪辑节奏，持续时间较长的不中断镜头。 | 一个持续较长时间的连续镜头，摄影机缓慢跟随人物从门口走到窗边，人物停下后摄影机也平稳停住，并继续保留一段安静停留的画面。 | 章节／多例。[StudioBinder 示例页](https://www.studiobinder.com/blog/jurassic-park-cinematography/)。观看斯皮尔伯格长镜头案例，观察走位怎样改变画面重心 |

“长镜头”强调持续时间较长且不中断；“单个连续镜头”只强调不中断，本身不限定时长；“长焦镜头”描述光学取景特征。

## 13. 连续性与稳定性控制

这一类是生成控制语句，不是保证结果的开关。重要人物和空间一致性仍应结合参考图、首尾帧或其他可用控制，并检查生成结果。

| 中文关键词 | English | 含义 | 可直接使用的提示词示例 | 视频入口与观察重点 |
|---|---|---|---|---|
| 人物身份一致 | Consistent character identity | 维持同一人物的面部与主要外观特征。 | 女子在转头过程中保持相同五官、发型、服装和年龄特征。 | 章节／多例。[Gemini Omni 示例](https://deepmind.google/models/gemini-omni/prompt-guide/)、[Runway 示例页](https://help.runwayml.com/hc/en-us/articles/41748090660499-Creating-Multi-Character-Dialogues-with-Act-Two)。在 Keep your scene consistent 看角色参考，另用双人对白看片段接续。页内示范：[Gemini Omni 视角改动后的外观连贯](https://storage.googleapis.com/gdm-deepmind-com-prod-public/media/3cYlYfozIFs5_Ngj/gemini-omni__edit-over-multiple-turns-with-consistency__angle.webm) |
| 服装与道具一致 | Consistent wardrobe and props | 避免服装、饰物、手持物在过程中无故变化。 | 男子始终穿同一件深蓝外套，右手持续握着同一只白色杯子。 | 章节／多例。[Runway 示例页](https://help.runwayml.com/hc/en-us/articles/41748090660499-Creating-Multi-Character-Dialogues-with-Act-Two)。观察车内对白示例跨镜头的服装与环境中的物件 |
| 场景布局稳定 | Stable scene geometry / Consistent layout | 保持门窗、家具等相对关系。 | 人物移动时，窗户始终位于后墙左侧，桌椅的位置与形状保持稳定。 | 章节／多例。[Genie 2 示例](https://deepmind.google/blog/genie-2-a-large-scale-foundation-world-model/)。定位 Long horizon memory 与 3D structures，观察房间转向前后空间。页内示范：[Genie 2 三维结构](https://storage.googleapis.com/gdm-deepmind-com-prod-public/media/media/3d_structures_1.mp4) |
| 尺度关系稳定 | Consistent scale and proportions | 主体和环境尺寸关系随透视合理变化。 | 人物经过门框时保持自然身高比例，手中杯子的大小与手掌关系稳定。 | 相近参考。[Pexels 片段](https://www.pexels.com/video/a-woman-running-exercise-along-the-riverside-3048883/)。实拍正例，观察同一主体经过栏杆和地面时相对比例是否合理 |
| 动作连续 | Continuous motion / Temporal consistency | 动作在时间上平顺衔接。 | 人物连续完成伸手、握杯和提起三个动作，手臂轨迹平滑衔接。 | 独立片段。[Pexels 片段](https://www.pexels.com/video/a-woman-running-exercise-along-the-riverside-3048883/)、[FXI 动态例](https://www.fxi.studio/tutorials/prompt-recipes/side-tracking)。顺着相邻几步观察四肢位置与移动轨迹 |
| 自然人体结构 | Natural anatomy / Anatomically coherent movement | 用自然关节关系和身体结构表达动作。 | 双手清晰可见，手指自然弯曲握住杯柄，手腕和前臂连贯运动。 | 相近参考。[Pexels 片段](https://www.pexels.com/video/hand-grabbing-cup-13675326/)。实拍正例，逐帧观察手指抓握与手腕角度 |
| 光照稳定 | Consistent lighting | 光源方向和亮度与场景变化相符。 | 人物缓慢转身，左侧窗光方向保持一致，阴影随面部朝向自然变化。 | 相近参考。[Pexels 片段](https://www.pexels.com/video/a-woman-standing-by-the-window-7277929/)。实拍参考，注意主体在窗旁运动时亮暗是否随几何关系变化。页内示范：[Genie 2 空间照明一致性参考](https://storage.googleapis.com/gdm-deepmind-com-prod-public/media/media/lighting_1.mp4) |
| 物体持续存在 | Object permanence | 物体经过遮挡后仍维持合理位置和外观。 | 人物短暂遮住桌上花瓶后继续走开，花瓶仍在原位，外观保持一致。 | 章节／多例。[Genie 2 示例](https://deepmind.google/blog/genie-2-a-large-scale-foundation-world-model/)。定位 Long horizon memory，观察移出画框的场景细节重新出现 |
| 单镜头连续呈现 | One continuous shot / Continuous, seamless shot | 强调同一镜头内的时间与空间连续性，本身不限定时长或摄影机运动方式。 | 整段视频为一个连续镜头，完整呈现人物从门口走到窗边并停下的过程。 | 章节／多例。[StudioBinder 示例页](https://www.studiobinder.com/blog/jurassic-park-cinematography/)、[Runway 示例页](https://help.runwayml.com/hc/en-us/articles/48324313115155-Image-to-Video-Prompting-Guide)。看长镜头示范或者无切镜的连续生成案例 |
| 明确结束画面 | Defined end frame / Final composition | 指定运动结束时看见什么。 | 摄影机最终停在人物胸部以上近景，人物位于右侧，左侧保留窗户。 | 章节／多例。[Runway 示例页](https://help.runwayml.com/hc/en-us/articles/50488490233363-Creating-with-Seedance-2-0)、[Gemini Omni 示例](https://deepmind.google/models/gemini-omni/prompt-guide/)。定位 Start/End frames 或 Specify first and last frames，检查最后的画幅。页内示范：[Gemini Omni 首尾帧示范](https://storage.googleapis.com/gdm-deepmind-com-prod-public/media/YMgFKThN-vej75eW/gemini-omni__first-last-frame__dummer-ballet.webm) |

## 14. 声音关键词：仅适用于支持声音生成的工作流

如果所用模型仅输出无声视频，可把以下内容作为后期声音设计说明。对白最好单独提供准确文本和说话者。

| 中文关键词 | English | 含义 | 可直接使用的提示词示例 | 视频入口与观察重点 |
|---|---|---|---|---|
| 环境声 | Ambient sound / Ambience | 持续建立地点氛围的背景声音。 | 安静室内保留轻微窗外风声，远处偶尔传来车辆经过声。 | 章节／多例。[Veo 视频示例](https://deepmind.google/models/veo/prompt-guide/)、[DeepMind 音画示例](https://deepmind.google/blog/generating-audio-for-video/)。找纸船入雨水沟的音视频，比较持续雨声与具体水声。页内示范：[Veo 雨中纸船 · 环境声](https://storage.googleapis.com/gdm-deepmind-com-prod-public/media/media/veo__veo-3__paper.mp4) |
| 室内底噪 | Room tone | 场景中相对稳定、低强度的声音底层。 | 保留轻微室内空气声和远处空调声，整体安静。 | 章节／多例。[StudioBinder 示例页](https://www.studiobinder.com/blog/what-is-room-tone/)。定位 Room tone example，比较安静场景中持续低电平背景 |
| 叙事内声音 | Diegetic sound | 声音来自故事世界中，如脚步、广播、对白；声源可以出现在画内，也可以位于画外。 | 人物走过木地板，脚步声与落脚同步，窗外传来模糊街道声。 | 章节／多例。[StudioBinder 示例页](https://www.studiobinder.com/blog/what-is-diegetic-sound/)。打开页内影片示范，听角色所在环境内实际存在的声音。页内示范：[Veo 雨中纸船 · 画内水声](https://storage.googleapis.com/gdm-deepmind-com-prod-public/media/media/veo__veo-3__paper.mp4) |
| 拟音 | Foley / Foley effects | 为动作和材质设计细节声音，常在后期补录。 | 清楚呈现衣料摩擦、手指接触纸张及杯子落在木桌上的轻响。 | 独立片段。[拟音视频](https://www.youtube.com/watch?v=U_tqB4IZvMk)。用耳机看拟音师如何对动作补录声音 |
| 同步对白 | Synchronized dialogue / Lip-synced dialogue | 人物说话与口型、时间相配合。 | 女子看向男子，平静地说：“我明天回来。”口型与这句中文对白同步。 | 章节／多例。[Runway 示例页](https://help.runwayml.com/hc/en-us/articles/41748090660499-Creating-Multi-Character-Dialogues-with-Act-Two)、[Veo 视频示例](https://deepmind.google/models/veo/prompt-guide/)。找双人对白或 Camping 示例，检查说话者、句子和口型起止。页内示范：[Veo 露营对话 · 声画同步参考](https://storage.googleapis.com/gdm-deepmind-com-prod-public/media/media/veo__veo-3__camper.webm) |
| 旁白 | Voice-over / Narration | 画面外的声音用于叙述或表达想法。 | 画面呈现清晨山谷，配低声、缓慢的中文旁白：“天亮之前，我们已经出发。” | 章节／多例。[StudioBinder 示例页](https://www.studiobinder.com/blog/what-is-voice-over-definition/)。用页内场景对照镜头画面与画外叙述 |
| 配乐 | Background score / Music underscore | 用音乐建立节奏和情绪。 | 轻柔稀疏的钢琴配乐缓慢进入，音量低于人物对白。 | 章节／多例。[DeepMind 音画示例](https://deepmind.google/blog/generating-audio-for-video/)。定位包含 dramatic score 的音画示范，听音乐与环境声叠加后的比例 |
| 声音远近与空间 | Sound perspective / Spatial ambience | 声音强弱、清晰度和混响体现距离与空间。 | 人物走进空旷大厅后，脚步声出现轻微回响，门外车流声逐渐变远。 | 相近参考。[DeepMind 音画示例](https://deepmind.google/blog/generating-audio-for-video/)、[StudioBinder 示例页](https://www.studiobinder.com/blog/what-is-room-tone/)。听同一场景内脚步与远处环境层次；精确距离变化需另行录制对照 |

## 15. 分镜衔接与剪辑关键词

以下多数用于多个镜头之间的组织。只有在模型或工作流明确支持多镜头生成时，才把它们作为一次生成的要求；否则分别生成素材后剪辑。

| 中文关键词 | English | 含义 | 可直接使用的提示词示例 | 视频入口与观察重点 |
|---|---|---|---|---|
| 正反打 | Shot–reverse shot | 在对话双方的相对视角间切换。 | 分别生成两人过肩近景，女子始终看向画面右侧，男子始终看向画面左侧。 | 章节／多例。[StudioBinder 示例页](https://www.studiobinder.com/blog/shot-reverse-shot-cutaways-coverage/)、[Runway 示例页](https://help.runwayml.com/hc/en-us/articles/41748090660499-Creating-Multi-Character-Dialogues-with-Act-Two)。观察两边过肩镜头如何相互承接 |
| 视线匹配 | Eyeline match | 人物看向的方向与后续所见对象对应。 | 前一镜头人物抬眼看向画面右上方，后一镜头展示高处阳台上的人。 | 章节／多例。[StudioBinder 示例页](https://www.studiobinder.com/blog/what-is-an-eyeline-match/)。定位《阅后即焚》示例，核对角色目光与所见对象 |
| 动作匹配剪辑 | Match on action | 在同一动作过程中切换视角并保持动作衔接。 | 镜头一拍人物伸手开门，镜头二从门内角度承接推门动作。 | 章节／多例。[StudioBinder 示例页](https://www.studiobinder.com/blog/what-is-a-match-on-action-cut/)、[Adobe 视频](https://www.youtube.com/watch?v=TO0cke22rgM)。定位开门或教程中的连续动作匹配，观察动作在哪一帧换视角 |
| 图形匹配剪辑 | Graphic match cut | 利用形状、位置或色彩相似连接两个镜头。 | 镜头一以居中的圆形钟表结束，镜头二以同位置的圆形车轮开始。 | 章节／多例。[StudioBinder 示例页](https://www.studiobinder.com/blog/match-cuts-creative-transitions-examples/)。定位 Graphic Match Cut，看两帧轮廓或位置的对应 |
| 叠化 | Dissolve / Cross-dissolve | 前后画面在一段时间内重叠过渡。 | 在后期让黄昏空屋逐渐叠化为同机位的清晨空屋，表达时间流逝。 | 章节／多例。[StudioBinder 示例页](https://www.studiobinder.com/blog/types-of-editing-transitions-in-film/)、[Adobe 视频](https://www.youtube.com/watch?v=488th30k738)。定位 Dissolve／Cross Dissolve，观察两画面重叠过程 |
| 淡入／淡出 | Fade in / Fade out | 画面从黑色等单色中出现，或逐渐消失。 | 人物离开后保持空房画面，随后在后期缓慢淡出至黑色。 | 章节／多例。[StudioBinder 示例页](https://www.studiobinder.com/blog/types-of-editing-transitions-in-film/)、[Adobe 视频](https://www.youtube.com/watch?v=488th30k738)。定位 Fade In／Fade Out，观察画面从黑色出现或消失 |
| J 型剪辑 | J-cut | 后一场景的声音先于画面进入。 | 先在室内画面中听见下一镜头的海浪声，再切到海边画面。 | 章节／多例。[视频](https://www.youtube.com/watch?v=fT5rRPMnka0)。定位 J-cut，注意后一个镜头的声音先进入 |
| L 型剪辑 | L-cut | 前一镜头声音延续到下一镜头画面。 | 人物对白继续播放，画面切到对方安静倾听的反应镜头。 | 章节／多例。[视频](https://www.youtube.com/watch?v=fT5rRPMnka0)。定位 L-cut，注意前一镜头声音延续到后一画面 |

## 16. 负面提示词与正向替代表达

先确认平台是否提供独立负面提示功能。Runway 的部分模型指南明确建议用正向表达；这类模型优先使用下表最后一列。[参考：Runway 正向表达说明](https://help.runwayml.com/hc/en-us/articles/39789879462419-Gen-4-Video-Prompting-Guide)

负面词表达的是希望减少的现象，不会自动修复结构、人物或运动问题。下表正向示例需与主体动作和运镜目标匹配；条件式写法应选择适用的一种，避免把所有选项同时拼接。

| 中文含义 | English negative term | 适用的负面提示片段 | 按镜头目标选用的正向示例 | 视频入口与观察重点 |
|---|---|---|---|---|
| 非预期切镜 | Unwanted cuts / Jump cuts | unwanted cuts, jump cuts | 一个连续镜头，完整呈现主体动作及其空间变化。 | 章节／多例。[Runway 示例页](https://help.runwayml.com/hc/en-us/articles/48324313115155-Image-to-Video-Prompting-Guide)、[Adobe 对照](https://helpx.adobe.com/premiere/desktop/add-video-effects/apply-video-transitions/morph-cut-overview.html)。AI 指南定位 unwanted cuts，Adobe 例用于分辨跳切的视觉跳跃 |
| 亮度或纹理闪烁 | Flicker / Temporal flickering | flicker, temporal flickering | 光照和材质外观在时间上保持稳定，细节随运动连续变化。 | 章节／多例。[AI 闪烁前后](https://digitalanarchy.com/blog/video-editing-plugins/removing-flicker-from-generative-ai-videos/)。看 AI 龙尾闪光和走廊光束变化的原例与去闪对照 |
| 人物外观漂移 | Identity drift | identity drift, changing facial features | 同一人物保持相同五官、发型与服装，转头过程面部特征连贯。 | 相近参考。[Gemini Omni 示例](https://deepmind.google/models/gemini-omni/prompt-guide/)、[Runway 示例页](https://help.runwayml.com/hc/en-us/articles/41748090660499-Creating-Multi-Character-Dialogues-with-Act-Two)。正向对照，比较多镜头五官与发型；暂无可复核的独立漂移反例 |
| 场景或物体形变 | Geometry warping / Object deformation | geometry warping, object deformation | 家具和门窗形状稳定，运动中保持原有结构与位置关系。 | 相近参考。[研究示范](https://openai.com/index/video-generation-models-as-world-simulators/#discussion)、[Runway 动图](https://help.runwayml.com/hc/article_attachments/47313515634835)。历史模型报告提供物理异常示范；建筑动图为有意形变，可帮助辨认形变方式 |
| 多余肢体或手指 | Extra limbs / Extra fingers | extra limbs, extra fingers | 双臂和双手清晰可辨，手指以自然结构握住物体。 | 相近参考。[Pexels 片段](https://www.pexels.com/video/hand-grabbing-cup-13675326/)、[Runway 示例页](https://help.runwayml.com/hc/en-us/articles/48324313115155-Image-to-Video-Prompting-Guide)。用实拍抓杯正例逐帧核对手部结构，指南说明瑕疵可能被放大；暂无独立多肢反例 |
| 非预期摄影机晃动 | Unwanted camera shake | unwanted camera shake | 固定机位时写：“摄影机保持静止”；移动机位时写：“摄影机沿既定轨迹平稳移动，画面稳定”。 | 章节／多例。[Adobe 稳定教学](https://helpx.adobe.com/ph_fil/after-effects/how-to/stabilize-footage.html)。按 Adobe 教学中的原片和稳定版比较背景边缘 |
| 非预期文字叠加 | Unwanted text overlays | unwanted text overlays, subtitles | 正向描述仅作间接引导：“画面完整呈现场景本身及其中的人物与物体”。字幕／文字叠加优先通过平台可用设置或支持的独立负面提示控制，必要时后期处理。 | 相近参考。[Adobe 移除演示](https://www.adobe.com/sg/learn/after-effects/web/remove-unwanted-element)。有视频的移除元素演示可作类比，未找到专门展示生成模型意外叠字的同条件对比 |
| 动作瞬间跳位 | Teleporting / Discontinuous motion | teleporting, discontinuous motion | 人物沿连续路径从门口走到桌边，位置变化与步伐相匹配。 | 相近参考。[研究示范](https://openai.com/index/video-generation-models-as-world-simulators/#discussion)、[Pexels 片段](https://www.pexels.com/video/a-woman-running-exercise-along-the-riverside-3048883/)。报告的物体突现和时序异常可作类比，实拍跑步作正例；暂无对应的角色瞬移对照 |

## 17. 通用提示词结构

### 17.1 文生视频

```text
[主体与场景]。
[主体动作：起始状态 → 主要动作 → 结束状态]。
[景别与拍摄角度]。
[摄影机运动：起点 → 路径／方向／速度 → 结束画面]。
[构图与焦点]。
[光线、色彩和影像质感]。
[必要的连续性要求]。
```

英文结构：

```text
[Subject and setting].
[Subject action: starting state → main action → ending state].
[Shot size and camera angle].
[Camera movement: starting position → path / direction / speed → final framing].
[Composition and focus].
[Lighting, color palette, and visual style].
[Essential continuity requirements].
```

### 17.2 图生视频

```text
以参考图为起始画面。
[主体进行什么动作，动作幅度与方向]。
[摄影机如何移动，最后停在哪里]。
[环境中哪些元素运动]。
[需要保持的外观、空间与光照关系]。
```

英文结构：

```text
Use the reference image as the starting frame.
[Subject action, amplitude, and direction].
[Camera movement and final framing].
[Environmental motion].
[Appearance, spatial relationships, and lighting to maintain].
```

图生视频不必重复参考图里所有细节。先把期望发生的运动说清楚，再针对实际问题补充限制。[参考：Runway 图生视频提示指南](https://help.runwayml.com/hc/en-us/articles/48324313115155-Image-to-Video-Prompting-Guide)

## 18. 可直接复制的完整中英文提示词

### 示例 A：人物情绪，缓慢推近

- **人物情绪，缓慢推近**。窗光、面部靠近和抬眼分别取参考。 [窗边实拍](https://www.pexels.com/video/woman-reading-by-window-light-36643095/)、[推近](https://help.runwayml.com/hc/article_attachments/47313515615379)、[抬眼](https://www.pexels.com/video/headshot-of-woman-looking-up-10050974/)

中文：

```text
黄昏的室内，一名穿灰色毛衣的女子站在窗边。她先低头看着手中的信封，随后缓慢抬眼望向窗外。胸部以上近景，平视，四分之三侧面。摄影机沿正前方缓慢推近，最后停在面部特写。人物位于画面右侧，左侧保留窗户。浅景深，焦点持续保持在双眼。柔和窗光从左侧照来，低饱和暖灰色调，自然皮肤纹理。一个连续镜头，人物五官、服装和窗户位置保持一致。
```

English:

```text
At dusk, a woman in a gray sweater stands beside a window inside a quiet room. She first looks down at an envelope in her hands, then slowly raises her eyes toward the window. An eye-level medium close-up from a three-quarter angle. The camera slowly dollies forward, ending on a close-up of her face. She stays on the right side of the frame, with the window visible on the left. Shallow depth of field, with focus tracking her eyes. Soft window light comes from the left. A muted warm-gray palette and natural skin texture. One continuous shot. Her facial features, clothing, and the window's position remain consistent.
```

### 示例 B：环境揭示，拉远后升高

- **环境揭示，拉远后升高**。荒漠场景与合成运镜分开参考。观察画面如何从人物揭示周围空间。 [荒漠遗迹](https://stock.adobe.com/video/aerial-view-of-woman-running-in-the-desert-towards-french-fortress-with-wadi-rum-sandstone-in-the-background-in-jordan-tilt-up/500255349)、[过肩拉远升高](https://help.runwayml.com/hc/article_attachments/47313504727955)、[摇臂升高](https://www.fxi.studio/tutorials/prompt-recipes/crane-up)、[FXI 摇臂升高 MP4](https://assets.fxi.studio/generations/oss/camera-moves/crane-up-v7.mp4)

中文：

```text
一名旅人背对摄影机，站在荒漠中的断墙前，外套下摆随微风轻轻摆动。以人物背面全身景开始。摄影机先平稳后退，逐渐显露断墙两侧；随后缓慢升高，展现延伸到远方的整片遗迹。旅人始终位于画面中央下方。深景深，夕阳逆光，沙石地面有细长阴影，空气中有少量尘埃。电影写实风格，一个连续镜头，遗迹结构随视角变化保持连贯。
```

English:

```text
A traveler stands with their back to the camera in front of a ruined wall in the desert. The hem of their coat moves gently in the breeze. Begin with a full shot from behind. The camera first dollies backward smoothly, revealing both sides of the wall, then slowly cranes upward to reveal an extensive field of ruins stretching into the distance. Keep the traveler near the lower center of the frame. Deep depth of field, sunset backlighting, long shadows across the rocky ground, and a small amount of airborne dust. Cinematic realism. One continuous shot, with coherent ruin geometry throughout the changing viewpoint.
```

### 示例 C：动作场面，侧向跟拍

- **动作场面，侧向跟拍**。前者看步态、衣物和河岸，后者看摄影机如何匹配主体速度。 [河岸跑步](https://www.pexels.com/video/a-woman-running-exercise-along-the-riverside-3048883/)、[侧向跟拍](https://www.fxi.studio/tutorials/prompt-recipes/side-tracking)、[FXI 侧向跟拍 MP4](https://assets.fxi.studio/generations/oss/camera-moves/side-tracking-v7.mp4)

中文：

```text
一名穿深色运动服的女子沿清晨河岸匀速跑步。侧面全身景，摄影机与她保持相同速度，从侧面平行跟拍。人物始终位于画面中央，河岸栏杆和远处树木在背景中连续掠过。双脚交替落地，膝盖自然缓冲，马尾和衣摆跟随步伐轻微摆动。清晨柔和自然光，色彩清爽，平稳的稳定器运动，实时速度，一个连续镜头。
```

English:

```text
A woman in dark athletic clothing runs at a steady pace along a riverside path in the early morning. A full-body profile shot. The camera tracks parallel to her at matching speed, keeping her centered in the frame. Railings and distant trees move continuously through the background. Her feet alternate naturally on the ground, her knees absorb each step, and her ponytail and clothing move with her stride. Soft natural morning light and a fresh, restrained color palette. Smooth stabilized tracking at real-time speed. One continuous shot.
```

### 示例 D：产品细节，固定机位转移焦点

- **产品细节，固定机位转移焦点**。手表结构和金属质感参考第一段，清晰度从前景换到后景参考第二段。 [机械表微距](https://developers.kreatorflow.ai/videos/seedance-2-5-prompt-watch-foley-macro)、[前后拉焦](https://help.runwayml.com/hc/article_attachments/47313515641107)

中文：

```text
一块机械手表放在深灰色石台上。摄影机固定，低角度微距取景，表壳边缘位于前景，表盘位于稍后的距离。镜头开始时前景金属边缘清晰，随后焦点缓慢转移到表盘刻度，秒针持续自然走动。背景柔和虚化。窄条柔光在金属边缘形成清晰但不过曝的高光，石台纹理真实，整体冷灰色调。一个连续镜头，手表结构保持稳定。
```

English:

```text
A mechanical wristwatch rests on a dark gray stone surface. A locked-off, low-angle macro shot places the edge of the case in the foreground and the dial slightly farther back. Begin with the foreground metal edge in sharp focus, then slowly rack focus to the dial markings as the second hand continues ticking naturally. A softly blurred background. A narrow strip of soft light creates a defined highlight along the metal edge while preserving surface detail. Realistic stone texture and a cool-gray palette. One continuous shot with stable watch geometry.
```

### 示例 E：环境空镜，固定机位与微小运动

- **环境空镜，固定机位与微小运动**。分别观察空巷构图、雨滴与雾气，合在一起作为场景参考。 [雨天空巷](https://www.pexels.com/video/serene-rainy-day-in-empty-urban-alley-37014836/)、[水面涟漪](https://pixabay.com/videos/rain-raindrops-ripples-puddle-356687/)、[林中雾气](https://www.pexels.com/video/sunlight-over-fog-in-forest-14096474/)

中文：

```text
雨后的旧巷道，石板地面有浅浅积水，远处一盏暖色路灯亮着。固定机位远景，巷道线条引向画面中央远处的路灯。画面中持续发生的运动只有檐口滴水、水面扩散的细小涟漪，以及低处缓慢移动的薄雾。深景深，冷蓝环境光与暖色路灯形成轻微冷暖对比，安静的写实影像，一个连续镜头。
```

English:

```text
An old alley after the rain, with shallow puddles on the stone pavement and a warm streetlamp glowing in the distance. A locked-off wide shot. The lines of the alley lead toward the distant lamp near the center of the frame. The ongoing motion consists of water dripping from the eaves, small ripples spreading across the puddles, and a thin layer of mist drifting close to the ground. Deep depth of field. Cool-blue ambient light contrasts gently with the warm streetlamp. Quiet, realistic imagery. One continuous shot.
```

### 示例 F：图生视频，保留参考图并加入动作

- **图生视频，保留参考图并加入动作**。第一项看首图如何传给视频，后两项分别看表演与环境运动。 [Runway 首图与输出示例](https://help.runwayml.com/hc/en-us/articles/48324313115155-Image-to-Video-Prompting-Guide)、[抬眼动作](https://www.pexels.com/video/headshot-of-woman-looking-up-10050974/)、[窗帘摆动](https://www.pexels.com/video/wind-blowing-the-curtain-854116/)

中文：

```text
以腰部以上中景或更宽取景的参考图为起始画面。人物保持原有站位和服装，先自然眨眼，随后轻轻抬起下巴，把视线转向窗外。摄影机从参考图的构图开始，沿正前方缓慢靠近，最后停在胸部以上近景。窗帘随微风轻微摆动。人物五官和发型、房间布局与原有光线方向保持一致。动作幅度克制，运动连续。
```

English:

```text
Use a reference image framed as a waist-up medium shot or wider as the starting frame. The character keeps the same position and clothing, blinks naturally, then gently raises their chin and shifts their gaze toward the window. Starting from the reference composition, the camera slowly dollies forward, ending on a medium close-up framed from the chest up. The curtain moves slightly in a gentle breeze. Maintain the character's facial features and hairstyle, the room layout, and the original lighting direction. Restrained actions and continuous motion.
```

本示例要求参考图采用腰部以上中景或更宽的取景；若起始图已是面部特写，应将前推改为拉远至胸部以上近景，或保持原景别。图生视频示例中的“窗户”“窗帘”等元素应替换为参考图中实际存在的对象；增加新元素时，应明确它何时、从哪里出现。

### 示例 G：双人对话，分别生成正反打素材

- **双人对话，女子的过肩镜头**。定位首个过肩镜头，肩在前景，观察被拍者视线与留白。 [实拍过肩段](https://www.vanityfair.com/video/watch/reverse-film-school-what-happens-when-a-movie-has-no-camera-operator)、[正反打示例](https://www.studiobinder.com/blog/shot-reverse-shot-cutaways-coverage/)
- **双人对话，男子的反打镜头**。在反向机位复核肩部、座位、视线方向和光线。 [正反打示例](https://www.studiobinder.com/blog/shot-reverse-shot-cutaways-coverage/)、[AI 双人对白](https://help.runwayml.com/hc/en-us/articles/41748090660499-Creating-Multi-Character-Dialogues-with-Act-Two)

以下是两个独立镜头的提示词，用于后期剪辑，不应直接合并成同一次单镜头生成。实际执行时，结合参考图确认座位、视线与轴线关系。

镜头 1，中文：

```text
女子与男子隔桌相对而坐。越过前景男子的肩部，拍摄对面女子胸部以上近景。女子位于画面左侧，视线朝向画面右侧的男子。她先看着对方，随后低头看桌上的照片。固定机位，柔和窗光，浅景深，前景男子的肩部轻微虚化。
```

Shot 1, English:

```text
A woman and a man sit opposite each other at a table. Shoot over the man's shoulder toward a medium close-up of the woman. Keep the woman on the left side of the frame, looking toward the man on screen right. She first looks at him, then lowers her gaze to a photograph on the table. A locked-off camera, soft window light, shallow depth of field, and a softly blurred foreground shoulder.
```

镜头 2，中文：

```text
延续同一房间、座位与光线关系。越过前景女子的肩部，拍摄对面男子胸部以上近景。男子位于画面右侧，视线朝向画面左侧的女子。他安静等待，随后轻轻点头。固定机位，柔和窗光，浅景深，前景女子的肩部轻微虚化。
```

Shot 2, English:

```text
Continue the same room, seating arrangement, and lighting relationships. Shoot over the woman's shoulder toward a medium close-up of the man. Keep the man on the right side of the frame, looking toward the woman on screen left. He waits quietly, then gives a small nod. A locked-off camera, soft window light, shallow depth of field, and a softly blurred foreground shoulder.
```

### 示例 H：自然物微距，风与焦点配合

- **自然物微距，风与焦点配合**。用前两段看水滴和合焦细节，后者看叶片摆幅。 [水滴滑过叶面](https://www.pexels.com/video/droplets-of-water-sliding-from-a-leaf-5210311/)、[水滴慢动作](https://www.pexels.com/video/water-droplets-on-a-leaf-7235029/)、[叶片随风](https://www.pexels.com/video/sun-dappled-leaves-swaying-in-summer-breeze-37469480/)

中文：

```text
清晨，一片带露水的叶子位于画面中央。微距特写，摄影机固定，焦点保持在叶缘的一颗露珠上。微风使叶子小幅摆动，露珠贴着叶面缓慢滑动一小段距离。背景树叶形成柔和绿色散景。侧后方柔光照亮露珠边缘，叶脉细节自然，一个连续镜头。
```

English:

```text
In the early morning, a dew-covered leaf sits near the center of the frame. A locked-off macro close-up, with focus tracking a single droplet near the leaf's edge. A gentle breeze moves the leaf slightly, and the droplet slowly slides a short distance along its surface. Background foliage forms soft green bokeh. Soft light from the side and behind illuminates the edge of the droplet. Natural leaf-vein detail. One continuous shot.
```

## 19. 容易混淆或冲突的写法

| 常见写法或问题 | 为什么容易产生歧义 | 更明确的写法 |
|---|---|---|
| “推近”和“变焦放大”混用 | 前者移动摄影机位置，后者改变焦距。 | 需要空间视差变化时写“摄影机向前移动”；需要固定位置放大时写“摄影机固定，变焦放大”。 |
| “摇摄”和“横移”混用 | 摇摄原地转动，横移改变摄影机位置。 | 明确“摄影机位置不变，向右转动”或“摄影机整体向右平移”。 |
| “仰拍”和“上摇”混用 | 仰拍是观察角度，上摇是随时间转动的动作。 | “低机位仰拍，摄影机固定”或“摄影机原地从脚部向上转到面部”。 |
| 同时写“固定机位”和“缓慢环绕” | 同一时段要求摄影机既静止又移动。 | 选一种；如确实分阶段，写“先固定片刻，随后开始缓慢环绕”。 |
| “背景虚化”和“前后全部清晰”并列 | 对同一画面提出不同景深目标；拉焦本身不能保证前后同时清晰。 | 分清目标：“浅景深，焦点从前景转到背景，前景随之虚化”；或“深景深，前后景同时保持清晰”。 |
| 只写“电影感”“高级感” | 这些词难以直接确定机位、动作和光线。 | 补充“平视近景、缓慢推近、柔和侧光、低饱和暖灰色调”。 |
| “长镜头”写成“长焦” | 前者强调持续时间较长且不中断，后者指光学特征。 | 分别写“持续较长时间的连续镜头”和“长焦取景、远距离空间压缩感”。 |
| 只写“35mm” | 可能指胶片规格，也可能指焦距；焦距对应的视角还取决于画幅。 | 分别写“35 毫米胶片质感”或“全画幅等效 35 毫米的较宽视角”。 |
| 把“广角”当作“远景” | 广角是镜头视角特征，远景是主体在画面中的取景大小。 | 同时描述：“广角、近距离人物特写”或“远景、人物占画面很小”。 |
| 把“高调”当作“高亮曝光” | 高调包含明暗结构，不要求丢失高光细节。 | “整体明亮、阴影浅淡、白色区域保留纹理”。 |
| 只写人物“悲伤” | 表演动作仍需模型自行解释。 | “人物低头，目光停在照片上，肩膀微微下沉，缓慢呼气”。 |
| 在很短片段里安排多次切镜和大量事件 | 指令密集，动作先后和空间关系不易同时清楚。 | 把主要事件拆成独立镜头，分别生成，再剪辑。 |
| 图生视频提示与参考图运动线索冲突 | 参考图中的姿态、模糊、尘土等可能暗示已有运动。 | 选择与目标动作更一致的起始画面，或先调整参考图。 |
| 在提示词里写“4K、60fps”就认为已设置输出 | 输出规格取决于模型和实际生成设置。 | 在平台参数中选择支持的分辨率、帧率、画幅和时长，提示词描述视觉目标。 |
| 期待一句“人物一致”解决所有变化 | 文字约束不等于身份与几何锁定。 | 使用清晰参考，减少不必要的遮挡和复杂运动，并逐镜头检查结果。 |
| 默认所有模型都理解同样的负面提示 | 不同模型的负面指令能力与写法不同。 | 查所用模型说明，优先使用清楚的正向场景与动作描述。 |

## 20. 快速选词方法

第一次写一个镜头，可以先填下面六项：

```text
1. 拍什么：谁，在什么地方。
2. 做什么：一个主要动作，以及动作的结束状态。
3. 拍多近：全身、腰部以上、胸部以上、面部或局部。
4. 怎么看：平视、仰拍、俯拍、侧面、过肩或主观视角。
5. 怎么动：固定、推近、拉远、横移、跟拍或环绕。
6. 什么光：光源方向、软硬、冷暖和整体反差。
```

得到基础结果后，每次只调整一个重要维度，例如先改运镜，再改表演，最后改光色。这样更容易判断哪项修改起了作用。

一个简洁起点：

```text
女子站在窗边，缓慢抬眼望向窗外。胸部以上近景，平视侧拍，摄影机缓慢推近。浅景深，焦点保持在眼睛。柔和窗光，低饱和暖灰色调，一个连续镜头。
```

## 参考说明

术语定义参考摄影与影视制作的常用用法；表格和模板中的具体提示词示例为本库自拟。生成建议主要参考以下官方资料，具体模型限制以其对应文档为准：

- [Adobe：镜头类型与拍摄角度](https://www.adobe.com/uk/creativecloud/video/production/cinematography/camera-shots-and-angles.html)
- [Adobe：荷兰角／倾斜镜头](https://www.adobe.com/creativecloud/video/production/cinematography/camera-shots-and-angles/dutch-angle-shot.html)
- [Canon：焦距与视角](https://files.canon-europe.com/files/webcontent/rf-lens-world/knowledge/focus/index.html)
- [Canon：景深](https://files.canon-europe.com/files/webcontent/rf-lens-world/knowledge/depth-of-field/index.html)
- [Canon：透视](https://files.canon-europe.com/files/webcontent/rf-lens-world/knowledge/perspective/index.html)
- [ARRI：灯光手册](https://www.arri.com/en/learn/lighting/lighting-handbook)
- [Runway：摄影机术语、提示词和示例](https://help.runwayml.com/hc/en-us/articles/47313504791059-Camera-Terms-Prompts-Examples)
- [Runway：图生视频提示指南](https://help.runwayml.com/hc/en-us/articles/48324313115155-Image-to-Video-Prompting-Guide)
- [Runway：Gen-4 提示指南](https://help.runwayml.com/hc/en-us/articles/39789879462419-Gen-4-Video-Prompting-Guide)
- [Google：视频生成提示指南](https://cloud.google.com/vertex-ai/generative-ai/docs/video/video-gen-prompt-guide)
