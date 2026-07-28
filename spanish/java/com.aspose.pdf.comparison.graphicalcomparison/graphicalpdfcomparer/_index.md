---
title: "GraphicalPdfComparer"
linktitle: "GraphicalPdfComparer"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa una clase para comparar gráficamente documentos PDF. Debe usarse para buscar pequeños cambios, principalmente de naturaleza gráfica. Para comparar cambios en el contenido de texto, use otra."
type: docs
weight: 10
url: /es/java/com.aspose.pdf.comparison.graphicalcomparison/graphicalpdfcomparer/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.comparison.graphicalcomparison.GraphicalPdfComparer

```
public class GraphicalPdfComparer extends Object
```

Representa una clase para comparar gráficamente documentos PDF. Debe usarse para buscar cambios pequeños, principalmente de naturaleza gráfica. Para comparar cambios en el contenido de texto, utilice otras clases de comparación de PDF.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [GraphicalPdfComparer](#GraphicalPdfComparer--) | Crea una instancia de la clase {@link GraphicalPdfComparer}. |

## Métodos

| Método | Descripción |
| --- | --- |
| [compareDocumentsToImages](#compareDocumentsToImages-com.aspose.pdf.Document-com.aspose.pdf.Document-java.lang.String-java.lang.String-com.aspose.ms.System.Drawing.Imaging.ImageFormat-) | Compara documentos gráficamente. |
| [compareDocumentsToPdf](#compareDocumentsToPdf-com.aspose.pdf.Document-com.aspose.pdf.Document-java.lang.String-) | Compara documentos gráficamente. El resultado de la comparación se coloca en un documento PDF. |
| [comparePagesToImage](#comparePagesToImage-com.aspose.pdf.Page-com.aspose.pdf.Page-java.lang.String-) | Compara páginas gráficamente. El resultado de la comparación se coloca en una imagen. |
| [comparePagesToPdf](#comparePagesToPdf-com.aspose.pdf.Page-com.aspose.pdf.Page-com.aspose.pdf.Document-) | Compara páginas gráficamente. El resultado de la comparación se coloca en un documento PDF. |
| [comparePagesToPdf](#comparePagesToPdf-com.aspose.pdf.Page-com.aspose.pdf.Page-java.lang.String-) | Compara páginas gráficamente. El resultado de la comparación se coloca en un documento PDF. |
| [getColor](#getColor--) | Obtiene y establece el color de la bandera de cambio. El color predeterminado es rojo. |
| [getDifference](#getDifference-com.aspose.pdf.Page-com.aspose.pdf.Page-) | Obtiene las diferencias entre imágenes de páginas. El resultado contiene una imagen de la primera página comparada y una matriz de diferencias. |
| [getResolution](#getResolution--) | Obtiene y establece la resolución de las imágenes resultantes. El valor predeterminado es 150dpi. |
| [getThreshold](#getThreshold--) | Obtiene y establece el valor del umbral en porcentaje. Este valor le permite ignorar pequeños cambios si no son significativos para usted. El valor predeterminado es 0%. |
| [setColor](#setColor-com.aspose.pdf.Color-) | Obtiene y establece el color de la bandera de cambio. El color predeterminado es rojo. |
| [setResolution](#setResolution-com.aspose.pdf.devices.Resolution-) | Obtiene y establece la resolución de las imágenes resultantes. El valor predeterminado es 150dpi. |
| [setThreshold](#setThreshold-double-) | Obtiene y establece el valor del umbral en porcentaje. Este valor le permite ignorar pequeños cambios si no son significativos para usted. El valor predeterminado es 0%. |

### GraphicalPdfComparer {#GraphicalPdfComparer--}
```
public GraphicalPdfComparer()
```

Crea una instancia de la clase {@link GraphicalPdfComparer}.

### compareDocumentsToImages {#compareDocumentsToImages-com.aspose.pdf.Document-com.aspose.pdf.Document-java.lang.String-java.lang.String-com.aspose.ms.System.Drawing.Imaging.ImageFormat-}
Compara documentos gráficamente.

### compareDocumentsToPdf {#compareDocumentsToPdf-com.aspose.pdf.Document-com.aspose.pdf.Document-java.lang.String-}
Compara documentos gráficamente. El resultado de la comparación se coloca en un documento PDF.

### comparePagesToImage {#comparePagesToImage-com.aspose.pdf.Page-com.aspose.pdf.Page-java.lang.String-}
Compara páginas gráficamente. El resultado de la comparación se coloca en una imagen.

### comparePagesToPdf {#comparePagesToPdf-com.aspose.pdf.Page-com.aspose.pdf.Page-com.aspose.pdf.Document-}
Compara páginas gráficamente. El resultado de la comparación se coloca en un documento PDF.

### comparePagesToPdf {#comparePagesToPdf-com.aspose.pdf.Page-com.aspose.pdf.Page-java.lang.String-}
Compara páginas gráficamente. El resultado de la comparación se coloca en un documento PDF.

### getColor {#getColor--}
```
public final Color getColor()
```

Obtiene y establece el color de la bandera de cambio. El color predeterminado es rojo.

**Returns:**
Instancia de Color

### getDifference {#getDifference-com.aspose.pdf.Page-com.aspose.pdf.Page-}
Obtiene las diferencias entre imágenes de páginas. El resultado contiene una imagen de la primera página comparada y una matriz de diferencias.

### getResolution {#getResolution--}
```
public final Resolution getResolution()
```

Obtiene y establece la resolución de las imágenes resultantes. El valor predeterminado es 150dpi.

**Returns:**
Instancia Resolution

### getThreshold {#getThreshold--}
```
public final double getThreshold()
```

Obtiene y establece el valor del umbral en porcentaje. Este valor le permite ignorar pequeños cambios si no son significativos para usted. El valor predeterminado es 0%.

**Returns:**
valor double

### setColor {#setColor-com.aspose.pdf.Color-}
Obtiene y establece el color de la bandera de cambio. El color predeterminado es rojo.

### setResolution {#setResolution-com.aspose.pdf.devices.Resolution-}
Obtiene y establece la resolución de las imágenes resultantes. El valor predeterminado es 150dpi.

### setThreshold {#setThreshold-double-}
```
public final void setThreshold(double value)
```

Obtiene y establece el valor del umbral en porcentaje. Este valor le permite ignorar pequeños cambios si no son significativos para usted. El valor predeterminado es 0%.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor double |
