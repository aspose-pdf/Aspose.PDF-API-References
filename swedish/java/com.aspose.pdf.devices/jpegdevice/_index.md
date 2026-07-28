---
title: "JpegDevice"
linktitle: "JpegDevice"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar en bildenhet som hjälper till att spara PDF-dokumentets sidor som JPEG."
type: docs
weight: 130
url: /sv/java/com.aspose.pdf.devices/jpegdevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.JpegDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.JpegDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.JpegDevice, com.aspose.pdf.devices.ImageDevice, com.aspose.pdf.devices.JpegDevice

```
public final class JpegDevice extends ImageDevice
```

Representerar en bildenhet som hjälper till att spara PDF-dokumentets sidor som JPEG.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [JpegDevice](#JpegDevice--) | Initierar en ny instans av {@code JpegDevice}-klassen med standardupplösning och maximal kvalitet. |
| [JpegDevice](#JpegDevice-int-) | Initierar en ny instans av {@code JpegDevice}-klassen. |
| [JpegDevice](#JpegDevice-int-int-) | Initierar en ny instans av {@code JpegDevice}-klassen med angivna bilddimensioner, standardupplösning (=150) och maximal kvalitet. |
| [JpegDevice](#JpegDevice-int-int-com.aspose.pdf.devices.Resolution-) | Initierar en ny instans av {@code JpegDevice}-klassen med standardupplösning och maximal kvalitet. |
| [JpegDevice](#JpegDevice-int-int-com.aspose.pdf.devices.Resolution-int-) | Initierar en ny instans av {@code JpegDevice}-klassen med standardupplösning och maximal kvalitet. |
| [JpegDevice](#JpegDevice-com.aspose.pdf.PageSize-) | Initierar en ny instans av {@code JpegDevice}-klassen med standardupplösning och maximal kvalitet. |
| [JpegDevice](#JpegDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-) | Initierar en ny instans av {@code JpegDevice}-klassen med standardupplösning och maximal kvalitet. |
| [JpegDevice](#JpegDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-int-) | Initierar en ny instans av {@code JpegDevice}-klassen med standardupplösning och maximal kvalitet. |
| [JpegDevice](#JpegDevice-com.aspose.pdf.devices.Resolution-) | Initierar en ny instans av {@code JpegDevice}-klassen med standardupplösning och maximal kvalitet. |
| [JpegDevice](#JpegDevice-com.aspose.pdf.devices.Resolution-int-) | Initierar en ny instans av {@code JpegDevice}-klassen med standardupplösning och maximal kvalitet. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [process](#process-com.aspose.pdf.Page-java.io.OutputStream-) | Konverterar sidan till jpeg och sparar den i utdataflödet. |
| [processInternal](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | Konverterar sidan till jpeg och sparar den i utdataflödet. |

### JpegDevice {#JpegDevice--}
```
public JpegDevice()
```

Initierar en ny instans av {@code JpegDevice}-klassen med standardupplösning och maximal kvalitet.

### JpegDevice {#JpegDevice-int-}
```
public JpegDevice(int quality)
```

Initierar en ny instans av {@code JpegDevice}-klassen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| kvalitet |  | Anger komprimeringsnivån för en bild. Intervallet för användbara värden för kvaliteten är från 0 till 100. Ju lägre tal som anges, desto högre blir komprimeringen och därmed lägre bildkvalitet. Noll ger den lägsta bildkvaliteten och 100 den högsta. |

### JpegDevice {#JpegDevice-int-int-}
```
public JpegDevice(int width, int height)
```

Initierar en ny instans av {@code JpegDevice}-klassen med angivna bilddimensioner, standardupplösning (=150) och maximal kvalitet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bredd |  | Bildens utskriftsbredd. |
| höjd |  | Bildens utskrifts‑höjd. |

### JpegDevice {#JpegDevice-int-int-com.aspose.pdf.devices.Resolution-}
Initierar en ny instans av {@code JpegDevice}-klassen med standardupplösning och maximal kvalitet.

### JpegDevice {#JpegDevice-int-int-com.aspose.pdf.devices.Resolution-int-}
Initierar en ny instans av {@code JpegDevice}-klassen med standardupplösning och maximal kvalitet.

### JpegDevice {#JpegDevice-com.aspose.pdf.PageSize-}
Initierar en ny instans av {@code JpegDevice}-klassen med standardupplösning och maximal kvalitet.

### JpegDevice {#JpegDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-}
Initierar en ny instans av {@code JpegDevice}-klassen med standardupplösning och maximal kvalitet.

### JpegDevice {#JpegDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-int-}
Initierar en ny instans av {@code JpegDevice}-klassen med standardupplösning och maximal kvalitet.

### JpegDevice {#JpegDevice-com.aspose.pdf.devices.Resolution-}
Initierar en ny instans av {@code JpegDevice}-klassen med standardupplösning och maximal kvalitet.

### JpegDevice {#JpegDevice-com.aspose.pdf.devices.Resolution-int-}
Initierar en ny instans av {@code JpegDevice}-klassen med standardupplösning och maximal kvalitet.

### process {#process-com.aspose.pdf.Page-java.io.OutputStream-}
Konverterar sidan till jpeg och sparar den i utdataflödet.

### processInternal {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
Konverterar sidan till jpeg och sparar den i utdataflödet.
