# 08 · 第五轮复核记录（2026-11-14）

## 事实复核

- 文章条目数：100 条，编号 1–100 连续，9 个分类数量与文章开头声明完全一致（12/14/9/7/16/10/16/10/6）。
- 去重：100 个 URL 无重复，名称无重复。同域名仅 developer.apple.com（第 6 条 Apple Design Awards 与第 49 条 Apple HIG，是两个不同栏目，保留）。
- 链接一致性：05/06/07 中引用的所有网站链接都能在 01 中找到，无库外链接。
- 核验结果：已访问核验 97 ｜ 无法访问 1 ｜ 仅凭文章描述 2。

| 编号 | 网站 | 情况 | 处理 |
|---|---|---|---|
| 92 | Realtime Colors | HTTP 402「Deployment Paused」，www 与非 www 均如此；WebFetch 同样 402 | 标「无法访问」，描述仅保留文章原话；推荐时需提示用户可能暂时不可用 |
| 17 | Behance 动态设计专区 | curl 403，WebFetch 超时 | 标「仅凭文章描述」 |
| 27 | ArtStation | curl 403，WebFetch 500 | 标「仅凭文章描述」 |
| 36/60/70/73 | ShotDeck / Siteinspire / CodePen Spark / Shadertoy | curl 被 Cloudflare/Vercel 验证页拦截，WebFetch 取到真实内容 | 标「已访问核验」，注明经 WebFetch |
| 24/75 | Oddfellows / Bruno Simon | 首次 TLS 握手失败，重试正常 | 已访问核验 |
| 58 | Game UI Database | 站点自述「1,300+ 游戏、55,000 截图」与文章「近 2000 款、7 万多张」不一致 | 两者并列记录，待复核 |
| 84 | Emil Kowalski | 站点 meta「Design engineer working at Linear」与文章「之前在 Linear」不一致 | 并列记录，待复核 |
| 59 | Recent（原 Godly） | 已核验 godly.website 跳转至 recent.design | 与文章一致 |
| 85 | Typewolf | 文章称 2025 年底后停更，未独立核验 | 保留文章说法并注明 |

## 分类一致性

- 01 保留文章原 9 类；另加「定位标签」（多标签）做横向检索，标签词表统一为 20 个（见 04），已合并「摄影」与「摄影/电影」。
- 风格编号 S01–S29 全库统一；02、03、04、05、06、07 使用同一套编号。

## 已知缺口（文章覆盖面）

文章作者以视频、UI、前端为主（文章自述），因此本库在以下方面资源不足，推荐时需说明或请用户补充（补充必须带来源）：

- 中文/中式设计资源：无站酷、花瓣、古田路 9 号等中文平台；新中式风格无直接参考站。
- 平面海报、包装、插画、摄影专门站点较少（主要靠 Savee、Pinterest、It's Nice That、Fonts In Use、D&AD、Tokyo TDC）。
- 电商视觉：无电商详情页/主图专门参考站。
- 品牌 VI：仅 Brand New（付费）、D&AD、One Show/ADC。
- AI 生图：无 Midjourney 等生图工具或提示词社区（仅 Runway AIF、Flim）。
- 网站「自身界面风格」：无头浏览器截图失败，仅记录文章明确描述的 9 个站点的界面特征，其余未做视觉核验。

## 方法限制

- 核验只读取首页 HTTP 状态、标题与 meta 描述，没有逐页浏览内容，也没有核实付费墙细节。
- 受众、情绪、行业适配全部为推测，没有数据来源。
