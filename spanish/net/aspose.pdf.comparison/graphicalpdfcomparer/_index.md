---
title: Class GraphicalPdfComparer
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Comparison.GraphicalPdfComparer. Representa una clase para comparar gráficamente documentos PDF. Debe usarse para buscar pequeños cambios, principalmente de naturaleza gráfica. Para comparar cambios en el contenido de texto, use otras clases de comparación de PDF.
type: docs
weight: 3190
url: /es/net/aspose.pdf.comparison/graphicalpdfcomparer/
---
## Clase GraphicalPdfComparer

Representa una clase para comparar gráficamente documentos PDF. Debe usarse para buscar pequeños cambios, principalmente de naturaleza gráfica. Para comparar cambios en el contenido de texto, use otras clases de comparación de PDF.

```csharp
public class GraphicalPdfComparer
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [GraphicalPdfComparer](graphicalpdfcomparer/)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Color](../../aspose.pdf.comparison/graphicalpdfcomparer/color/) { get; set; } | Obtiene y establece el color de la bandera de cambio. El color predeterminado es rojo. |
| [Resolution](../../aspose.pdf.comparison/graphicalpdfcomparer/resolution/) { get; set; } | Obtiene y establece la resolución de las imágenes resultantes. El valor predeterminado es 150dpi. |
| [Threshold](../../aspose.pdf.comparison/graphicalpdfcomparer/threshold/) { get; set; } | Obtiene y establece el valor del umbral en porcentaje. Este valor permite ignorar pequeños cambios si no son significativos para usted. El valor predeterminado es 0%. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [CompareDocumentsToImages](../../aspose.pdf.comparison/graphicalpdfcomparer/comparedocumentstoimages/)(Document, Document, string, string, ImageFormat) | Compara documentos gráficamente. El resultado de la comparación se coloca en imágenes. |
| [CompareDocumentsToPdf](../../aspose.pdf.comparison/graphicalpdfcomparer/comparedocumentstopdf/)(Document, Document, string) | Compara documentos gráficamente. El resultado de la comparación se coloca en un documento PDF. |
| [ComparePagesToImage](../../aspose.pdf.comparison/graphicalpdfcomparer/comparepagestoimage/)(Page, Page, string) | Compara páginas gráficamente. El resultado de la comparación se coloca en una imagen. |
| [ComparePagesToPdf](../../aspose.pdf.comparison/graphicalpdfcomparer/comparepagestopdf/#comparepagestopdf)(Page, Page, Document) | Compara páginas gráficamente. El resultado de la comparación se coloca en un documento PDF. |
| [ComparePagesToPdf](../../aspose.pdf.comparison/graphicalpdfcomparer/comparepagestopdf/#comparepagestopdf_1)(Page, Page, string) | Compara páginas gráficamente. El resultado de la comparación se coloca en un documento PDF. |
| [GetDifference](../../aspose.pdf.comparison/graphicalpdfcomparer/getdifference/)(Page, Page) | Obtiene diferencias entre imágenes de páginas. El resultado contiene una imagen de la primera página comparada y un arreglo de diferencias. |

### Véase también

* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)