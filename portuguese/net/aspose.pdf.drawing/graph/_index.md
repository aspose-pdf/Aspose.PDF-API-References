---
title: Class Graph
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Drawing.Graph. Representa um parágrafo gerador de gráficos.
type: docs
weight: 3940
url: /pt/net/aspose.pdf.drawing/graph/
---
## Classe Gráfico

Representa um parágrafo gerador de gráficos.

```csharp
public sealed class Graph : BaseParagraph
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [Graph](graph/#constructor)(double, double) | Inicializa uma nova instância da classe `Graph`. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [Border](../../aspose.pdf.drawing/graph/border/) { get; set; } | Obtém ou define a borda. |
| [GraphInfo](../../aspose.pdf.drawing/graph/graphinfo/) { get; set; } | Obtém ou define um objeto [`GraphInfo`](./graphinfo/) que indica as informações do gráfico, como cor, largura da linha, etc. |
| [Height](../../aspose.pdf.drawing/graph/height/) { get; set; } | Obtém ou define um valor float que indica a altura do gráfico. A unidade é ponto. |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | Obtém ou define um alinhamento horizontal do parágrafo. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Obtém ou define o hyperlink do fragmento (para gerador de pdf). |
| [IsChangePosition](../../aspose.pdf.drawing/graph/ischangeposition/) { get; set; } | Obtém ou define a mudança da posição atual após processar o parágrafo. (padrão verdadeiro) |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Obtém ou define um valor bool que indica se este parágrafo estará na próxima coluna. O padrão é falso. (para geração de pdf) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Obtém ou define se um parágrafo é inline. O padrão é falso. (para geração de pdf) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Obtém ou define um valor bool que força este parágrafo a ser gerado em uma nova página. O padrão é falso. (para geração de pdf) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Obtém ou define um valor bool que indica se o parágrafo atual permanece na mesma página junto com o próximo parágrafo. O padrão é falso. (para geração de pdf) |
| [Left](../../aspose.pdf.drawing/graph/left/) { get; set; } | Obtém ou define a coordenada esquerda da tabela. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Obtém ou define uma margem externa para o parágrafo (para geração de pdf) |
| [Shapes](../../aspose.pdf.drawing/graph/shapes/) { get; set; } | Obtém ou define uma coleção [`Shapes`](./shapes/) que indica todas as formas no gráfico. |
| [Title](../../aspose.pdf.drawing/graph/title/) { get; set; } | Obtém ou define um valor string que indica o título do gráfico. |
| [Top](../../aspose.pdf.drawing/graph/top/) { get; set; } | Obtém ou define a coordenada superior da tabela. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Obtém ou define um alinhamento vertical do parágrafo. |
| [Width](../../aspose.pdf.drawing/graph/width/) { get; set; } | Obtém ou define um valor float que indica a largura do gráfico. A unidade é ponto. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Obtém ou define um valor int que indica a ordem Z do gráfico. Um gráfico com um ZIndex maior será colocado sobre o gráfico com um ZIndex menor. O ZIndex pode ser negativo. Gráficos com ZIndex negativo serão colocados atrás do texto na página. |

## Métodos

| Nome | Descrição |
| --- | --- |
| override [Clone](../../aspose.pdf.drawing/graph/clone/)() | Clona o gráfico. |

### Veja Também

* classe [BaseParagraph](../../aspose.pdf/baseparagraph/)
* namespace [Aspose.Pdf.Drawing](../../aspose.pdf.drawing/)
* assembly [Aspose.PDF](../../)