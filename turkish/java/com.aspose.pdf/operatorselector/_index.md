---
title: "OperatorSelector"
linktitle: "OperatorSelector"
second_title: "Aspose.PDF for Java API Referansı"
description: "Bu sınıf, Visitor şablon fikri kullanılarak operatörleri seçmek için kullanılır."
type: docs
weight: 3200
url: /tr/java/com.aspose.pdf/operatorselector/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.OperatorSelector

**All Implemented Interfaces:**
IOperatorSelector

```
public final class OperatorSelector extends Object implements IOperatorSelector
```

Bu sınıf, Visitor şablon fikri kullanılarak operatörleri seçmek için kullanılır.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [OperatorSelector](#OperatorSelector--) | Yeni bir {@code Selector} sınıfı örneği oluşturur. |
| [OperatorSelector](#OperatorSelector-com.aspose.pdf.Operator-) | Yeni bir {@code Selector} sınıfı örneği oluşturur. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getSelected](#getSelected--) | Seçilen nesnelerin listesi. |
| [visit](#visit-com.aspose.pdf.operators.BDC-) | BDC operatörünü ziyaret/ seç. |
| [visit](#visit-com.aspose.pdf.operators.BI-) | BI operatörünü ziyaret/ seç. |
| [visit](#visit-com.aspose.pdf.operators.BMC-) | BMC operatörünü ziyaret/ seç. |
| [visit](#visit-com.aspose.pdf.operators.BT-) | BT operatörünü ziyaret/ seç. |
| [visit](#visit-com.aspose.pdf.operators.BX-) | Ziyaret edin/seç BX operatörü. |
| [visit](#visit-com.aspose.pdf.operators.Clip-) | Ziyaret edin/seç W operatörü. |
| [visit](#visit-com.aspose.pdf.operators.ClosePath-) | Ziyaret edin/seç h operatörü. |
| [visit](#visit-com.aspose.pdf.operators.ClosePathEOFillStroke-) | Ziyaret edin/seç b* operatörü. |
| [visit](#visit-com.aspose.pdf.operators.ClosePathFillStroke-) | Ziyaret edin/seç b operatörü. |
| [visit](#visit-com.aspose.pdf.operators.ClosePathStroke-) | Ziyaret edin/seç s operatörü. |
| [visit](#visit-com.aspose.pdf.operators.ConcatenateMatrix-) | Ziyaret edin/seç cm operatörü. |
| [visit](#visit-com.aspose.pdf.operators.CurveTo-) | Ziyaret edin/seç c operatörü. |
| [visit](#visit-com.aspose.pdf.operators.CurveTo1-) | Ziyaret edin/seç v operatörü. |
| [visit](#visit-com.aspose.pdf.operators.CurveTo2-) | Ziyaret edin/seç y operatörü. |
| [visit](#visit-com.aspose.pdf.operators.Do-) | Ziyaret edin/seç Do operatörü. |
| [visit](#visit-com.aspose.pdf.operators.DP-) | Ziyaret edin/seç DP operatörü. |
| [visit](#visit-com.aspose.pdf.operators.EI-) | Ziyaret edin/seç EI operatörü. |
| [visit](#visit-com.aspose.pdf.operators.EMC-) | Ziyaret edin/seç EMC operatörü. |
| [visit](#visit-com.aspose.pdf.operators.EndPath-) | Ziyaret edin/seç n operatörü. |
| [visit](#visit-com.aspose.pdf.operators.EOClip-) | Ziyaret edin/seç W* operatörü. |
| [visit](#visit-com.aspose.pdf.operators.EOFill-) | Ziyaret edin/seç operatör f*. |
| [visit](#visit-com.aspose.pdf.operators.EOFillStroke-) | Ziyaret edin/seç B* operatörü. |
| [visit](#visit-com.aspose.pdf.operators.ET-) | Ziyaret edin/seç ET operatörü. |
| [visit](#visit-com.aspose.pdf.operators.EX-) | Ziyaret edin/seç EX operatörü. |
| [visit](#visit-com.aspose.pdf.operators.Fill-) | Ziyaret edin/seç f operatörü. |
| [visit](#visit-com.aspose.pdf.operators.FillStroke-) | Ziyaret edin/seç B operatörü. |
| [visit](#visit-com.aspose.pdf.operators.GRestore-) | Ziyaret edin/seç Q operatörü. |
| [visit](#visit-com.aspose.pdf.operators.GS-) | Ziyaret edin/seç gs operatörü. |
| [visit](#visit-com.aspose.pdf.operators.GSave-) | Ziyaret edin/seç q operatörü. |
| [visit](#visit-com.aspose.pdf.operators.ID-) | Ziyaret/seç ID operatörü. |
| [visit](#visit-com.aspose.pdf.operators.LineTo-) | Ziyaret/seç l operatörü. |
| [visit](#visit-com.aspose.pdf.operators.MoveTextPosition-) | Ziyaret/seç Td operatörü. |
| [visit](#visit-com.aspose.pdf.operators.MoveTextPositionSetLeading-) | Ziyaret/seç TD operatörü. |
| [visit](#visit-com.aspose.pdf.operators.MoveTo-) | Ziyaret/seç m operatörü. |
| [visit](#visit-com.aspose.pdf.operators.MoveToNextLine-) | Ziyaret/seç T* operatörü. |
| [visit](#visit-com.aspose.pdf.operators.MoveToNextLineShowText-) | Ziyaret/seç ' operatörü. |
| [visit](#visit-com.aspose.pdf.operators.MP-) | Ziyaret/seç MP operatörü. |
| [visit](#visit-com.aspose.pdf.operators.ObsoleteFill-) | Ziyaret/seç F operatörü. |
| [visit](#visit-com.aspose.pdf.operators.Re-) | Ziyaret/seç re operatörü. |
| [visit](#visit-com.aspose.pdf.operators.SelectFont-) | Ziyaret/seç Tf operatörü. |
| [visit](#visit-com.aspose.pdf.operators.SetAdvancedColor-) | Ziyaret/seç scn operatörü. |
| [visit](#visit-com.aspose.pdf.operators.SetAdvancedColorStroke-) | Ziyaret/seç SCN operatörü. |
| [visit](#visit-com.aspose.pdf.operators.SetCharacterSpacing-) | Ziyaret/seç Tc operatörü. |
| [visit](#visit-com.aspose.pdf.operators.SetCharWidth-) | Ziyaret/seç d0 operatörü. |
| [visit](#visit-com.aspose.pdf.operators.SetCharWidthBoundingBox-) | Ziyaret/seç d1 operatörü. |
| [visit](#visit-com.aspose.pdf.operators.SetCMYKColor-) | Ziyaret/seç k operatörü. |
| [visit](#visit-com.aspose.pdf.operators.SetCMYKColorStroke-) | Ziyaret/seç K operatörü. |
| [visit](#visit-com.aspose.pdf.operators.SetColor-) | Ziyaret/seç sc operatörü. |
| [visit](#visit-com.aspose.pdf.operators.SetColorRenderingIntent-) | Ziyaret/seç ri operatörü. |
| [visit](#visit-com.aspose.pdf.operators.SetColorSpace-) | Ziyaret/seç cs operatörü. |
| [visit](#visit-com.aspose.pdf.operators.SetColorSpaceStroke-) | Ziyaret/seç CS operatörü. |
| [visit](#visit-com.aspose.pdf.operators.SetColorStroke-) | Ziyaret/seç SC operatörü. |
| [visit](#visit-com.aspose.pdf.operators.SetDash-) | Ziyaret/seç d operatörü. |
| [visit](#visit-com.aspose.pdf.operators.SetFlat-) | Ziyaret/seç i operatörü. |
| [visit](#visit-com.aspose.pdf.operators.SetGlyphsPositionShowText-) | Ziyaret et/seç TJ operatörü. |
| [visit](#visit-com.aspose.pdf.operators.SetGray-) | Ziyaret et/seç g operatörü. |
| [visit](#visit-com.aspose.pdf.operators.SetGrayStroke-) | Ziyaret et/seç G operatörü. |
| [visit](#visit-com.aspose.pdf.operators.SetHorizontalTextScaling-) | Ziyaret et/seç Tz operatörü. |
| [visit](#visit-com.aspose.pdf.operators.SetLineCap-) | Ziyaret et/seç J operatörü. |
| [visit](#visit-com.aspose.pdf.operators.SetLineJoin-) | Ziyaret et/seç j operatörü. |
| [visit](#visit-com.aspose.pdf.operators.SetLineWidth-) | Ziyaret et/seç w operatörü. |
| [visit](#visit-com.aspose.pdf.operators.SetMiterLimit-) | Ziyaret et/seç M operatörü. |
| [visit](#visit-com.aspose.pdf.operators.SetRGBColor-) | Ziyaret et/seç rg operatörü. |
| [visit](#visit-com.aspose.pdf.operators.SetRGBColorStroke-) | Ziyaret et/seç RG operatörü. |
| [visit](#visit-com.aspose.pdf.operators.SetSpacingMoveToNextLineShowText-) | Ziyaret et/seç '' operatörü. |
| [visit](#visit-com.aspose.pdf.operators.SetTextLeading-) | Ziyaret et/seç TL operatörü. |
| [visit](#visit-com.aspose.pdf.operators.SetTextMatrix-) | Ziyaret et/seç Tm operatörü. |
| [visit](#visit-com.aspose.pdf.operators.SetTextRenderingMode-) | Ziyaret et/seç Tr operatörü. |
| [visit](#visit-com.aspose.pdf.operators.SetTextRise-) | Ziyaret et/seç Ts operatörü. |
| [visit](#visit-com.aspose.pdf.operators.SetWordSpacing-) | Ziyaret et/seç Tw operatörü. |
| [visit](#visit-com.aspose.pdf.operators.ShFill-) | Ziyaret et/seç sh operatörü. |
| [visit](#visit-com.aspose.pdf.operators.ShowText-) | Ziyaret et/seç Tj operatörü. |
| [visit](#visit-com.aspose.pdf.operators.Stroke-) | Ziyaret et/seç S operatörü. |
| [visit](#visit-com.aspose.pdf.operators.TextOperator-) | Ziyaret et/seç herhangi bir metin operatörü operatörü. |

### OperatorSelector {#OperatorSelector--}
```
public OperatorSelector()
```

Yeni bir {@code Selector} sınıfı örneği oluşturur.

### OperatorSelector {#OperatorSelector-com.aspose.pdf.Operator-}
Yeni bir {@code Selector} sınıfı örneği oluşturur.

### getSelected {#getSelected--}
```
public List < Operator > getSelected()
```

Seçilen nesnelerin listesi.

**Returns:**
Operatör örneklerinin listesi

### visit {#visit-com.aspose.pdf.operators.BDC-}
BDC operatörünü ziyaret/ seç.

### visit {#visit-com.aspose.pdf.operators.BI-}
BI operatörünü ziyaret/ seç.

### visit {#visit-com.aspose.pdf.operators.BMC-}
BMC operatörünü ziyaret/ seç.

### visit {#visit-com.aspose.pdf.operators.BT-}
BT operatörünü ziyaret/ seç.

### visit {#visit-com.aspose.pdf.operators.BX-}
Ziyaret edin/seç BX operatörü.

### visit {#visit-com.aspose.pdf.operators.Clip-}
Ziyaret edin/seç W operatörü.

### visit {#visit-com.aspose.pdf.operators.ClosePath-}
Ziyaret edin/seç h operatörü.

### visit {#visit-com.aspose.pdf.operators.ClosePathEOFillStroke-}
Ziyaret edin/seç b* operatörü.

### visit {#visit-com.aspose.pdf.operators.ClosePathFillStroke-}
Ziyaret edin/seç b operatörü.

### visit {#visit-com.aspose.pdf.operators.ClosePathStroke-}
Ziyaret edin/seç s operatörü.

### visit {#visit-com.aspose.pdf.operators.ConcatenateMatrix-}
Ziyaret edin/seç cm operatörü.

### visit {#visit-com.aspose.pdf.operators.CurveTo-}
Ziyaret edin/seç c operatörü.

### visit {#visit-com.aspose.pdf.operators.CurveTo1-}
Ziyaret edin/seç v operatörü.

### visit {#visit-com.aspose.pdf.operators.CurveTo2-}
Ziyaret edin/seç y operatörü.

### visit {#visit-com.aspose.pdf.operators.Do-}
Ziyaret edin/seç Do operatörü.

### visit {#visit-com.aspose.pdf.operators.DP-}
Ziyaret edin/seç DP operatörü.

### visit {#visit-com.aspose.pdf.operators.EI-}
Ziyaret edin/seç EI operatörü.

### visit {#visit-com.aspose.pdf.operators.EMC-}
Ziyaret edin/seç EMC operatörü.

### visit {#visit-com.aspose.pdf.operators.EndPath-}
Ziyaret edin/seç n operatörü.

### visit {#visit-com.aspose.pdf.operators.EOClip-}
Ziyaret edin/seç W* operatörü.

### visit {#visit-com.aspose.pdf.operators.EOFill-}
Ziyaret edin/seç operatör f*.

### visit {#visit-com.aspose.pdf.operators.EOFillStroke-}
Ziyaret edin/seç B* operatörü.

### visit {#visit-com.aspose.pdf.operators.ET-}
Ziyaret edin/seç ET operatörü.

### visit {#visit-com.aspose.pdf.operators.EX-}
Ziyaret edin/seç EX operatörü.

### visit {#visit-com.aspose.pdf.operators.Fill-}
Ziyaret edin/seç f operatörü.

### visit {#visit-com.aspose.pdf.operators.FillStroke-}
Ziyaret edin/seç B operatörü.

### visit {#visit-com.aspose.pdf.operators.GRestore-}
Ziyaret edin/seç Q operatörü.

### visit {#visit-com.aspose.pdf.operators.GS-}
Ziyaret edin/seç gs operatörü.

### visit {#visit-com.aspose.pdf.operators.GSave-}
Ziyaret edin/seç q operatörü.

### visit {#visit-com.aspose.pdf.operators.ID-}
Ziyaret/seç ID operatörü.

### visit {#visit-com.aspose.pdf.operators.LineTo-}
Ziyaret/seç l operatörü.

### visit {#visit-com.aspose.pdf.operators.MoveTextPosition-}
Ziyaret/seç Td operatörü.

### visit {#visit-com.aspose.pdf.operators.MoveTextPositionSetLeading-}
Ziyaret/seç TD operatörü.

### visit {#visit-com.aspose.pdf.operators.MoveTo-}
Ziyaret/seç m operatörü.

### visit {#visit-com.aspose.pdf.operators.MoveToNextLine-}
Ziyaret/seç T* operatörü.

### visit {#visit-com.aspose.pdf.operators.MoveToNextLineShowText-}
Ziyaret/seç ' operatörü.

### visit {#visit-com.aspose.pdf.operators.MP-}
Ziyaret/seç MP operatörü.

### visit {#visit-com.aspose.pdf.operators.ObsoleteFill-}
Ziyaret/seç F operatörü.

### visit {#visit-com.aspose.pdf.operators.Re-}
Ziyaret/seç re operatörü.

### visit {#visit-com.aspose.pdf.operators.SelectFont-}
Ziyaret/seç Tf operatörü.

### visit {#visit-com.aspose.pdf.operators.SetAdvancedColor-}
Ziyaret/seç scn operatörü.

### visit {#visit-com.aspose.pdf.operators.SetAdvancedColorStroke-}
Ziyaret/seç SCN operatörü.

### visit {#visit-com.aspose.pdf.operators.SetCharacterSpacing-}
Ziyaret/seç Tc operatörü.

### visit {#visit-com.aspose.pdf.operators.SetCharWidth-}
Ziyaret/seç d0 operatörü.

### visit {#visit-com.aspose.pdf.operators.SetCharWidthBoundingBox-}
Ziyaret/seç d1 operatörü.

### visit {#visit-com.aspose.pdf.operators.SetCMYKColor-}
Ziyaret/seç k operatörü.

### visit {#visit-com.aspose.pdf.operators.SetCMYKColorStroke-}
Ziyaret/seç K operatörü.

### visit {#visit-com.aspose.pdf.operators.SetColor-}
Ziyaret/seç sc operatörü.

### visit {#visit-com.aspose.pdf.operators.SetColorRenderingIntent-}
Ziyaret/seç ri operatörü.

### visit {#visit-com.aspose.pdf.operators.SetColorSpace-}
Ziyaret/seç cs operatörü.

### visit {#visit-com.aspose.pdf.operators.SetColorSpaceStroke-}
Ziyaret/seç CS operatörü.

### visit {#visit-com.aspose.pdf.operators.SetColorStroke-}
Ziyaret/seç SC operatörü.

### visit {#visit-com.aspose.pdf.operators.SetDash-}
Ziyaret/seç d operatörü.

### visit {#visit-com.aspose.pdf.operators.SetFlat-}
Ziyaret/seç i operatörü.

### visit {#visit-com.aspose.pdf.operators.SetGlyphsPositionShowText-}
Ziyaret et/seç TJ operatörü.

### visit {#visit-com.aspose.pdf.operators.SetGray-}
Ziyaret et/seç g operatörü.

### visit {#visit-com.aspose.pdf.operators.SetGrayStroke-}
Ziyaret et/seç G operatörü.

### visit {#visit-com.aspose.pdf.operators.SetHorizontalTextScaling-}
Ziyaret et/seç Tz operatörü.

### visit {#visit-com.aspose.pdf.operators.SetLineCap-}
Ziyaret et/seç J operatörü.

### visit {#visit-com.aspose.pdf.operators.SetLineJoin-}
Ziyaret et/seç j operatörü.

### visit {#visit-com.aspose.pdf.operators.SetLineWidth-}
Ziyaret et/seç w operatörü.

### visit {#visit-com.aspose.pdf.operators.SetMiterLimit-}
Ziyaret et/seç M operatörü.

### visit {#visit-com.aspose.pdf.operators.SetRGBColor-}
Ziyaret et/seç rg operatörü.

### visit {#visit-com.aspose.pdf.operators.SetRGBColorStroke-}
Ziyaret et/seç RG operatörü.

### visit {#visit-com.aspose.pdf.operators.SetSpacingMoveToNextLineShowText-}
Ziyaret et/seç '' operatörü.

### visit {#visit-com.aspose.pdf.operators.SetTextLeading-}
Ziyaret et/seç TL operatörü.

### visit {#visit-com.aspose.pdf.operators.SetTextMatrix-}
Ziyaret et/seç Tm operatörü.

### visit {#visit-com.aspose.pdf.operators.SetTextRenderingMode-}
Ziyaret et/seç Tr operatörü.

### visit {#visit-com.aspose.pdf.operators.SetTextRise-}
Ziyaret et/seç Ts operatörü.

### visit {#visit-com.aspose.pdf.operators.SetWordSpacing-}
Ziyaret et/seç Tw operatörü.

### visit {#visit-com.aspose.pdf.operators.ShFill-}
Ziyaret et/seç sh operatörü.

### visit {#visit-com.aspose.pdf.operators.ShowText-}
Ziyaret et/seç Tj operatörü.

### visit {#visit-com.aspose.pdf.operators.Stroke-}
Ziyaret et/seç S operatörü.

### visit {#visit-com.aspose.pdf.operators.TextOperator-}
Ziyaret et/seç herhangi bir metin operatörü operatörü.
