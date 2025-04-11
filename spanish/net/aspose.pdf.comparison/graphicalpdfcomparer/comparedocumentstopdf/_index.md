---
title: GraphicalPdfComparer.CompareDocumentsToPdf
second_title: Aspose.PDF for .NET API Reference
description: Método GraphicalPdfComparer. Compara documentos gráficamente. El resultado de la comparación se coloca en un documento PDF
type: docs
weight: 60
url: /es/net/aspose.pdf.comparison/graphicalpdfcomparer/comparedocumentstopdf/
---
## Método GraphicalPdfComparer.CompareDocumentsToPdf

Compara documentos gráficamente. El resultado de la comparación se coloca en un documento PDF.

```csharp
public void CompareDocumentsToPdf(Document document1, Document document2, string resultPdfPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| document1 | Document | El primer documento a comparar. |
| document2 | Document | El segundo documento a comparar. |
| resultPdfPath | String | La ruta del archivo pdf de destino. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | Si las páginas que se comparan son de diferentes tamaños. Si resultPdfPath es nulo o una cadena vacía. |

### Véase también

* clase [Document](../../../aspose.pdf/document/)
* clase [GraphicalPdfComparer](../)
* espacio de nombres [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* ensamblaje [Aspose.PDF](../../../)