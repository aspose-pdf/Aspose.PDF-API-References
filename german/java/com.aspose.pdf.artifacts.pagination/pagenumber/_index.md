---
title: "PageNumber"
linktitle: "PageNumber"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt ein Seitenzahlenformat dar, das einen Index, die Gesamtseitenzahl und ein Trennzeichen enthält."
type: docs
weight: 150
url: /de/java/com.aspose.pdf.artifacts.pagination/pagenumber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.artifacts.pagination.PageNumber

```
public final class PageNumber extends Object
```

Stellt ein Seitenzahlenformat dar, das einen Index, die Gesamtseitenzahl und ein Trennzeichen enthält.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PageNumber](#PageNumber--) |  |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getDelimiter](#getDelimiter--) | Liest oder legt das Trennzeichen fest, das im Seitenzahlenformat verwendet wird. Die formatierte Zeichenkette wird basierend auf dem angegebenen Trennzeichen aktualisiert. |
| [getIndex](#getIndex--) | Liest oder legt die Seitenindex‑Komponente des Seitenzahlenformats fest. Die formatierte Zeichenkette enthält einen Platzhalter für den Seitenindex. |
| [getOffset](#getOffset--) | Liest oder legt den Versatz fest, der zum Seitenindex hinzugefügt wird. |
| [getPageNumberString](#getPageNumberString-int-int-) | Gibt eine formatierte Zeichenkette zurück, die die Seitenzahl basierend auf den aktuellen Einstellungen darstellt. |
| [getTotalNum](#getTotalNum--) | Liest oder legt die Gesamte‑Seiten‑Anzahl‑Komponente des Seitenzahlenformats fest. Die formatierte Zeichenkette enthält einen Platzhalter für die Gesamtzahl der Seiten. |
| [setDelimiter](#setDelimiter-java.lang.String-) | Liest oder legt das Trennzeichen fest, das im Seitenzahlenformat verwendet wird. Die formatierte Zeichenkette wird basierend auf dem angegebenen Trennzeichen aktualisiert. |
| [setIndex](#setIndex-com.aspose.pdf.artifacts.pagination.PageNumber.PageIndex-) | Liest oder legt die Seitenindex‑Komponente des Seitenzahlenformats fest. |
| [setOffset](#setOffset-int-) | Liest oder legt den Versatz fest, der zum Seitenindex hinzugefügt wird. |
| [setTotalNum](#setTotalNum-com.aspose.pdf.artifacts.pagination.PageNumber.PageTotalNum-) | Liest oder legt die Gesamte‑Seiten‑Anzahl‑Komponente des Seitenzahlenformats fest. |

### PageNumber {#PageNumber--}
```
public PageNumber()
```



### getDelimiter {#getDelimiter--}
```
public final String getDelimiter()
```

Liest oder legt das Trennzeichen fest, das im Seitenzahlenformat verwendet wird. Die formatierte Zeichenkette wird basierend auf dem angegebenen Trennzeichen aktualisiert.

**Returns:**
String Wert

### getIndex {#getIndex--}
```
public final PageNumber.PageIndex getIndex()
```

Liest oder legt die Seitenindex‑Komponente des Seitenzahlenformats fest. Die formatierte Zeichenkette enthält einen Platzhalter für den Seitenindex.

**Returns:**
PageIndex Instanz

### getOffset {#getOffset--}
```
public final int getOffset()
```

Liest oder legt den Versatz fest, der zum Seitenindex hinzugefügt wird.

**Returns:**
int-Wert

### getPageNumberString {#getPageNumberString-int-int-}
```
public final String getPageNumberString(int pageNumber, int count)
```

Gibt eine formatierte Zeichenkette zurück, die die Seitenzahl basierend auf den aktuellen Einstellungen darstellt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pageNumber |  | Die aktuelle Seitenzahl. |
| Anzahl |  | Die Gesamtzahl der Seiten. |

**Returns:**
Eine formatierte Seitenzahlzeichenkette.

### getTotalNum {#getTotalNum--}
```
public final PageNumber.PageTotalNum getTotalNum()
```

Liest oder legt die Gesamte‑Seiten‑Anzahl‑Komponente des Seitenzahlenformats fest. Die formatierte Zeichenkette enthält einen Platzhalter für die Gesamtzahl der Seiten.

**Returns:**
PageTotalNum Instanz

### setDelimiter {#setDelimiter-java.lang.String-}
Liest oder legt das Trennzeichen fest, das im Seitenzahlenformat verwendet wird. Die formatierte Zeichenkette wird basierend auf dem angegebenen Trennzeichen aktualisiert.

### setIndex {#setIndex-com.aspose.pdf.artifacts.pagination.PageNumber.PageIndex-}
Liest oder legt die Seitenindex‑Komponente des Seitenzahlenformats fest.

### setOffset {#setOffset-int-}
```
public final void setOffset(int value)
```

Liest oder legt den Versatz fest, der zum Seitenindex hinzugefügt wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert |

### setTotalNum {#setTotalNum-com.aspose.pdf.artifacts.pagination.PageNumber.PageTotalNum-}
Liest oder legt die Gesamte‑Seiten‑Anzahl‑Komponente des Seitenzahlenformats fest.
