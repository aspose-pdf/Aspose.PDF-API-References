---
title: Class FormattedFragment
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.FormattedFragment. Representa um fragmento formatado abstrato
type: docs
weight: 4940
url: /pt/net/aspose.pdf/formattedfragment/
---
## Classe FormattedFragment

Representa um fragmento formatado abstrato.

```csharp
public abstract class FormattedFragment : BaseParagraph
```

## Propriedades

| Nome | Descrição |
| --- | --- |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | Obtém ou define um alinhamento horizontal do parágrafo |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Obtém ou define o hyperlink do fragmento (para gerador de pdf). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Obtém ou define um valor bool que indica se este parágrafo estará na próxima coluna. O padrão é falso. (para geração de pdf) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Obtém ou define se o parágrafo é inline. O padrão é falso. (para geração de pdf) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Obtém ou define um valor bool que força este parágrafo a ser gerado em uma nova página. O padrão é falso. (para geração de pdf) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Obtém ou define um valor bool que indica se o parágrafo atual permanece na mesma página junto com o próximo parágrafo. O padrão é falso. (para geração de pdf) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Obtém ou define uma margem externa para o parágrafo (para geração de pdf) |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Obtém ou define um alinhamento vertical do parágrafo |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Obtém ou define um valor int que indica a ordem Z do gráfico. Um gráfico com um ZIndex maior será colocado sobre o gráfico com um ZIndex menor. O ZIndex pode ser negativo. Gráficos com ZIndex negativo serão colocados atrás do texto na página. |

## Métodos

| Nome | Descrição |
| --- | --- |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | Clona esta instância. Método virtual. Sempre retorna nulo. |

### Veja Também

* classe [BaseParagraph](../baseparagraph/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)