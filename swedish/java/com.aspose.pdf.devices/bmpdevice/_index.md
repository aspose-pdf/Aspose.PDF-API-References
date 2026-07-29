---
title: "BmpDevice"
linktitle: "BmpDevice"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar en bildenhet som hjälper till att spara PDF-dokumentets sidor som BMP."
type: docs
weight: 10
url: /sv/java/com.aspose.pdf.devices/bmpdevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.BmpDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.BmpDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.BmpDevice, com.aspose.pdf.devices.ImageDevice, com.aspose.pdf.devices.BmpDevice

```
public final class BmpDevice extends ImageDevice
```

Representerar en bildenhet som hjälper till att spara PDF-dokumentets sidor som BMP.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [BmpDevice](#BmpDevice--) | Initierar en ny instans av {@code BmpDevice}-klassen med standardupplösning. |
| [BmpDevice](#BmpDevice-int-int-) | Initierar en ny instans av {@code BmpDevice}-klassen med angivna bilddimensioner, standardupplösning (=150). |
| [BmpDevice](#BmpDevice-int-int-com.aspose.pdf.devices.Resolution-) | Initierar en ny instans av {@code BmpDevice}-klassen med standardupplösning. |
| [BmpDevice](#BmpDevice-com.aspose.pdf.PageSize-) | Initierar en ny instans av {@code BmpDevice}-klassen med standardupplösning. |
| [BmpDevice](#BmpDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-) | Initierar en ny instans av {@code BmpDevice}-klassen med standardupplösning. |
| [BmpDevice](#BmpDevice-com.aspose.pdf.devices.Resolution-) | Initierar en ny instans av {@code BmpDevice}-klassen med standardupplösning. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [process](#process-com.aspose.pdf.Page-com.aspose.ms.System.Drawing.Graphics-) | renderar sidan på grafiken |
| [process](#process-com.aspose.pdf.Page-java.io.OutputStream-) | Konverterar sidan till bmp och sparar den i utdataflödet. |
| [processInternal](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | Endast för internt bruk! |

### BmpDevice {#BmpDevice--}
```
public BmpDevice()
```

Initierar en ny instans av {@code BmpDevice}-klassen med standardupplösning.

### BmpDevice {#BmpDevice-int-int-}
```
public BmpDevice(int width, int height)
```

Initierar en ny instans av {@code BmpDevice}-klassen med angivna bilddimensioner, standardupplösning (=150).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bredd |  | Bildens utskriftsbredd. |
| höjd |  | Bildens utskrifts‑höjd. |

### BmpDevice {#BmpDevice-int-int-com.aspose.pdf.devices.Resolution-}
Initierar en ny instans av {@code BmpDevice}-klassen med standardupplösning.

### BmpDevice {#BmpDevice-com.aspose.pdf.PageSize-}
Initierar en ny instans av {@code BmpDevice}-klassen med standardupplösning.

### BmpDevice {#BmpDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-}
Initierar en ny instans av {@code BmpDevice}-klassen med standardupplösning.

### BmpDevice {#BmpDevice-com.aspose.pdf.devices.Resolution-}
Initierar en ny instans av {@code BmpDevice}-klassen med standardupplösning.

### process {#process-com.aspose.pdf.Page-com.aspose.ms.System.Drawing.Graphics-}
renderar sidan på grafiken

### process {#process-com.aspose.pdf.Page-java.io.OutputStream-}
Konverterar sidan till bmp och sparar den i utdataflödet.

### processInternal {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
Endast för internt bruk!
