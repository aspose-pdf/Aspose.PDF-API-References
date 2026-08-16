---
title: "ImageDevice"
linktitle: "ImageDevice"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Una clase abstracta para dispositivos de imagen."
type: docs
weight: 110
url: /es/java/com.aspose.pdf.devices/imagedevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.ImageDevice

```
public abstract class ImageDevice extends PageDevice
```

Una clase abstracta para dispositivos de imagen.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [ImageDevice](#ImageDevice--) | Inicializador abstracto para los descendientes de {@code ImageDevice}, establece la resolución a 150x150. |
| [ImageDevice](#ImageDevice-int-int-) | Inicializa una nueva instancia de la clase {@code JpegDevice} con las dimensiones de imagen proporcionadas y resolución predeterminada (=150). |
| [ImageDevice](#ImageDevice-int-int-com.aspose.pdf.devices.Resolution-) | Inicializador abstracto para los descendientes de {@code ImageDevice}, establece la resolución a 150x150. |
| [ImageDevice](#ImageDevice-com.aspose.pdf.PageSize-) | Inicializador abstracto para los descendientes de {@code ImageDevice}, establece la resolución a 150x150. |
| [ImageDevice](#ImageDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-) | Inicializador abstracto para los descendientes de {@code ImageDevice}, establece la resolución a 150x150. |
| [ImageDevice](#ImageDevice-com.aspose.pdf.devices.Resolution-) | Inicializador abstracto para los descendientes de {@code ImageDevice}, establece la resolución a 150x150. |

## Métodos

| Método | Descripción |
| --- | --- |
| [getBitmap](#getBitmap-com.aspose.pdf.Page-) | Convierte la página en {@link java.awt.image.BufferedImage}. |
| [getCoordinateType](#getCoordinateType--) | Obtiene el tipo de coordenada de la página (cajas Media/Crop). El valor CropBox se usa por defecto. |
| [getCropRectangle](#getCropRectangle--) | Obtiene el rectángulo que define el área que se convertirá en una imagen. El valor predeterminado es null, en cuyo caso toda la página se convierte en una imagen. |
| [getFormPresentationMode](#getFormPresentationMode--) | Obtiene el modo de presentación del formulario. |
| [getHeight](#getHeight--) | Obtiene la altura de salida de la imagen. |
| [getRenderingOptions](#getRenderingOptions--) | Obtiene las opciones de renderizado. |
| [getResolution](#getResolution--) | Obtiene la resolución de la imagen. |
| [getWidth](#getWidth--) | Obtiene el ancho de salida de la imagen. |
| [isShadingPerformanceHigh](#isShadingPerformanceHigh--) | Indica si el rendimiento de los procesos de sombreado es alto. Por defecto es verdadero. |
| [setCoordinateType](#setCoordinateType-com.aspose.pdf.PageCoordinateType-) | Establece el tipo de coordenada de la página (cajas Media/Crop). El valor CropBox se usa por defecto. |
| [setCropRectangle](#setCropRectangle-com.aspose.pdf.Rectangle-) | Establece el rectángulo que define el área que se convertirá en una imagen. |
| [setFormPresentationMode](#setFormPresentationMode-int-) | Establece el modo de presentación del formulario. |
| [setRenderingOptions](#setRenderingOptions-com.aspose.pdf.RenderingOptions-) | Establece las opciones de renderizado. |
| [setShadingPerformanceHigh](#setShadingPerformanceHigh-boolean-) | Establece si el rendimiento de los procesos de sombreado es alto o no. |

### ImageDevice {#ImageDevice--}
```
public ImageDevice()
```

Inicializador abstracto para los descendientes de {@code ImageDevice}, establece la resolución a 150x150.

### ImageDevice {#ImageDevice-int-int-}
```
public ImageDevice(int width, int height)
```

Inicializa una nueva instancia de la clase {@code JpegDevice} con las dimensiones de imagen proporcionadas y resolución predeterminada (=150).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ancho |  | Ancho de salida de la imagen. |
| altura |  | Altura de salida de la imagen. |

### ImageDevice {#ImageDevice-int-int-com.aspose.pdf.devices.Resolution-}
Inicializador abstracto para los descendientes de {@code ImageDevice}, establece la resolución a 150x150.

### ImageDevice {#ImageDevice-com.aspose.pdf.PageSize-}
Inicializador abstracto para los descendientes de {@code ImageDevice}, establece la resolución a 150x150.

### ImageDevice {#ImageDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-}
Inicializador abstracto para los descendientes de {@code ImageDevice}, establece la resolución a 150x150.

### ImageDevice {#ImageDevice-com.aspose.pdf.devices.Resolution-}
Inicializador abstracto para los descendientes de {@code ImageDevice}, establece la resolución a 150x150.

### getBitmap {#getBitmap-com.aspose.pdf.Page-}
Convierte la página en {@link java.awt.image.BufferedImage}.

### getCoordinateType {#getCoordinateType--}
```
public PageCoordinateType getCoordinateType()
```

Obtiene el tipo de coordenada de la página (cajas Media/Crop). El valor CropBox se usa por defecto.

**Returns:**
PageCoordinateType elemento @see PageCoordinateType

### getCropRectangle {#getCropRectangle--}
```
public Rectangle getCropRectangle()
```

Obtiene el rectángulo que define el área que se convertirá en una imagen. El valor predeterminado es null, en cuyo caso toda la página se convierte en una imagen.

**Returns:**
objeto Rectangle

### getFormPresentationMode {#getFormPresentationMode--}
```
public int getFormPresentationMode()
```

Obtiene el modo de presentación del formulario.

**Returns:**
Elemento FormPresentationMode @see FormPresentationMode

### getHeight {#getHeight--}
```
public int getHeight()
```

Obtiene la altura de salida de la imagen.

**Returns:**
valor int

### getRenderingOptions {#getRenderingOptions--}
```
public RenderingOptions getRenderingOptions()
```

Obtiene las opciones de renderizado.

**Returns:**
Elemento RenderingOptions

### getResolution {#getResolution--}
```
public Resolution getResolution()
```

Obtiene la resolución de la imagen.

**Returns:**
Elemento Resolution

### getWidth {#getWidth--}
```
public int getWidth()
```

Obtiene el ancho de salida de la imagen.

**Returns:**
valor int

### isShadingPerformanceHigh {#isShadingPerformanceHigh--}
```
public static boolean isShadingPerformanceHigh()
```

Indica si el rendimiento de los procesos de sombreado es alto. Por defecto es verdadero.

**Returns:**
valor booleano

### setCoordinateType {#setCoordinateType-com.aspose.pdf.PageCoordinateType-}
Establece el tipo de coordenada de la página (cajas Media/Crop). El valor CropBox se usa por defecto.

### setCropRectangle {#setCropRectangle-com.aspose.pdf.Rectangle-}
Establece el rectángulo que define el área que se convertirá en una imagen.

### setFormPresentationMode {#setFormPresentationMode-int-}
```
public void setFormPresentationMode(int value)
```

Establece el modo de presentación del formulario.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | Elemento FormPresentationMode @see FormPresentationMode |

### setRenderingOptions {#setRenderingOptions-com.aspose.pdf.RenderingOptions-}
Establece las opciones de renderizado.

### setShadingPerformanceHigh {#setShadingPerformanceHigh-boolean-}
```
public static void setShadingPerformanceHigh(boolean value)
```

Establece si el rendimiento de los procesos de sombreado es alto o no.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |
