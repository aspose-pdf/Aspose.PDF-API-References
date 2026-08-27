---
title: "BaseParagraph"
linktitle: "BaseParagraph"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt ein abstraktes Basiselement dar, das zur Seite hinzugefügt werden kann (doc.Paragraphs.Add())."
type: docs
weight: 280
url: /de/java/com.aspose.pdf/baseparagraph/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public abstract class BaseParagraph extends Object implements com.aspose.ms.System.ICloneable
```

Stellt ein abstraktes Basiselement dar, das zur Seite hinzugefügt werden kann (doc.Paragraphs.Add()).

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [BaseParagraph](#BaseParagraph--) |  |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [deepClone](#deepClone--) | Klont diese Instanz. Virtuelle Methode. Gibt immer null zurück. |
| [getHorizontalAlignment](#getHorizontalAlignment--) | Liefert eine horizontale Ausrichtung des Absatzes |
| [getHyperlink](#getHyperlink--) | / * / * Ruft ab oder legt fest, ob ein Absatz eine Fußnote ist. Standard ist false.(für PDF-Erstellung) / * / * |
| [getMargin](#getMargin--) | Liefert einen äußeren Rand für den Absatz (für PDF-Erstellung) |
| [getVerticalAlignment](#getVerticalAlignment--) | Liefert eine vertikale Ausrichtung des Absatzes |
| [getZIndex](#getZIndex--) | Liefert einen int-Wert, der die Z-Reihenfolge des Diagramms angibt. Ein Diagramm mit größerem ZIndex wird über einem Diagramm mit kleinerem ZIndex platziert. ZIndex kann negativ sein. Ein Diagramm mit negativem ZIndex wird hinter dem Text auf der Seite platziert. |
| [isFirstParagraphInColumn](#isFirstParagraphInColumn--) | Ruft ab oder legt einen bool-Wert fest, der angibt, ob dieser Absatz in die nächste Spalte gesetzt wird. Standard ist false.(für PDF-Erstellung) |
| [isInLineParagraph](#isInLineParagraph--) | Liefert, ob ein Absatz inline ist. Standard ist false.(für PDF-Erstellung) |
| [isInNewPage](#isInNewPage--) | Ruft einen bool-Wert ab, der erzwingt, dass dieser Absatz auf einer neuen Seite erzeugt wird. Standard ist false.(für PDF-Erstellung) |
| [isKeptWithNext](#isKeptWithNext--) | Liefert einen booleschen Wert, der angibt, ob der aktuelle Absatz zusammen mit dem nächsten Absatz auf derselben Seite bleibt. Standard ist false.(für PDF-Erstellung) |
| [setFirstParagraphInColumn](#setFirstParagraphInColumn-boolean-) | Ruft ab oder legt einen bool-Wert fest, der angibt, ob dieser Absatz in die nächste Spalte gesetzt wird. Standard ist false.(für PDF-Erstellung) |
| [setHorizontalAlignment](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | Setzt eine horizontale Ausrichtung des Absatzes |
| [setHyperlink](#setHyperlink-com.aspose.pdf.Hyperlink-) | Setzt einen Hyperlink (für PDF-Generator). |
| [setInLineParagraph](#setInLineParagraph-boolean-) | Setzt, dass ein Absatz inline ist. Standard ist false.(für PDF-Erstellung) |
| [setInNewPage](#setInNewPage-boolean-) | Setzt einen booleschen Wert, der erzwingt, dass dieser Absatz auf einer neuen Seite erzeugt wird. Standard ist false.(für PDF-Erstellung) |
| [setKeptWithNext](#setKeptWithNext-boolean-) | Setzt einen booleschen Wert, der angibt, ob der aktuelle Absatz zusammen mit dem nächsten Absatz auf derselben Seite bleibt. Standard ist false.(für PDF-Erstellung) |
| [setMargin](#setMargin-com.aspose.pdf.MarginInfo-) | Setzt einen äußeren Rand für den Absatz (für PDF-Erstellung) |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Setzt eine vertikale Ausrichtung des Absatzes |
| [setZIndex](#setZIndex-int-) | Setzt einen int-Wert, der die Z-Reihenfolge des Diagramms angibt. Ein Diagramm mit größerem ZIndex wird über einem Diagramm mit kleinerem ZIndex platziert. ZIndex kann negativ sein. Ein Diagramm mit negativem ZIndex wird hinter dem Text auf der Seite platziert. |

### BaseParagraph {#BaseParagraph--}
```
public BaseParagraph()
```



### deepClone {#deepClone--}
```
public Object deepClone()
```

Klont diese Instanz. Virtuelle Methode. Gibt immer null zurück.

**Returns:**
Null

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```

