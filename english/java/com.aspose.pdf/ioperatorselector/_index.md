---
title: IOperatorSelector
second_title: Aspose.PDF for Java API Reference
description: Defines Visitor for visiting different pdf operators.
type: docs
weight: 441
url: /java/com.aspose.pdf/ioperatorselector/
---```
public interface IOperatorSelector
```

Defines Visitor for visiting different pdf operators.
## Methods

| Method | Description |
| --- | --- |
| [visit(Fill f)](#visit-com.aspose.pdf.operators.Fill-) | Visit/select f operator. |
| [visit(ObsoleteFill F)](#visit-com.aspose.pdf.operators.ObsoleteFill-) | Visit/select F operator. |
| [visit(EOFill f_)](#visit-com.aspose.pdf.operators.EOFill-) | Visit/select operator f\*. |
| [visit(SetGrayStroke G)](#visit-com.aspose.pdf.operators.SetGrayStroke-) | Visit/select G operator. |
| [visit(SetGray g)](#visit-com.aspose.pdf.operators.SetGray-) | Visit/select g operator. |
| [visit(GS gs)](#visit-com.aspose.pdf.operators.GS-) | Visit/select gs operator. |
| [visit(ClosePath h)](#visit-com.aspose.pdf.operators.ClosePath-) | Visit/select h operator. |
| [visit(SetFlat i)](#visit-com.aspose.pdf.operators.SetFlat-) | Visit/select i operator. |
| [visit(ID ID)](#visit-com.aspose.pdf.operators.ID-) | Visit/select ID operator. |
| [visit(SetColorRenderingIntent ri)](#visit-com.aspose.pdf.operators.SetColorRenderingIntent-) | Visit/select ri operator. |
| [visit(SetLineCap J)](#visit-com.aspose.pdf.operators.SetLineCap-) | Visit/select J operator. |
| [visit(SetMiterLimit M)](#visit-com.aspose.pdf.operators.SetMiterLimit-) | Visit/select M operator. |
| [visit(MP MP)](#visit-com.aspose.pdf.operators.MP-) | Visit/select MP operator. |
| [visit(EndPath n)](#visit-com.aspose.pdf.operators.EndPath-) | Visit/select n operator. |
| [visit(GSave q)](#visit-com.aspose.pdf.operators.GSave-) | Visit/select q operator. |
| [visit(GRestore Q)](#visit-com.aspose.pdf.operators.GRestore-) | Visit/select Q operator. |
| [visit(Re re)](#visit-com.aspose.pdf.operators.Re-) | Visit/select re operator. |
| [visit(SetRGBColorStroke RG)](#visit-com.aspose.pdf.operators.SetRGBColorStroke-) | Visit/select RG operator. |
| [visit(SetRGBColor rg)](#visit-com.aspose.pdf.operators.SetRGBColor-) | Visit/select rg operator. |
| [visit(SetCMYKColorStroke K)](#visit-com.aspose.pdf.operators.SetCMYKColorStroke-) | Visit/select K operator. |
| [visit(SetCMYKColor k)](#visit-com.aspose.pdf.operators.SetCMYKColor-) | Visit/select k operator. |
| [visit(LineTo l)](#visit-com.aspose.pdf.operators.LineTo-) | Visit/select l operator. |
| [visit(MoveTo m)](#visit-com.aspose.pdf.operators.MoveTo-) | Visit/select m operator. |
| [visit(SetWordSpacing Tw)](#visit-com.aspose.pdf.operators.SetWordSpacing-) | Visit/select Tw operator. |
| [visit(ClosePathStroke s)](#visit-com.aspose.pdf.operators.ClosePathStroke-) | Visit/select s operator. |
| [visit(MoveTextPositionSetLeading TD)](#visit-com.aspose.pdf.operators.MoveTextPositionSetLeading-) | Visit/select TD operator. |
| [visit(SelectFont Tf)](#visit-com.aspose.pdf.operators.SelectFont-) | Visit/select Tf operator. |
| [visit(ShowText Tj)](#visit-com.aspose.pdf.operators.ShowText-) | Visit/select Tj operator. |
| [visit(SetGlyphsPositionShowText TJ)](#visit-com.aspose.pdf.operators.SetGlyphsPositionShowText-) | Visit/select TJ operator. |
| [visit(SetTextLeading TL)](#visit-com.aspose.pdf.operators.SetTextLeading-) | Visit/select TL operator. |
| [visit(SetTextMatrix Tm)](#visit-com.aspose.pdf.operators.SetTextMatrix-) | Visit/select Tm operator. |
| [visit(SetTextRenderingMode Tr)](#visit-com.aspose.pdf.operators.SetTextRenderingMode-) | Visit/select Tr operator. |
| [visit(SetTextRise Ts)](#visit-com.aspose.pdf.operators.SetTextRise-) | Visit/select Ts operator. |
| [visit(Stroke S)](#visit-com.aspose.pdf.operators.Stroke-) | Visit/select S operator. |
| [visit(SetColorStroke SC)](#visit-com.aspose.pdf.operators.SetColorStroke-) | Visit/select SC operator. |
| [visit(SetColor sc)](#visit-com.aspose.pdf.operators.SetColor-) | Visit/select sc operator. |
| [visit(SetAdvancedColorStroke SCN)](#visit-com.aspose.pdf.operators.SetAdvancedColorStroke-) | Visit/select SCN operator. |
| [visit(SetAdvancedColor scn)](#visit-com.aspose.pdf.operators.SetAdvancedColor-) | Visit/select scn operator. |
| [visit(ShFill sh)](#visit-com.aspose.pdf.operators.ShFill-) | Visit/select sh operator. |
| [visit(MoveToNextLine T_)](#visit-com.aspose.pdf.operators.MoveToNextLine-) | Visit/select T\* operator. |
| [visit(SetCharacterSpacing Tc)](#visit-com.aspose.pdf.operators.SetCharacterSpacing-) | Visit/select Tc operator. |
| [visit(MoveTextPosition Td)](#visit-com.aspose.pdf.operators.MoveTextPosition-) | Visit/select Td operator. |
| [visit(CurveTo2 y)](#visit-com.aspose.pdf.operators.CurveTo2-) | Visit/select y operator. |
| [visit(EOClip W_)](#visit-com.aspose.pdf.operators.EOClip-) | Visit/select W\* operator. |
| [visit(SetHorizontalTextScaling Tz)](#visit-com.aspose.pdf.operators.SetHorizontalTextScaling-) | Visit/select Tz operator. |
| [visit(CurveTo1 v)](#visit-com.aspose.pdf.operators.CurveTo1-) | Visit/select v operator. |
| [visit(Clip W)](#visit-com.aspose.pdf.operators.Clip-) | Visit/select W operator. |
| [visit(SetLineWidth w)](#visit-com.aspose.pdf.operators.SetLineWidth-) | Visit/select w operator. |
| [visit(SetLineJoin j)](#visit-com.aspose.pdf.operators.SetLineJoin-) | Visit/select j operator. |
| [visit(EX EX)](#visit-com.aspose.pdf.operators.EX-) | Visit/select EX operator. |
| [visit(ET ET)](#visit-com.aspose.pdf.operators.ET-) | Visit/select ET operator. |
| [visit(EMC EMC)](#visit-com.aspose.pdf.operators.EMC-) | Visit/select EMC operator. |
| [visit(EI EI)](#visit-com.aspose.pdf.operators.EI-) | Visit/select EI operator. |
| [visit(DP DP)](#visit-com.aspose.pdf.operators.DP-) | Visit/select DP operator. |
| [visit(Do Do)](#visit-com.aspose.pdf.operators.Do-) | Visit/select Do operator. |
| [visit(SetDash d)](#visit-com.aspose.pdf.operators.SetDash-) | Visit/select d operator. |
| [visit(SetCharWidth d0)](#visit-com.aspose.pdf.operators.SetCharWidth-) | Visit/select d0 operator. |
| [visit(SetCharWidthBoundingBox d1)](#visit-com.aspose.pdf.operators.SetCharWidthBoundingBox-) | Visit/select d1 operator. |
| [visit(SetColorSpaceStroke CS)](#visit-com.aspose.pdf.operators.SetColorSpaceStroke-) | Visit/select CS operator. |
| [visit(SetColorSpace cs)](#visit-com.aspose.pdf.operators.SetColorSpace-) | Visit/select cs operator. |
| [visit(ConcatenateMatrix cm)](#visit-com.aspose.pdf.operators.ConcatenateMatrix-) | Visit/select cm operator. |
| [visit(CurveTo c)](#visit-com.aspose.pdf.operators.CurveTo-) | Visit/select c operator. |
| [visit(BX BX)](#visit-com.aspose.pdf.operators.BX-) | Visit/select BX operator. |
| [visit(BT BT)](#visit-com.aspose.pdf.operators.BT-) | Visit/select BT operator. |
| [visit(BMC BMC)](#visit-com.aspose.pdf.operators.BMC-) | Visit/select BMC operator. |
| [visit(BI BI)](#visit-com.aspose.pdf.operators.BI-) | Visit/select BI operator. |
| [visit(BDC BDC)](#visit-com.aspose.pdf.operators.BDC-) | Visit/select BDC operator. |
| [visit(FillStroke B)](#visit-com.aspose.pdf.operators.FillStroke-) | Visit/select B operator. |
| [visit(ClosePathFillStroke b)](#visit-com.aspose.pdf.operators.ClosePathFillStroke-) | Visit/select b operator. |
| [visit(EOFillStroke B_)](#visit-com.aspose.pdf.operators.EOFillStroke-) | Visit/select B\* operator. |
| [visit(ClosePathEOFillStroke b_)](#visit-com.aspose.pdf.operators.ClosePathEOFillStroke-) | Visit/select b\* operator. |
| [visit(MoveToNextLineShowText value)](#visit-com.aspose.pdf.operators.MoveToNextLineShowText-) | Visit/select ' operator. |
| [visit(SetSpacingMoveToNextLineShowText value)](#visit-com.aspose.pdf.operators.SetSpacingMoveToNextLineShowText-) | Visit/select '' operator. |
| [visit(TextOperator textOperator)](#visit-com.aspose.pdf.operators.TextOperator-) | Visit/select any text operator operator. |
### visit(Fill f) {#visit-com.aspose.pdf.operators.Fill-}
```
public abstract void visit(Fill f)
```


Visit/select f operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| f | [Fill](../../com.aspose.pdf.operators/fill) | Fill path operator (nonzero winding number rule). |

### visit(ObsoleteFill F) {#visit-com.aspose.pdf.operators.ObsoleteFill-}
```
public abstract void visit(ObsoleteFill F)
```


Visit/select F operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| F | [ObsoleteFill](../../com.aspose.pdf.operators/obsoletefill) | Fill path operator (nonzero winding number rule). |

### visit(EOFill f_) {#visit-com.aspose.pdf.operators.EOFill-}
```
public abstract void visit(EOFill f_)
```


Visit/select operator f\*.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| f_ | [EOFill](../../com.aspose.pdf.operators/eofill) | Fill path operator (even-odd rule). |

### visit(SetGrayStroke G) {#visit-com.aspose.pdf.operators.SetGrayStroke-}
```
public abstract void visit(SetGrayStroke G)
```


Visit/select G operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| G | [SetGrayStroke](../../com.aspose.pdf.operators/setgraystroke) | Set gray level operator (for stroking operations). |

### visit(SetGray g) {#visit-com.aspose.pdf.operators.SetGray-}
```
public abstract void visit(SetGray g)
```


Visit/select g operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| g | [SetGray](../../com.aspose.pdf.operators/setgray) | Set gray level operator (for nonstroking operations). |

### visit(GS gs) {#visit-com.aspose.pdf.operators.GS-}
```
public abstract void visit(GS gs)
```


Visit/select gs operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| gs | [GS](../../com.aspose.pdf.operators/gs) | Set graphics state operator. |

### visit(ClosePath h) {#visit-com.aspose.pdf.operators.ClosePath-}
```
public abstract void visit(ClosePath h)
```


Visit/select h operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| h | [ClosePath](../../com.aspose.pdf.operators/closepath) | Close subpath operator. |

### visit(SetFlat i) {#visit-com.aspose.pdf.operators.SetFlat-}
```
public abstract void visit(SetFlat i)
```


Visit/select i operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| i | [SetFlat](../../com.aspose.pdf.operators/setflat) | Set flatness tolerance operator. |

### visit(ID ID) {#visit-com.aspose.pdf.operators.ID-}
```
public abstract void visit(ID ID)
```


Visit/select ID operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ID | [ID](../../com.aspose.pdf.operators/id) | Begin inline image data operator. |

### visit(SetColorRenderingIntent ri) {#visit-com.aspose.pdf.operators.SetColorRenderingIntent-}
```
public abstract void visit(SetColorRenderingIntent ri)
```


Visit/select ri operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ri | [SetColorRenderingIntent](../../com.aspose.pdf.operators/setcolorrenderingintent) | Set color rendering intent operator. |

### visit(SetLineCap J) {#visit-com.aspose.pdf.operators.SetLineCap-}
```
public abstract void visit(SetLineCap J)
```


Visit/select J operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| J | [SetLineCap](../../com.aspose.pdf.operators/setlinecap) | Set line cap style operator. |

### visit(SetMiterLimit M) {#visit-com.aspose.pdf.operators.SetMiterLimit-}
```
public abstract void visit(SetMiterLimit M)
```


Visit/select M operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| M | [SetMiterLimit](../../com.aspose.pdf.operators/setmiterlimit) | Set miter limit operator. |

### visit(MP MP) {#visit-com.aspose.pdf.operators.MP-}
```
public abstract void visit(MP MP)
```


Visit/select MP operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| MP | [MP](../../com.aspose.pdf.operators/mp) | Define marked-content point operator. |

### visit(EndPath n) {#visit-com.aspose.pdf.operators.EndPath-}
```
public abstract void visit(EndPath n)
```


Visit/select n operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| n | [EndPath](../../com.aspose.pdf.operators/endpath) | End path operator (without filling or stroking). |

### visit(GSave q) {#visit-com.aspose.pdf.operators.GSave-}
```
public abstract void visit(GSave q)
```


Visit/select q operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| q | [GSave](../../com.aspose.pdf.operators/gsave) | Save graphics state operator. |

### visit(GRestore Q) {#visit-com.aspose.pdf.operators.GRestore-}
```
public abstract void visit(GRestore Q)
```


Visit/select Q operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| Q | [GRestore](../../com.aspose.pdf.operators/grestore) | Restore graphics state operator. |

### visit(Re re) {#visit-com.aspose.pdf.operators.Re-}
```
public abstract void visit(Re re)
```


Visit/select re operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| re | [Re](../../com.aspose.pdf.operators/re) | Append rectangle to path operator. |

### visit(SetRGBColorStroke RG) {#visit-com.aspose.pdf.operators.SetRGBColorStroke-}
```
public abstract void visit(SetRGBColorStroke RG)
```


Visit/select RG operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| RG | [SetRGBColorStroke](../../com.aspose.pdf.operators/setrgbcolorstroke) | Set RGB color operator (for stroking operations). |

### visit(SetRGBColor rg) {#visit-com.aspose.pdf.operators.SetRGBColor-}
```
public abstract void visit(SetRGBColor rg)
```


Visit/select rg operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rg | [SetRGBColor](../../com.aspose.pdf.operators/setrgbcolor) | Set RGB color operator (for nonstroking operations). |

### visit(SetCMYKColorStroke K) {#visit-com.aspose.pdf.operators.SetCMYKColorStroke-}
```
public abstract void visit(SetCMYKColorStroke K)
```


Visit/select K operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| K | [SetCMYKColorStroke](../../com.aspose.pdf.operators/setcmykcolorstroke) | Set CMYK color operator (for stroking operations). |

### visit(SetCMYKColor k) {#visit-com.aspose.pdf.operators.SetCMYKColor-}
```
public abstract void visit(SetCMYKColor k)
```


Visit/select k operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| k | [SetCMYKColor](../../com.aspose.pdf.operators/setcmykcolor) | Set CMYK color operator (for nonstroking operations). |

### visit(LineTo l) {#visit-com.aspose.pdf.operators.LineTo-}
```
public abstract void visit(LineTo l)
```


Visit/select l operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| l | [LineTo](../../com.aspose.pdf.operators/lineto) | Append straight line segment to path operator. |

### visit(MoveTo m) {#visit-com.aspose.pdf.operators.MoveTo-}
```
public abstract void visit(MoveTo m)
```


Visit/select m operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| m | [MoveTo](../../com.aspose.pdf.operators/moveto) | Begin new subpath operator. |

### visit(SetWordSpacing Tw) {#visit-com.aspose.pdf.operators.SetWordSpacing-}
```
public abstract void visit(SetWordSpacing Tw)
```


Visit/select Tw operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| Tw | [SetWordSpacing](../../com.aspose.pdf.operators/setwordspacing) | Set word spacing operator. |

### visit(ClosePathStroke s) {#visit-com.aspose.pdf.operators.ClosePathStroke-}
```
public abstract void visit(ClosePathStroke s)
```


Visit/select s operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| s | [ClosePathStroke](../../com.aspose.pdf.operators/closepathstroke) | Close and stroke path operator. |

### visit(MoveTextPositionSetLeading TD) {#visit-com.aspose.pdf.operators.MoveTextPositionSetLeading-}
```
public abstract void visit(MoveTextPositionSetLeading TD)
```


Visit/select TD operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| TD | [MoveTextPositionSetLeading](../../com.aspose.pdf.operators/movetextpositionsetleading) | Move text position and set leading operator. |

### visit(SelectFont Tf) {#visit-com.aspose.pdf.operators.SelectFont-}
```
public abstract void visit(SelectFont Tf)
```


Visit/select Tf operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| Tf | [SelectFont](../../com.aspose.pdf.operators/selectfont) | Set text font and size operator. |

### visit(ShowText Tj) {#visit-com.aspose.pdf.operators.ShowText-}
```
public abstract void visit(ShowText Tj)
```


Visit/select Tj operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| Tj | [ShowText](../../com.aspose.pdf.operators/showtext) | Show text operator. |

### visit(SetGlyphsPositionShowText TJ) {#visit-com.aspose.pdf.operators.SetGlyphsPositionShowText-}
```
public abstract void visit(SetGlyphsPositionShowText TJ)
```


Visit/select TJ operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| TJ | [SetGlyphsPositionShowText](../../com.aspose.pdf.operators/setglyphspositionshowtext) | Show text operator (allowing individual glyph positioning). |

### visit(SetTextLeading TL) {#visit-com.aspose.pdf.operators.SetTextLeading-}
```
public abstract void visit(SetTextLeading TL)
```


Visit/select TL operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| TL | [SetTextLeading](../../com.aspose.pdf.operators/settextleading) | Set text leading operator. |

### visit(SetTextMatrix Tm) {#visit-com.aspose.pdf.operators.SetTextMatrix-}
```
public abstract void visit(SetTextMatrix Tm)
```


Visit/select Tm operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| Tm | [SetTextMatrix](../../com.aspose.pdf.operators/settextmatrix) | Set text matrix and text line matrix operator. |

### visit(SetTextRenderingMode Tr) {#visit-com.aspose.pdf.operators.SetTextRenderingMode-}
```
public abstract void visit(SetTextRenderingMode Tr)
```


Visit/select Tr operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| Tr | [SetTextRenderingMode](../../com.aspose.pdf.operators/settextrenderingmode) | Set text rendering mode operator. |

### visit(SetTextRise Ts) {#visit-com.aspose.pdf.operators.SetTextRise-}
```
public abstract void visit(SetTextRise Ts)
```


Visit/select Ts operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| Ts | [SetTextRise](../../com.aspose.pdf.operators/settextrise) | Set text rise operator. |

### visit(Stroke S) {#visit-com.aspose.pdf.operators.Stroke-}
```
public abstract void visit(Stroke S)
```


Visit/select S operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| S | [Stroke](../../com.aspose.pdf.operators/stroke) | Stroke path operator. |

### visit(SetColorStroke SC) {#visit-com.aspose.pdf.operators.SetColorStroke-}
```
public abstract void visit(SetColorStroke SC)
```


Visit/select SC operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| SC | [SetColorStroke](../../com.aspose.pdf.operators/setcolorstroke) | Set color operator (for stroking operations). |

### visit(SetColor sc) {#visit-com.aspose.pdf.operators.SetColor-}
```
public abstract void visit(SetColor sc)
```


Visit/select sc operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sc | [SetColor](../../com.aspose.pdf.operators/setcolor) | Set color operator (for nonstroking operations). |

### visit(SetAdvancedColorStroke SCN) {#visit-com.aspose.pdf.operators.SetAdvancedColorStroke-}
```
public abstract void visit(SetAdvancedColorStroke SCN)
```


Visit/select SCN operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| SCN | [SetAdvancedColorStroke](../../com.aspose.pdf.operators/setadvancedcolorstroke) | Set color operator (for stroking operations, ICCBasedand special colour spaces). |

### visit(SetAdvancedColor scn) {#visit-com.aspose.pdf.operators.SetAdvancedColor-}
```
public abstract void visit(SetAdvancedColor scn)
```


Visit/select scn operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| scn | [SetAdvancedColor](../../com.aspose.pdf.operators/setadvancedcolor) | Set color operator (for nonstroking operations, ICCBased and special colour spaces). |

### visit(ShFill sh) {#visit-com.aspose.pdf.operators.ShFill-}
```
public abstract void visit(ShFill sh)
```


Visit/select sh operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sh | [ShFill](../../com.aspose.pdf.operators/shfill) | Paint area defined by shading pattern operator. |

### visit(MoveToNextLine T_) {#visit-com.aspose.pdf.operators.MoveToNextLine-}
```
public abstract void visit(MoveToNextLine T_)
```


Visit/select T\* operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| T_ | [MoveToNextLine](../../com.aspose.pdf.operators/movetonextline) | Move to start of next text line operator. |

### visit(SetCharacterSpacing Tc) {#visit-com.aspose.pdf.operators.SetCharacterSpacing-}
```
public abstract void visit(SetCharacterSpacing Tc)
```


Visit/select Tc operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| Tc | [SetCharacterSpacing](../../com.aspose.pdf.operators/setcharacterspacing) | Set character spacing operator. |

### visit(MoveTextPosition Td) {#visit-com.aspose.pdf.operators.MoveTextPosition-}
```
public abstract void visit(MoveTextPosition Td)
```


Visit/select Td operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| Td | [MoveTextPosition](../../com.aspose.pdf.operators/movetextposition) | Move text position operator. |

### visit(CurveTo2 y) {#visit-com.aspose.pdf.operators.CurveTo2-}
```
public abstract void visit(CurveTo2 y)
```


Visit/select y operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| y | [CurveTo2](../../com.aspose.pdf.operators/curveto2) | Append curved segment to path operator (final point replicated). |

### visit(EOClip W_) {#visit-com.aspose.pdf.operators.EOClip-}
```
public abstract void visit(EOClip W_)
```


Visit/select W\* operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| W_ | [EOClip](../../com.aspose.pdf.operators/eoclip) | Set clipping path operator (even-odd rule). |

### visit(SetHorizontalTextScaling Tz) {#visit-com.aspose.pdf.operators.SetHorizontalTextScaling-}
```
public abstract void visit(SetHorizontalTextScaling Tz)
```


Visit/select Tz operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| Tz | [SetHorizontalTextScaling](../../com.aspose.pdf.operators/sethorizontaltextscaling) | Set horizontal text scaling operator. |

### visit(CurveTo1 v) {#visit-com.aspose.pdf.operators.CurveTo1-}
```
public abstract void visit(CurveTo1 v)
```


Visit/select v operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| v | [CurveTo1](../../com.aspose.pdf.operators/curveto1) | Append curved segment to path operator (initial point replicated). |

### visit(Clip W) {#visit-com.aspose.pdf.operators.Clip-}
```
public abstract void visit(Clip W)
```


Visit/select W operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| W | [Clip](../../com.aspose.pdf.operators/clip) | Set clipping path operator (nonzero winding number rule). |

### visit(SetLineWidth w) {#visit-com.aspose.pdf.operators.SetLineWidth-}
```
public abstract void visit(SetLineWidth w)
```


Visit/select w operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| w | [SetLineWidth](../../com.aspose.pdf.operators/setlinewidth) | Set line width operator. |

### visit(SetLineJoin j) {#visit-com.aspose.pdf.operators.SetLineJoin-}
```
public abstract void visit(SetLineJoin j)
```


Visit/select j operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| j | [SetLineJoin](../../com.aspose.pdf.operators/setlinejoin) | Set line join style operator. |

### visit(EX EX) {#visit-com.aspose.pdf.operators.EX-}
```
public abstract void visit(EX EX)
```


Visit/select EX operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| EX | [EX](../../com.aspose.pdf.operators/ex) | End compatibility section operator. |

### visit(ET ET) {#visit-com.aspose.pdf.operators.ET-}
```
public abstract void visit(ET ET)
```


Visit/select ET operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ET | [ET](../../com.aspose.pdf.operators/et) | End text object operator. |

### visit(EMC EMC) {#visit-com.aspose.pdf.operators.EMC-}
```
public abstract void visit(EMC EMC)
```


Visit/select EMC operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| EMC | [EMC](../../com.aspose.pdf.operators/emc) | End marked-content sequence operator. |

### visit(EI EI) {#visit-com.aspose.pdf.operators.EI-}
```
public abstract void visit(EI EI)
```


Visit/select EI operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| EI | [EI](../../com.aspose.pdf.operators/ei) | End inline image object operator. |

### visit(DP DP) {#visit-com.aspose.pdf.operators.DP-}
```
public abstract void visit(DP DP)
```


Visit/select DP operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| DP | [DP](../../com.aspose.pdf.operators/dp) | Define marked-content point operator (with property list). |

### visit(Do Do) {#visit-com.aspose.pdf.operators.Do-}
```
public abstract void visit(Do Do)
```


Visit/select Do operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| Do | [Do](../../com.aspose.pdf.operators/do) | Invoke named XObject operator. |

### visit(SetDash d) {#visit-com.aspose.pdf.operators.SetDash-}
```
public abstract void visit(SetDash d)
```


Visit/select d operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| d | [SetDash](../../com.aspose.pdf.operators/setdash) | Set line dash pattern operator. |

### visit(SetCharWidth d0) {#visit-com.aspose.pdf.operators.SetCharWidth-}
```
public abstract void visit(SetCharWidth d0)
```


Visit/select d0 operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| d0 | [SetCharWidth](../../com.aspose.pdf.operators/setcharwidth) | Set glyph width in Type 3 font operator. |

### visit(SetCharWidthBoundingBox d1) {#visit-com.aspose.pdf.operators.SetCharWidthBoundingBox-}
```
public abstract void visit(SetCharWidthBoundingBox d1)
```


Visit/select d1 operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| d1 | [SetCharWidthBoundingBox](../../com.aspose.pdf.operators/setcharwidthboundingbox) | Set glyph width and bounding box in Type 3 font operator. |

### visit(SetColorSpaceStroke CS) {#visit-com.aspose.pdf.operators.SetColorSpaceStroke-}
```
public abstract void visit(SetColorSpaceStroke CS)
```


Visit/select CS operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| CS | [SetColorSpaceStroke](../../com.aspose.pdf.operators/setcolorspacestroke) | Set color space operator (for stroking operations). |

### visit(SetColorSpace cs) {#visit-com.aspose.pdf.operators.SetColorSpace-}
```
public abstract void visit(SetColorSpace cs)
```


Visit/select cs operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cs | [SetColorSpace](../../com.aspose.pdf.operators/setcolorspace) | Set color space operator (for nonstroking operations). |

### visit(ConcatenateMatrix cm) {#visit-com.aspose.pdf.operators.ConcatenateMatrix-}
```
public abstract void visit(ConcatenateMatrix cm)
```


Visit/select cm operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cm | [ConcatenateMatrix](../../com.aspose.pdf.operators/concatenatematrix) | Concatenate matrix to current transformation matrix operator. |

### visit(CurveTo c) {#visit-com.aspose.pdf.operators.CurveTo-}
```
public abstract void visit(CurveTo c)
```


Visit/select c operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| c | [CurveTo](../../com.aspose.pdf.operators/curveto) | Append curved segment to path operator (three control points). |

### visit(BX BX) {#visit-com.aspose.pdf.operators.BX-}
```
public abstract void visit(BX BX)
```


Visit/select BX operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| BX | [BX](../../com.aspose.pdf.operators/bx) | Begin compatibility section operator. |

### visit(BT BT) {#visit-com.aspose.pdf.operators.BT-}
```
public abstract void visit(BT BT)
```


Visit/select BT operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| BT | [BT](../../com.aspose.pdf.operators/bt) | Begin text object operator. |

### visit(BMC BMC) {#visit-com.aspose.pdf.operators.BMC-}
```
public abstract void visit(BMC BMC)
```


Visit/select BMC operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| BMC | [BMC](../../com.aspose.pdf.operators/bmc) | Begin marked-content sequence operator. |

### visit(BI BI) {#visit-com.aspose.pdf.operators.BI-}
```
public abstract void visit(BI BI)
```


Visit/select BI operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| BI | [BI](../../com.aspose.pdf.operators/bi) | Begin inline image object operator. |

### visit(BDC BDC) {#visit-com.aspose.pdf.operators.BDC-}
```
public abstract void visit(BDC BDC)
```


Visit/select BDC operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| BDC | [BDC](../../com.aspose.pdf.operators/bdc) | Begin marked-content sequence operator (with property list). |

### visit(FillStroke B) {#visit-com.aspose.pdf.operators.FillStroke-}
```
public abstract void visit(FillStroke B)
```


Visit/select B operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| B | [FillStroke](../../com.aspose.pdf.operators/fillstroke) | Fill and stroke path operator (nonzero winding number rule). |

### visit(ClosePathFillStroke b) {#visit-com.aspose.pdf.operators.ClosePathFillStroke-}
```
public abstract void visit(ClosePathFillStroke b)
```


Visit/select b operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| b | [ClosePathFillStroke](../../com.aspose.pdf.operators/closepathfillstroke) | Close, fill, and stroke path operator (nonzero winding number rule). |

### visit(EOFillStroke B_) {#visit-com.aspose.pdf.operators.EOFillStroke-}
```
public abstract void visit(EOFillStroke B_)
```


Visit/select B\* operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| B_ | [EOFillStroke](../../com.aspose.pdf.operators/eofillstroke) | Fill and stroke path operator (even-odd rule). |

### visit(ClosePathEOFillStroke b_) {#visit-com.aspose.pdf.operators.ClosePathEOFillStroke-}
```
public abstract void visit(ClosePathEOFillStroke b_)
```


Visit/select b\* operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| b_ | [ClosePathEOFillStroke](../../com.aspose.pdf.operators/closepatheofillstroke) | Close, fill, and stroke path operator (even-odd rule). |

### visit(MoveToNextLineShowText value) {#visit-com.aspose.pdf.operators.MoveToNextLineShowText-}
```
public abstract void visit(MoveToNextLineShowText value)
```


Visit/select ' operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MoveToNextLineShowText](../../com.aspose.pdf.operators/movetonextlineshowtext) | Move to next line and show text operator. |

### visit(SetSpacingMoveToNextLineShowText value) {#visit-com.aspose.pdf.operators.SetSpacingMoveToNextLineShowText-}
```
public abstract void visit(SetSpacingMoveToNextLineShowText value)
```


Visit/select '' operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [SetSpacingMoveToNextLineShowText](../../com.aspose.pdf.operators/setspacingmovetonextlineshowtext) | Set word and character spacing, move to next line, and show text operator. |

### visit(TextOperator textOperator) {#visit-com.aspose.pdf.operators.TextOperator-}
```
public abstract void visit(TextOperator textOperator)
```


Visit/select any text operator operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| textOperator | [TextOperator](../../com.aspose.pdf.operators/textoperator) | General text operator which is used to select the set of corresponding pdf operators. |

