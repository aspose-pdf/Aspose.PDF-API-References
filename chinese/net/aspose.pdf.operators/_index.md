---
title: "Aspose.Pdf.Operators"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Operators 是 Operator 实现的命名空间。这些类描述了在 PDF 页面内容中使用的操作符。"
type: docs
weight: 160
url: /zh/net/aspose.pdf.operators/
---
**Aspose.Pdf.Operators** 是用于运算符实现的命名空间。这些类描述了在 PDF 页面内容中使用的运算符。

## 类

| 类 | 描述 |
| --- | --- |
| [BasicSetColorAndPatternOperator](./basicsetcolorandpatternoperator/) | 所有 Set Color 操作符的基操作符。 |
| [BasicSetColorOperator](./basicsetcoloroperator/) | set color 操作符的基类。 |
| [BDC](./bdc/) | 表示 BDC 操作符的类（Begin marked-content sequence） |
| [BI](./bi/) | 表示 BI 操作符的类（Begin inline image obect）。 |
| [BlockTextOperator](./blocktextoperator/) | 文本块操作符的抽象基类，即 Begin 和 End 文本操作符（BT/ET） |
| [BMC](./bmc/) | 表示 BMC 操作符的类（Begin marked-content sequence）。 |
| [BT](./bt/) | 表示 BT 操作符的类（Begin of text block）。 |
| [BX](./bx/) | 表示 BX 操作符的类（begin compatibility section）。 |
| [Clip](./clip/) | 表示 W 操作符的类（使用非零环绕规则设置剪裁路径）。 |
| [ClosePath](./closepath/) | 表示 h 操作符的类（close path）。 |
| [ClosePathEOFillStroke](./closepatheofillstroke/) | 表示 b* 操作符的类（使用奇偶规则关闭、填充和描边路径）。 |
| [ClosePathFillStroke](./closepathfillstroke/) | 表示 b 操作符的类（使用非零环绕规则关闭、填充和描边路径）。 |
| [ClosePathStroke](./closepathstroke/) | 表示 s 操作符的类（关闭并描边路径）。 |
| [ConcatenateMatrix](./concatenatematrix/) | 表示 cm 操作符的类（将矩阵连接到当前变换矩阵）。 |
| [CurveTo](./curveto/) | 表示 c 操作符的类（向路径追加曲线）。 |
| [CurveTo1](./curveto1/) | 表示 v 操作符的类（向路径追加曲线，复制初始点）。 |
| [CurveTo2](./curveto2/) | 表示 y 操作符的类（向路径追加曲线，复制终点）。 |
| [Do](./do/) | 表示 Do 操作符的类（调用 XObject）。 |
| [DP](./dp/) | 表示 DP 操作符的类（designamte 标记内容点）。 |
| [EI](./ei/) | 表示 EI 操作符的类（End inline image object）。 |
| [EMC](./emc/) | 表示 EMC 操作符的类（End of marked-content sequence）。 |
| [EndPath](./endpath/) | 表示 n 操作符的类（结束路径而不填充或描边）。 |
| [EOClip](./eoclip/) | 表示 W* 操作符的类（使用奇偶规则设置剪裁路径）。 |
| [EOFill](./eofill/) | 表示 f* 操作符的类（使用奇偶规则填充路径）。 |
| [EOFillStroke](./eofillstroke/) | 表示 B* 操作符的类（使用奇偶规则填充并描边路径）。 |
| [ET](./et/) | 表示运算符 ET（文本块结束）的类。 |
| [EX](./ex/) | 表示运算符 EX（兼容性节结束）的类。 |
| [Fill](./fill/) | 表示运算符 f（使用非零环绕数规则填充路径）的类。 |
| [FillStroke](./fillstroke/) | 表示运算符 B（使用非零环绕规则填充并描边路径）的类 |
| [GlyphPosition](./glyphposition/) | 描述用于运算符 TJ（设置带位置的字形）的文本和位置的类 |
| [GRestore](./grestore/) | 表示运算符 Q（恢复图形状态）的类。 |
| [GS](./gs/) | 表示运算符 gs（从图形状态参数字典设置参数）的类。 |
| [GSave](./gsave/) | 表示运算符 q（保存图形状态）的类。 |
| [ID](./id/) | 表示运算符 ID（开始内联图像数据）的类。 |
| [LineTo](./lineto/) | 表示运算符 l（向路径添加直线）的类。 |
| [MoveTextPosition](./movetextposition/) | 表示运算符 Td（移动文本位置）的类。 |
| [MoveTextPositionSetLeading](./movetextpositionsetleading/) | 表示运算符 TD（移动位置并设置行距）的类。 |
| [MoveTo](./moveto/) | 表示运算符 m（移动到并开始新子路径）的类。 |
| [MoveToNextLine](./movetonextline/) | 表示运算符 T*（移动到下一行的起始位置）的类。 |
| [MoveToNextLineShowText](./movetonextlineshowtext/) | 表示运算符 '（移动到下一行并显示文本）的类。 |
| [MP](./mp/) | 表示运算符 MP（定义标记内容点）的类。 |
| [ObsoleteFill](./obsoletefill/) | 表示运算符 F（使用非零环绕规则填充路径）的类。 |
| [Re](./re/) | 表示运算符 re（向路径添加矩形）的类。 |
| [SelectFont](./selectfont/) | 表示运算符 Tf（设置文本字体和大小）的类。 |
| [SetAdvancedColor](./setadvancedcolor/) | 表示运算符 scn（为非描边操作设置颜色）的类。 |
| [SetAdvancedColorStroke](./setadvancedcolorstroke/) | 表示运算符 SCN（为描边操作设置颜色）的类。 |
| [SetCharacterSpacing](./setcharacterspacing/) | 表示运算符 Tc（设置字符间距）的类。 |
| [SetCharWidth](./setcharwidth/) | 表示运算符 d0（设置字形宽度）的类。 |
| [SetCharWidthBoundingBox](./setcharwidthboundingbox/) | 表示运算符 d1（设置字形和边界框）的类。 |
| [SetCMYKColor](./setcmykcolor/) | 表示运算符 k（为非描边操作设置 CMYK 颜色）的类。 |
| [SetCMYKColorStroke](./setcmykcolorstroke/) | 表示 K 运算符的类（为描边操作设置 CMYK 颜色）。 |
| [SetColor](./setcolor/) | 表示 sc 运算符的类（为非描边操作设置颜色）。 |
| [SetColorOperator](./setcoloroperator/) | 表示设置颜色操作的类。 |
| [SetColorRenderingIntent](./setcolorrenderingintent/) | 表示 ri 运算符的类（设置颜色渲染意图）。 |
| [SetColorSpace](./setcolorspace/) | 表示 cs 运算符的类（为非描边操作设置颜色空间） |
| [SetColorSpaceStroke](./setcolorspacestroke/) | 表示 CS 运算符的类（为描边操作设置颜色）。 |
| [SetColorStroke](./setcolorstroke/) | 表示 SC 运算符的类，用于为描边颜色运算符设置颜色。 |
| [SetDash](./setdash/) | 表示 d 运算符的类（设置线段虚线模式）。 |
| [SetFlat](./setflat/) | 表示 i 运算符的类（设置平坦度容差）。 |
| [SetGlyphsPositionShowText](./setglyphspositionshowtext/) | 表示 TJ 运算符的类（显示带有字形定位的文本）。 |
| [SetGray](./setgray/) | 为非描边操作设置灰度级别。 |
| [SetGrayStroke](./setgraystroke/) | 表示描边操作灰度级别的类。 |
| [SetHorizontalTextScaling](./sethorizontaltextscaling/) | 表示 Tz 运算符的类（设置水平文本缩放）。 |
| [SetLineCap](./setlinecap/) | 表示 J 运算符的类（设置线帽样式）。 |
| [SetLineJoin](./setlinejoin/) | 表示 j 运算符的类（设置线段连接样式）。 |
| [SetLineWidth](./setlinewidth/) | 表示 w 运算符的类（设置线宽）。 |
| [SetMiterLimit](./setmiterlimit/) | 表示 M 运算符的类（设置斜接限制）。 |
| [SetRGBColor](./setrgbcolor/) | 表示 rg 运算符的类（为非描边运算符设置 RGB 颜色）。 |
| [SetRGBColorStroke](./setrgbcolorstroke/) | 表示 RG 运算符的类（为描边运算符设置 RGB 颜色）。 |
| [SetSpacingMoveToNextLineShowText](./setspacingmovetonextlineshowtext/) | 表示 \" 运算符的类（设置字间距和字符间距，移动到下一行并显示文本）。 |
| [SetTextLeading](./settextleading/) | 表示 TL 运算符的类（设置文本行距）。 |
| [SetTextMatrix](./settextmatrix/) | 表示 Tm 运算符的类（设置文本矩阵）。 |
| [SetTextRenderingMode](./settextrenderingmode/) | 表示 Tr 运算符的类（设置文本渲染模式）。 |
| [SetTextRise](./settextrise/) | 表示 Ts 运算符的类（设置文本上升）。 |
| [SetWordSpacing](./setwordspacing/) | 表示 Tw 运算符的类（设置单词间距）。 |
| [ShFill](./shfill/) | 表示 sh 操作符的类（使用阴影图案绘制区域）。 |
| [ShowText](./showtext/) | 表示 Tj 操作符的类（显示文本）。 |
| [Stroke](./stroke/) | 表示 S 操作符的类（描边路径）。 |
| [TextOperator](./textoperator/) | 文本相关操作符的抽象基类（TJ、Tj、Tm、BT、ET 等）。 |
| [TextPlaceOperator](./textplaceoperator/) | 改变文本位置的操作符的抽象基类（Tm、Td 等）。 |
| [TextShowOperator](./textshowoperator/) | 用于输出文本的所有操作符的抽象基类（Tj、TJ 等）。 |
| [TextStateOperator](./textstateoperator/) | 改变当前文本状态的操作符的抽象基类（Tc、Tf、TL 等）。 |
## 枚举

| 枚举 | 描述 |
| --- | --- |
| [LineCap](./linecap/) | 线帽样式应指定在描边时用于开放子路径（以及虚线，如有）的端点形状。 |
| [LineJoin](./linejoin/) | 线段连接样式应指定在描边路径的拐角处使用的形状。 |


