---
title: "ImagesDifference"
linktitle: "ImagesDifference"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt die Ergebnis-Klasse des Vergleichs zweier PDF-Seiten bereit."
type: docs
weight: 20
url: /de/java/com.aspose.pdf.comparison.graphicalcomparison/imagesdifference/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.comparison.graphicalcomparison.ImagesDifference

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable

```
public final class ImagesDifference extends Object implements com.aspose.ms.System.IDisposable
```

Stellt die Ergebnis-Klasse des Vergleichs zweier PDF-Seiten bereit.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [differenceToImage](#differenceToImage-com.aspose.pdf.Color-com.aspose.pdf.Color-) | Konvertiert das Differenzarray in ein Bitmap-Bild unter Verwendung der angegebenen Farben. |
| [dispose](#dispose--) | Führt alle erforderlichen Aufräumoperationen aus, bevor das Objekt zerstört wird. |
| [getDestinationImage](#getDestinationImage--) | Gibt ein neues Bitmap zurück, das das Zielbild darstellt, indem das Differenzarray auf das Quellbild angewendet wird. |
| [getDifference](#getDifference--) | Liefert das Differenzarray. Dieses Array ähnelt dem ursprünglichen Bilddatenarray, das als Ergebnis der LockBits-Methode erhalten wurde. |
| [getHeight](#getHeight--) | Die Höhe der Differenz. |
| [getSourceImage](#getSourceImage--) | Liefert das Bild der ersten verglichenen Seite. Das Bild hat ein Pixelformat von 24 bpp. |
| [getStride](#getStride--) | Die Zeilenbreite der Differenzbilddaten. |

### differenceToImage {#differenceToImage-com.aspose.pdf.Color-com.aspose.pdf.Color-}
Konvertiert das Differenzarray in ein Bitmap-Bild unter Verwendung der angegebenen Farben.

### dispose {#dispose--}
```
public final void dispose()
```

Führt alle erforderlichen Aufräumoperationen aus, bevor das Objekt zerstört wird.

### getDestinationImage {#getDestinationImage--}
```
public final BufferedImage getDestinationImage()
```

Gibt ein neues Bitmap zurück, das das Zielbild darstellt, indem das Differenzarray auf das Quellbild angewendet wird.

**Returns:**
Ein Zielbild.

### getDifference {#getDifference--}
```
public final int[] getDifference()
```

Liefert das Differenzarray. Dieses Array ähnelt dem ursprünglichen Bilddatenarray, das als Ergebnis der LockBits-Methode erhalten wurde.

**Returns:**
int[] array

### getHeight {#getHeight--}
```
public final int getHeight()
```

Die Höhe der Differenz.

**Returns:**
int-Wert

### getSourceImage {#getSourceImage--}
```
public final BufferedImage getSourceImage()
```

Liefert das Bild der ersten verglichenen Seite. Das Bild hat ein Pixelformat von 24 bpp.

**Returns:**
BufferedImage-Instanz

### getStride {#getStride--}
```
public final int getStride()
```

Die Zeilenbreite der Differenzbilddaten.

**Returns:**
int-Wert
