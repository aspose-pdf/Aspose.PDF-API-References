---
title: "PngDevice"
linktitle: "PngDevice"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt ein Bildgerät dar, das beim Speichern von PDF-Dokumentseiten im PNG-Format hilft."
type: docs
weight: 160
url: /de/java/com.aspose.pdf.devices/pngdevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.PngDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.PngDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.PngDevice, com.aspose.pdf.devices.ImageDevice, com.aspose.pdf.devices.PngDevice

```
public final class PngDevice extends ImageDevice
```

Stellt ein Bildgerät dar, das beim Speichern von PDF-Dokumentseiten im PNG-Format hilft.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PngDevice](#PngDevice--) | Initialisiert eine neue Instanz der {@code PngDevice} Klasse mit Standardauflösung. |
| [PngDevice](#PngDevice-int-int-) | Initialisiert eine neue Instanz der {@code PngDevice} Klasse mit angegebenen Bildabmessungen, Standardauflösung (=150). |
| [PngDevice](#PngDevice-int-int-com.aspose.pdf.devices.Resolution-) | Initialisiert eine neue Instanz der {@code PngDevice} Klasse mit Standardauflösung. |
| [PngDevice](#PngDevice-com.aspose.pdf.PageSize-) | Initialisiert eine neue Instanz der {@code PngDevice} Klasse mit Standardauflösung. |
| [PngDevice](#PngDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-) | Initialisiert eine neue Instanz der {@code PngDevice} Klasse mit Standardauflösung. |
| [PngDevice](#PngDevice-com.aspose.pdf.devices.Resolution-) | Initialisiert eine neue Instanz der {@code PngDevice} Klasse mit Standardauflösung. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [isTransparentBackground](#isTransparentBackground--) | Liest oder setzt, ob das Bild einen transparenten Hintergrund hat. |
| [process](#process-com.aspose.pdf.Page-java.io.OutputStream-) | Konvertiert die Seite in PNG und speichert sie im Ausgabestream. |
| [processInternal](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | Konvertiert die Seite in PNG und speichert sie im Ausgabestream. |
| [processToBufferedImage](#processToBufferedImage-com.aspose.pdf.Page-) | Konvertiert die Seite in ein BufferedImage. |
| [processToBufferedImageBinarized](#processToBufferedImageBinarized-com.aspose.pdf.Page-double-) | Konvertiert die Seite in ein BufferedImage mit Bradley-Binarisierung. |
| [setTransparentBackground](#setTransparentBackground-boolean-) | Liest oder setzt, ob das Bild einen transparenten Hintergrund hat. |

### PngDevice {#PngDevice--}
```
public PngDevice()
```

Initialisiert eine neue Instanz der {@code PngDevice} Klasse mit Standardauflösung.

### PngDevice {#PngDevice-int-int-}
```
public PngDevice(int width, int height)
```

Initialisiert eine neue Instanz der {@code PngDevice} Klasse mit angegebenen Bildabmessungen, Standardauflösung (=150).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Breite |  | Bildausgabe-Breite. |
| Höhe |  | Bildausgabe-Höhe. |

### PngDevice {#PngDevice-int-int-com.aspose.pdf.devices.Resolution-}
Initialisiert eine neue Instanz der {@code PngDevice} Klasse mit Standardauflösung.

### PngDevice {#PngDevice-com.aspose.pdf.PageSize-}
Initialisiert eine neue Instanz der {@code PngDevice} Klasse mit Standardauflösung.

### PngDevice {#PngDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-}
Initialisiert eine neue Instanz der {@code PngDevice} Klasse mit Standardauflösung.

### PngDevice {#PngDevice-com.aspose.pdf.devices.Resolution-}
Initialisiert eine neue Instanz der {@code PngDevice} Klasse mit Standardauflösung.

### isTransparentBackground {#isTransparentBackground--}
```
public final boolean isTransparentBackground()
```

Liest oder setzt, ob das Bild einen transparenten Hintergrund hat.

**Returns:**
boolescher Wert

### process {#process-com.aspose.pdf.Page-java.io.OutputStream-}
Konvertiert die Seite in PNG und speichert sie im Ausgabestream.

### processInternal {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
Konvertiert die Seite in PNG und speichert sie im Ausgabestream.

### processToBufferedImage {#processToBufferedImage-com.aspose.pdf.Page-}
Konvertiert die Seite in ein BufferedImage.

### processToBufferedImageBinarized {#processToBufferedImageBinarized-com.aspose.pdf.Page-double-}
Konvertiert die Seite in ein BufferedImage mit Bradley-Binarisierung.

### setTransparentBackground {#setTransparentBackground-boolean-}
```
public final void setTransparentBackground(boolean value)
```

Liest oder setzt, ob das Bild einen transparenten Hintergrund hat.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |
