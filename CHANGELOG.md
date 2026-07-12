# Changelog

## v1.4.0 — 2026-07-12
- 配色调整：「正确结论」语义色**重新固定为蓝 `#5f9cef`**（红=警示、蓝=正确双语义色固定，不随主题漂移）。主题色候选库移除蓝，避免与正确蓝撞色。
- ✓ 正确结论类元素（A 误区框正确句 / D 知识链接-正确办理方式）在模板中显式用 `#5f9cef`；其余结构色（标题条、子标题芯片、举个例子、Q、大数字、时间线、点位名）仍跟随主题色。
- 同步更新 SKILL.md / README / references / apply_theme_color.py（脚本 FIXED 恢复 `#5f9cef` 保护，候选库移除蓝）。

## v1.3.0 — 2026-07-12
- 配色调整：取消「正确蓝」固定语义色，**正向色(✓正确结论/正向强调)改为跟随主题色**（可换），只保留警示红 `#ff0000` 固定。蓝 `#5f9cef` 重新回到主题色候选库。
- 9 套模板统一加**三级小标题底色**：大分节=实底主题色条白字；子标题/标签=浅灰芯片(主题色字+左边框)；警示块(请注意/注意！/❎错误/IP郑重提醒)=浅红底 `#FDECEC`+红字（避免实底红刺眼）。
- 同步更新 SKILL.md / README / references / apply_theme_color.py（脚本 FIXED 仅保留 `#ff0000`，正向色随主题色一并替换）。

## v1.2.0 — 2026-07-12
- 内容类型从 6 类扩展到 9 类：新增 F 活动宣传/工作动态、G 年度盘点/数据战报、H 路线攻略/分类合集。
- 回写 C 办事指南（深度变体：多层嵌套 + 材料编号清单）、E 互动答疑（尾部模块：注意事项 + 相关链接）。
- 更新路由表、组件库骨架（大数字高亮 / 时间线 / 路线块 / 点位子卡片）、README 类型表（6→9）。
- 同步修正换色脚本示例（`#5f9cef` 现为正确蓝固定色，示例改用 `#be5960` 等主题色）。

## v1.1.0 — 2026-07-12
- 配色调整：「正确结论」语义色由绿色 `#2E9E5B` 改为固定蓝 `#5f9cef`（红=警示、蓝=正确）。
- 蓝色从主题色候选库移除，避免与正确蓝撞色；案例类主题色建议改为玫红 `#be5960`。
- 同步更新 SKILL.md / README / references / 6 套模板 / apply_theme_color.py（脚本已将 `#5f9cef` 纳入 FIXED 保护）。

## v1.0.0 — 2026-07-11
- Initial release.
- Six layout templates for 民生政务 public-service accounts: myth-busting / new-policy explainer / notice / how-to guide / cautionary case / Q&A.
- Swappable theme-color slot (theme `#ff6d4d` + fixed warn `#ff0000` + correct `#5f9cef`).
- Inline-style only → paste directly into the WeChat editor, no 135 editor required.
- Bundled: SKILL.md, README(.md / _EN.md), LICENSE, CHANGELOG, references (color / component / sop), assets (6 templates + icon), scripts/apply_theme_color.py.
