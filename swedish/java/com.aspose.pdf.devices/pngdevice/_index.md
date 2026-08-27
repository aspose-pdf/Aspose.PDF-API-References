---
title: "PngDevice"
linktitle: "PngDevice"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar en bildenhet som hjälper till att spara PDF-dokumentets sidor som PNG."
type: docs
weight: 160
url: /sv/java/com.aspose.pdf.devices/pngdevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.PngDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.PngDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.PngDevice, com.aspose.pdf.devices.ImageDevice, com.aspose.pdf.devices.PngDevice

```
public final class PngDevice extends ImageDevice
```

Representerar en bildenhet som hjälper till att spara PDF-dokumentets sidor som PNG.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [PngDevice](#PngDevice--) | Initierar en ny instans av klassen {@code PngDevice} med standardupplösning. |
| [PngDevice](#PngDevice-int-int-) | Initierar en ny instans av klassen {@code PngDevice} med angivna bilddimensioner, standardupplösning (=150). |
| [PngDevice](#PngDevice-int-int-com.aspose.pdf.devices.Resolution-) | Initierar en ny instans av klassen {@code PngDevice} med standardupplösning. |
| [PngDevice](#PngDevice-com.aspose.pdf.PageSize-) | Initierar en ny instans av klassen {@code PngDevice} med standardupplösning. |
| [PngDevice](#PngDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-) | Initierar en ny instans av klassen {@code PngDevice} med standardupplösning. |
| [PngDevice](#PngDevice-com.aspose.pdf.devices.Resolution-) | Initierar en ny instans av klassen {@code PngDevice} med standardupplösning. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [isTransparentBackground](#isTransparentBackground--) | Hämtar eller anger om bilden har transparent bakgrund. |
| [process](#process-com.aspose.pdf.Page-java.io.OutputStream-) | Konverterar sidan till png och sparar den i utdata-strömmen. |
| [processInternal](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | Konverterar sidan till png och sparar den i utdata-strömmen. |
| [processToBufferedImage](#processToBufferedImage-com.aspose.pdf.Page-) | Konverterar sidan till BufferedImage. |
| [processToBufferedImageBinarized](#processToBufferedImageBinarized-com.aspose.pdf.Page-double-) | Konverterar sidan till BufferedImage med Bradley-binarisering. |
| [setTransparentBackground](#setTransparentBackground-boolean-) | Hämtar eller anger om bilden har transparent bakgrund. |

### PngDevice {#PngDevice--}
```
public PngDevice()
```

Initierar en ny instans av klassen {@code PngDevice} med standardupplösning.

### PngDevice {#PngDevice-int-int-}
```
public PngDevice(int width, int height)
```

Initierar en ny instans av klassen {@code PngDevice} med angivna bilddimensioner, standardupplösning (=150).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bredd |  | Bildens utskriftsbredd. |
| höjd |  | Bildens utskrifts‑höjd. |

### PngDevice {#PngDevice-int-int-com.aspose.pdf.devices.Resolution-}
Initierar en ny instans av klassen {@code PngDevice} med standardupplösning.

### PngDevice {#PngDevice-com.aspose.pdf.PageSize-}
Initierar en ny instans av klassen {@code PngDevice} med standardupplösning.

### PngDevice {#PngDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-}
Initierar en ny instans av klassen {@code PngDevice} med standardupplösning.

### PngDevice {#PngDevice-com.aspose.pdf.devices.Resolution-}
Initierar en ny instans av klassen {@code PngDevice} med standardupplösning.

### isTransparentBackground {#isTransparentBackground--}
```
public final boolean isTransparentBackground()
```

Hämtar eller anger om bilden har transparent bakgrund.

**Returns:**
booleskt värde

### process {#process-com.aspose.pdf.Page-java.io.OutputStream-}
Konverterar sidan till png och sparar den i utdata-strömmen.

### processInternal {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
Konverterar sidan till png och sparar den i utdata-strömmen.

### processToBufferedImage {#processToBufferedImage-com.aspose.pdf.Page-}
Konverterar sidan till BufferedImage.

### processToBufferedImageBinarized {#processToBufferedImageBinarized-com.aspose.pdf.Page-double-}
Konverterar sidan till BufferedImage med Bradley-binarisering.

### setTransparentBackground {#setTransparentBackground-boolean-}
```
public final void setTransparentBackground(boolean value)
```

Hämtar eller anger om bilden har transparent bakgrund.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |
