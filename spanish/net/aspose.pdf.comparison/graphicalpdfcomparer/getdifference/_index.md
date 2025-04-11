---
title: GraphicalPdfComparer.GetDifference
second_title: Aspose.PDF for .NET API Reference
description: Método GraphicalPdfComparer. Obtiene diferencias entre imágenes de páginas. El resultado contiene una imagen de la primera página comparada y un array de diferencias.
type: docs
weight: 90
url: /es/net/aspose.pdf.comparison/graphicalpdfcomparer/getdifference/
---
## Método GraphicalPdfComparer.GetDifference

Obtiene diferencias entre imágenes de páginas. El resultado contiene una imagen de la primera página comparada y un array de diferencias.

```csharp
public ImagesDifference GetDifference(Page page1, Page page2)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| page1 | Page | La primera página. |
| page2 | Page | La segunda página. |

### Valor de Retorno

La instancia de [`ImagesDifference`](../../imagesdifference/).

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | Si las páginas que se comparan son de diferentes tamaños. |

### Véase También

* clase [ImagesDifference](../../imagesdifference/)
* clase [Page](../../../aspose.pdf/page/)
* clase [GraphicalPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)