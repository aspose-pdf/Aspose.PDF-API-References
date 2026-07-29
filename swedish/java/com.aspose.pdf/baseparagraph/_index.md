---
title: "BaseParagraph"
linktitle: "BaseParagraph"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar ett abstrakt basobjekt som kan läggas till på sidan (doc.Paragraphs.Add())."
type: docs
weight: 280
url: /sv/java/com.aspose.pdf/baseparagraph/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public abstract class BaseParagraph extends Object implements com.aspose.ms.System.ICloneable
```

Representerar ett abstrakt basobjekt som kan läggas till på sidan (doc.Paragraphs.Add()).

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [BaseParagraph](#BaseParagraph--) |  |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [deepClone](#deepClone--) | Klonar denna instans. Virtuell metod. Returnerar alltid null. |
| [getHorizontalAlignment](#getHorizontalAlignment--) | Hämtar en horisontell justering av stycket |
| [getHyperlink](#getHyperlink--) | / * / * Hämtar eller anger ett stycke är en fotnot. Standard är false.(för pdf-generering) / * / * |
| [getMargin](#getMargin--) | Hämtar en yttre marginal för stycket (för pdf-generering) |
| [getVerticalAlignment](#getVerticalAlignment--) | Hämtar en vertikal justering av stycket |
| [getZIndex](#getZIndex--) | Hämtar ett int‑värde som anger Z‑ordningen för grafen. En graf med större ZIndex placeras ovanför grafen med mindre ZIndex. ZIndex kan vara negativt. En graf med negativ ZIndex placeras bakom texten på sidan. |
| [isFirstParagraphInColumn](#isFirstParagraphInColumn--) | Hämtar eller anger ett bool‑värde som indikerar om detta stycke ska vara i nästa kolumn. Standard är false.(för pdf-generering) |
| [isInLineParagraph](#isInLineParagraph--) | Hämtar om ett stycke är inline. Standard är false.(för pdf-generering) |
| [isInNewPage](#isInNewPage--) | Hämtar ett bool‑värde som tvingar detta stycke att genereras på en ny sida. Standard är false.(för pdf-generering) |
| [isKeptWithNext](#isKeptWithNext--) | Hämtar ett bool‑värde som indikerar om aktuellt stycke förblir på samma sida tillsammans med nästa stycke. Standard är false.(för pdf-generering) |
| [setFirstParagraphInColumn](#setFirstParagraphInColumn-boolean-) | Hämtar eller anger ett bool‑värde som indikerar om detta stycke ska vara i nästa kolumn. Standard är false.(för pdf-generering) |
| [setHorizontalAlignment](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | Anger en horisontell justering av stycket |
| [setHyperlink](#setHyperlink-com.aspose.pdf.Hyperlink-) | Anger hyperlänk (för pdf‑generator). |
| [setInLineParagraph](#setInLineParagraph-boolean-) | Anger att ett stycke är inline. Standard är false.(för pdf-generering) |
| [setInNewPage](#setInNewPage-boolean-) | Anger ett bool‑värde som tvingar detta stycke att genereras på en ny sida. Standard är false.(för pdf-generering) |
| [setKeptWithNext](#setKeptWithNext-boolean-) | Anger ett bool‑värde som indikerar om aktuellt stycke förblir på samma sida tillsammans med nästa stycke. Standard är false.(för pdf-generering) |
| [setMargin](#setMargin-com.aspose.pdf.MarginInfo-) | Anger en yttre marginal för stycket (för pdf-generering) |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Anger en vertikal justering av stycket |
| [setZIndex](#setZIndex-int-) | Anger ett int‑värde som anger Z‑ordningen för grafen. En graf med större ZIndex placeras ovanför grafen med mindre ZIndex. ZIndex kan vara negativt. En graf med negativ ZIndex placeras bakom texten på sidan. |

### BaseParagraph {#BaseParagraph--}
```
public BaseParagraph()
```



### deepClone {#deepClone--}
```
public Object deepClone()
```

Klonar denna instans. Virtuell metod. Returnerar alltid null.

**Returns:**
Null

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```

