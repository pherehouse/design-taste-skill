# 01 · 设计网站资源库（100 个）

来源：EianLu《100 个提升审美的设计网站大赏》（[原帖](https://x.com/EianLu/status/2121219503988113557)）

- 核验时间：2026-11-14 约 14:00–14:30（太平洋时间，UTC-8）
- 核验方法：curl（Chrome UA、跟随跳转、20s 超时、并发）；被 403/429 拦截的再用 WebFetch 复查。仅抓取首页标题与 meta 描述，**未登录、未下载任何付费资源**。
- 状态：`已访问核验`＝返回 2xx/3xx 且有真实页面内容；`无法访问`＝站点本身报错/下线（附状态码）；`仅凭文章描述`＝被反爬拦截未能取到内容，描述只来自文章。
- 依据标记：【文】文章原文；【访】本次访问到的页面标题/描述；【通】通用设计知识/推测。「功能/场景」字段由文章内容归纳，站点描述（meta）为访问所得原文。
- 「网站自身界面」与「收录作品风格」分开记录：本轮无头浏览器截图失败，界面风格**只记录文章明确描述的**，其余标「—（未做视觉核验）」。
- 「适用场景与价值」「定位标签」「关联风格」为编者据文章原话归纳（不是站点官方分类）。

## 分类概览

| 分类（文章原分类） | 数量 |
|---|---|
| 大赛与奖项 | 12 |
| 动态设计与视频 | 14 |
| 3D 与渲染 | 9 |
| 电影画面与镜头参考 | 7 |
| UI 设计 | 16 |
| 网页灵感 | 10 |
| 前端与交互 | 16 |
| 字体与配色 | 10 |
| 日常收集灵感 | 6 |

核验统计：已访问核验 **97** ｜ 无法访问 **1** ｜ 仅凭文章描述 **2**

## 一、大赛与奖项

### 1. Pwnisher 3D 渲染挑战赛

- 链接：[https://www.youtube.com/@pwnisher](https://www.youtube.com/@pwnisher)
- 主要功能：全球 3D 渲染挑战赛，统一白模/镜头下几千人各自创作并合成长片【文】
- 内容/资源类型：视频（YouTube 频道）
- 定位标签：奖项 / 3D / 动态
- 适用场景与价值：对比学习打光、材质、叙事脑洞；3D/动态海报找画面灵感
- 收录作品风格倾向：多元：写实渲染、风格化 3D、科幻、超现实【文】
- 网站自身界面：—（未做视觉核验）
- 关联风格：S19 3D / 黏土风, S25 电影感
- 文章原话：油管博主 Clinton Jones（网名 Pwnisher）办的全球 3D 渲染比赛。玩法特别直观：他给一段定死相机轨迹和人物动作的白模，全世界几千个参赛者在这个底子上各自发挥，最后拼成一支长视频。到 2026 年已经办了 13 届。因为所有人的底子完全一样，谁的打光好、谁的脑洞大，放一起对比看得清清楚楚。
- 站点自述（访问所得 meta）：3D Challenges, Tutorials, Live Streams and Breakdowns. Let's learn and grow together!
- 来源：文章第 1 条
- 核验状态：**已访问核验** —— HTTP 200；页面标题「pwnisher - YouTube」

### 2. Awwwards

- 链接：[https://www.awwwards.com/](https://www.awwwards.com/)
- 主要功能：每日评选「今日最佳网站」，按设计/易用/创意/内容打分，年度大奖【文】
- 内容/资源类型：网站案例库、评审分
- 定位标签：奖项 / 网页 / 灵感
- 适用场景与价值：网页/落地页方向调研，每日刷新网页审美基准
- 收录作品风格倾向：创意网页：大字排版、WebGL、滚动叙事、实验交互【文+通】
- 网站自身界面：—（未做视觉核验）
- 关联风格：S29 沉浸式 WebGL/创意交互, S02 极简主义, S21 深色科技风, S13 编辑/杂志风
- 文章原话：做网页和前端绕不开的奖。每天评出一个「今日最佳网站」，评委按设计、易用性、创意、内容四项打分，年底还会选年度大奖。很适合每天早上开工前花五分钟刷一下，看看现在的网页设计又卷出了什么新花样。
- 站点自述（访问所得 meta）：Awwwards are the Website Awards that recognize and promote the talent and effort of the best developers, designers and web agencies in the world.
- 来源：文章第 2 条
- 核验状态：**已访问核验** —— HTTP 200；页面标题「Awwwards - Website Awards - Best Web Design Trends」

### 3. CSS Design Awards

- 链接：[https://www.cssdesignawards.com/](https://www.cssdesignawards.com/)
- 主要功能：网页设计奖，每日最佳站点，按 UI/UX/创新评分【文】
- 内容/资源类型：网站案例库
- 定位标签：奖项 / 网页 / 灵感
- 适用场景与价值：与 Awwwards 交叉看不同评审口味
- 收录作品风格倾向：创意网页【文】
- 网站自身界面：—（未做视觉核验）
- 关联风格：S29 沉浸式 WebGL/创意交互, S02 极简主义
- 文章原话：和 Awwwards 齐名的另一个网页大奖，也是每天推一个最佳站点，按 UI、UX、创新打分。它和 Awwwards 的评委口味不太一样，两边选出来的网站经常不重样，可以换着看。
- 站点自述（访问所得 meta）：CSS Design Awards. Be inspired, Be inspiring. Submit your website to the world
- 来源：文章第 3 条
- 核验状态：**已访问核验** —— HTTP 200；页面标题「CSS Design Awards - Website Awards - Best Web Design Inspira」

### 4. The FWA

- 链接：[https://thefwa.com/](https://thefwa.com/)
- 主要功能：2000 年起的数字设计奖，偏交互/WebGL/声音互动【文】
- 内容/资源类型：获奖项目库
- 定位标签：奖项 / 网页 / 前端代码
- 适用场景与价值：寻找技术流交互、沉浸式品牌站灵感
- 收录作品风格倾向：技术流、沉浸式、实验交互【文】
- 网站自身界面：—（未做视觉核验）
- 关联风格：S29 沉浸式 WebGL/创意交互, S26 实验/反设计
- 文章原话：2000 年就开始办的老牌数字设计奖，也是每天更新一个获奖项目。相比规规矩矩的商业排版，FWA 更喜欢选那些在交互、WebGL、声音互动上玩出花来的技术流作品。
- 站点自述（访问所得 meta）：Digital design awards since 2000. FWAi gives every entry a written critique; every award is decided by an independent human jury.
- 来源：文章第 4 条
- 核验状态：**已访问核验** —— HTTP 200；页面标题「The FWA — Digital design awards since 2000」

### 5. The Motion Awards

- 链接：[https://motionawards.com/](https://motionawards.com/)
- 主要功能：Motionographer 主办动态设计奖：片头、广告、品牌包装、纪录片、AI 单元【文】
- 内容/资源类型：获奖视频（页面内嵌成片）
- 定位标签：奖项 / 动态 / 品牌
- 适用场景与价值：一次性看完一年最佳动态作品；品牌动效/片头参考
- 收录作品风格倾向：片头、品牌动态包装【文】
- 网站自身界面：—（未做视觉核验）
- 关联风格：S25 电影感, S13 编辑/杂志风
- 文章原话：Motionographer 自己办的动态设计专项奖。片头、广告、品牌包装、纪录片各评各的，这两年还加了 AI 单元。最实在的是获奖页直接嵌着成片，不用再跳出去到处找，像《幕府将军》的片头就在里面，一个下午就能把一整年最好的动态作品刷一遍。
- 站点自述（访问所得 meta）：The 20th Anniversary Window is open. Submissions through January 15, 2027 — work published in 2025 or 2026 can both enter. The Final Stretch is open — last day 
- 来源：文章第 5 条
- 核验状态：**已访问核验** —— HTTP 200

### 6. Apple Design Awards

- 链接：[https://developer.apple.com/design/awards/](https://developer.apple.com/design/awards/)
- 主要功能：苹果 WWDC 年度设计奖，App/游戏，附官方评语【文】
- 内容/资源类型：获奖 App 案例+评语
- 定位标签：奖项 / UI/UX
- 适用场景与价值：移动端交互/视觉标杆；写设计说明时借鉴评语角度
- 收录作品风格倾向：果味：清晰层级、细腻动效、硬件特性结合【文】
- 网站自身界面：—（未做视觉核验）
- 关联风格：S28 克制产品风（Linear/Vercel 式）, S02 极简主义, S08 玻璃拟态
- 文章原话：苹果每年 WWDC 开发者大会上颁的奖。能上榜的 App 和游戏，在果味审美、交互手感和硬件特性结合上基本都是教科书级别的。苹果官方还会给每个获奖应用写一段评语，讲清楚为什么选它，做移动端的人非常值得细看。
- 站点自述（访问所得 meta）：The Apple Design Awards recognize innovation, ingenuity, and technical achievement in app and game design. Meet the winners and finalists for the 2026 Apple Des
- 来源：文章第 6 条
- 核验状态：**已访问核验** —— HTTP 200；页面标题「Apple Design Awards - 2026 winners and finalists - Apple Dev」

### 7. D&AD

- 链接：[https://www.dandad.org/](https://www.dandad.org/)
- 主要功能：英国设计与广告大奖（黄铅笔/黑铅笔）【文】
- 内容/资源类型：获奖档案
- 定位标签：奖项 / 品牌 / 平面 / 广告
- 适用场景与价值：品牌、广告、平面的顶级案例档案
- 收录作品风格倾向：广告创意、品牌识别、平面【文】
- 网站自身界面：—（未做视觉核验）
- 关联风格：S01 瑞士/国际主义风格, S13 编辑/杂志风, S02 极简主义
- 文章原话：英国的设计与广告大奖，因为奖杯造型是铅笔，国内同行一般叫它「黄铅笔奖」。它最高级别的「黑铅笔」评选极其苛刻，有些年份宁可空缺也不发，能拿下的全是能写进设计史的案子。做品牌、广告和平面的人可以多翻它的历年档案。
- 站点自述（访问所得 meta）：We stimulate, enable & celebrate creative excellence in design and commercial creativity.
- 来源：文章第 7 条
- 核验状态：**已访问核验** —— HTTP 200；页面标题「D&AD」

### 8. The One Show & ADC

- 链接：[https://www.oneclub.org/](https://www.oneclub.org/)
- 主要功能：The One Club：One Show（广告创意）与 ADC（视觉/字体/工艺）【文】
- 内容/资源类型：获奖档案
- 定位标签：奖项 / 广告 / 平面 / 字体
- 适用场景与价值：广告创意点子 + 字体排印工艺参考
- 收录作品风格倾向：广告创意；ADC 偏视觉与字体工艺【文】
- 网站自身界面：—（未做视觉核验）
- 关联风格：S01 瑞士/国际主义风格, S13 编辑/杂志风
- 文章原话：美国 The One Club 办的两个顶级大奖。One Show 更看重广告片背后的创意点子，而 1921 年创办的 ADC（纽约艺术指导俱乐部奖）更看重纯正的视觉表现、字体排印和工艺细节。
- 站点自述（访问所得 meta）：Home of The One Show, ADC Annual Awards, TDC and Young Ones. Enter global creative awards, explore winners, and join the creative community.
- 来源：文章第 8 条
- 核验状态：**已访问核验** —— HTTP 200；页面标题「The One Show & ADC Awards | Advertising & Design Awards | Th」

### 9. Runway AI Film Festival

- 链接：[https://aif.runwayml.com/](https://aif.runwayml.com/)
- 主要功能：Runway 主办 AI 影像节，短片/设计/新媒体/时尚/广告赛道，Screening Room 可看历届【文】
- 内容/资源类型：AI 视频作品
- 定位标签：奖项 / AI设计 / 动态
- 适用场景与价值：了解 AI 视频天花板；AI 视觉提案参考
- 收录作品风格倾向：AI 生成影像，风格多元【文】
- 网站自身界面：—（未做视觉核验）
- 关联风格：S25 电影感, S26 实验/反设计
- 文章原话：AI 视频工具 Runway 办的 AI 影像节，2026 年已经是第 4 届，在纽约、洛杉矶、东京都有线下放映。除了短片，还分了设计、新媒体、时尚、广告几个赛道。官网的 Screening Room 能直接看历届获奖片，想知道 AI 视频的天花板现在到了哪儿，看这里最直接。
- 站点自述（访问所得 meta）：AIF is a celebration of the art and artists embracing new and emerging AI tools for creative work. Works showcased offer a glimpse at a new creative era. One ma
- 来源：文章第 9 条
- 核验状态：**已访问核验** —— HTTP 200；页面标题「AIF 2026 | AI Festival」

### 10. Tokyo TDC

- 链接：[https://tokyotypedirectorsclub.org/](https://tokyotypedirectorsclub.org/)
- 主要功能：东京字体指导俱乐部年度奖，亚洲视觉设计风向标【文】
- 内容/资源类型：获奖海报/书籍/动态
- 定位标签：奖项 / 字体 / 平面
- 适用场景与价值：实验海报、字体海报、书籍设计灵感；东亚审美参考
- 收录作品风格倾向：强实验性字体与海报【文】
- 网站自身界面：—（未做视觉核验）
- 关联风格：S26 实验/反设计, S01 瑞士/国际主义风格, S14 日式/无印风
- 文章原话：东京字体指导俱乐部的年度奖。虽然名字里带「字体」，但它其实是整个亚洲视觉设计圈的风向标。评委眼光非常刁钻，获奖的海报、书籍和动态视觉大多带有很强的实验性，看腻了四平八稳的商业稿，去这儿洗洗眼睛特别好。
- 站点自述（访问所得 meta）：東京タイプディレクターズクラブ
- 来源：文章第 10 条
- 核验状态：**已访问核验** —— HTTP 200；页面标题「Tokyo TDC」

### 11. Annecy 安纳西国际动画节

- 链接：[https://www.annecyfestival.com/](https://www.annecyfestival.com/)
- 主要功能：1960 年创办的法国安纳西国际动画节，含商业委托单元【文】
- 内容/资源类型：动画作品/节展信息
- 定位标签：奖项 / 动态 / 插画
- 适用场景与价值：动画美术风格、MV/广告动画叙事参考
- 收录作品风格倾向：动画美术风格多元【文】
- 网站自身界面：—（未做视觉核验）
- 关联风格：S18 有机/手绘, S23 可爱/卡哇伊
- 文章原话：1960 年创办的法国动画节，动画人眼里的最高殿堂。除了动画长片和独立短片，它还有专门的商业委托单元（广告、MV、片头），能看到全世界最好的一批美术风格和动态叙事。
- 站点自述（访问所得 meta）：Site officiel du Festival et du Marché (Mifa) international du film d'animation d'Annecy : le rendez-vous mondial de plus de 12 000 professionnels
- 来源：文章第 11 条
- 核验状态：**已访问核验** —— HTTP 200；页面标题「Site officiel du Festival et du Marché international du film」

### 12. Ciclope Festival

- 链接：[https://www.ciclopefestival.com/](https://www.ciclopefestival.com/)
- 主要功能：按工种（导演/摄影/调色/剪辑/3D/VFX/配乐）发奖的影视广告节【文】
- 内容/资源类型：获奖影片
- 定位标签：奖项 / 动态 / 摄影/电影
- 适用场景与价值：单项研究调色、剪辑节奏、摄影
- 收录作品风格倾向：商业影像工艺【文】
- 网站自身界面：—（未做视觉核验）
- 关联风格：S25 电影感
- 文章原话：一个专门按「工种」发奖的影视广告节。别的奖大多看整体创意，它偏偏把片子拆开：导演、摄影、调色、剪辑、三维动画、视觉特效、配乐各评各的奖。做视频的人如果想单拎出「调色」或「剪辑节奏」来研究，看这个奖最对路。
- 站点自述（访问所得 meta）：Home to those who believe in the power of craft. The 2026 edition of CICLOPE Festival and Awards takes place 6 - 8 October in Berlin.
- 来源：文章第 12 条
- 核验状态：**已访问核验** —— HTTP 200；页面标题「CICLOPE Festival」

## 二、动态设计与视频

### 13. Motionographer

- 链接：[https://motionographer.com/](https://motionographer.com/)
- 主要功能：近二十年的动态设计媒体，精选作品+幕后手记【文】
- 内容/资源类型：文章、视频
- 定位标签：动态 / 灵感 / 品牌
- 适用场景与价值：动态设计灵感与制作拆解
- 收录作品风格倾向：动态设计、动画、VFX【文+访】
- 网站自身界面：—（未做视觉核验）
- 关联风格：S25 电影感, S19 3D / 黏土风
- 文章原话：动态设计圈办了快二十年的老牌网站。编辑挑片子的眼光很毒，平时不乱发水文，一旦更新基本都是值得反复拉片的好作品，还经常顺带放出工作室写的幕后制作手记。
- 站点自述（访问所得 meta）：Motionographer shares inspiring work and important news for the Motion Design, animation and visual effects communities.
- 来源：文章第 13 条
- 核验状态：**已访问核验** —— HTTP 200；页面标题「Motionographer® Unexpected Inspiration™」

### 14. STASH（付费/部分付费，据文章）

- 链接：[https://www.stashmedia.tv/](https://www.stashmedia.tv/)
- 主要功能：付费在线片库：动画、VFX、动态设计，附 Making-of【文】
- 内容/资源类型：视频库（付费）
- 定位标签：动态 / 3D / 品牌
- 适用场景与价值：商业广告/MV/频道包装参考，看制作花絮
- 收录作品风格倾向：商业动态、频道包装【文+访】
- 网站自身界面：—（未做视觉核验）
- 关联风格：S19 3D / 黏土风, S25 电影感
- 文章原话：很多动画和视效工作室都会订的在线片库（付费）。里面按风格和技法归档了成千上万支商业广告、MV 和频道包装，最大的价值是很多片子附带了制作花絮（Making-of）和工程拆解。
- 站点自述（访问所得 meta）：Welcome to the planet’s largest online library of animation, VFX and motion design.
- 来源：文章第 14 条
- 核验状态：**已访问核验** —— HTTP 200；页面标题「Motion design - STASH - Welcome to the planet’s largest onli」

### 15. Art of the Title

- 链接：[https://www.artofthetitle.com/](https://www.artofthetitle.com/)
- 主要功能：研究电影/剧集/游戏片头设计，附主创长访谈与草图【文】
- 内容/资源类型：视频+长文
- 定位标签：动态 / 字体 / 摄影/电影
- 适用场景与价值：片头设计、动态字体、叙事型品牌片
- 收录作品风格倾向：片头设计：字体动效、隐喻图形【文】
- 网站自身界面：—（未做视觉核验）
- 关联风格：S25 电影感, S13 编辑/杂志风
- 文章原话：专门研究电影、剧集和游戏「片头设计」的网站。它不光放高清片头视频，最下功夫的是长篇主创专访——把导演和设计师请来，把最初的草图、废稿、分镜脚本全摆出来，一步步讲这短短两分钟的片头是怎么磨出来的。
- 来源：文章第 15 条
- 核验状态：**已访问核验** —— HTTP 200；页面标题「Art of the Title」

### 16. Vimeo Staff Picks

- 链接：[https://vimeo.com/channels/staffpicks](https://vimeo.com/channels/staffpicks)
- 主要功能：Vimeo 编辑每日人工精选短片【文】
- 内容/资源类型：短片
- 定位标签：动态 / 摄影/电影 / 灵感
- 适用场景与价值：实拍短片、实验动画参考
- 收录作品风格倾向：实拍、实验动画、纪录片【文+访】
- 网站自身界面：—（未做视觉核验）
- 关联风格：S25 电影感, S26 实验/反设计
- 文章原话：Vimeo 编辑部每天人工挑出来的短片频道。在视频圈子里，自己的作品能挂上一枚 Staff Pick 的标志是挺值得吹一辈子的事。不管是实拍短片、实验动画还是纪录片，水准都非常稳。
- 站点自述（访问所得 meta）：The best short films on the internet, handpicked by Vimeo staff
- 来源：文章第 16 条
- 核验状态：**已访问核验** —— HTTP 200；页面标题「Vimeo Staff Picks on Vimeo」

### 17. Behance 动态设计专区

- 链接：[https://www.behance.net/galleries/motion](https://www.behance.net/galleries/motion)
- 主要功能：Behance 动态设计分类，常含情绪板、风格帧、Animatic【文】
- 内容/资源类型：项目案例
- 定位标签：动态 / 品牌 / 灵感
- 适用场景与价值：学习完整交稿流程：情绪板→风格帧→成片
- 收录作品风格倾向：多元【文】
- 网站自身界面：—（未做视觉核验）
- 关联风格：S19 3D / 黏土风, S20 渐变/极光
- 文章原话：虽然大家平时都在刷 Behance，但它的 Motion 分类尤其适合拿来学工作流。因为很多工作室在上面发项目时，会把前期的情绪板、风格帧（Styleframes）、动态分镜（Animatic）和最终成片一块儿放出来，相当于把整个交稿过程摊开给你看。
- 来源：文章第 17 条
- 核验状态：**仅凭文章描述** —— HTTP 403（反爬拦截；WebFetch 亦失败：Behance 超时 / ArtStation 500）

### 18. Short of the Week

- 链接：[https://www.shortoftheweek.com/](https://www.shortoftheweek.com/)
- 主要功能：推荐全球独立短片，附编辑影评【文】
- 内容/资源类型：短片+影评
- 定位标签：动态 / 摄影/电影
- 适用场景与价值：叙事、人物塑造参考
- 收录作品风格倾向：实拍与动画短片【文+访】
- 网站自身界面：—（未做视觉核验）
- 关联风格：S25 电影感
- 文章原话：专门推荐全球优秀独立短片的网站，实拍和动画都有。每部片子下面都配了一篇编辑写的正经影评，帮你拆解导演是怎么在十几分钟里立住人物、讲完一个好故事的。
- 站点自述（访问所得 meta）：Watch the most innovative stories—Documentary, Comedy, Sci-fi, Horror, Experimental, Animation, Inspiration, Student films, Award winners & more short films
- 来源：文章第 18 条
- 核验状态：**已访问核验** —— HTTP 200；页面标题「Short of the Week | The Best Short Films」

### 19. Directors Notes

- 链接：[https://directorsnotes.com/](https://directorsnotes.com/)
- 主要功能：独立导演访谈博客：预算、器材、后期【文】
- 内容/资源类型：访谈文章、短片
- 定位标签：摄影/电影 / 动态
- 适用场景与价值：拍摄/制作经验参考
- 收录作品风格倾向：独立电影【文+访】
- 网站自身界面：—（未做视觉核验）
- 关联风格：S25 电影感
- 文章原话：一个做独立导演访谈的博客。每次聊一部短片，问的问题都很实在：当时怎么凑的钱、现场用的什么机器和镜头、后期遇到了什么麻烦。自己平时接片子、拍东西的人看这个会很有共鸣。
- 站点自述（访问所得 meta）：Watch the world's best independent films and & discover how they were made: Animation, Live Action, Documentary, Music Video, Branded, Fashion, Experimental.
- 来源：文章第 19 条
- 核验状态：**已访问核验** —— HTTP 200；页面标题「Directors Notes // The Home of Independent Filmmaking」

### 20. Sakugabooru

- 链接：[https://www.sakugabooru.com/](https://www.sakugabooru.com/)
- 主要功能：动画「作画」片段库，32 万+条带原画师/作品/效果标签【文】
- 内容/资源类型：动画片段（GIF/视频）
- 定位标签：动态 / 插画
- 适用场景与价值：研究动作节奏/弹性；AI 动作镜头参考
- 收录作品风格倾向：日本动画作画【文+访】
- 网站自身界面：—（未做视觉核验）
- 关联风格：S23 可爱/卡哇伊, S18 有机/手绘
- 文章原话：动画迷自己维护的「作画」片段库，存了 32 万多条从动画里剪出来的高光片段。每条都打好了标签：哪位原画师画的、出自哪部作品、是爆炸特效还是角色表演。想研究一个动作的节奏和弹性，搜标签就能拉出几百个片段逐帧看，做动画的人和用 AI 生成动作镜头的人都用得上。
- 站点自述（访问所得 meta）：sakugabooru - a booru dedicated to sakuga videos and images
- 来源：文章第 20 条
- 核验状态：**已访问核验** —— HTTP 200；页面标题「sakugabooru」

### 21. Promonews

- 链接：[https://www.promonews.tv/](https://www.promonews.tv/)
- 主要功能：每日精选 MV/广告片，附导演创作说明【文】
- 内容/资源类型：视频+文章
- 定位标签：动态 / 摄影/电影
- 适用场景与价值：风格化镜头、色彩、剪辑节奏参考
- 收录作品风格倾向：MV：风格化、敢玩的色彩与剪辑【文+访】
- 网站自身界面：—（未做视觉核验）
- 关联风格：S25 电影感, S17 酸性设计, S07 Y2K / 千禧复古
- 文章原话：每天精选几支新出的 MV 和广告片，大多配着导演的创作说明：用什么机器拍的、为什么这么调色、某个镜头是怎么做出来的。MV 是风格化镜头、色彩和剪辑节奏最敢玩的地方，想找视觉风格参考，刷这里比在视频网站上大海捞针高效得多。
- 站点自述（访问所得 meta）：Music video creativity every day.  The latest, best and most inspiring music videos every day, interviews with music video directors, and much more. Your daily 
- 来源：文章第 21 条
- 核验状态：**已访问核验** —— HTTP 200；页面标题「Music video creativity everyday | Promonews」

### 22. BUCK

- 链接：[https://buck.co/](https://buck.co/)
- 主要功能：BUCK 工作室官网，2D/3D/实拍全能【文】
- 内容/资源类型：作品集
- 定位标签：动态 / 品牌 / 插画 / 3D
- 适用场景与价值：品牌动态、插画动画、3D 案例
- 收录作品风格倾向：多元、品牌插画与 3D【文】
- 网站自身界面：—（未做视觉核验）
- 关联风格：S18 有机/手绘, S19 3D / 黏土风, S10 扁平设计
- 文章原话：全球规模和名气最大的动态设计工作室之一，苹果、耐克、Meta 的常客。2D、3D、实拍结合全能，作品集大得像个博物馆。
- 站点自述（访问所得 meta）：BUCK is a global creative company that brings brands, stories, and experiences to life through art, design, and technology.
- 来源：文章第 22 条
- 核验状态：**已访问核验** —— HTTP 200；页面标题「BUCK」

### 23. ManvsMachine

- 链接：[https://mvsm.com/](https://mvsm.com/)
- 主要功能：ManvsMachine 伦敦创意工作室，三维材质碰撞、产品广告【文】
- 内容/资源类型：作品集
- 定位标签：3D / 动态 / 品牌
- 适用场景与价值：高端产品 3D 广告/KV 参考
- 收录作品风格倾向：硬核产品渲染、光影质感【文】
- 网站自身界面：—（未做视觉核验）
- 关联风格：S19 3D / 黏土风, S22 奢华/高端, S21 深色科技风
- 文章原话：伦敦的顶尖创意工作室，尤其擅长做三维材质碰撞和硬核产品广告，画面的光影质感好到让人头皮发麻。
- 站点自述（访问所得 meta）：ManvsMachine — Design & Direction Co.
- 来源：文章第 23 条
- 核验状态：**已访问核验** —— HTTP 200；页面标题「ManvsMachine」

### 24. Oddfellows

- 链接：[https://oddfellows.tv/](https://oddfellows.tv/)
- 主要功能：Oddfellows 美国工作室，插画风 2D 角色动画【文】
- 内容/资源类型：作品集
- 定位标签：动态 / 插画 / 品牌
- 适用场景与价值：扁平插画动画、品牌讲解片
- 收录作品风格倾向：插画风 2D、舒服配色【文】
- 网站自身界面：—（未做视觉核验）
- 关联风格：S10 扁平设计, S18 有机/手绘
- 文章原话：美国工作室，主打插画风和 2D 角色动画，配色极其舒服，镜头衔接和动作惯性做得丝滑无比。
- 来源：文章第 24 条
- 核验状态：**已访问核验** —— HTTP 000；首次 TLS 握手失败，重试 200 正常

### 25. Golden Wolf

- 链接：[https://www.goldenwolf.tv/](https://www.goldenwolf.tv/)
- 主要功能：Golden Wolf 伦敦动画工作室，高饱和撞色街头卡通【文】
- 内容/资源类型：作品集
- 定位标签：动态 / 插画
- 适用场景与价值：潮流/年轻品牌动画，社媒视频
- 收录作品风格倾向：高饱和撞色、夸张透视、快剪辑街头卡通【文】
- 网站自身界面：—（未做视觉核验）
- 关联风格：S27 街头潮流卡通, S06 孟菲斯, S17 酸性设计
- 文章原话：伦敦动画工作室，风格极好认——高饱和撞色、夸张的透视变形、快到飞起的剪辑节奏，满屏都是精力旺盛的街头卡通感。
- 站点自述（访问所得 meta）：Golden Wolf - Award-winning animation studio creating compelling content for global brands. Based in London and New York.
- 来源：文章第 25 条
- 核验状态：**已访问核验** —— HTTP 200；页面标题「Golden Wolf」

### 26. Ordinary Folk

- 链接：[https://www.ordinaryfolk.co/](https://www.ordinaryfolk.co/)
- 主要功能：Ordinary Folk 温哥华团队，2D 几何图形动效【文】
- 内容/资源类型：作品集
- 定位标签：动态 / 品牌
- 适用场景与价值：几何动态图形、科技品牌讲解动画
- 收录作品风格倾向：2D 几何、弹性运动曲线【文+访】
- 网站自身界面：—（未做视觉核验）
- 关联风格：S10 扁平设计, S05 包豪斯
- 文章原话：温哥华的团队，专门把基础的 2D 几何图形玩出花来，运动曲线的弹性和节奏感拿捏得死死的。
- 站点自述（访问所得 meta）：Vancouver motion design studio making motion graphics, explainer animation, brand videos, 2D and character animation for Google, Webflow and TED.
- 来源：文章第 26 条
- 核验状态：**已访问核验** —— HTTP 200；页面标题「Ordinary Folk – Motion Design & Animation Studio, Vancouver」

## 三、3D 与渲染

### 27. ArtStation

- 链接：[https://www.artstation.com/](https://www.artstation.com/)
- 主要功能：CG/游戏美术作品社区【文】
- 内容/资源类型：作品集社区
- 定位标签：3D / 插画 / 游戏
- 适用场景与价值：概念设计、3D 资产、角色/场景参考
- 收录作品风格倾向：CG、概念设计、游戏美术【文】
- 网站自身界面：—（未做视觉核验）
- 关联风格：S19 3D / 黏土风, S16 赛博朋克, S25 电影感
- 文章原话：干 CG 和游戏美术的人每天开机必逛的地方。全球各大游戏厂、影视视效公司的原画师、建模师、灯光师基本都在这儿安家，搜任何风格的概念设计或三维资产都能找到最顶级的参考。
- 来源：文章第 27 条
- 核验状态：**仅凭文章描述** —— HTTP 403（反爬拦截；WebFetch 亦失败：Behance 超时 / ArtStation 500）

### 28. The Rookies

- 链接：[https://www.therookies.co/](https://www.therookies.co/)
- 主要功能：面向学生/新人的年度比赛社区【文】
- 内容/资源类型：作品集、比赛
- 定位标签：3D / 游戏 / 动态
- 适用场景与价值：了解行业新人作品水准
- 收录作品风格倾向：3D、游戏、VFX、概念设计【文+访】
- 网站自身界面：—（未做视觉核验）
- 关联风格：S19 3D / 黏土风
- 文章原话：专门给全球相关专业大学生和入行新人办的年度比赛社区，分 3D 动画、游戏开发、视觉特效、概念设计好几个赛道。刚学软件或者准备找工作的人可以去翻翻，看看现在的应届生作品集都已经卷到什么地步了。
- 站点自述（访问所得 meta）：Join The Rookies: The premier community for budding artists across digital art, design, media, and more. Discover opportunities, gain support, and showcase your
- 来源：文章第 28 条
- 核验状态：**已访问核验** —— HTTP 200；页面标题「The Rookies - Creative Community for Next-Gen Artists | Digi」

### 29. 80 Level

- 链接：[https://80.lv/](https://80.lv/)
- 主要功能：游戏美术与三维技术媒体，Breakdown 制作拆解【文】
- 内容/资源类型：文章
- 定位标签：3D / 游戏 / 教程
- 适用场景与价值：学三维场景制作流程
- 收录作品风格倾向：游戏场景、写实/风格化 3D【文+访】
- 网站自身界面：—（未做视觉核验）
- 关联风格：S19 3D / 黏土风, S16 赛博朋克
- 文章原话：专聊游戏美术和三维技术的媒体。这个站最值得看的是它的 Breakdown（制作拆解）文章：请原作者出面，把一个复杂的三维场景拆开，从用什么软件建白模、怎么在 Substance 里刷脏迹，到怎么在引擎里摆灯光，写得跟操作手册一样细。
- 站点自述（访问所得 meta）：80 LEVEL is an industry-leading platform for game developers,, digital artists, animators, video game enthusiasts, CGI and VFX specialists. Join us to learn abo
- 来源：文章第 29 条
- 核验状态：**已访问核验** —— HTTP 200；页面标题「80 Level」

### 30. Sketchfab

- 链接：[https://sketchfab.com/](https://sketchfab.com/)
- 主要功能：网页 360° 查看 3D 模型，可切线框/法线等通道【文】
- 内容/资源类型：3D 模型（部分可下载）
- 定位标签：3D / 素材资源
- 适用场景与价值：研究模型布线/UV；3D 资产参考
- 收录作品风格倾向：多元 3D 模型【文+访】
- 网站自身界面：—（未做视觉核验）
- 关联风格：S19 3D / 黏土风
- 文章原话：直接在网页上 360 度转着看 3D 模型的平台。遇到做得好的模型，点一下右下角的查看器设置，就能直接切到纯白模、线框（Wireframe）、法线贴图或者粗糙度通道——别人模型是怎么布线的、UV 怎么拆的，扒得干干净净。
- 站点自述（访问所得 meta）：With a community of over one million creators, we are the world’s largest platform to publish, share, and discover 3D content on web, mobile, AR, and VR.
- 来源：文章第 30 条
- 核验状态：**已访问核验** —— HTTP 200；页面标题「Sketchfab - The best 3D viewer on the web」

### 31. befores & afters

- 链接：[https://beforesandafters.com/](https://beforesandafters.com/)
- 主要功能：好莱坞视效幕后杂志，前后对比图+访谈【文】
- 内容/资源类型：文章
- 定位标签：3D / 摄影/电影
- 适用场景与价值：了解 VFX 合成流程
- 收录作品风格倾向：影视 VFX【文+访】
- 网站自身界面：—（未做视觉核验）
- 关联风格：S25 电影感
- 文章原话：专门扒好莱坞大片视效幕后的在线杂志。文章最爱放特效前后的对比图：左边是演员穿着动作捕捉服站在绿幕前，右边是合成完的爆炸场面，同时配着视效总监的采访，讲清楚这场戏到底是怎么借位和合成的。
- 站点自述（访问所得 meta）：Visual effects and animation magazine from journalist Ian Failes.
- 来源：文章第 31 条
- 核验状态：**已访问核验** —— HTTP 200；页面标题「befores & afters - VFX magazine」

### 32. fxguide

- 链接：[https://www.fxguide.com/](https://www.fxguide.com/)
- 主要功能：资深影视视效技术媒体【文】
- 内容/资源类型：文章
- 定位标签：3D / 摄影/电影 / 教程
- 适用场景与价值：渲染/虚拟制片/流体技术深挖
- 收录作品风格倾向：技术向【文+访】
- 网站自身界面：—（未做视觉核验）
- 关联风格：S25 电影感
- 文章原话：圈内资历最老的影视视效技术媒体。文章写得非常硬核，不聊八卦，专门深挖渲染器底层算法、虚拟制片 LED 棚管线、流体解算技术，适合想往技术美术（TA）或视效深水区走的人。
- 站点自述（访问所得 meta）：fxguide is the leading in-depth news source for the visual effects industry. Founded in 1999, it keeps vfx artists up to date on the latest trends and tech.
- 来源：文章第 32 条
- 核验状态：**已访问核验** —— HTTP 200；页面标题「fxguide」

### 33. Blender Studio（付费/部分付费，据文章）

- 链接：[https://studio.blender.org/](https://studio.blender.org/)
- 主要功能：Blender 官方开源动画工作室（付费），教程+工程文件【文】
- 内容/资源类型：教程、工程文件（付费）
- 定位标签：3D / 教程 / 素材资源
- 适用场景与价值：学 Blender 全流程、拆角色绑定/灯光工程
- 收录作品风格倾向：风格化 3D 动画【文+访】
- 网站自身界面：—（未做视觉核验）
- 关联风格：S19 3D / 黏土风
- 文章原话：Blender 官方自己的开源动画工作室（付费）。官方团队每年都会用 Blender 做一部高质量动画短片来测试软件极限，订阅之后不仅能看教程，还能把他们做片子用的角色绑定、灯光工程文件直接下到自己电脑里打开研究。
- 站点自述（访问所得 meta）：Blender Studio is a web service that provides access the training videos and all the data from the Blender open projects.
- 来源：文章第 33 条
- 核验状态：**已访问核验** —— HTTP 200；页面标题「Blender Studio」；跳转至 /welcome/

### 34. Poly Haven

- 链接：[https://polyhaven.com/](https://polyhaven.com/)
- 主要功能：CC0 免费 HDRI、PBR 材质、扫描模型【文】
- 内容/资源类型：3D 素材（免费 CC0）
- 定位标签：3D / 素材资源
- 适用场景与价值：3D 渲染、产品图、海报 3D 元素的免费底材
- 收录作品风格倾向：写实 PBR 素材【文+访】
- 网站自身界面：—（未做视觉核验）
- 关联风格：S19 3D / 黏土风
- 文章原话：做三维渲染必存的良心资源站。里面的高清 HDRI 环境光贴图、PBR 材质球和扫描模型全部采用 CC0 协议——意思是完全免费、不用注册就能直接下载，拿去接商业私活也不用署名。
- 站点自述（访问所得 meta）：The Public 3D Asset Library
- 来源：文章第 34 条
- 核验状态：**已访问核验** —— HTTP 200；页面标题「Poly Haven」

### 35. Beeple Everydays

- 链接：[https://beeple-crap.com/everydays](https://beeple-crap.com/everydays)
- 主要功能：Beeple 自 2007-05-01 起每日一图的 Everydays 档案【文】
- 内容/资源类型：数字艺术作品
- 定位标签：3D / 灵感 / AI设计
- 适用场景与价值：观察长期练习成长；科幻/超现实 3D 灵感
- 收录作品风格倾向：超现实、科幻、讽刺数字艺术【文】
- 网站自身界面：—（未做视觉核验）
- 关联风格：S16 赛博朋克, S19 3D / 黏土风, S26 实验/反设计
- 文章原话：数字艺术家 Beeple 从 2007 年 5 月 1 日那天起，逼自己每天做一张图传上网，结婚、生病、过年一天都没断过，就这么连着画了快二十年。你如果往前翻他头两年的图，会发现画得也挺糙的，但一页页往后翻，能亲眼看到一个普通人是怎么靠每天交作业硬生生把自己练成大神的。
- 站点自述（访问所得 meta）：A picture every day since May 1, 2007. Explore the Everydays project and artwork archive by Beeple.
- 来源：文章第 35 条
- 核验状态：**已访问核验** —— HTTP 200；页面标题「Everydays | BEEPLE」

## 四、电影画面与镜头参考

### 36. ShotDeck（付费/部分付费，据文章）

- 链接：[https://shotdeck.com/](https://shotdeck.com/)
- 主要功能：专业电影截图库（付费），标签极细【文】
- 内容/资源类型：电影截图（付费）
- 定位标签：摄影/电影 / 灵感
- 适用场景与价值：分镜、调色、电影感 KV/海报参考
- 收录作品风格倾向：电影画面【文+访】
- 网站自身界面：—（未做视觉核验）
- 关联风格：S25 电影感
- 文章原话：《小丑》《宿醉》的摄影指导 Lawrence Sher 带头做出来的专业电影截图库（付费）。图库极其庞大，而且每张图的标签打得细到离谱：你可以直接筛选「黄金时刻 + 逆光 + 广角镜头 + 冷色调 + 车内景」，一秒钟就能拉出几十张完全符合要求的电影画面拿去做分镜参考。
- 来源：文章第 36 条
- 核验状态：**已访问核验** —— curl 403（Cloudflare 验证页）→ WebFetch 取到正文：「The library of cinematic imagery」，150 万+ 可搜索镜头

### 37. FILMGRAB

- 链接：[https://film-grab.com/](https://film-grab.com/)
- 主要功能：免费电影截图站，每部电影 50–60 张关键帧【文】
- 内容/资源类型：电影截图
- 定位标签：摄影/电影 / 配色
- 适用场景与价值：研究导演构图与用光、提取电影配色
- 收录作品风格倾向：电影画面【文】
- 网站自身界面：—（未做视觉核验）
- 关联风格：S25 电影感
- 文章原话：完全免费的电影截图网站，收了几千部经典电影。它的整理方式很纯粹：一部电影就是一个单独的页面，里面整整齐齐摆着从片中挑出来的五六十张高清关键帧。想研究某位导演的用光和构图习惯，点进一页从头划到底就全明白了。
- 来源：文章第 37 条
- 核验状态：**已访问核验** —— HTTP 200；页面标题「[FILMGRAB]」

### 38. StillsLab

- 链接：[https://stillslab.com/](https://stillslab.com/)
- 主要功能：免费影视截图库，可按景别/机位/光线/色彩/器材筛选，附视觉统计【文】
- 内容/资源类型：影视截图
- 定位标签：摄影/电影 / 配色
- 适用场景与价值：分镜参考、电影感视觉配方分析
- 收录作品风格倾向：电影/剧集/MV/广告画面【文+访】
- 网站自身界面：—（未做视觉核验）
- 关联风格：S25 电影感
- 文章原话：免费的影视截图库，电影、剧集、MV、广告都有，不付钱也能看全库。标签打得很细，可以按景别、机位角度、光线、色彩、日景夜景，甚至用的什么摄影机和镜头来筛，也能直接敲一句大白话描述画面去搜。每部片子的页面还会给出统计，比如《银翼杀手 2049》里夜景占 69%、柔光占 52%，研究一部片子的视觉配方特别方便。
- 站点自述（访问所得 meta）：Discover high-quality movie stills, film frames & TV screenshots for filmmakers. Perfect for cinematography references, shot lists, and mood boards.
- 来源：文章第 38 条
- 核验状态：**已访问核验** —— HTTP 200；页面标题「StillsLab — Movie Stills & TV Show Frames for Filmmakers」

### 39. Flim

- 链接：[https://flim.ai/](https://flim.ai/)
- 主要功能：AI 语义搜索影视截图库（200 万+帧）【文】
- 内容/资源类型：影视截图
- 定位标签：摄影/电影 / AI设计
- 适用场景与价值：用自然语言找镜头，做情绪板
- 收录作品风格倾向：电影感画面【文+访】
- 网站自身界面：—（未做视觉核验）
- 关联风格：S25 电影感
- 文章原话：接了 AI 语义搜索的影视截图库，除了电影还收了不少 MV 和商业广告。最好用的一点是不需要记片名，直接在搜索框里敲一句大白话（比如「一个人站在走廊尽头背光」或者「俯拍餐桌上的食物」），就能把各个片子里的类似镜头全搜出来。
- 站点自述（访问所得 meta）：Search over 2 million frames from films, series, ads and music videos by mood, colour or era. Build boards and generate cinematic images in one place.
- 来源：文章第 39 条
- 核验状态：**已访问核验** —— HTTP 200；页面标题「Flim | AI search engine for film stills and visual reference」；站点称 200 万+ 帧

### 40. EyeCannndy

- 链接：[https://eyecannndy.com/](https://eyecannndy.com/)
- 主要功能：镜头语言与剪辑技法动图词典【文】
- 内容/资源类型：GIF 词典
- 定位标签：动态 / 摄影/电影 / 教程
- 适用场景与价值：学转场/运镜名称，写 AI 视频提示词
- 收录作品风格倾向：技法向【文+访】
- 网站自身界面：—（未做视觉核验）
- 关联风格：S25 电影感
- 文章原话：一个把「镜头语言和剪辑手法」做成动图词典的网站。看到好看的转场或运镜叫不出名字很正常，这里把匹配剪辑（Match Cut）、希区柯克变焦、鞭甩转场、第一人称视角等几十种常见技法全列了出来，点开一个词条，直接给你看五六个不同广告和MV里的动图实例。
- 站点自述（访问所得 meta）：The visual technique library for visual technique lovers. Enjoy. Learn. Don
- 来源：文章第 40 条
- 核验状态：**已访问核验** —— HTTP 200；页面标题「Eyecandy - Visual Technique Library」

### 41. StudioBinder 镜头语言指南

- 链接：[https://www.studiobinder.com/blog/ultimate-guide-to-camera-shots/](https://www.studiobinder.com/blog/ultimate-guide-to-camera-shots/)
- 主要功能：StudioBinder 镜头景别/机位/运镜系统教程【文】
- 内容/资源类型：教程文章
- 定位标签：摄影/电影 / 教程 / AI设计
- 适用场景与价值：查镜头术语写 AI 视频提示词
- 收录作品风格倾向：技法向【文+访】
- 网站自身界面：—（未做视觉核验）
- 关联风格：S25 电影感
- 文章原话：一家做制片软件的公司写的系列教程，把景别、机位角度、运镜方式（推拉、摇移、甩镜头、环绕）一种一种讲清楚，每一种都配了电影里的实例。审美高度一般，但胜在系统、好查。用 AI 生成视频时，提示词里写「low angle」「dolly in」「whip pan」比写「拍得高级一点」管用得多，这些词在这里都能查到。
- 站点自述（访问所得 meta）：A complete guide to types of shots and angles in film, including shot size, camera angle, framing, focal length, and camera movement.
- 来源：文章第 41 条
- 核验状态：**已访问核验** —— HTTP 200；页面标题「50+ Types of Camera Shots, Angles, and Techniques」

### 42. American Cinematographer

- 链接：[https://theasc.com/](https://theasc.com/)
- 主要功能：美国电影摄影师协会杂志，摄影指导讲拍摄【文】
- 内容/资源类型：文章（部分免费）
- 定位标签：摄影/电影 / 教程
- 适用场景与价值：理解电影感背后的布光/镜头选择
- 收录作品风格倾向：电影摄影【文+访】
- 网站自身界面：—（未做视觉核验）
- 关联风格：S25 电影感
- 文章原话：美国电影摄影师协会（ASC）办了一百多年的杂志。上面的文章大多是摄影指导亲自讲一部片子：为什么选这套镜头、用的什么机器、主光从哪儿打、调色怎么定。截图库告诉你画面长什么样，这里告诉你为什么这么拍。不少文章在官网免费就能读全文。
- 站点自述（访问所得 meta）：Act now to receive 11 issues of the award-winning American Cinematographer — the world’s finest cinematography resource.
- 来源：文章第 42 条
- 核验状态：**已访问核验** —— HTTP 200；页面标题「Home - The ASC」

## 五、UI 设计

### 43. Mobbin（付费/部分付费，据文章）

- 链接：[https://mobbin.com/](https://mobbin.com/)
- 主要功能：真实 App/Web 截图库（60 万+张，付费为主）【文】
- 内容/资源类型：UI 截图、流程
- 定位标签：UI/UX / 灵感
- 适用场景与价值：画具体功能页（订阅页/空状态）对比大厂做法
- 收录作品风格倾向：主流 App 真实 UI【文+访】
- 网站自身界面：—（未做视觉核验）
- 关联风格：S28 克制产品风（Linear/Vercel 式）, S10 扁平设计, S02 极简主义
- 文章原话：目前最好用的真实 App 截图库（付费，免费号能看一部分）。团队把海外大量主流 iOS、Android 和 Web 应用从头到尾截了个遍，攒了 60 多万张界面。当你要画一个「订阅付费页」或者「空状态提醒」时，直接上去筛这个功能标签，就能把 Airbnb、Spotify、Notion 的做法并排摆在一起对比。
- 站点自述（访问所得 meta）：Save hours of UI & UX research with our library of over 600,000 fully searchable mobile & web app screenshots.
- 来源：文章第 43 条
- 核验状态：**已访问核验** —— HTTP 200；页面标题「Mobbin — UI & UX design inspiration for mobile & web apps」；站点称 60 万+ 截图（与文章一致）

### 44. Page Flows（付费/部分付费，据文章）

- 链接：[https://pageflows.com/](https://pageflows.com/)
- 主要功能：真实产品操作录屏库（付费）【文】
- 内容/资源类型：用户流程录屏
- 定位标签：UI/UX
- 适用场景与价值：梳理注册/付费/取消等交互流程
- 收录作品风格倾向：主流产品真实流程【文+访】
- 网站自身界面：—（未做视觉核验）
- 关联风格：S28 克制产品风（Linear/Vercel 式）
- 文章原话：Mobbin 看的是静态截图，而这个站存的全是真实产品的操作录屏（付费）。从新用户点开落地页、注册账号、绑卡付钱，一直到最后怎么找入口取消订阅，全程带着鼠标点击轨迹和页面跳转录下来，做交互流程梳理的时候极其省事。
- 站点自述（访问所得 meta）：Explore 100,000+ recorded user flows, app screens, and UI patterns from Airbnb, Uber, Netflix & more. Save hours on UX research with Page Flows.
- 来源：文章第 44 条
- 核验状态：**已访问核验** —— HTTP 200；页面标题「UI/UX Design Inspiration & User Flows from Top Apps — Page F」

### 45. Refero（付费/部分付费，据文章）

- 链接：[https://refero.design/](https://refero.design/)
- 主要功能：Web/iOS 界面截图库（付费），组件标签细；免费子站 styles.refero.design 提供 DESIGN.md【文】
- 内容/资源类型：UI 截图、DESIGN.md
- 定位标签：UI/UX / 网页 / AI设计
- 适用场景与价值：找细分组件参考；把真实网站风格喂给 AI
- 收录作品风格倾向：真实网站/App UI【文+访】
- 网站自身界面：—（未做视觉核验）
- 关联风格：S28 克制产品风（Linear/Vercel 式）, S02 极简主义
- 文章原话：专注 Web 网页端和 iOS 端的界面截图库（付费）。它的组件和页面类型标签切得非常碎，比如想单看别人怎么设计「表格筛选器」「面包屑导航」或者「价格对比表」，搜起来很准。它还有个免费子站 styles.refero.design，把两千多个真实网站的配色、字体、间距整理成了 AI 能直接读的 DESIGN.md，不登录就能看。
- 站点自述（访问所得 meta）：The largest collection of UI/UX references and design inspiration for web and iOS. Explore tens of thousands of screenshots with advanced search capabilities
- 来源：文章第 45 条
- 核验状态：**已访问核验** —— HTTP 200；页面标题「Refero — UI/UX Design Inspiration for Your Next Project」；免费子站 styles.refero.design 返回 200

### 46. Nicelydone（付费/部分付费，据文章）

- 链接：[https://nicelydone.club/](https://nicelydone.club/)
- 主要功能：SaaS/Web 应用界面库（付费），22 万+截图【文】
- 内容/资源类型：UI 截图
- 定位标签：UI/UX
- 适用场景与价值：ToB 后台、复杂表单、数据看板参考
- 收录作品风格倾向：SaaS 产品 UI【文+访】
- 网站自身界面：—（未做视觉核验）
- 关联风格：S28 克制产品风（Linear/Vercel 式）, S21 深色科技风
- 文章原话：专门收海外 Web 应用和 SaaS 软件界面的图库（付费）。平时做 ToB 业务、企业后台、工作台软件的人，看消费级 App 往往使不上劲，来这儿找复杂表单和数据看板的排版参考最合适。
- 站点自述（访问所得 meta）：Search 224,583 real UI screenshots from 500+ SaaS apps. Find pricing pages, onboarding flows, settings screens, and more, searchable like Google and draggable i
- 来源：文章第 46 条
- 核验状态：**已访问核验** —— HTTP 200；页面标题「Nicelydone — Web apps design inspiration (UX & UI)」；站点称 22 万+ 截图、500+ SaaS

### 47. SaaSFrame（付费/部分付费，据文章）

- 链接：[https://www.saasframe.io/](https://www.saasframe.io/)
- 主要功能：SaaS 产品界面库（付费），营销页/登录/设置等分类【文】
- 内容/资源类型：UI 截图、Figma
- 定位标签：UI/UX / 网页
- 适用场景与价值：独立开发者/B 端设计参考
- 收录作品风格倾向：SaaS 营销页与后台【文+访】
- 网站自身界面：—（未做视觉核验）
- 关联风格：S28 克制产品风（Linear/Vercel 式）, S24 Bento 网格
- 文章原话：也是盯着 SaaS 产品收集的界面库（付费），把营销官网、登录注册页、功能弹窗、后台设置页分门别类理好了，很适合独立开发者和 B 端设计师翻阅。
- 站点自述（访问所得 meta）：Explore real SaaS websites and product screens, discover UX patterns and user flows, and copy their Figma designs. The UI inspiration library for SaaS…
- 来源：文章第 47 条
- 核验状态：**已访问核验** —— HTTP 200；页面标题「SaaSFrame - SaaS UI & UX Design Inspiration Library」

### 48. Figma Community

- 链接：[https://www.figma.com/community](https://www.figma.com/community)
- 主要功能：Figma 开源社区：模板、组件库、插件【文】
- 内容/资源类型：Figma 源文件
- 定位标签：UI/UX / 设计系统 / 素材资源
- 适用场景与价值：直接打开源文件学 Auto Layout、变量命名
- 收录作品风格倾向：多元【文+访】
- 网站自身界面：—（未做视觉核验）
- 关联风格：S28 克制产品风（Linear/Vercel 式）, S10 扁平设计
- 文章原话：Figma 自带的开源社区。看别人的截图只能看个皮毛，在这里看到好的设计系统、大厂开源组件库或者排得漂亮的模板，点一下右上角的「Open in Figma」，整个源文件就直接进你草稿箱了。点开图层面板，别人怎么套的自动布局（Auto Layout）、怎么命名的颜色变量，一目了然。
- 站点自述（访问所得 meta）：Explore, install and use thousands of templates, plugins, and widgets published to the Figma Community by designers and developers.
- 来源：文章第 48 条
- 核验状态：**已访问核验** —— HTTP 200；页面标题「Discover community-made templates, plugins, and widgets | Fi」

### 49. Apple 人机界面指南（HIG）

- 链接：[https://developer.apple.com/design/human-interface-guidelines/](https://developer.apple.com/design/human-interface-guidelines/)
- 主要功能：苹果人机界面指南【文】
- 内容/资源类型：设计规范文档
- 定位标签：UI/UX / 设计系统
- 适用场景与价值：移动端基础规范（热区、导航、弹窗）
- 收录作品风格倾向：苹果平台规范【文+访】
- 网站自身界面：—（未做视觉核验）
- 关联风格：S28 克制产品风（Linear/Vercel 式）, S08 玻璃拟态
- 文章原话：苹果官方写给设计师和开发者的规范文档。遇到「底部导航栏该放几个图标」「手指点击热区最小留多少像素」「什么情况下该弹警告框」这种基础问题，不用在网上到处问人，直接翻苹果这套文档，里面把原因讲得明明白白。
- 站点自述（访问所得 meta）：The HIG contains guidance and best practices that can help you design a great experience for any Apple platform.
- 来源：文章第 49 条
- 核验状态：**已访问核验** —— HTTP 200；页面标题「Human Interface Guidelines | Apple Developer Documentation」

### 50. Material Design 3

- 链接：[https://m3.material.io/](https://m3.material.io/)
- 主要功能：Google Material Design 3 设计系统文档【文】
- 内容/资源类型：设计规范文档
- 定位标签：UI/UX / 设计系统 / 配色
- 适用场景与价值：色阶、字号层级、深色模式、组件状态逻辑
- 收录作品风格倾向：Material 3【文+访】
- 网站自身界面：—（未做视觉核验）
- 关联风格：S10 扁平设计, S28 克制产品风（Linear/Vercel 式）
- 文章原话：Google 的设计系统文档。就算你平时不做原生安卓应用，这套文档也极力推荐通读一遍。它把一套大厂设计系统是怎么定色阶、怎么算字号层级、怎么处理深色模式对比度、怎么定义组件悬停和按下状态的逻辑，毫无保留地全写出来了。
- 站点自述（访问所得 meta）：Material Design 3 - Google
- 来源：文章第 50 条
- 核验状态：**已访问核验** —— HTTP 200；页面标题「Material Design」

### 51. Vercel Web Interface Guidelines

- 链接：[https://vercel.com/design/guidelines](https://vercel.com/design/guidelines)
- 主要功能：Vercel 界面细节清单，附 AGENTS.md 与审查 skill【文】
- 内容/资源类型：规范清单
- 定位标签：UI/UX / 前端代码 / AI设计
- 适用场景与价值：AI 写界面后的自查标准
- 收录作品风格倾向：克制工程化 Web UI【文+访】
- 网站自身界面：—（未做视觉核验）
- 关联风格：S28 克制产品风（Linear/Vercel 式）, S21 深色科技风
- 文章原话：Vercel 整理的一份界面细节清单，交互、动画、布局、文案、表单、性能分门别类，每一条都是能直接照着检查的硬规矩，比如「手机上输入框字号不能小于 16px，不然 iOS 一点就会自动放大」「动画别偷懒写 transition: all」。最适合用 AI 写代码的人：页面上专门有一节教你接进 AI，给了现成的 AGENTS.md 和审查 skill，让 AI 写完界面后按清单逐条自查。
- 站点自述（访问所得 meta）：Guidelines for building great interfaces on the web. Covers interactions, animations, layout, content, forms, performance & design.
- 来源：文章第 51 条
- 核验状态：**已访问核验** —— HTTP 200；页面标题「Web Interface Guidelines」

### 52. Impeccable

- 链接：[https://impeccable.style/](https://impeccable.style/)
- 主要功能：治「AI 味」的设计 skill，62 项反模式检查【文】
- 内容/资源类型：AI skill/清单
- 定位标签：UI/UX / AI设计
- 适用场景与价值：避免 AI 默认审美（米黄配色、斜体衬线标题、卡片套卡片等）
- 收录作品风格倾向：反 AI 套路【文+访】
- 网站自身界面：—（未做视觉核验）
- 关联风格：S28 克制产品风（Linear/Vercel 式）
- 文章原话：专门治「AI 味」的设计 skill。它把 AI 最爱用的默认套路列成了 62 项检查：米黄色的「AI 配色」、斜体衬线大标题、提示框左边一根彩色竖条、卡片里再套卡片、「01 Discover」这种编号小标题……装进 Claude Code、Cursor、Codex 之后，可以用它的命令让 AI 打磨排版、调布局、给自己的设计挑毛病。就算不装，把这份清单读一遍，也能一眼看出很多页面为什么透着廉价感。
- 站点自述（访问所得 meta）：Turn AI slop into interfaces you’re proud to ship. Give your agent the design expertise to build, refine, and follow your design system.
- 来源：文章第 52 条
- 核验状态：**已访问核验** —— HTTP 200；页面标题「Impeccable: The missing design vocabulary for agents」

### 53. The Component Gallery

- 链接：[https://component.gallery/](https://component.gallery/)
- 主要功能：各大设计系统同类组件对比库【文】
- 内容/资源类型：组件截图+文档链接
- 定位标签：UI/UX / 设计系统
- 适用场景与价值：写组件规范时查漏补缺
- 收录作品风格倾向：设计系统组件【文+访】
- 网站自身界面：—（未做视觉核验）
- 关联风格：S28 克制产品风（Linear/Vercel 式）, S10 扁平设计
- 文章原话：一个专门把各家大厂「基础组件」拉出来同台比武的网站。比如你想研究一个最普通的「开关（Toggle）」或者「警告横幅（Alert）」，点进去，它会把苹果、谷歌、微软、Shopify、GitHub 等几十套设计系统里的对应组件截图和文档链接全列在一页上，写组件规范时拿来查漏补缺特别爽。
- 站点自述（访问所得 meta）：An up-to-date repository of interface components based on examples from the world of design systems, designed to be a reference for anyone building user interfa
- 来源：文章第 53 条
- 核验状态：**已访问核验** —— HTTP 200；页面标题「The Component Gallery」

### 54. 60fps

- 链接：[https://60fps.design/](https://60fps.design/)
- 主要功能：高帧率真实 App 动效片段库【文】
- 内容/资源类型：动效视频
- 定位标签：UI/UX / 动态
- 适用场景与价值：微交互/过渡动效参考
- 收录作品风格倾向：真实 App 动效【文+访】
- 网站自身界面：—（未做视觉核验）
- 关联风格：S28 克制产品风（Linear/Vercel 式）
- 文章原话：专门收集「丝滑 UI 动效」的网站。里面全是高帧率录下来的真实应用交互片段，没有花里胡哨的废话，打开网页满屏都是各种极有手感的卡片展开、下拉刷新和页面过渡动效。
- 站点自述（访问所得 meta）：60fps is a curated collection of UI/UX animation and interaction design details from the world’s best iOS, and web apps.
- 来源：文章第 54 条
- 核验状态：**已访问核验** —— HTTP 200；页面标题「60fps - UI/UX animation inspiration for mobile & web apps」

### 55. Spotted in Prod

- 链接：[https://www.spottedinprod.com/](https://www.spottedinprod.com/)
- 主要功能：精选 iOS 应用亮点细节短视频【文】
- 内容/资源类型：动效视频
- 定位标签：UI/UX / 动态
- 适用场景与价值：细节/彩蛋/反馈动效灵感
- 收录作品风格倾向：iOS 精品细节【文+访】
- 网站自身界面：—（未做视觉核验）
- 关联风格：S28 克制产品风（Linear/Vercel 式）, S08 玻璃拟态
- 文章原话：专门抓拍海外已上线 iOS 应用里那些「让人眼前一亮的小细节」。全是几秒钟的实机操作短视频，比如某个按钮按下去时的微弱震动反馈视觉化、或者一段藏在设置页里的小彩蛋，很适合平时抠细节找灵感。
- 站点自述（访问所得 meta）：Spotted in Prod is a curated collection of standout iOS apps and interactions. Discover the makers behind the work—and download apps that do it right.
- 来源：文章第 55 条
- 核验状态：**已访问核验** —— HTTP 200；页面标题「Spotted in Prod — The very best of iOS」

### 56. Growth.Design

- 链接：[https://growth.design/](https://growth.design/)
- 主要功能：连环画形式拆解知名 App 体验【文】
- 内容/资源类型：图文案例
- 定位标签：UI/UX / 教程
- 适用场景与价值：体验/增长设计分析、文案心理
- 收录作品风格倾向：插画连环画讲解【文】
- 网站自身界面：以连环画呈现【文】
- 关联风格：S18 有机/手绘
- 文章原话：两个产品设计师做的网站，专门用「连环画」的形式拆解知名 App 的真实体验。比如他们会像普通用户一样去走一遍 Duolingo 的新手引导，或者去订一次 Airbnb，然后一页页画出来：这一步文案为什么能让人安心付钱，下一步弹窗又为什么会把人吓跑。既好玩又有干货。
- 站点自述（访问所得 meta）：Level up your product skills with bite-sized tips. Learn the growth & design strategies used by the top product companies in the world.
- 来源：文章第 56 条
- 核验状态：**已访问核验** —— HTTP 200；页面标题「Growth.Design — Better Products, Better Growth.」

### 57. Laws of UX

- 链接：[https://lawsofux.com/](https://lawsofux.com/)
- 主要功能：UX 心理学定律图文卡片【文】
- 内容/资源类型：知识卡片
- 定位标签：UI/UX / 教程
- 适用场景与价值：改版方案找理论依据
- 收录作品风格倾向：—
- 网站自身界面：二十几张干净的图文卡片【文】
- 关联风格：S02 极简主义
- 文章原话：把交互设计里常被拿来装门面的心理学定律（比如菲茨定律、希克定律、米勒定律、峰终定律），浓缩成了二十几张干净的图文卡片。每点开一张，用三句话告诉你这定律是什么意思、最早是谁提出来的、落到具体界面设计上该注意什么。写改版方案需要找理论依据时，上去翻一下很快。
- 站点自述（访问所得 meta）：Laws of UX is a collection of best practices that designers can consider when building user interfaces.
- 来源：文章第 57 条
- 核验状态：**已访问核验** —— HTTP 200；页面标题「Home | Laws of UX」

### 58. Game UI Database

- 链接：[https://www.gameuidatabase.com/](https://www.gameuidatabase.com/)
- 主要功能：游戏界面截图库，按 UI 功能分类【文】
- 内容/资源类型：游戏 UI 截图
- 定位标签：UI/UX / 游戏
- 适用场景与价值：游戏 UI、复杂信息层级参考
- 收录作品风格倾向：游戏 UI：科幻/奇幻/HUD【文+访】
- 网站自身界面：—（未做视觉核验）
- 关联风格：S16 赛博朋克, S11 拟物化, S21 深色科技风
- 文章原话：一个规模吓人的游戏界面截图库，收了将近 2000 款主机与 PC 游戏、7 万多张高清截图。最牛的是它按 UI 功能做好了分类：你可以直接搜所有游戏里的「捏脸界面」「装备背包」「技能树」「任务弹窗」或「死亡结算画面」。哪怕不做游戏，去看看游戏设计师是怎么在极度复杂的信息量下排好视觉层级的，也相当涨见识。
- 站点自述（访问所得 meta）：Explore over 1,300 games and 55,000 UI screenshots. Browse by screen type, animation, layout, colour, and more. The ultimate game UI reference for designers and
- 来源：文章第 58 条
- 核验状态：**已访问核验** —— HTTP 200；页面标题「Game UI Database 2.0 | Welcome」；站点描述写「1,300+ 款游戏、55,000 张截图」，与文章「近 2000 款、7 万多张」不一致，以站点为准待复核

## 六、网页灵感

### 59. Recent（原 Godly）

- 链接：[https://recent.design/](https://recent.design/)
- 主要功能：Recent（原 Godly）网页灵感库，缩略图直接播放滚动录屏，扩至产品片/App 图标/品牌/海报【文】
- 内容/资源类型：网页录屏、品牌视觉
- 定位标签：网页 / 灵感 / 品牌 / 平面
- 适用场景与价值：看海外独立开发者/科技公司最新网页风向
- 收录作品风格倾向：当下流行科技网页风【文】
- 网站自身界面：—（未做视觉核验）
- 关联风格：S21 深色科技风, S20 渐变/极光, S24 Bento 网格, S04 新粗野主义
- 文章原话：以前网页设计师几乎人手一个书签的 Godly（godly.website），现在输入原网址会直接跳转到这个新站 Recent。它保留了以前那种不用点进原网站、直接在缩略图上就能看高清滚动录屏的爽快体验，同时还把收录范围扩到了产品宣传片、App 图标、品牌视觉和海报。想看眼下海外独立开发者和科技公司最流行什么网页风向，刷它就对了。
- 站点自述（访问所得 meta）：The best design inspiration on the Internet.
- 来源：文章第 59 条
- 核验状态：**已访问核验** —— HTTP 200；页面标题「Recent — Design Inspiration」；已核验 godly.website 会跳转到 recent.design（与文章一致）

### 60. Siteinspire

- 链接：[https://www.siteinspire.com/](https://www.siteinspire.com/)
- 主要功能：老牌网页灵感库，可按视觉风格/网站类型/行业叠加筛选【文】
- 内容/资源类型：网站案例
- 定位标签：网页 / 灵感
- 适用场景与价值：耐看排版、作品集/电商/建筑/时尚网站
- 收录作品风格倾向：克制、网格、极简、大字报【文+访：页面可见 Minimal/Grid Layout/Unusual Layout 标签】
- 网站自身界面：—（未做视觉核验）
- 关联风格：S01 瑞士/国际主义风格, S02 极简主义, S13 编辑/杂志风, S26 实验/反设计
- 文章原话：办了十来年的老牌网页灵感库，攒了几千个站。它的筛选器做得很好用，可以把「视觉风格（如网格、极简、大字报）」「网站类型（如作品集、电商）」和「所属行业（如建筑、时尚）」叠在一起筛。整体选品眼光很克制，很少收那种眼花缭乱的炫技站，全是耐看的排版。
- 来源：文章第 60 条
- 核验状态：**已访问核验** —— curl 429（Vercel 安全检查）→ WebFetch 取到正文：首页可见 Minimal / Grid Layout / Unusual Layout 等筛选标签与 2026-11 新收录

### 61. Land-book

- 链接：[https://land-book.com/](https://land-book.com/)
- 主要功能：落地页图库，含定价页/关于页/简历页合集【文】
- 内容/资源类型：网页截图
- 定位标签：网页 / 灵感
- 适用场景与价值：常规商业网站、落地页参考
- 收录作品风格倾向：商业落地页【文+访】
- 网站自身界面：—（未做视觉核验）
- 关联风格：S28 克制产品风（Linear/Vercel 式）, S24 Bento 网格, S20 渐变/极光
- 文章原话：专门收落地页（Landing Page）的图库。除了产品首页，里面也单独分出了定价页（Pricing）、关于我们、个人简历页的合集，做常规商业网站很实用。
- 站点自述（访问所得 meta）：Find the best hand-picked website design inspiration. We're a curated website design gallery for Creatives, updated daily.
- 来源：文章第 61 条
- 核验状态：**已访问核验** —— HTTP 200；页面标题「Landbook - website design inspiration gallery」

### 62. Landingfolio（付费/部分付费，据文章）

- 链接：[https://www.landingfolio.com/](https://www.landingfolio.com/)
- 主要功能：落地页区块库（4600+），可复制为 Tailwind/Figma/Webflow（部分付费）【文】
- 内容/资源类型：区块组件
- 定位标签：网页 / 前端代码 / AI设计
- 适用场景与价值：挑区块喂 AI 生成首屏等
- 收录作品风格倾向：商业落地页区块【文+访】
- 网站自身界面：—（未做视觉核验）
- 关联风格：S28 克制产品风（Linear/Vercel 式）, S24 Bento 网格
- 文章原话：也是收落地页的图库，但多做了一步：把页面拆成了首屏、功能介绍、用户评价、行动按钮、页脚这些区块，一共 4600 多个，能复制成 Tailwind、Figma 或 Webflow 格式（部分付费）。拿来喂 AI 特别顺手——挑一个喜欢的区块丢给它，比用文字描述「给我做个好看的首屏」准得多。
- 站点自述（访问所得 meta）：Looking for landing page inspiration? Landingfolio features the best landing page designs, templates and components on the web.
- 来源：文章第 62 条
- 核验状态：**已访问核验** —— HTTP 200；页面标题「The Best Landing Page Design Inspiration, Templates and More」

### 63. awesome-design-md

- 链接：[https://github.com/VoltAgent/awesome-design-md](https://github.com/VoltAgent/awesome-design-md)
- 主要功能：开源 DESIGN.md 合集（Stripe/Linear/Vercel/Apple 等），MIT【文】
- 内容/资源类型：Markdown 设计规范
- 定位标签：AI设计 / 设计系统 / 网页
- 适用场景与价值：让 AI 按某品牌规矩生成界面
- 收录作品风格倾向：知名科技品牌风格【文+访】
- 网站自身界面：—（未做视觉核验）
- 关联风格：S28 克制产品风（Linear/Vercel 式）, S21 深色科技风
- 文章原话：GitHub 上的一个开源合集，把 Stripe、Linear、Vercel、Apple 这些公认好看的网站，各自的配色、字体、间距和组件风格整理成一份 DESIGN.md 文件。把它放进你的项目里，AI 就会照着这个品牌的规矩来生成界面，比你自己描述「我要 Linear 那种感觉」靠谱得多。
- 站点自述（访问所得 meta）：A collection of DESIGN.md files analysis by popular brand design systems. Drop one into your project and let coding agents generate a matching UI. - VoltAgent/a
- 来源：文章第 63 条
- 核验状态：**已访问核验** —— HTTP 200；页面标题「GitHub - VoltAgent/awesome-design-md: A collection of DESIGN」；GitHub API：MIT 许可，约 12.7 万 star，最近推送 2026-10-28

### 64. One Page Love

- 链接：[https://onepagelove.com/](https://onepagelove.com/)
- 主要功能：单页网站图库【文】
- 内容/资源类型：网站案例
- 定位标签：网页 / 灵感
- 适用场景与价值：活动页、个人主页、小产品单页
- 收录作品风格倾向：单页叙事网站【文+访】
- 网站自身界面：—（未做视觉核验）
- 关联风格：S02 极简主义, S13 编辑/杂志风
- 文章原话：专门收集「单页网站」的网站。有些小产品、线下活动或者个人主页，根本撑不起好几个频道的导航栏，去这儿看看别人是怎么在一页从上滑到下的篇幅里，把事情讲得清清楚楚又有节奏感的。
- 站点自述（访问所得 meta）：One Page Love is a One Page website design gallery showcasing the best Single Page websites, templates and resources.
- 来源：文章第 64 条
- 核验状态：**已访问核验** —— HTTP 200；页面标题「One Page Love — One Page Website Inspiration and Templates」

### 65. Minimal Gallery

- 链接：[https://minimal.gallery/](https://minimal.gallery/)
- 主要功能：极简主义网站图库【文】
- 内容/资源类型：网站案例
- 定位标签：网页 / 灵感
- 适用场景与价值：学黑白灰、大留白、字号对比
- 收录作品风格倾向：极简【文+访】
- 网站自身界面：—（未做视觉核验）
- 关联风格：S02 极简主义, S01 瑞士/国际主义风格, S14 日式/无印风
- 文章原话：只收极简主义风格网站的图库。如果总觉得自己排出来的页面塞得满满当当、透不过气，去这里多看几个站，学学别人是怎么单靠黑白灰、大留白和干净的字号对比把页面撑起来的。
- 站点自述（访问所得 meta）：Get inspiration from the best modern website designs, submitted by talented designers worldwide. Discover new sites daily, plus premium Framer & Webflow templat
- 来源：文章第 65 条
- 核验状态：**已访问核验** —— HTTP 200；页面标题「Minimal Gallery – Hand-picked web design inspiration, premiu」

### 66. Dark Mode Design

- 链接：[https://www.darkmodedesign.com/](https://www.darkmodedesign.com/)
- 主要功能：深色模式网页图库【文】
- 内容/资源类型：网站案例
- 定位标签：网页 / 灵感 / 配色
- 适用场景与价值：深色界面层级、边框透明度参考
- 收录作品风格倾向：深色模式【文+访】
- 网站自身界面：—（未做视觉核验）
- 关联风格：S21 深色科技风, S16 赛博朋克
- 文章原话：全网只收「深色模式」网页的图库。很多人做黑底网页容易要么漆黑一片分不清主次，要么发光特效加太多显得廉价。去这儿翻翻成熟案例，看看纯黑、深灰怎么拉开卡片层级，文字和细线边框该把透明度压到多少才不刺眼。
- 站点自述（访问所得 meta）：Dark Mode Design is a showcase of beautifully designed and inspiring dark mode websites. Dim the lights, lower your screen brightness, and enjoy.
- 来源：文章第 66 条
- 核验状态：**已访问核验** —— HTTP 200；页面标题「Dark Mode Design 🌘 Handpicked website inspiration」

### 67. Hoverstat.es

- 链接：[https://www.hoverstat.es/](https://www.hoverstat.es/)
- 主要功能：「另类网页」合集：独立艺术家、先锋工作室【文】
- 内容/资源类型：网站案例
- 定位标签：网页 / 灵感 / 平面
- 适用场景与价值：寻找打破套路的实验网页
- 收录作品风格倾向：实验/反设计/粗野【文+访】
- 网站自身界面：—（未做视觉核验）
- 关联风格：S26 实验/反设计, S03 粗野主义（网页）, S17 酸性设计
- 文章原话：专门收录「怪网站」的地方。里面基本看不到正经的商业公司官网，全是独立艺术家、先锋设计工作室、地下乐队或者实验建筑师的主页。导航栏藏在奇怪的地方、鼠标滑过去满屏乱飞——当你觉得现在的网页全都长一个样、看腻了套路的时候，去这儿逛逛会非常解闷。
- 站点自述（访问所得 meta）：The home of alternative design, code and content on the world wide web.
- 来源：文章第 67 条
- 核验状态：**已访问核验** —— HTTP 200；页面标题「HOVERSTAT.ES | The home of alternative web-design.」

### 68. Web Design Museum

- 链接：[https://www.webdesignmuseum.org/](https://www.webdesignmuseum.org/)
- 主要功能：网页设计历史博物馆（1991–2006 截图、Flash）【文】
- 内容/资源类型：历史截图/视频
- 定位标签：网页 / 灵感
- 适用场景与价值：Y2K/千禧复古风一手史料
- 收录作品风格倾向：早期 Web、拟物、Flash、Y2K【文+访】
- 网站自身界面：—（未做视觉核验）
- 关联风格：S07 Y2K / 千禧复古, S11 拟物化, S12 复古/怀旧
- 文章原话：一个正儿八经的「网页设计历史博物馆」。站长把 1991 年到 2006 年之间几千个古早网站的截图全存了下来——你能看到 1997 年的苹果官网长什么样、千禧年前后的雅虎门户排得有多密，以及当年红极一时的拟物化按钮和 Flash 酷站。除了怀旧，现在很多潮牌爱玩的千禧年复古风（Y2K），来这儿直接就能翻到最纯正的一手史料。
- 站点自述（访问所得 meta）：Web Design Museum exhibits thousands of screenshots and videos of websites, apps, software, and Flash games from the 1990s to the late 2000s.
- 来源：文章第 68 条
- 核验状态：**已访问核验** —— HTTP 200；页面标题「Web Design Museum – Discover old websites, apps, software & 」

## 七、前端与交互

### 69. Codrops

- 链接：[https://tympanus.net/codrops/](https://tympanus.net/codrops/)
- 主要功能：创意前端特效教程，附 Demo 与源码【文】
- 内容/资源类型：教程+代码
- 定位标签：前端代码 / 网页 / 动态
- 适用场景与价值：WebGL/过渡/文字特效实现
- 收录作品风格倾向：创意前端特效【文+访】
- 网站自身界面：—（未做视觉核验）
- 关联风格：S29 沉浸式 WebGL/创意交互
- 文章原话：做创意前端的人必存的宝地。这个站常年分享各种能在 Awwwards 上拿奖的前端特效教程：WebGL 图片扭曲、丝滑的页面无刷新过渡、跟着滚动条变形的文字网格。最良心的是每一篇文章不仅把实现思路一步步讲清楚，还直接附上在线 Demo 和 GitHub 源码仓库。
- 站点自述（访问所得 meta）：Founded in 2009, Codrops is a destination for web design and development enthusiasts. Our team is dedicated to providing high-quality, innovative content that e
- 来源：文章第 69 条
- 核验状态：**已访问核验** —— HTTP 200；页面标题「Codrops | Fueling web creativity since 2009」

### 70. CodePen Spark

- 链接：[https://codepen.io/spark](https://codepen.io/spark)
- 主要功能：CodePen 编辑每周创意代码合集【文】
- 内容/资源类型：代码 Demo
- 定位标签：前端代码 / 灵感
- 适用场景与价值：练手、找小型交互/生成艺术
- 收录作品风格倾向：CSS/SVG/Canvas 小作品，近期含 Three.js/合成波【文+访】
- 网站自身界面：—（未做视觉核验）
- 关联风格：S29 沉浸式 WebGL/创意交互, S16 赛博朋克
- 文章原话：CodePen 编辑部每周整理一次的创意代码合集。里面全是世界各地的前端用几百行 CSS、SVG 或 Canvas 写出来的小玩具。看中哪个效果，点进去左边就是 HTML/CSS/JS 源码框，随手改两个数字，右边画面当场就跟着变，拿来练手再好不过。
- 来源：文章第 70 条
- 核验状态：**已访问核验** —— curl 403（Cloudflare）→ WebFetch 取到正文：本周主题「New Realms」等 Pen 列表

### 71. GSAP 官方 Demo 库

- 链接：[https://demos.gsap.com/](https://demos.gsap.com/)
- 主要功能：GSAP 官方 Demo 库（百余效果，含 CodePen 源码）【文】
- 内容/资源类型：代码 Demo
- 定位标签：前端代码 / 动态
- 适用场景与价值：滚动/文字/悬停动画实现
- 收录作品风格倾向：网页动效【文+访】
- 网站自身界面：—（未做视觉核验）
- 关联风格：S29 沉浸式 WebGL/创意交互
- 文章原话：网页动画老大哥 GSAP（GreenSock）的官方示例库，一百多个效果按滚动、文字、悬停、鼠标跟随、轮播分好了类，每个都附 CodePen 源码。以前 GSAP 很多最好用的高级插件（比如做滚动绑定的 ScrollTrigger、拆字动画的 SplitText）是要掏钱买会员的，被 Webflow 收购之后，现在连带所有商业插件全部免费开放了。看中哪个效果，把源码直接丢给 AI 改，非常香。
- 站点自述（访问所得 meta）：A growing collection of interactive demos and examples. Learn, explore, and see what’s possible with GSAP.
- 来源：文章第 71 条
- 核验状态：**已访问核验** —— HTTP 200；页面标题「GSAP Demo Hub」

### 72. Three.js 官方示例

- 链接：[https://threejs.org/examples/](https://threejs.org/examples/)
- 主要功能：Three.js 官方示例【文】
- 内容/资源类型：代码 Demo
- 定位标签：前端代码 / 3D
- 适用场景与价值：Web 3D 效果标准写法
- 收录作品风格倾向：Web 3D【文+访】
- 网站自身界面：—（未做视觉核验）
- 关联风格：S29 沉浸式 WebGL/创意交互, S19 3D / 黏土风
- 文章原话：想在浏览器里做 3D 效果，基本绕不开 Three.js。不用到处找野路子教程，先把官方这几百个在线 Demo 挨个点开看一遍——小到加载一个带骨骼动画的模型，大到海洋水面反射、物理碰撞、后期辉光通道，所有效果右下角都有个「源码」按钮，点开就是最标准的官方写法。
- 来源：文章第 72 条
- 核验状态：**已访问核验** —— HTTP 200；页面标题「three.js examples」

### 73. Shadertoy

- 链接：[https://www.shadertoy.com/](https://www.shadertoy.com/)
- 主要功能：GLSL 着色器实时作品社区【文】
- 内容/资源类型：代码作品
- 定位标签：前端代码 / 3D
- 适用场景与价值：流体背景、程序化视觉、图形学研究
- 收录作品风格倾向：程序化/生成艺术【文】
- 网站自身界面：—（未做视觉核验）
- 关联风格：S29 沉浸式 WebGL/创意交互, S20 渐变/极光, S16 赛博朋克
- 文章原话：图形学大神炫技的地方。这个网站里的所有酷炫画面——不管是翻滚的体积云、逼真的水波折射，还是一整座霓虹闪烁的立体城市，全都不靠导入外部图片或 3D 模型，纯粹是用几百行数学公式（GLSL 着色器代码）在显卡里实时算出来的。网页右边直接放着源码，虽然满屏三角函数看着头大，但想做流体背景或研究图形学的人绝对绕不开。
- 来源：文章第 73 条
- 核验状态：**已访问核验** —— curl 403（Cloudflare）→ WebFetch 取到页面（Shader of the Week，内容有限）

### 74. The Book of Shaders

- 链接：[https://thebookofshaders.com/](https://thebookofshaders.com/)
- 主要功能：片元着色器交互式在线教程（含中文）【文】
- 内容/资源类型：教程
- 定位标签：前端代码 / 教程
- 适用场景与价值：Shader 入门
- 收录作品风格倾向：—
- 网站自身界面：—（未做视觉核验）
- 关联风格：S29 沉浸式 WebGL/创意交互
- 文章原话：如果你点开上面的 Shadertoy 觉得像在看天书，那就先来读这本免费的在线互动教程（自带中文版）。作者把枯燥的片元着色器（Fragment Shaders）掰碎了，从怎么用一条数学公式画出一条线、一个圆、再到生成噪波纹理，每一段代码都可以直接在文章里边改数字边看图案变化，是公认最好的 Shader 启蒙书。
- 站点自述（访问所得 meta）：Gentle step-by-step guide through the abstract and complex universe of Fragment Shaders.
- 来源：文章第 74 条
- 核验状态：**已访问核验** —— HTTP 200；页面标题「The Book of Shaders」

### 75. Bruno Simon

- 链接：[https://bruno-simon.com/](https://bruno-simon.com/)
- 主要功能：Bruno Simon 个人主页：3D 玩具车沙盘简历【文】
- 内容/资源类型：互动网站
- 定位标签：前端代码 / 3D / 网页
- 适用场景与价值：沉浸式作品集/个人站灵感
- 收录作品风格倾向：—
- 网站自身界面：浏览器里开 3D 玩具车的沙盘【文】
- 关联风格：S29 沉浸式 WebGL/创意交互, S19 3D / 黏土风
- 文章原话：法国开发者 Bruno Simon 的个人主页。别人的简历是一页 PDF，他的简历是让你在浏览器里直接开着一辆玩具车，在 3D 沙盘里横冲直撞，撞倒路牌就能看他的工作经历和项目。他写的《Three.js Journey》也是目前把 Web 3D 讲得最透彻的课程之一。
- 来源：文章第 75 条
- 核验状态：**已访问核验** —— HTTP 000；首次 TLS 握手失败，重试 200 正常

### 76. Lusion

- 链接：[https://lusion.co/](https://lusion.co/)
- 主要功能：Lusion 英国高定创意开发工作室官网【文】
- 内容/资源类型：作品集/官网
- 定位标签：前端代码 / 3D / 网页
- 适用场景与价值：WebGL 沉浸式品牌站标杆
- 收录作品风格倾向：3D 叙事、沉浸式网站【文+访】
- 网站自身界面：官网即 WebGL 交互天花板之一【文】
- 关联风格：S29 沉浸式 WebGL/创意交互, S19 3D / 黏土风
- 文章原话：英国一家专门接高定创意开发的工作室。他们自己的官网本身就是目前 WebGL 网页交互的天花板之一——从页面加载、滚轮阻尼、三维粒子转场到音效配合，没有一帧是卡顿或多余的，值得每个前端打开慢慢观摩。
- 站点自述（访问所得 meta）：We design and produce 3D visual storytelling, immersive websites, and interactive digital experiences that help brands stand out online.
- 来源：文章第 76 条
- 核验状态：**已访问核验** —— HTTP 200；页面标题「Lusion - Award Winning 3D and Interactive Web Studio」

### 77. Active Theory

- 链接：[https://activetheory.net/](https://activetheory.net/)
- 主要功能：Active Theory 数字互动工作室官网【文】
- 内容/资源类型：作品集/官网
- 定位标签：前端代码 / 网页
- 适用场景与价值：大厂技术营销互动项目参考
- 收录作品风格倾向：互动体验【文+访】
- 网站自身界面：—（未做视觉核验）
- 关联风格：S29 沉浸式 WebGL/创意交互
- 文章原话：美国顶尖的数字互动工作室。像好几届 Google I/O 大会的线上互动体验、早几年 Spotify 年度听歌报告（Wrapped）的互动页，很多大厂刷屏级的技术营销项目背后都是他们在写代码。
- 站点自述（访问所得 meta）：Founded in 2012. We blend story, art & technology as an in-house team of passionate makers. Our industry-leading web toolset consistently delivers award-winning
- 来源：文章第 77 条
- 核验状态：**已访问核验** —— HTTP 200；页面标题「Active Theory · Creative Digital Experiences」

### 78. Framer Gallery

- 链接：[https://www.framer.com/gallery/](https://www.framer.com/gallery/)
- 主要功能：Framer 官方优秀网站画廊【文】
- 内容/资源类型：网站案例
- 定位标签：网页 / 灵感
- 适用场景与价值：无代码设计师网站动效上限参考
- 收录作品风格倾向：Framer 站：现代 SaaS/作品集【文+访】
- 网站自身界面：—（未做视觉核验）
- 关联风格：S24 Bento 网格, S20 渐变/极光, S28 克制产品风（Linear/Vercel 式）
- 文章原话：Framer 官方挑出来的优秀网站合集。Framer 的操作界面跟 Figma 几乎一模一样，但画完点一下发布就是个带真实代码的响应式网站。去这个画廊逛一圈，你就能知道现在一个不懂代码的设计师，单靠拖拽和自带组件能把网站动效做到什么程度。
- 站点自述（访问所得 meta）：Get inspired by the best website design on the internet, then build your own with Framer's agent, directly on the canvas, and submit it to the Framer Website De
- 来源：文章第 78 条
- 核验状态：**已访问核验** —— HTTP 200；页面标题「Framer Gallery: Explore the best websites built with Framer」；跳转至 framer.com/community/gallery/

### 79. Motion 官方示例（付费/部分付费，据文章）

- 链接：[https://motion.dev/examples](https://motion.dev/examples)
- 主要功能：Motion（原 Framer Motion）官方示例（部分付费）【文】
- 内容/资源类型：代码示例
- 定位标签：前端代码 / 动态
- 适用场景与价值：React/Vue UI 动效现成写法
- 收录作品风格倾向：UI 动效【文+访】
- 网站自身界面：—（未做视觉核验）
- 关联风格：S28 克制产品风（Linear/Vercel 式）
- 文章原话：现在写 React 和 Vue 最常用的动画库 Motion（以前叫 Framer Motion）的官方示例页。从最基础的弹簧物理缓动、列表增删重排，到复杂的跟随滚动条动画，常用的 UI 动效基本都有现成的简短示例（部分付费）：所有示例都能看演示，基础分类的一百多个免费给源码，复制过来就能改着用；其余的要买 Motion+ 才能看代码。
- 站点自述（访问所得 meta）：Production-ready snippets for Motion across React, JavaScript, and Vue. Ready to copy paste straight into your site, or adapt with AI.
- 来源：文章第 79 条
- 核验状态：**已访问核验** —— HTTP 200；页面标题「Examples: React, JavaScript, and Vue animation snippets | Mo」

### 80. React Bits

- 链接：[https://reactbits.dev/](https://reactbits.dev/)
- 主要功能：免费开源 React 动画组件库【文】
- 内容/资源类型：代码组件
- 定位标签：前端代码 / 动态
- 适用场景与价值：快速给页面加文字/背景/卡片动效
- 收录作品风格倾向：动效组件：流光、乱码、流体背景【文+访】
- 网站自身界面：—（未做视觉核验）
- 关联风格：S21 深色科技风, S20 渐变/极光
- 文章原话：一个完全免费开源的 React 动画组件小超市。里面全是现成封装好的视觉小零件：文字乱码浮现、鼠标磁性吸附按钮、流光卡片边框、动态流体背景。左边调好速度、颜色参数，右边直接复制代码贴进自己项目里，五分钟就能让干巴巴的页面活起来。
- 站点自述（访问所得 meta）：Free, open source React components for animated text, backgrounds, interactive cards and micro interactions. Explore live demos and copy the source.
- 来源：文章第 80 条
- 核验状态：**已访问核验** —— HTTP 200；页面标题「React Bits — Free Animated React Components」

### 81. coss ui

- 链接：[https://coss.com/ui](https://coss.com/ui)
- 主要功能：Cal.com 设计系统 coss ui（前身 Origin UI），Tailwind，MIT【文】
- 内容/资源类型：代码组件
- 定位标签：前端代码 / 设计系统 / UI/UX
- 适用场景与价值：克制真实产品感组件
- 收录作品风格倾向：克制产品风【文】
- 网站自身界面：风格克制，像认真打磨的真实产品【文】
- 关联风格：S28 克制产品风（Linear/Vercel 式）
- 文章原话：开源日程工具 Cal.com 自家的设计系统，前身是不少人收藏过的 Origin UI。基于 Tailwind 写的，五十多个基础组件加五百多个现成的小模块，MIT 协议随便用。它的风格很克制，看着就像一个认真打磨过的真实产品，而不是又一个「深色背景 + 发光边框 + 光束特效」的 AI 创业公司官网。
- 站点自述（访问所得 meta）：Accessible React components we use to build Cal.com, powered by Base UI and styled with Tailwind CSS. Designed for developers and AI, with source code you can m
- 来源：文章第 81 条
- 核验状态：**已访问核验** —— HTTP 200；页面标题「A modern React UI component library – coss ui」

### 82. Josh W. Comeau

- 链接：[https://www.joshwcomeau.com/](https://www.joshwcomeau.com/)
- 主要功能：Josh Comeau 前端博客，交互式图解【文】
- 内容/资源类型：文章（课程付费）
- 定位标签：前端代码 / 教程
- 适用场景与价值：理解 CSS/动画原理
- 收录作品风格倾向：—
- 网站自身界面：文章含可拖拽交互图解【文】
- 关联风格：S18 有机/手绘
- 文章原话：前端开发者 Josh Comeau 的博客。他讲 CSS 布局、弹簧动画、SVG 路径，不是干巴巴地贴代码，而是在文章里塞满能拖、能调参数的交互小图解，拖一下滑块你就明白为什么这条曲线看着更舒服。文章免费，进阶课程收费。原理看懂了，再让 AI 写动效时你才知道该提什么要求。
- 站点自述（访问所得 meta）：Friendly articles and tutorials for front-end web developers. ❤️
- 来源：文章第 82 条
- 核验状态：**已访问核验** —— HTTP 200；页面标题「Josh W. Comeau」

### 83. Rauno Freiberg

- 链接：[https://rauno.me/](https://rauno.me/)
- 主要功能：Rauno Freiberg 个人站，《Invisible Details of Interaction Design》【文】
- 内容/资源类型：文章+交互示例
- 定位标签：前端代码 / UI/UX
- 适用场景与价值：交互细节工程原理
- 收录作品风格倾向：—
- 网站自身界面：—（未做视觉核验）
- 关联风格：S28 克制产品风（Linear/Vercel 式）, S02 极简主义
- 文章原话：目前在 Vercel 担任设计工程师的 Rauno 的个人网站。强烈建议把他站里那篇《Invisible Details of Interaction Design》（交互设计中看不见的细节）从头到尾读一遍。他用十几个可以亲手点按的交互小组件，把「为什么苹果系统的滑动停下来那么自然」「下拉菜单怎么根据鼠标移动斜率防误触」这种藏在水面下的工程细节讲得明明白白。
- 来源：文章第 83 条
- 核验状态：**已访问核验** —— HTTP 200；页面标题「Rauno Freiberg」

### 84. Emil Kowalski

- 链接：[https://emilkowal.ski/](https://emilkowal.ski/)
- 主要功能：Emil Kowalski 博客（Sonner/Vaul 作者）【文】
- 内容/资源类型：文章
- 定位标签：前端代码 / UI/UX / 动态
- 适用场景与价值：克制跟手的界面动画原则
- 收录作品风格倾向：—
- 网站自身界面：—（未做视觉核验）
- 关联风格：S28 克制产品风（Linear/Vercel 式）
- 文章原话：很多前端都在用的开源提示框组件 Sonner 和抽屉组件 Vaul 的作者，之前在 Linear 做设计工程师。他的博客文章篇幅都不长，但全在死磕一个问题：怎么让界面动画显得「克制又跟手」。比如弹窗到底该用多少毫秒、什么情况下绝对不要加动画，读完能改掉不少乱加动效的坏毛病。
- 站点自述（访问所得 meta）：Design engineer working at Linear.
- 来源：文章第 84 条
- 核验状态：**已访问核验** —— HTTP 200；页面标题「Emil Kowalski」；站点 meta 写「Design engineer working at Linear」，文章写「之前在 Linear」，不一致待复核

## 八、字体与配色

### 85. Typewolf

- 链接：[https://www.typewolf.com/](https://www.typewolf.com/)
- 主要功能：字体指南与搭配榜单（文章称 2025 年底后停更）【文】
- 内容/资源类型：字体案例/榜单
- 定位标签：字体
- 适用场景与价值：中西混排、英文字体选择
- 收录作品风格倾向：—
- 网站自身界面：—（未做视觉核验）
- 关联风格：S01 瑞士/国际主义风格, S13 编辑/杂志风
- 文章原话：海外排版圈公认最靠谱的字体指南网站。站长是个对字体极度挑剔的设计师，以前每天推荐一个把字体用得极好看的真实网站，并标出它主标题和正文分别用了什么字（2025 年底之后就没再更新了，但攒下的案例和榜单照样能翻）。此外，网站里整理的「十佳无衬线体」「Google Fonts 最佳搭配方案」含金量极高，做英文或中西混排页面拿不准用什么字体时，去翻它的榜单绝对不会出错。
- 站点自述（访问所得 meta）：Typewolf helps designers choose the perfect font combination for their next design project—features web fonts in the wild, font recommendations and learning res
- 来源：文章第 85 条
- 核验状态：**已访问核验** —— HTTP 200；页面标题「What’s Trending in Type · Typewolf」；文章称 2025 年底后停更（未独立核验更新日期）

### 86. Fonts In Use

- 链接：[https://fontsinuse.com/](https://fontsinuse.com/)
- 主要功能：字体实战档案馆，标注真实作品所用字体【文】
- 内容/资源类型：字体案例
- 定位标签：字体 / 平面 / 品牌
- 适用场景与价值：看字体在海报/书籍/品牌中的实际气质
- 收录作品风格倾向：海报、书封、唱片、标识【文+访】
- 网站自身界面：—（未做视觉核验）
- 关联风格：S01 瑞士/国际主义风格, S13 编辑/杂志风, S12 复古/怀旧
- 文章原话：一个靠全球设计师共同维护的「字体实战档案馆」。它不卖字库，专门收集现实世界里的海报、书籍封面、唱片封套、路牌、网页截图，然后像法医一样把里面用到的每一款字体名字全扒出来标在旁边。你想知道某款字体印在纸上或排在网页上到底是什么气质，搜一下它里面的真实案例就清楚了。
- 站点自述（访问所得 meta）：A searchable archive of typographic design, indexed by typeface, format, and topic.
- 来源：文章第 86 条
- 核验状态：**已访问核验** —— HTTP 200；页面标题「Fonts In Use - Fonts In Use」

### 87. Google Fonts

- 链接：[https://fonts.google.com/](https://fonts.google.com/)
- 主要功能：Google 免费开源字库（含思源黑/宋等）【文】
- 内容/资源类型：字体（免费可商用）
- 定位标签：字体 / 素材资源
- 适用场景与价值：中英文网页字体、免费商用字体
- 收录作品风格倾向：—
- 网站自身界面：—（未做视觉核验）
- 关联风格：S10 扁平设计, S02 极简主义
- 文章原话：大家最熟悉的老朋友，完全免费可商用的开源字库。除了海量的英文字体，像中文里最常用的思源黑体（Noto Sans SC）、思源宋体（Noto Serif SC）、霞鹜文楷（繁体版）都能在上面直接下载，写前端更是连字体包都不用下，引一行链接就能跑。
- 站点自述（访问所得 meta）：Making the web more beautiful, fast, and open through great typography
- 来源：文章第 87 条
- 核验状态：**已访问核验** —— HTTP 200；页面标题「Browse Fonts - Google Fonts」

### 88. Fontshare

- 链接：[https://www.fontshare.com/](https://www.fontshare.com/)
- 主要功能：ITF 免费商用字库（Satoshi、Clash Display、General Sans 等）【文】
- 内容/资源类型：字体（免费可商用）
- 定位标签：字体 / 素材资源
- 适用场景与价值：科技/独立网页的几何无衬线标题
- 收录作品风格倾向：—
- 网站自身界面：—（未做视觉核验）
- 关联风格：S28 克制产品风（Linear/Vercel 式）, S04 新粗野主义, S24 Bento 网格
- 文章原话：印度知名字体大厂 ITF 办的免费字库网站。上面的字体虽然数量没有 Google Fonts 那么夸张，但款款都是精品，而且承诺 100% 免费供个人和商业项目使用。像这两年在海外独立网页和科技圈出镜率极高的几何无衬线体 Satoshi、标题字 Clash Display、General Sans，全是从这儿免费流出来的。
- 站点自述（访问所得 meta）：Fontshare is a free fonts service from the Indian Type Foundry (ITF), making quality fonts accessible to all.
- 来源：文章第 88 条
- 核验状态：**已访问核验** —— HTTP 200；页面标题「Fontshare: Quality Fonts. Free.」

### 89. Butterick's Practical Typography

- 链接：[https://practicaltypography.com/](https://practicaltypography.com/)
- 主要功能：免费在线排版小书【文】
- 内容/资源类型：教程
- 定位标签：字体 / 教程
- 适用场景与价值：行长、行高、字距硬指标
- 收录作品风格倾向：—
- 网站自身界面：—（未做视觉核验）
- 关联风格：S13 编辑/杂志风, S01 瑞士/国际主义风格
- 文章原话：一本写得极其痛快的免费在线排版小书。作者既写过代码又当过职业字体设计师，书里没有任何故弄玄虚的艺术理论，上来就用「10 分钟掌握排版核心」一章直接给你划硬指标：正文一行控制在多少个字母最舒服、行高设多少倍、为什么绝对不要随便拉宽字间距。哪怕只读完这第一章，你排出来的文档和网页都会立马顺眼一大截。
- 站点自述（访问所得 meta）：Butterick’s Practical Typography
- 来源：文章第 89 条
- 核验状态：**已访问核验** —— HTTP 200；页面标题「Butterick’s Practical Typography」

### 90. Utopia

- 链接：[https://utopia.fyi/](https://utopia.fyi/)
- 主要功能：流体字号/间距比例计算工具【文】
- 内容/资源类型：工具
- 定位标签：字体 / 前端代码
- 适用场景与价值：生成响应式字号阶梯给前端/AI
- 收录作品风格倾向：—
- 网站自身界面：—（未做视觉核验）
- 关联风格：S01 瑞士/国际主义风格
- 文章原话：很多新手画页面时，大标题设 32px、小标题设 22px、正文设 14px，全是拍脑袋瞎填的，最后页面看着毫无秩序。这个小工具就是帮你按「数学比例」定字号的：分别填好手机和电脑上的正文字号，再选一个缩放倍率（比如大三度 1.250），它自动算出一整套会随屏幕宽度平滑缩放的字号变量，间距也能一起算。免费、不用注册，生成的 CSS 复制下来就能用，也可以直接丢给 AI 当排版规范。
- 站点自述（访问所得 meta）：Fluid responsive design
- 来源：文章第 90 条
- 核验状态：**已访问核验** —— HTTP 200；页面标题「Fluid Responsive Design | Utopia」

### 91. Coolors

- 链接：[https://coolors.co/](https://coolors.co/)
- 主要功能：随机配色生成工具，支持色盲模拟、导出【文】
- 内容/资源类型：工具
- 定位标签：配色
- 适用场景与价值：快速出配色方案
- 收录作品风格倾向：—
- 网站自身界面：—（未做视觉核验）
- 关联风格：—（工具类，不绑定风格）
- 文章原话：最好用的傻瓜式配色工具。打开网页什么都不用设置，直接敲键盘空格键，屏幕上就会随机刷出一组五色卡；看到顺眼的颜色点一下锁头把它锁死，再继续敲空格，算法就会自动围绕你锁住的颜色去配剩下的颜色。支持一键模拟色盲用户眼里的画面，还能直接把色卡导出成图片或代码。
- 站点自述（访问所得 meta）：Generate or browse beautiful color combinations for your designs.
- 来源：文章第 91 条
- 核验状态：**已访问核验** —— HTTP 200；页面标题「Coolors - The super fast color palettes generator!」

### 92. Realtime Colors

- 链接：[https://www.realtimecolors.com/](https://www.realtimecolors.com/)
- 主要功能：实时预览配色在落地页上的效果，导出 Tailwind/CSS【文】
- 内容/资源类型：工具
- 定位标签：配色 / 网页
- 适用场景与价值：验证配色在真实页面和深色模式下的效果
- 收录作品风格倾向：—
- 网站自身界面：—（未做视觉核验）
- 关联风格：—（工具类，不绑定风格）
- 文章原话：存了一堆好看的五色卡，真到画页面时还是抓瞎——不知道哪个色填背景、哪个色涂按钮、哪个色写正文。这个工具解决的就是这个痛点：你可以在底部工具栏自己挑（或者随机摇出）文字色、背景色、主色、次色和强调色，上面的标准落地页和后台图表会实时跟着变色，还能随时点一下太阳/月亮图标看这套颜色切到深色模式会不会翻车。调好之后能直接导出 Tailwind 配置、CSS 变量，或者用它的同名插件一键同步进 Figma。
- 来源：文章第 92 条
- 核验状态：**无法访问** —— HTTP 402「Deployment Paused」（Vercel 部署暂停，www/非 www 均如此）

### 93. Radix Colors

- 链接：[https://www.radix-ui.com/colors](https://www.radix-ui.com/colors)
- 主要功能：Radix 12 级界面配色系统，含深色【文】
- 内容/资源类型：配色系统
- 定位标签：配色 / 设计系统 / UI/UX
- 适用场景与价值：界面用色规则化
- 收录作品风格倾向：—
- 网站自身界面：—（未做视觉核验）
- 关联风格：S28 克制产品风（Linear/Vercel 式）, S21 深色科技风
- 文章原话：开源组件库 Radix 配套的一整套界面配色。它给的不是几组好看的色卡，而是把每种颜色拆成 12 级，并且规定好了每一级干什么用：哪几级当背景、哪几级给按钮悬停、哪几级画边框、哪几级写文字，深色模式也一并配好了。照着这套规矩用色，页面很难乱；跟 AI 说一句「颜色按 Radix 的 12 级来用」，也比说「配色高级一点」管用。
- 站点自述（访问所得 meta）：An open-source color system for designing beautiful, accessible websites and apps.
- 来源：文章第 93 条
- 核验状态：**已访问核验** —— HTTP 200；页面标题「Radix Colors」

### 94. tweakcn

- 链接：[https://tweakcn.com/](https://tweakcn.com/)
- 主要功能：shadcn/ui 可视化换肤编辑器，开源【文】
- 内容/资源类型：工具
- 定位标签：配色 / 字体 / 前端代码 / UI/UX
- 适用场景与价值：避免 shadcn 千站一面
- 收录作品风格倾向：—
- 网站自身界面：—（未做视觉核验）
- 关联风格：S28 克制产品风（Linear/Vercel 式）, S04 新粗野主义
- 文章原话：现在用 AI 写前端，很多人用的都是 shadcn/ui 这套组件，结果就是满大街的网站长得一模一样——这也是作者做它的原因。tweakcn 是给 shadcn 换皮的可视化编辑器：颜色、字体、圆角、阴影在左边调，右边的卡片、表单、仪表盘实时变样，还有一堆预设主题可以直接套，调满意了导出主题代码贴进项目就行。免费开源。
- 站点自述（访问所得 meta）：Customize theme for shadcn/ui with tweakcn's interactive editor. Supports Tailwind CSS v4, Shadcn UI, and custom styles. Modify properties, preview changes, and
- 来源：文章第 94 条
- 核验状态：**已访问核验** —— HTTP 200；页面标题「Beautiful themes for shadcn/ui — tweakcn | Theme Editor & Ge」

## 九、日常收集灵感

### 95. Pinterest

- 链接：[https://www.pinterest.com/](https://www.pinterest.com/)
- 主要功能：全网最大图片灵感库【文】
- 内容/资源类型：图片
- 定位标签：灵感 / 收藏工具 / 平面 / 摄影/电影
- 适用场景与价值：顺藤摸瓜收集同风格参考，建私密画板
- 收录作品风格倾向：全风格；混入 AI 粗糙图【文】
- 网站自身界面：—（未做视觉核验）
- 关联风格：S12 复古/怀旧, S14 日式/无印风, S15 新中式, S23 可爱/卡哇伊
- 文章原话：图库体量依然是全网第一，尤其适合顺藤摸瓜：找准一张对味的参考图点进去，顺着底下的「相似图片」一路往下点，十分钟就能拉出几十张同风格的图。缺点是这两年首页信息流里混进了不少粗糙的 AI 生成图和营销号杂图，建议建几个私密画板（Board），只钉真正精挑细选过的好图，把推荐算法慢慢养干净。
- 站点自述（访问所得 meta）：Discover recipes, home ideas, style inspiration and other ideas to try.
- 来源：文章第 95 条
- 核验状态：**已访问核验** —— HTTP 200；页面标题「Pinterest」

### 96. Are.na

- 链接：[https://www.are.na/](https://www.are.na/)
- 主要功能：无广告无算法的研究资料收集工具【文】
- 内容/资源类型：收藏工具
- 定位标签：收藏工具 / 灵感
- 适用场景与价值：课题研究资料积累
- 收录作品风格倾向：—
- 网站自身界面：长得非常素，无广告无点赞【文】
- 关联风格：S02 极简主义, S03 粗野主义（网页）
- 文章原话：设计圈里很多极客、建筑师和独立撰稿人偏爱的资料收集工具。它长得非常素，没有广告、没有算法信息流、甚至连「点赞数」都没有。你可以建不同的频道（Channel），把图片、PDF 文献、网页链接、随手记的一段话塞进去，还能把自己的频道跟全世界其他人的公开频道串联起来。很适合安安静静攒某个特定课题的研究资料。
- 站点自述（访问所得 meta）：Are.na is a platform for connecting ideas and building knowledge.
- 来源：文章第 96 条
- 核验状态：**已访问核验** —— HTTP 200；页面标题「Are.na」

### 97. Cosmos

- 链接：[https://www.cosmos.so/](https://www.cosmos.so/)
- 主要功能：新一代灵感收藏夹，浏览器插件，发现页【文】
- 内容/资源类型：收藏工具
- 定位标签：收藏工具 / 灵感
- 适用场景与价值：收集高质量创意参考
- 收录作品风格倾向：高审美创意人收藏【文】
- 网站自身界面：界面排版极其干净【文】
- 关联风格：S02 极简主义, S13 编辑/杂志风
- 文章原话：这两年在海外设计师圈子里蹿红的新一代灵感收藏夹。装上它的浏览器插件，平时在推特或任何网站上看到好图、好视频，右键一下就能收进自己的空间。它的界面排版极其干净，而且因为早期用户大多是审美在线的创意人，直接在它的发现页（Discover）里逛别人公开的收藏夹，图片质量非常高。
- 站点自述（访问所得 meta）：Your space for inspiration
- 来源：文章第 97 条
- 核验状态：**已访问核验** —— HTTP 200；页面标题「Cosmos」

### 98. Savee

- 链接：[https://savee.com/](https://savee.com/)
- 主要功能：视觉设计师极简图片社区【文】
- 内容/资源类型：图片
- 定位标签：灵感 / 平面 / 品牌 / 摄影/电影
- 适用场景与价值：平面排版、品牌包装、先锋摄影、字体、工业造型参考
- 收录作品风格倾向：高级感平面【文】
- 网站自身界面：满屏高清大图瀑布流，无多余文字【文】
- 关联风格：S01 瑞士/国际主义风格, S02 极简主义, S13 编辑/杂志风, S22 奢华/高端
- 文章原话：专门做给视觉设计师看的极简图片社区。打开网站连多余的文字标题都没有，满屏就是干干净净的高清大图瀑布流。上面沉淀的内容非常纯粹，基本集中在平面排版、品牌包装、先锋摄影、字体设计和工业造型，想找高级感平面参考时，来这儿刷比去综合平台效率高得多。
- 站点自述（访问所得 meta）：Savee is a curated place for visual inspiration. Discover references chosen by designers, collect what matters, and build a sharper eye without ads or clutter.
- 来源：文章第 98 条
- 核验状态：**已访问核验** —— HTTP 200；页面标题「Savee」

### 99. It's Nice That

- 链接：[https://www.itsnicethat.com/](https://www.itsnicethat.com/)
- 主要功能：伦敦创意文化媒体：插画/平面/动画/摄影【文】
- 内容/资源类型：文章
- 定位标签：灵感 / 插画 / 平面 / 摄影/电影
- 适用场景与价值：看创作者故事与新作品
- 收录作品风格倾向：插画、平面、动画、摄影【文】
- 网站自身界面：—（未做视觉核验）
- 关联风格：S18 有机/手绘, S13 编辑/杂志风, S26 实验/反设计
- 文章原话：伦敦办了很多年的创意文化媒体。每天更新几篇短文章，聊全球各地最新的插画、平面、动画、摄影项目。它好看的地方在于不光贴图，编辑很会挖创作者背后的好玩故事——比如这个奇怪的字体是怎么因为一次印刷失误弄出来的、那支荒诞的短片导演当时在想什么。很适合当午饭时的电子榨菜。
- 站点自述（访问所得 meta）：Inspiring Creativity
- 来源：文章第 99 条
- 核验状态：**已访问核验** —— HTTP 200；页面标题「It's Nice That」

### 100. Brand New（付费/部分付费，据文章）

- 链接：[https://www.underconsideration.com/brandnew/](https://www.underconsideration.com/brandnew/)
- 主要功能：品牌换标点评站（付费看全文）【文】
- 内容/资源类型：品牌案例点评
- 定位标签：品牌 / 平面 / 字体
- 适用场景与价值：品牌识别新旧对比、练品牌判断力
- 收录作品风格倾向：企业/机构品牌识别【文+访】
- 网站自身界面：—（未做视觉核验）
- 关联风格：S01 瑞士/国际主义风格, S02 极简主义, S05 包豪斯
- 文章原话：全球品牌换标（Rebranding）的专业点评网站。只要国内外稍微有点名气的公司、大学、体育联赛或者消费品换了新 Logo 和新视觉系统，这里就会第一时间把旧版和新版并排摆出来，从字体微调、图形演变到实际延展应用做一番客观（有时相当毒舌）的拆解，底下还有全球同行投票打分（付费，不订阅只能看到新旧 Logo 的对比图）。常看这个站，能很快练出看透商业品牌设计好坏的眼力。
- 站点自述（访问所得 meta）：Opinions on corporate and brand identity work
- 来源：文章第 100 条
- 核验状态：**已访问核验** —— HTTP 200；页面标题「Brand New」
