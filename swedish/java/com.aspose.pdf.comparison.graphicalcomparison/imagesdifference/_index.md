---
title: "ImagesDifference"
linktitle: "ImagesDifference"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar resultatklassen för jämförelse av två PDF-sidor."
type: docs
weight: 20
url: /sv/java/com.aspose.pdf.comparison.graphicalcomparison/imagesdifference/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.comparison.graphicalcomparison.ImagesDifference

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable

```
public final class ImagesDifference extends Object implements com.aspose.ms.System.IDisposable
```

Representerar resultatklassen för jämförelse av två PDF-sidor.

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [differenceToImage](#differenceToImage-com.aspose.pdf.Color-com.aspose.pdf.Color-) | Konverterar skillnadsarrayen till en bitmap-bild med de angivna färgerna. |
| [dispose](#dispose--) | Utför eventuella nödvändiga rensningsoperationer innan objektet förstörs. |
| [getDestinationImage](#getDestinationImage--) | Returnerar en ny bitmap som representerar målbilden genom att applicera skillnadsarrayen på källbilden. |
| [getDifference](#getDifference--) | Hämtar skillnadsarrayen. Denna array liknar den ursprungliga bilddataarrayen som erhålls som resultat av metoden LockBits. |
| [getHeight](#getHeight--) | Höjden på skillnaden. |
| [getSourceImage](#getSourceImage--) | Hämtar bilden av den första jämförda sidan. Bilden har pixelformatet 24 bpp. |
| [getStride](#getStride--) | Radsteget för skillnadsbildens data. |

### differenceToImage {#differenceToImage-com.aspose.pdf.Color-com.aspose.pdf.Color-}
Konverterar skillnadsarrayen till en bitmap-bild med de angivna färgerna.

### dispose {#dispose--}
```
public final void dispose()
```

Utför eventuella nödvändiga rensningsoperationer innan objektet förstörs.

### getDestinationImage {#getDestinationImage--}
```
public final BufferedImage getDestinationImage()
```

Returnerar en ny bitmap som representerar målbilden genom att applicera skillnadsarrayen på källbilden.

**Returns:**
En målbild.

### getDifference {#getDifference--}
```
public final int[] getDifference()
```

Hämtar skillnadsarrayen. Denna array liknar den ursprungliga bilddataarrayen som erhålls som resultat av metoden LockBits.

**Returns:**
int[] array

### getHeight {#getHeight--}
```
public final int getHeight()
```

Höjden på skillnaden.

**Returns:**
int‑värde

### getSourceImage {#getSourceImage--}
```
public final BufferedImage getSourceImage()
```

Hämtar bilden av den första jämförda sidan. Bilden har pixelformatet 24 bpp.

**Returns:**
BufferedImage-instans

### getStride {#getStride--}
```
public final int getStride()
```

Radsteget för skillnadsbildens data.

**Returns:**
int‑värde
