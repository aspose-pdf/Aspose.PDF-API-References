---
title: "OperatorSelector"
linktitle: "OperatorSelector"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Diese Klasse wird verwendet, um Operatoren anhand der Visitor-Vorlagenidee auszuwählen."
type: docs
weight: 3200
url: /de/java/com.aspose.pdf/operatorselector/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.OperatorSelector

**All Implemented Interfaces:**
IOperatorSelector

```
public final class OperatorSelector extends Object implements IOperatorSelector
```

Diese Klasse wird verwendet, um Operatoren anhand der Visitor-Vorlagenidee auszuwählen.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [OperatorSelector](#OperatorSelector--) | Initialisiert eine neue Instanz der {@code Selector}-Klasse. |
| [OperatorSelector](#OperatorSelector-com.aspose.pdf.Operator-) | Initialisiert eine neue Instanz der {@code Selector}-Klasse. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getSelected](#getSelected--) | Die Liste der ausgewählten Objekte. |
| [visit](#visit-com.aspose.pdf.operators.BDC-) | Visit/select BDC-Operator. |
| [visit](#visit-com.aspose.pdf.operators.BI-) | Visit/select BI-Operator. |
| [visit](#visit-com.aspose.pdf.operators.BMC-) | Visit/select BMC-Operator. |
| [visit](#visit-com.aspose.pdf.operators.BT-) | Visit/select BT-Operator. |
| [visit](#visit-com.aspose.pdf.operators.BX-) | Visit/select BX-Operator. |
| [visit](#visit-com.aspose.pdf.operators.Clip-) | Visit/select W-Operator. |
| [visit](#visit-com.aspose.pdf.operators.ClosePath-) | Visit/select h-Operator. |
| [visit](#visit-com.aspose.pdf.operators.ClosePathEOFillStroke-) | Visit/select b*-Operator. |
| [visit](#visit-com.aspose.pdf.operators.ClosePathFillStroke-) | Visit/select b-Operator. |
| [visit](#visit-com.aspose.pdf.operators.ClosePathStroke-) | Visit/select s-Operator. |
| [visit](#visit-com.aspose.pdf.operators.ConcatenateMatrix-) | Besuchen/Auswählen cm Operator. |
| [visit](#visit-com.aspose.pdf.operators.CurveTo-) | Besuchen/Auswählen c Operator. |
| [visit](#visit-com.aspose.pdf.operators.CurveTo1-) | Besuchen/Auswählen v Operator. |
| [visit](#visit-com.aspose.pdf.operators.CurveTo2-) | Besuchen/Auswählen y Operator. |
| [visit](#visit-com.aspose.pdf.operators.Do-) | Besuchen/Auswählen Do Operator. |
| [visit](#visit-com.aspose.pdf.operators.DP-) | Besuchen/Auswählen DP Operator. |
| [visit](#visit-com.aspose.pdf.operators.EI-) | Besuchen/Auswählen EI Operator. |
| [visit](#visit-com.aspose.pdf.operators.EMC-) | Besuchen/Auswählen EMC Operator. |
| [visit](#visit-com.aspose.pdf.operators.EndPath-) | Besuchen/Auswählen n Operator. |
| [visit](#visit-com.aspose.pdf.operators.EOClip-) | Besuchen/Auswählen W* Operator. |
| [visit](#visit-com.aspose.pdf.operators.EOFill-) | Besuchen/Auswählen f* Operator. |
| [visit](#visit-com.aspose.pdf.operators.EOFillStroke-) | Besuchen/Auswählen B* Operator. |
| [visit](#visit-com.aspose.pdf.operators.ET-) | Besuchen/Auswählen ET Operator. |
| [visit](#visit-com.aspose.pdf.operators.EX-) | Besuchen/Auswählen EX Operator. |
| [visit](#visit-com.aspose.pdf.operators.Fill-) | Besuchen/Auswählen f Operator. |
| [visit](#visit-com.aspose.pdf.operators.FillStroke-) | Besuchen/Auswählen B Operator. |
| [visit](#visit-com.aspose.pdf.operators.GRestore-) | Besuchen/Auswählen Q Operator. |
| [visit](#visit-com.aspose.pdf.operators.GS-) | Besuchen/Auswählen gs Operator. |
| [visit](#visit-com.aspose.pdf.operators.GSave-) | Besuchen/Auswählen q Operator. |
| [visit](#visit-com.aspose.pdf.operators.ID-) | Besuchen/Auswählen ID Operator. |
| [visit](#visit-com.aspose.pdf.operators.LineTo-) | Besuchen/Auswählen l Operator. |
| [visit](#visit-com.aspose.pdf.operators.MoveTextPosition-) | Besuchen/Auswählen Td Operator. |
| [visit](#visit-com.aspose.pdf.operators.MoveTextPositionSetLeading-) | Besuchen/Auswählen TD Operator. |
| [visit](#visit-com.aspose.pdf.operators.MoveTo-) | Besuchen/Auswählen m Operator. |
| [visit](#visit-com.aspose.pdf.operators.MoveToNextLine-) | Besuchen/Auswählen T* Operator. |
| [visit](#visit-com.aspose.pdf.operators.MoveToNextLineShowText-) | Besuchen/Auswählen ' operator. |
| [visit](#visit-com.aspose.pdf.operators.MP-) | Besuchen/Auswählen MP operator. |
| [visit](#visit-com.aspose.pdf.operators.ObsoleteFill-) | Besuchen/Auswählen F operator. |
| [visit](#visit-com.aspose.pdf.operators.Re-) | Besuchen/Auswählen re operator. |
| [visit](#visit-com.aspose.pdf.operators.SelectFont-) | Besuchen/Auswählen Tf operator. |
| [visit](#visit-com.aspose.pdf.operators.SetAdvancedColor-) | Besuchen/Auswählen scn operator. |
| [visit](#visit-com.aspose.pdf.operators.SetAdvancedColorStroke-) | Besuchen/Auswählen SCN operator. |
| [visit](#visit-com.aspose.pdf.operators.SetCharacterSpacing-) | Besuchen/Auswählen Tc operator. |
| [visit](#visit-com.aspose.pdf.operators.SetCharWidth-) | Besuchen/Auswählen d0 operator. |
| [visit](#visit-com.aspose.pdf.operators.SetCharWidthBoundingBox-) | Besuchen/Auswählen d1 operator. |
| [visit](#visit-com.aspose.pdf.operators.SetCMYKColor-) | Besuchen/Auswählen k operator. |
| [visit](#visit-com.aspose.pdf.operators.SetCMYKColorStroke-) | Besuchen/Auswählen K operator. |
| [visit](#visit-com.aspose.pdf.operators.SetColor-) | Besuchen/Auswählen sc operator. |
| [visit](#visit-com.aspose.pdf.operators.SetColorRenderingIntent-) | Besuchen/Auswählen ri operator. |
| [visit](#visit-com.aspose.pdf.operators.SetColorSpace-) | Besuchen/Auswählen cs operator. |
| [visit](#visit-com.aspose.pdf.operators.SetColorSpaceStroke-) | Besuchen/Auswählen CS operator. |
| [visit](#visit-com.aspose.pdf.operators.SetColorStroke-) | Besuchen/Auswählen SC operator. |
| [visit](#visit-com.aspose.pdf.operators.SetDash-) | Besuchen/Auswählen d operator. |
| [visit](#visit-com.aspose.pdf.operators.SetFlat-) | Besuchen/Auswählen i operator. |
| [visit](#visit-com.aspose.pdf.operators.SetGlyphsPositionShowText-) | Besuchen/Auswählen TJ operator. |
| [visit](#visit-com.aspose.pdf.operators.SetGray-) | Besuchen/Auswählen g operator. |
| [visit](#visit-com.aspose.pdf.operators.SetGrayStroke-) | Besuchen/Auswählen G operator. |
| [visit](#visit-com.aspose.pdf.operators.SetHorizontalTextScaling-) | Besuchen/Auswählen Tz operator. |
| [visit](#visit-com.aspose.pdf.operators.SetLineCap-) | Besuchen/Auswählen J operator. |
| [visit](#visit-com.aspose.pdf.operators.SetLineJoin-) | Besuchen/Auswählen j operator. |
| [visit](#visit-com.aspose.pdf.operators.SetLineWidth-) | Besuchen/Auswählen w-Operator. |
| [visit](#visit-com.aspose.pdf.operators.SetMiterLimit-) | Besuchen/Auswählen M-Operator. |
| [visit](#visit-com.aspose.pdf.operators.SetRGBColor-) | Besuchen/Auswählen rg-Operator. |
| [visit](#visit-com.aspose.pdf.operators.SetRGBColorStroke-) | Besuchen/Auswählen RG-Operator. |
| [visit](#visit-com.aspose.pdf.operators.SetSpacingMoveToNextLineShowText-) | Besuchen/Auswählen ''-Operator. |
| [visit](#visit-com.aspose.pdf.operators.SetTextLeading-) | Besuchen/Auswählen TL-Operator. |
| [visit](#visit-com.aspose.pdf.operators.SetTextMatrix-) | Besuchen/Auswählen Tm-Operator. |
| [visit](#visit-com.aspose.pdf.operators.SetTextRenderingMode-) | Besuchen/Auswählen Tr-Operator. |
| [visit](#visit-com.aspose.pdf.operators.SetTextRise-) | Besuchen/Auswählen Ts-Operator. |
| [visit](#visit-com.aspose.pdf.operators.SetWordSpacing-) | Besuchen/Auswählen Tw-Operator. |
| [visit](#visit-com.aspose.pdf.operators.ShFill-) | Besuchen/Auswählen sh-Operator. |
| [visit](#visit-com.aspose.pdf.operators.ShowText-) | Besuchen/Auswählen Tj-Operator. |
| [visit](#visit-com.aspose.pdf.operators.Stroke-) | Besuchen/Auswählen S-Operator. |
| [visit](#visit-com.aspose.pdf.operators.TextOperator-) | Besuchen/Auswählen beliebiger Text-Operator Operator. |

### OperatorSelector {#OperatorSelector--}
```
public OperatorSelector()
```

Initialisiert eine neue Instanz der {@code Selector}-Klasse.

### OperatorSelector {#OperatorSelector-com.aspose.pdf.Operator-}
Initialisiert eine neue Instanz der {@code Selector}-Klasse.

### getSelected {#getSelected--}
```
public List < Operator > getSelected()
```

Die Liste der ausgewählten Objekte.

**Returns:**
Liste von Operator-Instanzen

### visit {#visit-com.aspose.pdf.operators.BDC-}
Visit/select BDC-Operator.

### visit {#visit-com.aspose.pdf.operators.BI-}
Visit/select BI-Operator.

### visit {#visit-com.aspose.pdf.operators.BMC-}
Visit/select BMC-Operator.

### visit {#visit-com.aspose.pdf.operators.BT-}
Visit/select BT-Operator.

### visit {#visit-com.aspose.pdf.operators.BX-}
Visit/select BX-Operator.

### visit {#visit-com.aspose.pdf.operators.Clip-}
Visit/select W-Operator.

### visit {#visit-com.aspose.pdf.operators.ClosePath-}
Visit/select h-Operator.

### visit {#visit-com.aspose.pdf.operators.ClosePathEOFillStroke-}
Visit/select b*-Operator.

### visit {#visit-com.aspose.pdf.operators.ClosePathFillStroke-}
Visit/select b-Operator.

### visit {#visit-com.aspose.pdf.operators.ClosePathStroke-}
Visit/select s-Operator.

### visit {#visit-com.aspose.pdf.operators.ConcatenateMatrix-}
Besuchen/Auswählen cm Operator.

### visit {#visit-com.aspose.pdf.operators.CurveTo-}
Besuchen/Auswählen c Operator.

### visit {#visit-com.aspose.pdf.operators.CurveTo1-}
Besuchen/Auswählen v Operator.

### visit {#visit-com.aspose.pdf.operators.CurveTo2-}
Besuchen/Auswählen y Operator.

### visit {#visit-com.aspose.pdf.operators.Do-}
Besuchen/Auswählen Do Operator.

### visit {#visit-com.aspose.pdf.operators.DP-}
Besuchen/Auswählen DP Operator.

### visit {#visit-com.aspose.pdf.operators.EI-}
Besuchen/Auswählen EI Operator.

### visit {#visit-com.aspose.pdf.operators.EMC-}
Besuchen/Auswählen EMC Operator.

### visit {#visit-com.aspose.pdf.operators.EndPath-}
Besuchen/Auswählen n Operator.

### visit {#visit-com.aspose.pdf.operators.EOClip-}
Besuchen/Auswählen W* Operator.

### visit {#visit-com.aspose.pdf.operators.EOFill-}
Besuchen/Auswählen f* Operator.

### visit {#visit-com.aspose.pdf.operators.EOFillStroke-}
Besuchen/Auswählen B* Operator.

### visit {#visit-com.aspose.pdf.operators.ET-}
Besuchen/Auswählen ET Operator.

### visit {#visit-com.aspose.pdf.operators.EX-}
Besuchen/Auswählen EX Operator.

### visit {#visit-com.aspose.pdf.operators.Fill-}
Besuchen/Auswählen f Operator.

### visit {#visit-com.aspose.pdf.operators.FillStroke-}
Besuchen/Auswählen B Operator.

### visit {#visit-com.aspose.pdf.operators.GRestore-}
Besuchen/Auswählen Q Operator.

### visit {#visit-com.aspose.pdf.operators.GS-}
Besuchen/Auswählen gs Operator.

### visit {#visit-com.aspose.pdf.operators.GSave-}
Besuchen/Auswählen q Operator.

### visit {#visit-com.aspose.pdf.operators.ID-}
Besuchen/Auswählen ID Operator.

### visit {#visit-com.aspose.pdf.operators.LineTo-}
Besuchen/Auswählen l Operator.

### visit {#visit-com.aspose.pdf.operators.MoveTextPosition-}
Besuchen/Auswählen Td Operator.

### visit {#visit-com.aspose.pdf.operators.MoveTextPositionSetLeading-}
Besuchen/Auswählen TD Operator.

### visit {#visit-com.aspose.pdf.operators.MoveTo-}
Besuchen/Auswählen m Operator.

### visit {#visit-com.aspose.pdf.operators.MoveToNextLine-}
Besuchen/Auswählen T* Operator.

### visit {#visit-com.aspose.pdf.operators.MoveToNextLineShowText-}
Besuchen/Auswählen ' operator.

### visit {#visit-com.aspose.pdf.operators.MP-}
Besuchen/Auswählen MP operator.

### visit {#visit-com.aspose.pdf.operators.ObsoleteFill-}
Besuchen/Auswählen F operator.

### visit {#visit-com.aspose.pdf.operators.Re-}
Besuchen/Auswählen re operator.

### visit {#visit-com.aspose.pdf.operators.SelectFont-}
Besuchen/Auswählen Tf operator.

### visit {#visit-com.aspose.pdf.operators.SetAdvancedColor-}
Besuchen/Auswählen scn operator.

### visit {#visit-com.aspose.pdf.operators.SetAdvancedColorStroke-}
Besuchen/Auswählen SCN operator.

### visit {#visit-com.aspose.pdf.operators.SetCharacterSpacing-}
Besuchen/Auswählen Tc operator.

### visit {#visit-com.aspose.pdf.operators.SetCharWidth-}
Besuchen/Auswählen d0 operator.

### visit {#visit-com.aspose.pdf.operators.SetCharWidthBoundingBox-}
Besuchen/Auswählen d1 operator.

### visit {#visit-com.aspose.pdf.operators.SetCMYKColor-}
Besuchen/Auswählen k operator.

### visit {#visit-com.aspose.pdf.operators.SetCMYKColorStroke-}
Besuchen/Auswählen K operator.

### visit {#visit-com.aspose.pdf.operators.SetColor-}
Besuchen/Auswählen sc operator.

### visit {#visit-com.aspose.pdf.operators.SetColorRenderingIntent-}
Besuchen/Auswählen ri operator.

### visit {#visit-com.aspose.pdf.operators.SetColorSpace-}
Besuchen/Auswählen cs operator.

### visit {#visit-com.aspose.pdf.operators.SetColorSpaceStroke-}
Besuchen/Auswählen CS operator.

### visit {#visit-com.aspose.pdf.operators.SetColorStroke-}
Besuchen/Auswählen SC operator.

### visit {#visit-com.aspose.pdf.operators.SetDash-}
Besuchen/Auswählen d operator.

### visit {#visit-com.aspose.pdf.operators.SetFlat-}
Besuchen/Auswählen i operator.

### visit {#visit-com.aspose.pdf.operators.SetGlyphsPositionShowText-}
Besuchen/Auswählen TJ operator.

### visit {#visit-com.aspose.pdf.operators.SetGray-}
Besuchen/Auswählen g operator.

### visit {#visit-com.aspose.pdf.operators.SetGrayStroke-}
Besuchen/Auswählen G operator.

### visit {#visit-com.aspose.pdf.operators.SetHorizontalTextScaling-}
Besuchen/Auswählen Tz operator.

### visit {#visit-com.aspose.pdf.operators.SetLineCap-}
Besuchen/Auswählen J operator.

### visit {#visit-com.aspose.pdf.operators.SetLineJoin-}
Besuchen/Auswählen j operator.

### visit {#visit-com.aspose.pdf.operators.SetLineWidth-}
Besuchen/Auswählen w-Operator.

### visit {#visit-com.aspose.pdf.operators.SetMiterLimit-}
Besuchen/Auswählen M-Operator.

### visit {#visit-com.aspose.pdf.operators.SetRGBColor-}
Besuchen/Auswählen rg-Operator.

### visit {#visit-com.aspose.pdf.operators.SetRGBColorStroke-}
Besuchen/Auswählen RG-Operator.

### visit {#visit-com.aspose.pdf.operators.SetSpacingMoveToNextLineShowText-}
Besuchen/Auswählen ''-Operator.

### visit {#visit-com.aspose.pdf.operators.SetTextLeading-}
Besuchen/Auswählen TL-Operator.

### visit {#visit-com.aspose.pdf.operators.SetTextMatrix-}
Besuchen/Auswählen Tm-Operator.

### visit {#visit-com.aspose.pdf.operators.SetTextRenderingMode-}
Besuchen/Auswählen Tr-Operator.

### visit {#visit-com.aspose.pdf.operators.SetTextRise-}
Besuchen/Auswählen Ts-Operator.

### visit {#visit-com.aspose.pdf.operators.SetWordSpacing-}
Besuchen/Auswählen Tw-Operator.

### visit {#visit-com.aspose.pdf.operators.ShFill-}
Besuchen/Auswählen sh-Operator.

### visit {#visit-com.aspose.pdf.operators.ShowText-}
Besuchen/Auswählen Tj-Operator.

### visit {#visit-com.aspose.pdf.operators.Stroke-}
Besuchen/Auswählen S-Operator.

### visit {#visit-com.aspose.pdf.operators.TextOperator-}
Besuchen/Auswählen beliebiger Text-Operator Operator.
