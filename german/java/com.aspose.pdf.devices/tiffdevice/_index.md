---
title: "TiffDevice"
linktitle: "TiffDevice"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Diese Klasse hilft dabei, PDF-Dokumentseiten einzeln in ein einziges TIFF‑Bild zu speichern."
type: docs
weight: 210
url: /de/java/com.aspose.pdf.devices/tiffdevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.DocumentDevice com.aspose.pdf.devices.TiffDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.DocumentDevice com.aspose.pdf.devices.TiffDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.DocumentDevice com.aspose.pdf.devices.TiffDevice, com.aspose.pdf.devices.DocumentDevice, com.aspose.pdf.devices.TiffDevice

```
public final class TiffDevice extends DocumentDevice
```

Diese Klasse hilft dabei, PDF-Dokumentseiten einzeln in ein einziges TIFF‑Bild zu speichern.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [TiffDevice](#TiffDevice--) | Initialisiert eine neue Instanz der {@code TiffDevice}-Klasse mit den Standardeinstellungen. |
| [TiffDevice](#TiffDevice-int-int-) | Initialisiert eine neue Instanz der {@code TiffDevice}-Klasse. |
| [TiffDevice](#TiffDevice-int-int-com.aspose.pdf.devices.Resolution-) | Initialisiert eine neue Instanz der {@code TiffDevice}-Klasse mit den Standardeinstellungen. |
| [TiffDevice](#TiffDevice-int-int-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-) | Initialisiert eine neue Instanz der {@code TiffDevice}-Klasse mit den Standardeinstellungen. |
| [TiffDevice](#TiffDevice-int-int-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Initialisiert eine neue Instanz der {@code TiffDevice}-Klasse mit den Standardeinstellungen. |
| [TiffDevice](#TiffDevice-int-int-com.aspose.pdf.devices.TiffSettings-) | Initialisiert eine neue Instanz der {@code TiffDevice}-Klasse mit den Standardeinstellungen. |
| [TiffDevice](#TiffDevice-int-int-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Initialisiert eine neue Instanz der {@code TiffDevice}-Klasse mit den Standardeinstellungen. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.PageSize-) | Initialisiert eine neue Instanz der {@code TiffDevice}-Klasse mit den Standardeinstellungen. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-) | Initialisiert eine neue Instanz der {@code TiffDevice}-Klasse mit den Standardeinstellungen. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-) | Initialisiert eine neue Instanz der {@code TiffDevice}-Klasse mit den Standardeinstellungen. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Initialisiert eine neue Instanz der {@code TiffDevice}-Klasse mit den Standardeinstellungen. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-) | Initialisiert eine neue Instanz der {@code TiffDevice}-Klasse mit den Standardeinstellungen. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Initialisiert eine neue Instanz der {@code TiffDevice}-Klasse mit den Standardeinstellungen. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.devices.Resolution-) | Initialisiert eine neue Instanz der {@code TiffDevice}-Klasse mit den Standardeinstellungen. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-) | Initialisiert eine neue Instanz der {@code TiffDevice}-Klasse mit den Standardeinstellungen. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Initialisiert eine neue Instanz der {@code TiffDevice}-Klasse mit den Standardeinstellungen. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.devices.TiffSettings-) | Initialisiert eine neue Instanz der {@code TiffDevice}-Klasse mit den Standardeinstellungen. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Initialisiert eine neue Instanz der {@code TiffDevice}-Klasse mit den Standardeinstellungen. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [binarizeBradley](#binarizeBradley-java.io.InputStream-java.io.OutputStream-double-) | Führt die Bradley-Binarisierung für den Eingabestream durch. |
| [getCropRectangle](#getCropRectangle--) | Ermittelt das Rechteck, das den Bereich definiert, der in ein Bild umgewandelt wird. Der Standardwert ist null, in diesem Fall wird das gesamte Bild in eine Seite umgewandelt. |
| [getFormPresentationMode](#getFormPresentationMode--) | Liefert den Formularpräsentationsmodus. |
| [getHeight](#getHeight--) | Liefert die Bildausgabehöhe. |
| [getRenderingOptions](#getRenderingOptions--) | Ruft Rendering-Optionen ab. |
| [getResolution](#getResolution--) | Ruft Bildauflösung ab. |
| [getSettings](#getSettings--) | Ruft Einstellungen für die Zuordnung von PDF zu TIFF-Bild ab. |
| [getWidth](#getWidth--) | Ruft Bildausgabe-Breite ab. |
| [process](#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-) | Konvertiert bestimmte Dokumentseiten in TIFF und speichert sie im Ausgabestream. |
| [processInternal](#processInternal-com.aspose.pdf.IDocument-int-int-com.aspose.ms.System.IO.Stream-) | Konvertiert bestimmte Dokumentseiten in TIFF und speichert sie im Ausgabestream. |
| [processInternal](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | Führt eine Operation auf der angegebenen Seite aus, z. B. |
| [setCropRectangle](#setCropRectangle-com.aspose.pdf.Rectangle-) | Setzt das Rechteck, das den Bereich definiert, der in ein Bild konvertiert wird. |
| [setFormPresentationMode](#setFormPresentationMode-int-) | Liefert den Formularpräsentationsmodus. |
| [setRenderingOptions](#setRenderingOptions-com.aspose.pdf.RenderingOptions-) | Setzt Rendering-Optionen. |

### TiffDevice {#TiffDevice--}
```
public TiffDevice()
```

Initialisiert eine neue Instanz der {@code TiffDevice}-Klasse mit den Standardeinstellungen.

### TiffDevice {#TiffDevice-int-int-}
```
public TiffDevice(int width, int height)
```

Initialisiert eine neue Instanz der {@code TiffDevice}-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Breite |  | Bildausgabe-Breite. |
| Höhe |  | Bildausgabe-Höhe. |

### TiffDevice {#TiffDevice-int-int-com.aspose.pdf.devices.Resolution-}
Initialisiert eine neue Instanz der {@code TiffDevice}-Klasse mit den Standardeinstellungen.

### TiffDevice {#TiffDevice-int-int-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-}
Initialisiert eine neue Instanz der {@code TiffDevice}-Klasse mit den Standardeinstellungen.

### TiffDevice {#TiffDevice-int-int-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
Initialisiert eine neue Instanz der {@code TiffDevice}-Klasse mit den Standardeinstellungen.

### TiffDevice {#TiffDevice-int-int-com.aspose.pdf.devices.TiffSettings-}
Initialisiert eine neue Instanz der {@code TiffDevice}-Klasse mit den Standardeinstellungen.

### TiffDevice {#TiffDevice-int-int-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
Initialisiert eine neue Instanz der {@code TiffDevice}-Klasse mit den Standardeinstellungen.

### TiffDevice {#TiffDevice-com.aspose.pdf.PageSize-}
Initialisiert eine neue Instanz der {@code TiffDevice}-Klasse mit den Standardeinstellungen.

### TiffDevice {#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-}
Initialisiert eine neue Instanz der {@code TiffDevice}-Klasse mit den Standardeinstellungen.

### TiffDevice {#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-}
Initialisiert eine neue Instanz der {@code TiffDevice}-Klasse mit den Standardeinstellungen.

### TiffDevice {#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
Initialisiert eine neue Instanz der {@code TiffDevice}-Klasse mit den Standardeinstellungen.

### TiffDevice {#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-}
Initialisiert eine neue Instanz der {@code TiffDevice}-Klasse mit den Standardeinstellungen.

### TiffDevice {#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
Initialisiert eine neue Instanz der {@code TiffDevice}-Klasse mit den Standardeinstellungen.

### TiffDevice {#TiffDevice-com.aspose.pdf.devices.Resolution-}
Initialisiert eine neue Instanz der {@code TiffDevice}-Klasse mit den Standardeinstellungen.

### TiffDevice {#TiffDevice-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-}
Initialisiert eine neue Instanz der {@code TiffDevice}-Klasse mit den Standardeinstellungen.

### TiffDevice {#TiffDevice-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
Initialisiert eine neue Instanz der {@code TiffDevice}-Klasse mit den Standardeinstellungen.

### TiffDevice {#TiffDevice-com.aspose.pdf.devices.TiffSettings-}
Initialisiert eine neue Instanz der {@code TiffDevice}-Klasse mit den Standardeinstellungen.

### TiffDevice {#TiffDevice-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
Initialisiert eine neue Instanz der {@code TiffDevice}-Klasse mit den Standardeinstellungen.

### binarizeBradley {#binarizeBradley-java.io.InputStream-java.io.OutputStream-double-}
Führt die Bradley-Binarisierung für den Eingabestream durch.

### getCropRectangle {#getCropRectangle--}
```
public Rectangle getCropRectangle()
```

Ermittelt das Rechteck, das den Bereich definiert, der in ein Bild umgewandelt wird. Der Standardwert ist null, in diesem Fall wird das gesamte Bild in eine Seite umgewandelt.

**Returns:**
Rectangle-Objekt

### getFormPresentationMode {#getFormPresentationMode--}
```
public int getFormPresentationMode()
```

Liefert den Formularpräsentationsmodus.

**Returns:**
FormPresentationMode-Wert @see FormPresentationMode

### getHeight {#getHeight--}
```
public int getHeight()
```

Liefert die Bildausgabehöhe.

**Returns:**
int-Wert

### getRenderingOptions {#getRenderingOptions--}
```
public RenderingOptions getRenderingOptions()
```

Ruft Rendering-Optionen ab.

**Returns:**
Rendering-Optionen.

### getResolution {#getResolution--}
```
public Resolution getResolution()
```

Ruft Bildauflösung ab.

**Returns:**
Auflösungselement

### getSettings {#getSettings--}
```
public TiffSettings getSettings()
```

Ruft Einstellungen für die Zuordnung von PDF zu TIFF-Bild ab.

**Returns:**
TiffSettings-Element

### getWidth {#getWidth--}
```
public int getWidth()
```

Ruft Bildausgabe-Breite ab.

**Returns:**
int-Wert

### process {#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-}
Konvertiert bestimmte Dokumentseiten in TIFF und speichert sie im Ausgabestream.

### processInternal {#processInternal-com.aspose.pdf.IDocument-int-int-com.aspose.ms.System.IO.Stream-}
Konvertiert bestimmte Dokumentseiten in TIFF und speichert sie im Ausgabestream.

### processInternal {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
Führt eine Operation auf der angegebenen Seite aus, z. B.

### setCropRectangle {#setCropRectangle-com.aspose.pdf.Rectangle-}
Setzt das Rechteck, das den Bereich definiert, der in ein Bild konvertiert wird.

### setFormPresentationMode {#setFormPresentationMode-int-}
```
public void setFormPresentationMode(int value)
```

Liefert den Formularpräsentationsmodus.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert @see FormPresentationMode |

### setRenderingOptions {#setRenderingOptions-com.aspose.pdf.RenderingOptions-}
Setzt Rendering-Optionen.
