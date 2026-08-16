---
title: "TiffSettings"
linktitle: "TiffSettings"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Esta clase representa la configuración para importar pdf a Tiff."
type: docs
weight: 220
url: /es/java/com.aspose.pdf.devices/tiffsettings/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.TiffSettings

```
public final class TiffSettings extends Object
```

Esta clase representa la configuración para importar pdf a Tiff.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [TiffSettings](#TiffSettings--) | Inicializa una nueva instancia de la clase {@code TiffSettings}. |
| [TiffSettings](#TiffSettings-boolean-) | Inicializa una nueva instancia de la clase {@code TiffSettings}. |
| [TiffSettings](#TiffSettings-com.aspose.pdf.devices.ColorDepth-) | Inicializa una nueva instancia de la clase {@code TiffSettings}. |
| [TiffSettings](#TiffSettings-com.aspose.pdf.devices.CompressionType-) | Inicializa una nueva instancia de la clase {@code TiffSettings}. |
| [TiffSettings](#TiffSettings-com.aspose.pdf.devices.CompressionType-com.aspose.pdf.devices.ColorDepth-com.aspose.pdf.devices.Margins-) | Inicializa una nueva instancia de la clase {@code TiffSettings}. |
| [TiffSettings](#TiffSettings-com.aspose.pdf.devices.CompressionType-com.aspose.pdf.devices.ColorDepth-com.aspose.pdf.devices.Margins-boolean-) | Inicializa una nueva instancia de la clase {@code TiffSettings}. |
| [TiffSettings](#TiffSettings-com.aspose.pdf.devices.CompressionType-com.aspose.pdf.devices.ColorDepth-com.aspose.pdf.devices.Margins-boolean-com.aspose.pdf.devices.ShapeType-) | Inicializa una nueva instancia de la clase {@code TiffSettings}. |
| [TiffSettings](#TiffSettings-com.aspose.pdf.devices.Margins-) | Inicializa una nueva instancia de la clase {@code TiffSettings}. |

## Métodos

| Método | Descripción |
| --- | --- |
| [getBrightness](#getBrightness--) | Obtiene el límite de valor de la transformación de colores en blanco y negro. Este parámetro puede aplicarse con EncoderValue.CompressionCCITT4, EncoderValue.CompressionCCITT3, EncoderValue.CompressionRle o ColorDepth.Format1bpp == 1 |
| [getCompression](#getCompression--) | <p> Obtiene el tipo de compresión. </p> Value: El tipo de compresión. <hr> <p> El valor predeterminado es CompressionType.LZW </p> |
| [getCoordinateType](#getCoordinateType--) | Obtiene el tipo de coordenada de la página (cajas Media/Crop). El valor CropBox se usa por defecto. |
| [getDepth](#getDepth--) | <p> Obtiene la profundidad de color. </p> Value: La profundidad de color. <hr> <p> El valor predeterminado es ColorDepth.Default </p> |
| [getIndexedConversionType](#getIndexedConversionType--) | Obtiene el IndexedConversionType. El valor predeterminado es Simple. |
| [getMargins](#getMargins--) | Obtiene los márgenes. |
| [getShape](#getShape--) | <p> Obtiene el tipo de la forma. </p> Value: El tipo de la forma. <hr> <p> El valor predeterminado es ShapeType.None </p> |
| [getSkipBlankPages](#getSkipBlankPages--) | <p> Obtiene un valor que indica si se deben omitir páginas en blanco. </p> Value: {@code true} si es necesario omitir páginas en blanco; de lo contrario, {@code false}. <hr> <p> El valor predeterminado es false </p> |
| [isUseAlternativeImageEngine](#isUseAlternativeImageEngine--) | Obtiene una bandera que determina si se utiliza o no el motor de imágenes alternativo. El valor true se usa de forma predeterminada para Linux OS. Para Windows OS el valor predeterminado es false. |
| [setBrightness](#setBrightness-float-) | Establece el límite de valor de la transformación de colores en blanco y negro. Este parámetro puede aplicarse con EncoderValue.CompressionCCITT4, EncoderValue.CompressionCCITT3, EncoderValue.CompressionRle o ColorDepth.Format1bpp == 1 |
| [setCompression](#setCompression-com.aspose.pdf.devices.CompressionType-) | <p> Establece el tipo de compresión. </p> Value: El tipo de compresión. <hr> <p> El valor predeterminado es CompressionType.LZW </p> |
| [setCoordinateType](#setCoordinateType-com.aspose.pdf.PageCoordinateType-) | Establece el tipo de coordenada de la página (cajas Media/Crop). El valor CropBox se usa por defecto. |
| [setDepth](#setDepth-com.aspose.pdf.devices.ColorDepth-) | <p> Obtiene la profundidad de color. </p> Value: La profundidad de color. <hr> <p> El valor predeterminado es ColorDepth.Default </p> |
| [setIndexedConversionType](#setIndexedConversionType-int-) | Establece el IndexedConversionType. |
| [setShape](#setShape-com.aspose.pdf.devices.ShapeType-) | <p> Establece el tipo de la forma. </p> Valor: El tipo de la forma. <hr> <p> El valor predeterminado es ShapeType.None </p> |
| [setSkipBlankPages](#setSkipBlankPages-boolean-) | <p> Establece un valor que indica si se deben omitir páginas en blanco. </p> Valor: {@code true} si es necesario omitir páginas en blanco; de lo contrario, {@code false}. <hr> <p> El valor predeterminado es false </p> |
| [setUseAlternativeImageEngine](#setUseAlternativeImageEngine-boolean-) | Establece una bandera que determina si se utiliza o no el motor de imágenes alternativo. |

### TiffSettings {#TiffSettings--}
```
public TiffSettings()
```

Inicializa una nueva instancia de la clase {@code TiffSettings}.

### TiffSettings {#TiffSettings-boolean-}
```
public TiffSettings(boolean skipBlankPages)
```

Inicializa una nueva instancia de la clase {@code TiffSettings}.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| skipBlankPages |  | si se establece en {@code true} [omitir páginas en blanco]. |

### TiffSettings {#TiffSettings-com.aspose.pdf.devices.ColorDepth-}
Inicializa una nueva instancia de la clase {@code TiffSettings}.

### TiffSettings {#TiffSettings-com.aspose.pdf.devices.CompressionType-}
Inicializa una nueva instancia de la clase {@code TiffSettings}.

### TiffSettings {#TiffSettings-com.aspose.pdf.devices.CompressionType-com.aspose.pdf.devices.ColorDepth-com.aspose.pdf.devices.Margins-}
Inicializa una nueva instancia de la clase {@code TiffSettings}.

### TiffSettings {#TiffSettings-com.aspose.pdf.devices.CompressionType-com.aspose.pdf.devices.ColorDepth-com.aspose.pdf.devices.Margins-boolean-}
Inicializa una nueva instancia de la clase {@code TiffSettings}.

### TiffSettings {#TiffSettings-com.aspose.pdf.devices.CompressionType-com.aspose.pdf.devices.ColorDepth-com.aspose.pdf.devices.Margins-boolean-com.aspose.pdf.devices.ShapeType-}
Inicializa una nueva instancia de la clase {@code TiffSettings}.

### TiffSettings {#TiffSettings-com.aspose.pdf.devices.Margins-}
Inicializa una nueva instancia de la clase {@code TiffSettings}.

### getBrightness {#getBrightness--}
```
public float getBrightness()
```

Obtiene el límite de valor de la transformación de colores en blanco y negro. Este parámetro puede aplicarse con EncoderValue.CompressionCCITT4, EncoderValue.CompressionCCITT3, EncoderValue.CompressionRle o ColorDepth.Format1bpp == 1

**Returns:**
El valor flotante de brillo debe estar en el rango de 0 a 1. Por defecto, el valor es igual a 0.33f

### getCompression {#getCompression--}
```
public CompressionType getCompression()
```

<p> Obtiene el tipo de compresión. </p> Value: El tipo de compresión. <hr> <p> El valor predeterminado es CompressionType.LZW </p>

**Returns:**
Elemento CompressionType @see CompressionType

### getCoordinateType {#getCoordinateType--}
```
public PageCoordinateType getCoordinateType()
```

Obtiene el tipo de coordenada de la página (cajas Media/Crop). El valor CropBox se usa por defecto.

**Returns:**
Valor PageCoordinateType @see PageCoordinateType

### getDepth {#getDepth--}
```
public ColorDepth getDepth()
```

<p> Obtiene la profundidad de color. </p> Value: La profundidad de color. <hr> <p> El valor predeterminado es ColorDepth.Default </p>

**Returns:**
Elemento ColorDepth @see ColorDepth

### getIndexedConversionType {#getIndexedConversionType--}
```
public int getIndexedConversionType()
```

Obtiene el IndexedConversionType. El valor predeterminado es Simple.

**Returns:**
Elemento IndexedConversionType @see IndexedConversionType

### getMargins {#getMargins--}
```
public Margins getMargins()
```

Obtiene los márgenes.

**Returns:**
Objeto Margins

### getShape {#getShape--}
```
public ShapeType getShape()
```

<p> Obtiene el tipo de la forma. </p> Value: El tipo de la forma. <hr> <p> El valor predeterminado es ShapeType.None </p>

**Returns:**
Elemento ShapeType @see ShapeType

### getSkipBlankPages {#getSkipBlankPages--}
```
public boolean getSkipBlankPages()
```

<p> Obtiene un valor que indica si se deben omitir páginas en blanco. </p> Value: {@code true} si es necesario omitir páginas en blanco; de lo contrario, {@code false}. <hr> <p> El valor predeterminado es false </p>

**Returns:**
valor booleano

### isUseAlternativeImageEngine {#isUseAlternativeImageEngine--}
```
public boolean isUseAlternativeImageEngine()
```

Obtiene una bandera que determina si se utiliza o no el motor de imágenes alternativo. El valor true se usa de forma predeterminada para Linux OS. Para Windows OS el valor predeterminado es false.

**Returns:**
valor booleano

### setBrightness {#setBrightness-float-}
```
public void setBrightness(float value)
```

Establece el límite de valor de la transformación de colores en blanco y negro. Este parámetro puede aplicarse con EncoderValue.CompressionCCITT4, EncoderValue.CompressionCCITT3, EncoderValue.CompressionRle o ColorDepth.Format1bpp == 1

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | : El valor de brillo debe estar en el rango de 0 a 1. Por defecto, el valor es igual a 0.33f |

### setCompression {#setCompression-com.aspose.pdf.devices.CompressionType-}
<p> Establece el tipo de compresión. </p> Value: El tipo de compresión. <hr> <p> El valor predeterminado es CompressionType.LZW </p>

### setCoordinateType {#setCoordinateType-com.aspose.pdf.PageCoordinateType-}
Establece el tipo de coordenada de la página (cajas Media/Crop). El valor CropBox se usa por defecto.

### setDepth {#setDepth-com.aspose.pdf.devices.ColorDepth-}
<p> Obtiene la profundidad de color. </p> Value: La profundidad de color. <hr> <p> El valor predeterminado es ColorDepth.Default </p>

### setIndexedConversionType {#setIndexedConversionType-int-}
```
public void setIndexedConversionType(int value)
```

Establece el IndexedConversionType.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | Elemento IndexedConversionType @see IndexedConversionType |

### setShape {#setShape-com.aspose.pdf.devices.ShapeType-}
<p> Establece el tipo de la forma. </p> Valor: El tipo de la forma. <hr> <p> El valor predeterminado es ShapeType.None </p>

### setSkipBlankPages {#setSkipBlankPages-boolean-}
```
public void setSkipBlankPages(boolean value)
```

<p> Establece un valor que indica si se deben omitir páginas en blanco. </p> Valor: {@code true} si es necesario omitir páginas en blanco; de lo contrario, {@code false}. <hr> <p> El valor predeterminado es false </p>

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setUseAlternativeImageEngine {#setUseAlternativeImageEngine-boolean-}
```
public void setUseAlternativeImageEngine(boolean useAlternativeImageEngine)
```

Establece una bandera que determina si se utiliza o no el motor de imágenes alternativo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| useAlternativeImageEngine |  | valor booleano |
