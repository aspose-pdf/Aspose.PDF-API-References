---
title: OperatorSelector
second_title: Aspose.PDF for Java API Reference
description: This class is used for selecting operators using Visitor template idea.
type: docs
weight: 188
url: /java/com.aspose.pdf/operatorselector/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Selector](../../com.aspose.pdf/selector)

**All Implemented Interfaces:**
[com.aspose.pdf.IOperatorSelector](../../com.aspose.pdf/ioperatorselector)
```
public final class OperatorSelector extends Selector implements IOperatorSelector
```

This class is used for selecting operators using Visitor template idea.
## Constructors

| Constructor | Description |
| --- | --- |
| [OperatorSelector(Operator op)](#OperatorSelector-com.aspose.pdf.Operator-) | Initializes new  OperatorSelector . |
## Methods

| Method | Description |
| --- | --- |
| [visit(Operator.SetLineJoin j)](#visit-com.aspose.pdf.Operator.SetLineJoin-) | Visit/select j operator. |
| [visit(Operator.EX EX)](#visit-com.aspose.pdf.Operator.EX-) | Visit/select EX operator. |
| [visit(Operator.ET ET)](#visit-com.aspose.pdf.Operator.ET-) | Visit/select ET operator. |
| [visit(Operator.EMC EMC)](#visit-com.aspose.pdf.Operator.EMC-) | Visit/select EMC operator. |
| [visit(Operator.EI EI)](#visit-com.aspose.pdf.Operator.EI-) | Visit/select EI operator. |
| [visit(Operator.DP DP)](#visit-com.aspose.pdf.Operator.DP-) | Visit/select DP operator. |
| [visit(Operator.Do Do)](#visit-com.aspose.pdf.Operator.Do-) | Visit/select Do operator. |
| [visit(Operator.SetCharWidthBoundingBox d1)](#visit-com.aspose.pdf.Operator.SetCharWidthBoundingBox-) | Visit/select d1 operator. |
| [visit(Operator.SetCharWidth d0)](#visit-com.aspose.pdf.Operator.SetCharWidth-) | Visit/select d0 operator. |
| [visit(Operator.SetDash d)](#visit-com.aspose.pdf.Operator.SetDash-) | Visit/select d operator. |
| [visit(Operator.SetColorSpaceStroke CS)](#visit-com.aspose.pdf.Operator.SetColorSpaceStroke-) | Visit/select CS operator. |
| [visit(Operator.SetColorSpace cs)](#visit-com.aspose.pdf.Operator.SetColorSpace-) | Visit/select cs operator. |
| [visit(Operator.ConcatenateMatrix cm)](#visit-com.aspose.pdf.Operator.ConcatenateMatrix-) | Visit/select cm operator. |
| [visit(Operator.CurveTo c)](#visit-com.aspose.pdf.Operator.CurveTo-) | Visit/select c operator. |
| [visit(Operator.BX BX)](#visit-com.aspose.pdf.Operator.BX-) | Visit/select BX operator. |
| [visit(Operator.BT BT)](#visit-com.aspose.pdf.Operator.BT-) | Visit/select BT operator. |
| [visit(Operator.BMC BMC)](#visit-com.aspose.pdf.Operator.BMC-) | Visit/select BMC operator. |
| [visit(Operator.BI BI)](#visit-com.aspose.pdf.Operator.BI-) | Visit/select BI operator. |
| [visit(Operator.BDC BDC)](#visit-com.aspose.pdf.Operator.BDC-) | Visit/select BDC operator. |
| [visit(Operator.FillStroke B)](#visit-com.aspose.pdf.Operator.FillStroke-) | Visit/select B operator. |
| [visit(Operator.ClosePathFillStroke b)](#visit-com.aspose.pdf.Operator.ClosePathFillStroke-) | Visit/select b operator. |
| [visit(Operator.EOFillStroke B_)](#visit-com.aspose.pdf.Operator.EOFillStroke-) | Visit/select B\* operator. |
| [visit(Operator.ClosePathEOFillStroke b_)](#visit-com.aspose.pdf.Operator.ClosePathEOFillStroke-) | Visit/select b\* operator. |
| [visit(Operator.MoveToNextLineShowText nextLineShowText)](#visit-com.aspose.pdf.Operator.MoveToNextLineShowText-) | Visit/select ' operator. |
| [visit(Operator.SetSpacingMoveToNextLineShowText nextLineShowText)](#visit-com.aspose.pdf.Operator.SetSpacingMoveToNextLineShowText-) | Visit/select '' operator. |
| [visit(Operator.EOFill f_)](#visit-com.aspose.pdf.Operator.EOFill-) | Visit/select operator f\*. |
| [visit(BDC BDC)](#visit-com.aspose.pdf.operators.BDC-) | Visit/select BDC operator. |
| [visit(Fill f)](#visit-com.aspose.pdf.operators.Fill-) | Visit/select f operator. |
| [visit(ClosePathStroke s)](#visit-com.aspose.pdf.operators.ClosePathStroke-) | Visit/select s operator. |
| [visit(Stroke S)](#visit-com.aspose.pdf.operators.Stroke-) | Visit/select S operator. |
| [visit(Operator.Fill f)](#visit-com.aspose.pdf.Operator.Fill-) | Visit/select f operator. |
| [visit(Operator.ObsoleteFill F)](#visit-com.aspose.pdf.Operator.ObsoleteFill-) | Visit/select F operator. |
| [visit(Operator.SetGray g)](#visit-com.aspose.pdf.Operator.SetGray-) | Visit/select g operator. |
| [visit(Operator.SetGrayStroke G)](#visit-com.aspose.pdf.Operator.SetGrayStroke-) | Visit/select G operator. |
| [visit(Operator.GS gs)](#visit-com.aspose.pdf.Operator.GS-) | Visit/select gs operator. |
| [visit(Operator.ClosePath h)](#visit-com.aspose.pdf.Operator.ClosePath-) | Visit/select h operator. |
| [visit(Operator.SetFlat i)](#visit-com.aspose.pdf.Operator.SetFlat-) | Visit/select i operator. |
| [visit(Operator.ID ID)](#visit-com.aspose.pdf.Operator.ID-) | Visit/select ID operator. |
| [visit(Operator.SetLineCap J)](#visit-com.aspose.pdf.Operator.SetLineCap-) | Visit/select J operator. |
| [visit(Operator.SetCMYKColor k)](#visit-com.aspose.pdf.Operator.SetCMYKColor-) | Visit/select k operator. |
| [visit(Operator.SetCMYKColorStroke K)](#visit-com.aspose.pdf.Operator.SetCMYKColorStroke-) | Visit/select K operator. |
| [visit(Operator.LineTo l)](#visit-com.aspose.pdf.Operator.LineTo-) | Visit/select l operator. |
| [visit(Operator.MoveTo m)](#visit-com.aspose.pdf.Operator.MoveTo-) | Visit/select m operator. |
| [visit(Operator.SetMiterLimit M)](#visit-com.aspose.pdf.Operator.SetMiterLimit-) | Visit/select M operator. |
| [visit(Operator.MP MP)](#visit-com.aspose.pdf.Operator.MP-) | Visit/select MP operator. |
| [visit(Operator.EndPath n)](#visit-com.aspose.pdf.Operator.EndPath-) | Visit/select n operator. |
| [visit(Operator.GSave q)](#visit-com.aspose.pdf.Operator.GSave-) | Visit/select q operator. |
| [visit(Operator.GRestore Q)](#visit-com.aspose.pdf.Operator.GRestore-) | Visit/select Q operator. |
| [visit(Operator.Re re)](#visit-com.aspose.pdf.Operator.Re-) | Visit/select re operator. |
| [visit(Operator.SetRGBColor rg)](#visit-com.aspose.pdf.Operator.SetRGBColor-) | Visit/select rg operator. |
| [visit(Operator.SetRGBColorStroke RG)](#visit-com.aspose.pdf.Operator.SetRGBColorStroke-) | Visit/select RG operator. |
| [visit(Operator.SetColorRenderingIntent ri)](#visit-com.aspose.pdf.Operator.SetColorRenderingIntent-) | Visit/select ri operator. |
| [visit(Operator.ClosePathStroke s)](#visit-com.aspose.pdf.Operator.ClosePathStroke-) | Visit/select s operator. |
| [visit(Operator.Stroke S)](#visit-com.aspose.pdf.Operator.Stroke-) | Visit/select S operator. |
| [visit(Operator.SetColor sc)](#visit-com.aspose.pdf.Operator.SetColor-) | Visit/select sc operator. |
| [visit(Operator.SetColorStroke SC)](#visit-com.aspose.pdf.Operator.SetColorStroke-) | Visit/select SC operator. |
| [visit(Operator.SetAdvancedColor scn)](#visit-com.aspose.pdf.Operator.SetAdvancedColor-) | Visit/select scn operator. |
| [visit(Operator.SetAdvancedColorStroke SCN)](#visit-com.aspose.pdf.Operator.SetAdvancedColorStroke-) | Visit/select SCN operator. |
| [visit(Operator.ShFill sh)](#visit-com.aspose.pdf.Operator.ShFill-) | Visit/select sh operator. |
| [visit(Operator.MoveToNextLine T_)](#visit-com.aspose.pdf.Operator.MoveToNextLine-) | Visit/select T\* operator. |
| [visit(Operator.SetCharacterSpacing Tc)](#visit-com.aspose.pdf.Operator.SetCharacterSpacing-) | Visit/select Tc operator. |
| [visit(Operator.MoveTextPosition Td)](#visit-com.aspose.pdf.Operator.MoveTextPosition-) | Visit/select Td operator. |
| [visit(Operator.MoveTextPositionSetLeading TD)](#visit-com.aspose.pdf.Operator.MoveTextPositionSetLeading-) | Visit/select TD operator. |
| [visit(Operator.SelectFont Tf)](#visit-com.aspose.pdf.Operator.SelectFont-) | Visit/select Tf operator. |
| [visit(Operator.ShowText Tj)](#visit-com.aspose.pdf.Operator.ShowText-) | Visit/select Tj operator. |
| [visit(Operator.SetGlyphsPositionShowText TJ)](#visit-com.aspose.pdf.Operator.SetGlyphsPositionShowText-) | Visit/select TJ operator. |
| [visit(Operator.SetTextLeading TL)](#visit-com.aspose.pdf.Operator.SetTextLeading-) | Visit/select TL operator. |
| [visit(Operator.SetTextMatrix Tm)](#visit-com.aspose.pdf.Operator.SetTextMatrix-) | Visit/select Tm operator. |
| [visit(Operator.SetTextRenderingMode Tr)](#visit-com.aspose.pdf.Operator.SetTextRenderingMode-) | Visit/select Tr operator. |
| [visit(Operator.SetTextRise Ts)](#visit-com.aspose.pdf.Operator.SetTextRise-) | Visit/select Ts operator. |
| [visit(Operator.SetWordSpacing Tw)](#visit-com.aspose.pdf.Operator.SetWordSpacing-) | Visit/select Tw operator. |
| [visit(Operator.SetHorizontalTextScaling Tz)](#visit-com.aspose.pdf.Operator.SetHorizontalTextScaling-) | Visit/select Tz operator. |
| [visit(Operator.CurveTo1 v)](#visit-com.aspose.pdf.Operator.CurveTo1-) | Visit/select v operator. |
| [visit(Operator.EOClip W_)](#visit-com.aspose.pdf.Operator.EOClip-) | Visit/select W\* operator. |
| [visit(Operator.SetLineWidth w)](#visit-com.aspose.pdf.Operator.SetLineWidth-) | Visit/select w operator. |
| [visit(Operator.Clip W)](#visit-com.aspose.pdf.Operator.Clip-) | Visit/select W operator. |
| [visit(Operator.CurveTo2 y)](#visit-com.aspose.pdf.Operator.CurveTo2-) | Visit/select y operator. |
| [visit(Operator.TextOperator textOperator)](#visit-com.aspose.pdf.Operator.TextOperator-) | Visit/select any text operator operator. |
### OperatorSelector(Operator op) {#OperatorSelector-com.aspose.pdf.Operator-}
```
public OperatorSelector(Operator op)
```


Initializes new  OperatorSelector .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| op | [Operator](../../com.aspose.pdf/operator) | The operator to visit/select. |

### visit(Operator.SetLineJoin j) {#visit-com.aspose.pdf.Operator.SetLineJoin-}
```
public void visit(Operator.SetLineJoin j)
```


Visit/select j operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| j | [SetLineJoin](../../com.aspose.pdf/setlinejoin) | Set line join style operator. |

### visit(Operator.EX EX) {#visit-com.aspose.pdf.Operator.EX-}
```
public void visit(Operator.EX EX)
```


Visit/select EX operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| EX | [EX](../../com.aspose.pdf/ex) | End compatibility section operator. |

### visit(Operator.ET ET) {#visit-com.aspose.pdf.Operator.ET-}
```
public void visit(Operator.ET ET)
```


Visit/select ET operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ET | [ET](../../com.aspose.pdf/et) | End text object operator. |

### visit(Operator.EMC EMC) {#visit-com.aspose.pdf.Operator.EMC-}
```
public void visit(Operator.EMC EMC)
```


Visit/select EMC operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| EMC | [EMC](../../com.aspose.pdf/emc) | End marked-content sequence operator. |

### visit(Operator.EI EI) {#visit-com.aspose.pdf.Operator.EI-}
```
public void visit(Operator.EI EI)
```


Visit/select EI operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| EI | [EI](../../com.aspose.pdf/ei) | End inline image object operator. |

### visit(Operator.DP DP) {#visit-com.aspose.pdf.Operator.DP-}
```
public void visit(Operator.DP DP)
```


Visit/select DP operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| DP | [DP](../../com.aspose.pdf/dp) | Define marked-content point operator (with property list). |

### visit(Operator.Do Do) {#visit-com.aspose.pdf.Operator.Do-}
```
public void visit(Operator.Do Do)
```


Visit/select Do operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| Do | [Do](../../com.aspose.pdf/do) | Invoke named XObject operator. |

### visit(Operator.SetCharWidthBoundingBox d1) {#visit-com.aspose.pdf.Operator.SetCharWidthBoundingBox-}
```
public void visit(Operator.SetCharWidthBoundingBox d1)
```


Visit/select d1 operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| d1 | [SetCharWidthBoundingBox](../../com.aspose.pdf/setcharwidthboundingbox) | Set glyph width and bounding box in Type 3 font operator. |

### visit(Operator.SetCharWidth d0) {#visit-com.aspose.pdf.Operator.SetCharWidth-}
```
public void visit(Operator.SetCharWidth d0)
```


Visit/select d0 operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| d0 | [SetCharWidth](../../com.aspose.pdf/setcharwidth) | Set glyph width in Type 3 font operator. |

### visit(Operator.SetDash d) {#visit-com.aspose.pdf.Operator.SetDash-}
```
public void visit(Operator.SetDash d)
```


Visit/select d operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| d | [SetDash](../../com.aspose.pdf/setdash) | Set line dash pattern operator. |

### visit(Operator.SetColorSpaceStroke CS) {#visit-com.aspose.pdf.Operator.SetColorSpaceStroke-}
```
public void visit(Operator.SetColorSpaceStroke CS)
```


Visit/select CS operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| CS | [SetColorSpaceStroke](../../com.aspose.pdf/setcolorspacestroke) | Set color space operator (for stroking operations). |

### visit(Operator.SetColorSpace cs) {#visit-com.aspose.pdf.Operator.SetColorSpace-}
```
public void visit(Operator.SetColorSpace cs)
```


Visit/select cs operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cs | [SetColorSpace](../../com.aspose.pdf/setcolorspace) | Set color space operator (for nonstroking operations). |

### visit(Operator.ConcatenateMatrix cm) {#visit-com.aspose.pdf.Operator.ConcatenateMatrix-}
```
public void visit(Operator.ConcatenateMatrix cm)
```


Visit/select cm operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cm | [ConcatenateMatrix](../../com.aspose.pdf/concatenatematrix) | Concatenate matrix to current transformation matrix operator. |

### visit(Operator.CurveTo c) {#visit-com.aspose.pdf.Operator.CurveTo-}
```
public void visit(Operator.CurveTo c)
```


Visit/select c operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| c | [CurveTo](../../com.aspose.pdf/curveto) | Append curved segment to path operator (three control points). |

### visit(Operator.BX BX) {#visit-com.aspose.pdf.Operator.BX-}
```
public void visit(Operator.BX BX)
```


Visit/select BX operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| BX | [BX](../../com.aspose.pdf/bx) | Begin compatibility section operator. |

### visit(Operator.BT BT) {#visit-com.aspose.pdf.Operator.BT-}
```
public void visit(Operator.BT BT)
```


Visit/select BT operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| BT | [BT](../../com.aspose.pdf/bt) | Begin text object operator. |

### visit(Operator.BMC BMC) {#visit-com.aspose.pdf.Operator.BMC-}
```
public void visit(Operator.BMC BMC)
```


Visit/select BMC operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| BMC | [BMC](../../com.aspose.pdf/bmc) | Begin marked-content sequence operator. |

### visit(Operator.BI BI) {#visit-com.aspose.pdf.Operator.BI-}
```
public void visit(Operator.BI BI)
```


Visit/select BI operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| BI | [BI](../../com.aspose.pdf/bi) | Begin inline image object operator. |

### visit(Operator.BDC BDC) {#visit-com.aspose.pdf.Operator.BDC-}
```
public void visit(Operator.BDC BDC)
```


Visit/select BDC operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| BDC | [BDC](../../com.aspose.pdf/bdc) | Begin marked-content sequence operator (with property list). |

### visit(Operator.FillStroke B) {#visit-com.aspose.pdf.Operator.FillStroke-}
```
public void visit(Operator.FillStroke B)
```


Visit/select B operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| B | [FillStroke](../../com.aspose.pdf/fillstroke) | Fill and stroke path operator (nonzero winding number rule). |

### visit(Operator.ClosePathFillStroke b) {#visit-com.aspose.pdf.Operator.ClosePathFillStroke-}
```
public void visit(Operator.ClosePathFillStroke b)
```


Visit/select b operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| b | [ClosePathFillStroke](../../com.aspose.pdf/closepathfillstroke) | Close, fill, and stroke path operator (nonzero winding number rule). |

### visit(Operator.EOFillStroke B_) {#visit-com.aspose.pdf.Operator.EOFillStroke-}
```
public void visit(Operator.EOFillStroke B_)
```


Visit/select B\* operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| B_ | [EOFillStroke](../../com.aspose.pdf/eofillstroke) | Fill and stroke path operator (even-odd rule). |

### visit(Operator.ClosePathEOFillStroke b_) {#visit-com.aspose.pdf.Operator.ClosePathEOFillStroke-}
```
public void visit(Operator.ClosePathEOFillStroke b_)
```


Visit/select b\* operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| b_ | [ClosePathEOFillStroke](../../com.aspose.pdf/closepatheofillstroke) | Close, fill, and stroke path operator (even-odd rule). |

### visit(Operator.MoveToNextLineShowText nextLineShowText) {#visit-com.aspose.pdf.Operator.MoveToNextLineShowText-}
```
public void visit(Operator.MoveToNextLineShowText nextLineShowText)
```


Visit/select ' operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| nextLineShowText | [MoveToNextLineShowText](../../com.aspose.pdf/movetonextlineshowtext) | Move to next line and show text operator. |

### visit(Operator.SetSpacingMoveToNextLineShowText nextLineShowText) {#visit-com.aspose.pdf.Operator.SetSpacingMoveToNextLineShowText-}
```
public void visit(Operator.SetSpacingMoveToNextLineShowText nextLineShowText)
```


Visit/select '' operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| nextLineShowText | [SetSpacingMoveToNextLineShowText](../../com.aspose.pdf/setspacingmovetonextlineshowtext) | Set word and character spacing, move to next line, and show text operator. |

### visit(Operator.EOFill f_) {#visit-com.aspose.pdf.Operator.EOFill-}
```
public void visit(Operator.EOFill f_)
```


Visit/select operator f\*.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| f_ | [EOFill](../../com.aspose.pdf/eofill) | Fill path operator (even-odd rule). |

### visit(BDC BDC) {#visit-com.aspose.pdf.operators.BDC-}
```
public void visit(BDC BDC)
```


Visit/select BDC operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| BDC | [BDC](../../com.aspose.pdf.operators/bdc) | Begin marked-content sequence operator (with property list). |

### visit(Fill f) {#visit-com.aspose.pdf.operators.Fill-}
```
public void visit(Fill f)
```


Visit/select f operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| f | [Fill](../../com.aspose.pdf.operators/fill) | Fill path operator (nonzero winding number rule). |

### visit(ClosePathStroke s) {#visit-com.aspose.pdf.operators.ClosePathStroke-}
```
public void visit(ClosePathStroke s)
```


Visit/select s operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| s | [ClosePathStroke](../../com.aspose.pdf.operators/closepathstroke) | Close and stroke path operator. |

### visit(Stroke S) {#visit-com.aspose.pdf.operators.Stroke-}
```
public void visit(Stroke S)
```


Visit/select S operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| S | [Stroke](../../com.aspose.pdf.operators/stroke) | Stroke path operator. |

### visit(Operator.Fill f) {#visit-com.aspose.pdf.Operator.Fill-}
```
public void visit(Operator.Fill f)
```


Visit/select f operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| f | [Fill](../../com.aspose.pdf/fill) | Fill path operator (nonzero winding number rule). |

### visit(Operator.ObsoleteFill F) {#visit-com.aspose.pdf.Operator.ObsoleteFill-}
```
public void visit(Operator.ObsoleteFill F)
```


Visit/select F operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| F | [ObsoleteFill](../../com.aspose.pdf/obsoletefill) | Fill path operator (nonzero winding number rule). |

### visit(Operator.SetGray g) {#visit-com.aspose.pdf.Operator.SetGray-}
```
public void visit(Operator.SetGray g)
```


Visit/select g operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| g | [SetGray](../../com.aspose.pdf/setgray) | Set gray level operator (for nonstroking operations). |

### visit(Operator.SetGrayStroke G) {#visit-com.aspose.pdf.Operator.SetGrayStroke-}
```
public void visit(Operator.SetGrayStroke G)
```


Visit/select G operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| G | [SetGrayStroke](../../com.aspose.pdf/setgraystroke) | Set gray level operator (for stroking operations). |

### visit(Operator.GS gs) {#visit-com.aspose.pdf.Operator.GS-}
```
public void visit(Operator.GS gs)
```


Visit/select gs operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| gs | [GS](../../com.aspose.pdf/gs) | Set graphics state operator. |

### visit(Operator.ClosePath h) {#visit-com.aspose.pdf.Operator.ClosePath-}
```
public void visit(Operator.ClosePath h)
```


Visit/select h operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| h | [ClosePath](../../com.aspose.pdf/closepath) | Close subpath operator. |

### visit(Operator.SetFlat i) {#visit-com.aspose.pdf.Operator.SetFlat-}
```
public void visit(Operator.SetFlat i)
```


Visit/select i operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| i | [SetFlat](../../com.aspose.pdf/setflat) | Set flatness tolerance operator. |

### visit(Operator.ID ID) {#visit-com.aspose.pdf.Operator.ID-}
```
public void visit(Operator.ID ID)
```


Visit/select ID operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ID | [ID](../../com.aspose.pdf/id) | Begin inline image data operator. |

### visit(Operator.SetLineCap J) {#visit-com.aspose.pdf.Operator.SetLineCap-}
```
public void visit(Operator.SetLineCap J)
```


Visit/select J operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| J | [SetLineCap](../../com.aspose.pdf/setlinecap) | Set line cap style operator. |

### visit(Operator.SetCMYKColor k) {#visit-com.aspose.pdf.Operator.SetCMYKColor-}
```
public void visit(Operator.SetCMYKColor k)
```


Visit/select k operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| k | [SetCMYKColor](../../com.aspose.pdf/setcmykcolor) | Set CMYK color operator (for nonstroking operations). |

### visit(Operator.SetCMYKColorStroke K) {#visit-com.aspose.pdf.Operator.SetCMYKColorStroke-}
```
public void visit(Operator.SetCMYKColorStroke K)
```


Visit/select K operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| K | [SetCMYKColorStroke](../../com.aspose.pdf/setcmykcolorstroke) | Set CMYK color operator (for stroking operations). |

### visit(Operator.LineTo l) {#visit-com.aspose.pdf.Operator.LineTo-}
```
public void visit(Operator.LineTo l)
```


Visit/select l operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| l | [LineTo](../../com.aspose.pdf/lineto) | Append straight line segment to path operator. |

### visit(Operator.MoveTo m) {#visit-com.aspose.pdf.Operator.MoveTo-}
```
public void visit(Operator.MoveTo m)
```


Visit/select m operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| m | [MoveTo](../../com.aspose.pdf/moveto) | Begin new subpath operator. |

### visit(Operator.SetMiterLimit M) {#visit-com.aspose.pdf.Operator.SetMiterLimit-}
```
public void visit(Operator.SetMiterLimit M)
```


Visit/select M operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| M | [SetMiterLimit](../../com.aspose.pdf/setmiterlimit) | Set miter limit operator. |

### visit(Operator.MP MP) {#visit-com.aspose.pdf.Operator.MP-}
```
public void visit(Operator.MP MP)
```


Visit/select MP operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| MP | [MP](../../com.aspose.pdf/mp) | Define marked-content point operator. |

### visit(Operator.EndPath n) {#visit-com.aspose.pdf.Operator.EndPath-}
```
public void visit(Operator.EndPath n)
```


Visit/select n operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| n | [EndPath](../../com.aspose.pdf/endpath) | End path operator (without filling or stroking). |

### visit(Operator.GSave q) {#visit-com.aspose.pdf.Operator.GSave-}
```
public void visit(Operator.GSave q)
```


Visit/select q operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| q | [GSave](../../com.aspose.pdf/gsave) | Save graphics state operator. |

### visit(Operator.GRestore Q) {#visit-com.aspose.pdf.Operator.GRestore-}
```
public void visit(Operator.GRestore Q)
```


Visit/select Q operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| Q | [GRestore](../../com.aspose.pdf/grestore) | Restore graphics state operator. |

### visit(Operator.Re re) {#visit-com.aspose.pdf.Operator.Re-}
```
public void visit(Operator.Re re)
```


Visit/select re operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| re | [Re](../../com.aspose.pdf/re) | Append rectangle to path operator. |

### visit(Operator.SetRGBColor rg) {#visit-com.aspose.pdf.Operator.SetRGBColor-}
```
public void visit(Operator.SetRGBColor rg)
```


Visit/select rg operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rg | [SetRGBColor](../../com.aspose.pdf/setrgbcolor) | Set RGB color operator (for nonstroking operations). |

### visit(Operator.SetRGBColorStroke RG) {#visit-com.aspose.pdf.Operator.SetRGBColorStroke-}
```
public void visit(Operator.SetRGBColorStroke RG)
```


Visit/select RG operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| RG | [SetRGBColorStroke](../../com.aspose.pdf/setrgbcolorstroke) | Set RGB color operator (for stroking operations). |

### visit(Operator.SetColorRenderingIntent ri) {#visit-com.aspose.pdf.Operator.SetColorRenderingIntent-}
```
public void visit(Operator.SetColorRenderingIntent ri)
```


Visit/select ri operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ri | [SetColorRenderingIntent](../../com.aspose.pdf/setcolorrenderingintent) | Set color rendering intent operator. |

### visit(Operator.ClosePathStroke s) {#visit-com.aspose.pdf.Operator.ClosePathStroke-}
```
public void visit(Operator.ClosePathStroke s)
```


Visit/select s operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| s | [ClosePathStroke](../../com.aspose.pdf/closepathstroke) | Close and stroke path operator. |

### visit(Operator.Stroke S) {#visit-com.aspose.pdf.Operator.Stroke-}
```
public void visit(Operator.Stroke S)
```


Visit/select S operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| S | [Stroke](../../com.aspose.pdf/stroke) | Stroke path operator. |

### visit(Operator.SetColor sc) {#visit-com.aspose.pdf.Operator.SetColor-}
```
public void visit(Operator.SetColor sc)
```


Visit/select sc operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sc | [SetColor](../../com.aspose.pdf/setcolor) | Set color operator (for nonstroking operations). |

### visit(Operator.SetColorStroke SC) {#visit-com.aspose.pdf.Operator.SetColorStroke-}
```
public void visit(Operator.SetColorStroke SC)
```


Visit/select SC operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| SC | [SetColorStroke](../../com.aspose.pdf/setcolorstroke) | Set color operator (for stroking operations). |

### visit(Operator.SetAdvancedColor scn) {#visit-com.aspose.pdf.Operator.SetAdvancedColor-}
```
public void visit(Operator.SetAdvancedColor scn)
```


Visit/select scn operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| scn | [SetAdvancedColor](../../com.aspose.pdf/setadvancedcolor) | Set color operator (for nonstroking operations, ICCBased and special colour spaces). |

### visit(Operator.SetAdvancedColorStroke SCN) {#visit-com.aspose.pdf.Operator.SetAdvancedColorStroke-}
```
public void visit(Operator.SetAdvancedColorStroke SCN)
```


Visit/select SCN operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| SCN | [SetAdvancedColorStroke](../../com.aspose.pdf/setadvancedcolorstroke) | Set color operator (for stroking operations, ICCBasedand special colour spaces). |

### visit(Operator.ShFill sh) {#visit-com.aspose.pdf.Operator.ShFill-}
```
public void visit(Operator.ShFill sh)
```


Visit/select sh operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sh | [ShFill](../../com.aspose.pdf/shfill) | Paint area defined by shading pattern operator. |

### visit(Operator.MoveToNextLine T_) {#visit-com.aspose.pdf.Operator.MoveToNextLine-}
```
public void visit(Operator.MoveToNextLine T_)
```


Visit/select T\* operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| T_ | [MoveToNextLine](../../com.aspose.pdf/movetonextline) | Move to start of next text line operator. |

### visit(Operator.SetCharacterSpacing Tc) {#visit-com.aspose.pdf.Operator.SetCharacterSpacing-}
```
public void visit(Operator.SetCharacterSpacing Tc)
```


Visit/select Tc operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| Tc | [SetCharacterSpacing](../../com.aspose.pdf/setcharacterspacing) | Set character spacing operator. |

### visit(Operator.MoveTextPosition Td) {#visit-com.aspose.pdf.Operator.MoveTextPosition-}
```
public void visit(Operator.MoveTextPosition Td)
```


Visit/select Td operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| Td | [MoveTextPosition](../../com.aspose.pdf/movetextposition) | Move text position operator. |

### visit(Operator.MoveTextPositionSetLeading TD) {#visit-com.aspose.pdf.Operator.MoveTextPositionSetLeading-}
```
public void visit(Operator.MoveTextPositionSetLeading TD)
```


Visit/select TD operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| TD | [MoveTextPositionSetLeading](../../com.aspose.pdf/movetextpositionsetleading) | Move text position and set leading operator. |

### visit(Operator.SelectFont Tf) {#visit-com.aspose.pdf.Operator.SelectFont-}
```
public void visit(Operator.SelectFont Tf)
```


Visit/select Tf operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| Tf | [SelectFont](../../com.aspose.pdf/selectfont) | Set text font and size operator. |

### visit(Operator.ShowText Tj) {#visit-com.aspose.pdf.Operator.ShowText-}
```
public void visit(Operator.ShowText Tj)
```


Visit/select Tj operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| Tj | [ShowText](../../com.aspose.pdf/showtext) | Show text operator. |

### visit(Operator.SetGlyphsPositionShowText TJ) {#visit-com.aspose.pdf.Operator.SetGlyphsPositionShowText-}
```
public void visit(Operator.SetGlyphsPositionShowText TJ)
```


Visit/select TJ operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| TJ | [SetGlyphsPositionShowText](../../com.aspose.pdf/setglyphspositionshowtext) | Show text operator (allowing individual glyph positioning). |

### visit(Operator.SetTextLeading TL) {#visit-com.aspose.pdf.Operator.SetTextLeading-}
```
public void visit(Operator.SetTextLeading TL)
```


Visit/select TL operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| TL | [SetTextLeading](../../com.aspose.pdf/settextleading) | Set text leading operator. |

### visit(Operator.SetTextMatrix Tm) {#visit-com.aspose.pdf.Operator.SetTextMatrix-}
```
public void visit(Operator.SetTextMatrix Tm)
```


Visit/select Tm operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| Tm | [SetTextMatrix](../../com.aspose.pdf/settextmatrix) | Set text matrix and text line matrix operator. |

### visit(Operator.SetTextRenderingMode Tr) {#visit-com.aspose.pdf.Operator.SetTextRenderingMode-}
```
public void visit(Operator.SetTextRenderingMode Tr)
```


Visit/select Tr operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| Tr | [SetTextRenderingMode](../../com.aspose.pdf/settextrenderingmode) | Set text rendering mode operator. |

### visit(Operator.SetTextRise Ts) {#visit-com.aspose.pdf.Operator.SetTextRise-}
```
public void visit(Operator.SetTextRise Ts)
```


Visit/select Ts operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| Ts | [SetTextRise](../../com.aspose.pdf/settextrise) | Set text rise operator. |

### visit(Operator.SetWordSpacing Tw) {#visit-com.aspose.pdf.Operator.SetWordSpacing-}
```
public void visit(Operator.SetWordSpacing Tw)
```


Visit/select Tw operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| Tw | [SetWordSpacing](../../com.aspose.pdf/setwordspacing) | Set word spacing operator. |

### visit(Operator.SetHorizontalTextScaling Tz) {#visit-com.aspose.pdf.Operator.SetHorizontalTextScaling-}
```
public void visit(Operator.SetHorizontalTextScaling Tz)
```


Visit/select Tz operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| Tz | [SetHorizontalTextScaling](../../com.aspose.pdf/sethorizontaltextscaling) | Set horizontal text scaling operator. |

### visit(Operator.CurveTo1 v) {#visit-com.aspose.pdf.Operator.CurveTo1-}
```
public void visit(Operator.CurveTo1 v)
```


Visit/select v operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| v | [CurveTo1](../../com.aspose.pdf/curveto1) | Append curved segment to path operator (initial point replicated). |

### visit(Operator.EOClip W_) {#visit-com.aspose.pdf.Operator.EOClip-}
```
public void visit(Operator.EOClip W_)
```


Visit/select W\* operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| W_ | [EOClip](../../com.aspose.pdf/eoclip) | Set clipping path operator (even-odd rule). |

### visit(Operator.SetLineWidth w) {#visit-com.aspose.pdf.Operator.SetLineWidth-}
```
public void visit(Operator.SetLineWidth w)
```


Visit/select w operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| w | [SetLineWidth](../../com.aspose.pdf/setlinewidth) | Set line width operator. |

### visit(Operator.Clip W) {#visit-com.aspose.pdf.Operator.Clip-}
```
public void visit(Operator.Clip W)
```


Visit/select W operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| W | [Clip](../../com.aspose.pdf/clip) | Set clipping path operator (nonzero winding number rule). |

### visit(Operator.CurveTo2 y) {#visit-com.aspose.pdf.Operator.CurveTo2-}
```
public void visit(Operator.CurveTo2 y)
```


Visit/select y operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| y | [CurveTo2](../../com.aspose.pdf/curveto2) | Append curved segment to path operator (final point replicated). |

### visit(Operator.TextOperator textOperator) {#visit-com.aspose.pdf.Operator.TextOperator-}
```
public void visit(Operator.TextOperator textOperator)
```


Visit/select any text operator operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| textOperator | [TextOperator](../../com.aspose.pdf/textoperator) | General text operator which is used to select the set of corresponding pdf operators. |

