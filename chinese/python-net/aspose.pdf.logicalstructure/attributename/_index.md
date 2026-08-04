---
title: "AttributeName"
second_title: "Aspose.PDF for Python via .NET API 参考"
description: "表示属性名称值的类。"
type: docs
weight: 50
url: /zh/python-net/aspose.pdf.logicalstructure/attributename/
---

## AttributeName class

表示属性名称值的类。

AttributeName 类型公开以下成员：
## 属性
| 名称 | 描述 |
| :- | :- |
| 名称 | 获取属性的名称值。 |
| attribute_key | 获取属性键。 |
| PLACEMENT_BLOCK | 属性放置：块 - 在封闭的参考区域或父 BLSE 中沿块进展方向堆叠。 |
| PLACEMENT_INLINE | 属性放置：内联 - 在封闭的 BLSE 中沿内联进展方向打包。 |
| PLACEMENT_BEFORE | 属性放置：之前 - 放置方式使元素分配矩形的前边缘与最近的封闭参考区域的前边缘重合。 |
| PLACEMENT_START | 属性 Placement: Start - 放置方式使元素分配矩形的起始边缘与最近的封闭参考区域的起始边缘重合。 |
| PLACEMENT_END | 属性 Placement: End - 放置方式使元素分配矩形的结束边缘与最近的封闭参考区域的结束边缘重合。 |
| WRITING_MODE_LR_TB | 属性 WritingMode: LrTb - 行内进展从左到右；块进展从上到下。这是西方书写系统的典型书写模式。 |
| WRITING_MODE_RL_TB | 属性 WritingMode: RlTb - 行内进展从右到左；块进展从上到下。这是阿拉伯语和希伯来语书写系统的典型书写模式。 |
| WRITING_MODE_TB_RL | 属性 WritingMode: TbRl - 行内进展从上到下；块进展从右到左。这是中文和日文书写系统的典型书写模式。 |
| BORDER_STYLE_NONE | 属性 BorderStyle: None - 无边框。强制将计算得到的 BorderThickness 值设为 0。 |
| BORDER_STYLE_HIDDEN | 属性 BorderStyle: Hidden - 与 None 相同，只是在表格元素的边框冲突解决方面有所不同。 |
| BORDER_STYLE_DOTTED | 属性 BorderStyle: Dotted - 边框由一系列点组成。 |
| BORDER_STYLE_DASHED | 属性 BorderStyle: Dashed - 边框由一系列短线段组成。 |
| BORDER_STYLE_SOLID | 属性 BorderStyle: Solid - 边框是一条单线段。 |
| BORDER_STYLE_DOUBLE | 属性 BorderStyle: Double - 边框由两条实线组成。两条线及其之间的间距之和等于 BorderThickness 的值。 |
| BORDER_STYLE_GROOVE | 属性 BorderStyle: Groove - 边框看起来像是被雕刻在画布上。 |
| BORDER_STYLE_RIDGE | 属性 BorderStyle: Ridge - 边框看起来像是从画布凸起（与 Groove 相反）。 |
| BORDER_STYLE_INSET | 属性 BorderStyle: Inset - 边框使整个盒子看起来像是嵌入在画布中。 |
| BORDER_STYLE_OUTSET | 属性 BorderStyle: Outset - 边框使整个盒子看起来好像从画布中凸出（与 Inset 相反）。 |
| TEXT_ALIGN_START | 属性 TextAlign: Start - 与起始边对齐。 |
| TEXT_ALIGN_CENTER | 属性 TextAlign: Center - 位于起始边和结束边之间居中。 |
| TEXT_ALIGN_END | 属性 TextAlign: End - 与结束边对齐。 |
| TEXT_ALIGN_JUSTIFY | 属性 TextAlign: Justify - 与起始边和结束边对齐，如有必要，通过扩展每行内部的间距来实现此对齐。最后（或唯一）一行仅与起始边对齐。 |
| WIDTH_AUTO | 属性 Width: Auto - 元素的宽度应由其内容的固有宽度决定。 |
| HEIGHT_AUTO | 属性 Height: Auto - 元素的高度应由其内容的固有高度决定。 |
| BLOCK_ALIGN_BEFORE | 属性 BlockAlign: Before - 第一个子元素分配矩形的前边缘与表格单元格内容矩形的前边缘对齐。 |
| BLOCK_ALIGN_MIDDLE | 属性 BlockAlign: Middle- 子元素在表格单元格内居中。第一个子元素分配矩形的前边缘与表格单元格内容矩形的前边缘之间的距离，应等于最后一个子元素分配矩形的后边缘与表格单元格内容矩形的后边缘之间的距离。 |
| BLOCK_ALIGN_AFTER | 属性 BlockAlign: After - 最后一个子元素分配矩形的后边缘与表格单元格内容矩形的后边缘对齐。 |
| BLOCK_ALIGN_JUSTIFY | 属性 BlockAlign: Justify - 子元素与表格单元格内容矩形的前后边缘均对齐。第一个子元素按 Before 的描述放置，最后一个子元素按 After 的描述放置，子元素之间间距相等。如果只有一个子元素，则仅与前边缘对齐，类似 Before。 |
| INLINE_ALIGN_START | 属性 InlineAlign: Start - 每个子元素分配矩形的起始边缘与表格单元格内容矩形的起始边缘对齐。 |
| INLINE_ALIGN_CENTER | 属性 InlineAlign：Center - 每个子项在表格单元格内居中。子项分配矩形的起始边缘与表格单元格内容矩形的起始边缘之间的距离，应与它们的结束边缘之间的距离相同。 |
| INLINE_ALIGN_END | 属性 InlineAlign：End - 每个子项的分配矩形的结束边缘与表格单元格内容矩形的结束边缘对齐。 |
| LINE_HEIGHT_NORMAL | 属性 LineHeight：Normal - 调整行高以包含 BaselineShift 指定的任何非零值。 |
| LINE_HEIGHT_AUTO | 属性 LineHeight：Auto - 不对 BaselineShift 的值进行调整。 |
| TEXT_DECORATION_TYPE_NONE | 属性 TextDecorationType：None - 无文本装饰。 |
| TEXT_DECORATION_TYPE_UNDERLINE | 属性 TextDecorationType：Underline - 文本下方有一条线。 |
| TEXT_DECORATION_TYPE_OVERLINE | 属性 TextDecorationType：Overline - 文本上方有一条线。 |
| TEXT_DECORATION_TYPE_LINE_THROUGH | 属性 TextDecorationType：LineThrough - 文本中部有一条线。 |
| RUBY_ALIGN_START | 属性 RubyAlign：Start - 内容在行内进展方向的起始边缘对齐。 |
| RUBY_ALIGN_CENTER | 属性 RubyAlign：Center - 内容在行内进展方向居中。 |
| RUBY_ALIGN_END | 属性 RubyAlign：End - 内容在行内进展方向的结束边缘对齐。 |
| RUBY_ALIGN_JUSTIFY | 属性 RubyAlign：Justify - 内容将在行内进展方向上扩展以填满可用宽度。 |
| RUBY_ALIGN_DISTRIBUTE | 属性 RubyAlign：Distribute - 内容将在行内进展方向上扩展以填满可用宽度。但同时会在文本的起始边缘和结束边缘插入空白。间距采用 1:2:1（起始:中间:结束）的比例分配。如果 ruby 出现在文本行的起始位置，则比例改为 0:1:1；如果 ruby 出现在文本行的结束位置，则比例改为 1:1:0。 |
| RUBY_POSITION_BEFORE | 属性 RubyPosition: Before - RT 内容应沿元素的前边缘对齐。 |
| RUBY_POSITION_AFTER | 属性 RubyPosition: After - RT 内容应沿元素的后边缘对齐。 |
| RUBY_POSITION_WARICHU | 属性 RubyPosition: Warichu - RT 及其关联的 RP 元素应在 RB 元素之后以 warichu 形式排版。 |
| RUBY_POSITION_INLINE | 属性 RubyPosition: Inline - RT 及其关联的 RP 元素应在 RB 元素之后以括号注释形式排版。 |
| GLYPH_ORIENTATION_VERTICAL_AUTO | 属性 GlyphOrientationVertical: Auto - 指定文本的默认方向，取决于其是否为全宽（宽度等于高度）。 |
| LIST_NUMBERING_NONE | 属性 ListNumbering: None - 不进行自动编号；Lbl 元素（如果存在）包含任意文本，不受任何编号方案约束。 |
| LIST_NUMBERING_DISC | 属性 ListNumbering: Disc - 实心圆形项目符号。 |
| LIST_NUMBERING_CIRCLE | 属性 ListNumbering: Circle - 空心圆形项目符号。 |
| LIST_NUMBERING_SQUARE | 属性 ListNumbering: Square - 实心方形项目符号。 |
| LIST_NUMBERING_DECIMAL | 属性 ListNumbering: Decimal - 十进制阿拉伯数字（1-9，10-99，...）。 |
| LIST_NUMBERING_UPPER_ROMAN | 属性 ListNumbering: UpperRoman - 大写罗马数字（I、II、III、IV、...）。 |
| LIST_NUMBERING_LOWER_ROMAN | 属性 ListNumbering: LowerRoman - 小写罗马数字（i、ii、iii、iv、...）。 |
| LIST_NUMBERING_UPPER_ALPHA | 属性 ListNumbering：UpperAlpha - 大写字母 (A, B, C, ...)。 |
| LIST_NUMBERING_LOWER_ALPHA | 属性 ListNumbering：LowerAlpha - 小写字母 (a, b, c, ...)。 |
| ROLE_RB | 属性 Role：rb - 单选按钮。 |
| ROLE_CB | 属性 Role：cb - 复选框。 |
| ROLE_PB | 属性 Role：pb - 推钮。 |
| ROLE_TV | 属性 Role：tv - 文本值字段。 |
| CHECKED_ON | 属性 checked：On - 单选按钮或复选框字段的状态为开启。 |
| CHECKED_OFF | 属性 checked：Off - 单选按钮或复选框字段的状态为关闭。 |
| CHECKED_NEUTRAL | 属性 checked：Neutral - 单选按钮或复选框字段的状态为中性。 |
| SCOPE_ROW | 属性 Scope：Row - 行。 |
| SCOPE_COLUMN | 属性 Scope：Column - 列。 |
| SCOPE_BOTH | 属性 Scope：Both - 两者。 |
## 方法
| 名称 | 描述 |
| :- | :- |
| from_name_attribute_key(name, attribute_key) | 获取属性键对应的属性名称。 |

### 另请参阅

* namespace [aspose.pdf.logicalstructure](/pdf/python-net/aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](/pdf/python-net/)

