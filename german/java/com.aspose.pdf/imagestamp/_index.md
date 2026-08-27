---
title: "ImageStamp"
linktitle: "ImageStamp"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt einen grafischen Stempel dar."
type: docs
weight: 2360
url: /de/java/com.aspose.pdf/imagestamp/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Stamp com.aspose.pdf.ImageStamp, com.aspose.pdf.Stamp, com.aspose.pdf.ImageStamp

```
public final class ImageStamp extends Stamp
```

Stellt einen grafischen Stempel dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ImageStamp](#ImageStamp-java.io.InputStream-) | Initialisiert eine neue Instanz der {@code ImageStamp}-Klasse. |
| [ImageStamp](#ImageStamp-java.lang.String-) | Erstellt einen Bildstempel aus dem Bild in der angegebenen Datei. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [close](#close--) | Schließt diese Instanz. |
| [getAlternativeText](#getAlternativeText--) | Liefert den Alternativtext für den Bildstempel. |
| [getHeight](#getHeight--) | Liefert die Bildhöhe. Das Festlegen dieses Bildes ermöglicht das vertikale Skalieren des Bildes. |
| [getImage](#getImage--) | Liefert den Bildstrom, der für das Stempeln verwendet wird. |
| [getQuality](#getQuality--) | Liefert die Qualität des Bildstempels in Prozent. Gültige Werte sind 0..100%. |
| [getWidth](#getWidth--) | Liefert die Bildbreite. Das Festlegen dieser Eigenschaft ermöglicht das horizontale Skalieren des Bildes. |
| [getXIndent](#getXIndent--) | Liefert und setzt die horizontale Stempelkoordinate, beginnend von links. |
| [getYIndent](#getYIndent--) | Liefert und setzt die vertikale Stempelkoordinate, beginnend vom Boden. |
| [put](#put-com.aspose.pdf.Page-) | Fügt einen grafischen Stempel auf der Seite hinzu. |
| [setAlternativeText](#setAlternativeText-java.lang.String-) | Setzt den Alternativtext für den Bildstempel. |
| [setHeight](#setHeight-double-) | Setzt die Bildhöhe. Das Festlegen dieses Bildes ermöglicht das vertikale Skalieren des Bildes. |
| [setQuality](#setQuality-int-) | Setzt die Qualität des Bildstempels in Prozent. Gültige Werte sind 0..100%. |
| [setWidth](#setWidth-double-) | Setzt die Bildbreite. Das Festlegen dieser Eigenschaft ermöglicht das horizontale Skalieren des Bildes. |
| [setXIndent](#setXIndent-double-) | Liefert und setzt die horizontale Stempelkoordinate, beginnend von links. |
| [setYIndent](#setYIndent-double-) | Liefert und setzt die vertikale Stempelkoordinate, beginnend vom Boden. |

### ImageStamp {#ImageStamp-java.io.InputStream-}
Initialisiert eine neue Instanz der {@code ImageStamp}-Klasse.

### ImageStamp {#ImageStamp-java.lang.String-}
Erstellt einen Bildstempel aus dem Bild in der angegebenen Datei.

### close {#close--}
```
public void close()
```

Schließt diese Instanz.

### getAlternativeText {#getAlternativeText--}
```
public final String getAlternativeText()
```

Liefert den Alternativtext für den Bildstempel.

**Returns:**
String Wert

### getHeight {#getHeight--}
```
public double getHeight()
```

Liefert die Bildhöhe. Das Festlegen dieses Bildes ermöglicht das vertikale Skalieren des Bildes.

**Returns:**
double-Wert

### getImage {#getImage--}
```
public InputStream getImage()
```

Liefert den Bildstrom, der für das Stempeln verwendet wird.

**Returns:**
InputStream‑Objekt

### getQuality {#getQuality--}
```
public int getQuality()
```

Liefert die Qualität des Bildstempels in Prozent. Gültige Werte sind 0..100%.

**Returns:**
int-Wert

### getWidth {#getWidth--}
```
public double getWidth()
```

Liefert die Bildbreite. Das Festlegen dieser Eigenschaft ermöglicht das horizontale Skalieren des Bildes.

**Returns:**
double-Wert

### getXIndent {#getXIndent--}
```
public double getXIndent()
```

Liefert und setzt die horizontale Stempelkoordinate, beginnend von links.

**Returns:**
double-Wert

### getYIndent {#getYIndent--}
```
public double getYIndent()
```

Liefert und setzt die vertikale Stempelkoordinate, beginnend vom Boden.

**Returns:**
double-Wert

### put {#put-com.aspose.pdf.Page-}
Fügt einen grafischen Stempel auf der Seite hinzu.

### setAlternativeText {#setAlternativeText-java.lang.String-}
Setzt den Alternativtext für den Bildstempel.

### setHeight {#setHeight-double-}
```
public void setHeight(double value)
```

Setzt die Bildhöhe. Das Festlegen dieses Bildes ermöglicht das vertikale Skalieren des Bildes.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | double-Wert |

### setQuality {#setQuality-int-}
```
public void setQuality(int value)
```

Setzt die Qualität des Bildstempels in Prozent. Gültige Werte sind 0..100%.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert |

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

Setzt die Bildbreite. Das Festlegen dieser Eigenschaft ermöglicht das horizontale Skalieren des Bildes.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | double-Wert |

### setXIndent {#setXIndent-double-}
```
public void setXIndent(double value)
```

Liefert und setzt die horizontale Stempelkoordinate, beginnend von links.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | double-Wert |

### setYIndent {#setYIndent-double-}
```
public void setYIndent(double value)
```

Liefert und setzt die vertikale Stempelkoordinate, beginnend vom Boden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | double-Wert |
