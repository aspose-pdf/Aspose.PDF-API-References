---
title: IOperatorSelector
linktitle: IOperatorSelector
second_title: Aspose.PDF for Java API Reference
description: Defines Visitor for visiting different pdf operators.
type: docs
weight: 2520
url: /java/com.aspose.pdf/ioperatorselector/
---
```
public interface IOperatorSelector
```

Defines Visitor for visiting different pdf operators.

## Methods

| Method | Description |
| --- | --- |
| [visit](#visit-com.aspose.pdf.operators.BDC-) | Visit/select BDC operator. |
| [visit](#visit-com.aspose.pdf.operators.BI-) | Visit/select BI operator. |
| [visit](#visit-com.aspose.pdf.operators.BMC-) | Visit/select BMC operator. |
| [visit](#visit-com.aspose.pdf.operators.BT-) | Visit/select BT operator. |
| [visit](#visit-com.aspose.pdf.operators.BX-) | Visit/select BX operator. |
| [visit](#visit-com.aspose.pdf.operators.Clip-) | Visit/select W operator. |
| [visit](#visit-com.aspose.pdf.operators.ClosePath-) | Visit/select h operator. |
| [visit](#visit-com.aspose.pdf.operators.ClosePathEOFillStroke-) | Visit/select b* operator. |
| [visit](#visit-com.aspose.pdf.operators.ClosePathFillStroke-) | Visit/select b operator. |
| [visit](#visit-com.aspose.pdf.operators.ClosePathStroke-) | Visit/select s operator. |
| [visit](#visit-com.aspose.pdf.operators.ConcatenateMatrix-) | Visit/select cm operator. |
| [visit](#visit-com.aspose.pdf.operators.CurveTo-) | Visit/select c operator. |
| [visit](#visit-com.aspose.pdf.operators.CurveTo1-) | Visit/select v operator. |
| [visit](#visit-com.aspose.pdf.operators.CurveTo2-) | Visit/select y operator. |
| [visit](#visit-com.aspose.pdf.operators.Do-) | Visit/select Do operator. |
| [visit](#visit-com.aspose.pdf.operators.DP-) | Visit/select DP operator. |
| [visit](#visit-com.aspose.pdf.operators.EI-) | Visit/select EI operator. |
| [visit](#visit-com.aspose.pdf.operators.EMC-) | Visit/select EMC operator. |
| [visit](#visit-com.aspose.pdf.operators.EndPath-) | Visit/select n operator. |
| [visit](#visit-com.aspose.pdf.operators.EOClip-) | Visit/select W* operator. |
| [visit](#visit-com.aspose.pdf.operators.EOFill-) | Visit/select operator f*. |
| [visit](#visit-com.aspose.pdf.operators.EOFillStroke-) | Visit/select B* operator. |
| [visit](#visit-com.aspose.pdf.operators.ET-) | Visit/select ET operator. |
| [visit](#visit-com.aspose.pdf.operators.EX-) | Visit/select EX operator. |
| [visit](#visit-com.aspose.pdf.operators.Fill-) | Visit/select f operator. |
| [visit](#visit-com.aspose.pdf.operators.FillStroke-) | Visit/select B operator. |
| [visit](#visit-com.aspose.pdf.operators.GRestore-) | Visit/select Q operator. |
| [visit](#visit-com.aspose.pdf.operators.GS-) | Visit/select gs operator. |
| [visit](#visit-com.aspose.pdf.operators.GSave-) | Visit/select q operator. |
| [visit](#visit-com.aspose.pdf.operators.ID-) | Visit/select ID operator. |
| [visit](#visit-com.aspose.pdf.operators.LineTo-) | Visit/select l operator. |
| [visit](#visit-com.aspose.pdf.operators.MoveTextPosition-) | Visit/select Td operator. |
| [visit](#visit-com.aspose.pdf.operators.MoveTextPositionSetLeading-) | Visit/select TD operator. |
| [visit](#visit-com.aspose.pdf.operators.MoveTo-) | Visit/select m operator. |
| [visit](#visit-com.aspose.pdf.operators.MoveToNextLine-) | Visit/select T* operator. |
| [visit](#visit-com.aspose.pdf.operators.MoveToNextLineShowText-) | Visit/select ' operator. |
| [visit](#visit-com.aspose.pdf.operators.MP-) | Visit/select MP operator. |
| [visit](#visit-com.aspose.pdf.operators.ObsoleteFill-) | Visit/select F operator. |
| [visit](#visit-com.aspose.pdf.operators.Re-) | Visit/select re operator. |
| [visit](#visit-com.aspose.pdf.operators.SelectFont-) | Visit/select Tf operator. |
| [visit](#visit-com.aspose.pdf.operators.SetAdvancedColor-) | Visit/select scn operator. |
| [visit](#visit-com.aspose.pdf.operators.SetAdvancedColorStroke-) | Visit/select SCN operator. |
| [visit](#visit-com.aspose.pdf.operators.SetCharacterSpacing-) | Visit/select Tc operator. |
| [visit](#visit-com.aspose.pdf.operators.SetCharWidth-) | Visit/select d0 operator. |
| [visit](#visit-com.aspose.pdf.operators.SetCharWidthBoundingBox-) | Visit/select d1 operator. |
| [visit](#visit-com.aspose.pdf.operators.SetCMYKColor-) | Visit/select k operator. |
| [visit](#visit-com.aspose.pdf.operators.SetCMYKColorStroke-) | Visit/select K operator. |
| [visit](#visit-com.aspose.pdf.operators.SetColor-) | Visit/select sc operator. |
| [visit](#visit-com.aspose.pdf.operators.SetColorRenderingIntent-) | Visit/select ri operator. |
| [visit](#visit-com.aspose.pdf.operators.SetColorSpace-) | Visit/select cs operator. |
| [visit](#visit-com.aspose.pdf.operators.SetColorSpaceStroke-) | Visit/select CS operator. |
| [visit](#visit-com.aspose.pdf.operators.SetColorStroke-) | Visit/select SC operator. |
| [visit](#visit-com.aspose.pdf.operators.SetDash-) | Visit/select d operator. |
| [visit](#visit-com.aspose.pdf.operators.SetFlat-) | Visit/select i operator. |
| [visit](#visit-com.aspose.pdf.operators.SetGlyphsPositionShowText-) | Visit/select TJ operator. |
| [visit](#visit-com.aspose.pdf.operators.SetGray-) | Visit/select g operator. |
| [visit](#visit-com.aspose.pdf.operators.SetGrayStroke-) | Visit/select G operator. |
| [visit](#visit-com.aspose.pdf.operators.SetHorizontalTextScaling-) | Visit/select Tz operator. |
| [visit](#visit-com.aspose.pdf.operators.SetLineCap-) | Visit/select J operator. |
| [visit](#visit-com.aspose.pdf.operators.SetLineJoin-) | Visit/select j operator. |
| [visit](#visit-com.aspose.pdf.operators.SetLineWidth-) | Visit/select w operator. |
| [visit](#visit-com.aspose.pdf.operators.SetMiterLimit-) | Visit/select M operator. |
| [visit](#visit-com.aspose.pdf.operators.SetRGBColor-) | Visit/select rg operator. |
| [visit](#visit-com.aspose.pdf.operators.SetRGBColorStroke-) | Visit/select RG operator. |
| [visit](#visit-com.aspose.pdf.operators.SetSpacingMoveToNextLineShowText-) | Visit/select '' operator. |
| [visit](#visit-com.aspose.pdf.operators.SetTextLeading-) | Visit/select TL operator. |
| [visit](#visit-com.aspose.pdf.operators.SetTextMatrix-) | Visit/select Tm operator. |
| [visit](#visit-com.aspose.pdf.operators.SetTextRenderingMode-) | Visit/select Tr operator. |
| [visit](#visit-com.aspose.pdf.operators.SetTextRise-) | Visit/select Ts operator. |
| [visit](#visit-com.aspose.pdf.operators.SetWordSpacing-) | Visit/select Tw operator. |
| [visit](#visit-com.aspose.pdf.operators.ShFill-) | Visit/select sh operator. |
| [visit](#visit-com.aspose.pdf.operators.ShowText-) | Visit/select Tj operator. |
| [visit](#visit-com.aspose.pdf.operators.Stroke-) | Visit/select S operator. |
| [visit](#visit-com.aspose.pdf.operators.TextOperator-) | Visit/select any text operator operator. |

### visit {#visit-com.aspose.pdf.operators.BDC-}
Visit/select BDC operator.

### visit {#visit-com.aspose.pdf.operators.BI-}
Visit/select BI operator.

### visit {#visit-com.aspose.pdf.operators.BMC-}
Visit/select BMC operator.

### visit {#visit-com.aspose.pdf.operators.BT-}
Visit/select BT operator.

### visit {#visit-com.aspose.pdf.operators.BX-}
Visit/select BX operator.

### visit {#visit-com.aspose.pdf.operators.Clip-}
Visit/select W operator.

### visit {#visit-com.aspose.pdf.operators.ClosePath-}
Visit/select h operator.

### visit {#visit-com.aspose.pdf.operators.ClosePathEOFillStroke-}
Visit/select b* operator.

### visit {#visit-com.aspose.pdf.operators.ClosePathFillStroke-}
Visit/select b operator.

### visit {#visit-com.aspose.pdf.operators.ClosePathStroke-}
Visit/select s operator.

### visit {#visit-com.aspose.pdf.operators.ConcatenateMatrix-}
Visit/select cm operator.

### visit {#visit-com.aspose.pdf.operators.CurveTo-}
Visit/select c operator.

### visit {#visit-com.aspose.pdf.operators.CurveTo1-}
Visit/select v operator.

### visit {#visit-com.aspose.pdf.operators.CurveTo2-}
Visit/select y operator.

### visit {#visit-com.aspose.pdf.operators.Do-}
Visit/select Do operator.

### visit {#visit-com.aspose.pdf.operators.DP-}
Visit/select DP operator.

### visit {#visit-com.aspose.pdf.operators.EI-}
Visit/select EI operator.

### visit {#visit-com.aspose.pdf.operators.EMC-}
Visit/select EMC operator.

### visit {#visit-com.aspose.pdf.operators.EndPath-}
Visit/select n operator.

### visit {#visit-com.aspose.pdf.operators.EOClip-}
Visit/select W* operator.

### visit {#visit-com.aspose.pdf.operators.EOFill-}
Visit/select operator f*.

### visit {#visit-com.aspose.pdf.operators.EOFillStroke-}
Visit/select B* operator.

### visit {#visit-com.aspose.pdf.operators.ET-}
Visit/select ET operator.

### visit {#visit-com.aspose.pdf.operators.EX-}
Visit/select EX operator.

### visit {#visit-com.aspose.pdf.operators.Fill-}
Visit/select f operator.

### visit {#visit-com.aspose.pdf.operators.FillStroke-}
Visit/select B operator.

### visit {#visit-com.aspose.pdf.operators.GRestore-}
Visit/select Q operator.

### visit {#visit-com.aspose.pdf.operators.GS-}
Visit/select gs operator.

### visit {#visit-com.aspose.pdf.operators.GSave-}
Visit/select q operator.

### visit {#visit-com.aspose.pdf.operators.ID-}
Visit/select ID operator.

### visit {#visit-com.aspose.pdf.operators.LineTo-}
Visit/select l operator.

### visit {#visit-com.aspose.pdf.operators.MoveTextPosition-}
Visit/select Td operator.

### visit {#visit-com.aspose.pdf.operators.MoveTextPositionSetLeading-}
Visit/select TD operator.

### visit {#visit-com.aspose.pdf.operators.MoveTo-}
Visit/select m operator.

### visit {#visit-com.aspose.pdf.operators.MoveToNextLine-}
Visit/select T* operator.

### visit {#visit-com.aspose.pdf.operators.MoveToNextLineShowText-}
Visit/select ' operator.

### visit {#visit-com.aspose.pdf.operators.MP-}
Visit/select MP operator.

### visit {#visit-com.aspose.pdf.operators.ObsoleteFill-}
Visit/select F operator.

### visit {#visit-com.aspose.pdf.operators.Re-}
Visit/select re operator.

### visit {#visit-com.aspose.pdf.operators.SelectFont-}
Visit/select Tf operator.

### visit {#visit-com.aspose.pdf.operators.SetAdvancedColor-}
Visit/select scn operator.

### visit {#visit-com.aspose.pdf.operators.SetAdvancedColorStroke-}
Visit/select SCN operator.

### visit {#visit-com.aspose.pdf.operators.SetCharacterSpacing-}
Visit/select Tc operator.

### visit {#visit-com.aspose.pdf.operators.SetCharWidth-}
Visit/select d0 operator.

### visit {#visit-com.aspose.pdf.operators.SetCharWidthBoundingBox-}
Visit/select d1 operator.

### visit {#visit-com.aspose.pdf.operators.SetCMYKColor-}
Visit/select k operator.

### visit {#visit-com.aspose.pdf.operators.SetCMYKColorStroke-}
Visit/select K operator.

### visit {#visit-com.aspose.pdf.operators.SetColor-}
Visit/select sc operator.

### visit {#visit-com.aspose.pdf.operators.SetColorRenderingIntent-}
Visit/select ri operator.

### visit {#visit-com.aspose.pdf.operators.SetColorSpace-}
Visit/select cs operator.

### visit {#visit-com.aspose.pdf.operators.SetColorSpaceStroke-}
Visit/select CS operator.

### visit {#visit-com.aspose.pdf.operators.SetColorStroke-}
Visit/select SC operator.

### visit {#visit-com.aspose.pdf.operators.SetDash-}
Visit/select d operator.

### visit {#visit-com.aspose.pdf.operators.SetFlat-}
Visit/select i operator.

### visit {#visit-com.aspose.pdf.operators.SetGlyphsPositionShowText-}
Visit/select TJ operator.

### visit {#visit-com.aspose.pdf.operators.SetGray-}
Visit/select g operator.

### visit {#visit-com.aspose.pdf.operators.SetGrayStroke-}
Visit/select G operator.

### visit {#visit-com.aspose.pdf.operators.SetHorizontalTextScaling-}
Visit/select Tz operator.

### visit {#visit-com.aspose.pdf.operators.SetLineCap-}
Visit/select J operator.

### visit {#visit-com.aspose.pdf.operators.SetLineJoin-}
Visit/select j operator.

### visit {#visit-com.aspose.pdf.operators.SetLineWidth-}
Visit/select w operator.

### visit {#visit-com.aspose.pdf.operators.SetMiterLimit-}
Visit/select M operator.

### visit {#visit-com.aspose.pdf.operators.SetRGBColor-}
Visit/select rg operator.

### visit {#visit-com.aspose.pdf.operators.SetRGBColorStroke-}
Visit/select RG operator.

### visit {#visit-com.aspose.pdf.operators.SetSpacingMoveToNextLineShowText-}
Visit/select '' operator.

### visit {#visit-com.aspose.pdf.operators.SetTextLeading-}
Visit/select TL operator.

### visit {#visit-com.aspose.pdf.operators.SetTextMatrix-}
Visit/select Tm operator.

### visit {#visit-com.aspose.pdf.operators.SetTextRenderingMode-}
Visit/select Tr operator.

### visit {#visit-com.aspose.pdf.operators.SetTextRise-}
Visit/select Ts operator.

### visit {#visit-com.aspose.pdf.operators.SetWordSpacing-}
Visit/select Tw operator.

### visit {#visit-com.aspose.pdf.operators.ShFill-}
Visit/select sh operator.

### visit {#visit-com.aspose.pdf.operators.ShowText-}
Visit/select Tj operator.

### visit {#visit-com.aspose.pdf.operators.Stroke-}
Visit/select S operator.

### visit {#visit-com.aspose.pdf.operators.TextOperator-}
Visit/select any text operator operator.
