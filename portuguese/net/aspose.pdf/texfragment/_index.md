---
title: Class TeXFragment
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.TeXFragment. Representa fragmento TeX
type: docs
weight: 10360
url: /pt/net/aspose.pdf/texfragment/
---
## Classe TeXFragment

Representa fragmento TeX.

```csharp
public class TeXFragment : FormattedFragment
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [TeXFragment](texfragment/#constructor)(string) | Inicializa uma nova instância da classe HtmlFragment. |
| [TeXFragment](texfragment/#constructor_1)(string, bool) | Inicializa uma nova instância da classe HtmlFragment. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | Obtém ou define um alinhamento horizontal do parágrafo |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Obtém ou define o hyperlink do fragmento (para gerador de pdf). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Obtém ou define um valor bool que indica se este parágrafo estará na próxima coluna. O padrão é falso. (para geração de pdf) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Obtém ou define se um parágrafo é inline. O padrão é falso. (para geração de pdf) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Obtém ou define um valor bool que força este parágrafo a ser gerado em uma nova página. O padrão é falso. (para geração de pdf) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Obtém ou define um valor bool que indica se o parágrafo atual permanece na mesma página junto com o próximo parágrafo. O padrão é falso. (para geração de pdf) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Obtém ou define uma margem externa para o parágrafo (para geração de pdf) |
| [TeXLoadOptionsOfInstance](../../aspose.pdf/texfragment/texloadoptionsofinstance/) { get; set; } | Obtém ou define TeXLoadOptions que serão usados para carregar (e renderizar) LaTeX nesta instância da classe. Por favor, use-o quando for necessário usar configurações específicas para a importação de LaTeX para esta ou aquela instância (por exemplo, quando esta ou aquela instância deve usar um BasePath específico para LaTeX importado ou deve usar um carregador específico de recursos externos). Se o parâmetro for padrão (nulo), então as opções padrão de carregamento de LaTeX serão usadas. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Obtém ou define um alinhamento vertical do parágrafo |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Obtém ou define um valor int que indica a ordem Z do gráfico. Um gráfico com um ZIndex maior será colocado sobre o gráfico com um ZIndex menor. ZIndex pode ser negativo. Gráficos com ZIndex negativo serão colocados atrás do texto na página. |

## Métodos

| Nome | Descrição |
| --- | --- |
| override [Clone](../../aspose.pdf/texfragment/clone/)() | Clona o fragmento. |

### Veja Também

* classe [FormattedFragment](../formattedfragment/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)