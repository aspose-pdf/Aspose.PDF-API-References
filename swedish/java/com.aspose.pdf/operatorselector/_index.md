---
title: "OperatorSelector"
linktitle: "OperatorSelector"
second_title: "Aspose.PDF för Java API-referens"
description: "Denna klass används för att välja operatörer med Visitor‑mallidé."
type: docs
weight: 3200
url: /sv/java/com.aspose.pdf/operatorselector/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.OperatorSelector

**All Implemented Interfaces:**
IOperatorSelector

```
public final class OperatorSelector extends Object implements IOperatorSelector
```

Denna klass används för att välja operatörer med Visitor‑mallidé.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [OperatorSelector](#OperatorSelector--) | Initierar en ny instans av klassen {@code Selector}. |
| [OperatorSelector](#OperatorSelector-com.aspose.pdf.Operator-) | Initierar en ny instans av klassen {@code Selector}. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getSelected](#getSelected--) | Listan med valda objekt. |
| [visit](#visit-com.aspose.pdf.operators.BDC-) | Besök/välj BDC-operator. |
| [visit](#visit-com.aspose.pdf.operators.BI-) | Besök/välj BI-operator. |
| [visit](#visit-com.aspose.pdf.operators.BMC-) | Besök/välj BMC-operator. |
| [visit](#visit-com.aspose.pdf.operators.BT-) | Besök/välj BT-operator. |
| [visit](#visit-com.aspose.pdf.operators.BX-) | Besök/välj BX-operator. |
| [visit](#visit-com.aspose.pdf.operators.Clip-) | Besök/välj W-operator. |
| [visit](#visit-com.aspose.pdf.operators.ClosePath-) | Besök/välj h-operator. |
| [visit](#visit-com.aspose.pdf.operators.ClosePathEOFillStroke-) | Besök/välj b*-operator. |
| [visit](#visit-com.aspose.pdf.operators.ClosePathFillStroke-) | Besök/välj b-operator. |
| [visit](#visit-com.aspose.pdf.operators.ClosePathStroke-) | Besök/välj s-operator. |
| [visit](#visit-com.aspose.pdf.operators.ConcatenateMatrix-) | Besök/välj cm-operator. |
| [visit](#visit-com.aspose.pdf.operators.CurveTo-) | Besök/välj c-operator. |
| [visit](#visit-com.aspose.pdf.operators.CurveTo1-) | Besök/välj v-operator. |
| [visit](#visit-com.aspose.pdf.operators.CurveTo2-) | Besök/välj y operator. |
| [visit](#visit-com.aspose.pdf.operators.Do-) | Besök/välj Do operator. |
| [visit](#visit-com.aspose.pdf.operators.DP-) | Besök/välj DP operator. |
| [visit](#visit-com.aspose.pdf.operators.EI-) | Besök/välj EI operator. |
| [visit](#visit-com.aspose.pdf.operators.EMC-) | Besök/välj EMC operator. |
| [visit](#visit-com.aspose.pdf.operators.EndPath-) | Besök/välj n operator. |
| [visit](#visit-com.aspose.pdf.operators.EOClip-) | Besök/välj W* operator. |
| [visit](#visit-com.aspose.pdf.operators.EOFill-) | Besök/välj operator f*. |
| [visit](#visit-com.aspose.pdf.operators.EOFillStroke-) | Besök/välj B* operator. |
| [visit](#visit-com.aspose.pdf.operators.ET-) | Besök/välj ET operator. |
| [visit](#visit-com.aspose.pdf.operators.EX-) | Besök/välj EX operator. |
| [visit](#visit-com.aspose.pdf.operators.Fill-) | Besök/välj f operator. |
| [visit](#visit-com.aspose.pdf.operators.FillStroke-) | Besök/välj B operator. |
| [visit](#visit-com.aspose.pdf.operators.GRestore-) | Besök/välj Q operator. |
| [visit](#visit-com.aspose.pdf.operators.GS-) | Besök/välj gs operator. |
| [visit](#visit-com.aspose.pdf.operators.GSave-) | Besök/välj q operator. |
| [visit](#visit-com.aspose.pdf.operators.ID-) | Besök/välj ID operator. |
| [visit](#visit-com.aspose.pdf.operators.LineTo-) | Besök/välj l operator. |
| [visit](#visit-com.aspose.pdf.operators.MoveTextPosition-) | Besök/välj Td operator. |
| [visit](#visit-com.aspose.pdf.operators.MoveTextPositionSetLeading-) | Besök/välj TD operator. |
| [visit](#visit-com.aspose.pdf.operators.MoveTo-) | Besök/välj m operator. |
| [visit](#visit-com.aspose.pdf.operators.MoveToNextLine-) | Besök/välj T* operator. |
| [visit](#visit-com.aspose.pdf.operators.MoveToNextLineShowText-) | Besök/välj ' operator. |
| [visit](#visit-com.aspose.pdf.operators.MP-) | Besök/välj MP operator. |
| [visit](#visit-com.aspose.pdf.operators.ObsoleteFill-) | Besök/välj F operator. |
| [visit](#visit-com.aspose.pdf.operators.Re-) | Besök/välj re-operatorn. |
| [visit](#visit-com.aspose.pdf.operators.SelectFont-) | Besök/välj Tf-operatorn. |
| [visit](#visit-com.aspose.pdf.operators.SetAdvancedColor-) | Besök/välj scn-operatorn. |
| [visit](#visit-com.aspose.pdf.operators.SetAdvancedColorStroke-) | Besök/välj SCN-operatorn. |
| [visit](#visit-com.aspose.pdf.operators.SetCharacterSpacing-) | Besök/välj Tc-operatorn. |
| [visit](#visit-com.aspose.pdf.operators.SetCharWidth-) | Besök/välj d0-operatorn. |
| [visit](#visit-com.aspose.pdf.operators.SetCharWidthBoundingBox-) | Besök/välj d1-operatorn. |
| [visit](#visit-com.aspose.pdf.operators.SetCMYKColor-) | Besök/välj k-operatorn. |
| [visit](#visit-com.aspose.pdf.operators.SetCMYKColorStroke-) | Besök/välj K-operatorn. |
| [visit](#visit-com.aspose.pdf.operators.SetColor-) | Besök/välj sc-operatorn. |
| [visit](#visit-com.aspose.pdf.operators.SetColorRenderingIntent-) | Besök/välj ri-operatorn. |
| [visit](#visit-com.aspose.pdf.operators.SetColorSpace-) | Besök/välj cs-operatorn. |
| [visit](#visit-com.aspose.pdf.operators.SetColorSpaceStroke-) | Besök/välj CS-operatorn. |
| [visit](#visit-com.aspose.pdf.operators.SetColorStroke-) | Besök/välj SC-operatorn. |
| [visit](#visit-com.aspose.pdf.operators.SetDash-) | Besök/välj d-operatorn. |
| [visit](#visit-com.aspose.pdf.operators.SetFlat-) | Besök/välj i-operatorn. |
| [visit](#visit-com.aspose.pdf.operators.SetGlyphsPositionShowText-) | Besök/välj TJ-operatorn. |
| [visit](#visit-com.aspose.pdf.operators.SetGray-) | Besök/välj g-operatorn. |
| [visit](#visit-com.aspose.pdf.operators.SetGrayStroke-) | Besök/välj G-operatorn. |
| [visit](#visit-com.aspose.pdf.operators.SetHorizontalTextScaling-) | Besök/välj Tz-operatorn. |
| [visit](#visit-com.aspose.pdf.operators.SetLineCap-) | Besök/välj J-operatorn. |
| [visit](#visit-com.aspose.pdf.operators.SetLineJoin-) | Besök/välj j-operatorn. |
| [visit](#visit-com.aspose.pdf.operators.SetLineWidth-) | Besök/välj w-operatorn. |
| [visit](#visit-com.aspose.pdf.operators.SetMiterLimit-) | Besök/välj M-operatorn. |
| [visit](#visit-com.aspose.pdf.operators.SetRGBColor-) | Besök/välj rg-operatorn. |
| [visit](#visit-com.aspose.pdf.operators.SetRGBColorStroke-) | Besök/välj RG-operator. |
| [visit](#visit-com.aspose.pdf.operators.SetSpacingMoveToNextLineShowText-) | Besök/välj ''-operator. |
| [visit](#visit-com.aspose.pdf.operators.SetTextLeading-) | Besök/välj TL-operator. |
| [visit](#visit-com.aspose.pdf.operators.SetTextMatrix-) | Besök/välj Tm-operator. |
| [visit](#visit-com.aspose.pdf.operators.SetTextRenderingMode-) | Besök/välj Tr-operator. |
| [visit](#visit-com.aspose.pdf.operators.SetTextRise-) | Besök/välj Ts-operator. |
| [visit](#visit-com.aspose.pdf.operators.SetWordSpacing-) | Besök/välj Tw-operator. |
| [visit](#visit-com.aspose.pdf.operators.ShFill-) | Besök/välj sh-operator. |
| [visit](#visit-com.aspose.pdf.operators.ShowText-) | Besök/välj Tj-operator. |
| [visit](#visit-com.aspose.pdf.operators.Stroke-) | Besök/välj S-operator. |
| [visit](#visit-com.aspose.pdf.operators.TextOperator-) | Besök/välj någon textoperator-operator. |

### OperatorSelector {#OperatorSelector--}
```
public OperatorSelector()
```

Initierar en ny instans av klassen {@code Selector}.

### OperatorSelector {#OperatorSelector-com.aspose.pdf.Operator-}
Initierar en ny instans av klassen {@code Selector}.

### getSelected {#getSelected--}
```
public List < Operator > getSelected()
```

Listan med valda objekt.

**Returns:**
Lista över Operator-instansier

### visit {#visit-com.aspose.pdf.operators.BDC-}
Besök/välj BDC-operator.

### visit {#visit-com.aspose.pdf.operators.BI-}
Besök/välj BI-operator.

### visit {#visit-com.aspose.pdf.operators.BMC-}
Besök/välj BMC-operator.

### visit {#visit-com.aspose.pdf.operators.BT-}
Besök/välj BT-operator.

### visit {#visit-com.aspose.pdf.operators.BX-}
Besök/välj BX-operator.

### visit {#visit-com.aspose.pdf.operators.Clip-}
Besök/välj W-operator.

### visit {#visit-com.aspose.pdf.operators.ClosePath-}
Besök/välj h-operator.

### visit {#visit-com.aspose.pdf.operators.ClosePathEOFillStroke-}
Besök/välj b*-operator.

### visit {#visit-com.aspose.pdf.operators.ClosePathFillStroke-}
Besök/välj b-operator.

### visit {#visit-com.aspose.pdf.operators.ClosePathStroke-}
Besök/välj s-operator.

### visit {#visit-com.aspose.pdf.operators.ConcatenateMatrix-}
Besök/välj cm-operator.

### visit {#visit-com.aspose.pdf.operators.CurveTo-}
Besök/välj c-operator.

### visit {#visit-com.aspose.pdf.operators.CurveTo1-}
Besök/välj v-operator.

### visit {#visit-com.aspose.pdf.operators.CurveTo2-}
Besök/välj y operator.

### visit {#visit-com.aspose.pdf.operators.Do-}
Besök/välj Do operator.

### visit {#visit-com.aspose.pdf.operators.DP-}
Besök/välj DP operator.

### visit {#visit-com.aspose.pdf.operators.EI-}
Besök/välj EI operator.

### visit {#visit-com.aspose.pdf.operators.EMC-}
Besök/välj EMC operator.

### visit {#visit-com.aspose.pdf.operators.EndPath-}
Besök/välj n operator.

### visit {#visit-com.aspose.pdf.operators.EOClip-}
Besök/välj W* operator.

### visit {#visit-com.aspose.pdf.operators.EOFill-}
Besök/välj operator f*.

### visit {#visit-com.aspose.pdf.operators.EOFillStroke-}
Besök/välj B* operator.

### visit {#visit-com.aspose.pdf.operators.ET-}
Besök/välj ET operator.

### visit {#visit-com.aspose.pdf.operators.EX-}
Besök/välj EX operator.

### visit {#visit-com.aspose.pdf.operators.Fill-}
Besök/välj f operator.

### visit {#visit-com.aspose.pdf.operators.FillStroke-}
Besök/välj B operator.

### visit {#visit-com.aspose.pdf.operators.GRestore-}
Besök/välj Q operator.

### visit {#visit-com.aspose.pdf.operators.GS-}
Besök/välj gs operator.

### visit {#visit-com.aspose.pdf.operators.GSave-}
Besök/välj q operator.

### visit {#visit-com.aspose.pdf.operators.ID-}
Besök/välj ID operator.

### visit {#visit-com.aspose.pdf.operators.LineTo-}
Besök/välj l operator.

### visit {#visit-com.aspose.pdf.operators.MoveTextPosition-}
Besök/välj Td operator.

### visit {#visit-com.aspose.pdf.operators.MoveTextPositionSetLeading-}
Besök/välj TD operator.

### visit {#visit-com.aspose.pdf.operators.MoveTo-}
Besök/välj m operator.

### visit {#visit-com.aspose.pdf.operators.MoveToNextLine-}
Besök/välj T* operator.

### visit {#visit-com.aspose.pdf.operators.MoveToNextLineShowText-}
Besök/välj ' operator.

### visit {#visit-com.aspose.pdf.operators.MP-}
Besök/välj MP operator.

### visit {#visit-com.aspose.pdf.operators.ObsoleteFill-}
Besök/välj F operator.

### visit {#visit-com.aspose.pdf.operators.Re-}
Besök/välj re-operatorn.

### visit {#visit-com.aspose.pdf.operators.SelectFont-}
Besök/välj Tf-operatorn.

### visit {#visit-com.aspose.pdf.operators.SetAdvancedColor-}
Besök/välj scn-operatorn.

### visit {#visit-com.aspose.pdf.operators.SetAdvancedColorStroke-}
Besök/välj SCN-operatorn.

### visit {#visit-com.aspose.pdf.operators.SetCharacterSpacing-}
Besök/välj Tc-operatorn.

### visit {#visit-com.aspose.pdf.operators.SetCharWidth-}
Besök/välj d0-operatorn.

### visit {#visit-com.aspose.pdf.operators.SetCharWidthBoundingBox-}
Besök/välj d1-operatorn.

### visit {#visit-com.aspose.pdf.operators.SetCMYKColor-}
Besök/välj k-operatorn.

### visit {#visit-com.aspose.pdf.operators.SetCMYKColorStroke-}
Besök/välj K-operatorn.

### visit {#visit-com.aspose.pdf.operators.SetColor-}
Besök/välj sc-operatorn.

### visit {#visit-com.aspose.pdf.operators.SetColorRenderingIntent-}
Besök/välj ri-operatorn.

### visit {#visit-com.aspose.pdf.operators.SetColorSpace-}
Besök/välj cs-operatorn.

### visit {#visit-com.aspose.pdf.operators.SetColorSpaceStroke-}
Besök/välj CS-operatorn.

### visit {#visit-com.aspose.pdf.operators.SetColorStroke-}
Besök/välj SC-operatorn.

### visit {#visit-com.aspose.pdf.operators.SetDash-}
Besök/välj d-operatorn.

### visit {#visit-com.aspose.pdf.operators.SetFlat-}
Besök/välj i-operatorn.

### visit {#visit-com.aspose.pdf.operators.SetGlyphsPositionShowText-}
Besök/välj TJ-operatorn.

### visit {#visit-com.aspose.pdf.operators.SetGray-}
Besök/välj g-operatorn.

### visit {#visit-com.aspose.pdf.operators.SetGrayStroke-}
Besök/välj G-operatorn.

### visit {#visit-com.aspose.pdf.operators.SetHorizontalTextScaling-}
Besök/välj Tz-operatorn.

### visit {#visit-com.aspose.pdf.operators.SetLineCap-}
Besök/välj J-operatorn.

### visit {#visit-com.aspose.pdf.operators.SetLineJoin-}
Besök/välj j-operatorn.

### visit {#visit-com.aspose.pdf.operators.SetLineWidth-}
Besök/välj w-operatorn.

### visit {#visit-com.aspose.pdf.operators.SetMiterLimit-}
Besök/välj M-operatorn.

### visit {#visit-com.aspose.pdf.operators.SetRGBColor-}
Besök/välj rg-operatorn.

### visit {#visit-com.aspose.pdf.operators.SetRGBColorStroke-}
Besök/välj RG-operator.

### visit {#visit-com.aspose.pdf.operators.SetSpacingMoveToNextLineShowText-}
Besök/välj ''-operator.

### visit {#visit-com.aspose.pdf.operators.SetTextLeading-}
Besök/välj TL-operator.

### visit {#visit-com.aspose.pdf.operators.SetTextMatrix-}
Besök/välj Tm-operator.

### visit {#visit-com.aspose.pdf.operators.SetTextRenderingMode-}
Besök/välj Tr-operator.

### visit {#visit-com.aspose.pdf.operators.SetTextRise-}
Besök/välj Ts-operator.

### visit {#visit-com.aspose.pdf.operators.SetWordSpacing-}
Besök/välj Tw-operator.

### visit {#visit-com.aspose.pdf.operators.ShFill-}
Besök/välj sh-operator.

### visit {#visit-com.aspose.pdf.operators.ShowText-}
Besök/välj Tj-operator.

### visit {#visit-com.aspose.pdf.operators.Stroke-}
Besök/välj S-operator.

### visit {#visit-com.aspose.pdf.operators.TextOperator-}
Besök/välj någon textoperator-operator.
