---
title: "TiffDevice"
linktitle: "TiffDevice"
second_title: "Aspose.PDF för Java API-referens"
description: "Denna klass hjälper till att spara pdf-dokument sida för sida i en enda tiff-bild."
type: docs
weight: 210
url: /sv/java/com.aspose.pdf.devices/tiffdevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.DocumentDevice com.aspose.pdf.devices.TiffDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.DocumentDevice com.aspose.pdf.devices.TiffDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.DocumentDevice com.aspose.pdf.devices.TiffDevice, com.aspose.pdf.devices.DocumentDevice, com.aspose.pdf.devices.TiffDevice

```
public final class TiffDevice extends DocumentDevice
```

Denna klass hjälper till att spara pdf-dokument sida för sida i en enda tiff-bild.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [TiffDevice](#TiffDevice--) | Initierar en ny instans av {@code TiffDevice}-klassen med standardinställningar. |
| [TiffDevice](#TiffDevice-int-int-) | Initierar en ny instans av {@code TiffDevice}-klassen. |
| [TiffDevice](#TiffDevice-int-int-com.aspose.pdf.devices.Resolution-) | Initierar en ny instans av {@code TiffDevice}-klassen med standardinställningar. |
| [TiffDevice](#TiffDevice-int-int-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-) | Initierar en ny instans av {@code TiffDevice}-klassen med standardinställningar. |
| [TiffDevice](#TiffDevice-int-int-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Initierar en ny instans av {@code TiffDevice}-klassen med standardinställningar. |
| [TiffDevice](#TiffDevice-int-int-com.aspose.pdf.devices.TiffSettings-) | Initierar en ny instans av {@code TiffDevice}-klassen med standardinställningar. |
| [TiffDevice](#TiffDevice-int-int-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Initierar en ny instans av {@code TiffDevice}-klassen med standardinställningar. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.PageSize-) | Initierar en ny instans av {@code TiffDevice}-klassen med standardinställningar. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-) | Initierar en ny instans av {@code TiffDevice}-klassen med standardinställningar. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-) | Initierar en ny instans av {@code TiffDevice}-klassen med standardinställningar. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Initierar en ny instans av {@code TiffDevice}-klassen med standardinställningar. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-) | Initierar en ny instans av {@code TiffDevice}-klassen med standardinställningar. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Initierar en ny instans av {@code TiffDevice}-klassen med standardinställningar. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.devices.Resolution-) | Initierar en ny instans av {@code TiffDevice}-klassen med standardinställningar. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-) | Initierar en ny instans av {@code TiffDevice}-klassen med standardinställningar. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Initierar en ny instans av {@code TiffDevice}-klassen med standardinställningar. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.devices.TiffSettings-) | Initierar en ny instans av {@code TiffDevice}-klassen med standardinställningar. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Initierar en ny instans av {@code TiffDevice}-klassen med standardinställningar. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [binarizeBradley](#binarizeBradley-java.io.InputStream-java.io.OutputStream-double-) | Utför Bradley-binarisering för inmatningsström. |
| [getCropRectangle](#getCropRectangle--) | Hämta rektangel som definierar området som kommer att konverteras till en bild. Standardvärdet är null, i vilket fall hela bilden konverteras till en sida. |
| [getFormPresentationMode](#getFormPresentationMode--) | Hämtar formulärpresentationsläge. |
| [getHeight](#getHeight--) | Hämtar bildens utskrifts‑höjd. |
| [getRenderingOptions](#getRenderingOptions--) | Hämtar renderingsalternativ. |
| [getResolution](#getResolution--) | Hämtar bildupplösning. |
| [getSettings](#getSettings--) | Hämtar inställningar för att mappa PDF till TIFF‑bild. |
| [getWidth](#getWidth--) | Hämtar bildens utskrifts‑bredd. |
| [process](#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-) | Konverterar vissa dokumentsidor till TIFF och sparar dem i utskriftsströmmen. |
| [processInternal](#processInternal-com.aspose.pdf.IDocument-int-int-com.aspose.ms.System.IO.Stream-) | Konverterar vissa dokumentsidor till TIFF och sparar dem i utskriftsströmmen. |
| [processInternal](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | Utför någon operation på den angivna sidan, t.ex. |
| [setCropRectangle](#setCropRectangle-com.aspose.pdf.Rectangle-) | Ange rektangel som definierar området som kommer att konverteras till en bild. |
| [setFormPresentationMode](#setFormPresentationMode-int-) | Hämtar formulärpresentationsläge. |
| [setRenderingOptions](#setRenderingOptions-com.aspose.pdf.RenderingOptions-) | Ställer in renderingsalternativ. |

### TiffDevice {#TiffDevice--}
```
public TiffDevice()
```

Initierar en ny instans av {@code TiffDevice}-klassen med standardinställningar.

### TiffDevice {#TiffDevice-int-int-}
```
public TiffDevice(int width, int height)
```

Initierar en ny instans av {@code TiffDevice}-klassen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bredd |  | Bildens utskriftsbredd. |
| höjd |  | Bildens utskrifts‑höjd. |

### TiffDevice {#TiffDevice-int-int-com.aspose.pdf.devices.Resolution-}
Initierar en ny instans av {@code TiffDevice}-klassen med standardinställningar.

### TiffDevice {#TiffDevice-int-int-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-}
Initierar en ny instans av {@code TiffDevice}-klassen med standardinställningar.

### TiffDevice {#TiffDevice-int-int-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
Initierar en ny instans av {@code TiffDevice}-klassen med standardinställningar.

### TiffDevice {#TiffDevice-int-int-com.aspose.pdf.devices.TiffSettings-}
Initierar en ny instans av {@code TiffDevice}-klassen med standardinställningar.

### TiffDevice {#TiffDevice-int-int-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
Initierar en ny instans av {@code TiffDevice}-klassen med standardinställningar.

### TiffDevice {#TiffDevice-com.aspose.pdf.PageSize-}
Initierar en ny instans av {@code TiffDevice}-klassen med standardinställningar.

### TiffDevice {#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-}
Initierar en ny instans av {@code TiffDevice}-klassen med standardinställningar.

### TiffDevice {#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-}
Initierar en ny instans av {@code TiffDevice}-klassen med standardinställningar.

### TiffDevice {#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
Initierar en ny instans av {@code TiffDevice}-klassen med standardinställningar.

### TiffDevice {#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-}
Initierar en ny instans av {@code TiffDevice}-klassen med standardinställningar.

### TiffDevice {#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
Initierar en ny instans av {@code TiffDevice}-klassen med standardinställningar.

### TiffDevice {#TiffDevice-com.aspose.pdf.devices.Resolution-}
Initierar en ny instans av {@code TiffDevice}-klassen med standardinställningar.

### TiffDevice {#TiffDevice-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-}
Initierar en ny instans av {@code TiffDevice}-klassen med standardinställningar.

### TiffDevice {#TiffDevice-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
Initierar en ny instans av {@code TiffDevice}-klassen med standardinställningar.

### TiffDevice {#TiffDevice-com.aspose.pdf.devices.TiffSettings-}
Initierar en ny instans av {@code TiffDevice}-klassen med standardinställningar.

### TiffDevice {#TiffDevice-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
Initierar en ny instans av {@code TiffDevice}-klassen med standardinställningar.

### binarizeBradley {#binarizeBradley-java.io.InputStream-java.io.OutputStream-double-}
Utför Bradley-binarisering för inmatningsström.

### getCropRectangle {#getCropRectangle--}
```
public Rectangle getCropRectangle()
```

Hämta rektangel som definierar området som kommer att konverteras till en bild. Standardvärdet är null, i vilket fall hela bilden konverteras till en sida.

**Returns:**
Rectangle‑objekt

### getFormPresentationMode {#getFormPresentationMode--}
```
public int getFormPresentationMode()
```

Hämtar formulärpresentationsläge.

**Returns:**
FormPresentationMode‑värde @see FormPresentationMode

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
renderingsalternativ.

### getResolution {#getResolution--}
```
public Resolution getResolution()
```

Hämtar bildupplösning.

**Returns:**
Upplösningselement

### getSettings {#getSettings--}
```
public TiffSettings getSettings()
```

Hämtar inställningar för att mappa PDF till TIFF‑bild.

**Returns:**
TiffSettings‑element

### getWidth {#getWidth--}
```
public int getWidth()
```

Hämtar bildens utskrifts‑bredd.

**Returns:**
int‑värde

### process {#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-}
Konverterar vissa dokumentsidor till TIFF och sparar dem i utskriftsströmmen.

### processInternal {#processInternal-com.aspose.pdf.IDocument-int-int-com.aspose.ms.System.IO.Stream-}
Konverterar vissa dokumentsidor till TIFF och sparar dem i utskriftsströmmen.

### processInternal {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
Utför någon operation på den angivna sidan, t.ex.

### setCropRectangle {#setCropRectangle-com.aspose.pdf.Rectangle-}
Ange rektangel som definierar området som kommer att konverteras till en bild.

### setFormPresentationMode {#setFormPresentationMode-int-}
```
public void setFormPresentationMode(int value)
```

Hämtar formulärpresentationsläge.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int värde @see FormPresentationMode |

### setRenderingOptions {#setRenderingOptions-com.aspose.pdf.RenderingOptions-}
Ställer in renderingsalternativ.
