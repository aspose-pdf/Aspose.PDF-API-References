---
title: Class Heading
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Heading. Representa cabeçalho
type: docs
weight: 5470
url: /pt/net/aspose.pdf/heading/
---
## Classe Heading

Representa cabeçalho.

```csharp
public sealed class Heading : TextFragment
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [Heading](heading/)(int) | Inicializa uma nova instância da classe Cell. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [BaselinePosition](../../aspose.pdf.text/textfragment/baselineposition/) { get; set; } | Obtém a posição do texto para o texto, representado com o objeto [`TextFragment`](../../aspose.pdf.text/textfragment/). O YIndent da estrutura Position representa a coordenada da linha de base do fragmento de texto. |
| [DestinationPage](../../aspose.pdf/heading/destinationpage/) { get; set; } | Obtém a página de destino. |
| [EndNote](../../aspose.pdf.text/textfragment/endnote/) { get; set; } | Obtém ou define a nota de rodapé do parágrafo. (apenas para geração de pdf) |
| [FootNote](../../aspose.pdf.text/textfragment/footnote/) { get; set; } | Obtém ou define a nota de rodapé do parágrafo. (apenas para geração de pdf) |
| [Form](../../aspose.pdf.text/textfragment/form/) { get; } | Obtém o objeto de formulário que contém o TextFragment |
| override [HorizontalAlignment](../../aspose.pdf.text/textfragment/horizontalalignment/) { get; set; } | Obtém ou define um alinhamento horizontal do fragmento de texto. |
| override [Hyperlink](../../aspose.pdf.text/textfragment/hyperlink/) { set; } | Define o hyperlink do fragmento |
| [IsAutoSequence](../../aspose.pdf/heading/isautosequence/) { get; set; } | Obtém se o cabeçalho deve ser numerado automaticamente. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Obtém ou define um valor bool que indica se este parágrafo estará na próxima coluna. O padrão é falso. (para geração de pdf) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Obtém ou define se um parágrafo é inline. O padrão é falso. (para geração de pdf) |
| [IsInList](../../aspose.pdf/heading/isinlist/) { get; set; } | Obtém se o cabeçalho deve estar na lista de toc. |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Obtém ou define um valor bool que força este parágrafo a ser gerado em uma nova página. O padrão é falso. (para geração de pdf) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Obtém ou define um valor bool que indica se o parágrafo atual permanece na mesma página junto com o próximo parágrafo. O padrão é falso. (para geração de pdf) |
| [Level](../../aspose.pdf/heading/level/) { get; set; } | Obtém o nível. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Obtém ou define uma margem externa para o parágrafo (para geração de pdf) |
| [Page](../../aspose.pdf.text/textfragment/page/) { get; } | Obtém a página que contém o TextFragment |
| [Position](../../aspose.pdf.text/textfragment/position/) { get; set; } | Obtém ou define a posição do texto para o texto, representado com o objeto [`TextFragment`](../../aspose.pdf.text/textfragment/). |
| [Rectangle](../../aspose.pdf.text/textfragment/rectangle/) { get; } | Obtém o retângulo do TextFragment |
| [ReplaceOptions](../../aspose.pdf.text/textfragment/replaceoptions/) { get; } | Obtém opções de substituição de texto. As opções definem o comportamento quando o texto do fragmento é substituído por algo mais curto/longo. |
| [Segments](../../aspose.pdf.text/textfragment/segments/) { get; set; } | Obtém segmentos de texto para o atual [`TextFragment`](../../aspose.pdf.text/textfragment/). |
| [StartNumber](../../aspose.pdf/heading/startnumber/) { get; set; } | Obtém o número inicial do cabeçalho. |
| [Style](../../aspose.pdf/heading/style/) { get; set; } | Obtém ou define o estilo. |
| [Text](../../aspose.pdf.text/textfragment/text/) { get; set; } | Obtém ou define o objeto de texto String que o objeto [`TextFragment`](../../aspose.pdf.text/textfragment/) representa. |
| [TextEditOptions](../../aspose.pdf.text/textfragment/texteditoptions/) { get; set; } | Obtém ou define opções de edição de texto. As opções definem um comportamento especial quando o símbolo solicitado não pode ser escrito com a fonte. |
| [TextState](../../aspose.pdf.text/textfragment/textstate/) { get; } | Obtém ou define o estado do texto para o texto que o objeto [`TextFragment`](../../aspose.pdf.text/textfragment/) representa. |
| [TocPage](../../aspose.pdf/heading/tocpage/) { get; set; } | Obtém a página que contém este cabeçalho. |
| [Top](../../aspose.pdf/heading/top/) { get; set; } | Obtém o Y superior destes cabeçalhos. |
| [UserLabel](../../aspose.pdf/heading/userlabel/) { get; set; } | Obtém ou define o rótulo do usuário. |
| override [VerticalAlignment](../../aspose.pdf.text/textfragment/verticalalignment/) { get; set; } | Obtém ou define um alinhamento vertical do fragmento de texto. |
| [WrapLinesCount](../../aspose.pdf.text/textfragment/wraplinescount/) { get; set; } | Obtém ou define a contagem de linhas de quebra para este parágrafo (apenas para geração de pdf) |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Obtém ou define um valor int que indica a ordem Z do gráfico. Um gráfico com um ZIndex maior será colocado sobre o gráfico com um ZIndex menor. O ZIndex pode ser negativo. Gráficos com ZIndex negativo serão colocados atrás do texto na página. |

## Métodos

| Nome | Descrição |
| --- | --- |
| override [Clone](../../aspose.pdf/heading/clone/)() | Clona o cabeçalho. |
| override [CloneWithSegments](../../aspose.pdf/heading/clonewithsegments/)() | Clona o cabeçalho com todos os segmentos. |
| [IsolateTextSegments](../../aspose.pdf.text/textfragment/isolatetextsegments/)(int, int) | Obtém [`TextSegment`](../../aspose.pdf.text/textsegment/)(s) representando a parte especificada do texto do [`TextFragment`](../../aspose.pdf.text/textfragment/). |

### Veja Também

* classe [TextFragment](../../aspose.pdf.text/textfragment/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)