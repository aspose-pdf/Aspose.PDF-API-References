---
title: "Document.OptimizationOptions"
linktitle: "Document.OptimizationOptions"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Clase que describe el algoritmo de optimización de documentos. La instancia de esta clase puede usarse como parámetro del método OptimizeResources(). @deprecated Esta clase está obsoleta. Por favor."
type: docs
weight: 1110
url: /es/java/com.aspose.pdf/document.optimizationoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.optimization.OptimizationOptions com.aspose.pdf.Document.OptimizationOptions, com.aspose.pdf.optimization.OptimizationOptions, com.aspose.pdf.Document.OptimizationOptions

```
@Deprecated public static class Document.OptimizationOptions extends OptimizationOptions
```

Clase que describe el algoritmo de optimización de documentos. Una instancia de esta clase puede usarse como parámetro del método OptimizeResources(). @deprecated Esta clase está obsoleta. Por favor use com.aspose.pdf.optimization.OptimizationOptions en su lugar.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [OptimizationOptions](#OptimizationOptions--) | Obsoleto. |

## Métodos

| Método | Descripción |
| --- | --- |
| [all](#all--) | Crea una estrategia de optimización con todas las opciones activadas. |
| [getMaximumImageDimension](#getMaximumImageDimension--) | Especifica la dimensión máxima de la imagen. Si el ancho o la altura de la imagen existente es mayor que este valor, el tamaño de la imagen se reducirá proporcionalmente. |
| [getResolution](#getResolution--) | Especifica el nuevo DPI de la imagen cuando se usa la bandera CompressIamges. |
| [setMaximumImageDimension](#setMaximumImageDimension-int-) | Especifica la dimensión máxima de la imagen. Si el ancho o la altura de la imagen existente es mayor que este valor, el tamaño de la imagen se reducirá proporcionalmente. |
| [setResolution](#setResolution-int-) | Especifica el nuevo DPI de la imagen cuando se usa la bandera CompressIamges. |

### OptimizationOptions {#OptimizationOptions--}
```
public OptimizationOptions()
```

Obsoleto.

### all {#all--}
```
public static Document.OptimizationOptions all()
```

Crea una estrategia de optimización con todas las opciones activadas.

**Returns:**
Objeto OptimizationOptions.

### getMaximumImageDimension {#getMaximumImageDimension--}
```
public int getMaximumImageDimension()
```

Especifica la dimensión máxima de la imagen. Si el ancho o la altura de la imagen existente es mayor que este valor, el tamaño de la imagen se reducirá proporcionalmente.

**Returns:**
dimensión máxima de la imagen

### getResolution {#getResolution--}
```
public int getResolution()
```

Especifica el nuevo DPI de la imagen cuando se usa la bandera CompressIamges.

**Returns:**
resolución de la imagen

### setMaximumImageDimension {#setMaximumImageDimension-int-}
```
public void setMaximumImageDimension(int dimension)
```

Especifica la dimensión máxima de la imagen. Si el ancho o la altura de la imagen existente es mayor que este valor, el tamaño de la imagen se reducirá proporcionalmente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dimensión |  | dimensión máxima de la imagen |

### setResolution {#setResolution-int-}
```
public void setResolution(int dpi)
```

Especifica el nuevo DPI de la imagen cuando se usa la bandera CompressIamges.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dpi |  | resolución de la imagen |
