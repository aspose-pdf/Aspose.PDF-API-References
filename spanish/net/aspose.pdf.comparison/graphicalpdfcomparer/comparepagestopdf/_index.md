---
title: GraphicalPdfComparer.ComparePagesToPdf
second_title: Aspose.PDF for .NET API Reference
description: Método GraphicalPdfComparer. Compara páginas gráficamente. El resultado de la comparación se coloca en un documento PDF.
type: docs
weight: 80
url: /es/net/aspose.pdf.comparison/graphicalpdfcomparer/comparepagestopdf/
---
## ComparePagesToPdf(Page, Page, string) {#comparepagestopdf_1}

Compara páginas gráficamente. El resultado de la comparación se coloca en un documento PDF.

```csharp
public void ComparePagesToPdf(Page page1, Page page2, string resultPdfPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| page1 | Page | La primera página. |
| page2 | Page | La segunda página. |
| resultPdfPath | String | La ruta al archivo pdf de destino. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | Si las páginas que se comparan son de diferentes tamaños. Si resultPdfPath es nulo o una cadena vacía. |

### Véase También

* clase [Page](../../../aspose.pdf/page/)
* clase [GraphicalPdfComparer](../)
* espacio de nombres [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* ensamblado [Aspose.PDF](../../../)

---

## ComparePagesToPdf(Page, Page, Document) {#comparepagestopdf}

Compara páginas gráficamente. El resultado de la comparación se coloca en un documento PDF.

```csharp
public void ComparePagesToPdf(Page page1, Page page2, Document pdfDocument)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| page1 | Page | La primera página. |
| page2 | Page | La segunda página. |
| pdfDocument | Document | La instancia del documento pdf. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | Si las páginas que se comparan son de diferentes tamaños. |

### Véase También

* clase [Page](../../../aspose.pdf/page/)
* clase [Document](../../../aspose.pdf/document/)
* clase [GraphicalPdfComparer](../)
* espacio de nombres [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* ensamblado [Aspose.PDF](../../../)