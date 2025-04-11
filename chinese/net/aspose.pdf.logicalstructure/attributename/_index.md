---
title: Class AttributeName
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.LogicalStructure.AttributeName 类。表示属性名称值的类
type: docs
weight: 6220
url: /zh/net/aspose.pdf.logicalstructure/attributename/
---
## AttributeName 类

表示属性名称值的类。

```csharp
public sealed class AttributeName
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [AttributeKey](../../aspose.pdf.logicalstructure/attributename/attributekey/) { get; } | 获取属性键。 |
| [Name](../../aspose.pdf.logicalstructure/attributename/name/) { get; } | 获取属性的名称值。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [FromNameAttributeKey](../../aspose.pdf.logicalstructure/attributename/fromnameattributekey/)(string, AttributeKey) | 获取属性键的属性名称。 |
| override [ToString](../../aspose.pdf.logicalstructure/attributename/tostring/)() | 返回一个表示当前对象的字符串。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| static readonly [BlockAlign_After](../../aspose.pdf.logicalstructure/attributename/blockalign_after/) | 属性 BlockAlign: After - 最后一个子元素的分配矩形的后边缘与表格单元格内容矩形的后边缘对齐。 |
| static readonly [BlockAlign_Before](../../aspose.pdf.logicalstructure/attributename/blockalign_before/) | 属性 BlockAlign: Before - 第一个子元素的分配矩形的前边缘与表格单元格内容矩形的前边缘对齐。 |
| static readonly [BlockAlign_Justify](../../aspose.pdf.logicalstructure/attributename/blockalign_justify/) | 属性 BlockAlign: Justify - 子元素与表格单元格内容矩形的前后边缘对齐。第一个子元素应按前边缘描述放置，最后一个子元素应按后边缘描述放置，子元素之间的间距相等。如果只有一个子元素，则仅与前边缘对齐，如同前边缘。 |
| static readonly [BlockAlign_Middle](../../aspose.pdf.logicalstructure/attributename/blockalign_middle/) | 属性 BlockAlign: Middle- 子元素在表格单元格内居中。第一个子元素的分配矩形的前边缘与表格单元格内容矩形的前边缘之间的距离应与最后一个子元素的分配矩形的后边缘与表格单元格内容矩形的后边缘之间的距离相同。 |
| static readonly [BorderStyle_Dashed](../../aspose.pdf.logicalstructure/attributename/borderstyle_dashed/) | 属性 BorderStyle: Dashed - 边框是一系列短线段。 |
| static readonly [BorderStyle_Dotted](../../aspose.pdf.logicalstructure/attributename/borderstyle_dotted/) | 属性 BorderStyle: Dotted - 边框是一系列点。 |
| static readonly [BorderStyle_Double](../../aspose.pdf.logicalstructure/attributename/borderstyle_double/) | 属性 BorderStyle: Double - 边框是两条实线。两条线的总和及其之间的间距等于 BorderThickness 的值。 |
| static readonly [BorderStyle_Groove](../../aspose.pdf.logicalstructure/attributename/borderstyle_groove/) | 属性 BorderStyle: Groove - 边框看起来像是雕刻在画布上。 |
| static readonly [BorderStyle_Hidden](../../aspose.pdf.logicalstructure/attributename/borderstyle_hidden/) | 属性 BorderStyle: Hidden - 与 None 相同，除了在表格元素的边框冲突解决方面。 |
| static readonly [BorderStyle_Inset](../../aspose.pdf.logicalstructure/attributename/borderstyle_inset/) | 属性 BorderStyle: Inset - 边框使整个框看起来像是嵌入在画布中。 |
| static readonly [BorderStyle_None](../../aspose.pdf.logicalstructure/attributename/borderstyle_none/) | 属性 BorderStyle: None - 无边框。强制计算的 BorderThickness 值为 0。 |
| static readonly [BorderStyle_Outset](../../aspose.pdf.logicalstructure/attributename/borderstyle_outset/) | 属性 BorderStyle: Outset - 边框使整个框看起来像是从画布中出来（与 Inset 相反）。 |
| static readonly [BorderStyle_Ridge](../../aspose.pdf.logicalstructure/attributename/borderstyle_ridge/) | 属性 BorderStyle: Ridge - 边框看起来像是从画布中出来（与 Groove 相反）。 |
| static readonly [BorderStyle_Solid](../../aspose.pdf.logicalstructure/attributename/borderstyle_solid/) | 属性 BorderStyle: Solid - 边框是单条线段。 |
| static readonly [Checked_neutral](../../aspose.pdf.logicalstructure/attributename/checked_neutral/) | 属性 checked: Neutral - 单选按钮或复选框字段的状态。 |
| static readonly [Checked_off](../../aspose.pdf.logicalstructure/attributename/checked_off/) | 属性 checked: Off - 单选按钮或复选框字段的状态。 |
| static readonly [Checked_on](../../aspose.pdf.logicalstructure/attributename/checked_on/) | 属性 checked: On - 单选按钮或复选框字段的状态。 |
| static readonly [GlyphOrientationVertical_Auto](../../aspose.pdf.logicalstructure/attributename/glyphorientationvertical_auto/) | 属性 GlyphOrientationVertical: Auto - 根据文本是否为全宽（宽度与高度相等）指定默认方向。 |
| static readonly [Height_Auto](../../aspose.pdf.logicalstructure/attributename/height_auto/) | 属性 Height: Auto - 元素的高度应由其内容的固有高度决定。 |
| static readonly [InlineAlign_Center](../../aspose.pdf.logicalstructure/attributename/inlinealign_center/) | 属性 InlineAlign: Center - 每个子元素在表格单元格内居中。子元素的分配矩形的起始边缘与表格单元格内容矩形的起始边缘之间的距离应与它们的结束边缘之间的距离相同。 |
| static readonly [InlineAlign_End](../../aspose.pdf.logicalstructure/attributename/inlinealign_end/) | 属性 InlineAlign: End - 每个子元素的分配矩形的结束边缘与表格单元格内容矩形的结束边缘对齐。 |
| static readonly [InlineAlign_Start](../../aspose.pdf.logicalstructure/attributename/inlinealign_start/) | 属性 InlineAlign: Start - 每个子元素的分配矩形的起始边缘与表格单元格内容矩形的起始边缘对齐。 |
| static readonly [LineHeight_Auto](../../aspose.pdf.logicalstructure/attributename/lineheight_auto/) | 属性 LineHeight: Auto - 不应对基线偏移的值进行调整。 |
| static readonly [LineHeight_Normal](../../aspose.pdf.logicalstructure/attributename/lineheight_normal/) | 属性 LineHeight: Normal - 调整行高以包括为基线偏移指定的任何非零值。 |
| static readonly [ListNumbering_Circle](../../aspose.pdf.logicalstructure/attributename/listnumbering_circle/) | 属性 ListNumbering: Circle - 开放圆形项目符号。 |
| static readonly [ListNumbering_Decimal](../../aspose.pdf.logicalstructure/attributename/listnumbering_decimal/) | 属性 ListNumbering: Decimal - 十进制阿拉伯数字（1-9，10-99，...）。 |
| static readonly [ListNumbering_Disc](../../aspose.pdf.logicalstructure/attributename/listnumbering_disc/) | 属性 ListNumbering: Disc - 实心圆形项目符号。 |
| static readonly [ListNumbering_LowerAlpha](../../aspose.pdf.logicalstructure/attributename/listnumbering_loweralpha/) | 属性 ListNumbering: LowerAlpha - 小写字母（a，b，c，...）。 |
| static readonly [ListNumbering_LowerRoman](../../aspose.pdf.logicalstructure/attributename/listnumbering_lowerroman/) | 属性 ListNumbering: LowerRoman - 小写罗马数字（i，ii，iii，iv，...）。 |
| static readonly [ListNumbering_None](../../aspose.pdf.logicalstructure/attributename/listnumbering_none/) | 属性 ListNumbering: None - 无自动编号；Lbl 元素（如果存在）包含不受任何编号方案约束的任意文本。 |
| static readonly [ListNumbering_Square](../../aspose.pdf.logicalstructure/attributename/listnumbering_square/) | 属性 ListNumbering: Square - 实心方形项目符号。 |
| static readonly [ListNumbering_UpperAlpha](../../aspose.pdf.logicalstructure/attributename/listnumbering_upperalpha/) | 属性 ListNumbering: UpperAlpha - 大写字母（A，B，C，...）。 |
| static readonly [ListNumbering_UpperRoman](../../aspose.pdf.logicalstructure/attributename/listnumbering_upperroman/) | 属性 ListNumbering: UpperRoman - 大写罗马数字（I，II，III，IV，...）。 |
| static readonly [Placement_Before](../../aspose.pdf.logicalstructure/attributename/placement_before/) | 属性 Placement: Before - 放置位置使元素的分配矩形的前边缘与最近的封闭参考区域的前边缘重合。 |
| static readonly [Placement_Block](../../aspose.pdf.logicalstructure/attributename/placement_block/) | 属性 Placement: Block - 在封闭参考区域或父级 BLSE 内按块进程方向堆叠。 |
| static readonly [Placement_End](../../aspose.pdf.logicalstructure/attributename/placement_end/) | 属性 Placement: End - 放置位置使元素的分配矩形的结束边缘与最近的封闭参考区域的结束边缘重合。 |
| static readonly [Placement_Inline](../../aspose.pdf.logicalstructure/attributename/placement_inline/) | 属性 Placement: Inline - 在封闭的 BLSE 内按行进程方向打包。 |
| static readonly [Placement_Start](../../aspose.pdf.logicalstructure/attributename/placement_start/) | 属性 Placement: Start - 放置位置使元素的分配矩形的起始边缘与最近的封闭参考区域的起始边缘重合。 |
| static readonly [Role_cb](../../aspose.pdf.logicalstructure/attributename/role_cb/) | 属性 Role: cb - 复选框。 |
| static readonly [Role_pb](../../aspose.pdf.logicalstructure/attributename/role_pb/) | 属性 Role: pb - 按钮。 |
| static readonly [Role_rb](../../aspose.pdf.logicalstructure/attributename/role_rb/) | 属性 Role: rb - 单选按钮。 |
| static readonly [Role_tv](../../aspose.pdf.logicalstructure/attributename/role_tv/) | 属性 Role: tv - 文本值字段。 |
| static readonly [RubyAlign_Center](../../aspose.pdf.logicalstructure/attributename/rubyalign_center/) | 属性 RubyAlign: Center - 内容在行进程方向上居中。 |
| static readonly [RubyAlign_Distribute](../../aspose.pdf.logicalstructure/attributename/rubyalign_distribute/) | 属性 RubyAlign: Distribute - 内容应扩展以填充行进程方向上的可用宽度。然而，文本的起始边缘和结束边缘也应插入空间。间距应按 1:2:1（起始:中缀:结束）比例分配。如果 ruby 出现在文本行的起始位置，则应更改为 0:1:1 比例；如果 ruby 出现在文本行的结束位置，则应更改为 1:1:0 比例。 |
| static readonly [RubyAlign_End](../../aspose.pdf.logicalstructure/attributename/rubyalign_end/) | 属性 RubyAlign: End - 内容在行进程方向上与结束边缘对齐。 |
| static readonly [RubyAlign_Justify](../../aspose.pdf.logicalstructure/attributename/rubyalign_justify/) | 属性 RubyAlign: Justify - 内容应扩展以填充行进程方向上的可用宽度。 |
| static readonly [RubyAlign_Start](../../aspose.pdf.logicalstructure/attributename/rubyalign_start/) | 属性 RubyAlign: Start - 内容在行进程方向上与起始边缘对齐。 |
| static readonly [RubyPosition_After](../../aspose.pdf.logicalstructure/attributename/rubyposition_after/) | 属性 RubyPosition: After - RT 内容应沿元素的后边缘对齐。 |
| static readonly [RubyPosition_Before](../../aspose.pdf.logicalstructure/attributename/rubyposition_before/) | 属性 RubyPosition: Before - RT 内容应沿元素的前边缘对齐。 |
| static readonly [RubyPosition_Inline](../../aspose.pdf.logicalstructure/attributename/rubyposition_inline/) | 属性 RubyPosition: Inline - RT 和相关的 RP 元素应格式化为括号注释，跟随 RB 元素。 |
| static readonly [RubyPosition_Warichu](../../aspose.pdf.logicalstructure/attributename/rubyposition_warichu/) | 属性 RubyPosition: Warichu - RT 和相关的 RP 元素应格式化为 warichu，跟随 RB 元素。 |
| static readonly [Scope_Both](../../aspose.pdf.logicalstructure/attributename/scope_both/) | 属性 Scope: Both。 |
| static readonly [Scope_Column](../../aspose.pdf.logicalstructure/attributename/scope_column/) | 属性 Scope: Column。 |
| static readonly [Scope_Row](../../aspose.pdf.logicalstructure/attributename/scope_row/) | 属性 Scope: Row。 |
| static readonly [TextAlign_Center](../../aspose.pdf.logicalstructure/attributename/textalign_center/) | 属性 TextAlign: Center - 在起始和结束边缘之间居中。 |
| static readonly [TextAlign_End](../../aspose.pdf.logicalstructure/attributename/textalign_end/) | 属性 TextAlign: End - 与结束边缘对齐。 |
| static readonly [TextAlign_Justify](../../aspose.pdf.logicalstructure/attributename/textalign_justify/) | 属性 TextAlign: Justify - 与起始和结束边缘对齐，必要时每行内部的间距扩展以实现这种对齐。最后一行（或唯一一行）应仅与起始边缘对齐。 |
| static readonly [TextAlign_Start](../../aspose.pdf.logicalstructure/attributename/textalign_start/) | 属性 TextAlign: Start - 与起始边缘对齐。 |
| static readonly [TextDecorationType_LineThrough](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_linethrough/) | 属性 TextDecorationType: LineThrough - 在文本中间划一条线。 |
| static readonly [TextDecorationType_None](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_none/) | 属性 TextDecorationType: None - 无文本装饰。 |
| static readonly [TextDecorationType_Overline](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_overline/) | 属性 TextDecorationType: Overline - 在文本上方划一条线。 |
| static readonly [TextDecorationType_Underline](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_underline/) | 属性 TextDecorationType: Underline - 在文本下方划一条线。 |
| static readonly [Width_Auto](../../aspose.pdf.logicalstructure/attributename/width_auto/) | 属性 Width: Auto - 元素的宽度应由其内容的固有宽度决定。 |
| static readonly [WritingMode_LrTb](../../aspose.pdf.logicalstructure/attributename/writingmode_lrtb/) | 属性 WritingMode: LrTb - 行进程从左到右；块进程从上到下。这是西方书写系统的典型书写模式。 |
| static readonly [WritingMode_RlTb](../../aspose.pdf.logicalstructure/attributename/writingmode_rltb/) | 属性 WritingMode: RlTb - 行进程从右到左；块进程从上到下。这是阿拉伯语和希伯来语书写系统的典型书写模式。 |
| static readonly [WritingMode_TbRl](../../aspose.pdf.logicalstructure/attributename/writingmode_tbrl/) | 属性 WritingMode: TbRl - 行进程从上到下；块进程从右到左。这是中文和日文书写系统的典型书写模式。 |

### 另请参见

* 命名空间 [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* 程序集 [Aspose.PDF](../../)