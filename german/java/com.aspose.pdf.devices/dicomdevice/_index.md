---
title: "DicomDevice"
linktitle: "DicomDevice"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt ein Bildgerät dar, das beim Speichern von PDF-Dokumentseiten im DICOM-Format hilft."
type: docs
weight: 50
url: /de/java/com.aspose.pdf.devices/dicomdevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.DicomDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.DicomDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.DicomDevice, com.aspose.pdf.devices.ImageDevice, com.aspose.pdf.devices.DicomDevice

```
public final class DicomDevice extends ImageDevice
```

Stellt ein Bildgerät dar, das beim Speichern von PDF-Dokumentseiten im DICOM-Format hilft.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [DicomDevice](#DicomDevice--) | Initialisiert eine neue Instanz der {@link DicomDevice} Klasse mit Standardauflösung. |
| [DicomDevice](#DicomDevice-int-int-) | Initialisiert eine neue Instanz der {@link DicomDevice} Klasse mit angegebenen Bildabmessungen und Standardauflösung (=150). |
| [DicomDevice](#DicomDevice-int-int-com.aspose.pdf.devices.Resolution-) | Initialisiert eine neue Instanz der {@link DicomDevice} Klasse mit Standardauflösung. |
| [DicomDevice](#DicomDevice-com.aspose.pdf.PageSize-) | Initialisiert eine neue Instanz der {@link DicomDevice} Klasse mit Standardauflösung. |
| [DicomDevice](#DicomDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-) | Initialisiert eine neue Instanz der {@link DicomDevice} Klasse mit Standardauflösung. |
| [DicomDevice](#DicomDevice-com.aspose.pdf.devices.Resolution-) | Initialisiert eine neue Instanz der {@link DicomDevice} Klasse mit Standardauflösung. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [process](#process-com.aspose.pdf.Page-java.io.OutputStream-) | Konvertiert die Seite in Dicom und speichert sie im Ausgabestream. |
| [processInternal](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | Führt eine Operation auf der angegebenen Seite aus, z. B. |

### DicomDevice {#DicomDevice--}
```
public DicomDevice()
```

Initialisiert eine neue Instanz der {@link DicomDevice} Klasse mit Standardauflösung.

### DicomDevice {#DicomDevice-int-int-}
```
public DicomDevice(int width, int height)
```

Initialisiert eine neue Instanz der {@link DicomDevice} Klasse mit angegebenen Bildabmessungen und Standardauflösung (=150).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Breite |  | Bildausgabe-Breite. |
| Höhe |  | Bildausgabe-Höhe. |

### DicomDevice {#DicomDevice-int-int-com.aspose.pdf.devices.Resolution-}
Initialisiert eine neue Instanz der {@link DicomDevice} Klasse mit Standardauflösung.

### DicomDevice {#DicomDevice-com.aspose.pdf.PageSize-}
Initialisiert eine neue Instanz der {@link DicomDevice} Klasse mit Standardauflösung.

### DicomDevice {#DicomDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-}
Initialisiert eine neue Instanz der {@link DicomDevice} Klasse mit Standardauflösung.

### DicomDevice {#DicomDevice-com.aspose.pdf.devices.Resolution-}
Initialisiert eine neue Instanz der {@link DicomDevice} Klasse mit Standardauflösung.

### process {#process-com.aspose.pdf.Page-java.io.OutputStream-}
Konvertiert die Seite in Dicom und speichert sie im Ausgabestream.

### processInternal {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
Führt eine Operation auf der angegebenen Seite aus, z. B.
