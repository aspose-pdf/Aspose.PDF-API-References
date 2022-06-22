---
title: AttributeName
second_title: Aspose.PDF for .NET API 参考
description: 表示属性名称值的类
type: docs
weight: 4050
url: /zh/net/aspose.pdf.logicalstructure/attributename/
---
## AttributeName class

表示属性名称值的类。

```csharp
public sealed class AttributeName
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [AttributeKey](../../aspose.pdf.logicalstructure/attributename/attributekey) { get; } | 获取属性键。 |
| [Name](../../aspose.pdf.logicalstructure/attributename/name) { get; } | 获取属性的名称值。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| static [FromNameAttributeKey](../../aspose.pdf.logicalstructure/attributename/fromnameattributekey)(string, AttributeKey) | 获取属性键的属性名称。 |
| override [ToString](../../aspose.pdf.logicalstructure/attributename/tostring)() | 返回代表当前对象的字符串。 |

## 字段

| 姓名 | 描述 |
| --- | --- |
| static readonly [BlockAlign_After](../../aspose.pdf.logicalstructure/attributename/blockalign_after) | 属性 BlockAlign:After - 最后一个子分配矩形的边缘与表格单元格的内容矩形的边缘对齐。 |
| static readonly [BlockAlign_Before](../../aspose.pdf.logicalstructure/attributename/blockalign_before) | 属性 BlockAlign:Before - 第一个子分配矩形的边缘与表格单元格内容矩形的边缘对齐。 |
| static readonly [BlockAlign_Justify](../../aspose.pdf.logicalstructure/attributename/blockalign_justify) | 属性 BlockAlign:Justify - 子元素与表格单元格内容矩形的前后边缘对齐。第一个孩子应按照之前的描述放置，最后一个孩子按照之后的描述放置，孩子之间的间距相等。如果只有一个孩子，它应该只与前边缘对齐，就像之前一样。 |
| static readonly [BlockAlign_Middle](../../aspose.pdf.logicalstructure/attributename/blockalign_middle) | 属性 BlockAlign:Middle- 在表格单元格中居中的子级。第一个孩子的分配矩形的前边缘与表格单元格的内容矩形的前边缘之间的距离应与最后一个孩子的分配矩形的后边缘之间的距离与表格单元的内容矩形的后边缘之间的距离相同。 |
| static readonly [BorderStyle_Dashed](../../aspose.pdf.logicalstructure/attributename/borderstyle_dashed) | 属性 BorderStyle:Dashed - 边框是一系列短线段。 |
| static readonly [BorderStyle_Dotted](../../aspose.pdf.logicalstructure/attributename/borderstyle_dotted) | 属性 BorderStyle:Dotted - 边框是一系列点。 |
| static readonly [BorderStyle_Double](../../aspose.pdf.logicalstructure/attributename/borderstyle_double) | 属性 BorderStyle:Double - 边框是两条实线。两条线的总和和它们之间的间距等于 BorderThickness 的值。 |
| static readonly [BorderStyle_Groove](../../aspose.pdf.logicalstructure/attributename/borderstyle_groove) | 属性 BorderStyle:Groove - 边框看起来好像是雕刻在画布上的。 |
| static readonly [BorderStyle_Hidden](../../aspose.pdf.logicalstructure/attributename/borderstyle_hidden) | 属性 BorderStyle:Hidden - 与无相同，除了表格元素的边界冲突解决方案。 |
| static readonly [BorderStyle_Inset](../../aspose.pdf.logicalstructure/attributename/borderstyle_inset) | 属性 BorderStyle:Inset - 边框使整个框看起来好像嵌入在画布中。 |
| static readonly [BorderStyle_None](../../aspose.pdf.logicalstructure/attributename/borderstyle_none) | 属性 BorderStyle:None - 无边框。强制 BorderThickness 的计算值为 0。 |
| static readonly [BorderStyle_Outset](../../aspose.pdf.logicalstructure/attributename/borderstyle_outset) | 属性 BorderStyle:Outset - 边框使整个框看起来好像从画布中出来（与 Inset 相反）。 |
| static readonly [BorderStyle_Ridge](../../aspose.pdf.logicalstructure/attributename/borderstyle_ridge) | 属性 BorderStyle:Ridge - 边框看起来好像从画布中出来（与 Groove 相对）。 |
| static readonly [BorderStyle_Solid](../../aspose.pdf.logicalstructure/attributename/borderstyle_solid) | 属性 BorderStyle:Solid - 边框是单线段。 |
| static readonly [Checked_neutral](../../aspose.pdf.logicalstructure/attributename/checked_neutral) | 属性检查:中性 - 单选按钮或复选框字段的状态。 |
| static readonly [Checked_off](../../aspose.pdf.logicalstructure/attributename/checked_off) | 属性检查:关闭 - 单选按钮或复选框字段的状态。 |
| static readonly [Checked_on](../../aspose.pdf.logicalstructure/attributename/checked_on) | 属性选中:On - 单选按钮或复选框字段的状态。 |
| static readonly [GlyphOrientationVertical_Auto](../../aspose.pdf.logicalstructure/attributename/glyphorientationvertical_auto) | 属性 GlyphOrientationVertical:Auto - 指定文本的默认方向，取决于它是否为全角（与高一样宽）。 |
| static readonly [Height_Auto](../../aspose.pdf.logicalstructure/attributename/height_auto) | 属性 Height:Auto - 元素的高度应由其内容的固有高度决定。 |
| static readonly [InlineAlign_Center](../../aspose.pdf.logicalstructure/attributename/inlinealign_center) | 属性 InlineAlign:Center - 每个子元素在表格单元格中居中。子分配矩形的起始边缘与表格单元格的内容矩形之间的距离应与它们的结束边缘之间的距离相同。 |
| static readonly [InlineAlign_End](../../aspose.pdf.logicalstructure/attributename/inlinealign_end) | 属性 InlineAlign:End - 每个子分配矩形的结束边缘与表格单元格的内容矩形的边缘对齐。 |
| static readonly [InlineAlign_Start](../../aspose.pdf.logicalstructure/attributename/inlinealign_start) | 属性 InlineAlign:Start - 每个子分配矩形的起始边缘与表格单元格的内容矩形的边缘对齐。 |
| static readonly [LineHeight_Auto](../../aspose.pdf.logicalstructure/attributename/lineheight_auto) | 属性 LineHeight:Auto - 不得调整 BaselineShift 的值。 |
| static readonly [LineHeight_Normal](../../aspose.pdf.logicalstructure/attributename/lineheight_normal) | 属性 LineHeight:Normal - 调整行高以包含为 BaselineShift 指定的任何非零值。 |
| static readonly [ListNumbering_Circle](../../aspose.pdf.logicalstructure/attributename/listnumbering_circle) | 属性 ListNumbering:Circle - 打开圆形项目符号。 |
| static readonly [ListNumbering_Decimal](../../aspose.pdf.logicalstructure/attributename/listnumbering_decimal) | 属性列表编号:十进制 - 十进制阿拉伯数字（1-9、10-99、...）。 |
| static readonly [ListNumbering_Disc](../../aspose.pdf.logicalstructure/attributename/listnumbering_disc) | 属性列表编号:光盘 - 实心圆形项目符号。 |
| static readonly [ListNumbering_LowerAlpha](../../aspose.pdf.logicalstructure/attributename/listnumbering_loweralpha) | 属性列表编号:LowerAlpha - 小写字母（a、b、c、...）。 |
| static readonly [ListNumbering_LowerRoman](../../aspose.pdf.logicalstructure/attributename/listnumbering_lowerroman) | 属性列表编号:LowerRoman - 小写罗马数字（i、ii、iii、iv、...）。 |
| static readonly [ListNumbering_None](../../aspose.pdf.logicalstructure/attributename/listnumbering_none) | 属性列表编号:无 - 无自动编号； Lbl 元素（如果存在）包含不受任何编号方案约束的任意文本。 |
| static readonly [ListNumbering_Square](../../aspose.pdf.logicalstructure/attributename/listnumbering_square) | 属性列表编号:方形 - 实心方形项目符号。 |
| static readonly [ListNumbering_UpperAlpha](../../aspose.pdf.logicalstructure/attributename/listnumbering_upperalpha) | 属性列表编号:UpperAlpha - 大写字母（A、B、C、...）。 |
| static readonly [ListNumbering_UpperRoman](../../aspose.pdf.logicalstructure/attributename/listnumbering_upperroman) | 属性列表编号:UpperRoman - 大写罗马数字（I, II, III, IV, ...）。 |
| static readonly [Placement_Before](../../aspose.pdf.logicalstructure/attributename/placement_before) | 属性放置:之前 - 放置元素的分配矩形的前边缘与最近的封闭参考区域的前边缘重合。 |
| static readonly [Placement_Block](../../aspose.pdf.logicalstructure/attributename/placement_block) | 属性放置:块 - 在封闭参考区域或父 BLSE 内沿块前进方向堆叠。 |
| static readonly [Placement_End](../../aspose.pdf.logicalstructure/attributename/placement_end) | 属性放置:结束 - 放置元素的分配矩形的末端边缘与最近的封闭参考区域的末端边缘重合。 |
| static readonly [Placement_Inline](../../aspose.pdf.logicalstructure/attributename/placement_inline) | 属性放置:内联 - 在封闭的 BLSE 内按内联进度方向打包。 |
| static readonly [Placement_Start](../../aspose.pdf.logicalstructure/attributename/placement_start) | 属性放置:开始 - 放置以使元素的分配矩形的开始边缘与最近的封闭参考区域的开始边缘重合。 |
| static readonly [Role_cb](../../aspose.pdf.logicalstructure/attributename/role_cb) | 属性角色:cb - 复选框。 |
| static readonly [Role_pb](../../aspose.pdf.logicalstructure/attributename/role_pb) | 属性角色:pb - 按钮。 |
| static readonly [Role_rb](../../aspose.pdf.logicalstructure/attributename/role_rb) | 属性角色:rb - 单选按钮。 |
| static readonly [Role_tv](../../aspose.pdf.logicalstructure/attributename/role_tv) | 属性角色:tv - 文本值字段。 |
| static readonly [RubyAlign_Center](../../aspose.pdf.logicalstructure/attributename/rubyalign_center) | 属性 RubyAlign:Center - 内容应在 inline-progression 方向居中。 |
| static readonly [RubyAlign_Distribute](../../aspose.pdf.logicalstructure/attributename/rubyalign_distribute) | 属性 RubyAlign:Distribute - 内容应扩大以填充行进方向上的可用宽度。但是，也应在文本的开始边缘和结束边缘插入空格。间距应使用 1:2:1（开始:中缀:结束）的比例分布。如果红宝石出现在文本行的开头，则应更改为 0:1:1 的比例，如果红宝石出现在文本行的末尾，则应更改为 1:1:0 的比例。 |
| static readonly [RubyAlign_End](../../aspose.pdf.logicalstructure/attributename/rubyalign_end) | 属性 RubyAlign:End - 内容应在行进方向的末端边缘对齐。 |
| static readonly [RubyAlign_Justify](../../aspose.pdf.logicalstructure/attributename/rubyalign_justify) | 属性 RubyAlign:Justify - 内容应扩大以填充行进方向上的可用宽度。 |
| static readonly [RubyAlign_Start](../../aspose.pdf.logicalstructure/attributename/rubyalign_start) | 属性 RubyAlign:Start - 内容应在行进方向的起始边缘对齐。 |
| static readonly [RubyPosition_After](../../aspose.pdf.logicalstructure/attributename/rubyposition_after) | 属性 RubyPosition:After - RT 内容应沿元素的后边缘对齐。 |
| static readonly [RubyPosition_Before](../../aspose.pdf.logicalstructure/attributename/rubyposition_before) | 属性 RubyPosition:Before - RT 内容应沿元素的前边缘对齐。 |
| static readonly [RubyPosition_Inline](../../aspose.pdf.logicalstructure/attributename/rubyposition_inline) | 属性 RubyPosition:Inline - RT 和相关的 RP 元素应格式化为括号注释，紧跟 RB 元素。 |
| static readonly [RubyPosition_Warichu](../../aspose.pdf.logicalstructure/attributename/rubyposition_warichu) | 属性 RubyPosition:Warichu - RT 和相关的 RP 元素应格式化为 warichu，紧跟 RB 元素。 |
| static readonly [Scope_Both](../../aspose.pdf.logicalstructure/attributename/scope_both) | 属性范围:两者。 |
| static readonly [Scope_Column](../../aspose.pdf.logicalstructure/attributename/scope_column) | 属性范围:列。 |
| static readonly [Scope_Row](../../aspose.pdf.logicalstructure/attributename/scope_row) | 属性范围:行。 |
| static readonly [TextAlign_Center](../../aspose.pdf.logicalstructure/attributename/textalign_center) | 属性 TextAlign:Center - 在开始边缘和结束边缘之间居中。 |
| static readonly [TextAlign_End](../../aspose.pdf.logicalstructure/attributename/textalign_end) | 属性 TextAlign:End - 与结束边缘对齐。 |
| static readonly [TextAlign_Justify](../../aspose.pdf.logicalstructure/attributename/textalign_justify) | 属性 TextAlign:Justify - 与开始和结束边缘对齐，如果需要，每行内的内部间距会扩大，以实现这种对齐。最后（或唯一）行应仅与起始边缘对齐。 |
| static readonly [TextAlign_Start](../../aspose.pdf.logicalstructure/attributename/textalign_start) | 属性 TextAlign:Start - 与起始边缘对齐。 |
| static readonly [TextDecorationType_LineThrough](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_linethrough) | 属性 TextDecorationType:LineThrough - 一条穿过文本中间的线。 |
| static readonly [TextDecorationType_None](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_none) | 属性 TextDecorationType:None - 无文字装饰。 |
| static readonly [TextDecorationType_Overline](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_overline) | 属性 TextDecorationType:Overline - 文本上方的一行。 |
| static readonly [TextDecorationType_Underline](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_underline) | 属性 TextDecorationType:Underline - 文本下方的一行。 |
| static readonly [Width_Auto](../../aspose.pdf.logicalstructure/attributename/width_auto) | 属性宽度:自动 - 元素的宽度应由其内容的固有宽度确定。 |
| static readonly [WritingMode_LrTb](../../aspose.pdf.logicalstructure/attributename/writingmode_lrtb) | 属性 WritingMode:LrTb - 从左到右的内联进程；阻止从上到下的进展。这是西方书写系统的典型书写模式。 |
| static readonly [WritingMode_RlTb](../../aspose.pdf.logicalstructure/attributename/writingmode_rltb) | 属性 WritingMode:RlTb - 从右到左的内联进程；阻止从上到下的进展。这是阿拉伯语和希伯来语书写系统的典型书写模式。 |
| static readonly [WritingMode_TbRl](../../aspose.pdf.logicalstructure/attributename/writingmode_tbrl) | 属性 WritingMode:TbRl - 从上到下的内联进程；阻止从右到左的进程。这是中文和日文书写系统的典型书写模式。 |

### 也可以看看

* 命名空间 [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure)
* 部件 [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
