---
title: "IOperatorSelector"
linktitle: "IOperatorSelector"
second_title: "Referência da API Aspose.PDF para Java"
description: "Define Visitor para visitar diferentes operadores pdf."
type: docs
weight: 2520
url: /pt/java/com.aspose.pdf/ioperatorselector/
---
```
public interface IOperatorSelector
```

Define Visitor para visitar diferentes operadores pdf.

## Métodos

| Método | Descrição |
| --- | --- |
| [visit](#visit-com.aspose.pdf.operators.BDC-) | Visitar/selecionar operador BDC. |
| [visit](#visit-com.aspose.pdf.operators.BI-) | Visitar/selecionar operador BI. |
| [visit](#visit-com.aspose.pdf.operators.BMC-) | Visitar/selecionar operador BMC. |
| [visit](#visit-com.aspose.pdf.operators.BT-) | Visitar/selecionar operador BT. |
| [visit](#visit-com.aspose.pdf.operators.BX-) | Visitar/selecionar operador BX. |
| [visit](#visit-com.aspose.pdf.operators.Clip-) | Visitar/selecionar operador W. |
| [visit](#visit-com.aspose.pdf.operators.ClosePath-) | Visitar/selecionar operador h. |
| [visit](#visit-com.aspose.pdf.operators.ClosePathEOFillStroke-) | Visitar/selecionar operador b*. |
| [visit](#visit-com.aspose.pdf.operators.ClosePathFillStroke-) | Visitar/selecionar operador b. |
| [visit](#visit-com.aspose.pdf.operators.ClosePathStroke-) | Visitar/selecionar operador s. |
| [visit](#visit-com.aspose.pdf.operators.ConcatenateMatrix-) | Visitar/selecionar operador cm. |
| [visit](#visit-com.aspose.pdf.operators.CurveTo-) | Visitar/selecionar operador c. |
| [visit](#visit-com.aspose.pdf.operators.CurveTo1-) | Visitar/selecionar operador v. |
| [visit](#visit-com.aspose.pdf.operators.CurveTo2-) | Visitar/selecionar operador y. |
| [visit](#visit-com.aspose.pdf.operators.Do-) | Visitar/selecionar operador Do. |
| [visit](#visit-com.aspose.pdf.operators.DP-) | Visitar/selecionar operador DP. |
| [visit](#visit-com.aspose.pdf.operators.EI-) | Visitar/selecionar operador EI. |
| [visit](#visit-com.aspose.pdf.operators.EMC-) | Visitar/selecionar operador EMC. |
| [visit](#visit-com.aspose.pdf.operators.EndPath-) | Visitar/selecionar operador n. |
| [visit](#visit-com.aspose.pdf.operators.EOClip-) | Visitar/selecionar operador W*. |
| [visit](#visit-com.aspose.pdf.operators.EOFill-) | Visitar/selecionar operador f*. |
| [visit](#visit-com.aspose.pdf.operators.EOFillStroke-) | Visitar/selecionar operador B*. |
| [visit](#visit-com.aspose.pdf.operators.ET-) | Visitar/selecionar operador ET. |
| [visit](#visit-com.aspose.pdf.operators.EX-) | Visitar/selecionar operador EX. |
| [visit](#visit-com.aspose.pdf.operators.Fill-) | Visitar/selecionar operador f. |
| [visit](#visit-com.aspose.pdf.operators.FillStroke-) | Visitar/selecionar operador B. |
| [visit](#visit-com.aspose.pdf.operators.GRestore-) | Visitar/selecionar operador Q. |
| [visit](#visit-com.aspose.pdf.operators.GS-) | Visitar/selecionar operador gs. |
| [visit](#visit-com.aspose.pdf.operators.GSave-) | Visitar/selecionar operador q. |
| [visit](#visit-com.aspose.pdf.operators.ID-) | Visitar/selecionar ID operador. |
| [visit](#visit-com.aspose.pdf.operators.LineTo-) | Visitar/selecionar l operador. |
| [visit](#visit-com.aspose.pdf.operators.MoveTextPosition-) | Visitar/selecionar Td operador. |
| [visit](#visit-com.aspose.pdf.operators.MoveTextPositionSetLeading-) | Visitar/selecionar TD operador. |
| [visit](#visit-com.aspose.pdf.operators.MoveTo-) | Visitar/selecionar m operador. |
| [visit](#visit-com.aspose.pdf.operators.MoveToNextLine-) | Visitar/selecionar T* operador. |
| [visit](#visit-com.aspose.pdf.operators.MoveToNextLineShowText-) | Visitar/selecionar ' operador. |
| [visit](#visit-com.aspose.pdf.operators.MP-) | Visitar/selecionar MP operador. |
| [visit](#visit-com.aspose.pdf.operators.ObsoleteFill-) | Visitar/selecionar F operador. |
| [visit](#visit-com.aspose.pdf.operators.Re-) | Visitar/selecionar re operador. |
| [visit](#visit-com.aspose.pdf.operators.SelectFont-) | Visitar/selecionar Tf operador. |
| [visit](#visit-com.aspose.pdf.operators.SetAdvancedColor-) | Visitar/selecionar scn operador. |
| [visit](#visit-com.aspose.pdf.operators.SetAdvancedColorStroke-) | Visitar/selecionar SCN operador. |
| [visit](#visit-com.aspose.pdf.operators.SetCharacterSpacing-) | Visitar/selecionar Tc operador. |
| [visit](#visit-com.aspose.pdf.operators.SetCharWidth-) | Visitar/selecionar d0 operador. |
| [visit](#visit-com.aspose.pdf.operators.SetCharWidthBoundingBox-) | Visitar/selecionar d1 operador. |
| [visit](#visit-com.aspose.pdf.operators.SetCMYKColor-) | Visitar/selecionar k operador. |
| [visit](#visit-com.aspose.pdf.operators.SetCMYKColorStroke-) | Visitar/selecionar K operador. |
| [visit](#visit-com.aspose.pdf.operators.SetColor-) | Visitar/selecionar sc operador. |
| [visit](#visit-com.aspose.pdf.operators.SetColorRenderingIntent-) | Visitar/selecionar ri operador. |
| [visit](#visit-com.aspose.pdf.operators.SetColorSpace-) | Visitar/selecionar cs operador. |
| [visit](#visit-com.aspose.pdf.operators.SetColorSpaceStroke-) | Visitar/selecionar CS operador. |
| [visit](#visit-com.aspose.pdf.operators.SetColorStroke-) | Visitar/selecionar SC operador. |
| [visit](#visit-com.aspose.pdf.operators.SetDash-) | Visitar/selecionar d operador. |
| [visit](#visit-com.aspose.pdf.operators.SetFlat-) | Visitar/selecionar i operador. |
| [visit](#visit-com.aspose.pdf.operators.SetGlyphsPositionShowText-) | Visitar/selecionar operador TJ. |
| [visit](#visit-com.aspose.pdf.operators.SetGray-) | Visitar/selecionar operador g. |
| [visit](#visit-com.aspose.pdf.operators.SetGrayStroke-) | Visitar/selecionar operador G. |
| [visit](#visit-com.aspose.pdf.operators.SetHorizontalTextScaling-) | Visitar/selecionar operador Tz. |
| [visit](#visit-com.aspose.pdf.operators.SetLineCap-) | Visitar/selecionar operador J. |
| [visit](#visit-com.aspose.pdf.operators.SetLineJoin-) | Visitar/selecionar operador j. |
| [visit](#visit-com.aspose.pdf.operators.SetLineWidth-) | Visitar/selecionar operador w. |
| [visit](#visit-com.aspose.pdf.operators.SetMiterLimit-) | Visitar/selecionar operador M. |
| [visit](#visit-com.aspose.pdf.operators.SetRGBColor-) | Visitar/selecionar operador rg. |
| [visit](#visit-com.aspose.pdf.operators.SetRGBColorStroke-) | Visitar/selecionar operador RG. |
| [visit](#visit-com.aspose.pdf.operators.SetSpacingMoveToNextLineShowText-) | Visitar/selecionar operador ''. |
| [visit](#visit-com.aspose.pdf.operators.SetTextLeading-) | Visitar/selecionar operador TL. |
| [visit](#visit-com.aspose.pdf.operators.SetTextMatrix-) | Visitar/selecionar operador Tm. |
| [visit](#visit-com.aspose.pdf.operators.SetTextRenderingMode-) | Visitar/selecionar operador Tr. |
| [visit](#visit-com.aspose.pdf.operators.SetTextRise-) | Visitar/selecionar operador Ts. |
| [visit](#visit-com.aspose.pdf.operators.SetWordSpacing-) | Visitar/selecionar operador Tw. |
| [visit](#visit-com.aspose.pdf.operators.ShFill-) | Visitar/selecionar operador sh. |
| [visit](#visit-com.aspose.pdf.operators.ShowText-) | Visitar/selecionar operador Tj. |
| [visit](#visit-com.aspose.pdf.operators.Stroke-) | Visitar/selecionar operador S. |
| [visit](#visit-com.aspose.pdf.operators.TextOperator-) | Visitar/selecionar operador de texto qualquer. |

### visit {#visit-com.aspose.pdf.operators.BDC-}
Visitar/selecionar operador BDC.

### visit {#visit-com.aspose.pdf.operators.BI-}
Visitar/selecionar operador BI.

### visit {#visit-com.aspose.pdf.operators.BMC-}
Visitar/selecionar operador BMC.

### visit {#visit-com.aspose.pdf.operators.BT-}
Visitar/selecionar operador BT.

### visit {#visit-com.aspose.pdf.operators.BX-}
Visitar/selecionar operador BX.

### visit {#visit-com.aspose.pdf.operators.Clip-}
Visitar/selecionar operador W.

### visit {#visit-com.aspose.pdf.operators.ClosePath-}
Visitar/selecionar operador h.

### visit {#visit-com.aspose.pdf.operators.ClosePathEOFillStroke-}
Visitar/selecionar operador b*.

### visit {#visit-com.aspose.pdf.operators.ClosePathFillStroke-}
Visitar/selecionar operador b.

### visit {#visit-com.aspose.pdf.operators.ClosePathStroke-}
Visitar/selecionar operador s.

### visit {#visit-com.aspose.pdf.operators.ConcatenateMatrix-}
Visitar/selecionar operador cm.

### visit {#visit-com.aspose.pdf.operators.CurveTo-}
Visitar/selecionar operador c.

### visit {#visit-com.aspose.pdf.operators.CurveTo1-}
Visitar/selecionar operador v.

### visit {#visit-com.aspose.pdf.operators.CurveTo2-}
Visitar/selecionar operador y.

### visit {#visit-com.aspose.pdf.operators.Do-}
Visitar/selecionar operador Do.

### visit {#visit-com.aspose.pdf.operators.DP-}
Visitar/selecionar operador DP.

### visit {#visit-com.aspose.pdf.operators.EI-}
Visitar/selecionar operador EI.

### visit {#visit-com.aspose.pdf.operators.EMC-}
Visitar/selecionar operador EMC.

### visit {#visit-com.aspose.pdf.operators.EndPath-}
Visitar/selecionar operador n.

### visit {#visit-com.aspose.pdf.operators.EOClip-}
Visitar/selecionar operador W*.

### visit {#visit-com.aspose.pdf.operators.EOFill-}
Visitar/selecionar operador f*.

### visit {#visit-com.aspose.pdf.operators.EOFillStroke-}
Visitar/selecionar operador B*.

### visit {#visit-com.aspose.pdf.operators.ET-}
Visitar/selecionar operador ET.

### visit {#visit-com.aspose.pdf.operators.EX-}
Visitar/selecionar operador EX.

### visit {#visit-com.aspose.pdf.operators.Fill-}
Visitar/selecionar operador f.

### visit {#visit-com.aspose.pdf.operators.FillStroke-}
Visitar/selecionar operador B.

### visit {#visit-com.aspose.pdf.operators.GRestore-}
Visitar/selecionar operador Q.

### visit {#visit-com.aspose.pdf.operators.GS-}
Visitar/selecionar operador gs.

### visit {#visit-com.aspose.pdf.operators.GSave-}
Visitar/selecionar operador q.

### visit {#visit-com.aspose.pdf.operators.ID-}
Visitar/selecionar ID operador.

### visit {#visit-com.aspose.pdf.operators.LineTo-}
Visitar/selecionar l operador.

### visit {#visit-com.aspose.pdf.operators.MoveTextPosition-}
Visitar/selecionar Td operador.

### visit {#visit-com.aspose.pdf.operators.MoveTextPositionSetLeading-}
Visitar/selecionar TD operador.

### visit {#visit-com.aspose.pdf.operators.MoveTo-}
Visitar/selecionar m operador.

### visit {#visit-com.aspose.pdf.operators.MoveToNextLine-}
Visitar/selecionar T* operador.

### visit {#visit-com.aspose.pdf.operators.MoveToNextLineShowText-}
Visitar/selecionar ' operador.

### visit {#visit-com.aspose.pdf.operators.MP-}
Visitar/selecionar MP operador.

### visit {#visit-com.aspose.pdf.operators.ObsoleteFill-}
Visitar/selecionar F operador.

### visit {#visit-com.aspose.pdf.operators.Re-}
Visitar/selecionar re operador.

### visit {#visit-com.aspose.pdf.operators.SelectFont-}
Visitar/selecionar Tf operador.

### visit {#visit-com.aspose.pdf.operators.SetAdvancedColor-}
Visitar/selecionar scn operador.

### visit {#visit-com.aspose.pdf.operators.SetAdvancedColorStroke-}
Visitar/selecionar SCN operador.

### visit {#visit-com.aspose.pdf.operators.SetCharacterSpacing-}
Visitar/selecionar Tc operador.

### visit {#visit-com.aspose.pdf.operators.SetCharWidth-}
Visitar/selecionar d0 operador.

### visit {#visit-com.aspose.pdf.operators.SetCharWidthBoundingBox-}
Visitar/selecionar d1 operador.

### visit {#visit-com.aspose.pdf.operators.SetCMYKColor-}
Visitar/selecionar k operador.

### visit {#visit-com.aspose.pdf.operators.SetCMYKColorStroke-}
Visitar/selecionar K operador.

### visit {#visit-com.aspose.pdf.operators.SetColor-}
Visitar/selecionar sc operador.

### visit {#visit-com.aspose.pdf.operators.SetColorRenderingIntent-}
Visitar/selecionar ri operador.

### visit {#visit-com.aspose.pdf.operators.SetColorSpace-}
Visitar/selecionar cs operador.

### visit {#visit-com.aspose.pdf.operators.SetColorSpaceStroke-}
Visitar/selecionar CS operador.

### visit {#visit-com.aspose.pdf.operators.SetColorStroke-}
Visitar/selecionar SC operador.

### visit {#visit-com.aspose.pdf.operators.SetDash-}
Visitar/selecionar d operador.

### visit {#visit-com.aspose.pdf.operators.SetFlat-}
Visitar/selecionar i operador.

### visit {#visit-com.aspose.pdf.operators.SetGlyphsPositionShowText-}
Visitar/selecionar operador TJ.

### visit {#visit-com.aspose.pdf.operators.SetGray-}
Visitar/selecionar operador g.

### visit {#visit-com.aspose.pdf.operators.SetGrayStroke-}
Visitar/selecionar operador G.

### visit {#visit-com.aspose.pdf.operators.SetHorizontalTextScaling-}
Visitar/selecionar operador Tz.

### visit {#visit-com.aspose.pdf.operators.SetLineCap-}
Visitar/selecionar operador J.

### visit {#visit-com.aspose.pdf.operators.SetLineJoin-}
Visitar/selecionar operador j.

### visit {#visit-com.aspose.pdf.operators.SetLineWidth-}
Visitar/selecionar operador w.

### visit {#visit-com.aspose.pdf.operators.SetMiterLimit-}
Visitar/selecionar operador M.

### visit {#visit-com.aspose.pdf.operators.SetRGBColor-}
Visitar/selecionar operador rg.

### visit {#visit-com.aspose.pdf.operators.SetRGBColorStroke-}
Visitar/selecionar operador RG.

### visit {#visit-com.aspose.pdf.operators.SetSpacingMoveToNextLineShowText-}
Visitar/selecionar operador ''.

### visit {#visit-com.aspose.pdf.operators.SetTextLeading-}
Visitar/selecionar operador TL.

### visit {#visit-com.aspose.pdf.operators.SetTextMatrix-}
Visitar/selecionar operador Tm.

### visit {#visit-com.aspose.pdf.operators.SetTextRenderingMode-}
Visitar/selecionar operador Tr.

### visit {#visit-com.aspose.pdf.operators.SetTextRise-}
Visitar/selecionar operador Ts.

### visit {#visit-com.aspose.pdf.operators.SetWordSpacing-}
Visitar/selecionar operador Tw.

### visit {#visit-com.aspose.pdf.operators.ShFill-}
Visitar/selecionar operador sh.

### visit {#visit-com.aspose.pdf.operators.ShowText-}
Visitar/selecionar operador Tj.

### visit {#visit-com.aspose.pdf.operators.Stroke-}
Visitar/selecionar operador S.

### visit {#visit-com.aspose.pdf.operators.TextOperator-}
Visitar/selecionar operador de texto qualquer.
