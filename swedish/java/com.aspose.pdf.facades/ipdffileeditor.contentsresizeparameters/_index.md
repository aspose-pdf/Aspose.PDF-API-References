---
title: "IPdfFileEditor.ContentsResizeParameters"
linktitle: "IPdfFileEditor.ContentsResizeParameters"
second_title: "Aspose.PDF för Java API-referens"
description: "Klass för att specificera parametrar för sidändring. Tillåter att ställa in följande parametrar: Storlek på resultatsidan (bredd, höjd) i standardenheter eller i procent av ursprungssidorna."
type: docs
weight: 300
url: /sv/java/com.aspose.pdf.facades/ipdffileeditor.contentsresizeparameters/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters

```
public static class IPdfFileEditor.ContentsResizeParameters extends Object
```

Klass för att specificera sidändringsparametrar. Tillåter att ställa in följande parametrar: Storlek på resultatsidan (bredd, höjd) i standardenhetsmått eller i procent av den ursprungliga sidans storlek; Vänster-, topp-, botten- och högermarginaler i standardenhetsmått eller i procent av den ursprungliga sidans storlek; Vissa värden kan lämnas null för automatisk beräkning. Dessa värden beräknas från återstående sidstorlek efter beräkning av explicit angivna värden. Till exempel: om sidbredd = 100 och ny sidbredd anges till 60 enheter så beräknas vänster- och högermarginaler automatiskt: (100 - 60) / 2 = 15. Denna klass används i metoden ResizeContents.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [ContentsResizeParameters](#ContentsResizeParameters--) | Skapar ändringsparametrar där alla värden är satta till \"auto\". Senare kan marginaler och innehållsstorlek specificeras om det behövs. |
| [ContentsResizeParameters](#ContentsResizeParameters-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | Skapar ändringsparametrar där alla värden är satta till \"auto\". Senare kan marginaler och innehållsstorlek specificeras om det behövs. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [contentSize](#contentSize-double-double-) | Skapar ändringsparametrar med specificerad innehållsstorlek. |
| [contentSizePercent](#contentSizePercent-double-double-) | Skapar ändringsparametrar med specificerad innehållsstorlek i procent av den ursprungliga sidstorleken. Marginaler beräknas automatiskt. |
| [getBottomMargin](#getBottomMargin--) | Hämtar eller anger bottenmarginal på den resulterande sidan. |
| [getContentsHeight](#getContentsHeight--) | Hämtar eller anger höjden på innehållet från källsidan på den resulterande sidan. |
| [getContentsWidth](#getContentsWidth--) | Hämtar eller anger bredden på innehållet från källsidan på den resulterande sidan. |
| [getLeftMargin](#getLeftMargin--) | Hämtar eller anger vänstermarginal på den resulterande sidan. |
| [getRightMargin](#getRightMargin--) | Hämtar eller anger högermarginal på den resulterande sidan. |
| [getTopMargin](#getTopMargin--) | Hämtar eller anger övre marginal på den resulterande sidan. |
| [isChangeMediaBox](#isChangeMediaBox--) | Hämtar om MediaBox för en PDF-sida ska justeras under ändringsoperationen. Standardvärdet är {@code false}. Att sätta denna parameter möjliggör att anpassa MediaBox till CropBox-värdet under ändring. |
| [margins](#margins-double-double-double-double-) | Skapar storleksändringsparametrar med specificerat marginalvärde. Innehållsstorleken beräknas automatiskt. |
| [marginsPercent](#marginsPercent-double-double-double-double-) | Skapar storleksändringsparametrar. Marginalerna specificeras i procent av den ursprungliga sidans storlek. |
| [pageResize](#pageResize-double-double-) | Skapar storleksändringsparametrar för sidändring. |
| [pageResizePct](#pageResizePct-double-double-) | Skapar storleksändringsparametrar för sidändring. Nya storlekar specificeras i procent. |
| [setBottomMargin](#setBottomMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | Hämtar eller anger bottenmarginal på den resulterande sidan. |
| [setChangeMediaBox](#setChangeMediaBox-boolean-) | Anger om MediaBox för en PDF-sida ska justeras under storleksändringsoperationen. Standardvärdet är {@code false}. Att ställa in denna parameter möjliggör att anpassa MediaBox till CropBox-värdet under storleksändring. |
| [setContentsHeight](#setContentsHeight-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | Hämtar eller anger höjden på innehållet från källsidan på den resulterande sidan. |
| [setContentsWidth](#setContentsWidth-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | Hämtar eller anger bredden på innehållet från källsidan på den resulterande sidan. |
| [setLeftMargin](#setLeftMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | Hämtar eller anger vänstermarginal på den resulterande sidan. |
| [setRightMargin](#setRightMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | Hämtar eller anger högermarginal på den resulterande sidan. |
| [setTopMargin](#setTopMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | Hämtar eller anger övre marginal på den resulterande sidan. |

### ContentsResizeParameters {#ContentsResizeParameters--}
```
public ContentsResizeParameters()
```

Skapar ändringsparametrar där alla värden är satta till \"auto\". Senare kan marginaler och innehållsstorlek specificeras om det behövs.

### ContentsResizeParameters {#ContentsResizeParameters-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
Skapar ändringsparametrar där alla värden är satta till \"auto\". Senare kan marginaler och innehållsstorlek specificeras om det behövs.

### contentSize {#contentSize-double-double-}
```
public static IPdfFileEditor.ContentsResizeParameters contentSize(double width, double height)
```

Skapar ändringsparametrar med specificerad innehållsstorlek.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bredd |  | Ny bredd på innehållet. |
| höjd |  | Ny höjd på innehållet. |

**Returns:**
Returnerar nya storleksändringsparametrar.

### contentSizePercent {#contentSizePercent-double-double-}
```
public static IPdfFileEditor.ContentsResizeParameters contentSizePercent(double width, double height)
```

Skapar ändringsparametrar med specificerad innehållsstorlek i procent av den ursprungliga sidstorleken. Marginaler beräknas automatiskt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bredd |  | Ny innehållsbredd i procent. |
| höjd |  | Ny innehållshöjd i procent. |

**Returns:**
Nya storleksändringsparametrar.

### getBottomMargin {#getBottomMargin--}
```
public IPdfFileEditor.ContentsResizeValue getBottomMargin()
```

Hämtar eller anger bottenmarginal på den resulterande sidan.

**Returns:**
ContentsResizeValue-objekt

### getContentsHeight {#getContentsHeight--}
```
public IPdfFileEditor.ContentsResizeValue getContentsHeight()
```

Hämtar eller anger höjden på innehållet från källsidan på den resulterande sidan.

**Returns:**
ContentsResizeValue-objekt

### getContentsWidth {#getContentsWidth--}
```
public IPdfFileEditor.ContentsResizeValue getContentsWidth()
```

Hämtar eller anger bredden på innehållet från källsidan på den resulterande sidan.

**Returns:**
ContentsResizeValue-objekt

### getLeftMargin {#getLeftMargin--}
```
public IPdfFileEditor.ContentsResizeValue getLeftMargin()
```

Hämtar eller anger vänstermarginal på den resulterande sidan.

**Returns:**
ContentsResizeValue-objekt

### getRightMargin {#getRightMargin--}
```
public IPdfFileEditor.ContentsResizeValue getRightMargin()
```

Hämtar eller anger högermarginal på den resulterande sidan.

**Returns:**
ContentsResizeValue-objekt

### getTopMargin {#getTopMargin--}
```
public IPdfFileEditor.ContentsResizeValue getTopMargin()
```

Hämtar eller anger övre marginal på den resulterande sidan.

**Returns:**
ContentsResizeValue-objekt

### isChangeMediaBox {#isChangeMediaBox--}
```
public final boolean isChangeMediaBox()
```

Hämtar om MediaBox för en PDF-sida ska justeras under ändringsoperationen. Standardvärdet är {@code false}. Att sätta denna parameter möjliggör att anpassa MediaBox till CropBox-värdet under ändring.

**Returns:**
om MediaBox för en PDF-sida ska justeras under storleksändringsoperationen.

### margins {#margins-double-double-double-double-}
```
public static IPdfFileEditor.ContentsResizeParameters margins(double left, double right, double top, double bottom)
```

Skapar storleksändringsparametrar med specificerat marginalvärde. Innehållsstorleken beräknas automatiskt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| vänster |  | Vänster marginal. |
| höger |  | Höger marginal. |
| övre |  | Övre marginal. |
| nedre |  | Nedre marginal. |

**Returns:**
Skapade storleksändringsparametrar.

### marginsPercent {#marginsPercent-double-double-double-double-}
```
public static IPdfFileEditor.ContentsResizeParameters marginsPercent(double left, double right, double top, double bottom)
```

Skapar storleksändringsparametrar. Marginalerna specificeras i procent av den ursprungliga sidans storlek.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| vänster |  | Vänster marginal (i procent av sidbredden). |
| höger |  | Höger marginal (i procent av sidhöjden). |
| övre |  | Övre marginal (i procent av sidhöjden). |
| nedre |  | Nedre marginal (i procent av sidhöjden). |

**Returns:**
Returnerar nya storleksändringsparametrar.

### pageResize {#pageResize-double-double-}
```
public static IPdfFileEditor.ContentsResizeParameters pageResize(double width, double height)
```

Skapar storleksändringsparametrar för sidändring.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bredd |  | Ny sidbredd i enheter. |
| höjd |  | Ny sidhöjd i enheter. |

**Returns:**
Nya storleksändringsparametrar.

### pageResizePct {#pageResizePct-double-double-}
```
public IPdfFileEditor.ContentsResizeParameters pageResizePct(double widthPct, double heightPct)
```

Skapar storleksändringsparametrar för sidändring. Nya storlekar specificeras i procent.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| widthPct |  | Ny sidbredd i procent. |
| heightPct |  | Ny sidhöjd i procent. |

**Returns:**
Nya storleksändringsparametrar.

### setBottomMargin {#setBottomMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
Hämtar eller anger bottenmarginal på den resulterande sidan.

### setChangeMediaBox {#setChangeMediaBox-boolean-}
```
public final void setChangeMediaBox(boolean value)
```

Anger om MediaBox för en PDF-sida ska justeras under storleksändringsoperationen. Standardvärdet är {@code false}. Att ställa in denna parameter möjliggör att anpassa MediaBox till CropBox-värdet under storleksändring.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | om MediaBox för en PDF-sida ska justeras under storleksändringsoperationen. |

### setContentsHeight {#setContentsHeight-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
Hämtar eller anger höjden på innehållet från källsidan på den resulterande sidan.

### setContentsWidth {#setContentsWidth-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
Hämtar eller anger bredden på innehållet från källsidan på den resulterande sidan.

### setLeftMargin {#setLeftMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
Hämtar eller anger vänstermarginal på den resulterande sidan.

### setRightMargin {#setRightMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
Hämtar eller anger högermarginal på den resulterande sidan.

### setTopMargin {#setTopMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
Hämtar eller anger övre marginal på den resulterande sidan.
