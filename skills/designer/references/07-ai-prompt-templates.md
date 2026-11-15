# 07 · AI 视觉提示词模板

依据：模板为编者根据通用设计知识与 AI 生图常见写法编写【通】；「用具体名称和手法跟 AI 说话」的思路来自 EianLu 文章最后一节【文】。模板未针对某一模型做系统测试，效果因模型而异。
用法：把 `{花括号}` 替换成具体内容；中英文二选一（多数生图模型英文更稳，中文模型可直接用中文）；先出 4 张小图挑方向，再加细节。

## 通用骨架

```
{主体} ，{风格名} 风格，{构图/镜头}，{配色}，{光线/材质}，{字体/文字要求}，{画幅比例}，{排除项}
{subject}, {style} style, {composition/camera}, {color palette}, {lighting/material}, {typography}, aspect ratio {ratio}, avoid {negatives}
```

## 十大精选风格模板

### 1 极简主义（S02）
```
中：一瓶{产品}居中摆放在纯白背景上，极简主义，大量留白，柔和自然侧光，浅灰投影，黑白灰配色加一点{点缀色}，干净无装饰，4:5
EN: a single {product} centered on a pure white background, minimalist, generous negative space, soft natural side light, subtle gray shadow, monochrome palette with a touch of {accent color}, clean, no decoration, 4:5
```
提示：加 "negative space" "single focal point"；排除 "clutter, busy background, extra props"。

### 2 瑞士国际主义（S01）
```
中：{主题}海报，瑞士国际主义平面设计，严格网格，左对齐粗体无衬线大标题，黑白加红色，几何色块，非对称构图，印刷质感，3:4
EN: {topic} poster, Swiss International Typographic Style, strict modular grid, flush-left bold sans-serif headline, black white and red, geometric shapes, asymmetric layout, offset print texture, 3:4
```
提示：生图模型写字常出错，标题文字建议出图后在设计软件里替换；用 "Josef Müller-Brockmann inspired grid" 这类流派描述，不要指定在世设计师模仿。

