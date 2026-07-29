---
title: "BmpDevice"
linktitle: "BmpDevice"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt ein Bildgerät dar, das beim Speichern von PDF-Dokumentseiten im BMP-Format hilft."
type: docs
weight: 10
url: /de/java/com.aspose.pdf.devices/bmpdevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.BmpDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.BmpDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.BmpDevice, com.aspose.pdf.devices.ImageDevice, com.aspose.pdf.devices.BmpDevice

```
public final class BmpDevice extends ImageDevice
```

Stellt ein Bildgerät dar, das beim Speichern von PDF-Dokumentseiten im BMP-Format hilft.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [BmpDevice](#BmpDevice--) | Initialisiert eine neue Instanz der {@code BmpDevice} Klasse mit Standardauflösung. |
| [BmpDevice](#BmpDevice-int-int-) | Initialisiert eine neue Instanz der {@code BmpDevice} Klasse mit angegebenen Bildabmessungen, Standardauflösung (=150). |
| [BmpDevice](#BmpDevice-int-int-com.aspose.pdf.devices.Resolution-) | Initialisiert eine neue Instanz der {@code BmpDevice} Klasse mit Standardauflösung. |
| [BmpDevice](#BmpDevice-com.aspose.pdf.PageSize-) | Initialisiert eine neue Instanz der {@code BmpDevice} Klasse mit Standardauflösung. |
| [BmpDevice](#BmpDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-) | Initialisiert eine neue Instanz der {@code BmpDevice} Klasse mit Standardauflösung. |
| [BmpDevice](#BmpDevice-com.aspose.pdf.devices.Resolution-) | Initialisiert eine neue Instanz der {@code BmpDevice} Klasse mit Standardauflösung. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [process](#process-com.aspose.pdf.Page-com.aspose.ms.System.Drawing.Graphics-) | rendert die Seite auf dem Grafikgerät. |
| [process](#process-com.aspose.pdf.Page-java.io.OutputStream-) | Konvertiert die Seite in bmp und speichert sie im Ausgabestream. |
| [processInternal](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | Nur für den internen Gebrauch! |

### BmpDevice {#BmpDevice--}
```
public BmpDevice()
```

Initialisiert eine neue Instanz der {@code BmpDevice} Klasse mit Standardauflösung.

### BmpDevice {#BmpDevice-int-int-}
```
public BmpDevice(int width, int height)
```

Initialisiert eine neue Instanz der {@code BmpDevice} Klasse mit angegebenen Bildabmessungen, Standardauflösung (=150).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Breite |  | Bildausgabe-Breite. |
| Höhe |  | Bildausgabe-Höhe. |

### BmpDevice {#BmpDevice-int-int-com.aspose.pdf.devices.Resolution-}
Initialisiert eine neue Instanz der {@code BmpDevice} Klasse mit Standardauflösung.

### BmpDevice {#BmpDevice-com.aspose.pdf.PageSize-}
Initialisiert eine neue Instanz der {@code BmpDevice} Klasse mit Standardauflösung.

### BmpDevice {#BmpDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-}
Initialisiert eine neue Instanz der {@code BmpDevice} Klasse mit Standardauflösung.

### BmpDevice {#BmpDevice-com.aspose.pdf.devices.Resolution-}
Initialisiert eine neue Instanz der {@code BmpDevice} Klasse mit Standardauflösung.

### process {#process-com.aspose.pdf.Page-com.aspose.ms.System.Drawing.Graphics-}
rendert die Seite auf dem Grafikgerät.

### process {#process-com.aspose.pdf.Page-java.io.OutputStream-}
Konvertiert die Seite in bmp und speichert sie im Ausgabestream.

### processInternal {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
Nur für den internen Gebrauch!
