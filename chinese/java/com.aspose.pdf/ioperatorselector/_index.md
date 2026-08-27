---
title: "IOperatorSelector"
linktitle: "IOperatorSelector"
second_title: "Aspose.PDF for Java API 参考"
description: "定义用于访问不同 PDF 操作符的 Visitor。"
type: docs
weight: 2520
url: /zh/java/com.aspose.pdf/ioperatorselector/
---
```
public interface IOperatorSelector
```

定义用于访问不同 PDF 操作符的 Visitor。

## 方法

| 方法 | 描述 |
| --- | --- |
| [visit](#visit-com.aspose.pdf.operators.BDC-) | 访问/选择 BDC 操作符。 |
| [visit](#visit-com.aspose.pdf.operators.BI-) | 访问/选择 BI 操作符。 |
| [visit](#visit-com.aspose.pdf.operators.BMC-) | 访问/选择 BMC 操作符。 |
| [visit](#visit-com.aspose.pdf.operators.BT-) | 访问/选择 BT 操作符。 |
| [visit](#visit-com.aspose.pdf.operators.BX-) | 访问/选择 BX 操作符。 |
| [visit](#visit-com.aspose.pdf.operators.Clip-) | 访问/选择 W 操作符。 |
| [visit](#visit-com.aspose.pdf.operators.ClosePath-) | 访问/选择 h 操作符。 |
| [visit](#visit-com.aspose.pdf.operators.ClosePathEOFillStroke-) | 访问/选择 b* 操作符。 |
| [visit](#visit-com.aspose.pdf.operators.ClosePathFillStroke-) | 访问/选择 b 操作符。 |
| [visit](#visit-com.aspose.pdf.operators.ClosePathStroke-) | 访问/选择 s 操作符。 |
| [visit](#visit-com.aspose.pdf.operators.ConcatenateMatrix-) | 访问/选择 cm 操作符。 |
| [visit](#visit-com.aspose.pdf.operators.CurveTo-) | 访问/选择 c 操作符。 |
| [visit](#visit-com.aspose.pdf.operators.CurveTo1-) | 访问/选择 v 操作符。 |
| [visit](#visit-com.aspose.pdf.operators.CurveTo2-) | 访问/选择 y 操作符。 |
| [visit](#visit-com.aspose.pdf.operators.Do-) | 访问/选择 Do 操作符。 |
| [visit](#visit-com.aspose.pdf.operators.DP-) | 访问/选择 DP 操作符。 |
| [visit](#visit-com.aspose.pdf.operators.EI-) | 访问/选择 EI 操作符。 |
| [visit](#visit-com.aspose.pdf.operators.EMC-) | 访问/选择 EMC 操作符。 |
| [visit](#visit-com.aspose.pdf.operators.EndPath-) | 访问/选择 n 操作符。 |
| [visit](#visit-com.aspose.pdf.operators.EOClip-) | 访问/选择 W* 操作符。 |
| [visit](#visit-com.aspose.pdf.operators.EOFill-) | 访问/选择 f* 操作符。 |
| [visit](#visit-com.aspose.pdf.operators.EOFillStroke-) | 访问/选择 B* 操作符。 |
| [visit](#visit-com.aspose.pdf.operators.ET-) | 访问/选择 ET 操作符。 |
| [visit](#visit-com.aspose.pdf.operators.EX-) | 访问/选择 EX 运算符。 |
| [visit](#visit-com.aspose.pdf.operators.Fill-) | 访问/选择 f 运算符。 |
| [visit](#visit-com.aspose.pdf.operators.FillStroke-) | 访问/选择 B 运算符。 |
| [visit](#visit-com.aspose.pdf.operators.GRestore-) | 访问/选择 Q 运算符。 |
| [visit](#visit-com.aspose.pdf.operators.GS-) | 访问/选择 gs 运算符。 |
| [visit](#visit-com.aspose.pdf.operators.GSave-) | 访问/选择 q 运算符。 |
| [visit](#visit-com.aspose.pdf.operators.ID-) | 访问/选择 ID 运算符。 |
| [visit](#visit-com.aspose.pdf.operators.LineTo-) | 访问/选择 l 运算符。 |
| [visit](#visit-com.aspose.pdf.operators.MoveTextPosition-) | 访问/选择 Td 运算符。 |
| [visit](#visit-com.aspose.pdf.operators.MoveTextPositionSetLeading-) | 访问/选择 TD 运算符。 |
| [visit](#visit-com.aspose.pdf.operators.MoveTo-) | 访问/选择 m 运算符。 |
| [visit](#visit-com.aspose.pdf.operators.MoveToNextLine-) | 访问/选择 T* 运算符。 |
| [visit](#visit-com.aspose.pdf.operators.MoveToNextLineShowText-) | 访问/选择 ' 运算符。 |
| [visit](#visit-com.aspose.pdf.operators.MP-) | 访问/选择 MP 运算符。 |
| [visit](#visit-com.aspose.pdf.operators.ObsoleteFill-) | 访问/选择 F 运算符。 |
| [visit](#visit-com.aspose.pdf.operators.Re-) | 访问/选择 re 运算符。 |
| [visit](#visit-com.aspose.pdf.operators.SelectFont-) | 访问/选择 Tf 运算符。 |
| [visit](#visit-com.aspose.pdf.operators.SetAdvancedColor-) | 访问/选择 scn 运算符。 |
| [visit](#visit-com.aspose.pdf.operators.SetAdvancedColorStroke-) | 访问/选择 SCN 运算符。 |
| [visit](#visit-com.aspose.pdf.operators.SetCharacterSpacing-) | 访问/选择 Tc 运算符。 |
| [visit](#visit-com.aspose.pdf.operators.SetCharWidth-) | 访问/选择 d0 运算符。 |
| [visit](#visit-com.aspose.pdf.operators.SetCharWidthBoundingBox-) | 访问/选择 d1 运算符。 |
| [visit](#visit-com.aspose.pdf.operators.SetCMYKColor-) | 访问/选择 k 运算符。 |
| [visit](#visit-com.aspose.pdf.operators.SetCMYKColorStroke-) | 访问/选择 K 运算符。 |
| [visit](#visit-com.aspose.pdf.operators.SetColor-) | 访问/选择 sc 运算符。 |
| [visit](#visit-com.aspose.pdf.operators.SetColorRenderingIntent-) | 访问/选择 ri 操作符。 |
| [visit](#visit-com.aspose.pdf.operators.SetColorSpace-) | 访问/选择 cs 操作符。 |
| [visit](#visit-com.aspose.pdf.operators.SetColorSpaceStroke-) | 访问/选择 CS 操作符。 |
| [visit](#visit-com.aspose.pdf.operators.SetColorStroke-) | 访问/选择 SC 操作符。 |
| [visit](#visit-com.aspose.pdf.operators.SetDash-) | 访问/选择 d 操作符。 |
| [visit](#visit-com.aspose.pdf.operators.SetFlat-) | 访问/选择 i 操作符。 |
| [visit](#visit-com.aspose.pdf.operators.SetGlyphsPositionShowText-) | 访问/选择 TJ 操作符。 |
| [visit](#visit-com.aspose.pdf.operators.SetGray-) | 访问/选择 g 操作符。 |
| [visit](#visit-com.aspose.pdf.operators.SetGrayStroke-) | 访问/选择 G 操作符。 |
| [visit](#visit-com.aspose.pdf.operators.SetHorizontalTextScaling-) | 访问/选择 Tz 操作符。 |
| [visit](#visit-com.aspose.pdf.operators.SetLineCap-) | 访问/选择 J 操作符。 |
| [visit](#visit-com.aspose.pdf.operators.SetLineJoin-) | 访问/选择 j 操作符。 |
| [visit](#visit-com.aspose.pdf.operators.SetLineWidth-) | 访问/选择 w 操作符。 |
| [visit](#visit-com.aspose.pdf.operators.SetMiterLimit-) | 访问/选择 M 操作符。 |
| [visit](#visit-com.aspose.pdf.operators.SetRGBColor-) | 访问/选择 rg 操作符。 |
| [visit](#visit-com.aspose.pdf.operators.SetRGBColorStroke-) | 访问/选择 RG 操作符。 |
| [visit](#visit-com.aspose.pdf.operators.SetSpacingMoveToNextLineShowText-) | 访问/选择 '' 操作符。 |
| [visit](#visit-com.aspose.pdf.operators.SetTextLeading-) | 访问/选择 TL 操作符。 |
| [visit](#visit-com.aspose.pdf.operators.SetTextMatrix-) | 访问/选择 Tm 操作符。 |
| [visit](#visit-com.aspose.pdf.operators.SetTextRenderingMode-) | 访问/选择 Tr 操作符。 |
| [visit](#visit-com.aspose.pdf.operators.SetTextRise-) | 访问/选择 Ts 操作符。 |
| [visit](#visit-com.aspose.pdf.operators.SetWordSpacing-) | 访问/选择 Tw 操作符。 |
| [visit](#visit-com.aspose.pdf.operators.ShFill-) | 访问/选择 sh 操作符。 |
| [visit](#visit-com.aspose.pdf.operators.ShowText-) | 访问/选择 Tj 操作符。 |
| [visit](#visit-com.aspose.pdf.operators.Stroke-) | 访问/选择 S 操作符。 |
| [visit](#visit-com.aspose.pdf.operators.TextOperator-) | 访问/选择任意文本运算符运算符。 |

### visit {#visit-com.aspose.pdf.operators.BDC-}
访问/选择 BDC 操作符。

### visit {#visit-com.aspose.pdf.operators.BI-}
访问/选择 BI 操作符。

### visit {#visit-com.aspose.pdf.operators.BMC-}
访问/选择 BMC 操作符。

### visit {#visit-com.aspose.pdf.operators.BT-}
访问/选择 BT 操作符。

### visit {#visit-com.aspose.pdf.operators.BX-}
访问/选择 BX 操作符。

### visit {#visit-com.aspose.pdf.operators.Clip-}
访问/选择 W 操作符。

### visit {#visit-com.aspose.pdf.operators.ClosePath-}
访问/选择 h 操作符。

### visit {#visit-com.aspose.pdf.operators.ClosePathEOFillStroke-}
访问/选择 b* 操作符。

### visit {#visit-com.aspose.pdf.operators.ClosePathFillStroke-}
访问/选择 b 操作符。

### visit {#visit-com.aspose.pdf.operators.ClosePathStroke-}
访问/选择 s 操作符。

### visit {#visit-com.aspose.pdf.operators.ConcatenateMatrix-}
访问/选择 cm 操作符。

### visit {#visit-com.aspose.pdf.operators.CurveTo-}
访问/选择 c 操作符。

### visit {#visit-com.aspose.pdf.operators.CurveTo1-}
访问/选择 v 操作符。

### visit {#visit-com.aspose.pdf.operators.CurveTo2-}
访问/选择 y 操作符。

### visit {#visit-com.aspose.pdf.operators.Do-}
访问/选择 Do 操作符。

### visit {#visit-com.aspose.pdf.operators.DP-}
访问/选择 DP 操作符。

### visit {#visit-com.aspose.pdf.operators.EI-}
访问/选择 EI 操作符。

### visit {#visit-com.aspose.pdf.operators.EMC-}
访问/选择 EMC 操作符。

### visit {#visit-com.aspose.pdf.operators.EndPath-}
访问/选择 n 操作符。

### visit {#visit-com.aspose.pdf.operators.EOClip-}
访问/选择 W* 操作符。

### visit {#visit-com.aspose.pdf.operators.EOFill-}
访问/选择 f* 操作符。

### visit {#visit-com.aspose.pdf.operators.EOFillStroke-}
访问/选择 B* 操作符。

### visit {#visit-com.aspose.pdf.operators.ET-}
访问/选择 ET 操作符。

### visit {#visit-com.aspose.pdf.operators.EX-}
访问/选择 EX 运算符。

### visit {#visit-com.aspose.pdf.operators.Fill-}
访问/选择 f 运算符。

### visit {#visit-com.aspose.pdf.operators.FillStroke-}
访问/选择 B 运算符。

### visit {#visit-com.aspose.pdf.operators.GRestore-}
访问/选择 Q 运算符。

### visit {#visit-com.aspose.pdf.operators.GS-}
访问/选择 gs 运算符。

### visit {#visit-com.aspose.pdf.operators.GSave-}
访问/选择 q 运算符。

### visit {#visit-com.aspose.pdf.operators.ID-}
访问/选择 ID 运算符。

### visit {#visit-com.aspose.pdf.operators.LineTo-}
访问/选择 l 运算符。

### visit {#visit-com.aspose.pdf.operators.MoveTextPosition-}
访问/选择 Td 运算符。

### visit {#visit-com.aspose.pdf.operators.MoveTextPositionSetLeading-}
访问/选择 TD 运算符。

### visit {#visit-com.aspose.pdf.operators.MoveTo-}
访问/选择 m 运算符。

### visit {#visit-com.aspose.pdf.operators.MoveToNextLine-}
访问/选择 T* 运算符。

### visit {#visit-com.aspose.pdf.operators.MoveToNextLineShowText-}
访问/选择 ' 运算符。

### visit {#visit-com.aspose.pdf.operators.MP-}
访问/选择 MP 运算符。

### visit {#visit-com.aspose.pdf.operators.ObsoleteFill-}
访问/选择 F 运算符。

### visit {#visit-com.aspose.pdf.operators.Re-}
访问/选择 re 运算符。

### visit {#visit-com.aspose.pdf.operators.SelectFont-}
访问/选择 Tf 运算符。

### visit {#visit-com.aspose.pdf.operators.SetAdvancedColor-}
访问/选择 scn 运算符。

### visit {#visit-com.aspose.pdf.operators.SetAdvancedColorStroke-}
访问/选择 SCN 运算符。

### visit {#visit-com.aspose.pdf.operators.SetCharacterSpacing-}
访问/选择 Tc 运算符。

### visit {#visit-com.aspose.pdf.operators.SetCharWidth-}
访问/选择 d0 运算符。

### visit {#visit-com.aspose.pdf.operators.SetCharWidthBoundingBox-}
访问/选择 d1 运算符。

### visit {#visit-com.aspose.pdf.operators.SetCMYKColor-}
访问/选择 k 运算符。

### visit {#visit-com.aspose.pdf.operators.SetCMYKColorStroke-}
访问/选择 K 运算符。

### visit {#visit-com.aspose.pdf.operators.SetColor-}
访问/选择 sc 运算符。

### visit {#visit-com.aspose.pdf.operators.SetColorRenderingIntent-}
访问/选择 ri 操作符。

### visit {#visit-com.aspose.pdf.operators.SetColorSpace-}
访问/选择 cs 操作符。

### visit {#visit-com.aspose.pdf.operators.SetColorSpaceStroke-}
访问/选择 CS 操作符。

### visit {#visit-com.aspose.pdf.operators.SetColorStroke-}
访问/选择 SC 操作符。

### visit {#visit-com.aspose.pdf.operators.SetDash-}
访问/选择 d 操作符。

### visit {#visit-com.aspose.pdf.operators.SetFlat-}
访问/选择 i 操作符。

### visit {#visit-com.aspose.pdf.operators.SetGlyphsPositionShowText-}
访问/选择 TJ 操作符。

### visit {#visit-com.aspose.pdf.operators.SetGray-}
访问/选择 g 操作符。

### visit {#visit-com.aspose.pdf.operators.SetGrayStroke-}
访问/选择 G 操作符。

### visit {#visit-com.aspose.pdf.operators.SetHorizontalTextScaling-}
访问/选择 Tz 操作符。

### visit {#visit-com.aspose.pdf.operators.SetLineCap-}
访问/选择 J 操作符。

### visit {#visit-com.aspose.pdf.operators.SetLineJoin-}
访问/选择 j 操作符。

### visit {#visit-com.aspose.pdf.operators.SetLineWidth-}
访问/选择 w 操作符。

### visit {#visit-com.aspose.pdf.operators.SetMiterLimit-}
访问/选择 M 操作符。

### visit {#visit-com.aspose.pdf.operators.SetRGBColor-}
访问/选择 rg 操作符。

### visit {#visit-com.aspose.pdf.operators.SetRGBColorStroke-}
访问/选择 RG 操作符。

### visit {#visit-com.aspose.pdf.operators.SetSpacingMoveToNextLineShowText-}
访问/选择 '' 操作符。

### visit {#visit-com.aspose.pdf.operators.SetTextLeading-}
访问/选择 TL 操作符。

### visit {#visit-com.aspose.pdf.operators.SetTextMatrix-}
访问/选择 Tm 操作符。

### visit {#visit-com.aspose.pdf.operators.SetTextRenderingMode-}
访问/选择 Tr 操作符。

### visit {#visit-com.aspose.pdf.operators.SetTextRise-}
访问/选择 Ts 操作符。

### visit {#visit-com.aspose.pdf.operators.SetWordSpacing-}
访问/选择 Tw 操作符。

### visit {#visit-com.aspose.pdf.operators.ShFill-}
访问/选择 sh 操作符。

### visit {#visit-com.aspose.pdf.operators.ShowText-}
访问/选择 Tj 操作符。

### visit {#visit-com.aspose.pdf.operators.Stroke-}
访问/选择 S 操作符。

### visit {#visit-com.aspose.pdf.operators.TextOperator-}
访问/选择任意文本运算符运算符。
