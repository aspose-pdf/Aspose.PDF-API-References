---
title: "ImageDevice"
linktitle: "ImageDevice"
second_title: "Aspose.PDF för Java API-referens"
description: "En abstrakt klass för bildenheter."
type: docs
weight: 110
url: /sv/java/com.aspose.pdf.devices/imagedevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.ImageDevice

```
public abstract class ImageDevice extends PageDevice
```

En abstrakt klass för bildenheter.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [ImageDevice](#ImageDevice--) | Abstrakt initierare för {@code ImageDevice}-avledda, sätt upplösning till 150x150. |
| [ImageDevice](#ImageDevice-int-int-) | Initierar en ny instans av {@code JpegDevice}-klassen med angivna bilddimensioner och standardupplösning (=150). |
| [ImageDevice](#ImageDevice-int-int-com.aspose.pdf.devices.Resolution-) | Abstrakt initierare för {@code ImageDevice}-avledda, sätt upplösning till 150x150. |
| [ImageDevice](#ImageDevice-com.aspose.pdf.PageSize-) | Abstrakt initierare för {@code ImageDevice}-avledda, sätt upplösning till 150x150. |
| [ImageDevice](#ImageDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-) | Abstrakt initierare för {@code ImageDevice}-avledda, sätt upplösning till 150x150. |
| [ImageDevice](#ImageDevice-com.aspose.pdf.devices.Resolution-) | Abstrakt initierare för {@code ImageDevice}-avledda, sätt upplösning till 150x150. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBitmap](#getBitmap-com.aspose.pdf.Page-) | Konverterar sidan till {@link java.awt.image.BufferedImage}. |
| [getCoordinateType](#getCoordinateType--) | Hämtar sidans koordinattyp (Media-/Crop-boxar). CropBox-värdet används som standard. |
| [getCropRectangle](#getCropRectangle--) | Hämta rektangel som definierar området som kommer att konverteras till en bild. Standardvärdet är null, i vilket fall hela sidan konverteras till en bild. |
| [getFormPresentationMode](#getFormPresentationMode--) | Hämtar formulärpresentationsläge. |
| [getHeight](#getHeight--) | Hämtar bildens utskrifts‑höjd. |
| [getRenderingOptions](#getRenderingOptions--) | Hämtar renderingsalternativ. |
| [getResolution](#getResolution--) | Hämtar bildupplösning. |
| [getWidth](#getWidth--) | Hämtar bildens utskrifts‑bredd. |
| [isShadingPerformanceHigh](#isShadingPerformanceHigh--) | Är prestandan för skuggningsprocesser hög. Som standard är den sann. |
| [setCoordinateType](#setCoordinateType-com.aspose.pdf.PageCoordinateType-) | Ställer in sidkoordinattypen (Media/Crop-boxar). CropBox-värdet används som standard. |
| [setCropRectangle](#setCropRectangle-com.aspose.pdf.Rectangle-) | Ange rektangel som definierar området som kommer att konverteras till en bild. |
| [setFormPresentationMode](#setFormPresentationMode-int-) | Ställer in formulärets presentationsläge. |
| [setRenderingOptions](#setRenderingOptions-com.aspose.pdf.RenderingOptions-) | Ställer in renderingsalternativ. |
| [setShadingPerformanceHigh](#setShadingPerformanceHigh-boolean-) | Ställer in om prestandan för skuggningsprocesser är hög eller inte. |

### ImageDevice {#ImageDevice--}
```
public ImageDevice()
```

Abstrakt initierare för {@code ImageDevice}-avledda, sätt upplösning till 150x150.

### ImageDevice {#ImageDevice-int-int-}
```
public ImageDevice(int width, int height)
```

Initierar en ny instans av {@code JpegDevice}-klassen med angivna bilddimensioner och standardupplösning (=150).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bredd |  | Bildens utskriftsbredd. |
| höjd |  | Bildens utskrifts‑höjd. |

### ImageDevice {#ImageDevice-int-int-com.aspose.pdf.devices.Resolution-}
Abstrakt initierare för {@code ImageDevice}-avledda, sätt upplösning till 150x150.

### ImageDevice {#ImageDevice-com.aspose.pdf.PageSize-}
Abstrakt initierare för {@code ImageDevice}-avledda, sätt upplösning till 150x150.

### ImageDevice {#ImageDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-}
Abstrakt initierare för {@code ImageDevice}-avledda, sätt upplösning till 150x150.

### ImageDevice {#ImageDevice-com.aspose.pdf.devices.Resolution-}
Abstrakt initierare för {@code ImageDevice}-avledda, sätt upplösning till 150x150.

### getBitmap {#getBitmap-com.aspose.pdf.Page-}
Konverterar sidan till {@link java.awt.image.BufferedImage}.

### getCoordinateType {#getCoordinateType--}
```
public PageCoordinateType getCoordinateType()
```

Hämtar sidans koordinattyp (Media-/Crop-boxar). CropBox-värdet används som standard.

**Returns:**
PageCoordinateType-element @see PageCoordinateType

### getCropRectangle {#getCropRectangle--}
```
public Rectangle getCropRectangle()
```

Hämta rektangel som definierar området som kommer att konverteras till en bild. Standardvärdet är null, i vilket fall hela sidan konverteras till en bild.

**Returns:**
Rectangle‑objekt

### getFormPresentationMode {#getFormPresentationMode--}
```
public int getFormPresentationMode()
```

Hämtar formulärpresentationsläge.

**Returns:**
FormPresentationMode-element @see FormPresentationMode

### getHeight {#getHeight--}
```
public int getHeight()
```

Hämtar bildens utskrifts‑höjd.

**Returns:**
int‑värde

### getRenderingOptions {#getRenderingOptions--}
```
public RenderingOptions getRenderingOptions()
```

Hämtar renderingsalternativ.

**Returns:**
RenderingOptions-element

### getResolution {#getResolution--}
```
public Resolution getResolution()
```

Hämtar bildupplösning.

**Returns:**
Upplösningselement

### getWidth {#getWidth--}
```
public int getWidth()
```

Hämtar bildens utskrifts‑bredd.

**Returns:**
int‑värde

### isShadingPerformanceHigh {#isShadingPerformanceHigh--}
```
public static boolean isShadingPerformanceHigh()
```

Är prestandan för skuggningsprocesser hög. Som standard är den sann.

**Returns:**
booleskt värde

### setCoordinateType {#setCoordinateType-com.aspose.pdf.PageCoordinateType-}
Ställer in sidkoordinattypen (Media/Crop-boxar). CropBox-värdet används som standard.

### setCropRectangle {#setCropRectangle-com.aspose.pdf.Rectangle-}
Ange rektangel som definierar området som kommer att konverteras till en bild.

### setFormPresentationMode {#setFormPresentationMode-int-}
```
public void setFormPresentationMode(int value)
```

Ställer in formulärets presentationsläge.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | FormPresentationMode-element @see FormPresentationMode |

### setRenderingOptions {#setRenderingOptions-com.aspose.pdf.RenderingOptions-}
Ställer in renderingsalternativ.

### setShadingPerformanceHigh {#setShadingPerformanceHigh-boolean-}
```
public static void setShadingPerformanceHigh(boolean value)
```

Ställer in om prestandan för skuggningsprocesser är hög eller inte.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |
