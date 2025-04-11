---
title: Class GraphicalPdfComparer
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Comparison.GraphicalPdfComparer. Representa uma classe para comparar graficamente documentos PDF. Deve ser usada para buscar pequenas mudanças, principalmente de natureza gráfica. Para comparar mudanças no conteúdo de texto, use outras classes de comparação de PDF.
type: docs
weight: 3190
url: /pt/net/aspose.pdf.comparison/graphicalpdfcomparer/
---
## Classe GraphicalPdfComparer

Representa uma classe para comparar graficamente documentos PDF. Deve ser usada para buscar pequenas mudanças, principalmente de natureza gráfica. Para comparar mudanças no conteúdo de texto, use outras classes de comparação de PDF.

```csharp
public class GraphicalPdfComparer
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [GraphicalPdfComparer](graphicalpdfcomparer/)() | O construtor padrão. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [Color](../../aspose.pdf.comparison/graphicalpdfcomparer/color/) { get; set; } | Obtém e define a cor da bandeira de mudança. A cor padrão é vermelha. |
| [Resolution](../../aspose.pdf.comparison/graphicalpdfcomparer/resolution/) { get; set; } | Obtém e define a resolução das imagens resultantes. O valor padrão é 150dpi. |
| [Threshold](../../aspose.pdf.comparison/graphicalpdfcomparer/threshold/) { get; set; } | Obtém e define o valor do limite em porcentagem. Este valor permite ignorar pequenas mudanças se não forem significativas para você. O valor padrão é 0%. |

## Métodos

| Nome | Descrição |
| --- | --- |
| [CompareDocumentsToImages](../../aspose.pdf.comparison/graphicalpdfcomparer/comparedocumentstoimages/)(Document, Document, string, string, ImageFormat) | Compara documentos graficamente. O resultado da comparação é colocado em imagens. |
| [CompareDocumentsToPdf](../../aspose.pdf.comparison/graphicalpdfcomparer/comparedocumentstopdf/)(Document, Document, string) | Compara documentos graficamente. O resultado da comparação é colocado em um documento PDF. |
| [ComparePagesToImage](../../aspose.pdf.comparison/graphicalpdfcomparer/comparepagestoimage/)(Page, Page, string) | Compara páginas graficamente. O resultado da comparação é colocado em uma imagem. |
| [ComparePagesToPdf](../../aspose.pdf.comparison/graphicalpdfcomparer/comparepagestopdf/#comparepagestopdf)(Page, Page, Document) | Compara páginas graficamente. O resultado da comparação é colocado em um documento PDF. |
| [ComparePagesToPdf](../../aspose.pdf.comparison/graphicalpdfcomparer/comparepagestopdf/#comparepagestopdf_1)(Page, Page, string) | Compara páginas graficamente. O resultado da comparação é colocado em um documento PDF. |
| [GetDifference](../../aspose.pdf.comparison/graphicalpdfcomparer/getdifference/)(Page, Page) | Obtém diferenças entre as imagens das páginas. O resultado contém uma imagem da primeira página comparada e um array de diferenças. |

### Veja Também

* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)