Hämtar en horisontell justering av stycket

**Returns:**
HorizontalAlignment‑värde @see HorizontalAlignment

### getHyperlink {#getHyperlink--}
```
public Hyperlink getHyperlink()
```

/ * / * Hämtar eller anger ett stycke är en fotnot. Standard är false.(för pdf-generering) / * / *

**Returns:**
bool‑värde /

### getMargin {#getMargin--}
```
public MarginInfo getMargin()
```

Hämtar en yttre marginal för stycket (för pdf-generering)

**Returns:**
MarginInfo‑värde

### getVerticalAlignment {#getVerticalAlignment--}
```
public VerticalAlignment getVerticalAlignment()
```

Hämtar en vertikal justering av stycket

**Returns:**
VerticalAlignment-element @see VerticalAlignment

### getZIndex {#getZIndex--}
```
public int getZIndex()
```

Hämtar ett int‑värde som anger Z‑ordningen för grafen. En graf med större ZIndex placeras ovanför grafen med mindre ZIndex. ZIndex kan vara negativt. En graf med negativ ZIndex placeras bakom texten på sidan.

**Returns:**
int‑värde

### isFirstParagraphInColumn {#isFirstParagraphInColumn--}
```
public boolean isFirstParagraphInColumn()
```

Hämtar eller anger ett bool‑värde som indikerar om detta stycke ska vara i nästa kolumn. Standard är false.(för pdf-generering)

**Returns:**
booleskt värde

### isInLineParagraph {#isInLineParagraph--}
```
public boolean isInLineParagraph()
```

Hämtar om ett stycke är inline. Standard är false.(för pdf-generering)

**Returns:**
booleskt värde

### isInNewPage {#isInNewPage--}
```
public boolean isInNewPage()
```

Hämtar ett bool‑värde som tvingar detta stycke att genereras på en ny sida. Standard är false.(för pdf-generering)

**Returns:**
booleskt värde

### isKeptWithNext {#isKeptWithNext--}
```
public boolean isKeptWithNext()
```

Hämtar ett bool‑värde som indikerar om aktuellt stycke förblir på samma sida tillsammans med nästa stycke. Standard är false.(för pdf-generering)

**Returns:**
booleskt värde

### setFirstParagraphInColumn {#setFirstParagraphInColumn-boolean-}
```
public void setFirstParagraphInColumn(boolean value)
```

Hämtar eller anger ett bool‑värde som indikerar om detta stycke ska vara i nästa kolumn. Standard är false.(för pdf-generering)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setHorizontalAlignment {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
Anger en horisontell justering av stycket

### setHyperlink {#setHyperlink-com.aspose.pdf.Hyperlink-}
Anger hyperlänk (för pdf‑generator).

### setInLineParagraph {#setInLineParagraph-boolean-}
```
public void setInLineParagraph(boolean value)
```

Anger att ett stycke är inline. Standard är false.(för pdf-generering)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setInNewPage {#setInNewPage-boolean-}
```
public void setInNewPage(boolean value)
```

Anger ett bool‑värde som tvingar detta stycke att genereras på en ny sida. Standard är false.(för pdf-generering)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setKeptWithNext {#setKeptWithNext-boolean-}
```
public final void setKeptWithNext(boolean value)
```

Anger ett bool‑värde som indikerar om aktuellt stycke förblir på samma sida tillsammans med nästa stycke. Standard är false.(för pdf-generering)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setMargin {#setMargin-com.aspose.pdf.MarginInfo-}
Anger en yttre marginal för stycket (för pdf-generering)

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
Anger en vertikal justering av stycket

### setZIndex {#setZIndex-int-}
```
public void setZIndex(int value)
```

Anger ett int‑värde som anger Z‑ordningen för grafen. En graf med större ZIndex placeras ovanför grafen med mindre ZIndex. ZIndex kan vara negativt. En graf med negativ ZIndex placeras bakom texten på sidan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde |
