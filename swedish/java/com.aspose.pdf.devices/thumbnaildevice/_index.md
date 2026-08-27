---
title: "ThumbnailDevice"
linktitle: "ThumbnailDevice"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar en bildenhet som sparar PDF-dokumentets sidor som miniatyrbild."
type: docs
weight: 200
url: /sv/java/com.aspose.pdf.devices/thumbnaildevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.ThumbnailDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.ThumbnailDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.ThumbnailDevice, com.aspose.pdf.devices.ImageDevice, com.aspose.pdf.devices.ThumbnailDevice

```
public final class ThumbnailDevice extends ImageDevice
```

Representerar en bildenhet som sparar PDF-dokumentets sidor som miniatyrbild.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [ThumbnailDevice](#ThumbnailDevice--) | Initierar en ny instans av klassen {@link ThumbnailDevice} med standardstorlek för miniatyrbild (200x200 pixlar). |
| [ThumbnailDevice](#ThumbnailDevice-int-int-) | Initierar en ny instans av klassen {@link ThumbnailDevice}. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [processInternal](#processInternal-com.aspose.pdf.Page-java.io.OutputStream-) | Konverterar sidan till en miniatyr-png-bild och sparar den i utdata-strömmen. |
| [processInternal](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | Utför någon operation på den angivna sidan, t.ex. |

### ThumbnailDevice {#ThumbnailDevice--}
```
public ThumbnailDevice()
```

Initierar en ny instans av klassen {@link ThumbnailDevice} med standardstorlek för miniatyrbild (200x200 pixlar).

### ThumbnailDevice {#ThumbnailDevice-int-int-}
```
public ThumbnailDevice(int width, int height)
```

Initierar en ny instans av klassen {@link ThumbnailDevice}.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bredd |  | Bredd för miniatyrbildens utdata. |
| höjd |  | Höjd för miniatyrbildens utdata. |

### processInternal {#processInternal-com.aspose.pdf.Page-java.io.OutputStream-}
Konverterar sidan till en miniatyr-png-bild och sparar den i utdata-strömmen.

### processInternal {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
Utför någon operation på den angivna sidan, t.ex.
