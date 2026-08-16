---
title: "TiffDevice"
linktitle: "TiffDevice"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Esta clase ayuda a guardar el documento pdf página por página en una única imagen tiff."
type: docs
weight: 210
url: /es/java/com.aspose.pdf.devices/tiffdevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.DocumentDevice com.aspose.pdf.devices.TiffDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.DocumentDevice com.aspose.pdf.devices.TiffDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.DocumentDevice com.aspose.pdf.devices.TiffDevice, com.aspose.pdf.devices.DocumentDevice, com.aspose.pdf.devices.TiffDevice

```
public final class TiffDevice extends DocumentDevice
```

Esta clase ayuda a guardar el documento pdf página por página en una única imagen tiff.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [TiffDevice](#TiffDevice--) | Inicializa una nueva instancia de la clase {@code TiffDevice} con la configuración predeterminada. |
| [TiffDevice](#TiffDevice-int-int-) | Inicializa una nueva instancia de la clase {@code TiffDevice}. |
| [TiffDevice](#TiffDevice-int-int-com.aspose.pdf.devices.Resolution-) | Inicializa una nueva instancia de la clase {@code TiffDevice} con la configuración predeterminada. |
| [TiffDevice](#TiffDevice-int-int-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-) | Inicializa una nueva instancia de la clase {@code TiffDevice} con la configuración predeterminada. |
| [TiffDevice](#TiffDevice-int-int-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Inicializa una nueva instancia de la clase {@code TiffDevice} con la configuración predeterminada. |
| [TiffDevice](#TiffDevice-int-int-com.aspose.pdf.devices.TiffSettings-) | Inicializa una nueva instancia de la clase {@code TiffDevice} con la configuración predeterminada. |
| [TiffDevice](#TiffDevice-int-int-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Inicializa una nueva instancia de la clase {@code TiffDevice} con la configuración predeterminada. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.PageSize-) | Inicializa una nueva instancia de la clase {@code TiffDevice} con la configuración predeterminada. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-) | Inicializa una nueva instancia de la clase {@code TiffDevice} con la configuración predeterminada. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-) | Inicializa una nueva instancia de la clase {@code TiffDevice} con la configuración predeterminada. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Inicializa una nueva instancia de la clase {@code TiffDevice} con la configuración predeterminada. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-) | Inicializa una nueva instancia de la clase {@code TiffDevice} con la configuración predeterminada. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Inicializa una nueva instancia de la clase {@code TiffDevice} con la configuración predeterminada. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.devices.Resolution-) | Inicializa una nueva instancia de la clase {@code TiffDevice} con la configuración predeterminada. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-) | Inicializa una nueva instancia de la clase {@code TiffDevice} con la configuración predeterminada. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Inicializa una nueva instancia de la clase {@code TiffDevice} con la configuración predeterminada. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.devices.TiffSettings-) | Inicializa una nueva instancia de la clase {@code TiffDevice} con la configuración predeterminada. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Inicializa una nueva instancia de la clase {@code TiffDevice} con la configuración predeterminada. |

## Métodos

| Método | Descripción |
| --- | --- |
| [binarizeBradley](#binarizeBradley-java.io.InputStream-java.io.OutputStream-double-) | Realiza la binarización Bradley para el flujo de entrada. |
| [getCropRectangle](#getCropRectangle--) | Obtiene el rectángulo que define el área que se convertirá en una imagen. El valor predeterminado es null, en cuyo caso toda la imagen se convierte en una página. |
| [getFormPresentationMode](#getFormPresentationMode--) | Obtiene el modo de presentación del formulario. |
| [getHeight](#getHeight--) | Obtiene la altura de salida de la imagen. |
| [getRenderingOptions](#getRenderingOptions--) | Obtiene las opciones de renderizado. |
| [getResolution](#getResolution--) | Obtiene la resolución de la imagen. |
| [getSettings](#getSettings--) | Obtiene la configuración para mapear PDF a imagen TIFF. |
| [getWidth](#getWidth--) | Obtiene el ancho de salida de la imagen. |
| [process](#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-) | Convierte ciertas páginas del documento a TIFF y las guarda en el flujo de salida. |
| [processInternal](#processInternal-com.aspose.pdf.IDocument-int-int-com.aspose.ms.System.IO.Stream-) | Convierte ciertas páginas del documento a TIFF y las guarda en el flujo de salida. |
| [processInternal](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | Realiza alguna operación en la página dada, p. ej. |
| [setCropRectangle](#setCropRectangle-com.aspose.pdf.Rectangle-) | Establece el rectángulo que define el área que se convertirá en una imagen. |
| [setFormPresentationMode](#setFormPresentationMode-int-) | Obtiene el modo de presentación del formulario. |
| [setRenderingOptions](#setRenderingOptions-com.aspose.pdf.RenderingOptions-) | Establece las opciones de renderizado. |

### TiffDevice {#TiffDevice--}
```
public TiffDevice()
```

Inicializa una nueva instancia de la clase {@code TiffDevice} con la configuración predeterminada.

### TiffDevice {#TiffDevice-int-int-}
```
public TiffDevice(int width, int height)
```

Inicializa una nueva instancia de la clase {@code TiffDevice}.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ancho |  | Ancho de salida de la imagen. |
| altura |  | Altura de salida de la imagen. |

### TiffDevice {#TiffDevice-int-int-com.aspose.pdf.devices.Resolution-}
Inicializa una nueva instancia de la clase {@code TiffDevice} con la configuración predeterminada.

### TiffDevice {#TiffDevice-int-int-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-}
Inicializa una nueva instancia de la clase {@code TiffDevice} con la configuración predeterminada.

### TiffDevice {#TiffDevice-int-int-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
Inicializa una nueva instancia de la clase {@code TiffDevice} con la configuración predeterminada.

### TiffDevice {#TiffDevice-int-int-com.aspose.pdf.devices.TiffSettings-}
Inicializa una nueva instancia de la clase {@code TiffDevice} con la configuración predeterminada.

### TiffDevice {#TiffDevice-int-int-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
Inicializa una nueva instancia de la clase {@code TiffDevice} con la configuración predeterminada.

### TiffDevice {#TiffDevice-com.aspose.pdf.PageSize-}
Inicializa una nueva instancia de la clase {@code TiffDevice} con la configuración predeterminada.

### TiffDevice {#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-}
Inicializa una nueva instancia de la clase {@code TiffDevice} con la configuración predeterminada.

### TiffDevice {#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-}
Inicializa una nueva instancia de la clase {@code TiffDevice} con la configuración predeterminada.

### TiffDevice {#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
Inicializa una nueva instancia de la clase {@code TiffDevice} con la configuración predeterminada.

### TiffDevice {#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-}
Inicializa una nueva instancia de la clase {@code TiffDevice} con la configuración predeterminada.

### TiffDevice {#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
Inicializa una nueva instancia de la clase {@code TiffDevice} con la configuración predeterminada.

### TiffDevice {#TiffDevice-com.aspose.pdf.devices.Resolution-}
Inicializa una nueva instancia de la clase {@code TiffDevice} con la configuración predeterminada.

### TiffDevice {#TiffDevice-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-}
Inicializa una nueva instancia de la clase {@code TiffDevice} con la configuración predeterminada.

### TiffDevice {#TiffDevice-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
Inicializa una nueva instancia de la clase {@code TiffDevice} con la configuración predeterminada.

### TiffDevice {#TiffDevice-com.aspose.pdf.devices.TiffSettings-}
Inicializa una nueva instancia de la clase {@code TiffDevice} con la configuración predeterminada.

### TiffDevice {#TiffDevice-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
Inicializa una nueva instancia de la clase {@code TiffDevice} con la configuración predeterminada.

### binarizeBradley {#binarizeBradley-java.io.InputStream-java.io.OutputStream-double-}
Realiza la binarización Bradley para el flujo de entrada.

### getCropRectangle {#getCropRectangle--}
```
public Rectangle getCropRectangle()
```

Obtiene el rectángulo que define el área que se convertirá en una imagen. El valor predeterminado es null, en cuyo caso toda la imagen se convierte en una página.

**Returns:**
objeto Rectangle

### getFormPresentationMode {#getFormPresentationMode--}
```
public int getFormPresentationMode()
```

Obtiene el modo de presentación del formulario.

**Returns:**
Valor de FormPresentationMode @see FormPresentationMode

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
opciones de renderizado.

### getResolution {#getResolution--}
```
public Resolution getResolution()
```

Obtiene la resolución de la imagen.

**Returns:**
Elemento Resolution

### getSettings {#getSettings--}
```
public TiffSettings getSettings()
```

Obtiene la configuración para mapear PDF a imagen TIFF.

**Returns:**
Elemento TiffSettings

### getWidth {#getWidth--}
```
public int getWidth()
```

Obtiene el ancho de salida de la imagen.

**Returns:**
valor int

### process {#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-}
Convierte ciertas páginas del documento a TIFF y las guarda en el flujo de salida.

### processInternal {#processInternal-com.aspose.pdf.IDocument-int-int-com.aspose.ms.System.IO.Stream-}
Convierte ciertas páginas del documento a TIFF y las guarda en el flujo de salida.

### processInternal {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
Realiza alguna operación en la página dada, p. ej.

### setCropRectangle {#setCropRectangle-com.aspose.pdf.Rectangle-}
Establece el rectángulo que define el área que se convertirá en una imagen.

### setFormPresentationMode {#setFormPresentationMode-int-}
```
public void setFormPresentationMode(int value)
```

Obtiene el modo de presentación del formulario.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int @see FormPresentationMode |

### setRenderingOptions {#setRenderingOptions-com.aspose.pdf.RenderingOptions-}
Establece las opciones de renderizado.
