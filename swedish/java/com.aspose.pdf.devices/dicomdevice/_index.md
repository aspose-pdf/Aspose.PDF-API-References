---
title: "DicomDevice"
linktitle: "DicomDevice"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar en bildenhet som hjälper till att spara PDF-dokumentets sidor i DICOM-format."
type: docs
weight: 50
url: /sv/java/com.aspose.pdf.devices/dicomdevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.DicomDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.DicomDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.DicomDevice, com.aspose.pdf.devices.ImageDevice, com.aspose.pdf.devices.DicomDevice

```
public final class DicomDevice extends ImageDevice
```

Representerar en bildenhet som hjälper till att spara PDF-dokumentets sidor i DICOM-format.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [DicomDevice](#DicomDevice--) | Initierar en ny instans av {@link DicomDevice}-klassen med standardupplösning. |
| [DicomDevice](#DicomDevice-int-int-) | Initierar en ny instans av {@link DicomDevice}-klassen med angivna bilddimensioner, med standardupplösning (=150). |
| [DicomDevice](#DicomDevice-int-int-com.aspose.pdf.devices.Resolution-) | Initierar en ny instans av {@link DicomDevice}-klassen med standardupplösning. |
| [DicomDevice](#DicomDevice-com.aspose.pdf.PageSize-) | Initierar en ny instans av {@link DicomDevice}-klassen med standardupplösning. |
| [DicomDevice](#DicomDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-) | Initierar en ny instans av {@link DicomDevice}-klassen med standardupplösning. |
| [DicomDevice](#DicomDevice-com.aspose.pdf.devices.Resolution-) | Initierar en ny instans av {@link DicomDevice}-klassen med standardupplösning. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [process](#process-com.aspose.pdf.Page-java.io.OutputStream-) | Konverterar sidan till Dicom och sparar den i utdataflödet. |
| [processInternal](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | Utför någon operation på den angivna sidan, t.ex. |

### DicomDevice {#DicomDevice--}
```
public DicomDevice()
```

Initierar en ny instans av {@link DicomDevice}-klassen med standardupplösning.

### DicomDevice {#DicomDevice-int-int-}
```
public DicomDevice(int width, int height)
```

Initierar en ny instans av {@link DicomDevice}-klassen med angivna bilddimensioner, med standardupplösning (=150).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bredd |  | Bildens utskriftsbredd. |
| höjd |  | Bildens utskrifts‑höjd. |

### DicomDevice {#DicomDevice-int-int-com.aspose.pdf.devices.Resolution-}
Initierar en ny instans av {@link DicomDevice}-klassen med standardupplösning.

### DicomDevice {#DicomDevice-com.aspose.pdf.PageSize-}
Initierar en ny instans av {@link DicomDevice}-klassen med standardupplösning.

### DicomDevice {#DicomDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-}
Initierar en ny instans av {@link DicomDevice}-klassen med standardupplösning.

### DicomDevice {#DicomDevice-com.aspose.pdf.devices.Resolution-}
Initierar en ny instans av {@link DicomDevice}-klassen med standardupplösning.

### process {#process-com.aspose.pdf.Page-java.io.OutputStream-}
Konverterar sidan till Dicom och sparar den i utdataflödet.

### processInternal {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
Utför någon operation på den angivna sidan, t.ex.