Liefert eine horizontale Ausrichtung des Absatzes

**Returns:**
HorizontalAlignment-Wert @see HorizontalAlignment

### getHyperlink {#getHyperlink--}
```
public Hyperlink getHyperlink()
```

/ * / * Ruft ab oder legt fest, ob ein Absatz eine Fußnote ist. Standard ist false.(für PDF-Erstellung) / * / *

**Returns:**
boolescher Wert /

### getMargin {#getMargin--}
```
public MarginInfo getMargin()
```

Liefert einen äußeren Rand für den Absatz (für PDF-Erstellung)

**Returns:**
MarginInfo-Wert

### getVerticalAlignment {#getVerticalAlignment--}
```
public VerticalAlignment getVerticalAlignment()
```

Liefert eine vertikale Ausrichtung des Absatzes

**Returns:**
VerticalAlignment Element @see VerticalAlignment

### getZIndex {#getZIndex--}
```
public int getZIndex()
```

Liefert einen int-Wert, der die Z-Reihenfolge des Diagramms angibt. Ein Diagramm mit größerem ZIndex wird über einem Diagramm mit kleinerem ZIndex platziert. ZIndex kann negativ sein. Ein Diagramm mit negativem ZIndex wird hinter dem Text auf der Seite platziert.

**Returns:**
int-Wert

### isFirstParagraphInColumn {#isFirstParagraphInColumn--}
```
public boolean isFirstParagraphInColumn()
```

Ruft ab oder legt einen bool-Wert fest, der angibt, ob dieser Absatz in die nächste Spalte gesetzt wird. Standard ist false.(für PDF-Erstellung)

**Returns:**
boolescher Wert

### isInLineParagraph {#isInLineParagraph--}
```
public boolean isInLineParagraph()
```

Liefert, ob ein Absatz inline ist. Standard ist false.(für PDF-Erstellung)

**Returns:**
boolescher Wert

### isInNewPage {#isInNewPage--}
```
public boolean isInNewPage()
```

Ruft einen bool-Wert ab, der erzwingt, dass dieser Absatz auf einer neuen Seite erzeugt wird. Standard ist false.(für PDF-Erstellung)

**Returns:**
boolescher Wert

### isKeptWithNext {#isKeptWithNext--}
```
public boolean isKeptWithNext()
```

Liefert einen booleschen Wert, der angibt, ob der aktuelle Absatz zusammen mit dem nächsten Absatz auf derselben Seite bleibt. Standard ist false.(für PDF-Erstellung)

**Returns:**
boolescher Wert

### setFirstParagraphInColumn {#setFirstParagraphInColumn-boolean-}
```
public void setFirstParagraphInColumn(boolean value)
```

Ruft ab oder legt einen bool-Wert fest, der angibt, ob dieser Absatz in die nächste Spalte gesetzt wird. Standard ist false.(für PDF-Erstellung)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setHorizontalAlignment {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
Setzt eine horizontale Ausrichtung des Absatzes

### setHyperlink {#setHyperlink-com.aspose.pdf.Hyperlink-}
Setzt einen Hyperlink (für PDF-Generator).

### setInLineParagraph {#setInLineParagraph-boolean-}
```
public void setInLineParagraph(boolean value)
```

Setzt, dass ein Absatz inline ist. Standard ist false.(für PDF-Erstellung)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setInNewPage {#setInNewPage-boolean-}
```
public void setInNewPage(boolean value)
```

Setzt einen booleschen Wert, der erzwingt, dass dieser Absatz auf einer neuen Seite erzeugt wird. Standard ist false.(für PDF-Erstellung)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setKeptWithNext {#setKeptWithNext-boolean-}
```
public final void setKeptWithNext(boolean value)
```

Setzt einen booleschen Wert, der angibt, ob der aktuelle Absatz zusammen mit dem nächsten Absatz auf derselben Seite bleibt. Standard ist false.(für PDF-Erstellung)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setMargin {#setMargin-com.aspose.pdf.MarginInfo-}
Setzt einen äußeren Rand für den Absatz (für PDF-Erstellung)

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
Setzt eine vertikale Ausrichtung des Absatzes

### setZIndex {#setZIndex-int-}
```
public void setZIndex(int value)
```

Setzt einen int-Wert, der die Z-Reihenfolge des Diagramms angibt. Ein Diagramm mit größerem ZIndex wird über einem Diagramm mit kleinerem ZIndex platziert. ZIndex kann negativ sein. Ein Diagramm mit negativem ZIndex wird hinter dem Text auf der Seite platziert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert |
