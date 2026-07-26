---
title: "EmfDevice"
linktitle: "EmfDevice"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt ein Bildgerät dar, das beim Speichern von PDF-Dokumentseiten im EMF-Format hilft."
type: docs
weight: 70
url: /de/java/com.aspose.pdf.devices/emfdevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.EmfDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.EmfDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.EmfDevice, com.aspose.pdf.devices.ImageDevice, com.aspose.pdf.devices.EmfDevice

```
public final class EmfDevice extends ImageDevice
```

Stellt ein Bildgerät dar, das beim Speichern von PDF-Dokumentseiten im EMF-Format hilft.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfDevice](#EmfDevice--) | Initialisiert eine neue Instanz der {@code EmfDevice}-Klasse mit der Standardauflösung des in EMF geschriebenen Rasterbildes. |
| [EmfDevice](#EmfDevice-int-int-) | Initialisiert eine neue Instanz der {@code EmfDevice}-Klasse mit den angegebenen Bildabmessungen und der Standardauflösung für das in EMF geschriebene Rasterbild (=150). |
| [EmfDevice](#EmfDevice-int-int-com.aspose.pdf.devices.Resolution-) | Initialisiert eine neue Instanz der {@code EmfDevice}-Klasse mit der Standardauflösung des in EMF geschriebenen Rasterbildes. |
| [EmfDevice](#EmfDevice-com.aspose.pdf.PageSize-) | Initialisiert eine neue Instanz der {@code EmfDevice}-Klasse mit der Standardauflösung des in EMF geschriebenen Rasterbildes. |
| [EmfDevice](#EmfDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-) | Initialisiert eine neue Instanz der {@code EmfDevice}-Klasse mit der Standardauflösung des in EMF geschriebenen Rasterbildes. |
| [EmfDevice](#EmfDevice-com.aspose.pdf.devices.Resolution-) | Initialisiert eine neue Instanz der {@code EmfDevice}-Klasse mit der Standardauflösung des in EMF geschriebenen Rasterbildes. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [process](#process-com.aspose.pdf.Page-java.io.OutputStream-) | Konvertiert die Seite in EMF und speichert sie im Ausgabestream. |
| [processInternal](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | Konvertiert die Seite in EMF und speichert sie im Ausgabestream. |

### EmfDevice {#EmfDevice--}
```
public EmfDevice()
```

Initialisiert eine neue Instanz der {@code EmfDevice}-Klasse mit der Standardauflösung des in EMF geschriebenen Rasterbildes.

### EmfDevice {#EmfDevice-int-int-}
```
public EmfDevice(int width, int height)
```

Initialisiert eine neue Instanz der {@code EmfDevice}-Klasse mit den angegebenen Bildabmessungen und der Standardauflösung für das in EMF geschriebene Rasterbild (=150).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Breite |  | Bildausgabe-Breite. |
| Höhe |  | Bildausgabe-Höhe. |

### EmfDevice {#EmfDevice-int-int-com.aspose.pdf.devices.Resolution-}
Initialisiert eine neue Instanz der {@code EmfDevice}-Klasse mit der Standardauflösung des in EMF geschriebenen Rasterbildes.

### EmfDevice {#EmfDevice-com.aspose.pdf.PageSize-}
Initialisiert eine neue Instanz der {@code EmfDevice}-Klasse mit der Standardauflösung des in EMF geschriebenen Rasterbildes.

### EmfDevice {#EmfDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-}
Initialisiert eine neue Instanz der {@code EmfDevice}-Klasse mit der Standardauflösung des in EMF geschriebenen Rasterbildes.

### EmfDevice {#EmfDevice-com.aspose.pdf.devices.Resolution-}
Initialisiert eine neue Instanz der {@code EmfDevice}-Klasse mit der Standardauflösung des in EMF geschriebenen Rasterbildes.

### process {#process-com.aspose.pdf.Page-java.io.OutputStream-}
Konvertiert die Seite in EMF und speichert sie im Ausgabestream.

### processInternal {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
Konvertiert die Seite in EMF und speichert sie im Ausgabestream.
