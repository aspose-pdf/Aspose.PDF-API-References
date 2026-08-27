---
title: "PageNumberStamp"
linktitle: "PageNumberStamp"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Klasse, die die Größe einer Seite in einem PDF‑Dokument darstellt."
type: docs
weight: 3440
url: /de/java/com.aspose.pdf/pagenumberstamp/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Stamp com.aspose.pdf.TextStamp com.aspose.pdf.PageNumberStamp, com.aspose.pdf.Stamp, com.aspose.pdf.TextStamp com.aspose.pdf.PageNumberStamp, com.aspose.pdf.TextStamp, com.aspose.pdf.PageNumberStamp

```
public final class PageNumberStamp extends TextStamp
```

Klasse, die die Größe einer Seite in einem PDF‑Dokument darstellt.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PageNumberStamp](#PageNumberStamp--) | Initialisiert eine neue Instanz der {@code PageNumberStamp}-Klasse. Das Format ist auf "#" gesetzt. |
| [PageNumberStamp](#PageNumberStamp-com.aspose.pdf.facades.FormattedText-) | Initialisiert eine neue Instanz der {@code PageNumberStamp}-Klasse. Das Format ist auf "#" gesetzt. |
| [PageNumberStamp](#PageNumberStamp-java.lang.String-) | Initialisiert eine neue Instanz der {@code PageNumberStamp}-Klasse. Das Format ist auf "#" gesetzt. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getFormat](#getFormat--) | Liefert den String‑Wert zum Stempeln von Seitenzahlen. Der Wert muss das Zeichen '#' enthalten, das im Stempelvorgang durch die Seitenzahl ersetzt wird. |
| [getNumberingStyle](#getNumberingStyle--) | Nummerierungsstil, der von diesem Stempel verwendet wird. |
| [getStartingNumber](#getStartingNumber--) | Ermittelt den Wert der Nummer der Startseite. Andere Seiten werden ab diesem Wert nummeriert. |
| [put](#put-com.aspose.pdf.Page-) | Fügt Seitenzahl hinzu. |
| [setFormat](#setFormat-java.lang.String-) | Setzt den String‑Wert für das Stempeln von Seitenzahlen. Der Wert muss das Zeichen ‘#’ enthalten, das im Stempelvorgang durch die Seitenzahl ersetzt wird. |
| [setNumberingStyle](#setNumberingStyle-com.aspose.pdf.NumberingStyle-) | Nummerierungsstil, der von diesem Stempel verwendet wird. |
| [setStartingNumber](#setStartingNumber-int-) | Setzt den Wert der Nummer der Startseite. Andere Seiten werden ab diesem Wert nummeriert. |

### PageNumberStamp {#PageNumberStamp--}
```
public PageNumberStamp()
```

Initialisiert eine neue Instanz der {@code PageNumberStamp}-Klasse. Das Format ist auf "#" gesetzt.

### PageNumberStamp {#PageNumberStamp-com.aspose.pdf.facades.FormattedText-}
Initialisiert eine neue Instanz der {@code PageNumberStamp}-Klasse. Das Format ist auf "#" gesetzt.

### PageNumberStamp {#PageNumberStamp-java.lang.String-}
Initialisiert eine neue Instanz der {@code PageNumberStamp}-Klasse. Das Format ist auf "#" gesetzt.

### getFormat {#getFormat--}
```
public String getFormat()
```

Liefert den String‑Wert zum Stempeln von Seitenzahlen. Der Wert muss das Zeichen '#' enthalten, das im Stempelvorgang durch die Seitenzahl ersetzt wird.

**Returns:**
String Wert

### getNumberingStyle {#getNumberingStyle--}
```
public NumberingStyle getNumberingStyle()
```

Nummerierungsstil, der von diesem Stempel verwendet wird.

**Returns:**
NumberingStyle‑Wert @see NumberingStyle

### getStartingNumber {#getStartingNumber--}
```
public int getStartingNumber()
```

Ermittelt den Wert der Nummer der Startseite. Andere Seiten werden ab diesem Wert nummeriert.

**Returns:**
int-Wert

### put {#put-com.aspose.pdf.Page-}
Fügt Seitenzahl hinzu.

### setFormat {#setFormat-java.lang.String-}
Setzt den String‑Wert für das Stempeln von Seitenzahlen. Der Wert muss das Zeichen ‘#’ enthalten, das im Stempelvorgang durch die Seitenzahl ersetzt wird.

### setNumberingStyle {#setNumberingStyle-com.aspose.pdf.NumberingStyle-}
Nummerierungsstil, der von diesem Stempel verwendet wird.

### setStartingNumber {#setStartingNumber-int-}
```
public void setStartingNumber(int value)
```

Setzt den Wert der Nummer der Startseite. Andere Seiten werden ab diesem Wert nummeriert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert |
