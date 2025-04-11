---
title: Class TextFragment
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Text.TextFragment. Representa fragmento de texto Pdf
type: docs
weight: 10940
url: /pt/net/aspose.pdf.text/textfragment/
---
## Classe TextFragment

Representa fragmento de texto Pdf.

```csharp
public class TextFragment : BaseParagraph
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [TextFragment](textfragment/#constructor)() | Inicializa uma nova instância do objeto `TextFragment`. |
| [TextFragment](textfragment/#constructor_2)(string) | Cria um objeto `TextFragment` com um único objeto [`TextSegment`](../textsegment/) dentro. Especifica a string de texto dentro do segmento. |
| [TextFragment](textfragment/#constructor_1)(TabStops) | Inicializa uma nova instância do objeto `TextFragment` com posições de [`TabStops`](../tabstops/) predefinidas. |
| [TextFragment](textfragment/#constructor_3)(string, TabStops) | Cria um objeto `TextFragment` com um único objeto [`TextSegment`](../textsegment/) dentro e posições de [`TabStops`](../tabstops/) predefinidas. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [BaselinePosition](../../aspose.pdf.text/textfragment/baselineposition/) { get; set; } | Obtém a posição do texto para o texto, representado pelo objeto `TextFragment`. O YIndent da estrutura Position representa a coordenada da linha de base do fragmento de texto. |
| [EndNote](../../aspose.pdf.text/textfragment/endnote/) { get; set; } | Obtém ou define a nota de rodapé do parágrafo. (apenas para geração de pdf) |
| [FootNote](../../aspose.pdf.text/textfragment/footnote/) { get; set; } | Obtém ou define a nota de rodapé do parágrafo. (apenas para geração de pdf) |
| [Form](../../aspose.pdf.text/textfragment/form/) { get; } | Obtém o objeto de formulário que contém o TextFragment |
| override [HorizontalAlignment](../../aspose.pdf.text/textfragment/horizontalalignment/) { get; set; } | Obtém ou define um alinhamento horizontal do fragmento de texto. |
| override [Hyperlink](../../aspose.pdf.text/textfragment/hyperlink/) { set; } | Define o hyperlink do fragmento |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Obtém ou define um valor bool que indica se este parágrafo estará na próxima coluna. O padrão é falso. (para geração de pdf) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Obtém ou define se um parágrafo é inline. O padrão é falso. (para geração de pdf) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Obtém ou define um valor bool que força este parágrafo a ser gerado em uma nova página. O padrão é falso. (para geração de pdf) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Obtém ou define um valor bool que indica se o parágrafo atual permanece na mesma página junto com o próximo parágrafo. O padrão é falso. (para geração de pdf) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Obtém ou define uma margem externa para o parágrafo (para geração de pdf) |
| [Page](../../aspose.pdf.text/textfragment/page/) { get; } | Obtém a página que contém o TextFragment |
| [Position](../../aspose.pdf.text/textfragment/position/) { get; set; } | Obtém ou define a posição do texto para o texto, representado pelo objeto `TextFragment`. |
| [Rectangle](../../aspose.pdf.text/textfragment/rectangle/) { get; } | Obtém o retângulo do TextFragment |
| [ReplaceOptions](../../aspose.pdf.text/textfragment/replaceoptions/) { get; } | Obtém opções de substituição de texto. As opções definem o comportamento quando o texto do fragmento é substituído por um texto mais curto/longo. |
| [Segments](../../aspose.pdf.text/textfragment/segments/) { get; set; } | Obtém os segmentos de texto para o atual `TextFragment`. |
| [Text](../../aspose.pdf.text/textfragment/text/) { get; set; } | Obtém ou define o objeto de texto String que o objeto `TextFragment` representa. |
| [TextEditOptions](../../aspose.pdf.text/textfragment/texteditoptions/) { get; set; } | Obtém ou define opções de edição de texto. As opções definem um comportamento especial quando o símbolo solicitado não pode ser escrito com a fonte. |
| [TextState](../../aspose.pdf.text/textfragment/textstate/) { get; } | Obtém ou define o estado do texto para o texto que o objeto `TextFragment` representa. |
| override [VerticalAlignment](../../aspose.pdf.text/textfragment/verticalalignment/) { get; set; } | Obtém ou define um alinhamento vertical do fragmento de texto. |
| [WrapLinesCount](../../aspose.pdf.text/textfragment/wraplinescount/) { get; set; } | Obtém ou define a contagem de linhas de quebra para este parágrafo (apenas para geração de pdf) |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Obtém ou define um valor int que indica a ordem Z do gráfico. Um gráfico com um ZIndex maior será colocado sobre o gráfico com um ZIndex menor. O ZIndex pode ser negativo. Gráficos com ZIndex negativo serão colocados atrás do texto na página. |

## Métodos

| Nome | Descrição |
| --- | --- |
| override [Clone](../../aspose.pdf.text/textfragment/clone/)() | Clona o fragmento. |
| virtual [CloneWithSegments](../../aspose.pdf.text/textfragment/clonewithsegments/)() | Clona o fragmento com todos os segmentos. |
| [IsolateTextSegments](../../aspose.pdf.text/textfragment/isolatetextsegments/)(int, int) | Obtém os [`TextSegment`](../textsegment/)(s) representando a parte especificada do texto `TextFragment`. |

## Observações

Em poucas palavras, o objeto `TextFragment` contém uma lista de objetos [`TextSegment`](../textsegment/). Em detalhes: O texto do documento pdf em Pdf é representado por dois objetos básicos: `TextFragment` e [`TextSegment`](../textsegment/). As diferenças entre eles são principalmente dependentes do contexto. Vamos considerar o seguinte cenário. O usuário busca o texto "hello world" para operar com ele, alterar suas propriedades, visualizar etc.

```csharp
Document doc = new Document(docFile);
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
doc.Pages[1].Accept(absorber);
```

A representação física do texto pdf é muito complexa. O texto "hello world" pode consistir em vários segmentos de texto fisicamente independentes. O modelo de texto Aspose.Pdf basicamente estabelece que o objeto `TextFragment` fornece um único conjunto de operações lógicas sobre o conjunto físico de objetos [`TextSegment`](../textsegment/) que representam a consulta do usuário. No cenário de busca de texto, `TextFragment` é a representação lógica do texto "hello world", e a coleção de objetos [`TextSegment`](../textsegment/) representa todos os segmentos físicos que constroem o objeto de texto "hello world". Assim, `TextFragment` está próximo da representação lógica do texto. E [`TextSegment`](../textsegment/) está próximo da representação física do texto. Obviamente, cada objeto [`TextSegment`](../textsegment/) pode ter sua própria fonte, coloração, propriedades de posicionamento. `TextFragment` fornece uma maneira simples de alterar o texto com suas propriedades: definir fonte, definir tamanho da fonte, definir cor da fonte etc. Enquanto isso, os objetos [`TextSegment`](../textsegment/) são acessíveis e os usuários podem operar com os objetos [`TextSegment`](../textsegment/) de forma independente. Observe que alterar as propriedades do TextFragment pode alterar a coleção interna [`Segments`](./segments/) porque o TextFragment é um objeto agregado e pode reorganizar segmentos internos ou mesclá-los em um único segmento. Se sua exigência é deixar a coleção [`Segments`](./segments/) inalterada, por favor, altere os segmentos internos individualmente.

## Exemplos

O exemplo demonstra como encontrar texto na primeira página do documento PDF e substituir o texto e sua fonte.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Find font that will be used to change document text font
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change text and font of the first text occurrence
absorber.TextFragments[1].Text = "hi world";
absorber.TextFragments[1].TextState.Font = font;

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### Veja Também

* classe [BaseParagraph](../../aspose.pdf/baseparagraph/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)