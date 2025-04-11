---
title: Class HtmlFragment
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.HtmlFragment. Representa fragmento html
type: docs
weight: 5520
url: /pt/net/aspose.pdf/htmlfragment/
---
## Classe HtmlFragment

Representa fragmento html.

```csharp
public sealed class HtmlFragment : FormattedFragment
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [HtmlFragment](htmlfragment/)(string) | Inicializa uma nova instância da classe HtmlFragment. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | Obtém ou define um alinhamento horizontal do parágrafo |
| [HtmlLoadOptions](../../aspose.pdf/htmlfragment/htmlloadoptions/) { get; set; } | Obtém ou define HtmlLoadOptions que serão usadas para carregar (e renderizar) HTML nesta instância da classe. Por favor, use quando for necessário usar configurações específicas para a importação de HTML para esta ou aquela instância (por exemplo, quando esta ou aquela instância deve usar um BasePath específico para HTML importado ou deve usar um carregador específico de recursos externos). Se o parâmetro for padrão (null), então as opções padrão de carregamento de HTML serão usadas. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Obtém ou define o hyperlink do fragmento (para gerador de pdf). |
| [IsBreakWords](../../aspose.pdf/htmlfragment/isbreakwords/) { get; set; } | Obtém ou define a quebra de palavras |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Obtém ou define um valor bool que indica se este parágrafo estará na próxima coluna. O padrão é falso. (para geração de pdf) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Obtém ou define se um parágrafo é inline. O padrão é falso. (para geração de pdf) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Obtém ou define um valor bool que força este parágrafo a ser gerado em uma nova página. O padrão é falso. (para geração de pdf) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Obtém ou define um valor bool que indica se o parágrafo atual permanece na mesma página junto com o próximo parágrafo. O padrão é falso. (para geração de pdf) |
| [IsParagraphHasMargin](../../aspose.pdf/htmlfragment/isparagraphhasmargin/) { get; set; } | Obtém ou define se o parágrafo tem margem padrão, caso contrário, a margem é 0 |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Obtém ou define uma margem externa para o parágrafo (para geração de pdf) |
| [Rectangle](../../aspose.pdf/htmlfragment/rectangle/) { get; } | Obtém o retângulo do HtmlFragment |
| [TextState](../../aspose.pdf/htmlfragment/textstate/) { get; set; } | Obtém ou define a fonte |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Obtém ou define um alinhamento vertical do parágrafo |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Obtém ou define um valor int que indica a ordem Z do gráfico. Um gráfico com ZIndex maior será colocado sobre o gráfico com ZIndex menor. ZIndex pode ser negativo. Gráficos com ZIndex negativo serão colocados atrás do texto na página. |

## Métodos

| Nome | Descrição |
| --- | --- |
| override [Clone](../../aspose.pdf/htmlfragment/clone/)() | Clona o fragmento html. |

### Veja Também

* classe [FormattedFragment](../formattedfragment/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)