### 3 克制产品风（S28）
```
中：一个{产品类型} SaaS 网页界面截图，克制的产品设计风格，中性灰阶，单一{品牌色}强调，1px 细边框，精确 8px 间距，清晰层级，真实数据，无发光特效，16:10
EN: UI screenshot of a {product type} SaaS dashboard, refined product design, neutral gray scale, single {brand color} accent, 1px hairline borders, precise 8px spacing, clear hierarchy, realistic data, no glow effects, 16:10
```
提示：写代码时更有效的是给 AI 一份 DESIGN.md（[awesome-design-md](https://github.com/VoltAgent/awesome-design-md)）并让它按 [Vercel 规范](https://vercel.com/design/guidelines) 自查【文】。

### 4 深色科技风（S21）
```
中：{产品}发布主视觉，深色科技风，近黑背景，产品居中，细线网格，微弱{青色/绿色}边缘光，低噪点，冷静专业，16:9
EN: launch key visual for {product}, dark mode tech aesthetic, near-black background, product centered, faint line grid, subtle {cyan/lime} rim light, fine grain, calm and professional, 16:9
```
提示：排除 "lens flare, excessive glow, light beams"，避免文章提到的廉价发光套路【文】。

### 5 Bento 网格（S24）
```
中：{产品}功能介绍信息图，Bento 便当盒网格布局，6 个大小不一的圆角卡片，每个卡片一个功能图标和短标题，{浅色/深色}背景，统一圆角和间距，现代几何无衬线字体，1:1
EN: feature overview infographic for {product}, bento grid layout, six rounded cards of varying sizes, each with one icon and short title, {light/dark} background, consistent corner radius and gutters, modern geometric sans-serif, 1:1
```
提示：卡片文案后期替换；指定 "largest card top-left for hero feature"。

### 6 新粗野主义（S04）
```
中：{活动/产品}社媒海报，新粗野主义风格，粗黑描边卡片，无模糊硬投影，明黄粉色薄荷色块，超粗无衬线标题，手绘星星箭头贴纸，俏皮直接，4:5
EN: social media poster for {event/product}, neo-brutalism, thick black outlines, hard offset shadows with no blur, bright yellow pink and mint blocks, ultra-bold sans-serif headline, hand-drawn star and arrow stickers, playful, 4:5
```
提示：排除 "gradient, soft shadow, realistic photo"。

### 7 编辑杂志风（S13）
```
中：{主题}杂志跨页版式，编辑设计风格，衬线大标题，三栏正文，放大引言，出血人物摄影，纸张米白底，墨黑文字，一处{品牌色}点缀，3:2
EN: magazine spread about {topic}, editorial layout, large serif headline, three-column body text, oversized pull quote, full-bleed portrait photography, off-white paper, ink black text, one {brand color} accent, 3:2
```

### 8 电影感（S25）
```
中：{场景描述}，电影画面，2.39:1 宽画幅，{低角度/推镜}，黄金时刻逆光，浅景深，青橙调色，暗部压黑，35mm 胶片颗粒
EN: {scene}, cinematic film still, 2.39:1 anamorphic, {low angle / dolly in}, golden hour backlight, shallow depth of field, teal and orange grade, crushed blacks, 35mm film grain
```
提示：镜头术语查 [StudioBinder](https://www.studiobinder.com/blog/ultimate-guide-to-camera-shots/) 与 [EyeCannndy](https://eyecannndy.com/)：写 "low angle" "dolly in" "whip pan" 比「拍得高级一点」管用【文】。

### 9 新中式（S15）
```
中：{产品，如：茶叶礼盒}主视觉，新中式风格，大面积留白，水墨远山，朱砂红印章点缀，宋体竖排标题，宣纸肌理，月白与黛青配色，雅致克制，3:4
EN: key visual for {product, e.g. tea gift box}, modern Chinese (neo-Chinese) aesthetic, generous negative space, ink-wash distant mountains, vermilion seal accent, vertical serif Chinese title, rice paper texture, pale blue-white and indigo palette, elegant and restrained, 3:4
```
提示：排除 "dragon, excessive gold, cluttered patterns"；汉字务必后期替换为正版字体。

### 10 3D 黏土风（S19）
```
中：{物体/角色}的 3D 黏土风插图，圆润倒角，柔和棚拍光，马卡龙配色，软阴影，纯色背景，可爱简洁，C4D/Blender 渲染质感，1:1
EN: 3D clay style illustration of {object/character}, rounded bevels, soft studio lighting, pastel macaron palette, soft shadows, solid background, cute and simple, Blender render, 1:1
```
提示：电商主图改为 "photorealistic PBR materials, HDRI studio lighting"。

## 按用途的补充模板

| 用途 | 模板（中 / EN） |
|---|---|
| 电商主图 | 白底/浅色背景{产品}，45° 视角，柔光，倒影，留出右侧文字区，1:1 ／ {product} on light background, 45-degree view, soft light, subtle reflection, empty space on the right for copy, 1:1 |
| 品牌 Logo 探索 | {品牌名}标志设计，{风格}，简洁矢量，单色，白底，多个方案网格排列 ／ logo exploration for {brand}, {style}, simple vector mark, monochrome, white background, grid of variations |
| 社媒封面 | {主题}小红书封面，{风格}，大标题区留白，3:4 ／ {topic} social cover, {style}, large headline space, 3:4 |
| App 插图 | {场景}空状态插画，{风格}，与 UI 配色 {色值} 一致，透明背景 ／ empty-state illustration of {scene}, {style}, matching UI colors {hex}, transparent background |
| 情绪板 | {项目}情绪板，9 宫格，{风格}，包含配色条与字体样张 ／ moodboard for {project}, 3x3 grid, {style}, include color swatches and type specimen |

## 使用技巧

1. 结构顺序：主体 → 风格 → 构图镜头 → 配色 → 光线材质 → 比例 → 排除项；越靠前权重通常越高。
2. 混搭写法：主风格放前面，辅风格只借一个元素，例如「瑞士网格海报，带一枚朱砂印章」（见 `06-hybrid-combos.md`）。
3. 色值比色名稳定：给出 2–4 个 HEX。
4. 文字：多数生图模型中文字渲染不稳定，标题留白后在设计软件中排版。
5. 参考图优先：支持图生图的工具里，先从本库网站（如 [StillsLab](https://stillslab.com/)、[Savee](https://savee.com/)）找参考图，比纯文字描述准确【文的思路】。注意参考图版权，只作风格参考，不直接商用。
6. 不要在提示词中要求模仿在世艺术家/工作室的个人作品（版权与伦理风险），改用风格与手法描述。
7. 出图后按 [Impeccable](https://impeccable.style/) 等清单检查是否有「AI 味」套路【文】。
