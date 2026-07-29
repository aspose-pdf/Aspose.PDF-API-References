---
title: "OperatorSelector"
linktitle: "OperatorSelector"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Cette classe est utilisée pour sélectionner des opérateurs en utilisant le concept de modèle Visitor."
type: docs
weight: 3200
url: /fr/java/com.aspose.pdf/operatorselector/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.OperatorSelector

**All Implemented Interfaces:**
IOperatorSelector

```
public final class OperatorSelector extends Object implements IOperatorSelector
```

Cette classe est utilisée pour sélectionner des opérateurs en utilisant le concept de modèle Visitor.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [OperatorSelector](#OperatorSelector--) | Initialise une nouvelle instance de la classe {@code Selector}. |
| [OperatorSelector](#OperatorSelector-com.aspose.pdf.Operator-) | Initialise une nouvelle instance de la classe {@code Selector}. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getSelected](#getSelected--) | La liste des objets sélectionnés. |
| [visit](#visit-com.aspose.pdf.operators.BDC-) | Visiter/sélectionner l'opérateur BDC. |
| [visit](#visit-com.aspose.pdf.operators.BI-) | Visiter/sélectionner l'opérateur BI. |
| [visit](#visit-com.aspose.pdf.operators.BMC-) | Visiter/sélectionner l'opérateur BMC. |
| [visit](#visit-com.aspose.pdf.operators.BT-) | Visiter/sélectionner l'opérateur BT. |
| [visit](#visit-com.aspose.pdf.operators.BX-) | Visiter/sélectionner l'opérateur BX. |
| [visit](#visit-com.aspose.pdf.operators.Clip-) | Visiter/sélectionner l'opérateur W. |
| [visit](#visit-com.aspose.pdf.operators.ClosePath-) | Visiter/sélectionner l'opérateur h. |
| [visit](#visit-com.aspose.pdf.operators.ClosePathEOFillStroke-) | Visiter/sélectionner l'opérateur b*. |
| [visit](#visit-com.aspose.pdf.operators.ClosePathFillStroke-) | Visiter/sélectionner l'opérateur b. |
| [visit](#visit-com.aspose.pdf.operators.ClosePathStroke-) | Visiter/sélectionner l'opérateur s. |
| [visit](#visit-com.aspose.pdf.operators.ConcatenateMatrix-) | Visiter/sélectionner l'opérateur cm. |
| [visit](#visit-com.aspose.pdf.operators.CurveTo-) | Visiter/sélectionner l'opérateur c. |
| [visit](#visit-com.aspose.pdf.operators.CurveTo1-) | Visiter/sélectionner l'opérateur v. |
| [visit](#visit-com.aspose.pdf.operators.CurveTo2-) | Visiter/sélectionner l'opérateur y. |
| [visit](#visit-com.aspose.pdf.operators.Do-) | Visiter/sélectionner l'opérateur Do. |
| [visit](#visit-com.aspose.pdf.operators.DP-) | Visiter/sélectionner l'opérateur DP. |
| [visit](#visit-com.aspose.pdf.operators.EI-) | Visiter/sélectionner l'opérateur EI. |
| [visit](#visit-com.aspose.pdf.operators.EMC-) | Visiter/sélectionner l'opérateur EMC. |
| [visit](#visit-com.aspose.pdf.operators.EndPath-) | Visiter/sélectionner l'opérateur n. |
| [visit](#visit-com.aspose.pdf.operators.EOClip-) | Visiter/sélectionner l'opérateur W*. |
| [visit](#visit-com.aspose.pdf.operators.EOFill-) | Visiter/sélectionner l'opérateur f*. |
| [visit](#visit-com.aspose.pdf.operators.EOFillStroke-) | Visiter/sélectionner l'opérateur B*. |
| [visit](#visit-com.aspose.pdf.operators.ET-) | Visiter/sélectionner l'opérateur ET. |
| [visit](#visit-com.aspose.pdf.operators.EX-) | Visiter/sélectionner l'opérateur EX. |
| [visit](#visit-com.aspose.pdf.operators.Fill-) | Visiter/sélectionner l'opérateur f. |
| [visit](#visit-com.aspose.pdf.operators.FillStroke-) | Visiter/sélectionner l'opérateur B. |
| [visit](#visit-com.aspose.pdf.operators.GRestore-) | Visiter/sélectionner l'opérateur Q. |
| [visit](#visit-com.aspose.pdf.operators.GS-) | Visiter/sélectionner l'opérateur gs. |
| [visit](#visit-com.aspose.pdf.operators.GSave-) | Visiter/sélectionner l'opérateur q. |
| [visit](#visit-com.aspose.pdf.operators.ID-) | Visiter/sélectionner l'opérateur ID. |
| [visit](#visit-com.aspose.pdf.operators.LineTo-) | Visiter/sélectionner l'opérateur l. |
| [visit](#visit-com.aspose.pdf.operators.MoveTextPosition-) | Visiter/sélectionner l'opérateur Td. |
| [visit](#visit-com.aspose.pdf.operators.MoveTextPositionSetLeading-) | Visiter/sélectionner l'opérateur TD. |
| [visit](#visit-com.aspose.pdf.operators.MoveTo-) | Visiter/sélectionner l'opérateur m. |
| [visit](#visit-com.aspose.pdf.operators.MoveToNextLine-) | Visiter/sélectionner l'opérateur T*. |
| [visit](#visit-com.aspose.pdf.operators.MoveToNextLineShowText-) | Visiter/sélectionner l'opérateur '. |
| [visit](#visit-com.aspose.pdf.operators.MP-) | Visiter/sélectionner l'opérateur MP. |
| [visit](#visit-com.aspose.pdf.operators.ObsoleteFill-) | Visiter/sélectionner l'opérateur F. |
| [visit](#visit-com.aspose.pdf.operators.Re-) | Visiter/sélectionner l'opérateur re. |
| [visit](#visit-com.aspose.pdf.operators.SelectFont-) | Visiter/sélectionner l'opérateur Tf. |
| [visit](#visit-com.aspose.pdf.operators.SetAdvancedColor-) | Visiter/sélectionner l'opérateur scn. |
| [visit](#visit-com.aspose.pdf.operators.SetAdvancedColorStroke-) | Visiter/sélectionner l'opérateur SCN. |
| [visit](#visit-com.aspose.pdf.operators.SetCharacterSpacing-) | Visiter/sélectionner l'opérateur Tc. |
| [visit](#visit-com.aspose.pdf.operators.SetCharWidth-) | Visiter/sélectionner l'opérateur d0. |
| [visit](#visit-com.aspose.pdf.operators.SetCharWidthBoundingBox-) | Visiter/sélectionner l'opérateur d1. |
| [visit](#visit-com.aspose.pdf.operators.SetCMYKColor-) | Visiter/sélectionner l'opérateur k. |
| [visit](#visit-com.aspose.pdf.operators.SetCMYKColorStroke-) | Visiter/sélectionner l'opérateur K. |
| [visit](#visit-com.aspose.pdf.operators.SetColor-) | Visiter/sélectionner l'opérateur sc. |
| [visit](#visit-com.aspose.pdf.operators.SetColorRenderingIntent-) | Visiter/sélectionner l'opérateur ri. |
| [visit](#visit-com.aspose.pdf.operators.SetColorSpace-) | Visiter/sélectionner l'opérateur cs. |
| [visit](#visit-com.aspose.pdf.operators.SetColorSpaceStroke-) | Visiter/sélectionner l'opérateur CS. |
| [visit](#visit-com.aspose.pdf.operators.SetColorStroke-) | Visiter/sélectionner l'opérateur SC. |
| [visit](#visit-com.aspose.pdf.operators.SetDash-) | Visiter/sélectionner l'opérateur d. |
| [visit](#visit-com.aspose.pdf.operators.SetFlat-) | Visiter/sélectionner l'opérateur i. |
| [visit](#visit-com.aspose.pdf.operators.SetGlyphsPositionShowText-) | Visiter/sélectionner l'opérateur TJ. |
| [visit](#visit-com.aspose.pdf.operators.SetGray-) | Visiter/sélectionner l'opérateur g. |
| [visit](#visit-com.aspose.pdf.operators.SetGrayStroke-) | Visiter/sélectionner l'opérateur G. |
| [visit](#visit-com.aspose.pdf.operators.SetHorizontalTextScaling-) | Visiter/sélectionner l'opérateur Tz. |
| [visit](#visit-com.aspose.pdf.operators.SetLineCap-) | Visiter/sélectionner l'opérateur J. |
| [visit](#visit-com.aspose.pdf.operators.SetLineJoin-) | Visiter/sélectionner l'opérateur j. |
| [visit](#visit-com.aspose.pdf.operators.SetLineWidth-) | Visiter/sélectionner l'opérateur w. |
| [visit](#visit-com.aspose.pdf.operators.SetMiterLimit-) | Visiter/sélectionner l'opérateur M. |
| [visit](#visit-com.aspose.pdf.operators.SetRGBColor-) | Visiter/sélectionner l'opérateur rg. |
| [visit](#visit-com.aspose.pdf.operators.SetRGBColorStroke-) | Visiter/sélectionner l'opérateur RG. |
| [visit](#visit-com.aspose.pdf.operators.SetSpacingMoveToNextLineShowText-) | Visiter/sélectionner l'opérateur ''. |
| [visit](#visit-com.aspose.pdf.operators.SetTextLeading-) | Visiter/sélectionner l'opérateur TL. |
| [visit](#visit-com.aspose.pdf.operators.SetTextMatrix-) | Visiter/sélectionner l'opérateur Tm. |
| [visit](#visit-com.aspose.pdf.operators.SetTextRenderingMode-) | Visiter/sélectionner l'opérateur Tr. |
| [visit](#visit-com.aspose.pdf.operators.SetTextRise-) | Visiter/sélectionner l'opérateur Ts. |
| [visit](#visit-com.aspose.pdf.operators.SetWordSpacing-) | Visiter/sélectionner l'opérateur Tw. |
| [visit](#visit-com.aspose.pdf.operators.ShFill-) | Visiter/sélectionner l'opérateur sh. |
| [visit](#visit-com.aspose.pdf.operators.ShowText-) | Visiter/sélectionner l'opérateur Tj. |
| [visit](#visit-com.aspose.pdf.operators.Stroke-) | Visiter/sélectionner l'opérateur S. |
| [visit](#visit-com.aspose.pdf.operators.TextOperator-) | Visiter/sélectionner tout texte opérateur opérateur. |

### OperatorSelector {#OperatorSelector--}
```
public OperatorSelector()
```

Initialise une nouvelle instance de la classe {@code Selector}.

### OperatorSelector {#OperatorSelector-com.aspose.pdf.Operator-}
Initialise une nouvelle instance de la classe {@code Selector}.

### getSelected {#getSelected--}
```
public List < Operator > getSelected()
```

La liste des objets sélectionnés.

**Returns:**
Liste des instances d'Opérateur

### visit {#visit-com.aspose.pdf.operators.BDC-}
Visiter/sélectionner l'opérateur BDC.

### visit {#visit-com.aspose.pdf.operators.BI-}
Visiter/sélectionner l'opérateur BI.

### visit {#visit-com.aspose.pdf.operators.BMC-}
Visiter/sélectionner l'opérateur BMC.

### visit {#visit-com.aspose.pdf.operators.BT-}
Visiter/sélectionner l'opérateur BT.

### visit {#visit-com.aspose.pdf.operators.BX-}
Visiter/sélectionner l'opérateur BX.

### visit {#visit-com.aspose.pdf.operators.Clip-}
Visiter/sélectionner l'opérateur W.

### visit {#visit-com.aspose.pdf.operators.ClosePath-}
Visiter/sélectionner l'opérateur h.

### visit {#visit-com.aspose.pdf.operators.ClosePathEOFillStroke-}
Visiter/sélectionner l'opérateur b*.

### visit {#visit-com.aspose.pdf.operators.ClosePathFillStroke-}
Visiter/sélectionner l'opérateur b.

### visit {#visit-com.aspose.pdf.operators.ClosePathStroke-}
Visiter/sélectionner l'opérateur s.

### visit {#visit-com.aspose.pdf.operators.ConcatenateMatrix-}
Visiter/sélectionner l'opérateur cm.

### visit {#visit-com.aspose.pdf.operators.CurveTo-}
Visiter/sélectionner l'opérateur c.

### visit {#visit-com.aspose.pdf.operators.CurveTo1-}
Visiter/sélectionner l'opérateur v.

### visit {#visit-com.aspose.pdf.operators.CurveTo2-}
Visiter/sélectionner l'opérateur y.

### visit {#visit-com.aspose.pdf.operators.Do-}
Visiter/sélectionner l'opérateur Do.

### visit {#visit-com.aspose.pdf.operators.DP-}
Visiter/sélectionner l'opérateur DP.

### visit {#visit-com.aspose.pdf.operators.EI-}
Visiter/sélectionner l'opérateur EI.

### visit {#visit-com.aspose.pdf.operators.EMC-}
Visiter/sélectionner l'opérateur EMC.

### visit {#visit-com.aspose.pdf.operators.EndPath-}
Visiter/sélectionner l'opérateur n.

### visit {#visit-com.aspose.pdf.operators.EOClip-}
Visiter/sélectionner l'opérateur W*.

### visit {#visit-com.aspose.pdf.operators.EOFill-}
Visiter/sélectionner l'opérateur f*.

### visit {#visit-com.aspose.pdf.operators.EOFillStroke-}
Visiter/sélectionner l'opérateur B*.

### visit {#visit-com.aspose.pdf.operators.ET-}
Visiter/sélectionner l'opérateur ET.

### visit {#visit-com.aspose.pdf.operators.EX-}
Visiter/sélectionner l'opérateur EX.

### visit {#visit-com.aspose.pdf.operators.Fill-}
Visiter/sélectionner l'opérateur f.

### visit {#visit-com.aspose.pdf.operators.FillStroke-}
Visiter/sélectionner l'opérateur B.

### visit {#visit-com.aspose.pdf.operators.GRestore-}
Visiter/sélectionner l'opérateur Q.

### visit {#visit-com.aspose.pdf.operators.GS-}
Visiter/sélectionner l'opérateur gs.

### visit {#visit-com.aspose.pdf.operators.GSave-}
Visiter/sélectionner l'opérateur q.

### visit {#visit-com.aspose.pdf.operators.ID-}
Visiter/sélectionner l'opérateur ID.

### visit {#visit-com.aspose.pdf.operators.LineTo-}
Visiter/sélectionner l'opérateur l.

### visit {#visit-com.aspose.pdf.operators.MoveTextPosition-}
Visiter/sélectionner l'opérateur Td.

### visit {#visit-com.aspose.pdf.operators.MoveTextPositionSetLeading-}
Visiter/sélectionner l'opérateur TD.

### visit {#visit-com.aspose.pdf.operators.MoveTo-}
Visiter/sélectionner l'opérateur m.

### visit {#visit-com.aspose.pdf.operators.MoveToNextLine-}
Visiter/sélectionner l'opérateur T*.

### visit {#visit-com.aspose.pdf.operators.MoveToNextLineShowText-}
Visiter/sélectionner l'opérateur '.

### visit {#visit-com.aspose.pdf.operators.MP-}
Visiter/sélectionner l'opérateur MP.

### visit {#visit-com.aspose.pdf.operators.ObsoleteFill-}
Visiter/sélectionner l'opérateur F.

### visit {#visit-com.aspose.pdf.operators.Re-}
Visiter/sélectionner l'opérateur re.

### visit {#visit-com.aspose.pdf.operators.SelectFont-}
Visiter/sélectionner l'opérateur Tf.

### visit {#visit-com.aspose.pdf.operators.SetAdvancedColor-}
Visiter/sélectionner l'opérateur scn.

### visit {#visit-com.aspose.pdf.operators.SetAdvancedColorStroke-}
Visiter/sélectionner l'opérateur SCN.

### visit {#visit-com.aspose.pdf.operators.SetCharacterSpacing-}
Visiter/sélectionner l'opérateur Tc.

### visit {#visit-com.aspose.pdf.operators.SetCharWidth-}
Visiter/sélectionner l'opérateur d0.

### visit {#visit-com.aspose.pdf.operators.SetCharWidthBoundingBox-}
Visiter/sélectionner l'opérateur d1.

### visit {#visit-com.aspose.pdf.operators.SetCMYKColor-}
Visiter/sélectionner l'opérateur k.

### visit {#visit-com.aspose.pdf.operators.SetCMYKColorStroke-}
Visiter/sélectionner l'opérateur K.

### visit {#visit-com.aspose.pdf.operators.SetColor-}
Visiter/sélectionner l'opérateur sc.

### visit {#visit-com.aspose.pdf.operators.SetColorRenderingIntent-}
Visiter/sélectionner l'opérateur ri.

### visit {#visit-com.aspose.pdf.operators.SetColorSpace-}
Visiter/sélectionner l'opérateur cs.

### visit {#visit-com.aspose.pdf.operators.SetColorSpaceStroke-}
Visiter/sélectionner l'opérateur CS.

### visit {#visit-com.aspose.pdf.operators.SetColorStroke-}
Visiter/sélectionner l'opérateur SC.

### visit {#visit-com.aspose.pdf.operators.SetDash-}
Visiter/sélectionner l'opérateur d.

### visit {#visit-com.aspose.pdf.operators.SetFlat-}
Visiter/sélectionner l'opérateur i.

### visit {#visit-com.aspose.pdf.operators.SetGlyphsPositionShowText-}
Visiter/sélectionner l'opérateur TJ.

### visit {#visit-com.aspose.pdf.operators.SetGray-}
Visiter/sélectionner l'opérateur g.

### visit {#visit-com.aspose.pdf.operators.SetGrayStroke-}
Visiter/sélectionner l'opérateur G.

### visit {#visit-com.aspose.pdf.operators.SetHorizontalTextScaling-}
Visiter/sélectionner l'opérateur Tz.

### visit {#visit-com.aspose.pdf.operators.SetLineCap-}
Visiter/sélectionner l'opérateur J.

### visit {#visit-com.aspose.pdf.operators.SetLineJoin-}
Visiter/sélectionner l'opérateur j.

### visit {#visit-com.aspose.pdf.operators.SetLineWidth-}
Visiter/sélectionner l'opérateur w.

### visit {#visit-com.aspose.pdf.operators.SetMiterLimit-}
Visiter/sélectionner l'opérateur M.

### visit {#visit-com.aspose.pdf.operators.SetRGBColor-}
Visiter/sélectionner l'opérateur rg.

### visit {#visit-com.aspose.pdf.operators.SetRGBColorStroke-}
Visiter/sélectionner l'opérateur RG.

### visit {#visit-com.aspose.pdf.operators.SetSpacingMoveToNextLineShowText-}
Visiter/sélectionner l'opérateur ''.

### visit {#visit-com.aspose.pdf.operators.SetTextLeading-}
Visiter/sélectionner l'opérateur TL.

### visit {#visit-com.aspose.pdf.operators.SetTextMatrix-}
Visiter/sélectionner l'opérateur Tm.

### visit {#visit-com.aspose.pdf.operators.SetTextRenderingMode-}
Visiter/sélectionner l'opérateur Tr.

### visit {#visit-com.aspose.pdf.operators.SetTextRise-}
Visiter/sélectionner l'opérateur Ts.

### visit {#visit-com.aspose.pdf.operators.SetWordSpacing-}
Visiter/sélectionner l'opérateur Tw.

### visit {#visit-com.aspose.pdf.operators.ShFill-}
Visiter/sélectionner l'opérateur sh.

### visit {#visit-com.aspose.pdf.operators.ShowText-}
Visiter/sélectionner l'opérateur Tj.

### visit {#visit-com.aspose.pdf.operators.Stroke-}
Visiter/sélectionner l'opérateur S.

### visit {#visit-com.aspose.pdf.operators.TextOperator-}
Visiter/sélectionner tout texte opérateur opérateur.
