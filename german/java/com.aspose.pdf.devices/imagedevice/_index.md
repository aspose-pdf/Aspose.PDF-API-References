---
title: "ImageDevice"
linktitle: "ImageDevice"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Eine abstrakte Klasse für Bildgeräte."
type: docs
weight: 110
url: /de/java/com.aspose.pdf.devices/imagedevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.ImageDevice

```
public abstract class ImageDevice extends PageDevice
```

Eine abstrakte Klasse für Bildgeräte.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ImageDevice](#ImageDevice--) | Abstrakter Initialisierer für {@code ImageDevice}-Abkömmlinge, setzt die Auflösung auf 150x150. |
| [ImageDevice](#ImageDevice-int-int-) | Initialisiert eine neue Instanz der {@code JpegDevice}-Klasse mit den angegebenen Bildabmessungen und der Standardauflösung (=150). |
| [ImageDevice](#ImageDevice-int-int-com.aspose.pdf.devices.Resolution-) | Abstrakter Initialisierer für {@code ImageDevice}-Abkömmlinge, setzt die Auflösung auf 150x150. |
| [ImageDevice](#ImageDevice-com.aspose.pdf.PageSize-) | Abstrakter Initialisierer für {@code ImageDevice}-Abkömmlinge, setzt die Auflösung auf 150x150. |
| [ImageDevice](#ImageDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-) | Abstrakter Initialisierer für {@code ImageDevice}-Abkömmlinge, setzt die Auflösung auf 150x150. |
| [ImageDevice](#ImageDevice-com.aspose.pdf.devices.Resolution-) | Abstrakter Initialisierer für {@code ImageDevice}-Abkömmlinge, setzt die Auflösung auf 150x150. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBitmap](#getBitmap-com.aspose.pdf.Page-) | Konvertiert die Seite in {@link java.awt.image.BufferedImage}. |
| [getCoordinateType](#getCoordinateType--) | Ermittelt den Seitencoordinate-Typ (Media-/Crop-Boxen). Der CropBox-Wert wird standardmäßig verwendet. |
| [getCropRectangle](#getCropRectangle--) | Gibt das Rechteck zurück, das den Bereich definiert, der in ein Bild konvertiert wird. Der Standardwert ist null, in diesem Fall wird die gesamte Seite in ein Bild konvertiert. |
| [getFormPresentationMode](#getFormPresentationMode--) | Liefert den Formularpräsentationsmodus. |
| [getHeight](#getHeight--) | Liefert die Bildausgabehöhe. |
| [getRenderingOptions](#getRenderingOptions--) | Ruft Rendering-Optionen ab. |
| [getResolution](#getResolution--) | Ruft Bildauflösung ab. |
| [getWidth](#getWidth--) | Ruft Bildausgabe-Breite ab. |
| [isShadingPerformanceHigh](#isShadingPerformanceHigh--) | Ist die Leistung der Schattierungsprozesse hoch. Standardmäßig ist sie wahr. |
| [setCoordinateType](#setCoordinateType-com.aspose.pdf.PageCoordinateType-) | Setzt den Seitencoordinate-Typ (Media-/Crop-Boxen). Der CropBox-Wert wird standardmäßig verwendet. |
| [setCropRectangle](#setCropRectangle-com.aspose.pdf.Rectangle-) | Setzt das Rechteck, das den Bereich definiert, der in ein Bild konvertiert wird. |
| [setFormPresentationMode](#setFormPresentationMode-int-) | Setzt den Formular-Präsentationsmodus. |
| [setRenderingOptions](#setRenderingOptions-com.aspose.pdf.RenderingOptions-) | Setzt Rendering-Optionen. |
| [setShadingPerformanceHigh](#setShadingPerformanceHigh-boolean-) | Setzt die Leistung der Schattierungsprozesse auf hoch oder nicht. |

### ImageDevice {#ImageDevice--}
```
public ImageDevice()
```

Abstrakter Initialisierer für {@code ImageDevice}-Abkömmlinge, setzt die Auflösung auf 150x150.

### ImageDevice {#ImageDevice-int-int-}
```
public ImageDevice(int width, int height)
```

Initialisiert eine neue Instanz der {@code JpegDevice}-Klasse mit den angegebenen Bildabmessungen und der Standardauflösung (=150).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Breite |  | Bildausgabe-Breite. |
| Höhe |  | Bildausgabe-Höhe. |

### ImageDevice {#ImageDevice-int-int-com.aspose.pdf.devices.Resolution-}
Abstrakter Initialisierer für {@code ImageDevice}-Abkömmlinge, setzt die Auflösung auf 150x150.

### ImageDevice {#ImageDevice-com.aspose.pdf.PageSize-}
Abstrakter Initialisierer für {@code ImageDevice}-Abkömmlinge, setzt die Auflösung auf 150x150.

### ImageDevice {#ImageDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-}
Abstrakter Initialisierer für {@code ImageDevice}-Abkömmlinge, setzt die Auflösung auf 150x150.

### ImageDevice {#ImageDevice-com.aspose.pdf.devices.Resolution-}
Abstrakter Initialisierer für {@code ImageDevice}-Abkömmlinge, setzt die Auflösung auf 150x150.

### getBitmap {#getBitmap-com.aspose.pdf.Page-}
Konvertiert die Seite in {@link java.awt.image.BufferedImage}.

### getCoordinateType {#getCoordinateType--}
```
public PageCoordinateType getCoordinateType()
```

Ermittelt den Seitencoordinate-Typ (Media-/Crop-Boxen). Der CropBox-Wert wird standardmäßig verwendet.

**Returns:**
PageCoordinateType-Element @see PageCoordinateType

### getCropRectangle {#getCropRectangle--}
```
public Rectangle getCropRectangle()
```

Gibt das Rechteck zurück, das den Bereich definiert, der in ein Bild konvertiert wird. Der Standardwert ist null, in diesem Fall wird die gesamte Seite in ein Bild konvertiert.

**Returns:**
Rectangle-Objekt

### getFormPresentationMode {#getFormPresentationMode--}
```
public int getFormPresentationMode()
```

Liefert den Formularpräsentationsmodus.

**Returns:**
FormPresentationMode-Element @see FormPresentationMode

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
RenderingOptions-Element

### getResolution {#getResolution--}
```
public Resolution getResolution()
```

Ruft Bildauflösung ab.

**Returns:**
Auflösungselement

### getWidth {#getWidth--}
```
public int getWidth()
```

Ruft Bildausgabe-Breite ab.

**Returns:**
int-Wert

### isShadingPerformanceHigh {#isShadingPerformanceHigh--}
```
public static boolean isShadingPerformanceHigh()
```

Ist die Leistung der Schattierungsprozesse hoch. Standardmäßig ist sie wahr.

**Returns:**
boolescher Wert

### setCoordinateType {#setCoordinateType-com.aspose.pdf.PageCoordinateType-}
Setzt den Seitencoordinate-Typ (Media-/Crop-Boxen). Der CropBox-Wert wird standardmäßig verwendet.

### setCropRectangle {#setCropRectangle-com.aspose.pdf.Rectangle-}
Setzt das Rechteck, das den Bereich definiert, der in ein Bild konvertiert wird.

### setFormPresentationMode {#setFormPresentationMode-int-}
```
public void setFormPresentationMode(int value)
```

Setzt den Formular-Präsentationsmodus.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | FormPresentationMode-Element @see FormPresentationMode |

### setRenderingOptions {#setRenderingOptions-com.aspose.pdf.RenderingOptions-}
Setzt Rendering-Optionen.

### setShadingPerformanceHigh {#setShadingPerformanceHigh-boolean-}
```
public static void setShadingPerformanceHigh(boolean value)
```

Setzt die Leistung der Schattierungsprozesse auf hoch oder nicht.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |
