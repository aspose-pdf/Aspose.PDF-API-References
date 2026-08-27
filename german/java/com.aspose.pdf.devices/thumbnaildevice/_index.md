---
title: "ThumbnailDevice"
linktitle: "ThumbnailDevice"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt ein Bildgerät dar, das PDF-Dokumentseiten in ein Miniaturbild speichert."
type: docs
weight: 200
url: /de/java/com.aspose.pdf.devices/thumbnaildevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.ThumbnailDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.ThumbnailDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.ThumbnailDevice, com.aspose.pdf.devices.ImageDevice, com.aspose.pdf.devices.ThumbnailDevice

```
public final class ThumbnailDevice extends ImageDevice
```

Stellt ein Bildgerät dar, das PDF-Dokumentseiten in ein Miniaturbild speichert.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ThumbnailDevice](#ThumbnailDevice--) | Initialisiert eine neue Instanz der {@link ThumbnailDevice} Klasse mit Standardgröße des Miniaturbildes (200×200 Pixel). |
| [ThumbnailDevice](#ThumbnailDevice-int-int-) | Initialisiert eine neue Instanz der {@link ThumbnailDevice} Klasse. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [processInternal](#processInternal-com.aspose.pdf.Page-java.io.OutputStream-) | Konvertiert die Seite in ein Miniatur‑png‑Bild und speichert es im Ausgabestream. |
| [processInternal](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | Führt eine Operation auf der angegebenen Seite aus, z. B. |

### ThumbnailDevice {#ThumbnailDevice--}
```
public ThumbnailDevice()
```

Initialisiert eine neue Instanz der {@link ThumbnailDevice} Klasse mit Standardgröße des Miniaturbildes (200×200 Pixel).

### ThumbnailDevice {#ThumbnailDevice-int-int-}
```
public ThumbnailDevice(int width, int height)
```

Initialisiert eine neue Instanz der {@link ThumbnailDevice} Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Breite |  | Ausgabebreite des Miniaturbildes. |
| Höhe |  | Ausgabehöhe des Miniaturbildes. |

### processInternal {#processInternal-com.aspose.pdf.Page-java.io.OutputStream-}
Konvertiert die Seite in ein Miniatur‑png‑Bild und speichert es im Ausgabestream.

### processInternal {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
Führt eine Operation auf der angegebenen Seite aus, z. B.
