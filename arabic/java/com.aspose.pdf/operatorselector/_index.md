---
title: "OperatorSelector"
linktitle: "OperatorSelector"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "تُستخدم هذه الفئة لاختيار المشغلات باستخدام فكرة قالب Visitor."
type: docs
weight: 3200
url: /ar/java/com.aspose.pdf/operatorselector/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.OperatorSelector

**All Implemented Interfaces:**
IOperatorSelector

```
public final class OperatorSelector extends Object implements IOperatorSelector
```

تُستخدم هذه الفئة لاختيار المشغلات باستخدام فكرة قالب Visitor.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [OperatorSelector](#OperatorSelector--) | يُنشئ مثلاً جديداً من الـ {@code Selector} الفئة. |
| [OperatorSelector](#OperatorSelector-com.aspose.pdf.Operator-) | يُنشئ مثلاً جديداً من الـ {@code Selector} الفئة. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getSelected](#getSelected--) | قائمة الكائنات المحددة. |
| [visit](#visit-com.aspose.pdf.operators.BDC-) | زيارة/اختيار عامل BDC. |
| [visit](#visit-com.aspose.pdf.operators.BI-) | زيارة/اختيار عامل BI. |
| [visit](#visit-com.aspose.pdf.operators.BMC-) | زيارة/اختيار عامل BMC. |
| [visit](#visit-com.aspose.pdf.operators.BT-) | زيارة/اختيار عامل BT. |
| [visit](#visit-com.aspose.pdf.operators.BX-) | زيارة/اختيار المشغل BX. |
| [visit](#visit-com.aspose.pdf.operators.Clip-) | زيارة/اختيار المشغل W. |
| [visit](#visit-com.aspose.pdf.operators.ClosePath-) | زيارة/اختيار المشغل h. |
| [visit](#visit-com.aspose.pdf.operators.ClosePathEOFillStroke-) | زيارة/اختيار المشغل b*. |
| [visit](#visit-com.aspose.pdf.operators.ClosePathFillStroke-) | زيارة/اختيار المشغل b. |
| [visit](#visit-com.aspose.pdf.operators.ClosePathStroke-) | زيارة/اختيار المشغل s. |
| [visit](#visit-com.aspose.pdf.operators.ConcatenateMatrix-) | زيارة/اختيار المشغل cm. |
| [visit](#visit-com.aspose.pdf.operators.CurveTo-) | زيارة/اختيار المشغل c. |
| [visit](#visit-com.aspose.pdf.operators.CurveTo1-) | زيارة/اختيار المشغل v. |
| [visit](#visit-com.aspose.pdf.operators.CurveTo2-) | زيارة/اختيار المشغل y. |
| [visit](#visit-com.aspose.pdf.operators.Do-) | زيارة/اختيار المشغل Do. |
| [visit](#visit-com.aspose.pdf.operators.DP-) | زيارة/اختيار المشغل DP. |
| [visit](#visit-com.aspose.pdf.operators.EI-) | زيارة/اختيار المشغل EI. |
| [visit](#visit-com.aspose.pdf.operators.EMC-) | زيارة/اختيار المشغل EMC. |
| [visit](#visit-com.aspose.pdf.operators.EndPath-) | زيارة/اختيار المشغل n. |
| [visit](#visit-com.aspose.pdf.operators.EOClip-) | زيارة/اختيار المشغل W*. |
| [visit](#visit-com.aspose.pdf.operators.EOFill-) | زيارة/اختيار المشغل f*. |
| [visit](#visit-com.aspose.pdf.operators.EOFillStroke-) | زيارة/اختيار المشغل B*. |
| [visit](#visit-com.aspose.pdf.operators.ET-) | زيارة/اختيار المشغل ET. |
| [visit](#visit-com.aspose.pdf.operators.EX-) | زيارة/اختيار المشغل EX. |
| [visit](#visit-com.aspose.pdf.operators.Fill-) | زيارة/اختيار المشغل f. |
| [visit](#visit-com.aspose.pdf.operators.FillStroke-) | زيارة/اختيار المشغل B. |
| [visit](#visit-com.aspose.pdf.operators.GRestore-) | زيارة/اختيار المشغل Q. |
| [visit](#visit-com.aspose.pdf.operators.GS-) | زيارة/اختيار المشغل gs. |
| [visit](#visit-com.aspose.pdf.operators.GSave-) | زيارة/اختيار المشغل q. |
| [visit](#visit-com.aspose.pdf.operators.ID-) | زيارة/اختيار ID المعامل. |
| [visit](#visit-com.aspose.pdf.operators.LineTo-) | زيارة/اختيار l المعامل. |
| [visit](#visit-com.aspose.pdf.operators.MoveTextPosition-) | زيارة/اختيار Td المعامل. |
| [visit](#visit-com.aspose.pdf.operators.MoveTextPositionSetLeading-) | زيارة/اختيار TD المعامل. |
| [visit](#visit-com.aspose.pdf.operators.MoveTo-) | زيارة/اختيار m المعامل. |
| [visit](#visit-com.aspose.pdf.operators.MoveToNextLine-) | زيارة/اختيار T* المعامل. |
| [visit](#visit-com.aspose.pdf.operators.MoveToNextLineShowText-) | زيارة/اختيار ' المعامل. |
| [visit](#visit-com.aspose.pdf.operators.MP-) | زيارة/اختيار MP المعامل. |
| [visit](#visit-com.aspose.pdf.operators.ObsoleteFill-) | زيارة/اختيار F المعامل. |
| [visit](#visit-com.aspose.pdf.operators.Re-) | زيارة/اختيار re المعامل. |
| [visit](#visit-com.aspose.pdf.operators.SelectFont-) | زيارة/اختيار Tf المعامل. |
| [visit](#visit-com.aspose.pdf.operators.SetAdvancedColor-) | زيارة/اختيار scn المعامل. |
| [visit](#visit-com.aspose.pdf.operators.SetAdvancedColorStroke-) | زيارة/اختيار SCN المعامل. |
| [visit](#visit-com.aspose.pdf.operators.SetCharacterSpacing-) | زيارة/اختيار Tc المعامل. |
| [visit](#visit-com.aspose.pdf.operators.SetCharWidth-) | زيارة/اختيار d0 المعامل. |
| [visit](#visit-com.aspose.pdf.operators.SetCharWidthBoundingBox-) | زيارة/اختيار d1 المعامل. |
| [visit](#visit-com.aspose.pdf.operators.SetCMYKColor-) | زيارة/اختيار k المعامل. |
| [visit](#visit-com.aspose.pdf.operators.SetCMYKColorStroke-) | زيارة/اختيار K المعامل. |
| [visit](#visit-com.aspose.pdf.operators.SetColor-) | زيارة/اختيار sc المعامل. |
| [visit](#visit-com.aspose.pdf.operators.SetColorRenderingIntent-) | زيارة/اختيار ri المعامل. |
| [visit](#visit-com.aspose.pdf.operators.SetColorSpace-) | زيارة/اختيار cs المعامل. |
| [visit](#visit-com.aspose.pdf.operators.SetColorSpaceStroke-) | زيارة/اختيار CS المعامل. |
| [visit](#visit-com.aspose.pdf.operators.SetColorStroke-) | زيارة/اختيار SC المعامل. |
| [visit](#visit-com.aspose.pdf.operators.SetDash-) | زيارة/اختيار d المعامل. |
| [visit](#visit-com.aspose.pdf.operators.SetFlat-) | زيارة/اختيار i المعامل. |
| [visit](#visit-com.aspose.pdf.operators.SetGlyphsPositionShowText-) | زيارة/اختيار المشغل TJ. |
| [visit](#visit-com.aspose.pdf.operators.SetGray-) | زيارة/اختيار المشغل g. |
| [visit](#visit-com.aspose.pdf.operators.SetGrayStroke-) | زيارة/اختيار المشغل G. |
| [visit](#visit-com.aspose.pdf.operators.SetHorizontalTextScaling-) | زيارة/اختيار المشغل Tz. |
| [visit](#visit-com.aspose.pdf.operators.SetLineCap-) | زيارة/اختيار المشغل J. |
| [visit](#visit-com.aspose.pdf.operators.SetLineJoin-) | زيارة/اختيار المشغل j. |
| [visit](#visit-com.aspose.pdf.operators.SetLineWidth-) | زيارة/اختيار المشغل w. |
| [visit](#visit-com.aspose.pdf.operators.SetMiterLimit-) | زيارة/اختيار المشغل M. |
| [visit](#visit-com.aspose.pdf.operators.SetRGBColor-) | زيارة/اختيار المشغل rg. |
| [visit](#visit-com.aspose.pdf.operators.SetRGBColorStroke-) | زيارة/اختيار المشغل RG. |
| [visit](#visit-com.aspose.pdf.operators.SetSpacingMoveToNextLineShowText-) | زيارة/اختيار المشغل ''. |
| [visit](#visit-com.aspose.pdf.operators.SetTextLeading-) | زيارة/اختيار المشغل TL. |
| [visit](#visit-com.aspose.pdf.operators.SetTextMatrix-) | زيارة/اختيار المشغل Tm. |
| [visit](#visit-com.aspose.pdf.operators.SetTextRenderingMode-) | زيارة/اختيار المشغل Tr. |
| [visit](#visit-com.aspose.pdf.operators.SetTextRise-) | زيارة/اختيار المشغل Ts. |
| [visit](#visit-com.aspose.pdf.operators.SetWordSpacing-) | زيارة/اختيار المشغل Tw. |
| [visit](#visit-com.aspose.pdf.operators.ShFill-) | زيارة/اختيار المشغل sh. |
| [visit](#visit-com.aspose.pdf.operators.ShowText-) | زيارة/اختيار المشغل Tj. |
| [visit](#visit-com.aspose.pdf.operators.Stroke-) | زيارة/اختيار المشغل S. |
| [visit](#visit-com.aspose.pdf.operators.TextOperator-) | زيارة/اختيار أي مشغل نص مشغل. |

### OperatorSelector {#OperatorSelector--}
```
public OperatorSelector()
```

يُنشئ مثلاً جديداً من الـ {@code Selector} الفئة.

### OperatorSelector {#OperatorSelector-com.aspose.pdf.Operator-}
يُنشئ مثلاً جديداً من الـ {@code Selector} الفئة.

### getSelected {#getSelected--}
```
public List < Operator > getSelected()
```

قائمة الكائنات المحددة.

**Returns:**
قائمة مثيلات المشغل

### visit {#visit-com.aspose.pdf.operators.BDC-}
زيارة/اختيار عامل BDC.

### visit {#visit-com.aspose.pdf.operators.BI-}
زيارة/اختيار عامل BI.

### visit {#visit-com.aspose.pdf.operators.BMC-}
زيارة/اختيار عامل BMC.

### visit {#visit-com.aspose.pdf.operators.BT-}
زيارة/اختيار عامل BT.

### visit {#visit-com.aspose.pdf.operators.BX-}
زيارة/اختيار المشغل BX.

### visit {#visit-com.aspose.pdf.operators.Clip-}
زيارة/اختيار المشغل W.

### visit {#visit-com.aspose.pdf.operators.ClosePath-}
زيارة/اختيار المشغل h.

### visit {#visit-com.aspose.pdf.operators.ClosePathEOFillStroke-}
زيارة/اختيار المشغل b*.

### visit {#visit-com.aspose.pdf.operators.ClosePathFillStroke-}
زيارة/اختيار المشغل b.

### visit {#visit-com.aspose.pdf.operators.ClosePathStroke-}
زيارة/اختيار المشغل s.

### visit {#visit-com.aspose.pdf.operators.ConcatenateMatrix-}
زيارة/اختيار المشغل cm.

### visit {#visit-com.aspose.pdf.operators.CurveTo-}
زيارة/اختيار المشغل c.

### visit {#visit-com.aspose.pdf.operators.CurveTo1-}
زيارة/اختيار المشغل v.

### visit {#visit-com.aspose.pdf.operators.CurveTo2-}
زيارة/اختيار المشغل y.

### visit {#visit-com.aspose.pdf.operators.Do-}
زيارة/اختيار المشغل Do.

### visit {#visit-com.aspose.pdf.operators.DP-}
زيارة/اختيار المشغل DP.

### visit {#visit-com.aspose.pdf.operators.EI-}
زيارة/اختيار المشغل EI.

### visit {#visit-com.aspose.pdf.operators.EMC-}
زيارة/اختيار المشغل EMC.

### visit {#visit-com.aspose.pdf.operators.EndPath-}
زيارة/اختيار المشغل n.

### visit {#visit-com.aspose.pdf.operators.EOClip-}
زيارة/اختيار المشغل W*.

### visit {#visit-com.aspose.pdf.operators.EOFill-}
زيارة/اختيار المشغل f*.

### visit {#visit-com.aspose.pdf.operators.EOFillStroke-}
زيارة/اختيار المشغل B*.

### visit {#visit-com.aspose.pdf.operators.ET-}
زيارة/اختيار المشغل ET.

### visit {#visit-com.aspose.pdf.operators.EX-}
زيارة/اختيار المشغل EX.

### visit {#visit-com.aspose.pdf.operators.Fill-}
زيارة/اختيار المشغل f.

### visit {#visit-com.aspose.pdf.operators.FillStroke-}
زيارة/اختيار المشغل B.

### visit {#visit-com.aspose.pdf.operators.GRestore-}
زيارة/اختيار المشغل Q.

### visit {#visit-com.aspose.pdf.operators.GS-}
زيارة/اختيار المشغل gs.

### visit {#visit-com.aspose.pdf.operators.GSave-}
زيارة/اختيار المشغل q.

### visit {#visit-com.aspose.pdf.operators.ID-}
زيارة/اختيار ID المعامل.

### visit {#visit-com.aspose.pdf.operators.LineTo-}
زيارة/اختيار l المعامل.

### visit {#visit-com.aspose.pdf.operators.MoveTextPosition-}
زيارة/اختيار Td المعامل.

### visit {#visit-com.aspose.pdf.operators.MoveTextPositionSetLeading-}
زيارة/اختيار TD المعامل.

### visit {#visit-com.aspose.pdf.operators.MoveTo-}
زيارة/اختيار m المعامل.

### visit {#visit-com.aspose.pdf.operators.MoveToNextLine-}
زيارة/اختيار T* المعامل.

### visit {#visit-com.aspose.pdf.operators.MoveToNextLineShowText-}
زيارة/اختيار ' المعامل.

### visit {#visit-com.aspose.pdf.operators.MP-}
زيارة/اختيار MP المعامل.

### visit {#visit-com.aspose.pdf.operators.ObsoleteFill-}
زيارة/اختيار F المعامل.

### visit {#visit-com.aspose.pdf.operators.Re-}
زيارة/اختيار re المعامل.

### visit {#visit-com.aspose.pdf.operators.SelectFont-}
زيارة/اختيار Tf المعامل.

### visit {#visit-com.aspose.pdf.operators.SetAdvancedColor-}
زيارة/اختيار scn المعامل.

### visit {#visit-com.aspose.pdf.operators.SetAdvancedColorStroke-}
زيارة/اختيار SCN المعامل.

### visit {#visit-com.aspose.pdf.operators.SetCharacterSpacing-}
زيارة/اختيار Tc المعامل.

### visit {#visit-com.aspose.pdf.operators.SetCharWidth-}
زيارة/اختيار d0 المعامل.

### visit {#visit-com.aspose.pdf.operators.SetCharWidthBoundingBox-}
زيارة/اختيار d1 المعامل.

### visit {#visit-com.aspose.pdf.operators.SetCMYKColor-}
زيارة/اختيار k المعامل.

### visit {#visit-com.aspose.pdf.operators.SetCMYKColorStroke-}
زيارة/اختيار K المعامل.

### visit {#visit-com.aspose.pdf.operators.SetColor-}
زيارة/اختيار sc المعامل.

### visit {#visit-com.aspose.pdf.operators.SetColorRenderingIntent-}
زيارة/اختيار ri المعامل.

### visit {#visit-com.aspose.pdf.operators.SetColorSpace-}
زيارة/اختيار cs المعامل.

### visit {#visit-com.aspose.pdf.operators.SetColorSpaceStroke-}
زيارة/اختيار CS المعامل.

### visit {#visit-com.aspose.pdf.operators.SetColorStroke-}
زيارة/اختيار SC المعامل.

### visit {#visit-com.aspose.pdf.operators.SetDash-}
زيارة/اختيار d المعامل.

### visit {#visit-com.aspose.pdf.operators.SetFlat-}
زيارة/اختيار i المعامل.

### visit {#visit-com.aspose.pdf.operators.SetGlyphsPositionShowText-}
زيارة/اختيار المشغل TJ.

### visit {#visit-com.aspose.pdf.operators.SetGray-}
زيارة/اختيار المشغل g.

### visit {#visit-com.aspose.pdf.operators.SetGrayStroke-}
زيارة/اختيار المشغل G.

### visit {#visit-com.aspose.pdf.operators.SetHorizontalTextScaling-}
زيارة/اختيار المشغل Tz.

### visit {#visit-com.aspose.pdf.operators.SetLineCap-}
زيارة/اختيار المشغل J.

### visit {#visit-com.aspose.pdf.operators.SetLineJoin-}
زيارة/اختيار المشغل j.

### visit {#visit-com.aspose.pdf.operators.SetLineWidth-}
زيارة/اختيار المشغل w.

### visit {#visit-com.aspose.pdf.operators.SetMiterLimit-}
زيارة/اختيار المشغل M.

### visit {#visit-com.aspose.pdf.operators.SetRGBColor-}
زيارة/اختيار المشغل rg.

### visit {#visit-com.aspose.pdf.operators.SetRGBColorStroke-}
زيارة/اختيار المشغل RG.

### visit {#visit-com.aspose.pdf.operators.SetSpacingMoveToNextLineShowText-}
زيارة/اختيار المشغل ''.

### visit {#visit-com.aspose.pdf.operators.SetTextLeading-}
زيارة/اختيار المشغل TL.

### visit {#visit-com.aspose.pdf.operators.SetTextMatrix-}
زيارة/اختيار المشغل Tm.

### visit {#visit-com.aspose.pdf.operators.SetTextRenderingMode-}
زيارة/اختيار المشغل Tr.

### visit {#visit-com.aspose.pdf.operators.SetTextRise-}
زيارة/اختيار المشغل Ts.

### visit {#visit-com.aspose.pdf.operators.SetWordSpacing-}
زيارة/اختيار المشغل Tw.

### visit {#visit-com.aspose.pdf.operators.ShFill-}
زيارة/اختيار المشغل sh.

### visit {#visit-com.aspose.pdf.operators.ShowText-}
زيارة/اختيار المشغل Tj.

### visit {#visit-com.aspose.pdf.operators.Stroke-}
زيارة/اختيار المشغل S.

### visit {#visit-com.aspose.pdf.operators.TextOperator-}
زيارة/اختيار أي مشغل نص مشغل.
