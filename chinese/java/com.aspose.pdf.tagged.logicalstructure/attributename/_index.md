---
title: "AttributeName"
linktitle: "AttributeName"
second_title: "Aspose.PDF for Java API 参考"
description: "表示 Attribute Name Values 的类。"
type: docs
weight: 20
url: /zh/java/com.aspose.pdf.tagged.logicalstructure/attributename/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.AttributeName

```
public final class AttributeName extends Object
```

表示 Attribute Name Values 的类。

## 字段

| 字段 | 描述 |
| --- | --- |
| [BlockAlign_After](#BlockAlign_After) | Attribute BlockAlign: After - 最后一个子元素的分配矩形的后边缘与表格单元格内容矩形的后边缘对齐。 |
| [BlockAlign_Before](#BlockAlign_Before) | Attribute BlockAlign: Before - 第一个子元素的分配矩形的前边缘与表格单元格内容矩形的前边缘对齐。 |
| [BlockAlign_Justify](#BlockAlign_Justify) | Attribute BlockAlign: Justify - 子元素同时与表格单元格内容矩形的前后边缘对齐。第一个子元素按照 Before 的描述放置，最后一个子元素按照 After 的描述放置，子元素之间间距相等。如果只有一个子元素，则仅与前边缘对齐，类似于 Before。 |
| [BlockAlign_Middle](#BlockAlign_Middle) | Attribute BlockAlign: Middle- 子元素在表格单元格内居中。第一个子元素的分配矩形的前边缘与表格单元格内容矩形的前边缘之间的距离，应与最后一个子元素的分配矩形的后边缘与表格单元格内容矩形的后边缘之间的距离相同。 |
| [BorderStyle_Dashed](#BorderStyle_Dashed) | Attribute BorderStyle: Dashed - 边框由一系列短线段组成。 |
| [BorderStyle_Dotted](#BorderStyle_Dotted) | Attribute BorderStyle: Dotted - 边框由一系列点组成。 |
| [BorderStyle_Double](#BorderStyle_Double) | Attribute BorderStyle: Double - 边框由两条实线组成。两条线及其之间的间距之和等于 BorderThickness 的值。 |
| [BorderStyle_Groove](#BorderStyle_Groove) | Attribute BorderStyle: Groove - 边框看起来像是被雕刻在画布上。 |
| [BorderStyle_Hidden](#BorderStyle_Hidden) | Attribute BorderStyle: Hidden - 与 None 相同，只是在表格元素的边框冲突解决方面有所不同。 |
| [BorderStyle_Inset](#BorderStyle_Inset) | Attribute BorderStyle: Inset - 边框使整个盒子看起来像嵌入在画布中。 |
| [BorderStyle_None](#BorderStyle_None) | Attribute BorderStyle: None - 无边框。强制将 BorderThicknessto 的计算值设为 0。 |
| [BorderStyle_Outset](#BorderStyle_Outset) | Attribute BorderStyle: Outset - 边框使整个盒子看起来像是从画布中凸出（与 Inset 相反）。 |
| [BorderStyle_Ridge](#BorderStyle_Ridge) | Attribute BorderStyle: Ridge - 边框看起来像是从画布凸起（与 Groove 相反）。 |
| [BorderStyle_Solid](#BorderStyle_Solid) | Attribute BorderStyle: Solid - 边框是一条单线段。 |
| [Checked_neutral](#Checked_neutral) | Attribute checked: Neutral - 单选按钮或复选框字段的状态。 |
| [Checked_off](#Checked_off) | Attribute checked: Off - 单选按钮或复选框字段的状态。 |
| [Checked_on](#Checked_on) | Attribute checked: On - 单选按钮或复选框字段的状态。 |
| [GlyphOrientationVertical_Auto](#GlyphOrientationVertical_Auto) | Attribute GlyphOrientationVertical: Auto - 指定文本的默认方向，取决于它是否为全宽（宽高相等）。 |
| [Height_Auto](#Height_Auto) | Attribute Height: Auto - 元素的高度应由其内容的固有高度决定。 |
| [InlineAlign_Center](#InlineAlign_Center) | Attribute InlineAlign: Center - 每个子元素在表格单元格内居中。子元素分配矩形的起始边缘与表格单元格内容矩形的起始边缘之间的距离应与它们结束边缘之间的距离相同。 |
| [InlineAlign_End](#InlineAlign_End) | Attribute InlineAlign: End - 每个子元素分配矩形的结束边缘与表格单元格内容矩形的结束边缘对齐。 |
| [InlineAlign_Start](#InlineAlign_Start) | Attribute InlineAlign: Start - 每个子元素分配矩形的起始边缘与表格单元格内容矩形的起始边缘对齐。 |
| [LineHeight_Auto](#LineHeight_Auto) | Attribute LineHeight: Auto - 不对 BaselineShift 的值进行调整。 |
| [LineHeight_Normal](#LineHeight_Normal) | Attribute LineHeight: Normal - 调整行高以包括 BaselineShift 指定的任何非零值。 |
| [ListNumbering_Circle](#ListNumbering_Circle) | Attribute ListNumbering: Circle - 开放的圆形项目符号。 |
| [ListNumbering_Decimal](#ListNumbering_Decimal) | Attribute ListNumbering: Decimal - 十进制阿拉伯数字（1-9，10-99，...）。 |
| [ListNumbering_Disc](#ListNumbering_Disc) | Attribute ListNumbering: Disc - 实心圆形项目符号。 |
| [ListNumbering_LowerAlpha](#ListNumbering_LowerAlpha) | Attribute ListNumbering: LowerAlpha - 小写字母（a，b，c，...）。 |
| [ListNumbering_LowerRoman](#ListNumbering_LowerRoman) | Attribute ListNumbering: LowerRoman - 小写罗马数字（i，ii，iii，iv，...）。 |
| [ListNumbering_None](#ListNumbering_None) | Attribute ListNumbering: None - 无自动编号；Lbl 元素（如果存在）包含不受任何编号方案约束的任意文本。 |
| [ListNumbering_Square](#ListNumbering_Square) | Attribute ListNumbering: Square - 实心方形项目符号。 |
| [ListNumbering_UpperAlpha](#ListNumbering_UpperAlpha) | Attribute ListNumbering: UpperAlpha - 大写字母（A，B，C，...）。 |
| [ListNumbering_UpperRoman](#ListNumbering_UpperRoman) | Attribute ListNumbering: UpperRoman - 大写罗马数字（I，II，III，IV，...）。 |
| [Placement_Before](#Placement_Before) | Attribute Placement: Before - 放置方式使元素分配矩形的前边缘与最近的封闭参考区域的前边缘重合。 |
| [Placement_Block](#Placement_Block) | Attribute Placement: Block - 在封闭参考区域或父 BLSE 内沿块进程方向堆叠。 |
| [Placement_End](#Placement_End) | Attribute Placement: End - 放置方式使元素分配矩形的结束边缘与最近的封闭参考区域的结束边缘重合。 |
| [Placement_Inline](#Placement_Inline) | Attribute Placement: Inline - 在封闭 BLSE 内沿行内进程方向紧凑排列。 |
| [Placement_Start](#Placement_Start) | 属性放置：Start - 放置方式使元素分配矩形的起始边缘与最近的封闭参考区域的起始边缘重合。 |
| [Role_cb](#Role_cb) | 属性角色：cb - 复选框。 |
| [Role_pb](#Role_pb) | 属性角色：pb - 按钮。 |
| [Role_rb](#Role_rb) | 属性角色：rb - 单选按钮。 |
| [Role_tv](#Role_tv) | 属性角色：tv - 文本值字段。 |
| [RubyAlign_Center](#RubyAlign_Center) | 属性 RubyAlign：Center - 内容应在行内进展方向居中。 |
| [RubyAlign_Distribute](#RubyAlign_Distribute) | 属性 RubyAlign：Distribute - 内容应在行内进展方向上扩展以填满可用宽度。然而，还应在文本的起始边缘和结束边缘插入空白。间距应使用 1:2:1（起始:中间:结束）比例分配。如果 ruby 出现在文本行的起始位置，则比例改为 0:1:1；如果 ruby 出现在文本行的结束位置，则比例改为 1:1:0。 |
| [RubyAlign_End](#RubyAlign_End) | 属性 RubyAlign：End - 内容应在行内进展方向的结束边缘对齐。 |
| [RubyAlign_Justify](#RubyAlign_Justify) | 属性 RubyAlign：Justify - 内容应在行内进展方向上扩展以填满可用宽度。 |
| [RubyAlign_Start](#RubyAlign_Start) | 属性 RubyAlign：Start - 内容应在行内进展方向的起始边缘对齐。 |
| [RubyPosition_After](#RubyPosition_After) | 属性 RubyPosition：After - RT 内容应沿元素的后边缘对齐。 |
| [RubyPosition_Before](#RubyPosition_Before) | 属性 RubyPosition：Before - RT 内容应沿元素的前边缘对齐。 |
| [RubyPosition_Inline](#RubyPosition_Inline) | 属性 RubyPosition：Inline - RT 及其关联的 RP 元素应格式化为括号注释，位于 RB 元素之后。 |
| [RubyPosition_Warichu](#RubyPosition_Warichu) | 属性 RubyPosition：Warichu - RT 及其关联的 RP 元素应格式化为割注（warichu），位于 RB 元素之后。 |
| [Scope_Both](#Scope_Both) | 属性范围：Both。 |
| [Scope_Column](#Scope_Column) | 属性范围：Column。 |
| [Scope_Row](#Scope_Row) | 属性范围：Row。 |
| [TextAlign_Center](#TextAlign_Center) | 属性 TextAlign：Center - 在起始和结束边缘之间居中。 |
| [TextAlign_End](#TextAlign_End) | 属性 TextAlign：End - 与结束边缘对齐。 |
| [TextAlign_Justify](#TextAlign_Justify) | 属性 TextAlign：Justify - 与起始和结束边缘对齐，如有必要，通过扩展每行内部间距来实现此对齐。最后一行（或唯一一行）仅与起始边缘对齐。 |
| [TextAlign_Start](#TextAlign_Start) | 属性 TextAlign：Start - 与起始边缘对齐。 |
| [TextDecorationType_LineThrough](#TextDecorationType_LineThrough) | 属性 TextDecorationType：LineThrough - 在文本中部加一条横线。 |
| [TextDecorationType_None](#TextDecorationType_None) | 属性 TextDecorationType：None - 无文本装饰。 |
| [TextDecorationType_Overline](#TextDecorationType_Overline) | 属性 TextDecorationType：Overline - 在文本上方加一条横线。 |
| [TextDecorationType_Underline](#TextDecorationType_Underline) | 属性 TextDecorationType：Underline - 在文本下方加一条横线。 |
| [Width_Auto](#Width_Auto) | 属性宽度：Auto - 元素的宽度应由其内容的固有宽度决定。 |
| [WritingMode_LrTb](#WritingMode_LrTb) | 属性写作模式：LrTb - 行内从左到右；块级从上到下。这是西方书写系统的典型写作模式。 |
| [WritingMode_RlTb](#WritingMode_RlTb) | 属性写作模式：RlTb - 行内从右到左；块级从上到下。这是阿拉伯语和希伯来语书写系统的典型写作模式。 |
| [WritingMode_TbRl](#WritingMode_TbRl) | 属性写作模式：TbRl - 行内从上到下；块级从右到左。这是中文和日文书写系统的典型写作模式。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [fromNameAttributeKey](#fromNameAttributeKey-java.lang.String-com.aspose.pdf.tagged.logicalstructure.AttributeKey-) | 获取属性键对应的属性名称。 |
| [getAttributeKey](#getAttributeKey--) | 获取属性键。 |
| [getName](#getName--) | 获取属性的名称值。 |
| [toString](#toString--) | 返回表示当前对象的字符串。 |

### BlockAlign_After {#BlockAlign_After}
```
public static final AttributeName BlockAlign_After
```

Attribute BlockAlign: After - 最后一个子元素的分配矩形的后边缘与表格单元格内容矩形的后边缘对齐。

### BlockAlign_Before {#BlockAlign_Before}
```
public static final AttributeName BlockAlign_Before
```

Attribute BlockAlign: Before - 第一个子元素的分配矩形的前边缘与表格单元格内容矩形的前边缘对齐。

### BlockAlign_Justify {#BlockAlign_Justify}
```
public static final AttributeName BlockAlign_Justify
```

Attribute BlockAlign: Justify - 子元素同时与表格单元格内容矩形的前后边缘对齐。第一个子元素按照 Before 的描述放置，最后一个子元素按照 After 的描述放置，子元素之间间距相等。如果只有一个子元素，则仅与前边缘对齐，类似于 Before。

### BlockAlign_Middle {#BlockAlign_Middle}
```
public static final AttributeName BlockAlign_Middle
```

Attribute BlockAlign: Middle- 子元素在表格单元格内居中。第一个子元素的分配矩形的前边缘与表格单元格内容矩形的前边缘之间的距离，应与最后一个子元素的分配矩形的后边缘与表格单元格内容矩形的后边缘之间的距离相同。

### BorderStyle_Dashed {#BorderStyle_Dashed}
```
public static final AttributeName BorderStyle_Dashed
```

Attribute BorderStyle: Dashed - 边框由一系列短线段组成。

### BorderStyle_Dotted {#BorderStyle_Dotted}
```
public static final AttributeName BorderStyle_Dotted
```

Attribute BorderStyle: Dotted - 边框由一系列点组成。

### BorderStyle_Double {#BorderStyle_Double}
```
public static final AttributeName BorderStyle_Double
```

Attribute BorderStyle: Double - 边框由两条实线组成。两条线及其之间的间距之和等于 BorderThickness 的值。

### BorderStyle_Groove {#BorderStyle_Groove}
```
public static final AttributeName BorderStyle_Groove
```

Attribute BorderStyle: Groove - 边框看起来像是被雕刻在画布上。

### BorderStyle_Hidden {#BorderStyle_Hidden}
```
public static final AttributeName BorderStyle_Hidden
```

Attribute BorderStyle: Hidden - 与 None 相同，只是在表格元素的边框冲突解决方面有所不同。

### BorderStyle_Inset {#BorderStyle_Inset}
```
public static final AttributeName BorderStyle_Inset
```

Attribute BorderStyle: Inset - 边框使整个盒子看起来像嵌入在画布中。

### BorderStyle_None {#BorderStyle_None}
```
public static final AttributeName BorderStyle_None
```

Attribute BorderStyle: None - 无边框。强制将 BorderThicknessto 的计算值设为 0。

### BorderStyle_Outset {#BorderStyle_Outset}
```
public static final AttributeName BorderStyle_Outset
```

Attribute BorderStyle: Outset - 边框使整个盒子看起来像是从画布中凸出（与 Inset 相反）。

### BorderStyle_Ridge {#BorderStyle_Ridge}
```
public static final AttributeName BorderStyle_Ridge
```

Attribute BorderStyle: Ridge - 边框看起来像是从画布凸起（与 Groove 相反）。

### BorderStyle_Solid {#BorderStyle_Solid}
```
public static final AttributeName BorderStyle_Solid
```

Attribute BorderStyle: Solid - 边框是一条单线段。

### Checked_neutral {#Checked_neutral}
```
public static final AttributeName Checked_neutral
```

Attribute checked: Neutral - 单选按钮或复选框字段的状态。

### Checked_off {#Checked_off}
```
public static final AttributeName Checked_off
```

Attribute checked: Off - 单选按钮或复选框字段的状态。

### Checked_on {#Checked_on}
```
public static final AttributeName Checked_on
```

Attribute checked: On - 单选按钮或复选框字段的状态。

### GlyphOrientationVertical_Auto {#GlyphOrientationVertical_Auto}
```
public static final AttributeName GlyphOrientationVertical_Auto
```

Attribute GlyphOrientationVertical: Auto - 指定文本的默认方向，取决于它是否为全宽（宽高相等）。

### Height_Auto {#Height_Auto}
```
public static final AttributeName Height_Auto
```

Attribute Height: Auto - 元素的高度应由其内容的固有高度决定。

### InlineAlign_Center {#InlineAlign_Center}
```
public static final AttributeName InlineAlign_Center
```

Attribute InlineAlign: Center - 每个子元素在表格单元格内居中。子元素分配矩形的起始边缘与表格单元格内容矩形的起始边缘之间的距离应与它们结束边缘之间的距离相同。

### InlineAlign_End {#InlineAlign_End}
```
public static final AttributeName InlineAlign_End
```

Attribute InlineAlign: End - 每个子元素分配矩形的结束边缘与表格单元格内容矩形的结束边缘对齐。

### InlineAlign_Start {#InlineAlign_Start}
```
public static final AttributeName InlineAlign_Start
```

Attribute InlineAlign: Start - 每个子元素分配矩形的起始边缘与表格单元格内容矩形的起始边缘对齐。

### LineHeight_Auto {#LineHeight_Auto}
```
public static final AttributeName LineHeight_Auto
```

Attribute LineHeight: Auto - 不对 BaselineShift 的值进行调整。

### LineHeight_Normal {#LineHeight_Normal}
```
public static final AttributeName LineHeight_Normal
```

Attribute LineHeight: Normal - 调整行高以包括 BaselineShift 指定的任何非零值。

### ListNumbering_Circle {#ListNumbering_Circle}
```
public static final AttributeName ListNumbering_Circle
```

Attribute ListNumbering: Circle - 开放的圆形项目符号。

### ListNumbering_Decimal {#ListNumbering_Decimal}
```
public static final AttributeName ListNumbering_Decimal
```

Attribute ListNumbering: Decimal - 十进制阿拉伯数字（1-9，10-99，...）。

### ListNumbering_Disc {#ListNumbering_Disc}
```
public static final AttributeName ListNumbering_Disc
```

Attribute ListNumbering: Disc - 实心圆形项目符号。

### ListNumbering_LowerAlpha {#ListNumbering_LowerAlpha}
```
public static final AttributeName ListNumbering_LowerAlpha
```

Attribute ListNumbering: LowerAlpha - 小写字母（a，b，c，...）。

### ListNumbering_LowerRoman {#ListNumbering_LowerRoman}
```
public static final AttributeName ListNumbering_LowerRoman
```

Attribute ListNumbering: LowerRoman - 小写罗马数字（i，ii，iii，iv，...）。

### ListNumbering_None {#ListNumbering_None}
```
public static final AttributeName ListNumbering_None
```

Attribute ListNumbering: None - 无自动编号；Lbl 元素（如果存在）包含不受任何编号方案约束的任意文本。

### ListNumbering_Square {#ListNumbering_Square}
```
public static final AttributeName ListNumbering_Square
```

Attribute ListNumbering: Square - 实心方形项目符号。

### ListNumbering_UpperAlpha {#ListNumbering_UpperAlpha}
```
public static final AttributeName ListNumbering_UpperAlpha
```

Attribute ListNumbering: UpperAlpha - 大写字母（A，B，C，...）。

### ListNumbering_UpperRoman {#ListNumbering_UpperRoman}
```
public static final AttributeName ListNumbering_UpperRoman
```

Attribute ListNumbering: UpperRoman - 大写罗马数字（I，II，III，IV，...）。

### Placement_Before {#Placement_Before}
```
public static final AttributeName Placement_Before
```

Attribute Placement: Before - 放置方式使元素分配矩形的前边缘与最近的封闭参考区域的前边缘重合。

### Placement_Block {#Placement_Block}
```
public static final AttributeName Placement_Block
```

Attribute Placement: Block - 在封闭参考区域或父 BLSE 内沿块进程方向堆叠。

### Placement_End {#Placement_End}
```
public static final AttributeName Placement_End
```

Attribute Placement: End - 放置方式使元素分配矩形的结束边缘与最近的封闭参考区域的结束边缘重合。

### Placement_Inline {#Placement_Inline}
```
public static final AttributeName Placement_Inline
```

Attribute Placement: Inline - 在封闭 BLSE 内沿行内进程方向紧凑排列。

### Placement_Start {#Placement_Start}
```
public static final AttributeName Placement_Start
```

属性放置：Start - 放置方式使元素分配矩形的起始边缘与最近的封闭参考区域的起始边缘重合。

### Role_cb {#Role_cb}
```
public static final AttributeName Role_cb
```

属性角色：cb - 复选框。

### Role_pb {#Role_pb}
```
public static final AttributeName Role_pb
```

属性角色：pb - 按钮。

### Role_rb {#Role_rb}
```
public static final AttributeName Role_rb
```

属性角色：rb - 单选按钮。

### Role_tv {#Role_tv}
```
public static final AttributeName Role_tv
```

属性角色：tv - 文本值字段。

### RubyAlign_Center {#RubyAlign_Center}
```
public static final AttributeName RubyAlign_Center
```

属性 RubyAlign：Center - 内容应在行内进展方向居中。

### RubyAlign_Distribute {#RubyAlign_Distribute}
```
public static final AttributeName RubyAlign_Distribute
```

属性 RubyAlign：Distribute - 内容应在行内进展方向上扩展以填满可用宽度。然而，还应在文本的起始边缘和结束边缘插入空白。间距应使用 1:2:1（起始:中间:结束）比例分配。如果 ruby 出现在文本行的起始位置，则比例改为 0:1:1；如果 ruby 出现在文本行的结束位置，则比例改为 1:1:0。

### RubyAlign_End {#RubyAlign_End}
```
public static final AttributeName RubyAlign_End
```

属性 RubyAlign：End - 内容应在行内进展方向的结束边缘对齐。

### RubyAlign_Justify {#RubyAlign_Justify}
```
public static final AttributeName RubyAlign_Justify
```

属性 RubyAlign：Justify - 内容应在行内进展方向上扩展以填满可用宽度。

### RubyAlign_Start {#RubyAlign_Start}
```
public static final AttributeName RubyAlign_Start
```

属性 RubyAlign：Start - 内容应在行内进展方向的起始边缘对齐。

### RubyPosition_After {#RubyPosition_After}
```
public static final AttributeName RubyPosition_After
```

属性 RubyPosition：After - RT 内容应沿元素的后边缘对齐。

### RubyPosition_Before {#RubyPosition_Before}
```
public static final AttributeName RubyPosition_Before
```

属性 RubyPosition：Before - RT 内容应沿元素的前边缘对齐。

### RubyPosition_Inline {#RubyPosition_Inline}
```
public static final AttributeName RubyPosition_Inline
```

属性 RubyPosition：Inline - RT 及其关联的 RP 元素应格式化为括号注释，位于 RB 元素之后。

### RubyPosition_Warichu {#RubyPosition_Warichu}
```
public static final AttributeName RubyPosition_Warichu
```

属性 RubyPosition：Warichu - RT 及其关联的 RP 元素应格式化为割注（warichu），位于 RB 元素之后。

### Scope_Both {#Scope_Both}
```
public static final AttributeName Scope_Both
```

属性范围：Both。

### Scope_Column {#Scope_Column}
```
public static final AttributeName Scope_Column
```

属性范围：Column。

### Scope_Row {#Scope_Row}
```
public static final AttributeName Scope_Row
```

属性范围：Row。

### TextAlign_Center {#TextAlign_Center}
```
public static final AttributeName TextAlign_Center
```

属性 TextAlign：Center - 在起始和结束边缘之间居中。

### TextAlign_End {#TextAlign_End}
```
public static final AttributeName TextAlign_End
```

属性 TextAlign：End - 与结束边缘对齐。

### TextAlign_Justify {#TextAlign_Justify}
```
public static final AttributeName TextAlign_Justify
```

属性 TextAlign：Justify - 与起始和结束边缘对齐，如有必要，通过扩展每行内部间距来实现此对齐。最后一行（或唯一一行）仅与起始边缘对齐。

### TextAlign_Start {#TextAlign_Start}
```
public static final AttributeName TextAlign_Start
```

属性 TextAlign：Start - 与起始边缘对齐。

### TextDecorationType_LineThrough {#TextDecorationType_LineThrough}
```
public static final AttributeName TextDecorationType_LineThrough
```

属性 TextDecorationType：LineThrough - 在文本中部加一条横线。

### TextDecorationType_None {#TextDecorationType_None}
```
public static final AttributeName TextDecorationType_None
```

属性 TextDecorationType：None - 无文本装饰。

### TextDecorationType_Overline {#TextDecorationType_Overline}
```
public static final AttributeName TextDecorationType_Overline
```

属性 TextDecorationType：Overline - 在文本上方加一条横线。

### TextDecorationType_Underline {#TextDecorationType_Underline}
```
public static final AttributeName TextDecorationType_Underline
```

属性 TextDecorationType：Underline - 在文本下方加一条横线。

### Width_Auto {#Width_Auto}
```
public static final AttributeName Width_Auto
```

属性宽度：Auto - 元素的宽度应由其内容的固有宽度决定。

### WritingMode_LrTb {#WritingMode_LrTb}
```
public static final AttributeName WritingMode_LrTb
```

属性写作模式：LrTb - 行内从左到右；块级从上到下。这是西方书写系统的典型写作模式。

### WritingMode_RlTb {#WritingMode_RlTb}
```
public static final AttributeName WritingMode_RlTb
```

属性写作模式：RlTb - 行内从右到左；块级从上到下。这是阿拉伯语和希伯来语书写系统的典型写作模式。

### WritingMode_TbRl {#WritingMode_TbRl}
```
public static final AttributeName WritingMode_TbRl
```

属性写作模式：TbRl - 行内从上到下；块级从右到左。这是中文和日文书写系统的典型写作模式。

### fromNameAttributeKey {#fromNameAttributeKey-java.lang.String-com.aspose.pdf.tagged.logicalstructure.AttributeKey-}
获取属性键对应的属性名称。

### getAttributeKey {#getAttributeKey--}
```
public final AttributeKey getAttributeKey()
```

获取属性键。

**Returns:**
AttributeKey 实例

### getName {#getName--}
```
public final String getName()
```

获取属性的名称值。

**Returns:**
字符串值

### toString {#toString--}
```
public String toString()
```

返回表示当前对象的字符串。

**Returns:**
表示当前对象的字符串。
