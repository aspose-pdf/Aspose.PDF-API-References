---
title: "JpegDevice"
linktitle: "JpegDevice"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt ein Bildgerät dar, das beim Speichern von PDF-Dokumentseiten im JPEG-Format hilft."
type: docs
weight: 130
url: /de/java/com.aspose.pdf.devices/jpegdevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.JpegDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.JpegDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.JpegDevice, com.aspose.pdf.devices.ImageDevice, com.aspose.pdf.devices.JpegDevice

```
public final class JpegDevice extends ImageDevice
```

Stellt ein Bildgerät dar, das beim Speichern von PDF-Dokumentseiten im JPEG-Format hilft.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [JpegDevice](#JpegDevice--) | Initialisiert eine neue Instanz der {@code JpegDevice} Klasse mit Standardauflösung und maximaler Qualität. |
| [JpegDevice](#JpegDevice-int-) | Initialisiert eine neue Instanz der {@code JpegDevice} Klasse. |
| [JpegDevice](#JpegDevice-int-int-) | Initialisiert eine neue Instanz der {@code JpegDevice} Klasse mit angegebenen Bildabmessungen, Standardauflösung (=150) und maximaler Qualität. |
| [JpegDevice](#JpegDevice-int-int-com.aspose.pdf.devices.Resolution-) | Initialisiert eine neue Instanz der {@code JpegDevice} Klasse mit Standardauflösung und maximaler Qualität. |
| [JpegDevice](#JpegDevice-int-int-com.aspose.pdf.devices.Resolution-int-) | Initialisiert eine neue Instanz der {@code JpegDevice} Klasse mit Standardauflösung und maximaler Qualität. |
| [JpegDevice](#JpegDevice-com.aspose.pdf.PageSize-) | Initialisiert eine neue Instanz der {@code JpegDevice} Klasse mit Standardauflösung und maximaler Qualität. |
| [JpegDevice](#JpegDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-) | Initialisiert eine neue Instanz der {@code JpegDevice} Klasse mit Standardauflösung und maximaler Qualität. |
| [JpegDevice](#JpegDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-int-) | Initialisiert eine neue Instanz der {@code JpegDevice} Klasse mit Standardauflösung und maximaler Qualität. |
| [JpegDevice](#JpegDevice-com.aspose.pdf.devices.Resolution-) | Initialisiert eine neue Instanz der {@code JpegDevice} Klasse mit Standardauflösung und maximaler Qualität. |
| [JpegDevice](#JpegDevice-com.aspose.pdf.devices.Resolution-int-) | Initialisiert eine neue Instanz der {@code JpegDevice} Klasse mit Standardauflösung und maximaler Qualität. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [process](#process-com.aspose.pdf.Page-java.io.OutputStream-) | Konvertiert die Seite in JPEG und speichert sie im Ausgabestream. |
| [processInternal](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | Konvertiert die Seite in JPEG und speichert sie im Ausgabestream. |

### JpegDevice {#JpegDevice--}
```
public JpegDevice()
```

Initialisiert eine neue Instanz der {@code JpegDevice} Klasse mit Standardauflösung und maximaler Qualität.

### JpegDevice {#JpegDevice-int-}
```
public JpegDevice(int quality)
```

Initialisiert eine neue Instanz der {@code JpegDevice} Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Qualität |  | Gibt das Kompressionsniveau für ein Bild an. Der Bereich nützlicher Werte für die Qualität liegt zwischen 0 und 100. Je niedriger die angegebene Zahl, desto höher die Kompression und damit die geringere Bildqualität. Null ergibt das Bild mit der niedrigsten Qualität und 100 die höchste. |

### JpegDevice {#JpegDevice-int-int-}
```
public JpegDevice(int width, int height)
```

Initialisiert eine neue Instanz der {@code JpegDevice} Klasse mit angegebenen Bildabmessungen, Standardauflösung (=150) und maximaler Qualität.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Breite |  | Bildausgabe-Breite. |
| Höhe |  | Bildausgabe-Höhe. |

### JpegDevice {#JpegDevice-int-int-com.aspose.pdf.devices.Resolution-}
Initialisiert eine neue Instanz der {@code JpegDevice} Klasse mit Standardauflösung und maximaler Qualität.

### JpegDevice {#JpegDevice-int-int-com.aspose.pdf.devices.Resolution-int-}
Initialisiert eine neue Instanz der {@code JpegDevice} Klasse mit Standardauflösung und maximaler Qualität.

### JpegDevice {#JpegDevice-com.aspose.pdf.PageSize-}
Initialisiert eine neue Instanz der {@code JpegDevice} Klasse mit Standardauflösung und maximaler Qualität.

### JpegDevice {#JpegDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-}
Initialisiert eine neue Instanz der {@code JpegDevice} Klasse mit Standardauflösung und maximaler Qualität.

### JpegDevice {#JpegDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-int-}
Initialisiert eine neue Instanz der {@code JpegDevice} Klasse mit Standardauflösung und maximaler Qualität.

### JpegDevice {#JpegDevice-com.aspose.pdf.devices.Resolution-}
Initialisiert eine neue Instanz der {@code JpegDevice} Klasse mit Standardauflösung und maximaler Qualität.

### JpegDevice {#JpegDevice-com.aspose.pdf.devices.Resolution-int-}
Initialisiert eine neue Instanz der {@code JpegDevice} Klasse mit Standardauflösung und maximaler Qualität.

### process {#process-com.aspose.pdf.Page-java.io.OutputStream-}
Konvertiert die Seite in JPEG und speichert sie im Ausgabestream.

### processInternal {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
Konvertiert die Seite in JPEG und speichert sie im Ausgabestream.
