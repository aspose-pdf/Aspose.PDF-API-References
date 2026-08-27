---
title: "IOperatorSelector"
linktitle: "IOperatorSelector"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Definisce un Visitor per visitare diversi operatori PDF."
type: docs
weight: 2520
url: /it/java/com.aspose.pdf/ioperatorselector/
---
```
public interface IOperatorSelector
```

Definisce un Visitor per visitare diversi operatori PDF.

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [visit](#visit-com.aspose.pdf.operators.BDC-) | Visita/seleziona l'operatore BDC. |
| [visit](#visit-com.aspose.pdf.operators.BI-) | Visita/seleziona l'operatore BI. |
| [visit](#visit-com.aspose.pdf.operators.BMC-) | Visita/seleziona l'operatore BMC. |
| [visit](#visit-com.aspose.pdf.operators.BT-) | Visita/seleziona l'operatore BT. |
| [visit](#visit-com.aspose.pdf.operators.BX-) | Visita/seleziona l'operatore BX. |
| [visit](#visit-com.aspose.pdf.operators.Clip-) | Visita/seleziona l'operatore W. |
| [visit](#visit-com.aspose.pdf.operators.ClosePath-) | Visita/seleziona l'operatore h. |
| [visit](#visit-com.aspose.pdf.operators.ClosePathEOFillStroke-) | Visita/seleziona l'operatore b*. |
| [visit](#visit-com.aspose.pdf.operators.ClosePathFillStroke-) | Visita/seleziona l'operatore b. |
| [visit](#visit-com.aspose.pdf.operators.ClosePathStroke-) | Visita/seleziona l'operatore s. |
| [visit](#visit-com.aspose.pdf.operators.ConcatenateMatrix-) | Visita/seleziona l'operatore cm. |
| [visit](#visit-com.aspose.pdf.operators.CurveTo-) | Visita/seleziona l'operatore c. |
| [visit](#visit-com.aspose.pdf.operators.CurveTo1-) | Visita/seleziona l'operatore v. |
| [visit](#visit-com.aspose.pdf.operators.CurveTo2-) | Visita/seleziona l'operatore y. |
| [visit](#visit-com.aspose.pdf.operators.Do-) | Visita/seleziona l'operatore Do. |
| [visit](#visit-com.aspose.pdf.operators.DP-) | Visita/seleziona l'operatore DP. |
| [visit](#visit-com.aspose.pdf.operators.EI-) | Visita/seleziona l'operatore EI. |
| [visit](#visit-com.aspose.pdf.operators.EMC-) | Visita/seleziona l'operatore EMC. |
| [visit](#visit-com.aspose.pdf.operators.EndPath-) | Visita/seleziona l'operatore n. |
| [visit](#visit-com.aspose.pdf.operators.EOClip-) | Visita/seleziona l'operatore W*. |
| [visit](#visit-com.aspose.pdf.operators.EOFill-) | Visita/seleziona l'operatore f*. |
| [visit](#visit-com.aspose.pdf.operators.EOFillStroke-) | Visita/seleziona l'operatore B*. |
| [visit](#visit-com.aspose.pdf.operators.ET-) | Visita/seleziona l'operatore ET. |
| [visit](#visit-com.aspose.pdf.operators.EX-) | Visita/seleziona l'operatore EX. |
| [visit](#visit-com.aspose.pdf.operators.Fill-) | Visita/seleziona l'operatore f. |
| [visit](#visit-com.aspose.pdf.operators.FillStroke-) | Visita/seleziona l'operatore B. |
| [visit](#visit-com.aspose.pdf.operators.GRestore-) | Visita/seleziona l'operatore Q. |
| [visit](#visit-com.aspose.pdf.operators.GS-) | Visita/seleziona l'operatore gs. |
| [visit](#visit-com.aspose.pdf.operators.GSave-) | Visita/seleziona l'operatore q. |
| [visit](#visit-com.aspose.pdf.operators.ID-) | Visita/seleziona ID operatore. |
| [visit](#visit-com.aspose.pdf.operators.LineTo-) | Visita/seleziona l operatore. |
| [visit](#visit-com.aspose.pdf.operators.MoveTextPosition-) | Visita/seleziona Td operatore. |
| [visit](#visit-com.aspose.pdf.operators.MoveTextPositionSetLeading-) | Visita/seleziona TD operatore. |
| [visit](#visit-com.aspose.pdf.operators.MoveTo-) | Visita/seleziona m operatore. |
| [visit](#visit-com.aspose.pdf.operators.MoveToNextLine-) | Visita/seleziona T* operatore. |
| [visit](#visit-com.aspose.pdf.operators.MoveToNextLineShowText-) | Visita/seleziona ' operatore. |
| [visit](#visit-com.aspose.pdf.operators.MP-) | Visita/seleziona MP operatore. |
| [visit](#visit-com.aspose.pdf.operators.ObsoleteFill-) | Visita/seleziona F operatore. |
| [visit](#visit-com.aspose.pdf.operators.Re-) | Visita/seleziona re operatore. |
| [visit](#visit-com.aspose.pdf.operators.SelectFont-) | Visita/seleziona Tf operatore. |
| [visit](#visit-com.aspose.pdf.operators.SetAdvancedColor-) | Visita/seleziona scn operatore. |
| [visit](#visit-com.aspose.pdf.operators.SetAdvancedColorStroke-) | Visita/seleziona SCN operatore. |
| [visit](#visit-com.aspose.pdf.operators.SetCharacterSpacing-) | Visita/seleziona Tc operatore. |
| [visit](#visit-com.aspose.pdf.operators.SetCharWidth-) | Visita/seleziona d0 operatore. |
| [visit](#visit-com.aspose.pdf.operators.SetCharWidthBoundingBox-) | Visita/seleziona d1 operatore. |
| [visit](#visit-com.aspose.pdf.operators.SetCMYKColor-) | Visita/seleziona k operatore. |
| [visit](#visit-com.aspose.pdf.operators.SetCMYKColorStroke-) | Visita/seleziona K operatore. |
| [visit](#visit-com.aspose.pdf.operators.SetColor-) | Visita/seleziona sc operatore. |
| [visit](#visit-com.aspose.pdf.operators.SetColorRenderingIntent-) | Visita/seleziona ri operatore. |
| [visit](#visit-com.aspose.pdf.operators.SetColorSpace-) | Visita/seleziona cs operatore. |
| [visit](#visit-com.aspose.pdf.operators.SetColorSpaceStroke-) | Visita/seleziona CS operatore. |
| [visit](#visit-com.aspose.pdf.operators.SetColorStroke-) | Visita/seleziona SC operatore. |
| [visit](#visit-com.aspose.pdf.operators.SetDash-) | Visita/seleziona d operatore. |
| [visit](#visit-com.aspose.pdf.operators.SetFlat-) | Visita/seleziona i operatore. |
| [visit](#visit-com.aspose.pdf.operators.SetGlyphsPositionShowText-) | Visita/seleziona l'operatore TJ. |
| [visit](#visit-com.aspose.pdf.operators.SetGray-) | Visita/seleziona l'operatore g. |
| [visit](#visit-com.aspose.pdf.operators.SetGrayStroke-) | Visita/seleziona l'operatore G. |
| [visit](#visit-com.aspose.pdf.operators.SetHorizontalTextScaling-) | Visita/seleziona l'operatore Tz. |
| [visit](#visit-com.aspose.pdf.operators.SetLineCap-) | Visita/seleziona l'operatore J. |
| [visit](#visit-com.aspose.pdf.operators.SetLineJoin-) | Visita/seleziona l'operatore j. |
| [visit](#visit-com.aspose.pdf.operators.SetLineWidth-) | Visita/seleziona l'operatore w. |
| [visit](#visit-com.aspose.pdf.operators.SetMiterLimit-) | Visita/seleziona l'operatore M. |
| [visit](#visit-com.aspose.pdf.operators.SetRGBColor-) | Visita/seleziona l'operatore rg. |
| [visit](#visit-com.aspose.pdf.operators.SetRGBColorStroke-) | Visita/seleziona l'operatore RG. |
| [visit](#visit-com.aspose.pdf.operators.SetSpacingMoveToNextLineShowText-) | Visita/seleziona l'operatore ''. |
| [visit](#visit-com.aspose.pdf.operators.SetTextLeading-) | Visita/seleziona l'operatore TL. |
| [visit](#visit-com.aspose.pdf.operators.SetTextMatrix-) | Visita/seleziona l'operatore Tm. |
| [visit](#visit-com.aspose.pdf.operators.SetTextRenderingMode-) | Visita/seleziona l'operatore Tr. |
| [visit](#visit-com.aspose.pdf.operators.SetTextRise-) | Visita/seleziona l'operatore Ts. |
| [visit](#visit-com.aspose.pdf.operators.SetWordSpacing-) | Visita/seleziona l'operatore Tw. |
| [visit](#visit-com.aspose.pdf.operators.ShFill-) | Visita/seleziona l'operatore sh. |
| [visit](#visit-com.aspose.pdf.operators.ShowText-) | Visita/seleziona l'operatore Tj. |
| [visit](#visit-com.aspose.pdf.operators.Stroke-) | Visita/seleziona l'operatore S. |
| [visit](#visit-com.aspose.pdf.operators.TextOperator-) | Visita/seleziona qualsiasi operatore di testo. |

### visit {#visit-com.aspose.pdf.operators.BDC-}
Visita/seleziona l'operatore BDC.

### visit {#visit-com.aspose.pdf.operators.BI-}
Visita/seleziona l'operatore BI.

### visit {#visit-com.aspose.pdf.operators.BMC-}
Visita/seleziona l'operatore BMC.

### visit {#visit-com.aspose.pdf.operators.BT-}
Visita/seleziona l'operatore BT.

### visit {#visit-com.aspose.pdf.operators.BX-}
Visita/seleziona l'operatore BX.

### visit {#visit-com.aspose.pdf.operators.Clip-}
Visita/seleziona l'operatore W.

### visit {#visit-com.aspose.pdf.operators.ClosePath-}
Visita/seleziona l'operatore h.

### visit {#visit-com.aspose.pdf.operators.ClosePathEOFillStroke-}
Visita/seleziona l'operatore b*.

### visit {#visit-com.aspose.pdf.operators.ClosePathFillStroke-}
Visita/seleziona l'operatore b.

### visit {#visit-com.aspose.pdf.operators.ClosePathStroke-}
Visita/seleziona l'operatore s.

### visit {#visit-com.aspose.pdf.operators.ConcatenateMatrix-}
Visita/seleziona l'operatore cm.

### visit {#visit-com.aspose.pdf.operators.CurveTo-}
Visita/seleziona l'operatore c.

### visit {#visit-com.aspose.pdf.operators.CurveTo1-}
Visita/seleziona l'operatore v.

### visit {#visit-com.aspose.pdf.operators.CurveTo2-}
Visita/seleziona l'operatore y.

### visit {#visit-com.aspose.pdf.operators.Do-}
Visita/seleziona l'operatore Do.

### visit {#visit-com.aspose.pdf.operators.DP-}
Visita/seleziona l'operatore DP.

### visit {#visit-com.aspose.pdf.operators.EI-}
Visita/seleziona l'operatore EI.

### visit {#visit-com.aspose.pdf.operators.EMC-}
Visita/seleziona l'operatore EMC.

### visit {#visit-com.aspose.pdf.operators.EndPath-}
Visita/seleziona l'operatore n.

### visit {#visit-com.aspose.pdf.operators.EOClip-}
Visita/seleziona l'operatore W*.

### visit {#visit-com.aspose.pdf.operators.EOFill-}
Visita/seleziona l'operatore f*.

### visit {#visit-com.aspose.pdf.operators.EOFillStroke-}
Visita/seleziona l'operatore B*.

### visit {#visit-com.aspose.pdf.operators.ET-}
Visita/seleziona l'operatore ET.

### visit {#visit-com.aspose.pdf.operators.EX-}
Visita/seleziona l'operatore EX.

### visit {#visit-com.aspose.pdf.operators.Fill-}
Visita/seleziona l'operatore f.

### visit {#visit-com.aspose.pdf.operators.FillStroke-}
Visita/seleziona l'operatore B.

### visit {#visit-com.aspose.pdf.operators.GRestore-}
Visita/seleziona l'operatore Q.

### visit {#visit-com.aspose.pdf.operators.GS-}
Visita/seleziona l'operatore gs.

### visit {#visit-com.aspose.pdf.operators.GSave-}
Visita/seleziona l'operatore q.

### visit {#visit-com.aspose.pdf.operators.ID-}
Visita/seleziona ID operatore.

### visit {#visit-com.aspose.pdf.operators.LineTo-}
Visita/seleziona l operatore.

### visit {#visit-com.aspose.pdf.operators.MoveTextPosition-}
Visita/seleziona Td operatore.

### visit {#visit-com.aspose.pdf.operators.MoveTextPositionSetLeading-}
Visita/seleziona TD operatore.

### visit {#visit-com.aspose.pdf.operators.MoveTo-}
Visita/seleziona m operatore.

### visit {#visit-com.aspose.pdf.operators.MoveToNextLine-}
Visita/seleziona T* operatore.

### visit {#visit-com.aspose.pdf.operators.MoveToNextLineShowText-}
Visita/seleziona ' operatore.

### visit {#visit-com.aspose.pdf.operators.MP-}
Visita/seleziona MP operatore.

### visit {#visit-com.aspose.pdf.operators.ObsoleteFill-}
Visita/seleziona F operatore.

### visit {#visit-com.aspose.pdf.operators.Re-}
Visita/seleziona re operatore.

### visit {#visit-com.aspose.pdf.operators.SelectFont-}
Visita/seleziona Tf operatore.

### visit {#visit-com.aspose.pdf.operators.SetAdvancedColor-}
Visita/seleziona scn operatore.

### visit {#visit-com.aspose.pdf.operators.SetAdvancedColorStroke-}
Visita/seleziona SCN operatore.

### visit {#visit-com.aspose.pdf.operators.SetCharacterSpacing-}
Visita/seleziona Tc operatore.

### visit {#visit-com.aspose.pdf.operators.SetCharWidth-}
Visita/seleziona d0 operatore.

### visit {#visit-com.aspose.pdf.operators.SetCharWidthBoundingBox-}
Visita/seleziona d1 operatore.

### visit {#visit-com.aspose.pdf.operators.SetCMYKColor-}
Visita/seleziona k operatore.

### visit {#visit-com.aspose.pdf.operators.SetCMYKColorStroke-}
Visita/seleziona K operatore.

### visit {#visit-com.aspose.pdf.operators.SetColor-}
Visita/seleziona sc operatore.

### visit {#visit-com.aspose.pdf.operators.SetColorRenderingIntent-}
Visita/seleziona ri operatore.

### visit {#visit-com.aspose.pdf.operators.SetColorSpace-}
Visita/seleziona cs operatore.

### visit {#visit-com.aspose.pdf.operators.SetColorSpaceStroke-}
Visita/seleziona CS operatore.

### visit {#visit-com.aspose.pdf.operators.SetColorStroke-}
Visita/seleziona SC operatore.

### visit {#visit-com.aspose.pdf.operators.SetDash-}
Visita/seleziona d operatore.

### visit {#visit-com.aspose.pdf.operators.SetFlat-}
Visita/seleziona i operatore.

### visit {#visit-com.aspose.pdf.operators.SetGlyphsPositionShowText-}
Visita/seleziona l'operatore TJ.

### visit {#visit-com.aspose.pdf.operators.SetGray-}
Visita/seleziona l'operatore g.

### visit {#visit-com.aspose.pdf.operators.SetGrayStroke-}
Visita/seleziona l'operatore G.

### visit {#visit-com.aspose.pdf.operators.SetHorizontalTextScaling-}
Visita/seleziona l'operatore Tz.

### visit {#visit-com.aspose.pdf.operators.SetLineCap-}
Visita/seleziona l'operatore J.

### visit {#visit-com.aspose.pdf.operators.SetLineJoin-}
Visita/seleziona l'operatore j.

### visit {#visit-com.aspose.pdf.operators.SetLineWidth-}
Visita/seleziona l'operatore w.

### visit {#visit-com.aspose.pdf.operators.SetMiterLimit-}
Visita/seleziona l'operatore M.

### visit {#visit-com.aspose.pdf.operators.SetRGBColor-}
Visita/seleziona l'operatore rg.

### visit {#visit-com.aspose.pdf.operators.SetRGBColorStroke-}
Visita/seleziona l'operatore RG.

### visit {#visit-com.aspose.pdf.operators.SetSpacingMoveToNextLineShowText-}
Visita/seleziona l'operatore ''.

### visit {#visit-com.aspose.pdf.operators.SetTextLeading-}
Visita/seleziona l'operatore TL.

### visit {#visit-com.aspose.pdf.operators.SetTextMatrix-}
Visita/seleziona l'operatore Tm.

### visit {#visit-com.aspose.pdf.operators.SetTextRenderingMode-}
Visita/seleziona l'operatore Tr.

### visit {#visit-com.aspose.pdf.operators.SetTextRise-}
Visita/seleziona l'operatore Ts.

### visit {#visit-com.aspose.pdf.operators.SetWordSpacing-}
Visita/seleziona l'operatore Tw.

### visit {#visit-com.aspose.pdf.operators.ShFill-}
Visita/seleziona l'operatore sh.

### visit {#visit-com.aspose.pdf.operators.ShowText-}
Visita/seleziona l'operatore Tj.

### visit {#visit-com.aspose.pdf.operators.Stroke-}
Visita/seleziona l'operatore S.

### visit {#visit-com.aspose.pdf.operators.TextOperator-}
Visita/seleziona qualsiasi operatore di testo.
