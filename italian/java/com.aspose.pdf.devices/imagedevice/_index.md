---
title: "ImageDevice"
linktitle: "ImageDevice"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Una classe astratta per dispositivi immagine."
type: docs
weight: 110
url: /it/java/com.aspose.pdf.devices/imagedevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.ImageDevice

```
public abstract class ImageDevice extends PageDevice
```

Una classe astratta per dispositivi immagine.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [ImageDevice](#ImageDevice--) | Inizializzatore astratto per i discendenti di {@code ImageDevice}, imposta la risoluzione a 150x150. |
| [ImageDevice](#ImageDevice-int-int-) | Inizializza una nuova istanza della classe {@code JpegDevice} con le dimensioni dell'immagine fornite e la risoluzione predefinita (=150). |
| [ImageDevice](#ImageDevice-int-int-com.aspose.pdf.devices.Resolution-) | Inizializzatore astratto per i discendenti di {@code ImageDevice}, imposta la risoluzione a 150x150. |
| [ImageDevice](#ImageDevice-com.aspose.pdf.PageSize-) | Inizializzatore astratto per i discendenti di {@code ImageDevice}, imposta la risoluzione a 150x150. |
| [ImageDevice](#ImageDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-) | Inizializzatore astratto per i discendenti di {@code ImageDevice}, imposta la risoluzione a 150x150. |
| [ImageDevice](#ImageDevice-com.aspose.pdf.devices.Resolution-) | Inizializzatore astratto per i discendenti di {@code ImageDevice}, imposta la risoluzione a 150x150. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBitmap](#getBitmap-com.aspose.pdf.Page-) | Converte la pagina in {@link java.awt.image.BufferedImage}. |
| [getCoordinateType](#getCoordinateType--) | Ottiene il tipo di coordinate della pagina (box Media/Crop). Il valore CropBox è usato per impostazione predefinita. |
| [getCropRectangle](#getCropRectangle--) | Ottieni il rettangolo che definisce l'area da convertire in immagine. Il valore predefinito è null, nel qual caso l'intera pagina viene convertita in un'immagine. |
| [getFormPresentationMode](#getFormPresentationMode--) | Ottiene la modalità di presentazione del modulo. |
| [getHeight](#getHeight--) | Ottiene l'altezza dell'output dell'immagine. |
| [getRenderingOptions](#getRenderingOptions--) | Ottiene le opzioni di rendering. |
| [getResolution](#getResolution--) | Ottiene la risoluzione dell'immagine. |
| [getWidth](#getWidth--) | Ottiene la larghezza dell'output dell'immagine. |
| [isShadingPerformanceHigh](#isShadingPerformanceHigh--) | Indica se le prestazioni dei processi di ombreggiatura sono alte. Per impostazione predefinita è vero. |
| [setCoordinateType](#setCoordinateType-com.aspose.pdf.PageCoordinateType-) | Imposta il tipo di coordinate della pagina (box Media/Crop). Il valore CropBox è usato per impostazione predefinita. |
| [setCropRectangle](#setCropRectangle-com.aspose.pdf.Rectangle-) | Imposta il rettangolo che definisce l'area che sarà convertita in un'immagine. |
| [setFormPresentationMode](#setFormPresentationMode-int-) | Imposta la modalità di presentazione del modulo. |
| [setRenderingOptions](#setRenderingOptions-com.aspose.pdf.RenderingOptions-) | Imposta le opzioni di rendering. |
| [setShadingPerformanceHigh](#setShadingPerformanceHigh-boolean-) | Imposta se le prestazioni dei processi di ombreggiatura sono alte o meno. |

### ImageDevice {#ImageDevice--}
```
public ImageDevice()
```

Inizializzatore astratto per i discendenti di {@code ImageDevice}, imposta la risoluzione a 150x150.

### ImageDevice {#ImageDevice-int-int-}
```
public ImageDevice(int width, int height)
```

Inizializza una nuova istanza della classe {@code JpegDevice} con le dimensioni dell'immagine fornite e la risoluzione predefinita (=150).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| larghezza |  | Larghezza dell'output dell'immagine. |
| altezza |  | Altezza dell'output dell'immagine. |

### ImageDevice {#ImageDevice-int-int-com.aspose.pdf.devices.Resolution-}
Inizializzatore astratto per i discendenti di {@code ImageDevice}, imposta la risoluzione a 150x150.

### ImageDevice {#ImageDevice-com.aspose.pdf.PageSize-}
Inizializzatore astratto per i discendenti di {@code ImageDevice}, imposta la risoluzione a 150x150.

### ImageDevice {#ImageDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-}
Inizializzatore astratto per i discendenti di {@code ImageDevice}, imposta la risoluzione a 150x150.

### ImageDevice {#ImageDevice-com.aspose.pdf.devices.Resolution-}
Inizializzatore astratto per i discendenti di {@code ImageDevice}, imposta la risoluzione a 150x150.

### getBitmap {#getBitmap-com.aspose.pdf.Page-}
Converte la pagina in {@link java.awt.image.BufferedImage}.

### getCoordinateType {#getCoordinateType--}
```
public PageCoordinateType getCoordinateType()
```

Ottiene il tipo di coordinate della pagina (box Media/Crop). Il valore CropBox è usato per impostazione predefinita.

**Returns:**
Elemento PageCoordinateType @see PageCoordinateType

### getCropRectangle {#getCropRectangle--}
```
public Rectangle getCropRectangle()
```

Ottieni il rettangolo che definisce l'area da convertire in immagine. Il valore predefinito è null, nel qual caso l'intera pagina viene convertita in un'immagine.

**Returns:**
oggetto Rectangle

### getFormPresentationMode {#getFormPresentationMode--}
```
public int getFormPresentationMode()
```

Ottiene la modalità di presentazione del modulo.

**Returns:**
FormPresentationMode elemento @see FormPresentationMode

### getHeight {#getHeight--}
```
public int getHeight()
```

Ottiene l'altezza dell'output dell'immagine.

**Returns:**
valore int

### getRenderingOptions {#getRenderingOptions--}
```
public RenderingOptions getRenderingOptions()
```

Ottiene le opzioni di rendering.

**Returns:**
RenderingOptions elemento

### getResolution {#getResolution--}
```
public Resolution getResolution()
```

Ottiene la risoluzione dell'immagine.

**Returns:**
Elemento Resolution

### getWidth {#getWidth--}
```
public int getWidth()
```

Ottiene la larghezza dell'output dell'immagine.

**Returns:**
valore int

### isShadingPerformanceHigh {#isShadingPerformanceHigh--}
```
public static boolean isShadingPerformanceHigh()
```

Indica se le prestazioni dei processi di ombreggiatura sono alte. Per impostazione predefinita è vero.

**Returns:**
valore booleano

### setCoordinateType {#setCoordinateType-com.aspose.pdf.PageCoordinateType-}
Imposta il tipo di coordinate della pagina (box Media/Crop). Il valore CropBox è usato per impostazione predefinita.

### setCropRectangle {#setCropRectangle-com.aspose.pdf.Rectangle-}
Imposta il rettangolo che definisce l'area che sarà convertita in un'immagine.

### setFormPresentationMode {#setFormPresentationMode-int-}
```
public void setFormPresentationMode(int value)
```

Imposta la modalità di presentazione del modulo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | FormPresentationMode elemento @see FormPresentationMode |

### setRenderingOptions {#setRenderingOptions-com.aspose.pdf.RenderingOptions-}
Imposta le opzioni di rendering.

### setShadingPerformanceHigh {#setShadingPerformanceHigh-boolean-}
```
public static void setShadingPerformanceHigh(boolean value)
```

Imposta se le prestazioni dei processi di ombreggiatura sono alte o meno.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |
