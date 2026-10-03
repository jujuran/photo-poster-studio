# Photo Poster Studio

A reusable Codex Skill that turns each source photograph into a separate, art-directed poster. It includes six named styles, automatic style recommendations, per-style acceptance checks, and a workflow that protects subject identity and source order.

## Style catalog

| Style | Best for | Default format | Visual direction |
| --- | --- | --- | --- |
| `quiet-editorial-split` | Poetic photos, editorial stories | 3:4 | Faithful photo above, minimal handmade illustration below |
| `cinematic-story-poster` | Travel, street, landscape, emotional portraits | 2:3 | Filmic light, atmospheric depth, restrained title card |
| `swiss-photo-grid` | Architecture, fashion, products, brands | 4:5 | Asymmetric grid, bold geometry, disciplined typography |
| `risograph-pulse` | Music, events, youth culture, retro themes | 3:4 | Two or three inks, halftones, paper grain, print energy |
| `paper-cut-diary` | Family, pets, food, crafts, personal memories | 4:5 | Photo window, cut paper, tape, warm handwritten details |
| `museum-archive` | Artworks, objects, documentary and historical photos | 3:4 | Exhibition margins, catalog labels, archival restraint |

## Usage

Invoke `$photo-poster-studio` and upload one or more photographs. You can name a style directly:

> Use `$photo-poster-studio` with `risograph-pulse` to turn these photos into separate posters.

Or let the Skill recommend one:

> Use `$photo-poster-studio` to choose the best style for each uploaded photo and make separate posters.

Every input photo is inspected and processed independently. The Skill does not merge images into a collage unless the selected style explicitly calls for it.

## Extend the catalog

Add substantial styles as separate files under `references/styles/`, then register each one in `SKILL.md`. Keep shared workflow rules in `SKILL.md` and composition, palette, typography, exclusions, and acceptance checks in the style reference.

---

# 照片海报工作室

这是一个可复用的 Codex Skill，可把每张原始照片分别制作成经过艺术指导的海报。当前包含 6 种命名风格、自动风格推荐、逐风格验收标准，并在处理过程中保护人物身份、照片内容和输入顺序。

## 风格目录

| 风格 | 适合内容 | 默认比例 | 视觉方向 |
| --- | --- | --- | --- |
| `quiet-editorial-split` | 诗意照片、编辑故事 | 3:4 | 上半部真实照片，下半部极简手绘插画 |
| `cinematic-story-poster` | 旅行、街头、风景、情绪人像 | 2:3 | 电影光影、空间氛围、克制片名字体 |
| `swiss-photo-grid` | 建筑、时尚、产品、品牌 | 4:5 | 非对称网格、大胆几何、严谨字体 |
| `risograph-pulse` | 音乐、活动、青年文化、复古主题 | 3:4 | 两至三色油墨、网点、纸张颗粒、印刷张力 |
| `paper-cut-diary` | 家庭、宠物、美食、手作、私人回忆 | 4:5 | 照片窗口、剪纸、胶带、温暖手写细节 |
| `museum-archive` | 艺术品、物件、纪实与历史照片 | 3:4 | 展览留白、馆藏标签、档案气质 |

## 使用方法

调用 `$photo-poster-studio` 并上传一张或多张照片。可以直接指定风格：

> 使用 `$photo-poster-studio` 的 `risograph-pulse` 风格，把这些照片分别做成海报。

也可以让 Skill 推荐：

> 使用 `$photo-poster-studio`，为每张上传的照片选择最合适的风格，并分别生成海报。

每张输入照片都会独立检查和处理。除非所选风格明确需要，否则不会把多张照片合并成拼贴。

## 扩展风格库

新增完整风格时，在 `references/styles/` 下创建独立文件，并在 `SKILL.md` 中登记。通用流程放在 `SKILL.md`，构图、配色、字体、禁用项和验收标准放在风格参考文件中。
