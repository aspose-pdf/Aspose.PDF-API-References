---
title: Class MarkupParagraph
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Text.MarkupParagraph. Representa um parágrafo
type: docs
weight: 10630
url: /pt/net/aspose.pdf.text/markupparagraph/
---
## Classe MarkupParagraph

Representa um parágrafo.

```csharp
public sealed class MarkupParagraph
```

## Propriedades

| Nome | Descrição |
| --- | --- |
| [ContinuationPageNumbers](../../aspose.pdf.text/markupparagraph/continuationpagenumbers/) { get; } | Lista de números de página nos quais o parágrafo é continuado. Ele corresponderá à página onde o parágrafo começou se estiver continuando na próxima coluna na mesma página. |
| [Fragments](../../aspose.pdf.text/markupparagraph/fragments/) { get; } | Coleção de objetos [`TextFragment`](../textfragment/) não vazios do parágrafo. |
| [Lines](../../aspose.pdf.text/markupparagraph/lines/) { get; } | Linhas do parágrafo. Cada linha é representada por uma lista de fragmentos de texto. |
| [Points](../../aspose.pdf.text/markupparagraph/points/) { get; } | Pontos do polígono que descreve o parágrafo. O ponto inicial é o canto inferior esquerdo do parágrafo. E os próximos pontos estão em sequência anti-horária. |
| [SecondaryPoints](../../aspose.pdf.text/markupparagraph/secondarypoints/) { get; } | Pontos do polígono secundário que descreve a continuação do parágrafo. Não será nulo se o parágrafo for continuado na próxima coluna ou página. O ponto inicial é o canto inferior esquerdo do parágrafo. E os próximos pontos estão em sequência anti-horária. |
| [Text](../../aspose.pdf.text/markupparagraph/text/) { get; set; } | Obtém ou define o texto do parágrafo. |

### Veja Também

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)