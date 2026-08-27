---
title: "Überschrift"
linktitle: "Überschrift"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt eine Überschrift dar."
type: docs
weight: 1890
url: /de/java/com.aspose.pdf/heading/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.TextFragment com.aspose.pdf.Heading, com.aspose.pdf.BaseParagraph, com.aspose.pdf.TextFragment com.aspose.pdf.Heading, com.aspose.pdf.TextFragment, com.aspose.pdf.Heading

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class Heading extends TextFragment
```

Stellt eine Überschrift dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Heading](#Heading--) | Nur für den internen Gebrauch. |
| [Heading](#Heading-int-) | Initialisiert eine neue Instanz der Cell-Klasse. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [cloneWithSegments](#cloneWithSegments--) | Kopiert die Überschrift mit allen Segmenten. |
| [deepClone](#deepClone--) | Kopiert die Überschrift. |
| [getDestinationPage](#getDestinationPage--) | Liefert die Zielseite. |
| [getLevel](#getLevel--) | Liefert die Ebene. |
| [getStartNumber](#getStartNumber--) | Liefert die Startnummer der Überschrift. |
| [getStyle](#getStyle--) | Liefert oder setzt den Stil. |
| [getTocPage](#getTocPage--) | Liefert die Seite, die diese Überschrift enthält. |
| [getTop](#getTop--) | Liefert das obere Y dieser Überschriften (zur internen Verwendung). |
| [getUserLabel](#getUserLabel--) | Liefert oder setzt das Benutzerlabel. |
| [isAutoSequence](#isAutoSequence--) | Liefert, ob die Überschrift automatisch nummeriert werden soll. |
| [isInList](#isInList--) | Liefert, ob die Überschrift in der Inhaltsliste stehen soll. |
| [setAutoSequence](#setAutoSequence-boolean-) | Setzt, ob die Überschrift automatisch nummeriert werden soll. |
| [setDestinationPage](#setDestinationPage-com.aspose.pdf.Page-) | Setzt die Zielseite. |
| [setInList](#setInList-boolean-) | Setzt, ob die Überschrift in der Inhaltsliste stehen soll. |
| [setLevel](#setLevel-int-) | Setzt die Ebene. |
| [setStartNumber](#setStartNumber-int-) | Liefert die Startnummer der Überschrift. Wert: Die startNumber. |
| [setStyle](#setStyle-com.aspose.pdf.NumberingStyle-) | Setzt oder setzt den Stil. |
| [setTocPage](#setTocPage-com.aspose.pdf.Page-) | Setzt die Seite, die diese Überschrift enthält. |
| [setTop](#setTop-double-) | Setzt das obere Y dieser Überschriften (zur internen Verwendung). |
| [setUserLabel](#setUserLabel-com.aspose.pdf.TextSegment-) | Liefert oder setzt das Benutzerlabel. |

### Heading {#Heading--}
```
public Heading()
```

Nur für den internen Gebrauch.

### Heading {#Heading-int-}
```
public Heading(int level)
```

Initialisiert eine neue Instanz der Cell-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Ebene |  | Die Ebene der Überschrift. |

### cloneWithSegments {#cloneWithSegments--}
```
public Object cloneWithSegments()
```

Kopiert die Überschrift mit allen Segmenten.

**Returns:**
Das geklonte Objekt

### deepClone {#deepClone--}
```
public Object deepClone()
```

Kopiert die Überschrift.

**Returns:**
Das geklonte Objekt

### getDestinationPage {#getDestinationPage--}
```
public Page getDestinationPage()
```

Liefert die Zielseite.

**Returns:**
Die Zielseite.

### getLevel {#getLevel--}
```
public int getLevel()
```

Liefert die Ebene.

**Returns:**
Die Überschriftenebene.

### getStartNumber {#getStartNumber--}
```
public int getStartNumber()
```

Liefert die Startnummer der Überschrift.

**Returns:**
Wert: Die startNumber.

### getStyle {#getStyle--}
```
public NumberingStyle getStyle()
```

Liefert oder setzt den Stil.

**Returns:**
Der Überschriftsstil.

### getTocPage {#getTocPage--}
```
public Page getTocPage()
```

Liefert die Seite, die diese Überschrift enthält.

**Returns:**
Die Seite.

### getTop {#getTop--}
```
public double getTop()
```

Liefert das obere Y dieser Überschriften (zur internen Verwendung).

**Returns:**
Der obere Y-Wert.

### getUserLabel {#getUserLabel--}
```
public TextSegment getUserLabel()
```

Liefert oder setzt das Benutzerlabel.

**Returns:**
TextSegment-Objekt.

### isAutoSequence {#isAutoSequence--}
```
public boolean isAutoSequence()
```

Liefert, ob die Überschrift automatisch nummeriert werden soll.

**Returns:**
Das IsAutoSequens.

### isInList {#isInList--}
```
public boolean isInList()
```

Liefert, ob die Überschrift in der Inhaltsliste stehen soll.

**Returns:**
Das IsInList.

### setAutoSequence {#setAutoSequence-boolean-}
```
public void setAutoSequence(boolean value)
```

Setzt, ob die Überschrift automatisch nummeriert werden soll.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | Das IsAutoSequens. |

### setDestinationPage {#setDestinationPage-com.aspose.pdf.Page-}
Setzt die Zielseite.

### setInList {#setInList-boolean-}
```
public void setInList(boolean value)
```

Setzt, ob die Überschrift in der Inhaltsliste stehen soll.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | Das IsInList. |

### setLevel {#setLevel-int-}
```
public void setLevel(int value)
```

Setzt die Ebene.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | Die Überschriftenebene. |

### setStartNumber {#setStartNumber-int-}
```
public void setStartNumber(int value)
```

Liefert die Startnummer der Überschrift. Wert: Die startNumber.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | Die startNumber. |

### setStyle {#setStyle-com.aspose.pdf.NumberingStyle-}
Setzt oder setzt den Stil.

### setTocPage {#setTocPage-com.aspose.pdf.Page-}
Setzt die Seite, die diese Überschrift enthält.

### setTop {#setTop-double-}
```
public void setTop(double value)
```

Setzt das obere Y dieser Überschriften (zur internen Verwendung).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | Der obere Y-Wert. |

### setUserLabel {#setUserLabel-com.aspose.pdf.TextSegment-}
Liefert oder setzt das Benutzerlabel.
